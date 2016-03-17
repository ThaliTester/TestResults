#### Test 62509094764c200_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
03-17 06:44:13.109  2333  2333 I Mms/ReservationManager: resetAfterConnected()
03-17 06:44:13.119  2930  2982 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458193453121
03-17 06:44:13.119  2930  2930 I KnoxUsageLogPro: premStatus:2
03-17 06:44:13.119  2930  2930 I KnoxUsageLogPro: isEulaShown : false
03-17 06:44:13.119  2930  2930 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
03-17 06:44:13.119  1464  1476 D TP/MmsSmsProvider: query,matched:7, calling pid = 2333
03-17 06:44:13.119  1464  1476 D TP/MmsSmsProvider: match 7:Elapsed time : 1.354 ms
--------- beginning of system
03-17 06:44:13.119  1017  1533 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
03-17 06:44:13.119  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.119  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.119  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.119  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.129  2333  2983 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 06:44:13.129  2333  2983 D Mms/TelephonyPermission: isDefault true
03-17 06:44:13.139  2986  2986 E Zygote  : MountEmulatedStorage()
03-17 06:44:13.139  2986  2986 E Zygote  : v2
03-17 06:44:13.139  2986  2986 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:13.139  2986  2986 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:13.139  2965  2965 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
03-17 06:44:13.139  2986  2986 I libpersona: KNOX_SDCARD checking this for 10085
03-17 06:44:13.139  2986  2986 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:13.139  1017  1533 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2986 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:13.139  1017  1533 I ActivityManager: Killing 1506:com.android.printspooler/u0a136 (adj 15): empty #31
03-17 06:44:13.149  2986  2986 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:13.149  1464  1701 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2333
03-17 06:44:13.149  2965  2965 V SmartcardService: main Received broadcast
03-17 06:44:13.149  2965  2965 V SmartcardService: Starting smartcard service after boot completed
03-17 06:44:13.149  2333  2333 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
03-17 06:44:13.149  1017  1348 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.149  1017  1348 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:13.149  1017  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
03-17 06:44:13.149  1017  1348 D ActivityManager: startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
03-17 06:44:13.149  1017  1348 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
03-17 06:44:13.159  1017  1488 I ActivityManager: Killing 2140:com.vlingo.midas/u0a31 (adj 15): empty #31
03-17 06:44:13.169  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.169  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:13.169  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-17 06:44:13.169  2986  2986 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.169  2986  2986 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.169  1017  1151 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.169  1017  1151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:13.169  1017  1151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-17 06:44:13.169  1017  1504 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
03-17 06:44:13.169  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
03-17 06:44:13.169  1017  1151 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
03-17 06:44:13.169  1017  1151 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
03-17 06:44:13.189  1464  1701 D TP/MmsSmsProvider: query,matched:200, calling pid = 2333
03-17 06:44:13.189  1464  1701 D TP/MmsSmsProvider: match 200:Elapsed time : 2.647 ms
03-17 06:44:13.199  1017  1348 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
03-17 06:44:13.199  2986  2986 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 06:44:13.199  2986  2986 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:44:13.199  2986  2986 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:13.199  2986  2986 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 06:44:13.199  2986  2986 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:13.199  2986  2986 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-17 06:44:13.199  1017  1501 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 06:44:13.199  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.199  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.199  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.199  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.199  1017  1501 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-17 06:44:13.209  1017  1501 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
03-17 06:44:13.209  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 06:44:13.219  3006  3006 E Zygote  : MountEmulatedStorage()
03-17 06:44:13.219  3006  3006 E Zygote  : v2
03-17 06:44:13.219  3006  3006 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:13.219  3006  3006 I libpersona: KNOX_SDCARD checking this for 10048
03-17 06:44:13.219  3006  3006 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:13.219  3006  3006 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:13.219  3006  3006 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:13.219  1017  1348 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3006 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 06:44:13.229  1017  1348 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
03-17 06:44:13.229  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.229  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.229  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.229  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.249  3019  3019 E Zygote  : MountEmulatedStorage()
03-17 06:44:13.249  3019  3019 E Zygote  : v2
03-17 06:44:13.249  3019  3019 I libpersona: KNOX_SDCARD checking this for 10157
03-17 06:44:13.249  3019  3019 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:13.249  3019  3019 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:13.249  3019  3019 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:13.249  1017  1348 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3019 uid=10157 gids={50157, 9997} abi=armeabi-v7a
03-17 06:44:13.259  3019  3019 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:13.269  1017  1017 I MotionRecognitionService: Plugged
03-17 06:44:13.269  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
03-17 06:44:13.269  3006  3006 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.269  3006  3006 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.279  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 06:44:13.279  1183  1183 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 06:44:13.279  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 06:44:13.279  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 06:44:13.279  1183  1183 D PowerUI : Cable  true --> true mBootCompleted : true
03-17 06:44:13.279  1183  1183 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-17 06:44:13.289  3019  3019 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.289  3019  3019 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.289  2627  2627 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 06:44:13.289  2627  2708 D HeadsetStateMachine: Disconnected process message: 10
03-17 06:44:13.289  2333  2333 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-17 06:44:13.289  2333  3005 D Mms/TelephonyPermission: isDefault true
03-17 06:44:13.289  2333  3005 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-17 06:44:13.289  2333  3005 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 188.33
03-17 06:44:13.299  2930  2982 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 35500
03-17 06:44:13.309  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 06:44:13.309  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 06:44:13.309  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 06:44:13.309  1017  1151 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-17 06:44:13.309  1017  1151 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
03-17 06:44:13.309  1017  1151 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.309  1017  1151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:13.309  1017  1151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 06:44:13.319  1464  1473 D TP/SmsProvider: query,matched:0, calling pid = 2333
03-17 06:44:13.329  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-17 06:44:13.329  1464  1473 D TP/SmsProvider: match 0:Elapsed time : 2.932 ms
03-17 06:44:13.329  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
03-17 06:44:13.329   295   295 E USB_UICC: Timeout! No signal received. Retry num = 29
03-17 06:44:13.329  1017  1041 W libprocessgroup: failed to open /acct/uid_10136/pid_1506/cgroup.procs: No such file or directory
03-17 06:44:13.329  1017  1041 W libprocessgroup: failed to open /acct/uid_10107/pid_1627/cgroup.procs: No such file or directory
03-17 06:44:13.329  3006  3006 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 06:44:13.329   312   312 I ServiceManager: Waiting for service AtCmdFwd...
03-17 06:44:13.329  3006  3006 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:13.329  3006  3006 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 06:44:13.329  1237  2929 E SQLiteLog: (283) recovered 292 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
03-17 06:44:13.339  1464  1476 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-17 06:44:13.339  1464  1476 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
03-17 06:44:13.339  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.339  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:13.339  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 06:44:13.349  1464  1476 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 06:44:13.349  1464  1476 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
03-17 06:44:13.349  1017  1501 D ActivityManager: startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
03-17 06:44:13.349  3019  3019 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:13.349  1464  1758 D TP/SmsProvider: query,matched:51, calling pid = 2333
03-17 06:44:13.359  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.359  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.359  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.359  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.369  2945  3040 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
03-17 06:44:13.369  3041  3041 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:13.369  3041  3041 E Zygote  : MountEmulatedStorage()
03-17 06:44:13.369  3041  3041 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:13.369  3041  3041 E Zygote  : v2
03-17 06:44:13.369  3041  3041 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:13.369  3041  3041 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:13.369  3041  3041 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:13.379  1464  1758 D TP/SmsProvider: match 51:Elapsed time : 20.428 ms
03-17 06:44:13.379  1017  1501 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3041 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:13.379  1017  1501 I ActivityManager: Killing 2193:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
03-17 06:44:13.389  1464  1476 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
03-17 06:44:13.399  1464  1476 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:13.399  1464  1476 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:13.399  1464  1476 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:13.399  1464  1476 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:13.399  1464  1476 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:13.399  1464  1476 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:13.399  2333  2983 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 06:44:13.399  3041  3041 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.399  3041  3041 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.409  1464  1476 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-17 06:44:13.409  1464  1476 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 06:44:13.419  1017  1533 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
03-17 06:44:13.419  1237  2929 D MediaScanner: Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 06:44:13.419  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.419  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.419  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.419  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.429  2333  3005 D Mms/Conversation: deleteTempConversation(),deleted=0
03-17 06:44:13.439  1017  1533 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=3057 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:13.439  3057  3057 E Zygote  : MountEmulatedStorage()
03-17 06:44:13.439  3057  3057 I libpersona: KNOX_SDCARD checking this for 10159
03-17 06:44:13.439  3057  3057 E Zygote  : v2
03-17 06:44:13.439  3057  3057 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:13.449  3057  3057 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:13.449  3057  3057 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:13.449  3057  3057 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
03-17 06:44:13.449  1017  1533 I ActivityManager: Killing 2254:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
03-17 06:44:13.459  1017  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-17 06:44:13.459  1017  1041 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
03-17 06:44:13.469  1017  1041 W libprocessgroup: failed to open /acct/uid_10031/pid_2140/cgroup.procs: No such file or directory
03-17 06:44:13.479  2945  3040 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
03-17 06:44:13.479  1577  2801 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 06:44:13.479  3029  3029 D AndroidRuntime: 
03-17 06:44:13.479  3029  3029 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 06:44:13.479  3029  3029 D AndroidRuntime: CheckJNI is OFF
03-17 06:44:13.479  3029  3029 D AndroidRuntime: readGMSProperty: start
03-17 06:44:13.479  3029  3029 D AndroidRuntime: readGMSProperty: already setted!!
03-17 06:44:13.479  3029  3029 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 06:44:13.479  3029  3029 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 06:44:13.479  3029  3029 D AndroidRuntime: readGMSProperty: end
03-17 06:44:13.479  3029  3029 D AndroidRuntime: addProductProperty: start
03-17 06:44:13.499  1017  1504 D SettingsProvider: name = block_emergency_message
03-17 06:44:13.499  1017  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:13.499  1017  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:13.499  1017  1504 D SettingsProvider: selectionArgs: false
03-17 06:44:13.499  1017  1504 D SettingsProvider: selectionArgs: 10048
03-17 06:44:13.499  1017  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:13.499  1017  1504 D SettingsProvider: ret = -1
03-17 06:44:13.499  1464  1701 D SmsProvider: Update uri=content://sms/outbox, match=8
03-17 06:44:13.499   329   329 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2945
03-17 06:44:13.499   329   329 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
03-17 06:44:13.499  1464  1701 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 06:44:13.499  2945  3040 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
03-17 06:44:13.499  2945  3040 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
03-17 06:44:13.499   329   329 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2945
03-17 06:44:13.499   329   329 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
03-17 06:44:13.499  1017  1532 W ActivityManager: getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
03-17 06:44:13.499  2333  3005 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-17 06:44:13.499  2333  3005 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-17 06:44:13.509  3057  3057 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.509  3057  3057 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.509  1017  1263 D SettingsProvider: name = next_alarm_formatted
03-17 06:44:13.509  1017  1263 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:13.509  1017  1263 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:13.509  1017  1263 D SettingsProvider: selectionArgs: false
03-17 06:44:13.509  1017  1263 D SettingsProvider: selectionArgs: 10085
03-17 06:44:13.509  1017  1263 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:13.509  1017  1263 D SettingsProvider: ret = -1
03-17 06:44:13.509  1577  1597 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 06:44:13.509  1577  1597 D BadgeProvider: sendNotify, [notify] : null
03-17 06:44:13.509  1577  1597 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 06:44:13.509  1577  1597 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 06:44:13.509  1577  1597 D BadgeProvider: update, [UpdateCount] : 1
03-17 06:44:13.509  2333  2983 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 06:44:13.519  1489  1489 D Launcher.Model: reloadBadges entered.
03-17 06:44:13.519  2333  3005 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
03-17 06:44:13.519  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 06:44:13.519  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:13.519  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:13.519  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:13.519  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:13.519  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:13.519  1017  1263 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
03-17 06:44:13.529  2333  2983 D Mms/MessagingNotification: remove alarm
03-17 06:44:13.549  1017  1532 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
03-17 06:44:13.549  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
03-17 06:44:13.549  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.549  1017  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:13.549  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
03-17 06:44:13.559  1464  1758 D TP/SmsProvider: query,matched:0, calling pid = 2333
03-17 06:44:13.559  1464  1758 D TP/SmsProvider: match 0:Elapsed time : 3.932 ms
03-17 06:44:13.569  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 06:44:13.569  1316  1316 I WifiCredService: onCreate
03-17 06:44:13.569  2333  3073 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 06:44:13.569  2333  2983 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 279.630468
03-17 06:44:13.579  1017  3038 D ActivityManager: bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: null
03-17 06:44:13.579  1017  3038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
03-17 06:44:13.579  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.579  1017  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:13.579  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
03-17 06:44:13.579  1464  1476 D TP/SmsProvider: query,matched:26, calling pid = 2333
03-17 06:44:13.579  1017  1041 W libprocessgroup: failed to open /acct/uid_10050/pid_2193/cgroup.procs: No such file or directory
03-17 06:44:13.579  1017  1041 W libprocessgroup: failed to open /acct/uid_10113/pid_2254/cgroup.procs: No such file or directory
03-17 06:44:13.599  3057  3057 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
03-17 06:44:13.609  1316  1316 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 06:44:13.609  1316  1316 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 06:44:13.609  1316  1316 D MY_TAG  : Action boot completed received
03-17 06:44:13.609  1464  1476 D TP/SmsProvider: match 26:Elapsed time : 24.877 ms
03-17 06:44:13.609  1237  2929 V MediaScanner: processDirectory :  /system/media
03-17 06:44:13.609  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
03-17 06:44:13.609  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.609  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.609  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.609  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.619  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-17 06:44:13.619  1017  1143 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 06:44:13.619  1017  1143 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 06:44:13.619  1017  1143 E WifiNative-wlan0: invaild command id : 215
03-17 06:44:13.619  3041  3041 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-17 06:44:13.629  3086  3086 E Zygote  : MountEmulatedStorage()
03-17 06:44:13.629  3086  3086 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:13.629  3086  3086 E Zygote  : v2
03-17 06:44:13.629  3086  3086 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:13.629  3086  3086 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:13.639  3029  3029 E AffinityControl: AffinityControl: registerfunction enter
03-17 06:44:13.639  3086  3086 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:13.639  3086  3086 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:13.639  1017  1488 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3086 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:13.639  1017  1488 I ActivityManager: Killing 1650:com.google.android.partnersetup/u0a15 (adj 15): empty #31
03-17 06:44:13.649  3041  3041 D DSM     : [Lines:107] Normal booted
03-17 06:44:13.649  3041  3041 D DSM     : [Lines:114] Boot completed
03-17 06:44:13.659  3086  3086 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.659  3029  3029 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 06:44:13.659  3086  3086 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.669  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
03-17 06:44:13.669  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.669  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.669  1017  1151 E PersonaManagerService: inState():  stateMachine is null !!
03-17 06:44:13.669  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.669  1017  1151 I PersonaManagerService: PersonaId don't exist
03-17 06:44:13.669  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.669  1017  1151 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 06:44:13.689  1237  2929 V MediaScanner:  prescan time: 545ms (DB items: 141)
03-17 06:44:13.689  1237  2929 V MediaScanner:     scan time: 91ms (Caching mode: true), (makeEntry time: 44ms ~48%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 06:44:13.689  1237  2929 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 06:44:13.689  1237  2929 V MediaScanner:    total time: 636ms
03-17 06:44:13.689  1237  2929 V MediaScanner: checked files: 133  directories : 6  (I: 0, U: 0)
03-17 06:44:13.699  1237  2929 D MediaScanner: checkDefaultSounds
03-17 06:44:13.699  1237  2929 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
03-17 06:44:13.699  1017  1030 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3103 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:13.709  3103  3103 E Zygote  : MountEmulatedStorage()
03-17 06:44:13.709  3103  3103 E Zygote  : v2
03-17 06:44:13.709  3103  3103 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:13.709  3103  3103 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:13.709  1017  1151 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 06:44:13.709  3103  3103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:13.709  1316  1316 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
03-17 06:44:13.709  1316  1316 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
03-17 06:44:13.709  1316  1316 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
03-17 06:44:13.709  3103  3103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:13.709  3103  3103 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:13.729  1017  1151 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 06:44:13.729  1017  1151 W ActivityManager: mDVFSHelper.acquire()
03-17 06:44:13.729  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-17 06:44:13.729  1316  3109 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-17 06:44:13.729  1017  1151 D FocusedStackFrame: Set to : 0
03-17 06:44:13.739  3103  3103 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.739  3103  3103 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.739  1489  1489 D Launcher.HomeView: onPause
03-17 06:44:13.739  1017  1532 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-17 06:44:13.739  1489  1489 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 06:44:13.749  1017  1151 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 06:44:13.749  1017  1151 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 06:44:13.749  1017  1151 D InputDispatcher: Focused application set to: xxxx
03-17 06:44:13.749  1017  1151 D InputDispatcher: Focus left window: 1489
03-17 06:44:13.749  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 06:44:13.749  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 06:44:13.769  1316  1316 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-17 06:44:13.769  1316  1316 I NearbySettings: MountReceiver.onReceive - Internal Path
03-17 06:44:13.769  1237  2929 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-17 06:44:13.769  3029  3029 D AndroidRuntime: Shutting down VM
03-17 06:44:13.769  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 06:44:13.779  1237  2929 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
03-17 06:44:13.779  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 06:44:13.779  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 06:44:13.789  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 06:44:13.789  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 06:44:13.789  2333  3005 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 06:44:13.789  2333  3005 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 06:44:13.789  2333  3005 D Mms/TelephonyPermission: isDefault true
03-17 06:44:13.789   257   257 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 06:44:13.799  1237  2929 D MediaScanner: OK. notification_sound is already exist in setting DB.
03-17 06:44:13.799  1237  2929 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
03-17 06:44:13.799  3103  3103 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 06:44:13.799  1237  2929 D MediaScanner: OK. ringtone is already exist in setting DB.
03-17 06:44:13.809  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.809  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.809  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.809  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.839  3123  3123 E Zygote  : MountEmulatedStorage()
03-17 06:44:13.839  2986  2986 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 288.295ms
03-17 06:44:13.839  3123  3123 E Zygote  : v2
03-17 06:44:13.839  3123  3123 I libpersona: KNOX_SDCARD checking this for 10155
03-17 06:44:13.839  3123  3123 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:13.839  3123  3123 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:13.849  3123  3123 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:13.849  3123  3123 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 06:44:13.849  1017  1151 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3123 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 06:44:13.859  3103  3103 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 06:44:13.859  1017  3038 D SettingsProvider: name = personal_mode_enabled
03-17 06:44:13.869  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-17 06:44:13.869  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
03-17 06:44:13.869  3103  3103 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
03-17 06:44:13.879  1017  1533 I art     : Explicit concurrent mark sweep GC freed 144181(8MB) AllocSpace objects, 6(1846KB) LOS objects, 33% free, 26MB/40MB, paused 2.966ms total 226.276ms
03-17 06:44:13.879  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
03-17 06:44:13.879  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.879  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.879  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.879  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.909  3135  3135 E Zygote  : MountEmulatedStorage()
03-17 06:44:13.909  3135  3135 E Zygote  : v2
03-17 06:44:13.909  3135  3135 I libpersona: KNOX_SDCARD checking this for 10160
03-17 06:44:13.909  3135  3135 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:13.909  3135  3135 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:13.909  3135  3135 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:13.909  3135  3135 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:13.909  1017  1030 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3135 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-17 06:44:13.919  1017  1030 I ActivityManager: Killing 2320:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-17 06:44:13.919  3123  3123 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.919  3123  3123 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.939  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-17 06:44:13.939   302   302 I art     : Explicit concurrent mark sweep GC freed 8731(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 27.699ms
03-17 06:44:13.949  3135  3135 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.949  1489  1489 V ActivityThread: updateVisibility : ActivityRecord{1b3e12ac token=android.os.BinderProxy@264605e1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 06:44:13.949  3135  3135 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.949  1464  1701 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2333
03-17 06:44:13.949  1017  1151 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 06:44:13.949  1017  1151 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 06:44:13.949  1017  1151 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 06:44:13.959  1489  1489 D Launcher.HomeView: onStop
03-17 06:44:13.959  2590  2590 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2590) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 06:44:13.959  2590  2590 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2590) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-17 06:44:13.959  2590  2590 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2590) ACTION_MEDIA_SCANNER_FINISHED = Ignored
03-17 06:44:13.959   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 970us total 23.334ms
03-17 06:44:13.969  1489  1489 V ActivityThread: updateVisibility : ActivityRecord{1b3e12ac token=android.os.BinderProxy@264605e1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 06:44:13.969  1489  1489 D Launcher: onTrimMemory. Level: 20
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-17 06:44:13.969  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-17 06:44:13.979   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 18.111ms
03-17 06:44:13.989  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 06:44:13.989  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-17 06:44:13.989  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 06:44:13.989  3029  3029 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 06:44:13.999  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-17 06:44:13.999  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,03-17 06:44:13.999  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-17 06:44:13.999  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-17 06:44:13.999  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-17 06:44:13.999  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,03-17 06:44:13.999  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,03-17 06:44:14.019  1237  2929 D MediaScannerService: !@done scanning volume internal
,03-17 06:44:14.019  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-17 06:44:14.019  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 06:44:14.019  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-17 06:44:14.019  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,03-17 06:44:14.019  1017  1151 D PersonaManager: isKioskContainerExistOnDevice
,03-17 06:44:14.019  3103  3103 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,03-17 06:44:14.019  1464  1464 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 06:44:14.029  1464  1464 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 06:44:14.029  1464  1464 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 06:44:14.029  1464  1464 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 06:44:14.029  1464  1464 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:14.029  1464  1464 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 06:44:14.029  3103  3103 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,03-17 06:44:14.069  1017  1533 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,03-17 06:44:14.069  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:14.069  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.069  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.069  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:14.079  3135  3135 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 06:44:14.079  3156  3156 E Zygote  : MountEmulatedStorage()
,03-17 06:44:14.079  3156  3156 E Zygote  : v2
03-17 06:44:14.079  3156  3156 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:14.079  3156  3156 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:14.079  1017  1533 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3156 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:14.089  3156  3156 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:14.089  3156  3156 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:14.089  1017  1533 I ActivityManager: Killing 2356:com.sec.android.omc/1000 (adj 15): empty #31,
,03-17 06:44:14.099  3156  3156 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:14.099  1237  2929 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,03-17 06:44:14.109  1316  1316 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 06:44:14.109  1316  1316 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
,03-17 06:44:14.119  1017  1017 D SensorService: [SO] activate (ident=0xb85d63a0, enabled=0)
03-17 06:44:14.119  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 06:44:14.119  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 06:44:14.119  1017  1151 I ActivityManager: Killing 2386:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,03-17 06:44:14.129  1017  1017 D SensorManager: unregisterListener ::   
03-17 06:44:14.129  1017  1017 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-17 06:44:14.129  1017  1017 D SensorService: [SO] changed settle time [1]
03-17 06:44:14.129  1017  1017 D SensorService: [SO] setDelay [66000000]
03-17 06:44:14.129  1017  1017 D SensorService: [SO] activate (ident=0xb8755020, enabled=1)
03-17 06:44:14.129  1017  1017 D SensorService: [SO] AR_init,
03-17 06:44:14.129  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 06:44:14.139  1017  1017 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 06:44:14.149  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:14.149  1316  1316 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-17 06:44:14.169  1017  1041 W libprocessgroup: failed to open /acct/uid_10015/pid_1650/cgroup.procs: No such file or directory,
03-17 06:44:14.169  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2320/cgroup.procs: No such file or directory
,03-17 06:44:14.179  3156  3156 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:14.179  3156  3156 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:14.189  1237  2929 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-17 06:44:14.189  1237  2929 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed,
,03-17 06:44:14.199  1237  2929 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,03-17 06:44:14.199  1237  2929 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 06:44:14.199  1237  2929 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 06:44:14.199  1237  2929 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-17 06:44:14.199  1237  2929 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,03-17 06:44:14.199  3123  3123 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 06:44:14.209  1237  2929 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-17 06:44:14.209  1017  1039 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 06:44:14.209  1464  1476 D TP/MmsSmsProvider: query,matched:200, calling pid = 2333
,03-17 06:44:14.219  1464  1476 D TP/MmsSmsProvider: match 200:Elapsed time : 7.108 ms
,03-17 06:44:14.219  3123  3123 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6607-6609)
03-17 06:44:14.219  3123  3123 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 06:44:14.239  1237  2929 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-17 06:44:14.249  1464  1473 D TP/SmsProvider: query,matched:0, calling pid = 2333
,03-17 06:44:14.249  1464  1473 D TP/SmsProvider: match 0:Elapsed time : 1.421 ms
03-17 06:44:14.249  1316  1316 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-17 06:44:14.259  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2356/cgroup.procs: No such file or directory
03-17 06:44:14.259  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2386/cgroup.procs: No such file or directory
,03-17 06:44:14.269  1316  1316 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-17 06:44:14.269  1316  1316 I SettingSearch/SearchIntentReceiver: search setting db init!!
03-17 06:44:14.269  1464  1758 D TP/SmsProvider: query,matched:51, calling pid = 2333
,03-17 06:44:14.269  1464  1758 D TP/SmsProvider: match 51:Elapsed time : 0.855 ms
,03-17 06:44:14.269  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-17 06:44:14.269  1316  3177 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
03-17 06:44:14.279  1017  1039 D SensorService: [SO] 0.115 0.421 10.113
03-17 06:44:14.279  1017  1039 D SensorService: [SO] [100 -> 255]
03-17 06:44:14.279  2333  3005 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 06:44:14.289  1577  2801 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 06:44:14.289  1017  1097 V AlarmManager: waitForAlarm result :8
03-17 06:44:14.289  1017  1097 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:14.299  1017  1501 D ActivityManager: startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,03-17 06:44:14.299  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:14.299  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.299  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.299  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:14.309  3178  3178 E Zygote  : MountEmulatedStorage()
03-17 06:44:14.309  3178  3178 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:14.309  3178  3178 E Zygote  : v2
03-17 06:44:14.309  3178  3178 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:14.319  3178  3178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:14.319  1017  1501 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3178 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-17 06:44:14.319  1489  1489 D Launcher.Model: reloadBadges entered.
03-17 06:44:14.319  1577  1597 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 06:44:14.319  1577  1597 D BadgeProvider: sendNotify, [notify] : null
03-17 06:44:14.319  1577  1597 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 06:44:14.319  1577  1597 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 06:44:14.319  1577  1597 D BadgeProvider: update, [UpdateCount] : 1
03-17 06:44:14.319  3178  3178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:14.319  3178  3178 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:14.329  2333  3005 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 06:44:14.329   295   295 E USB_UICC: Timeout! No signal received. Retry num = 30
,03-17 06:44:14.339  2333  3005 D Mms/MessagingNotification: remove alarm
,03-17 06:44:14.349  3123  3123 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {24694b6d}
03-17 06:44:14.349  3123  3123 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 06:44:14.349  3123  3123 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 06:44:14.359   312   312 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 06:44:14.359  1237  2929 V MediaScanner: processDirectory :  /storage/emulated/0
,03-17 06:44:14.379  1237  2929 D MediaScanner: Skipping:
03-17 06:44:14.379  1237  2929 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
03-17 06:44:14.379  1237  2929 D MediaScanner: Skipping:
03-17 06:44:14.379  1237  2929 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,03-17 06:44:14.389  3123  3123 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-17 06:44:14.389  3123  3123 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 06:44:14.389  3123  3123 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 06:44:14.409  1237  2929 V MediaScanner: processDirectory :  /storage/extSdCard
,03-17 06:44:14.409  1237  2929 W MediaScanner: Error opening directory, reason : Permission denied.
03-17 06:44:14.409  1237  2929 W MediaScanner: 7klwibgf7fxlKdCbid7
,03-17 06:44:14.419  3135  3135 D [0]UMC:UMCContentProvider: @onCreate
03-17 06:44:14.419  3178  3178 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:14.419  3178  3178 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:14.429  2333  3185 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 06:44:14.429  1237  2929 V MediaScanner:  prescan time: 153ms (DB items: 27)
03-17 06:44:14.429  1237  2929 V MediaScanner:     scan time: 54ms (Caching mode: true), (makeEntry time: 48ms ~88%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 06:44:14.429  1237  2929 V MediaScanner: postscan time: 21ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 06:44:14.429  1237  2929 V MediaScanner:    total time: 228ms
03-17 06:44:14.429  1237  2929 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
,03-17 06:44:14.449   295   295 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 06:44:14.449   295   295 E USB_UICC: usb_uicc_init_qmi failed ! 
03-17 06:44:14.449   295   295 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 06:44:14.449   295   295 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-17 06:44:14.449  3123  3123 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
03-17 06:44:14.449  1237  2929 D MediaScannerService: !@done scanning volume external
03-17 06:44:14.449  3123  3123 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50556 len=3379
03-17 06:44:14.449  3123  3123 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:7638088 len:1165478
03-17 06:44:14.449  2763  2925 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:44:14.449  3123  3123 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 06:44:14.449  3123  3123 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 06:44:14.449  3123  3123 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 06:44:14.449  3123  3123 I Adreno-EGL: Local Branch: 
03-17 06:44:14.449  3123  3123 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 06:44:14.449  3123  3123 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 06:44:14.449  3123  3123 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 06:44:14.459  1464  1473 D TP/SmsProvider: query,matched:0, calling pid = 2333
,03-17 06:44:14.479  2590  2590 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2590) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 06:44:14.479  2590  2590 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2590) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-17 06:44:14.479  2590  2590 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2590) ...
03-17 06:44:14.479  2590  2590 D FactoryTestApp: [Support$Values.getString](2590) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 06:44:14.479  2590  2590 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2590) mConnectionMode = gsm
,03-17 06:44:14.479   329   329 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0,
,03-17 06:44:14.489  2590  2590 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2590) Create IPCWriterToSecPhoneService
03-17 06:44:14.489  2590  2590 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2590)  
,03-17 06:44:14.489  2590  2590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-17 06:44:14.489  1464  1473 D TP/SmsProvider: match 0:Elapsed time : 23.769 ms
,03-17 06:44:14.489  1017  1151 D ActivityManager: bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
03-17 06:44:14.489  1017  1151 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-17 06:44:14.499  1017  1151 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:14.499  1017  3038 D ActivityManager: getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
03-17 06:44:14.499  1017  1151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:14.499  1017  1151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-17 06:44:14.499   257   440 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
03-17 06:44:14.499   257   435 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-17 06:44:14.499  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:14.509  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.509  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.509  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:14.509  3178  3178 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:14.519  3135  3135 D [0]UMC:Core: onCreate(): 
,03-17 06:44:14.519  3135  3135 D [0]UMC:Core: @isManagedProfileUser
,03-17 06:44:14.519  3135  3135 D [0]UMC:Core: userId: 0
,03-17 06:44:14.529  3216  3216 E Zygote  : MountEmulatedStorage()
03-17 06:44:14.529  1017  3038 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3216 uid=10150 gids={50150, 9997} abi=armeabi-v7a,
03-17 06:44:14.529  3216  3216 E Zygote  : v2
03-17 06:44:14.529  3216  3216 I libpersona: KNOX_SDCARD checking this for 10150
03-17 06:44:14.529  3216  3216 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:14.529  3135  3135 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
03-17 06:44:14.529  3135  3135 D [0]UMC:Core: userInfo.isManagedProfile() : false
,03-17 06:44:14.529  3216  3216 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:14.539  3216  3216 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:14.539  3216  3216 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,03-17 06:44:14.549  2590  2590 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2590) connected done
03-17 06:44:14.549  2590  2590 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2590) Send Response Message to SecPhone
03-17 06:44:14.549  2590  2590 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2590) Response ��
,03-17 06:44:14.559  2945  3040 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,03-17 06:44:14.559  2945  3040 I SecureStorage: [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,03-17 06:44:14.559  2333  3005 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 990.22901
,03-17 06:44:14.579  3156  3156 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 06:44:14.579   308  1074 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 06:44:14.579  2590  2590 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2590) Send BOOTING COMPLETED done
,03-17 06:44:14.589  3216  3216 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:14.589  3216  3216 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:14.599  3135  3135 D [0]UMC:DeviceInfo: USA==US==
,03-17 06:44:14.649  2627  2711 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-17 06:44:14.659  2627  2711 D BluetoothMediaBrowser: no now playing list
03-17 06:44:14.659  2627  2711 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-17 06:44:14.679   308  1074 D AT_Distributor: SetAtdStatus(), 1_1_0,
03-17 06:44:14.679   308  1074 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 06:44:14.749  3156  3156 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 06:44:14.759  3156  3156 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 06:44:14.789  3123  3211 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-17 06:44:14.819  3135  3135 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,03-17 06:44:14.829  3156  3156 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-17 06:44:14.829  3156  3156 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,03-17 06:44:14.829  3156  3156 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,03-17 06:44:14.829  3156  3156 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 06:44:14.839   274   977 D EnterpriseController: uids 10120
03-17 06:44:14.839   274   977 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 06:44:14.839   274   977 D Netd    : getNetworkForDns: using netid 502 for uid 10120
,03-17 06:44:14.849  3135  3135 D [0]UMC:AdminManager: init - start
,03-17 06:44:14.869  3123  3123 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:44:14.869  3135  3135 D [0]UMC:AdminManager: loadAdmins
,03-17 06:44:14.889  3135  3135 D [0]UMC:AdminManager: init - end
,03-17 06:44:14.889  3135  3135 D GSLBManager: migrateStoredUrlFromOldPref
,03-17 06:44:14.899  3135  3135 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,03-17 06:44:14.899  3135  3135 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 06:44:14.899  3135  3135 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 06:44:14.899  3123  3123 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 06:44:14.909  3135  3135 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,03-17 06:44:14.909  3135  3135 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 06:44:14.909  3135  3135 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 06:44:14.909  3178  3178 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 06:44:14.909  3123  3123 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 06:44:14.909  3123  3123 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 06:44:14.919  1017  1488 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 06:44:14.919  3123  3123 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 06:44:14.919  3135  3135 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-17 06:44:14.919  3135  3135 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 06:44:14.919  3123  3123 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 06:44:14.919  3123  3123 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:44:14.929  3135  3135 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 06:44:14.929  1017  1151 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,03-17 06:44:14.929  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.929  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.929  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.929  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:14.949  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 06:44:14.949  3251  3251 E Zygote  : MountEmulatedStorage()
03-17 06:44:14.949  3251  3251 E Zygote  : v2
,03-17 06:44:14.949  3251  3251 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:14.949  3251  3251 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:14.949  3251  3251 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:14.949  1017  1151 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3251 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:14.949  3251  3251 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:14.949  3251  3251 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:14.949  1017  1523 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
03-17 06:44:14.959  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
03-17 06:44:14.959  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-17 06:44:14.959  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.959  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.959  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.959  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:14.969  3268  3268 E Zygote  : MountEmulatedStorage(),
03-17 06:44:14.969  3268  3268 E Zygote  : v2
03-17 06:44:14.969  3268  3268 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 06:44:14.969  3268  3268 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:14.969  3268  3268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:14.979  3268  3268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:14.979  3268  3268 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:14.979  1017  1523 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3268 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:14.979  1017  1029 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
03-17 06:44:14.979  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 06:44:14.989  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:14.989  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:14.989  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 06:44:14.989  3135  3135 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,03-17 06:44:14.999  3135  3135 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-17 06:44:14.999  3135  3135 D [0]UMC:CoreReceiver:  check PreETag 
,03-17 06:44:14.999  3251  3251 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:14.999  3251  3251 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.009  3123  3281 D OpenGLRenderer: Render dirty regions requested: true
,03-17 06:44:15.019  3268  3268 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:15.019  3268  3268 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:15.019  1017  3038 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 06:44:15.019  1017  3038 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 06:44:15.019  1017  3038 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 06:44:15.019  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 06:44:15.019  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 06:44:15.019  1017  1263 I ActivityManager: Killing 2401:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-17 06:44:15.029  3123  3123 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 06:44:15.029  3123  3123 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 06:44:15.039  3251  3251 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 06:44:15.039   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 06:44:15.049  3135  3135 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-17 06:44:15.049  3135  3135 V [0]UMC:ProfileStorage: Enter loadList
,03-17 06:44:15.049  3135  3135 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
03-17 06:44:15.049  3135  3135 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 06:44:15.049  3135  3135 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 06:44:15.049  3135  3135 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 06:44:15.049  3135  3135 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 06:44:15.049  3135  3135 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 06:44:15.049  1017  3038 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 06:44:15.049  3135  3135 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
,03-17 06:44:15.049  3135  3135 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 06:44:15.059  1017  1151 D InputDispatcher: Focus entered window: 3123
,03-17 06:44:15.059  3135  3135 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 06:44:15.059  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 06:44:15.059  3123  3123 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 06:44:15.059  3123  3281 I OpenGLRenderer: Initialized EGL, version 1.4
03-17 06:44:15.059  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 06:44:15.069  3123  3281 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 06:44:15.069  3123  3281 D OpenGLRenderer: Enabling debug mode 0
,03-17 06:44:15.089  3135  3135 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-17 06:44:15.089  3135  3135 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
03-17 06:44:15.089  3135  3135 I [0]UMC:Core: shutdown
,03-17 06:44:15.089  1017  1263 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 06:44:15.089  1017  1263 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:15.089  1017  1263 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:15.089  1017  1263 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 06:44:15.089  3135  3135 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-17 06:44:15.089  3135  3135 I art     : System.exit called, status: 0
03-17 06:44:15.089  3135  3135 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-17 06:44:15.089  1017  3038 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,03-17 06:44:15.099  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.099  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.099  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.099  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.109  3290  3290 E Zygote  : MountEmulatedStorage(),
03-17 06:44:15.109  3290  3290 I libpersona: KNOX_SDCARD checking this for 10086
03-17 06:44:15.109  3290  3290 E Zygote  : v2
,03-17 06:44:15.109  3290  3290 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:15.109  1017  3038 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3290 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,03-17 06:44:15.119  1017  3038 I ActivityManager: Killing 2308:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 06:44:15.119  3290  3290 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:15.129  3290  3290 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:15.129  3290  3290 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:15.129  1017  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 06:44:15.149  1183  1183 D PanelView: There is/are notification(s) 
,03-17 06:44:15.149  1017  3300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-17 06:44:15.149  1017  1029 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3135)(adj 0) has died(255,1046)
,03-17 06:44:15.149  3290  3290 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:15.149  3290  3290 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.159  3123  3123 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d25789e time:37541
,03-17 06:44:15.169  1017  1047 I ActivityManager: Displayed Component not be shown by security: +1s357ms
,03-17 06:44:15.169  1801  1801 I SamsungIME: getCurrentCandidateView
,03-17 06:44:15.169  1017  1047 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 06:44:15.169  1017  1047 W ActivityManager: mDVFSHelper.release()
,03-17 06:44:15.169  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2af90842 u0 com.test.thalitest/.MainActivity t12} time:37557
03-17 06:44:15.169  1017  1042 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 06:44:15.179  1017  1348 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-17 06:44:15.179  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.179  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.179  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.179  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.189  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 06:44:15.189  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 06:44:15.199  3312  3312 E Zygote  : MountEmulatedStorage(),
03-17 06:44:15.199  3312  3312 E Zygote  : v2
03-17 06:44:15.199  3312  3312 I libpersona: KNOX_SDCARD checking this for 10009
03-17 06:44:15.199  1327  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 06:44:15.199  3312  3312 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:15.199  3312  3312 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:15.199  1017  1348 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3312 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:15.199  3312  3312 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:15.209  1327  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 06:44:15.209  3312  3312 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 06:44:15.209  1017  1041 W libprocessgroup: failed to open /acct/uid_10131/pid_2401/cgroup.procs: No such file or directory
03-17 06:44:15.209  2945  2945 E BluetoothHeadset: BTStateChangeCB is registed
03-17 06:44:15.209  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2308/cgroup.procs: No such file or directory
,03-17 06:44:15.209  1327  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 06:44:15.209  2945  2945 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-17 06:44:15.209  1017  1523 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
03-17 06:44:15.209  1017  1523 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-17 06:44:15.209  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:15.209  1017  1523 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:15.209  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-17 06:44:15.219  2945  2945 E BluetoothHeadset: BluetoothHeadset service is binded
03-17 06:44:15.219  1327  1327 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,03-17 06:44:15.219  2945  2945 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-17 06:44:15.219  1327  1327 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 06:44:15.219  1327  1327 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 06:44:15.219  1327  1327 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 06:44:15.219  1017  1263 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
03-17 06:44:15.219  1327  1327 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 06:44:15.219  1017  1263 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
03-17 06:44:15.219  1327  1327 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 06:44:15.219  1327  1327 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-17 06:44:15.219  1017  1263 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:15.219  1017  1263 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:15.219  1017  1263 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
03-17 06:44:15.219  3268  3268 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-17 06:44:15.229  1017  1532 D SettingsProvider: name = aw_daemon_service_key_version_check
03-17 06:44:15.229  1017  1532 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:15.229  1017  1532 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:15.229  1017  1532 D SettingsProvider: selectionArgs: false
03-17 06:44:15.229  1017  1532 D SettingsProvider: selectionArgs: 10162
03-17 06:44:15.229  1017  1532 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:15.229  1017  1532 D SettingsProvider: ret = -1
,03-17 06:44:15.229  3312  3312 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:15.229  3268  3268 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-17 06:44:15.229  3312  3312 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.249  3268  3310 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-17 06:44:15.249  3268  3268 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-17 06:44:15.249  3268  3268 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 06:44:15.279  3268  3268 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 06:44:15.279  3268  3268 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 06:44:15.279  3268  3268 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-17 06:44:15.279  3268  3268 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 06:44:15.279  3268  3268 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-17 06:44:15.309  3268  3310 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,03-17 06:44:15.339  3268  3310 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-17 06:44:15.339   287   287 E SMD     : DCD OFF
,03-17 06:44:15.359   312   312 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 06:44:15.379   257   435 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-17 06:44:15.379   257  1099 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-17 06:44:15.389  1017  1532 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-17 06:44:15.399  1327  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 06:44:15.399  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 06:44:15.409  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:15.409  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 06:44:15.409  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 06:44:15.409  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 06:44:15.409  3178  3178 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-17 06:44:15.409  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-17 06:44:15.419  1327  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-17 06:44:15.419  1017  1488 I ActivityManager: Killing 2457:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
,03-17 06:44:15.419  3178  3178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-17 06:44:15.419  1017  1501 D ActivityManager: startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
03-17 06:44:15.419  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 06:44:15.419  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:15.419  1017  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:15.419  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 06:44:15.429  2945  2945 D BluetoothA2dp: Proxy object connected
,03-17 06:44:15.429  3290  3290 E UpdateRequestReceiver: ignoring update request
03-17 06:44:15.429  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 06:44:15.429  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-17 06:44:15.429  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-17 06:44:15.449  1327  1327 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 06:44:15.449  1327  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 06:44:15.459  3290  3290 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:15.459  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458193455455
,03-17 06:44:15.459  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458215040000
03-17 06:44:15.459  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-17 06:44:15.459  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-17 06:44:15.469  1183  1183 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-17 06:44:15.469  1183  1183 D OverheatReceiver: into the SAFE_MODE_ACTION
03-17 06:44:15.469  1183  1183 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-17 06:44:15.469  1183  1183 D OverheatReceiver: isSafeMode = false
,03-17 06:44:15.469  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 06:44:15.479  3178  3178 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
03-17 06:44:15.479  1017  1017 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 06:44:15.479  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-17 06:44:15.479  1464  1464 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
03-17 06:44:15.479  3178  3178 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-17 06:44:15.479  1017  1534 D SettingsProvider: name = internet_call_settings_visibility
,03-17 06:44:15.479  1017  1534 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:15.479  1017  1534 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:15.479  1017  1534 D SettingsProvider: selectionArgs: false
03-17 06:44:15.479  1017  1534 D SettingsProvider: selectionArgs: 1001
03-17 06:44:15.479  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-17 06:44:15.479  1017  1534 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:15.479  1017  1534 D SettingsProvider: ret = -1
03-17 06:44:15.479  1464  1464 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 06:44:15.479  3178  3178 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-17 06:44:15.479  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-17 06:44:15.489  1327  1327 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458215040000
,03-17 06:44:15.489  1442  1442 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
03-17 06:44:15.489  3178  3178 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-17 06:44:15.489  1017  1151 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
03-17 06:44:15.489  1017  1151 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-17 06:44:15.499  1017  1151 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:15.499  1017  1151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:15.499  1017  1151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
03-17 06:44:15.499  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,03-17 06:44:15.499  3290  3290 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:15.499  3178  3249 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-17 06:44:15.509  1017  1533 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
,03-17 06:44:15.509  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-17 06:44:15.509  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:15.509  1017  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:15.509  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 06:44:15.509  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-17 06:44:15.509  1017  1534 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,03-17 06:44:15.509  1017  1041 W libprocessgroup: failed to open /acct/uid_10088/pid_2457/cgroup.procs: No such file or directory
,03-17 06:44:15.509  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.509  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.509  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.509  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.519  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
03-17 06:44:15.519  3178  3249 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 06:44:15.519  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-17 06:44:15.519  3290  3290 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:15.519  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-17 06:44:15.519  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!,
,03-17 06:44:15.529  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 06:44:15.529  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:15.529  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:15.529  3178  3249 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-17 06:44:15.529  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:15.529  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:15.529  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:15.529  3123  3123 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3123
,03-17 06:44:15.529  3345  3345 E Zygote  : MountEmulatedStorage()
03-17 06:44:15.529  3345  3345 I libpersona: KNOX_SDCARD checking this for 10057
03-17 06:44:15.529  3345  3345 E Zygote  : v2
03-17 06:44:15.529  3345  3345 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:15.529  3345  3345 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:15.529  3345  3345 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:15.539  3345  3345 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:15.539  1017  1534 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3345 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-17 06:44:15.549  1327  1327 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 60
03-17 06:44:15.549  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458215040000
,03-17 06:44:15.549  1017  1532 D ActivityManager: bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
03-17 06:44:15.549  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 06:44:15.559  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:15.559  1017  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:15.559  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 06:44:15.559  1442  1442 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-17 06:44:15.569  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-17 06:44:15.579  3290  3290 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:15.589  1017  1533 E Tethering: No numeric data
,03-17 06:44:15.599  3345  3345 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:15.599  3345  3345 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.609  1327  1327 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,03-17 06:44:15.609  1327  1327 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 06:44:15.609  1017  1534 E Tethering: No numeric data
,03-17 06:44:15.619  1017  1263 D ActivityManager: startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,03-17 06:44:15.619  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.619  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.619  1017  1501 E Tethering: No numeric data
03-17 06:44:15.619  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.619  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.639  3370  3370 E Zygote  : MountEmulatedStorage()
03-17 06:44:15.639  3370  3370 I libpersona: KNOX_SDCARD checking this for 10166
03-17 06:44:15.639  3370  3370 E Zygote  : v2
03-17 06:44:15.639  3370  3370 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:15.639  3370  3370 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:15.639  1017  1263 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3370 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:15.639  3290  3290 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:15.649  3370  3370 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:15.649  3370  3370 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:15.649  1017  1534 E Tethering: No numeric data
,03-17 06:44:15.649  1017  1263 D ActivityManager: startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,03-17 06:44:15.659  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.659  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.659  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.659  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.659  1017  1533 E Tethering: No numeric data
,03-17 06:44:15.669  1017  1263 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3380 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:15.669  1017  1263 I ActivityManager: Killing 2472:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,03-17 06:44:15.679  3178  3178 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
03-17 06:44:15.679  3380  3380 I libpersona: KNOX_SDCARD checking this for 10092
03-17 06:44:15.679  3380  3380 E Zygote  : MountEmulatedStorage()
03-17 06:44:15.679  3380  3380 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:15.679  3380  3380 E Zygote  : v2
03-17 06:44:15.679  3380  3380 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:15.679  1017  1030 E Tethering: No numeric data
,03-17 06:44:15.679  3380  3380 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:15.689  3380  3380 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 06:44:15.689  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-17 06:44:15.699  3370  3370 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:15.699  3370  3370 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.709   282   702 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-17 06:44:15.709   282   702 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 06:44:15.709   282   702 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 06:44:15.709   282   702 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 06:44:15.709   282   702 I str_params: key: 'call_forwarding' value: ''
03-17 06:44:15.709  1957  1957 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 06:44:15.709  1957  1957 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-17 06:44:15.719  1957  1957 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-17 06:44:15.719  3268  3310 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 06:44:15.719  1957  1957 D ScoverManager: serviceVersion : 16908288
,03-17 06:44:15.719  1017  1488 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 06:44:15.719  1957  1957 D InCall  : InCallUtils - isCoverClosed false
,03-17 06:44:15.729  1017  1263 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 06:44:15.729  1442  1442 I Telecom : ProximitySensorManager: Proximity wake lock already released
03-17 06:44:15.729  1957  1957 D InCall  : InCallUtils - isCoverClosed false
,03-17 06:44:15.729  1957  1957 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-17 06:44:15.729  3380  3380 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:15.729  3380  3380 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.729  1957  1957 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS,
,03-17 06:44:15.729  1957  1957 D InCall  : InCallPresenter -  - dismissCoverDialog()...,
,03-17 06:44:15.729  3268  3310 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected,
,03-17 06:44:15.739  1957  1957 I InCall  : CallSContextMotion - stopPutDownListening
,03-17 06:44:15.739  1957  1957 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 06:44:15.749  1183  1183 D PhoneStatusBarView: setCallBackground:0
,03-17 06:44:15.749  3268  3310 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-17 06:44:15.749  3268  3310 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
03-17 06:44:15.749  1017  1523 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 06:44:15.749  1957  1957 D InCall  : InCallUtils - isCoverClosed false,
,03-17 06:44:15.749  3268  3310 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-17 06:44:15.789  1316  3177 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 06:44:15.789  1316  3177 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 06:44:15.799  3178  3249 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-17 06:44:15.799  1017  1041 W libprocessgroup: failed to open /acct/uid_10142/pid_2472/cgroup.procs: No such file or directory
,03-17 06:44:15.799  1017  1501 D ActivityManager: startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,03-17 06:44:15.799  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.799  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.799  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.799  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.809  3268  3310 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-17 06:44:15.829  1017  1501 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3403 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 06:44:15.829  1017  1501 I ActivityManager: Killing 2553:com.samsung.android.securitylogagent/1000 (adj 15): empty #31,
03-17 06:44:15.829  1017  1501 I ActivityManager: Killing 2524:com.wsomacp/u0a25 (adj 15): empty #32
03-17 06:44:15.829  1017  1501 I ActivityManager: Killing 2508:com.sec.android.app.camera/u0a139 (adj 15): empty #33
03-17 06:44:15.829  1801  1801 D SamsungIME: Dismiss ExpandCandiate
,03-17 06:44:15.829  3403  3403 E Zygote  : MountEmulatedStorage(),
,03-17 06:44:15.839  3403  3403 E Zygote  : v2
,03-17 06:44:15.839  3403  3403 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:15.839  3403  3403 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:15.839  3403  3403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:15.839  3403  3403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:15.849  3403  3403 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:15.849   302   302 I art     : Explicit concurrent mark sweep GC freed 8743(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 667us total 29.752ms
03-17 06:44:15.859  3123  3123 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-17 06:44:15.869  3403  3403 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:15.869  1017  1533 E Tethering: No numeric data
03-17 06:44:15.869  3403  3403 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.869  1017  1029 E Tethering: No numeric data
,03-17 06:44:15.879   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 600us total 25.413ms
,03-17 06:44:15.889  1017  1523 E Tethering: No numeric data
,03-17 06:44:15.899  3268  3310 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 06:44:15.899   302   302 W art     : Suspending all threads took: 9.670ms
,03-17 06:44:15.909   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 10.471ms total 26.752ms
,03-17 06:44:15.909  1957  1957 D VideoCallManager: Instantiating VideoCallManager
,03-17 06:44:15.919  3268  3310 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 06:44:15.919  1957  1957 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 06:44:15.919  3268  3310 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-17 06:44:15.919  3268  3310 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-17 06:44:15.919  1957  1957 I GFX construct_block_size_descriptor_2d second part: took 2.601511ms for 0*0 texture 0
,03-17 06:44:15.919  3268  3311 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 06:44:15.929  1957  1957 I GFX generate_partition_tables: took 5.579688ms for 0*0 texture 0
,03-17 06:44:15.929  3268  3310 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,03-17 06:44:15.929  1957  1957 I GFX raster: took 12.443751ms for 176*144 texture 0
03-17 06:44:15.929  1957  1957 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8391c68 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb83a9e78 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 06:44:15.939  3268  3311 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 06:44:15.939  1957  1957 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-17 06:44:15.939  1957  1957 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 06:44:15.939  1957  1957 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 06:44:15.939  1957  1957 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 06:44:15.939  1957  1957 I Adreno-EGL: Local Branch: 
03-17 06:44:15.939  1957  1957 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 06:44:15.939  1957  1957 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 06:44:15.939  1957  1957 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 06:44:15.939  3268  3311 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 06:44:15.959  3268  3310 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/17/06:44:15
,03-17 06:44:15.959  1017  1348 E Tethering: No numeric data
,03-17 06:44:15.969  3268  3311 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 06:44:15.969  3268  3310 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
03-17 06:44:15.969  3268  3311 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 06:44:15.969  1957  1957 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 06:44:15.979  1957  1957 I glCompressedTexImage2D: took 0.459583ms for 320*61440 texture 37809
,03-17 06:44:15.989  2129  2129 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-17 06:44:15.989  3268  3310 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
03-17 06:44:15.989  2129  2129 I dhcpcd  : wlan0: no IPv6 Routers available
,03-17 06:44:15.989  1957  1957 I draw setup: took 12.706614ms for 320*240 texture 37809
03-17 06:44:15.989  1957  1957 E GFX GPU raster: drawn
,03-17 06:44:15.989  1957  1957 I GFX GPU raster ASTC: took 45.058905ms for 320*240 texture 12
03-17 06:44:15.989  1957  1957 I GFX raster: took 45.135468ms for 320*240 texture 0
03-17 06:44:15.989  1957  1957 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a9e78 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb83ac1b8 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 06:44:16.009  1957  1957 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 06:44:16.009  3268  3311 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 06:44:16.009  1957  1957 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 06:44:16.009  3268  3311 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 06:44:16.009  1957  1957 I glCompressedTexImage2D: took 0.427864ms for 480*122880 texture 37813
03-17 06:44:16.009  1957  1957 I draw setup: took 0.923020ms for 480*640 texture 37813
03-17 06:44:16.009  1957  1957 E GFX GPU raster: drawn
,03-17 06:44:16.009  3268  3311 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-17 06:44:16.009  3268  3311 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 06:44:16.019  3268  3311 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 06:44:16.019  1957  1957 I GFX GPU raster ASTC: took 8.795885ms for 480*640 texture 12
03-17 06:44:16.019  1957  1957 I GFX raster: took 8.873489ms for 480*640 texture 0
03-17 06:44:16.019  1957  1957 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83ac1b8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb85da648 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 06:44:16.059  1957  1957 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-17 06:44:16.059  1957  1957 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 06:44:16.059  1957  1957 I glCompressedTexImage2D: took 0.336459ms for 440*116864 texture 37809
03-17 06:44:16.059  1957  1957 I draw setup: took 0.834687ms for 440*330 texture 37809
03-17 06:44:16.059  1957  1957 E GFX GPU raster: drawn
,03-17 06:44:16.069  1957  1957 I GFX GPU raster ASTC: took 5.172500ms for 440*330 texture 12
03-17 06:44:16.069  1957  1957 I GFX raster: took 5.249010ms for 440*330 texture 0
03-17 06:44:16.069  1957  1957 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb85da648 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb85eea38 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 06:44:16.069  3268  3311 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 06:44:16.079  3403  3403 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-17 06:44:16.109  3403  3403 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 06:44:16.109  3403  3403 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 06:44:16.109  3403  3403 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 06:44:16.109  1957  1957 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 06:44:16.119  1957  1957 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 06:44:16.119  1957  1957 I glCompressedTexImage2D: took 0.475573ms for 480*163840 texture 37811
03-17 06:44:16.119  1957  1957 I draw setup: took 0.871042ms for 480*640 texture 37811
03-17 06:44:16.119  1957  1957 E GFX GPU raster: drawn
,03-17 06:44:16.119  1957  1957 I GFX GPU raster ASTC: took 5.793386ms for 480*640 texture 12
03-17 06:44:16.119  1957  1957 I GFX raster: took 5.880937ms for 480*640 texture 0
03-17 06:44:16.119  1957  1957 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb85de848 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb85ee570 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 06:44:16.149  1017  2712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 06:44:16.159  3123  3329 D jxcore_app_log: JniHelper::setJavaVM(0xb7fc8450), pthread_self() = -1202525752
,03-17 06:44:16.179  1017  1523 D ActivityManager: getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,03-17 06:44:16.179  1957  1957 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 06:44:16.179  1957  1957 I GFX construct_block_size_descriptor_2d second part: took 2.037396ms for 0*0 texture 0
,03-17 06:44:16.179  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.179  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.179  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.179  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.189  1957  1957 I GFX generate_partition_tables: took 7.533489ms for 0*0 texture 0
03-17 06:44:16.189  1017  3038 I art     : Explicit concurrent mark sweep GC freed 19609(991KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/40MB, paused 3.495ms total 184.902ms
,03-17 06:44:16.189  1957  1957 I GFX raster: took 11.582396ms for 176*144 texture 0
03-17 06:44:16.189  1957  1957 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb85d7f08 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb85d8028 counterpartCT=4 counterpartW=176 counterparth=144
03-17 06:44:16.189  3123  3329 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 06:44:16.189  3123  3329 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 06:44:16.189  3123  3329 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 06:44:16.189  3123  3329 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 06:44:16.189  3123  3329 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 06:44:16.189  3123  3329 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fab7005 added. We now have 1 listener(s)
,03-17 06:44:16.209  3422  3422 E Zygote  : MountEmulatedStorage()
03-17 06:44:16.209  3422  3422 E Zygote  : v2
03-17 06:44:16.209  3422  3422 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:16.209  3422  3422 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:16.209  3422  3422 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:16.219  3422  3422 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:16.219  1017  1523 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3422 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:16.219  3422  3422 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:16.239  3123  3329 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,03-17 06:44:16.239  1957  1957 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 06:44:16.239  1957  1957 I GFX construct_block_size_descriptor_2d second part: took 2.251771ms for 0*0 texture 0
,03-17 06:44:16.249  3123  3329 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,03-17 06:44:16.249  3123  3329 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
03-17 06:44:16.249  3123  3329 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 06:44:16.249  3123  3329 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 06:44:16.259  3123  3329 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 06:44:16.259  3123  3329 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 06:44:16.259  3123  3329 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 06:44:16.259  3123  3329 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
03-17 06:44:16.259  3123  3329 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 06:44:16.259  3123  3329 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 06:44:16.259  3123  3329 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 06:44:16.259  3123  3329 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 06:44:16.259  3123  3329 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 06:44:16.259  3123  3329 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 06:44:16.259  3123  3329 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23ef0768 added. We now have 1 listener(s)
,03-17 06:44:16.259  3123  3329 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 06:44:16.259  1957  1957 I GFX generate_partition_tables: took 6.169688ms for 0*0 texture 0
,03-17 06:44:16.259  1957  1957 I GFX raster: took 10.647760ms for 176*144 texture 0
03-17 06:44:16.259  1957  1957 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb85d8248 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb85d81e8 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 06:44:16.259  1017  1041 W libprocessgroup: failed to open /acct/uid_10139/pid_2508/cgroup.procs: No such file or directory
03-17 06:44:16.259  1017  1041 W libprocessgroup: failed to open /acct/uid_10025/pid_2524/cgroup.procs: No such file or directory
03-17 06:44:16.259  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2553/cgroup.procs: No such file or directory
,03-17 06:44:16.269  3422  3422 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:16.269  3422  3422 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:16.269  1957  1957 D ScoverManager: registerListener
,03-17 06:44:16.269  1017  1348 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 06:44:16.269  1017  1534 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 06:44:16.269  1017  1534 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@2d45ffd3, pid : 1957, uid : 1001, type : 1
,03-17 06:44:16.279  1957  1957 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 06:44:16.289  3123  3329 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 06:44:16.289  3123  3329 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-17 06:44:16.289  3123  3329 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-17 06:44:16.289  3123  3329 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,03-17 06:44:16.289  3123  3329 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 06:44:16.299  3123  3329 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 06:44:16.299  3123  3329 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,03-17 06:44:16.309  3268  3311 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-17 06:44:16.319  1017  1348 V VibratorService: hasVibrator - useVibetonz: true
,03-17 06:44:16.329  1316  3177 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 06:44:16.329  3123  3329 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 06:44:16.329  3123  3329 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 06:44:16.329  3123  3329 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 06:44:16.329  3123  3329 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 06:44:16.329  3123  3329 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 06:44:16.329  3123  3329 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 06:44:16.329  3123  3329 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 06:44:16.329  3123  3329 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 06:44:16.329  3123  3329 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 06:44:16.329  3123  3329 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 06:44:16.359   312   312 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 06:44:16.359  1017  1533 V VibratorService: hasVibrator - useVibetonz: true
,03-17 06:44:16.379  1017  1532 V VibratorService: hasVibrator - useVibetonz: true
,03-17 06:44:16.399  3268  3310 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-17 06:44:16.409  3422  3422 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 06:44:16.409  3422  3422 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 06:44:16.409  3123  3123 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 06:44:16.419  3123  3123 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 06:44:16.419  3422  3422 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 06:44:16.419  3123  3123 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-17 06:44:16.419  1316  3177 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 06:44:16.449  1017  1488 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,03-17 06:44:16.449  3422  3430 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 06:44:16.459  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.459  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.459  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.459  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.479  3178  3249 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-17 06:44:16.489  3442  3442 E Zygote  : MountEmulatedStorage(),
,03-17 06:44:16.489  3442  3442 E Zygote  : v2,
,03-17 06:44:16.489  1017  1488 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3442 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
03-17 06:44:16.499  3442  3442 I libpersona: KNOX_SDCARD checking this for 10015
03-17 06:44:16.499  3442  3442 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:16.499  3442  3442 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:16.499  3442  3442 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:16.509  3442  3442 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:16.519  3178  3249 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 06:44:16.539  3403  3403 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 06:44:16.539  3178  3249 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-17 06:44:16.539  3178  3249 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 06:44:16.559  1316  3177 D ScoverManager: serviceVersion : 16908288
,03-17 06:44:16.559  3442  3442 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:16.559  3442  3442 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:16.579  3403  3403 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 06:44:16.579  3403  3403 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 06:44:16.589  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,03-17 06:44:16.589  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.589  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.589  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.589  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.619  1017  1534 D LocationManagerService: getProviders()=[passive]
,03-17 06:44:16.619  3460  3460 E Zygote  : MountEmulatedStorage()
03-17 06:44:16.619  3460  3460 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:16.619  3460  3460 E Zygote  : v2
03-17 06:44:16.619  3460  3460 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:16.629  1017  1030 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3460 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:16.629  3460  3460 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 06:44:16.629  1017  1030 I ActivityManager: Killing 2648:com.android.keychain/1000 (adj 15): empty #31
03-17 06:44:16.629  3460  3460 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:16.629  1017  1030 I ActivityManager: Killing 2605:com.android.calendar/u0a135 (adj 15): empty #32
03-17 06:44:16.629  3460  3460 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 06:44:16.659  3460  3460 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:16.659  3460  3460 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:16.769  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2648/cgroup.procs: No such file or directory
,03-17 06:44:16.769  1017  1041 W libprocessgroup: failed to open /acct/uid_10135/pid_2605/cgroup.procs: No such file or directory
,03-17 06:44:16.799  3460  3460 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 06:44:16.809  3460  3460 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 06:44:16.839  3268  3310 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,03-17 06:44:16.849  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:16.849  1017  2828 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:44:16.849  3268  3310 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 06:44:16.849  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:16.849  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:16.849  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 06:44:16.859  3422  3430 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 06:44:16.869  1017  1029 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
,03-17 06:44:16.869  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-17 06:44:16.879  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:16.879  1017  1029 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 06:44:16.879  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 06:44:16.879  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.879  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.879  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.879  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.889  3370  3441 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
03-17 06:44:16.889  3370  3441 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 06:44:16.899  3485  3485 E Zygote  : MountEmulatedStorage(),
03-17 06:44:16.899  3485  3485 E Zygote  : v2
,03-17 06:44:16.899  3485  3485 I libpersona: KNOX_SDCARD checking this for 10092
,03-17 06:44:16.899  3485  3485 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:16.899  1017  1029 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3485 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 06:44:16.899  3485  3485 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:16.909  3485  3485 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:16.909  3485  3485 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 06:44:16.909  3460  3460 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 06:44:16.929  3460  3460 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 06:44:16.929  1017  1532 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-17 06:44:16.929  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-17 06:44:16.929  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:16.929  1017  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:16.929  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 06:44:16.949  3485  3485 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:16.949  3485  3485 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:16.969  1801  1801 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 06:44:17.039  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-17 06:44:17.039  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.039  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.039  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.039  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.049  1017  1017 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3505 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a,
,03-17 06:44:17.059  3505  3505 E Zygote  : MountEmulatedStorage()
03-17 06:44:17.059  3505  3505 E Zygote  : v2
03-17 06:44:17.059  3505  3505 I libpersona: KNOX_SDCARD checking this for 10003
03-17 06:44:17.059  3505  3505 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:17.059  3505  3505 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:17.059  3505  3505 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:17.059  3505  3505 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:17.079  1017  1501 I ActivityManager: Killing 2448:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,03-17 06:44:17.089  1316  3177 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 06:44:17.109  3505  3505 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:17.109  3505  3505 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:17.119  1316  3177 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-17 06:44:17.139  3370  3441 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 06:44:17.159  3460  3460 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 06:44:17.179  3460  3460 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 06:44:17.179  3460  3460 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 06:44:17.179  3460  3460 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 06:44:17.179  3460  3460 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 06:44:17.179  3460  3460 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-17 06:44:17.179  3460  3460 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 06:44:17.199  1801  1801 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 06:44:17.199  1017  1263 I ActivityManager: Killing 2723:com.android.email/u0a145 (adj 15): empty #31
,03-17 06:44:17.219  3312  3312 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 06:44:17.229  3312  3312 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 06:44:17.239  1017  1348 I ActivityManager: Killing 2736:com.samsung.android.sm/1000 (adj 15): empty #31
,03-17 06:44:17.239  3312  3312 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 06:44:17.249  3505  3505 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 06:44:17.249  3123  3438 W jxcore-log: Initializing JXcore engine
03-17 06:44:17.249  3123  3438 W jxcore-log: JXcore engine is ready
,03-17 06:44:17.279  1017  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
03-17 06:44:17.279  1017  1041 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,03-17 06:44:17.279  1017  1041 W libprocessgroup: failed to open /acct/uid_10044/pid_2448/cgroup.procs: No such file or directory
,03-17 06:44:17.289  1801  1801 I SamsungIME: KeybaordView init() : load resources
,03-17 06:44:17.309  3380  3380 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 06:44:17.319  3312  3312 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 06:44:17.319  1017  1533 D ActivityManager: startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,03-17 06:44:17.319  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.319  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.319  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.319  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.329  3268  3311 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
03-17 06:44:17.329  1926  1926 E audit   : type=1400 msg=audit(1458193457.329:205): avc:  denied  { ioctl } for  pid=3438 comm="Thread-408" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 06:44:17.329  1926  1926 E audit   :  SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:17.329  1926  1926 E audit   : type=1300 msg=audit(1458193457.329:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9b40f8f8 items=0 ppid=302 ppcomm=main pid=3438 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-408" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 06:44:17.329  1926  1926 E audit   : type=1320 msg=audit(1458193457.329:205): 
,03-17 06:44:17.349  3526  3526 E Zygote  : MountEmulatedStorage()
,03-17 06:44:17.349  3526  3526 E Zygote  : v2
03-17 06:44:17.349  3526  3526 I libpersona: KNOX_SDCARD checking this for 10014
03-17 06:44:17.349  3526  3526 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:17.349  3526  3526 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:17.349  3526  3526 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:17.349  3526  3526 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:17.349  3123  3438 W jxcore-log: Starting JXcore engine
,03-17 06:44:17.359  1017  1533 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3526 uid=10014 gids={50014, 9997} abi=armeabi-v7a,
,03-17 06:44:17.359  1017  1533 I ActivityManager: Killing 2863:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-17 06:44:17.369  1801  1801 I SamsungIME: getCurrentKeyboard
03-17 06:44:17.369  1801  1801 I SamsungIME: getTextKeyboard
,03-17 06:44:17.369  3526  3526 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:17.369  3526  3526 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:17.389  1017  1041 W libprocessgroup: failed to open /acct/uid_10145/pid_2723/cgroup.procs: No such file or directory
,03-17 06:44:17.409  3268  3311 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,03-17 06:44:17.419  3380  3380 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-17 06:44:17.419  1801  1801 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 06:44:17.429  3526  3526 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 06:44:17.429  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
,03-17 06:44:17.429  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-17 06:44:17.429  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:17.439  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:17.439  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 06:44:17.459  3526  3545 V OneTimeService: OneTimeService.onHandleIntent
,03-17 06:44:17.469  3505  3505 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 06:44:17.499  3505  3505 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 06:44:17.499  3505  3505 D UserAnalysis: Create SecureDbHelper
,03-17 06:44:17.499  3123  3438 W jxcore-log: Platform android
03-17 06:44:17.499  3123  3438 W jxcore-log: 
,03-17 06:44:17.499  3123  3438 W jxcore-log: Process ARCH arm
03-17 06:44:17.499  3123  3438 W jxcore-log: 
,03-17 06:44:17.499  1017  3038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:17.509  3380  3380 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-17 06:44:17.509  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2736/cgroup.procs: No such file or directory
03-17 06:44:17.509  1017  1041 W libprocessgroup: failed to open /acct/uid_10099/pid_2863/cgroup.procs: No such file or directory
,03-17 06:44:17.509  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:17.509  1017  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:17.509  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:17.529  3505  3505 D IntelligenceServiceApplication: onCreate()
,03-17 06:44:17.539  3505  3505 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 06:44:17.539  1017  3038 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 06:44:17.539  1017  3038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-17 06:44:17.549  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:17.549  1017  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:17.549  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:17.549  1017  1534 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,03-17 06:44:17.559  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.559  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.559  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.559  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.579  3551  3551 E Zygote  : MountEmulatedStorage()
03-17 06:44:17.579  3551  3551 E Zygote  : v2
03-17 06:44:17.579  3551  3551 I libpersona: KNOX_SDCARD checking this for 10060
,03-17 06:44:17.579  3551  3551 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:17.579  3551  3551 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 06:44:17.579  1017  1534 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3551 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 06:44:17.589  3551  3551 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 06:44:17.589  1017  1504 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-17 06:44:17.589  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0,
,03-17 06:44:17.589  3551  3551 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 06:44:17.589  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:17.589  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:17.589  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:17.589  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 06:44:17.599  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,03-17 06:44:17.599  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:17.599  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:17.599  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:17.599  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 06:44:17.599  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-17 06:44:17.599  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:17.599  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:17.599  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:17.609  2590  3230 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3230)  
,03-17 06:44:17.609  3178  3249 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 06:44:17.629  3551  3551 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:17.639  3551  3551 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:17.639  3380  3380 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-17 06:44:17.639  3380  3380 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-17 06:44:17.659  3505  3505 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 06:44:17.669  3370  3441 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 06:44:17.669  3370  3441 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3fd0d2f1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 06:44:17.669  3370  3441 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 06:44:17.669  3380  3380 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-17 06:44:17.679  1017  1532 I ActivityManager: Killing 2211:flipboard.app/u0a98 (adj 15): empty #31
,03-17 06:44:17.689  1017  3038 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-17 06:44:17.689  1017  3038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-17 06:44:17.689  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:17.689  1017  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:17.689  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:17.689  3380  3380 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 06:44:17.689  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-17 06:44:17.699  3505  3505 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 06:44:17.719  1017  1532 D ActivityManager: startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
,03-17 06:44:17.719  1017  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.719  1017  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.719  1017  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.719  1017  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.729  3505  3505 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 06:44:17.729  3505  3505 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 06:44:17.739  3577  3577 E Zygote  : MountEmulatedStorage()
03-17 06:44:17.739  3577  3577 E Zygote  : v2
03-17 06:44:17.739  3577  3577 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:17.739  3577  3577 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:17.739  3577  3577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:17.739  3577  3577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:17.739  3577  3577 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:17.749  1017  1532 I ActivityManager: Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3577 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:17.779  3577  3577 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:17.779  3577  3577 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:17.789  3345  3479 W art     : Verification of void com.google.android.apps.gsa.extradex.attemptedsearchhistory.i.run() took 436.127ms
,03-17 06:44:17.799  3123  3438 I jxcore-log: JXcore Cordova bridge is ready!
03-17 06:44:17.799  3123  3438 I jxcore-log: 
,03-17 06:44:17.799  3123  3438 W jxcore-log: JXcore engine is started
,03-17 06:44:17.809  1017  1534 I ActivityManager: Killing 2886:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-17 06:44:17.809  3123  3329 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 06:44:17.819  3123  3123 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-17 06:44:17.819  3380  3380 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 06:44:17.879  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,03-17 06:44:17.879  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,03-17 06:44:17.879  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:17.879  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:17.879  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 06:44:17.889  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-17 06:44:17.889  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 06:44:17.889  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:17.889  3380  3380 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-17 06:44:17.889  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:17.889  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 06:44:17.899  3577  3577 I Hs20UtilService: onCreate
,03-17 06:44:17.899  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,03-17 06:44:17.899  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.899  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.899  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.899  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.909  3345  3596 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 06:44:17.909  3345  3596 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 06:44:17.909  3345  3596 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_hotword_models]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 06:44:17.909  3345  3601 I SearchServiceFactory: refreshing search history.
,03-17 06:44:17.919  3602  3602 E Zygote  : MountEmulatedStorage()
03-17 06:44:17.919  3602  3602 E Zygote  : v2
03-17 06:44:17.919  3602  3602 I libpersona: KNOX_SDCARD checking this for 10019
03-17 06:44:17.919  3602  3602 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:17.919  3602  3602 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:17.919  1017  1488 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3602 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 06:44:17.929  3602  3602 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:17.929  3602  3602 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:17.949  3602  3602 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:17.949  3602  3602 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:17.949  1017  1532 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-17 06:44:17.949  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,03-17 06:44:17.969  3577  3577 I Hs20UtilService: Starting #1
,03-17 06:44:17.969  3577  3597 I Hs20UtilService: Message received 5003
,03-17 06:44:17.969  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:17.969  1017  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:17.969  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:18.029  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2886/cgroup.procs: No such file or directory
03-17 06:44:18.029  1017  1041 W libprocessgroup: failed to open /acct/uid_10098/pid_2211/cgroup.procs: No such file or directory
,03-17 06:44:18.049  3551  3551 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-17 06:44:18.079  1017  1263 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,03-17 06:44:18.089  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.089  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.089  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.089  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.099  1316  3177 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 06:44:18.099  1017  1263 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3623 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:44:18.109  3623  3623 E Zygote  : MountEmulatedStorage()
03-17 06:44:18.109  3623  3623 I libpersona: KNOX_SDCARD checking this for 10062
03-17 06:44:18.109  3623  3623 E Zygote  : v2
03-17 06:44:18.109  3623  3623 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:18.109  3623  3623 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:18.109  3623  3623 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:18.109  3623  3623 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:18.129  3442  3442 I RlzPingService: Setting next ping for 1458798258132
,03-17 06:44:18.149  3623  3623 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.149  3623  3623 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.179  1017  1263 I ActivityManager: Killing 1931:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-17 06:44:18.179  3370  3392 W art     : Suspending all threads took: 9.948ms
,03-17 06:44:18.219  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-17 06:44:18.219  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.219  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.219  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.219  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.219  3345  3480 W art     : Verification of com.google.m.a.a.a.f com.google.m.a.a.a.f.dR(long) took 134.207ms
,03-17 06:44:18.239  3642  3642 E Zygote  : MountEmulatedStorage()
,03-17 06:44:18.239  3642  3642 E Zygote  : v2
03-17 06:44:18.239  3642  3642 I libpersona: KNOX_SDCARD checking this for 10094
03-17 06:44:18.239  3642  3642 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:18.239  3642  3642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:18.239  3642  3642 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:18.239  1017  1029 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3642 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
03-17 06:44:18.239  3642  3642 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:18.239  1017  1029 I ActivityManager: Killing 2897:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,03-17 06:44:18.269   302   302 I art     : Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 34.822ms
,03-17 06:44:18.289  3642  3642 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.289  3642  3642 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.289   302   302 I art     : Explicit concurrent mark sweep GC freed 3(96B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 626us total 17.565ms
,03-17 06:44:18.299  3602  3602 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 06:44:18 GMT+01:00 2016
,03-17 06:44:18.299  1017  1534 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-17 06:44:18.299  1017  1534 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 06:44:18.309  1017  1534 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.309  1017  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:18.309  1017  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 06:44:18.309  3602  3602 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 06:44:18.309  1017  3038 D ActivityManager: startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,03-17 06:44:18.309   302   302 I art     : Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 20.404ms
03-17 06:44:18.309  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.309  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.309  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.309  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.329  3602  3602 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 06:44:18.339   287   287 E SMD     : DCD OFF,
,03-17 06:44:18.349  3659  3659 E Zygote  : MountEmulatedStorage()
03-17 06:44:18.349  3659  3659 I libpersona: KNOX_SDCARD checking this for 10022
03-17 06:44:18.349  3659  3659 E Zygote  : v2
03-17 06:44:18.349  3659  3659 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:18.349  3659  3659 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:18.349  3659  3659 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:18.349  3659  3659 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:18.359  1017  3038 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3659 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a,
,03-17 06:44:18.379  3623  3623 I ExternalOEMControlProvider: onCreate
,03-17 06:44:18.379  3380  3641 I System.out: Thread-449(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 06:44:18.379  3380  3641 I System.out: Thread-449(ApacheHTTPLog):isSBSettingEnabled false
03-17 06:44:18.379  3380  3641 I System.out: Thread-449(ApacheHTTPLog):isShipBuild true
03-17 06:44:18.379  3380  3641 I System.out: Thread-449(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 06:44:18.379  3380  3641 I System.out: Thread-449(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 06:44:18.389  2627  2696 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 06:44:18.389   274   977 D EnterpriseController: uids 10092
03-17 06:44:18.389   274   977 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 06:44:18.389   274   977 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-17 06:44:18.399  3659  3659 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.399  3659  3659 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.399  3602  3602 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 06:44:18.409  1017  1533 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,03-17 06:44:18.419  3602  3602 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 06:44:18.419  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.419  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.419  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.419  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.429  3678  3678 E Zygote  : MountEmulatedStorage()
,03-17 06:44:18.429  3678  3678 E Zygote  : v2
03-17 06:44:18.429  3678  3678 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:18.429  3678  3678 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:18.429  3678  3678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:18.439  1017  1533 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3678 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:18.439  1017  1533 I ActivityManager: Killing 2370:com.sec.modem.settings/1000 (adj 15): empty #31
,03-17 06:44:18.439  1017  1488 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-17 06:44:18.439  3678  3678 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:18.439  1017  1488 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 06:44:18.439  3678  3678 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:18.439  1017  1488 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 06:44:18.439  1017  1488 D SettingsProvider: selectionArgs: false
03-17 06:44:18.439  1017  1488 D SettingsProvider: selectionArgs: 10062
,03-17 06:44:18.439  1017  1488 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:18.439  1017  1488 D SettingsProvider: ret = -1
,03-17 06:44:18.449  3642  3642 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 06:44:18.449  3642  3642 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 06:44:18.459  1017  1488 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 06:44:18.459  1017  1263 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
,03-17 06:44:18.459  3642  3642 D elm:15183: MDMBridge.setEnterpriseBridge()
03-17 06:44:18.459  1017  1263 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:18.459  1017  1263 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 06:44:18.459  1017  1263 D SettingsProvider: selectionArgs: false
03-17 06:44:18.459  1017  1263 D SettingsProvider: selectionArgs: 10062
,03-17 06:44:18.469  1017  1532 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,03-17 06:44:18.469  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 06:44:18.469  1017  1263 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-17 06:44:18.469  1017  1263 D SettingsProvider: ret = -1
,03-17 06:44:18.469  1017  1263 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 06:44:18.479  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.479  1017  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:18.479  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 06:44:18.489  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:18.489  3642  3642 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 06:44:18.489  3678  3678 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.499  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:18.509  3678  3678 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.519  3642  3642 D elm:15183: ElmAgentService : onCreate()
,03-17 06:44:18.519  3642  3693 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 06:44:18.519  3642  3642 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,03-17 06:44:18.519  3642  3642 D elm:15183: BootCompletedState : startBootCompleted() call
,03-17 06:44:18.549  3642  3642 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 06:44:18.549  3642  3642 I elm:15183: Get License : 0
,03-17 06:44:18.549  3642  3642 D elm:15183: ElmAgentService : onDestroy().
,03-17 06:44:18.559  1427  1427 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 06:44:18.569  3602  3657 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 06:44:18.569  3678  3678 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 06:44:18.589  1316  3177 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 06:44:18.589  1017  1501 I ActivityManager: Killing 2930:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-17 06:44:18.599  1316  3177 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 06:44:18.599  1316  3177 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 06:44:18.599  3678  3678 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-17 06:44:18.599  3678  3678 I ServiceMode: setReferenceIsDumpState : 0
,03-17 06:44:18.609  3178  3249 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 06:44:18.609  3602  3657 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED
,03-17 06:44:18.639  1017  1263 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-17 06:44:18.639  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.639  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.639  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.639  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.649  1427  1427 V EmergencyMode: [EmergencyBase] setBootTime
,03-17 06:44:18.649  1427  1427 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 06:44:18.649  3701  3701 E Zygote  : MountEmulatedStorage()
03-17 06:44:18.649  3701  3701 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:18.649  3701  3701 E Zygote  : v2
03-17 06:44:18.649  3701  3701 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:18.659  3701  3701 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:18.659  1017  1263 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3701 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:18.659  1017  1263 I ActivityManager: Killing 2965:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 06:44:18.659  3701  3701 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:18.659  1017  1041 W libprocessgroup: failed to open /acct/uid_10004/pid_1931/cgroup.procs: No such file or directory
,03-17 06:44:18.669  1017  1041 W libprocessgroup: failed to open /acct/uid_10152/pid_2897/cgroup.procs: No such file or directory
,03-17 06:44:18.679  3701  3701 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:18.679  1017  1151 D ActivityManager: startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,03-17 06:44:18.679  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.679  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.679  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.679  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.699  3708  3708 E Zygote  : MountEmulatedStorage()
03-17 06:44:18.699  3708  3708 E Zygote  : v2
03-17 06:44:18.699  3708  3708 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:18.699  3708  3708 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:18.699  3708  3708 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:18.709  3708  3708 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:18.709  1017  1151 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3708 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:18.709  3708  3708 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:18.729  3602  3602 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 06:44:18.729  1017  3038 D ActivityManager: startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
,03-17 06:44:18.729  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.729  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.729  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.729  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.749  3701  3701 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.749  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2370/cgroup.procs: No such file or directory
03-17 06:44:18.749  3701  3701 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.749  3730  3730 E Zygote  : MountEmulatedStorage()
03-17 06:44:18.749  3730  3730 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:18.749  3730  3730 E Zygote  : v2
03-17 06:44:18.749  3730  3730 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:18.749  3730  3730 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:18.759  1017  3038 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3730 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:18.759  1017  3038 I ActivityManager: Killing 2333:com.android.mms/u0a46 (adj 15): empty #31
,03-17 06:44:18.759  3730  3730 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:18.759  3730  3730 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:18.779  3708  3708 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.789  3708  3708 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.789  3730  3730 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.789  3730  3730 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.799  3370  3370 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 06:44:18.819  3701  3701 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-17 06:44:18.819  1017  1030 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 06:44:18.819  1017  1030 D SecContentProvider2: mCursor = null
,03-17 06:44:18.819  1017  1151 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 06:44:18.819  1017  1151 D SecContentProvider2: mCursor = null
,03-17 06:44:18.829  3701  3701 V MTPRx   : sealedState: false
,03-17 06:44:18.829  3701  3701 V MTPRx   : sealedUsbMassStorageState: false
,03-17 06:44:18.829  1017  1532 D SettingsProvider: name = mtp_usb_connection_status
,03-17 06:44:18.859  1017  1501 D SettingsProvider: name = media_player_mode
,03-17 06:44:18.869  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:18.869  1017  1488 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 06:44:18.879  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:18.889  1017  3038 D SettingsProvider: name = mtp_running_status
,03-17 06:44:18.889  3345  3601 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 06:44:18.889  1017  1533 D SettingsProvider: name = media_mount_count
,03-17 06:44:18.899  1017  3038 D CountryDetector: No listener is left
,03-17 06:44:18.899  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:18.899  1017  1534 D SettingsProvider: name = mtp_sync_alive
,03-17 06:44:18.909  1017  3038 D SettingsProvider: name = sdcard_launch
,03-17 06:44:18.919  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:18.919  1017  1263 D SettingsProvider: name = boot_time_connected
,03-17 06:44:18.919  3345  3601 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1305-1307)
03-17 06:44:18.919  3345  3601 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 06:44:18.929  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:18.929  1017  1504 D SettingsProvider: name = mtp_open_session
,03-17 06:44:18.939  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:18.939  3345  3601 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:44:18.939  3345  3601 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 06:44:18.949  3370  3550 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 06:44:18.949  3370  3550 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 06:44:18.949  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:18.959  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:18.979  3730  3730 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-17 06:44:18.979  3730  3730 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:18.979  1017  1534 D ActivityManager: startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
03-17 06:44:18.979  1017  1534 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 06:44:18.979  1017  1534 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:18.979  1017  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:18.979  1017  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 06:44:18.989  1017  1523 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,03-17 06:44:18.989  3730  3730 D NPS_WSSNPS: [] Service onCreate!!
,03-17 06:44:18.989  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.989  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.989  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.989  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.009  3759  3759 E Zygote  : MountEmulatedStorage(),
03-17 06:44:19.009  3759  3759 E Zygote  : v2
,03-17 06:44:19.009  3759  3759 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:19.009  3759  3759 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:19.009  3759  3759 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:19.019  3759  3759 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:19.019  3759  3759 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 06:44:19.029  1017  1523 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3759 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:19.029  3708  3708 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-17 06:44:19.029  3708  3708 I testFeature: Feature.Feature(context)
03-17 06:44:19.029  3708  3708 I testFeature: Feature.readInternalDefaultXml()
03-17 06:44:19.029  3708  3708 I testFeature: ResetFeatureValue
,03-17 06:44:19.029  3708  3708 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 06:44:19.029  3708  3708 I CameraApp: CameraApp.getAppFeature()...
,03-17 06:44:19.039  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,03-17 06:44:19.039  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.039  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.039  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.039  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.059  3759  3759 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-17 06:44:19.059  3759  3759 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:19.059  3775  3775 E Zygote  : MountEmulatedStorage(),
03-17 06:44:19.059  1017  1029 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3775 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-17 06:44:19.059  1017  1029 I ActivityManager: Killing 3006:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
03-17 06:44:19.069  3775  3775 E Zygote  : v2
03-17 06:44:19.069  3775  3775 I libpersona: KNOX_SDCARD checking this for 10100
,03-17 06:44:19.069  3775  3775 I libpersona: KNOX_SDCARD not a persona,
03-17 06:44:19.069  3422  3422 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 06:44:19.069  3422  3422 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 06:44:19.069  3422  3422 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 06:44:19.069  3422  3422 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED,
03-17 06:44:19.069  3422  3422 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 06:44:19.069  3422  3422 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 06:44:19.069  3758  3758 I dex2oat : ----------------------------------------------------,
03-17 06:44:19.069  3758  3758 I dex2oat : <SS>: S T A R T I N G . . .
03-17 06:44:19.069  3758  3758 I dex2oat : <SS>: Zip is absent. Canceled.
03-17 06:44:19.069  3758  3758 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1093245448.jar --oat-fd=37 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1093245448.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 06:44:19.079  3775  3775 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:19.079  3775  3775 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:19.079  3775  3775 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:19.099  3370  3370 I System.out: YouTube MDX: MDX video stage moved to NEW,
,03-17 06:44:19.099  3775  3775 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:19.109  3775  3775 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:19.109  3759  3759 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:19.109  3370  3370 I System.out: YouTube MDX: MDX video player state moved to UNSTARTED
,03-17 06:44:19.109  3370  3370 I System.out: YouTube MDX: MDX ad player state moved to UNSTARTED
,03-17 06:44:19.129  3758  3758 I dex2oat : dex2oat took 57.041ms (threads: 4)
,03-17 06:44:19.129  3422  3422 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 06:44:19.139  3730  3730 D NPS_WSSNPS: [50.150621] smlDBHelper
,03-17 06:44:19.139  3730  3796 D NPS_WSSNPS: [50.150621] NpsServiceTask Start
,03-17 06:44:19.179  3775  3775 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 06:44:19.189  3730  3730 I NPS_WSSNPS: [50.150621] AsyncBulkFlagCheck
,03-17 06:44:19.189  3775  3775 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-17 06:44:19.189  1017  1523 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,03-17 06:44:19.189  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.199  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.199  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.199  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.199  3730  3803 I NPS_WSSNPS: [50.150621] IsRemain_AsyncBulkCheck
,03-17 06:44:19.199  3730  3803 I NPS_WSSNPS: [50.150621] IsRemain_Asyncing nothing
,03-17 06:44:19.199  3730  3803 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-17 06:44:19.209  3422  3422 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 06:44:19.209  3422  3422 I ReactiveServiceManager: Supported : 1
,03-17 06:44:19.209  1017  1030 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-17 06:44:19.219  1017  1030 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 06:44:19.219  3805  3805 E Zygote  : MountEmulatedStorage()
,03-17 06:44:19.219  3805  3805 E Zygote  : v2
03-17 06:44:19.219  3805  3805 I libpersona: KNOX_SDCARD checking this for 10101
03-17 06:44:19.219  3805  3805 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:19.219  3805  3805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:19.229  1017  1523 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3805 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 06:44:19.229  3805  3805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:19.229  3805  3805 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 06:44:19.229  1017  1523 I ActivityManager: Killing 3019:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,03-17 06:44:19.239  1017  1030 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 06:44:19.259  1017  1030 D QSEECOMAPI: : QSEECom_dealloc_memory 
,03-17 06:44:19.259  1017  1030 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-17 06:44:19.259  3805  3805 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:19.259  1017  1030 E terrier : handleString: Failed to handle string(-4)
,03-17 06:44:19.259  1017  1030 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-17 06:44:19.259  3805  3805 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:19.279  3422  3422 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 06:44:19.279  3422  3422 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 06:44:19.289  3422  3422 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 06:44:19.289  3422  3422 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 06:44:19.289  3422  3422 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 06:44:19.289  3422  3422 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 06:44:19.369  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2930/cgroup.procs: No such file or directory
03-17 06:44:19.369  1017  1041 W libprocessgroup: failed to open /acct/uid_1101/pid_2965/cgroup.procs: No such file or directory
,03-17 06:44:19.379  1017  1534 I art     : Explicit concurrent mark sweep GC freed 24700(1259KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/40MB, paused 2.731ms total 173.057ms
,03-17 06:44:19.409  1017  1532 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,03-17 06:44:19.409  1017  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.409  1017  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.409  1017  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.409  1017  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.409  1017  1041 W libprocessgroup: failed to open /acct/uid_10046/pid_2333/cgroup.procs: No such file or directory
,03-17 06:44:19.419  3823  3823 E Zygote  : MountEmulatedStorage(),
03-17 06:44:19.429  3823  3823 E Zygote  : v2
03-17 06:44:19.429  3823  3823 I libpersona: KNOX_SDCARD checking this for 10031,
03-17 06:44:19.429  3823  3823 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:19.429  1017  1532 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3823 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a,
03-17 06:44:19.429  1017  1532 I ActivityManager: Killing 2080:com.google.android.gms/u0a12 (adj 15): empty #31
03-17 06:44:19.429  1017  1041 W libprocessgroup: failed to open /acct/uid_10048/pid_3006/cgroup.procs: No such file or directory
03-17 06:44:19.429  1017  1488 D ActivityManager: bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
03-17 06:44:19.429  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0,
,03-17 06:44:19.429  3823  3823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:19.439  1017  1488 W ActivityManager: userId = 0, bbcId = -10000,
03-17 06:44:19.439  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:19.439  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:19.439  3823  3823 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 06:44:19.439  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 06:44:19.439  3823  3823 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:19.449  1017  1029 W ActivityManager: userId = 0, bbcId = -10000,
03-17 06:44:19.449  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:19.449  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 06:44:19.459  3730  3730 D NPS_WSSNPS: [50.150621] Service onDestroy
,03-17 06:44:19.469  1017  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:19.469  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:19.469  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:19.469  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 06:44:19.479  1017  1504 W ActivityManager: ProcessRecord{c2c1191 2080:com.google.android.gms/u0a12} is already killed
,03-17 06:44:19.479   254   254 E lowmemorykiller: Error writing /proc/2080/oom_score_adj; errno=22
,03-17 06:44:19.489  3823  3823 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:19.489  3823  3823 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:19.509  2590  2590 D FactoryTestApp: [DummyFtClient$onDestroy](2590) Destroy DummyFtClient service
,03-17 06:44:19.509  2590  2590 D FactoryTestApp: [Support$Values.getString](2590) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 06:44:19.509  2590  2590 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2590) mConnectionMode = gsm
03-17 06:44:19.509  2590  2590 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2590) RUNNING_FTCLIENT : false
03-17 06:44:19.509  2590  2590 D FactoryTestApp: [DummyFtClient$onDestroy](2590) kill process
03-17 06:44:19.509  2590  2590 I Process : Sending signal. PID: 2590 SIG: 9
,03-17 06:44:19.529  3823  3823 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 06:44:19.539  1017  3038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:19.539  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:19.539  1017  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:19.539  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 06:44:19.559  1017  1533 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:19.559  3730  3730 I NPS_WSSNPS: [50.150621] smlBRConfigurationDelete
03-17 06:44:19.559  3730  3730 I NPS_WSSNPS: [50.150621] smlBRMessageDelete
03-17 06:44:19.559  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:19.559  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:19.559  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
03-17 06:44:19.559  3730  3730 I NPS_WSSNPS: [50.150621] smlBREmailDelete
,03-17 06:44:19.559  3730  3730 I NPS_WSSNPS: [50.150621] smlBRNetworkDelete
,03-17 06:44:19.559  3730  3730 I NPS_WSSNPS: [50.150621] smlBRCallLogDelete
,03-17 06:44:19.569  3730  3730 I NPS_WSSNPS: [50.150621] smlBRMiniDiaryDelete
,03-17 06:44:19.569  3730  3730 I NPS_WSSNPS: [50.150621] smlBRPenMemoMDelete
,03-17 06:44:19.569  3730  3730 I NPS_WSSNPS: [50.150621] smlBRSMemoDelete
,03-17 06:44:19.569  3730  3730 I NPS_WSSNPS: [50.150621] verifier installed? false
03-17 06:44:19.569  3730  3730 I NPS_WSSNPS: [50.150621] cpuBooster release : false
,03-17 06:44:19.569  1017  1488 I ActivityManager: Process com.sec.factory (pid 2590)(adj 0) has died(100,1114)
03-17 06:44:19.569  3730  3730 D NPS_WSSNPS: [50.150621] dsServerSocket close
,03-17 06:44:19.579  1017  1504 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3aa52f01)
,03-17 06:44:19.579  1017  1145 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-17 06:44:19.579  1017  3038 I ActivityManager: Killing 3057:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,03-17 06:44:19.579   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 06:44:19.579   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:19.579  3370  3370 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 06:44:19.579  1017  1029 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.ads.identifier.service.AdvertisingIdService in 1000ms
,03-17 06:44:19.599  3345  3601 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:44:19.609  1017  1145 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-17 06:44:19.609  1801  3543 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 06:44:19.609  3178  3249 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 06:44:19.679  1017  1041 W libprocessgroup: failed to open /acct/uid_10157/pid_3019/cgroup.procs: No such file or directory
,03-17 06:44:19.679  1017  1041 W libprocessgroup: failed to open /acct/uid_10012/pid_2080/cgroup.procs: No such file or directory
,03-17 06:44:19.679  1017  1041 W libprocessgroup: failed to open /acct/uid_10159/pid_3057/cgroup.procs: No such file or directory
,03-17 06:44:19.729  1017  1523 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,03-17 06:44:19.729  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.729  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.729  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.729  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.749  3855  3855 E Zygote  : MountEmulatedStorage(),
03-17 06:44:19.749  3855  3855 E Zygote  : v2
03-17 06:44:19.749  3855  3855 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 06:44:19.749  3855  3855 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:19.749  3855  3855 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:19.749  1017  1523 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3855 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:19.749  1017  1523 I ActivityManager: Killing 1577:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
03-17 06:44:19.749  3855  3855 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:19.749  3855  3855 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:19.779  3855  3855 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:19.779  3855  3855 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:19.799  3380  3641 I System.out: pool-10-thread-1 calls detatch()
,03-17 06:44:19.839  1017  1041 W libprocessgroup: failed to open /acct/uid_10072/pid_1577/cgroup.procs: No such file or directory
,03-17 06:44:19.859   274   977 D EnterpriseController: uids 10057
03-17 06:44:19.859   274   977 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 06:44:19.859   274   977 D Netd    : getNetworkForDns: using netid 502 for uid 10057
,03-17 06:44:19.869  1017  1523 D SettingsProvider: name = access_control_enabled
,03-17 06:44:19.869  1017  3038 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,03-17 06:44:19.869  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.869  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.879  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.879  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-17 06:44:19.899  3879  3879 E Zygote  : MountEmulatedStorage(),
,03-17 06:44:19.899  3879  3879 E Zygote  : v2
,03-17 06:44:19.899  3879  3879 I libpersona: KNOX_SDCARD checking this for 10069
03-17 06:44:19.899  3879  3879 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:19.899  3879  3879 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:19.899  3879  3879 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:19.899  3879  3879 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:19.909  1017  3038 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3879 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:44:19.909  3823  3823 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,03-17 06:44:19.909  1017  3038 I ActivityManager: Killing 3041:com.sec.dsm.system/1000 (adj 15): empty #31
,03-17 06:44:19.929   302   302 I art     : Explicit concurrent mark sweep GC freed 8783(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 20.867ms
,03-17 06:44:19.929  3879  3879 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:19.929  3879  3879 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:19.949   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 22.657ms
,03-17 06:44:19.959  3823  3823 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,03-17 06:44:19.969   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 16.974ms
,03-17 06:44:20.009  3879  3879 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 06:44:20.019  3268  3310 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 06:44:20.029  3268  3310 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 06:44:20.029  3268  3310 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 06:44:20.029  3268  3310 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 06:44:20.029  3268  3310 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 06:44:20.029  3268  3310 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 06:44:20.029  3268  3310 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 06:44:20.049  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3041/cgroup.procs: No such file or directory
,03-17 06:44:20.049  3268  3284 I art     : WaitForGcToComplete blocked for 20.300ms for cause HomogeneousSpaceCompact
,03-17 06:44:20.119  3823  3823 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 06:44:20.119  3823  3823 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 06:44:20.139  3823  3823 D DialogFlow: initQueue()
,03-17 06:44:20.169  1017  1263 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 06:44:20.169  1017  1348 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,03-17 06:44:20.179  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.179  1017  1504 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 06:44:20.179  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.179  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.179  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.189  1017  1348 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3900 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,03-17 06:44:20.189  1017  1348 I ActivityManager: Killing 3086:com.sec.usbsettings/1000 (adj 15): empty #31
,03-17 06:44:20.199  1017  1523 I AudioService: getStreamVolume 3 index 0
,03-17 06:44:20.199  3900  3900 E Zygote  : MountEmulatedStorage()
03-17 06:44:20.199  3900  3900 E Zygote  : v2
03-17 06:44:20.199  3900  3900 I libpersona: KNOX_SDCARD checking this for 10032
03-17 06:44:20.199  3900  3900 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.209  3900  3900 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:20.209  3900  3900 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:20.209  3900  3900 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:20.209  1017  1501 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 06:44:20.209  1017  1501 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 06:44:20.239  3900  3900 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:20.239  3900  3900 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.299  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3086/cgroup.procs: No such file or directory
,03-17 06:44:20.389  1017  1501 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,03-17 06:44:20.389  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.389  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.389  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.389  1017  1501 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.409  3926  3926 E Zygote  : MountEmulatedStorage()
03-17 06:44:20.409  3926  3926 E Zygote  : v2
03-17 06:44:20.409  3926  3926 I libpersona: KNOX_SDCARD checking this for 10033
03-17 06:44:20.409  3926  3926 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.409  3926  3926 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:20.409  1017  1501 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3926 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 06:44:20.409  1017  1501 I ActivityManager: Killing 3103:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
03-17 06:44:20.409  3926  3926 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:20.409  3926  3926 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 06:44:20.419   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 06:44:20.419   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:20.429  3805  3921 I Gmail   : getAccountsCursor
,03-17 06:44:20.429  3370  3370 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 06:44:20.429  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:20.429   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 06:44:20.429   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:20.429  3370  3370 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 06:44:20.439   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 06:44:20.439   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:20.439  3370  3370 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 06:44:20.439  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.439  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.439  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.439  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.439  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.439  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.439  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.459  3946  3946 E Zygote  : MountEmulatedStorage()
03-17 06:44:20.459  3946  3946 E Zygote  : v2
03-17 06:44:20.459  3946  3946 I libpersona: KNOX_SDCARD checking this for 10012
03-17 06:44:20.459  3946  3946 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.459  3946  3946 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:20.459  3926  3926 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:20.459  3926  3926 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.459  3946  3946 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:20.469  3946  3946 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:20.469  1017  1029 I ActivityManager: Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=3946 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-17 06:44:20.469  1017  1263 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-17 06:44:20.469  1017  1263 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.479  1818  1818 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:20.489  1017  1488 I ActivityManager: Killing 2986:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,03-17 06:44:20.499  3946  3946 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:20.499  3946  3946 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.509  1017  1017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 06:44:20.509  1017  1017 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-17 06:44:20.509  1017  1017 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:20.519  1017  1151 I ActivityManager: Killing 3156:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-17 06:44:20.519  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,03-17 06:44:20.529  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.529  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.529  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.529  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.529  3805  3805 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 06:44:20.539  3963  3963 E Zygote  : MountEmulatedStorage(),
03-17 06:44:20.539  3963  3963 E Zygote  : v2
03-17 06:44:20.539  3963  3963 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:20.539  3963  3963 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.539  3963  3963 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:20.549  1017  1017 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3963 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:20.549  3963  3963 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:20.549  3946  3946 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 06:44:20.549  3946  3946 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-17 06:44:20.549  3963  3963 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:20.579  1017  3038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.579  1017  3038 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 06:44:20.589  3963  3963 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:20.589  3963  3963 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.609  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-17 06:44:20.609  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.609  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.609  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.609  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:20.609  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 06:44:20.609  1017  1029 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 06:44:20.609  3805  3978 I Gmail   : Observing account changes for notifications
,03-17 06:44:20.619  3178  3249 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 06:44:20.679  1017  1504 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-17 06:44:20.679  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.679  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.679  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.679  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 06:44:20.689  1017  1151 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-17 06:44:20.689  1017  1151 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.689  1017  1151 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.689  1017  1151 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.689  1017  1151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:20.699  3963  3963 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:20.709  1017  1348 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-17 06:44:20.709  1017  1348 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.709  1017  1348 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.709  1017  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.709  1017  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 06:44:20.719  1017  1501 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,03-17 06:44:20.719  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.719  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.719  1017  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:20.719  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 06:44:20.729  1017  1263 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 06:44:20.729  1017  1263 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 06:44:20.729  1017  1151 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,03-17 06:44:20.729  3946  3946 I MultiDex: VM with version 2.1.0 has multidex support
03-17 06:44:20.729  3946  3946 I MultiDex: install
03-17 06:44:20.729  3946  3946 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 06:44:20.739  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.739  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.739  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.739  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.749  4002  4002 E Zygote  : MountEmulatedStorage()
,03-17 06:44:20.749  4002  4002 E Zygote  : v2
03-17 06:44:20.749  4002  4002 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 06:44:20.749  4002  4002 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.759  4002  4002 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:20.759  4002  4002 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:20.759  1017  1151 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=4002 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:20.759  4002  4002 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:20.769  3805  4000 E Gmail   : Error finding the version of the Email provider.....
03-17 06:44:20.769  3805  4000 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 06:44:20.769  3805  4000 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 06:44:20.769  3805  4000 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
03-17 06:44:20.769  3805  4000 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-17 06:44:20.769  3805  4000 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 06:44:20.769  3805  4000 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:20.769  3805  4000 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:20.769  3805  4000 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 06:44:20.769  3805  4000 W EmailMigration: We do not support migrating this version of the Email provider.
,03-17 06:44:20.779  3926  3926 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 06:44:20.779  3926  3926 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:20.779  3926  3926 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 06:44:20.789  1017  1534 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-17 06:44:20.789  1017  1534 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.789  1017  1534 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.789  1017  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.789  1017  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 06:44:20.799  4002  4002 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:20.799  4002  4002 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.809  1017  1532 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-17 06:44:20.809  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.809  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.819  1017  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.819  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 06:44:20.819  1017  1348 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-17 06:44:20.819  1017  1348 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.819  3805  4017 I Gmail   : getAccountsCursor
,03-17 06:44:20.829  1818  1818 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:20.829  4002  4002 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-17 06:44:20.839  1017  1501 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-17 06:44:20.839  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.839  1017  1523 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
03-17 06:44:20.839  1017  1523 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.849  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.849  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.849  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-17 06:44:20.869  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,03-17 06:44:20.869  3926  3926 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:44:20.869  3926  3926 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:20.869  3926  3926 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:20.879  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.879  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.879  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.879  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.889  4025  4025 E Zygote  : MountEmulatedStorage()
03-17 06:44:20.889  4025  4025 E Zygote  : v2
03-17 06:44:20.889  4025  4025 I libpersona: KNOX_SDCARD checking this for 10104
03-17 06:44:20.889  4025  4025 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.889  4025  4025 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:20.899  4025  4025 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:20.899  1017  1488 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4025 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-17 06:44:20.899  4025  4025 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:20.899  1017  3038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 06:44:20.899  1017  3038 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 06:44:20.909  3926  3926 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 06:44:20.909  3926  3926 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-17 06:44:20.909  3926  3926 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 06:44:20.919  1660  4023 I GoogleHttpClient: GMS http client unavailable, use old client
,03-17 06:44:20.929  4025  4025 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:20.929  4025  4025 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.969  1017  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 06:44:20.969  1017  1488 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 06:44:20.969  3805  3805 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@3ec1be50 that was originally bound here
03-17 06:44:20.969  3805  3805 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@3ec1be50 that was originally bound here
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at com.android.emailcommon.service.ah.a(SourceFile:181)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at com.android.emailcommon.service.ah.e(SourceFile:224)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:161)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:173)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:117)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:20.969  3805  3805 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 06:44:20.969  1017  1348 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@10446f8f
,03-17 06:44:20.989  4025  4025 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 06:44:21.009  3805  4018 E SQLiteLog: (283) recovered 22 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 06:44:21.059  1017  1348 I ActivityManager: Killing 3216:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,03-17 06:44:21.059  1017  1523 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 06:44:21.129  1017  2712 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-17 06:44:21.159  1017  1029 D TimaService: TIMA: in getTimaVersion
,03-17 06:44:21.159  1017  1030 D TimaService: TIMA3: KeyStore3_init
03-17 06:44:21.159  1017  1030 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize()
03-17 06:44:21.159  1017  1030 D TimaService: TIMA: in getTimaVersion
03-17 06:44:21.159  1017  1030 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-17 06:44:21.159  1017  1030 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-17 06:44:21.159  1017  1030 I TLC_TZ_KEYSTORE: : root = /firmware/image, root_strlen = 15
03-17 06:44:21.159  1017  1030 I TLC_TZ_KEYSTORE: : process = tima_key, process_strlen = 8
03-17 06:44:21.159  1017  1030 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-17 06:44:21.159  1017  1030 I TZ: qc_tlc_communication: process = tima_key, process_strlen = 8
03-17 06:44:21.159  1017  1030 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 1088 = 0x440
03-17 06:44:21.159  1017  1030 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 1088 = 0x440
03-17 06:44:21.159  1017  1030 I TZ: qc_tlc_communication: max_message_size = 2176 = 0x880
03-17 06:44:21.159  1017  1030 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x880
03-17 06:44:21.159  1017  1030 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 06:44:21.169  1017  1504 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-17 06:44:21.169  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.169  3946  3946 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 06:44:21.179  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:21.179  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:21.179  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:21.179  1017  1501 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-17 06:44:21.179  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.179  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.179  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:21.179  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:21.189  1017  1030 D QSEECOMAPI: : Loaded image: APP id = 10
,03-17 06:44:21.189  1017  1030 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
,03-17 06:44:21.189  1017  1030 I TLC_TZ_KEYSTORE: : ctx = 0xb892da28, comm = 0xb8a47998, sendmsg = 0xa0882000, recvmsg = 0xa0882440
03-17 06:44:21.189  1017  1030 I TZ_init: : TZ_init: sending initialization request...
,03-17 06:44:21.189  1017  1030 E TZ_init: : TZ_init Process: Secure memory is not initialized!
,03-17 06:44:21.189  1017  1030 E TZ_init: : trustlet initialization failed
,03-17 06:44:21.189  1017  1030 I TZ_init: : TZ_init_START...
,03-17 06:44:21.199  1017  1533 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-17 06:44:21.199  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.199  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:21.209  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:21.209  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:21.209  1017  1030 I TZ_init: : TZ_init_with_data: sending initialization request...
,03-17 06:44:21.209  1017  1030 I TZ_init: : TZ_init: successful initialization
,03-17 06:44:21.209  1017  1030 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 06:44:21.209  1017  1030 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-17 06:44:21.209  1017  1030 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,03-17 06:44:21.219  3805  4018 E File    : fail readDirectory() errno=2
,03-17 06:44:21.249  1947  1947 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:21.249  1017  1488 D ActivityManager: startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
,03-17 06:44:21.249  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.259  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.259  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.259  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-17 06:44:21.269  1947  1947 D SecUISvc: Service started flags 0 startId 1
,03-17 06:44:21.269  1017  1533 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,03-17 06:44:21.269  1947  4050 D SecUISvc: Thread created.
03-17 06:44:21.269  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.269  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.269  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.269  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.269  3805  4041 I Gmail   : notifyAccountChanged
,03-17 06:44:21.269  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-17 06:44:21.269  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:21.269  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 06:44:21.269  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-17 06:44:21.269  3963  4008 I AMMetaDataParserService: Resource data:2131165186
,03-17 06:44:21.279  3963  4008 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 06:44:21.279  3963  4008 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:21.279  3963  4008 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 06:44:21.279  3963  4008 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:44:21.289  3963  4008 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-17 06:44:21.289  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:21.299  1017  1533 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4053 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:21.299  4053  4053 E Zygote  : MountEmulatedStorage()
03-17 06:44:21.299  4053  4053 E Zygote  : v2
03-17 06:44:21.299  4053  4053 I libpersona: KNOX_SDCARD checking this for 10028
03-17 06:44:21.299  4053  4053 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:21.299  4053  4053 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:21.309  4053  4053 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:21.309  4053  4053 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:21.309  3805  4041 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 06:44:21.329  3963  4008 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,03-17 06:44:21.329  1017  1533 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-17 06:44:21.329  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.329  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.329  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:21.329  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:21.339  4053  4053 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.339  4053  4053 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:21.339  3946  3946 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 06:44:21.339  3946  3946 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@82899e0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 06:44:21.339  3946  3946 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 06:44:21.339   287   287 E SMD     : DCD OFF
,03-17 06:44:21.389  3963  4008 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-17 06:44:21.389  4002  4002 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,03-17 06:44:21.399  1017  2712 D SSRM:n  : SIOP:: AP = 370
,03-17 06:44:21.449  3963  4008 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,03-17 06:44:21.489  3805  4041 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-17 06:44:21.509  3963  4008 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.,SelectBookmarkFolderActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-17 06:44:21.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,03-17 06:44:21.529  1017  1029 I art     : Explicit concurrent mark sweep GC freed 26962(1665KB) AllocSpace objects, 5(86KB) LOS objects, 33% free, 27MB/40MB, paused 27.833ms total 188.752ms
,03-17 06:44:21.539  1017  1501 D ActivityManager: startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
03-17 06:44:21.539  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.539  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:21.539  1017  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:21.539  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,03-17 06:44:21.539  3805  4041 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 06:44:21.549  3805  4041 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 06:44:21.569  1017  1263 I ActivityManager: Killing 3251:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-17 06:44:21.569  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
,03-17 06:44:21.569  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 06:44:21.569  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 06:44:21.579  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700",
03-17 06:44:21.579  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:21.579  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
03-17 06:44:21.579  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:21.579  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:21.579  1017  1029 W ActivityManager: userId = 0, bbcId = -10000,
03-17 06:44:21.579  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:21.579  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 06:44:21.589  3926  3926 I Process : Sending signal. PID: 3926 SIG: 9,
03-17 06:44:21.589  1017  1532 D ActivityManager: startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
03-17 06:44:21.589  1818  1818 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:21.599  1017  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 06:44:21.599  1017  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.599  1017  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.599  1017  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.599  1818  1818 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:21.609  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity,
03-17 06:44:21.609  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:21.609  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:21.609  3963  4008 I AMMetaDataParserService: Resource data:2131034113
,03-17 06:44:21.609  1017  1532 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4082 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-17 06:44:21.619  4082  4082 E Zygote  : MountEmulatedStorage()
03-17 06:44:21.619  4082  4082 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:21.619  4082  4082 E Zygote  : v2
03-17 06:44:21.619  4082  4082 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:21.619  4082  4082 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:21.619  4082  4082 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:21.619  3178  3249 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 06:44:21.629  4082  4082 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:21.629  3963  4008 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 06:44:21.629  3963  4008 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:21.639  3963  4008 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-17 06:44:21.639  3963  4008 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 06:44:21.639  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:21.639  4082  4082 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.649  4082  4082 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.649  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:21.679  3963  4008 I GFX construct_block_size_descriptor_2d second part: took 2.666770ms for 0*0 texture 0
,03-17 06:44:21.679  4082  4082 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 06:44:21.689  3963  4008 I GFX generate_partition_tables: took 6.252396ms for 0*0 texture 0
,03-17 06:44:21.689  3963  4008 I GFX raster: took 10.155937ms for 96*96 texture 0
03-17 06:44:21.689  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb839c7c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb839cb48 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:21.709  1017  1504 W SEAMService:  hashset_to_int_array returning null
,03-17 06:44:21.729  1017  1533 W SEAMService:  hashset_to_int_array returning null
,03-17 06:44:21.729  4082  4082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:21.739  4002  4002 E SQLiteLog: (284) automatic index on seams_container_info(seams_container_id)
,03-17 06:44:21.739  1017  1151 I ActivityManager: Process com.sec.android.app.sns3 (pid 3926)(adj 0) has died(45,1140)
,03-17 06:44:21.739  1017  1532 D ActivityManager: startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
,03-17 06:44:21.739  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.749  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:21.749  1017  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.749  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-17 06:44:21.749  3946  4075 D NativeLibraryUtils: Install completed successfully. count=14 extracted=0
,03-17 06:44:21.749  4002  4002 E SQLiteLog: (284) automatic index on seams_container_info(sp_id)
,03-17 06:44:21.749  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,03-17 06:44:21.749  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.749  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.749  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.749  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.759  3963  4008 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 06:44:21.769  1017  1151 W SEAMService:  hashset_to_int_array returning null
,03-17 06:44:21.769  1017  1042 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4103 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,03-17 06:44:21.779  4103  4103 E Zygote  : MountEmulatedStorage()
03-17 06:44:21.779  4103  4103 E Zygote  : v2
03-17 06:44:21.779  4103  4103 I libpersona: KNOX_SDCARD checking this for 10034
03-17 06:44:21.779  4103  4103 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:21.779  4103  4103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:21.779  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:21.779  4103  4103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:21.779  4103  4103 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:21.789  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.789  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:21.789  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:21.809  4082  4082 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-17 06:44:21.809  4082  4082 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-17 06:44:21.809  4103  4103 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:21.809  1017  1534 D ActivityManager: bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
03-17 06:44:21.809  4103  4103 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:21.809  1017  1534 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
03-17 06:44:21.809  1017  1534 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.809  1017  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.809  1017  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-17 06:44:21.839  4082  4082 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-17 06:44:21.839  4082  4082 I F_PHONE : default registerAction()
03-17 06:44:21.839  4082  4082 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 06:44:21.849  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:21.849  3963  4008 I GFX raster: took 0.855155ms for 96*96 texture 0
03-17 06:44:21.849  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb839c7c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83a4b88 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:21.859  1017  2828 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:44:21.859  3963  4008 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 06:44:21.879  3370  4099 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
03-17 06:44:21.879  3370  4099 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 06:44:21.879  3370  4099 I System.out: Thread-498(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 06:44:21.879  3370  4099 I System.out: Thread-498(ApacheHTTPLog):isSBSettingEnabled false
03-17 06:44:21.879  3370  4099 I System.out: Thread-498(ApacheHTTPLog):isShipBuild true
03-17 06:44:21.879  3370  4099 I System.out: Thread-498(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 06:44:21.879  3370  4099 I System.out: Thread-498(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 06:44:21.879  1017  1041 W libprocessgroup: failed to open /acct/uid_10085/pid_2986/cgroup.procs: No such file or directory
03-17 06:44:21.879  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3103/cgroup.procs: No such file or directory
03-17 06:44:21.879  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3156/cgroup.procs: No such file or directory
03-17 06:44:21.879  1017  1041 W libprocessgroup: failed to open /acct/uid_10150/pid_3216/cgroup.procs: No such file or directory
03-17 06:44:21.879  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3251/cgroup.procs: No such file or directory
,03-17 06:44:21.879   274   977 D EnterpriseController: uids 10166
03-17 06:44:21.879   274   977 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 06:44:21.879   274   977 D Netd    : getNetworkForDns: using netid 502 for uid 10166
,03-17 06:44:21.959  1660  1731 I art     : Explicit concurrent mark sweep GC freed 3965(179KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 709us total 45.424ms
,03-17 06:44:21.969  3900  3916 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 06:44:21.969  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:21.979  1660  1675 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-17 06:44:21.989  3963  4008 I GFX construct_block_size_descriptor_2d second part: took 2.495261ms for 0*0 texture 0
,03-17 06:44:21.989  3963  4008 I GFX generate_partition_tables: took 7.787552ms for 0*0 texture 0
,03-17 06:44:22.019  3963  4008 I GFX raster: took 11.441927ms for 96*96 texture 0
03-17 06:44:22.019  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a1300 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a13a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.029  3963  4008 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 06:44:22.049  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,03-17 06:44:22.049  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.049  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.049  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.049  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.059  3900  3916 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
03-17 06:44:22.059  3900  3916 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:22.059  3900  3916 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,03-17 06:44:22.069  4133  4133 E Zygote  : MountEmulatedStorage()
03-17 06:44:22.069  4133  4133 E Zygote  : v2
03-17 06:44:22.069  4133  4133 I libpersona: KNOX_SDCARD checking this for 10035
03-17 06:44:22.069  4133  4133 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:22.069  4133  4133 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:22.069  4133  4133 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 06:44:22.069  1017  1029 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4133 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:44:22.069  4133  4133 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 06:44:22.099  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:22.099  3963  4008 I GFX raster: took 0.610104ms for 96*96 texture 0
,03-17 06:44:22.099  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb839f950 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb839f9f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.109  3963  4008 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 06:44:22.109  4133  4133 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:22.109  4133  4133 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:22.139  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:22.139  3963  4008 I GFX raster: took 0.838229ms for 96*96 texture 0
03-17 06:44:22.139  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a2988 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a2ae0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.139  3963  4008 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 06:44:22.169  4025  4151 I Babel   : MmsConfig: mnc/mcc: 0/0
,03-17 06:44:22.169  4025  4151 I Babel   : MmsConfig.loadMmsSettings
,03-17 06:44:22.169  4025  4151 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
03-17 06:44:22.169  4025  4151 I Babel   : MmsConfig.loadFromDatabase
,03-17 06:44:22.209  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:22.219  3963  4008 I GFX raster: took 0.646407ms for 96*96 texture 0
,03-17 06:44:22.219  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a61d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a6330 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.229  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 06:44:22.239  4025  4151 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,03-17 06:44:22.239  4025  4151 I Babel   : MmsConfig.loadFromResources
,03-17 06:44:22.239  4133  4152 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
03-17 06:44:22.239  4133  4152 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-17 06:44:22.239  4025  4151 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,03-17 06:44:22.239  4025  4151 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,03-17 06:44:22.239  4133  4133 E SPPClientService: [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,03-17 06:44:22.249  1017  1533 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,03-17 06:44:22.249  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,03-17 06:44:22.249  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:22.249  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:22.249  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 06:44:22.259  1017  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-17 06:44:22.259  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 06:44:22.259  1818  1818 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:22.269  4025  4025 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 06:44:22.279  3805  4155 I Gmail   : getAccountsCursor
,03-17 06:44:22.279  4053  4053 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 06:44:22.279  1017  1029 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-17 06:44:22.289  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 06:44:22.289  1818  1818 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:22.289  4133  4152 D SPPClientService: PushLog.txt file is not deleted.
03-17 06:44:22.289  4133  4152 D SPPClientService: PushLog.txt file is not deleted.
03-17 06:44:22.289  4133  4152 D SPPClientService: ============PushLog. stop!
,03-17 06:44:22.309  3805  3921 I Gmail   : getAccountsCursor
,03-17 06:44:22.319  1017  1501 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-17 06:44:22.319  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 06:44:22.319  1818  1818 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:22.329  1017  1533 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,03-17 06:44:22.339  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.339  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.339  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.339  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-17 06:44:22.359  1017  1533 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4161 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:22.359  1017  1533 I ActivityManager: Killing 3290:com.google.android.configupdater/u0a86 (adj 15): empty #31
,03-17 06:44:22.359  4161  4161 E Zygote  : MountEmulatedStorage()
03-17 06:44:22.359  4161  4161 I libpersona: KNOX_SDCARD checking this for 10041
03-17 06:44:22.359  4161  4161 E Zygote  : v2
03-17 06:44:22.359  4161  4161 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:22.359  4161  4161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:22.369  4161  4161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:22.369  4161  4161 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 06:44:22.389   302   302 I art     : Explicit concurrent mark sweep GC freed 8742(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 32.017ms
,03-17 06:44:22.389  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 06:44:22.389  3963  4008 I GFX raster: took 0.694115ms for 96*96 texture 0
03-17 06:44:22.389  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a1168 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a0ec0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.399  3963  4008 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534,
,03-17 06:44:22.409   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 17.446ms,
,03-17 06:44:22.429   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 17.268ms,
,03-17 06:44:22.449  3370  4099 I System.out: Thread-498 calls detatch()
,03-17 06:44:22.459  4161  4161 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:22.459  4161  4161 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:22.469  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:22.469  3963  4008 I GFX raster: took 0.541458ms for 96*96 texture 0
03-17 06:44:22.469  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a0ec0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a2340 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.469  3963  4008 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 06:44:22.479  4025  4025 I Babel_StickerModule: App launched.
,03-17 06:44:22.509  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-17 06:44:22.509  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:22.509  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:22.509  3963  4008 I AMMetaDataParserService: Resource data:2131034113
,03-17 06:44:22.509  3963  4008 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 06:44:22.509  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:22.509  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:22.509  3963  4008 I GFX raster: took 0.814583ms for 96*96 texture 0
03-17 06:44:22.509  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb839c7c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83a1d10 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.539  3963  4008 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 06:44:22.539  1017  1041 W libprocessgroup: failed to open /acct/uid_10086/pid_3290/cgroup.procs: No such file or directory
,03-17 06:44:22.559  4025  4025 V Babel   : babel boot account: SMS
,03-17 06:44:22.569  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 06:44:22.569  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,03-17 06:44:22.579  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:22.579  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:22.579  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:22.579  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:22.589  4025  4025 W Babel   : EsDatabaseHelper.static should not be called on main thread [called on main thread]
,03-17 06:44:22.589  4025  4025 W Babel   : java.lang.Exception
03-17 06:44:22.589  4025  4025 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-17 06:44:22.589  4025  4025 W Babel   : 	at aes.<clinit>(SourceFile:95)
03-17 06:44:22.589  4025  4025 W Babel   : 	at ckh.<init>(SourceFile:103)
03-17 06:44:22.589  4025  4025 W Babel   : 	at ckh.a(SourceFile:67)
03-17 06:44:22.589  4025  4025 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-17 06:44:22.589  4025  4025 W Babel   : 	at bhn.a(SourceFile:301)
03-17 06:44:22.589  4025  4025 W Babel   : 	at bhn.a(SourceFile:137)
03-17 06:44:22.589  4025  4025 W Babel   : 	at bhn.a(SourceFile:126)
03-17 06:44:22.589  4025  4025 W Babel   : 	at bhn.a(SourceFile:159)
03-17 06:44:22.589  4025  4025 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-17 06:44:22.589  4025  4025 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 06:44:22.589  4025  4025 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 06:44:22.589  4025  4025 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 06:44:22.589  4025  4025 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:22.589  4025  4025 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:22.589  4025  4025 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:22.589  4025  4025 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:22.589  4025  4025 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:22.589  4025  4025 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:22.589  4025  4025 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 06:44:22.589  4025  4025 W Babel   : EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,03-17 06:44:22.589  4025  4025 W Babel   : java.lang.Exception
03-17 06:44:22.589  4025  4025 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-17 06:44:22.589  4025  4025 W Babel   : 	at aes.a(SourceFile:145)
03-17 06:44:22.589  4025  4025 W Babel   : 	at ckh.<init>(SourceFile:103)
03-17 06:44:22.589  4025  4025 W Babel   : 	at ckh.a(SourceFile:67)
03-17 06:44:22.589  4025  4025 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-17 06:44:22.589  4025  4025 W Babel   : 	at bhn.a(SourceFile:301)
03-17 06:44:22.589  4025  4025 W Babel   : 	at bhn.a(SourceFile:137)
03-17 06:44:22.589  4025  4025 W Babel   : 	at bhn.a(SourceFile:126)
03-17 06:44:22.589  4025  4025 W Babel   : 	at bhn.a(SourceFile:159)
03-17 06:44:22.589  4025  4025 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-17 06:44:22.589  4025  4025 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 06:44:22.589  4025  4025 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 06:44:22.589  4025  4025 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 06:44:22.589  4025  4025 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:22.589  4025  4025 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:22.589  4025  4025 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:22.589  4025  4025 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:22.589  4025  4025 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:22.589  4025  4025 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:22.589  4025  4025 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 06:44:22.609  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:22.609  3963  4008 I GFX raster: took 0.831302ms for 96*96 texture 0
,03-17 06:44:22.609  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb839c7c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83a5ee0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.619  3963  4008 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 06:44:22.629  4161  4161 I SA      : [SSP] onCreated
,03-17 06:44:22.639  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:22.639  3963  4008 I GFX raster: took 0.619480ms for 96*96 texture 0
,03-17 06:44:22.639  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a1300 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a14f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.649  3178  3249 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-17 06:44:22.649  3963  4008 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 06:44:22.659  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-17 06:44:22.659  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 06:44:22.659  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:22.659  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:22.659  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 06:44:22.669  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 06:44:22.669  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 06:44:22.669  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:22.669  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:22.669  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 06:44:22.669  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 06:44:22.669  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 06:44:22.679  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:22.679  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:22.679  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 06:44:22.679  4025  4025 V Babel   : babel boot account: thalitester@gmail.com
,03-17 06:44:22.689  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:22.689  3963  4008 I GFX raster: took 0.633177ms for 96*96 texture 0
,03-17 06:44:22.689  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb839f950 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a5ee0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.699  4025  4025 W Babel   : EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,03-17 06:44:22.699  4025  4025 W Babel   : java.lang.Exception
03-17 06:44:22.699  4025  4025 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-17 06:44:22.699  4025  4025 W Babel   : 	at aes.a(SourceFile:145)
03-17 06:44:22.699  4025  4025 W Babel   : 	at ckh.<init>(SourceFile:103)
03-17 06:44:22.699  4025  4025 W Babel   : 	at ckh.a(SourceFile:67)
03-17 06:44:22.699  4025  4025 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-17 06:44:22.699  4025  4025 W Babel   : 	at bhn.a(SourceFile:301)
03-17 06:44:22.699  4025  4025 W Babel   : 	at bhn.a(SourceFile:137)
03-17 06:44:22.699  4025  4025 W Babel   : 	at bhn.a(SourceFile:126)
03-17 06:44:22.699  4025  4025 W Babel   : 	at bhn.a(SourceFile:159)
03-17 06:44:22.699  4025  4025 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-17 06:44:22.699  4025  4025 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 06:44:22.699  4025  4025 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 06:44:22.699  4025  4025 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 06:44:22.699  4025  4025 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:22.699  4025  4025 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:22.699  4025  4025 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:22.699  4025  4025 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:22.699  4025  4025 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:22.699  4025  4025 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:22.699  4025  4025 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 06:44:22.709  3963  4008 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 06:44:22.719  4161  4161 I SA      : [TPM] There is no property file
,03-17 06:44:22.729  4161  4161 I SA      : [SCU] isHaveSA() - false
,03-17 06:44:22.729  4161  4161 I SA      : [TPM] getModelProperty : null
,03-17 06:44:22.729  4161  4161 I SA      : [TPM] getCSCProperty : null
,03-17 06:44:22.739  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:22.739  3963  4008 I GFX raster: took 0.821563ms for 96*96 texture 0
03-17 06:44:22.739  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a2988 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a4628 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.749  4161  4161 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-17 06:44:22.749  4161  4161 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-17 06:44:22.749  4161  4161 I SA      : [DM] TFT FEATURE: false
,03-17 06:44:22.749  3963  4008 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 06:44:22.759  4161  4161 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
03-17 06:44:22.759  4161  4161 I SA      : [DM] init START
,03-17 06:44:22.759  4161  4161 I SA      : [DM] This device is not a Vodafone
,03-17 06:44:22.769  4161  4161 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,03-17 06:44:22.769  4161  4161 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,03-17 06:44:22.769  4161  4161 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
03-17 06:44:22.769  4161  4161 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
03-17 06:44:22.769  4161  4161 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,03-17 06:44:22.769  4161  4161 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,03-17 06:44:22.769  4161  4161 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,03-17 06:44:22.769  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:22.779  3963  4008 I GFX raster: took 0.849375ms for 96*96 texture 0
03-17 06:44:22.779  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a61d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83a26b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.779  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 06:44:22.789  4161  4161 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-17 06:44:22.789  4161  4161 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,03-17 06:44:22.789  4161  4161 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,03-17 06:44:22.789  4161  4161 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,03-17 06:44:22.789  4161  4161 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
03-17 06:44:22.789  4053  4053 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
03-17 06:44:22.789  4161  4161 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,03-17 06:44:22.789  4161  4161 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,03-17 06:44:22.789  4161  4161 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
03-17 06:44:22.789  4161  4161 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,03-17 06:44:22.789  4161  4161 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,03-17 06:44:22.789  4161  4161 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-17 06:44:22.789  4161  4161 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-17 06:44:22.789  4161  4161 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,03-17 06:44:22.799  1017  1504 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 06:44:22.799  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 06:44:22.799  4161  4161 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,03-17 06:44:22.799  4161  4161 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
03-17 06:44:22.799  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:22.799  4161  4161 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
03-17 06:44:22.799  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:22.799  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
03-17 06:44:22.799  4161  4161 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,03-17 06:44:22.799  4161  4161 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,03-17 06:44:22.799  1017  3038 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-17 06:44:22.799  1017  3038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 06:44:22.799  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:22.799  1017  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:22.799  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 06:44:22.799  1017  1151 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-17 06:44:22.799  1017  1151 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 06:44:22.799  1017  1151 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:22.799  1017  1151 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:22.799  1017  1151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 06:44:22.809  4161  4161 I SA      : [SCU] isHaveSA() - false,
,03-17 06:44:22.809  4161  4161 I SA      : support phone number id : false
03-17 06:44:22.809  1017  1151 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
03-17 06:44:22.809  4161  4161 I SA      : [DM] Supports Ref Jpn : true
03-17 06:44:22.809  4161  4161 I SA      : [DM] init END
,03-17 06:44:22.809  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.809  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.809  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.809  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.809  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:22.809  3963  4008 I GFX raster: took 0.838020ms for 96*96 texture 0
03-17 06:44:22.809  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83566f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb837d020 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.819  3963  4008 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 06:44:22.829  4194  4194 E Zygote  : MountEmulatedStorage()
,03-17 06:44:22.829  4194  4194 E Zygote  : v2
03-17 06:44:22.829  4194  4194 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:22.829  4194  4194 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:22.829  4194  4194 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 06:44:22.829  1017  1151 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4194 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:22.829  4194  4194 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:22.839  4194  4194 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:22.839  4161  4161 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,03-17 06:44:22.839  4161  4161 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
03-17 06:44:22.849  1017  1533 D ActivityManager: startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
03-17 06:44:22.849  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,03-17 06:44:22.849  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:22.849  1017  1533 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 06:44:22.849  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-17 06:44:22.849  4161  4161 I SA      : [OR] onReceive END
,03-17 06:44:22.859  4194  4194 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:22.859  1017  1504 D ActivityManager: startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,03-17 06:44:22.859  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.859  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.859  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.859  1017  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.859  4194  4194 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:22.869   282   282 W QCamera2Factory: getCameraInfo: E, camera_id = 0
03-17 06:44:22.869   282   282 W QCamera2Factory: getCameraInfo: X
03-17 06:44:22.869   282   696 W QCamera2Factory: getCameraInfo: E, camera_id = 1
03-17 06:44:22.869   282   696 W QCamera2Factory: getCameraInfo: X
03-17 06:44:22.879  4207  4207 E Zygote  : MountEmulatedStorage()
03-17 06:44:22.879  4207  4207 E Zygote  : v2
03-17 06:44:22.879  4207  4207 I libpersona: KNOX_SDCARD checking this for 10042
03-17 06:44:22.879  4207  4207 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:22.879  4207  4207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:22.879  4207  4207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:22.879  4207  4207 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 06:44:22.879  1017  1504 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4207 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:22.889  4161  4161 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-17 06:44:22.889  4161  4161 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-17 06:44:22.899  4161  4161 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-17 06:44:22.899  4161  4161 I SA      : [LBE] REF_JPN : true
03-17 06:44:22.899  4161  4161 I SA      : [BDC] create
,03-17 06:44:22.909  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:22.919  3963  4008 I GFX raster: took 0.584740ms for 96*96 texture 0
03-17 06:44:22.919  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb837cec0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8383ec0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:22.919  3963  4008 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 06:44:22.929  4207  4207 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:22.929  4161  4161 I SA      : [DBMV2] getEmailID
,03-17 06:44:22.929  4161  4161 I SA      : [DBMV2] getDataV02ForItems
03-17 06:44:22.929  4161  4161 I SA      : [SSP] query invoked
,03-17 06:44:22.929  4207  4207 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:22.929  4025  4025 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 06:44:22.939  4161  4161 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-17 06:44:22.949  4161  4161 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-17 06:44:22.949  4161  4161 I SA      : [BDC] destroy
,03-17 06:44:22.949  1017  1534 I ActivityManager: Killing 3380:com.dropbox.android/u0a92 (adj 15): empty #31
,03-17 06:44:22.969  4025  4025 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 06:44:22.979  4025  4025 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 06:44:22.979  4025  4025 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 06:44:22.979  4025  4025 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 06:44:22.979  4207  4207 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 06:44:22.989  4053  4053 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 06:44:22.989  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,03-17 06:44:22.989  4053  4053 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 06:44:22.989  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
,03-17 06:44:22.989  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-17 06:44:22.989  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-17 06:44:22.989  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
,03-17 06:44:22.989  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-17 06:44:22.989  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
,03-17 06:44:22.989  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-17 06:44:22.989  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-17 06:44:22.999  4025  4025 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 06:44:22.999  4025  4025 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:22.999  4025  4025 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 06:44:22.999  3963  4008 I AMMetaDataParserService: Resource data:2131034112
03-17 06:44:23.009  3963  4008 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-17 06:44:23.009  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
03-17 06:44:23.009  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 06:44:23.009  3963  4008 I GFX raster: took 0.613386ms for 96*96 texture 0
,03-17 06:44:23.019  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8383ec0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83847b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:23.019  4025  4025 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 06:44:23.029  2574  2587 I art     : WaitForGcToComplete blocked for 36.549ms for cause HomogeneousSpaceCompact
,03-17 06:44:23.049  3963  4008 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-17 06:44:23.049  4025  4025 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 06:44:23.049  4025  4025 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 06:44:23.079  4025  4025 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-17 06:44:23.079  4025  4025 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 06:44:23.079  4025  4025 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 06:44:23.079  4025  4025 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-17 06:44:23.089  1017  1041 W libprocessgroup: failed to open /acct/uid_10092/pid_3380/cgroup.procs: No such file or directory
,03-17 06:44:23.099  4025  4025 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-17 06:44:23.099  4025  4025 W VideoCapabilities: Unsupported mime video/mp43
,03-17 06:44:23.099  4025  4025 W VideoCapabilities: Unsupported mime video/sorenson
,03-17 06:44:23.109  4025  4025 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-17 06:44:23.129  4025  4025 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es,
,03-17 06:44:23.129  4207  4207 I CalendarProvider2: CalendarProvider2.onCreate() called,
,03-17 06:44:23.139  1017  1533 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,03-17 06:44:23.139  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.149  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.149  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.149  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.149  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:23.149  3963  4008 I GFX raster: took 0.623437ms for 96*96 texture 0
,03-17 06:44:23.159  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8383ec0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb837d020 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:23.159  4225  4225 E Zygote  : MountEmulatedStorage(),
03-17 06:44:23.159  4225  4225 E Zygote  : v2
03-17 06:44:23.159  4225  4225 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 06:44:23.159  1017  1533 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4225 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:23.159  1017  1533 I ActivityManager: Killing 3403:com.fmm.dm/1000 (adj 15): empty #31,
03-17 06:44:23.169  4225  4225 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:23.169  4225  4225 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:23.169  4225  4225 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:23.169  4225  4225 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:23.189  3963  4008 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-17 06:44:23.189  4225  4225 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:23.199  4225  4225 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:23.229  1017  1488 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,03-17 06:44:23.229  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,03-17 06:44:23.239  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:23.239  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:23.239  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.239  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 06:44:23.239  3963  4008 I GFX raster: took 0.704479ms for 96*96 texture 0
03-17 06:44:23.239  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83847b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb837d020 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:23.249  3963  4008 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-17 06:44:23.269  1017  1532 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-17 06:44:23.269  1017  1532 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
,03-17 06:44:23.269  1017  1532 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
03-17 06:44:23.269  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,03-17 06:44:23.269  1017  1017 I MotionRecognitionService: Plugged
,03-17 06:44:23.269  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 06:44:23.269  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 06:44:23.269  1183  1183 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-17 06:44:23.269  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 06:44:23.269  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 06:44:23.269  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:23.279  3963  4008 I GFX raster: took 0.729531ms for 96*96 texture 0
,03-17 06:44:23.279  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a61d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb837d020 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:23.289  2627  2627 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 06:44:23.289  2627  2708 D HeadsetStateMachine: Disconnected process message: 10
,03-17 06:44:23.289  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-17 06:44:23.289  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-17 06:44:23.289  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 06:44:23.289  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-17 06:44:23.299  4225  4225 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
,03-17 06:44:23.309  4225  4225 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.em,ergency.InteractionEmergencyMessageActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity,
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity,
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
,03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: Resource data:2131034113
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 06:44:23.329  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
03-17 06:44:23.329  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:23.329  3963  4008 I GFX raster: took 0.817292ms for 96*96 texture 0
03-17 06:44:23.329  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb837d020 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb837cfb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:23.349  3963  4008 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 06:44:23.359  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:23.359  3963  4008 I GFX raster: took 0.856980ms for 96*96 texture 0
03-17 06:44:23.359  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb837d020 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb837cfb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:23.369  3963  4008 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 06:44:23.379  4225  4225 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-17 06:44:23.379  4225  4225 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
,03-17 06:44:23.379  4225  4225 D ShortcutReceiver:  shortcut migration not required 
,03-17 06:44:23.379  4053  4158 D Volley  : [596] DiskBasedCache.clear: Cache cleared.
,03-17 06:44:23.389  4053  4185 D Volley  : [603] DiskBasedCache.clear: Cache cleared.
,03-17 06:44:23.409  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3403/cgroup.procs: No such file or directory
,03-17 06:44:23.419  1017  1029 I ActivityManager: Killing 3485:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,03-17 06:44:23.419  1017  1029 I ActivityManager: Killing 3460:com.fmm.ds/1000 (adj 15): empty #32
,03-17 06:44:23.419  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,03-17 06:44:23.419  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.419  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.419  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.419  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.439  4053  4246 D Ads     : Skipping gmscore version check,
,03-17 06:44:23.439  1017  1029 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4247 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 06:44:23.439  1017  1029 I ActivityManager: Killing 3505:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,03-17 06:44:23.439  4247  4247 E Zygote  : MountEmulatedStorage(),
03-17 06:44:23.449  4247  4247 E Zygote  : v2
03-17 06:44:23.449  4247  4247 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 06:44:23.449  4247  4247 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:23.449  1017  1523 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:23.449  4247  4247 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 06:44:23.449  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:23.449  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.449  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:23.449  4247  4247 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:23.459  4247  4247 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:23.469  1017  1532 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
03-17 06:44:23.469  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,03-17 06:44:23.469  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:23.469  1017  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.469  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 06:44:23.479  4025  4244 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 06:44:23.479  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:23.489  3963  4008 I GFX raster: took 0.704843ms for 96*96 texture 0
03-17 06:44:23.489  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb837cfb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8390c98 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:23.489  3963  4008 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 06:44:23.509  4247  4247 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:23.509  4247  4247 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:23.529  4053  4053 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-17 06:44:23.529  4053  4053 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-17 06:44:23.559  3946  4254 D FileApkUtils: Optimizing (staging complete)
,03-17 06:44:23.559  3946  4254 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
,03-17 06:44:23.559  3946  4254 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-17 06:44:23.569  1017  1533 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:23.569  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:23.569  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:23.569  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 06:44:23.579  4025  4244 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 06:44:23.589  1017  1041 W libprocessgroup: failed to open /acct/uid_10092/pid_3485/cgroup.procs: No such file or directory
03-17 06:44:23.589  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3460/cgroup.procs: No such file or directory
03-17 06:44:23.589  1017  1041 W libprocessgroup: failed to open /acct/uid_10003/pid_3505/cgroup.procs: No such file or directory
,03-17 06:44:23.589  4025  4244 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 06:44:23.599  3946  4254 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
03-17 06:44:23.599  3946  4254 D DexOptUtils: Lollipop platform, using <isa> directory.
,03-17 06:44:23.599  3946  4254 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
03-17 06:44:23.599  3946  4254 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,03-17 06:44:23.609  4247  4247 E KnoxSetupWizardClient: isShipMode : 1
03-17 06:44:23.609  4247  4247 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 06:44:23.649  1017  1533 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
03-17 06:44:23.649  3178  3249 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-17 06:44:23.649  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.649  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.649  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.649  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.669  4271  4271 E Zygote  : MountEmulatedStorage(),
,03-17 06:44:23.679  4271  4271 E Zygote  : v2
03-17 06:44:23.679  4271  4271 I libpersona: KNOX_SDCARD checking this for 10107,
03-17 06:44:23.679  4271  4271 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:23.679  4271  4271 I libpersona: KNOX_SDCARD not a persona,
,03-17 06:44:23.679  4271  4271 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:23.679  4271  4271 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 06:44:23.679  1017  1533 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4271 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,03-17 06:44:23.699  1017  1533 I ActivityManager: Killing 3312:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,03-17 06:44:23.709  1017  1348 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:23.709  1017  1348 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,03-17 06:44:23.709  1017  1348 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:23.709  1017  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:23.709  1017  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:23.719  4025  4244 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 06:44:23.729  4025  4244 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 06:44:23.729  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:23.729  3963  4008 I GFX raster: took 0.602032ms for 96*96 texture 0
03-17 06:44:23.729  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8383ec0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83467a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:23.739  4271  4271 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:23.739  4271  4271 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:23.739  1017  1504 I ActivityManager: Killing 3526:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,03-17 06:44:23.749  3963  4008 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 06:44:23.759  1017  1533 I ActivityManager: Killing 2763:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,03-17 06:44:23.759  1017  3038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:23.769  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:23.769  1017  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.769  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:23.789  4053  4053 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-17 06:44:23.789  1818  1818 D ChimeraCfgMgr: Reading stored module config
,03-17 06:44:23.799  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:23.809  1017  1151 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:23.809  3963  4008 I GFX raster: took 0.916145ms for 96*96 texture 0
03-17 06:44:23.809  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a2988 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8390c98 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:23.809  1017  1151 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 06:44:23.809  1017  1151 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:23.809  1017  1151 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.809  1017  1151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:23.819  3963  4008 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 06:44:23.819  4247  4267 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-17 06:44:23.819  1818  1818 D WearableService: callingUid 10012, callindPid: 1818
,03-17 06:44:23.819  4247  4267 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
,03-17 06:44:23.829  4247  4267 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-17 06:44:23.829  4247  4267 W System.err: ,	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
03-17 06:44:23.829  4247  4267 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
03-17 06:44:23.829  4247  4267 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-17 06:44:23.829  4247  4267 W System.err: ,	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-17 06:44:23.829  1017  1263 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,03-17 06:44:23.829  1017  1263 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,03-17 06:44:23.829  1017  1263 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:23.829  1017  1263 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.829  1017  1263 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 06:44:23.839  1017  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-17 06:44:23.849  3823  3837 W art     : Suspending all threads took: 48.476ms
,03-17 06:44:23.879  1017  1039 D SensorService: [SO] 0.134 0.421 10.132
,03-17 06:44:23.879  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:23.879  1017  1501 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,03-17 06:44:23.879  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 06:44:23.879  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:23.879  3963  4008 I GFX raster: took 0.780157ms for 96*96 texture 0
03-17 06:44:23.879  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a61d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83467a8 counterpartCT=4 counterpartW=96 counterparth=96
03-17 06:44:23.879  1017  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:23.879  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 06:44:23.899  1818  1818 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 06:44:23.899  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 06:44:23.919  4269  4269 I dex2oat : ----------------------------------------------------
03-17 06:44:23.919  4269  4269 I dex2oat : <SS>: S T A R T I N G . . .
03-17 06:44:23.919  4269  4269 I dex2oat : <SS>: Zip is absent. Canceled.
03-17 06:44:23.919  4269  4269 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=35 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 06:44:23.929  4053  4053 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-17 06:44:23.929  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:23.929  3963  4008 I GFX raster: took 0.878490ms for 96*96 texture 0,
03-17 06:44:23.929  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83566f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8390c98 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:23.939  3963  4008 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 06:44:23.959  1017  1041 W libprocessgroup: failed to open /acct/uid_10009/pid_3312/cgroup.procs: No such file or directory
03-17 06:44:23.959  1017  1041 W libprocessgroup: failed to open /acct/uid_10014/pid_3526/cgroup.procs: No such file or directory
03-17 06:44:23.959  1017  1041 W libprocessgroup: failed to open /acct/uid_10120/pid_2763/cgroup.procs: No such file or directory
,03-17 06:44:23.979  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:23.979  3963  4008 I GFX raster: took 0.653959ms for 96*96 texture 0
03-17 06:44:23.979  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb837cec0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83467a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:23.979  3946  3946 W InstanceID/Rpc: Found 10012
,03-17 06:44:23.999  3963  4008 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527,
,03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-17 06:44:24.009  3963  4008 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 06:44:24.009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-17 06:44:24.,009  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.Ac,countSecurity
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:24.029  3963  4008 I AMMetaDataParserService: Resource data:2131165203
,03-17 06:44:24.039  3963  4008 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 06:44:24.039  3963  4008 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:24.039  3963  4008 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 06:44:24.039  3963  4008 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:24.039  3963  4008 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:44:24.039  3963  4008 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-17 06:44:24.039  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:24.039  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.039  3963  4008 I GFX construct_block_size_descriptor_2d second part: took 2.840781ms for 0*0 texture 0
,03-17 06:44:24.059  1017  1501 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:24.059  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.059  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.059  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:24.059  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.069  3963  4008 I GFX generate_partition_tables: took 10.222552ms for 0*0 texture 0
,03-17 06:44:24.069  3963  4008 I GFX raster: took 14.301093ms for 96*96 texture 0
03-17 06:44:24.069  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb837cfe8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8554ee0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.079  1017  1348 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 06:44:24.079  1017  1348 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.079  1017  1348 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:24.079  1017  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:24.079  1017  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.089  3963  4008 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-17 06:44:24.099  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.099  3963  4008 I GFX raster: took 1.128438ms for 96*96 texture 0
03-17 06:44:24.099  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8373ea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8373f50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.109  3963  4008 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 06:44:24.119  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:24.119  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.119  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.119  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:24.119  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.149   256   517 I SecDataIO: Write to block
,03-17 06:44:24.159  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.159  3963  4008 I GFX raster: took 0.957031ms for 96*96 texture 0
03-17 06:44:24.159  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8373ea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8375378 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.169  1017  1263 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:24.169  1017  1263 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.169  1017  1263 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.169  1017  1263 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:24.169  1017  1263 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.169  3963  4008 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 06:44:24.179  2574  3198 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-17 06:44:24.179  3178  3178 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,03-17 06:44:24.179  1017  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:24.189  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.199  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:24.199  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:24.199  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.199  3178  3178 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,03-17 06:44:24.209  3178  3178 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
03-17 06:44:24.209  2574  2574 I Process : Sending signal. PID: 2574 SIG: 9
,03-17 06:44:24.219  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-17 06:44:24.229  1017  1523 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:24.229  1017  1523 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.229  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.229  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:24.229  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.239  3946  4300 D GCM     : COMPAT: Multi user not supported
,03-17 06:44:24.249  1017  1504 I ActivityManager: Process com.sec.android.app.sysscope (pid 2574)(adj 0) has died(48,1100)
,03-17 06:44:24.249  1017  1348 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:24.249  1017  1348 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.249  1017  1348 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.249  1017  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:24.249  1017  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.259  1017  1501 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:24.259  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0,
03-17 06:44:24.259  1818  1818 D GCM     : COMPAT: Multi user not supported
,03-17 06:44:24.259  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.259  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:24.259  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.269  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.269  1017  1523 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 06:44:24.269  1017  1523 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.269  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:24.269  3963  4008 I GFX raster: took 0.980208ms for 96*96 texture 0
03-17 06:44:24.269  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8373ea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb837a400 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.269  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:24.269  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.279  1017  1532 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:24.279  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.279  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.279  1017  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:24.279  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.289  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:24.289  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.289  3963  4008 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
03-17 06:44:24.289  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:24.289  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:24.289  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.299  1017  1263 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:24.299  1017  1263 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 06:44:24.299  1017  1263 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.299  1017  1263 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:24.299  1017  1263 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.309  3946  4300 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 06:44:24.319  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 06:44:24.319  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.319  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.319  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:24.319  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.319  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.319  3963  4008 I GFX raster: took 0.613021ms for 96*96 texture 0
03-17 06:44:24.319  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb837a5d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb837a678 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.339  3963  4008 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 06:44:24.339   287   287 E SMD     : DCD OFF
,03-17 06:44:24.369  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.369  3963  4008 I GFX raster: took 0.605000ms for 96*96 texture 0
,03-17 06:44:24.369  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb837a5d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8377740 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.399  3963  4008 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 06:44:24.409  3946  4313 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:24.419  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
,03-17 06:44:24.429  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
,03-17 06:44:24.429  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
,03-17 06:44:24.429  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-17 06:44:24.429  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-17 06:44:24.429  3963  4008 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 06:44:24.469  3946  3946 D ChimeraCfgMgr: Reading stored module config
,03-17 06:44:24.519  3823  3836 W art     : Suspending all threads took: 7.245ms
,03-17 06:44:24.519  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-17 06:44:24.519  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-17 06:44:24.519  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-17 06:44:24.519  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-17 06:44:24.519  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-17 06:44:24.519  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:24.519  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 06:44:24.519  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 06:44:24.519  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:24.519  3963  4008 I AMMetaDataParserService: Resource data:2131099648
,03-17 06:44:24.579  3963  4008 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-17 06:44:24.579  3963  4008 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:24.579  3963  4008 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 06:44:24.579  3963  4008 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:24.579  3963  4008 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 06:44:24.579  3963  4008 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 06:44:24.579  3963  4008 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-17 06:44:24.579  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:24.579  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.589  3963  4008 I GFX raster: took 0.839323ms for 96*96 texture 0
03-17 06:44:24.589  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88a92b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88a9590 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.589  1017  1348 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-17 06:44:24.589  1017  1348 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 06:44:24.589  1017  1348 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.589  1017  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:24.599  1017  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.599  3963  4008 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 06:44:24.609  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.609  3963  4008 I GFX construct_block_size_descriptor_2d second part: took 2.618645ms for 0*0 texture 0
,03-17 06:44:24.619  3946  3946 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-17 06:44:24.619  3946  3946 D BootCompletedReceiver: Got an BootCompleted event.
,03-17 06:44:24.629  3963  4008 I GFX generate_partition_tables: took 8.943177ms for 0*0 texture 0
,03-17 06:44:24.629  3963  4008 I GFX raster: took 12.512186ms for 96*96 texture 0
03-17 06:44:24.629  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88aa308 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb88aa340 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.629  3946  3946 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-17 06:44:24.629  3946  3946 D SystemUpdateService: onCreate
,03-17 06:44:24.639  3963  4008 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 06:44:24.659  3178  3249 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-17 06:44:24.659  3178  3249 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 06:44:24.659  3178  3249 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-17 06:44:24.659  3178  3249 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,03-17 06:44:24.659  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.669  3963  4008 I GFX raster: took 0.713750ms for 96*96 texture 0
,03-17 06:44:24.669  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88abe10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb88abeb8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.669  3963  4008 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 06:44:24.689  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.689  3963  4008 I GFX raster: took 0.648021ms for 96*96 texture 0
03-17 06:44:24.689  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88ae398 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88ae3d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.699  3963  4008 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 06:44:24.709  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.709  3963  4008 I GFX raster: took 0.641667ms for 96*96 texture 0
03-17 06:44:24.709  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88af908 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88af940 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.719  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 06:44:24.729  3946  3946 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 06:44:24.739  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.739  3963  4008 I GFX raster: took 0.728490ms for 96*96 texture 0
03-17 06:44:24.739  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88b1bb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88b1be8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.749  3963  4008 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 06:44:24.749  3178  3249 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
03-17 06:44:24.759  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-17 06:44:24.759  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-17 06:44:24.759  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:24.759  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:24.759  3963  4008 I AMMetaDataParserService: Resource data:2131099648
,03-17 06:44:24.759  3946  4322 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 06:44:24.769  3963  4008 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 06:44:24.769  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:24.769  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.769  3963  4008 I GFX raster: took 0.691093ms for 96*96 texture 0
03-17 06:44:24.769  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8376e90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb837b5e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.769  3963  4008 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 06:44:24.789  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
03-17 06:44:24.789  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 06:44:24.789  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.789  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:24.789  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.799  3946  4314 I CheckinService: Checking schedule, now: 1458193464803 next: 1458246240395
03-17 06:44:24.799  3946  4314 I CheckinService: active receiver: disabled
,03-17 06:44:24.799  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:24.799  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.799  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.799  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:24.799  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.809  3178  3249 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-17 06:44:24.819  3946  4321 I SystemUpdateService: cancelUpdate (empty URL)
03-17 06:44:24.819  3946  4321 I SystemUpdateService: active receiver: disabled
,03-17 06:44:24.829  4271  4271 D StrictMode: StrictMode policy violation; ~duration=858 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 06:44:24.829  4271  4271 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:24.829  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 06:44:24.849  4271  4271 D StrictMode: StrictMode policy violation; ~duration=851 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 06:44:24.849  4271  4271 D StrictMode: StrictMode policy violation; ~duration=756 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.File.exists(File.java:363)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 06:44:24.849  4271  4271 D StrictMod,e: 	at com.google.b.a.ca.a(PG:125)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 06:44:24.849  4271  4271 D StrictMode: StrictMode policy violation; ~duration=755 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at androi,d.os.Looper.loop(Looper.java:145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 06:44:24.849  4271  4271 D StrictMode: StrictMode policy violation; ~duration=752 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 06:44:24.849  4271  4271 D StrictMode: StrictMode policy violation; ~duration=742 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.k.c(PG:1187)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.k.a(PG:2107)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.v.a(PG:1206)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.y.a(PG:2233)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.e.b(PG:170)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.e.b(PG:13188)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 06:44:24.849  4271  4271 D StrictMode: StrictMode policy violation; ~duration=739 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.k.c(PG:1187)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.k.b(PG:14147)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.k.c(PG:583)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.v.a(PG:1206)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.y.a(PG:2233)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.e.b(PG:170)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.r.e.b(PG:13188)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 06:44:24.849  4271  4271 D StrictMode: StrictMode policy violation; ~duration=706 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.File.exists(File.java:363)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 06:44:24.849  1017  1533 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
03-17 06:44:24.849  4271  4271 D StrictMode: StrictMode policy violation; ~duration=706 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.io.File.exists(File.java:363)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:24.849  4271  4271 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 06:44:24.859  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.849  3178  3249 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
03-17 06:44:24.859  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.859  3178  3249 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
03-17 06:44:24.859  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.859  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.869  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 06:44:24.869  3963  4008 I GFX raster: took 0.639896ms for 96*96 texture 0
03-17 06:44:24.869  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88af440 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8376db0 counterpartCT=4 counterpartW=96 counterparth=96
03-17 06:44:24.869  4326  4326 E Zygote  : MountEmulatedStorage()
03-17 06:44:24.869  4326  4326 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:24.869  4326  4326 E Zygote  : v2
03-17 06:44:24.869  4326  4326 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:24.879  1017  1533 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4326 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:24.879  3178  3249 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
03-17 06:44:24.879  3178  3249 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
03-17 06:44:24.879  4326  4326 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:24.879  3963  4008 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 06:44:24.889  4326  4326 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:24.889  3178  3250 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
03-17 06:44:24.889  4326  4326 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:24.889  4207  4207 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-17 06:44:24.899  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 06:44:24.899  3963  4008 I GFX raster: took 0.644584ms for 96*96 texture 0
03-17 06:44:24.899  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88a92b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb83566f8 counterpartCT=4 counterpartW=96 counterparth=96
03-17 06:44:24.909  3963  4008 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-17 06:44:24.909  3946  4322 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
03-17 06:44:24.919  3178  3249 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,03-17 06:44:24.929  3178  3249 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-17 06:44:24.929  3178  3250 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,03-17 06:44:24.929  3178  3249 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,03-17 06:44:24.939  1017  1348 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.949  1017  1348 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.959  1017  1348 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,03-17 06:44:24.959  1017  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar,
,03-17 06:44:24.959  4326  4326 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:24.959  4326  4326 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:24.989  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:24.989  3963  4008 I GFX raster: took 0.639062ms for 96*96 texture 0
03-17 06:44:24.989  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88ae398 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb802afc8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:24.999  1017  1523 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 06:44:24.999  1017  1523 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.999  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:24.999  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:24.999  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:25.009  3178  3250 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,03-17 06:44:25.009  3178  3250 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,03-17 06:44:25.019  1818  4342 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-17 06:44:25.029   274   977 D EnterpriseController: uids 10012
03-17 06:44:25.029   274   977 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 06:44:25.029   274   977 D Netd    : getNetworkForDns: using netid 502 for uid 10012
03-17 06:44:25.029  3963  4008 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 06:44:25.049  4326  4326 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 06:44:25.049  3178  3250 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,03-17 06:44:25.049  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:25.049  3963  4008 I GFX raster: took 0.691927ms for 96*96 texture 0
,03-17 06:44:25.049  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88af908 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8383ec0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:25.059  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 06:44:25.069  4326  4326 I StatusChecker: onReceive : net.mt.init : DONE
,03-17 06:44:25.069  1017  1051 D PowerManagerService: [s] UserActivityState : 1 -> 2
03-17 06:44:25.069  1017  1051 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-17 06:44:25.069  1017  1051 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 06:44:25.069  3178  3250 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,03-17 06:44:25.079  1017  1051 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 06:44:25.089  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:25.089  3963  4008 I GFX raster: took 0.748281ms for 96*96 texture 0,
03-17 06:44:25.089  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88b1bb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb839e498 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:25.089  1017  1171 D lights  : lcd : 20 +
,03-17 06:44:25.109  3178  3250 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,03-17 06:44:25.109  3178  3250 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,03-17 06:44:25.109  1017  1051 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-17 06:44:25.109  1017  1051 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 06:44:25.109  3963  4008 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 06:44:25.109  1017  1171 D lights  : lcd : 20 -
,03-17 06:44:25.109  1017  1171 D lights  : lcd : 19 +
03-17 06:44:25.109  1017  1348 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,03-17 06:44:25.119  3178  3178 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,03-17 06:44:25.119  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.129  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.129  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.129  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.129  1017  1171 D lights  : lcd : 19 -,
,03-17 06:44:25.129  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity,
03-17 06:44:25.129  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-17 06:44:25.129  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity,
,03-17 06:44:25.129  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-17 06:44:25.139  1017  1051 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-17 06:44:25.129  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:25.139  1017  1051 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-17 06:44:25.129  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
,03-17 06:44:25.129  3963  4008 I AMMetaDataParserService: Resource data:2131099648
,03-17 06:44:25.149  3963  4008 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging,
03-17 06:44:25.149  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml,
03-17 06:44:25.149  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-17 06:44:25.149  3963  4008 I GFX raster: took 0.710208ms for 96*96 texture 0
03-17 06:44:25.149  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8376e90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8027400 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:25.149  4352  4352 E Zygote  : MountEmulatedStorage(),
03-17 06:44:25.149  4352  4352 E Zygote  : v2,
03-17 06:44:25.149  4352  4352 I libpersona: KNOX_SDCARD checking this for 10116
,03-17 06:44:25.149  4352  4352 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:25.149  4352  4352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 06:44:25.149  3963  4008 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 06:44:25.159  4352  4352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:25.159  4352  4352 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:25.169  1017  1348 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4352 uid=10116 gids={50116, 9997} abi=armeabi-v7a
03-17 06:44:25.169  1017  1348 I ActivityManager: Killing 3551:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,03-17 06:44:25.189  4352  4352 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:25.189  4352  4352 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:25.209  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:25.209  3963  4008 I GFX raster: took 0.652657ms for 96*96 texture 0
03-17 06:44:25.209  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88af440 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8383ec0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:25.219  1818  1818 I GCoreUlr: DispatchingService.onCreate()
,03-17 06:44:25.229  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-17 06:44:25.229  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,03-17 06:44:25.239  3963  4008 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 06:44:25.249  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,03-17 06:44:25.249  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:25.249  3963  4008 I GFX raster: took 0.720834ms for 96*96 texture 0
03-17 06:44:25.249  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88a92b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb839ea50 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:25.259  3178  3250 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,03-17 06:44:25.259  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,03-17 06:44:25.259  3178  3250 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,03-17 06:44:25.269  3946  4322 W BaseAppContext: Using Auth Proxy for data requests.,
03-17 06:44:25.269  1017  1151 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 06:44:25.279  3178  3178 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,03-17 06:44:25.279  3963  4008 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
03-17 06:44:25.279  3178  3178 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@203f4844
,03-17 06:44:25.309  1017  1151 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:25.309  1017  1151 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.309  1017  1151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:25.319  1017  1348 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,03-17 06:44:25.329  1017  1348 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:25.329  1017  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-17 06:44:25.329  1017  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:25.339  4352  4352 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-17 06:44:25.349  1017  1533 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:25.349  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:25.349  3963  4008 I GFX raster: took 0.641511ms for 96*96 texture 0
03-17 06:44:25.349  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88ae398 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb837d240 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:25.359  3178  3250 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,03-17 06:44:25.359  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:25.359  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:25.359  3178  3250 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,03-17 06:44:25.369  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:25.369  3178  3250 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,03-17 06:44:25.379  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.379  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.379  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.379  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:25.389  3963  4008 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 06:44:25.389  1017  1488 D SettingsProvider: name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,03-17 06:44:25.409  4352  4352 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 ,
,03-17 06:44:25.419  1017  1151 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
03-17 06:44:25.419  1017  1151 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.419  1017  1151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
03-17 06:44:25.419  1017  1151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-17 06:44:25.419  4352  4352 I PageBuddyNotiSvc: onCreate mCpBitFlag=0,
03-17 06:44:25.429  1017  1263 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,03-17 06:44:25.429  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.429  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.429  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.429  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.429  1017  1041 W libprocessgroup: failed to open /acct/uid_10060/pid_3551/cgroup.procs: No such file or directory
,03-17 06:44:25.439  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-17 06:44:25.439  3963  4008 I GFX raster: took 0.650156ms for 96*96 texture 0
03-17 06:44:25.439  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88af908 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83566f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:25.449  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:25.449  4373  4373 E Zygote  : MountEmulatedStorage()
,03-17 06:44:25.449  4373  4373 E Zygote  : v2,
,03-17 06:44:25.449  4373  4373 I libpersona: KNOX_SDCARD checking this for 10125
03-17 06:44:25.449  1017  1263 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4373 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-17 06:44:25.459  4373  4373 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:25.459  1818  4341 I GCM     : GCM config loaded
03-17 06:44:25.459  4373  4373 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:25.459  4373  4373 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:25.469  4373  4373 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:25.469  1017  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-17 06:44:25.469  1017  1041 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.479  3178  3250 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-17 06:44:25.479  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 06:44:25.499  1818  4368 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-17 06:44:25.499  4373  4373 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:25.499  4373  4373 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:25.519  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:25.519  3963  4008 I GFX raster: took 0.724011ms for 96*96 texture 0
03-17 06:44:25.519  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88b1bb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb835e820 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:25.539  3963  4008 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 06:44:25.579  1017  1151 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
03-17 06:44:25.579  1017  1151 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.579  1017  1151 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.579  1017  1151 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.579  1017  1151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 06:44:25.599  3805  3962 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 06:44:25.599  4373  4373 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:25.599  4373  4373 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 06:44:25.599  4373  4373 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 06:44:25.599  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-17 06:44:25.599  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:25.599  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:25.599  3963  4008 I AMMetaDataParserService: Resource data:2131099648
,03-17 06:44:25.619  4271  4351 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 06:44:25.629  4271  4351 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,03-17 06:44:25.639  3946  3959 W art     : Suspending all threads took: 59.336ms
03-17 06:44:25.639  4271  4351 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 06:44:25.639  4271  4351 I System.out: (HTTPLog)-Static: isShipBuild true
03-17 06:44:25.639  4271  4351 I System.out: (HTTPLog)-Thread-645-753436595: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 06:44:25.639  4271  4351 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 06:44:25.639   274   977 D EnterpriseController: uids 10107
03-17 06:44:25.639   274   977 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 06:44:25.639   274   977 D Netd    : getNetworkForDns: using netid 502 for uid 10107
,03-17 06:44:25.639  1818  4380 I art     : Explicit concurrent mark sweep GC freed 32716(2MB) AllocSpace objects, 37(592KB) LOS objects, 40% free, 12MB/20MB, paused 2.761ms total 92.317ms
,03-17 06:44:25.689  4271  4351 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 06:44:25.729  1017  1534 I art     : Explicit concurrent mark sweep GC freed 36759(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/40MB, paused 4.793ms total 200.697ms
,03-17 06:44:25.729  1017  1348 I art     : WaitForGcToComplete blocked for 206.777ms for cause Explicit
,03-17 06:44:25.729  1017  1043 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 06:44:25.739  1017  1043 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 06:44:25.759  1660  1668 I art     : Explicit concurrent mark sweep GC freed 2488(87KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 732us total 32.510ms
,03-17 06:44:25.769  3946  3946 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-17 06:44:25.769  3946  3946 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,03-17 06:44:25.769  3946  3946 W art     : Verification of void com.google.android.gms.common.j.b.a(android.content.pm.PackageManager) took 165.834ms
,03-17 06:44:25.789  4373  4373 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-17 06:44:25.799  4373  4373 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-17 06:44:25.799  3946  4300 I art     : WaitForGcToComplete blocked for 24.088ms for cause DisableMovingGc
,03-17 06:44:25.799  3946  3946 I art     : WaitForGcToComplete blocked for 23.181ms for cause DisableMovingGc
,03-17 06:44:25.819  3946  4322 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-17 06:44:25.819  1017  1534 D SettingsProvider: name = scon_is_running
03-17 06:44:25.819  1017  1534 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:25.819  1017  1534 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:25.819  1017  1534 D SettingsProvider: selectionArgs: false
03-17 06:44:25.819  1017  1534 D SettingsProvider: selectionArgs: 10125
03-17 06:44:25.819  1017  1534 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:25.819  1017  1534 D SettingsProvider: ret = -1
,03-17 06:44:25.829  1017  1534 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,03-17 06:44:25.829  4373  4373 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-17 06:44:25.839  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:25.839  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:25.839  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.839  4373  4373 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 06:44:25.849  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:25.849  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.849  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:25.849  1017  1263 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,03-17 06:44:25.859  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.859  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.859  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.859  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.879  1017  1263 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4399 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-17 06:44:25.879  4399  4399 E Zygote  : MountEmulatedStorage()
,03-17 06:44:25.879  4399  4399 E Zygote  : v2
03-17 06:44:25.879  4399  4399 I libpersona: KNOX_SDCARD checking this for 10131
03-17 06:44:25.879  4399  4399 I libpersona: KNOX_SDCARD not a persona,
,03-17 06:44:25.879  4399  4399 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:25.879  1017  1263 I ActivityManager: Killing 3345:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,03-17 06:44:25.879  4399  4399 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:25.879  4399  4399 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:25.899  4399  4399 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:25.909  4399  4399 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:25.909  3963  4008 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 06:44:25.909  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:25.909  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:25.909  3963  4008 I GFX raster: took 0.871718ms for 96*96 texture 0
03-17 06:44:25.909  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a2ad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88abb98 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:25.919  3963  4008 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 06:44:25.929  4399  4399 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 06:44:25.929  4399  4399 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:25.929  4399  4399 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 06:44:25.929  4399  4399 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:44:25.929  1818  1818 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,03-17 06:44:25.939  1017  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 06:44:25.939  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.939  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.939  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.939  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:25.949  1818  1818 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:25.959  1017  1348 I art     : Explicit concurrent mark sweep GC freed 5937(312KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 3.042ms total 237.335ms
,03-17 06:44:25.979  3178  3250 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-17 06:44:26.009  4271  4299 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,03-17 06:44:26.019  1017  1534 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,03-17 06:44:26.019  1017  1534 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 06:44:26.029  1017  1017 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-17 06:44:26.029  3946  3946 D SystemUpdateService: onDestroy
,03-17 06:44:26.029  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 06:44:26.029  1183  1925 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:26.039  1017  1523 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
03-17 06:44:26.039  1017  1523 D SecContentProvider2: mCursor = null
,03-17 06:44:26.039  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.039  3963  4008 I GFX raster: took 0.627604ms for 96*96 texture 0
03-17 06:44:26.039  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88abb98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb88a92b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.049  1017  1151 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-17 06:44:26.049  1017  1151 D SecContentProvider2: mCursor = null
,03-17 06:44:26.049  1017  1030 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
03-17 06:44:26.049  1017  1030 D SecContentProvider2: mCursor = null
,03-17 06:44:26.059  1017  1504 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
03-17 06:44:26.059  1017  1504 D SecContentProvider2: mCursor = null
,03-17 06:44:26.059  3178  3250 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,03-17 06:44:26.059  3963  4008 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 06:44:26.069  3178  3250 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 06:44:26.089  1183  1183 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-17 06:44:26.089  3946  4322 I AuthZen : Fetching signing key...
,03-17 06:44:26.109  3946  4322 I AuthZen : Signing key fetched successfully!
,03-17 06:44:26.129  3178  3250 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,03-17 06:44:26.129  3946  4322 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 06:44:26.139  3178  3250 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,03-17 06:44:26.139  3178  3250 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,03-17 06:44:26.139  3946  3946 I GAv4-SVC: Google Analytics 8.7.03 is starting up.
,03-17 06:44:26.159  1017  1041 W libprocessgroup: failed to open /acct/uid_10057/pid_3345/cgroup.procs: No such file or directory
,03-17 06:44:26.159  1183  1183 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-17 06:44:26.169  1183  1183 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
,03-17 06:44:26.189  1017  1029 D SecContentProvider2: uri = 15 selection = getToastEnabledState
03-17 06:44:26.189  1017  1029 D SecContentProvider2: mCursor = null
,03-17 06:44:26.189  1183  1183 D PersonaManager: isKioskContainerExistOnDevice
,03-17 06:44:26.189  1183  1183 D PersonaManager: isKioskContainerExistOnDevice
,03-17 06:44:26.189  1017  1533 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
03-17 06:44:26.189  1017  1533 D SecContentProvider2: mCursor = null
,03-17 06:44:26.189  1183  1183 D PanelView: There is/are notification(s) 
,03-17 06:44:26.189  1183  1183 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 06:44:26.199  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.199  3963  4008 I GFX raster: took 0.637448ms for 96*96 texture 0
03-17 06:44:26.199  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88af440 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb88b1bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.209  1183  1183 D PersonaManager: isKioskContainerExistOnDevice
,03-17 06:44:26.209  1183  1183 D PanelView: There is/are notification(s) 
,03-17 06:44:26.209  1183  1183 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 06:44:26.219  3178  4426 D OpenGLRenderer: Render dirty regions requested: true
,03-17 06:44:26.239   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=4, Uoast
,03-17 06:44:26.269  3963  4008 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 06:44:26.279  1183  1183 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-17 06:44:26.279  1818  4368 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-17 06:44:26.289  1017  1534 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,03-17 06:44:26.289  1017  1051 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
,03-17 06:44:26.289  1017  1051 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 06:44:26.289  1017  1051 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 06:44:26.289  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.299  3963  4008 I GFX raster: took 0.821979ms for 96*96 texture 0
03-17 06:44:26.299  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8377510 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb839e128 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.299  3178  3178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 06:44:26.299  3178  4426 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 06:44:26.299  3178  4426 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 06:44:26.299  3178  4426 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 06:44:26.299  3178  4426 I Adreno-EGL: Local Branch: 
03-17 06:44:26.299  3178  4426 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 06:44:26.299  3178  4426 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 06:44:26.299  3178  4426 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 06:44:26.299  3178  4426 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 06:44:26.309  1017  1171 D lights  : lcd : 44 +
,03-17 06:44:26.319  1017  1051 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
,03-17 06:44:26.319  1017  1171 D lights  : lcd : 44 -
03-17 06:44:26.319  1017  1171 D lights  : lcd : 60 +
,03-17 06:44:26.319  1017  1051 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-17 06:44:26.319  3178  4426 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 06:44:26.319  3178  4426 D OpenGLRenderer: Enabling debug mode 0
,03-17 06:44:26.339  1017  1171 D lights  : lcd : 60 -
,03-17 06:44:26.339  1017  1051 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-17 06:44:26.339  1017  1051 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 06:44:26.339  3946  4322 D a       : Opening database auth.proximity.permit_store...
,03-17 06:44:26.339  3963  4008 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 06:44:26.359  3946  4322 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
,03-17 06:44:26.359  3946  4322 D AuthZenTransactionCache: Clearing transaction cache
,03-17 06:44:26.359  4399  4399 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-17 06:44:26.369  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.369  3963  4008 I GFX raster: took 0.623698ms for 96*96 texture 0
03-17 06:44:26.369  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88a92b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88b1bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.369  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 06:44:26.399  1818  4368 I GCoreUlr: Unbound from all location providers
03-17 06:44:26.399  1818  4368 I GCoreUlr: Place inference reporting - stopped
,03-17 06:44:26.439  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.439  3963  4008 I GFX raster: took 0.930417ms for 96*96 texture 0
,03-17 06:44:26.439  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb839e128 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88b1bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.449  3963  4008 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 06:44:26.459  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
,03-17 06:44:26.459  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:26.459  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
,03-17 06:44:26.459  3963  4008 I AMMetaDataParserService: Resource data:2131099648
,03-17 06:44:26.469  3963  4008 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 06:44:26.479  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:26.479  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.479  3963  4008 I GFX raster: took 0.684011ms for 96*96 texture 0
03-17 06:44:26.479  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a2ad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88aea58 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.479  3963  4008 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 06:44:26.499  1818  1818 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-17 06:44:26.499  4399  4399 D ManifestProvider: onCreate()
,03-17 06:44:26.509  1017  1532 I ActivityManager: Killing 3442:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-17 06:44:26.509  1818  1818 I GCoreUlr: DispatchingService.onDestroy()
,03-17 06:44:26.509  1818  1818 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-17 06:44:26.519  1017  1263 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:26.519  1017  1263 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.519  1017  1263 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:26.519  1017  1263 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:26.519  1017  1263 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:26.539  4399  4399 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-17 06:44:26.549  4271  4284 W art     : Suspending all threads took: 50.740ms
,03-17 06:44:26.569  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.569  3963  4008 I GFX raster: took 0.803021ms for 96*96 texture 0
03-17 06:44:26.569  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88abb98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb88b1bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.569  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:26.569  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.569  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:26.569  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:26.569  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:26.579  1818  1818 I GCoreUlr: Unbound from all location providers
,03-17 06:44:26.579  1818  1818 I GCoreUlr: Place inference reporting - stopped
,03-17 06:44:26.599  3963  4008 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 06:44:26.609  4399  4399 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@185c3169
,03-17 06:44:26.609  4399  4399 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
,03-17 06:44:26.609  4399  4399 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-17 06:44:26.609  1017  1523 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,03-17 06:44:26.609  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.609  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.619  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.619  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.639  1017  1041 W libprocessgroup: failed to open /acct/uid_10015/pid_3442/cgroup.procs: No such file or directory,
03-17 06:44:26.639  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.639  3963  4008 I GFX raster: took 0.912917ms for 96*96 texture 0,
03-17 06:44:26.639  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88af440 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb88aea58 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.639  4439  4439 E Zygote  : MountEmulatedStorage(),
03-17 06:44:26.639  4439  4439 E Zygote  : v2
,03-17 06:44:26.649  1017  1523 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4439 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
03-17 06:44:26.649  4439  4439 I libpersona: KNOX_SDCARD checking this for 10135,
03-17 06:44:26.649  4439  4439 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:26.649  4439  4439 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:26.649  4439  4439 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:26.649  4439  4439 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:26.649  1017  1533 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:26.659  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:26.659  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:26.659  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-17 06:44:26.669  3963  4008 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 06:44:26.679  1017  1488 I ActivityManager: Killing 3623:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,03-17 06:44:26.699  4439  4439 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:26.699  4439  4439 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:26.699  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.699  3963  4008 I GFX raster: took 0.650938ms for 96*96 texture 0
03-17 06:44:26.699  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8377510 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88b1bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.719  1017  1263 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:26.719  1017  1263 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:26.719  1017  1263 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:26.719  1017  1263 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 06:44:26.719  3963  4008 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 06:44:26.729  1017  1533 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:26.729  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:26.729  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:26.729  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-17 06:44:26.729  1017  3038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:26.729  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:26.729  1017  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:26.729  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:26.739  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.739  3963  4008 I GFX raster: took 0.741198ms for 96*96 texture 0
03-17 06:44:26.739  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88a92b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88aea58 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.749  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 06:44:26.769  4439  4439 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 06:44:26.769  4439  4439 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:26.769  4439  4439 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:26.779  1017  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,03-17 06:44:26.779  3946  3946 V Herrevad: NQAS connected
,03-17 06:44:26.779  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.779  3963  4008 I GFX raster: took 0.778541ms for 96*96 texture 0
03-17 06:44:26.779  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb839e128 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88b1bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.779  1017  1041 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.789  1017  1041 W libprocessgroup: failed to open /acct/uid_10062/pid_3623/cgroup.procs: No such file or directory
,03-17 06:44:26.819  3963  4008 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 06:44:26.829  1017  1534 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,03-17 06:44:26.829  1017  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.829  1017  1534 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:26.829  1017  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:26.829  1017  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 06:44:26.829  1327  1345 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 06:44:26.859  1017  2828 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:44:26.869  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
03-17 06:44:26.869  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:26.869  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:26.869  3963  4008 I AMMetaDataParserService: Resource data:2131099648
,03-17 06:44:26.879  3963  4008 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 06:44:26.879  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:26.879  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.879  3963  4008 I GFX raster: took 0.692708ms for 96*96 texture 0
03-17 06:44:26.879  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a2ad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88b1bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.879  3963  4008 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 06:44:26.879  1017  1534 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,03-17 06:44:26.889  1017  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.889  1017  1534 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:26.889  1017  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:26.889  1017  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 06:44:26.899  1017  1348 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,03-17 06:44:26.899  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.899  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.899  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.899  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.909  4464  4464 E Zygote  : MountEmulatedStorage()
03-17 06:44:26.909  4464  4464 E Zygote  : v2
03-17 06:44:26.909  4464  4464 I libpersona: KNOX_SDCARD checking this for 10139
03-17 06:44:26.909  4464  4464 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:26.909  4464  4464 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:26.919  4464  4464 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:26.919  4464  4464 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 06:44:26.939  4464  4464 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:26.939  1017  1348 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4464 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
03-17 06:44:26.939  4464  4464 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:26.939  1017  1320 E Watchdog: !@Sync 1
,03-17 06:44:26.959   302   302 I art     : Explicit concurrent mark sweep GC freed 8756(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 31.460ms
,03-17 06:44:26.959  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:26.959  3963  4008 I GFX raster: took 0.633125ms for 96*96 texture 0
03-17 06:44:26.959  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88abb98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb88b1bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:26.979  1017  1150 D SettingsProvider: name = audio_safe_volume_state
,03-17 06:44:26.979  3963  4008 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 06:44:26.979  1818  2096 W GCoreFlp: No location to return for getLastLocation()
,03-17 06:44:26.989  1818  1827 W FusedLocationProvider: location=null
,03-17 06:44:26.989   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 791us total 24.712ms
,03-17 06:44:26.999  1818  2096 W GCoreFlp: No location to return for getLastLocation()
,03-17 06:44:26.999  1818  2099 W FusedLocationProvider: location=null
,03-17 06:44:27.009  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.009   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 696us total 19.971ms
03-17 06:44:27.009  3963  4008 I GFX raster: took 0.635833ms for 96*96 texture 0
03-17 06:44:27.009  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88af440 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8384ea0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.029  1017  1523 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:27.029  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:27.029  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:27.029  3963  4008 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-17 06:44:27.029  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.039  4464  4464 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,03-17 06:44:27.039  4464  4464 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 06:44:27.039  4464  4464 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,03-17 06:44:27.039  4464  4464 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 06:44:27.039  4464  4464 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:44:27.049  1017  3038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:27.049  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.049  1017  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.049  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.079  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.079  3963  4008 I GFX raster: took 0.819062ms for 96*96 texture 0
03-17 06:44:27.079  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8377510 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88b1bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.089  3963  4008 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 06:44:27.099  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.109  3963  4008 I GFX raster: took 0.639531ms for 96*96 texture 0
03-17 06:44:27.109  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88a92b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8384ea0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.109  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 06:44:27.119  1017  3038 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,03-17 06:44:27.119  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.119  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.119  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.129  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.139  4486  4486 E Zygote  : MountEmulatedStorage(),
,03-17 06:44:27.149  4486  4486 E Zygote  : v2,
,03-17 06:44:27.149  4486  4486 I libpersona: KNOX_SDCARD checking this for 10145,
03-17 06:44:27.149  4486  4486 I libpersona: KNOX_SDCARD not a persona,
,03-17 06:44:27.149  1017  3038 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4486 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,03-17 06:44:27.149  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-17 06:44:27.159  3963  4008 I GFX raster: took 0.819220ms for 96*96 texture 0,
03-17 06:44:27.159  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb839e128 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88b1bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.159  4486  4486 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:27.159  3963  4008 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 06:44:27.159  4486  4486 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:27.169  4486  4486 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:27.199  4486  4486 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:27.199  4486  4486 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-17 06:44:27.209  3963  4008 W ContextImpl: Calling a method in the system process without a qualified use,r: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationM,apActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-17 06:44:27.209  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
03-17 06:44:27.229  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-17 06:44:27.229  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.229  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:27.229  3963  4008 I AMMetaDataParserService: Resource data:2131165197
03-17 06:44:27.239  3963  4008 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:44:27.239  3963  4008 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:27.239  3963  4008 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 06:44:27.239  3963  4008 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:27.239  3963  4008 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 06:44:27.239  3963  4008 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 06:44:27.239  3963  4008 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 06:44:27.239  3963  4008 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 06:44:27.249  4486  4486 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 06:44:27.249  4486  4486 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:27.249  4486  4486 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 06:44:27.249  4486  4486 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:27.249  4486  4486 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:44:27.249  1017  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 06:44:27.249  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.249  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.249  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 06:44:27.259  3963  4008 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 06:44:27.259  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
03-17 06:44:27.259  1818  1818 I ConfigService: onCreate
03-17 06:44:27.269  3963  4008 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 06:44:27.299  1017  1523 I ActivityManager: Killing 3659:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,03-17 06:44:27.299  1017  1501 I ActivityManager: Killing 3642:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,03-17 06:44:27.319  3963  4008 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 06:44:27.349   287   287 E SMD     : DCD OFF
,03-17 06:44:27.359  3963  4008 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 06:44:27.399  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 06:44:27.409  1017  1041 W libprocessgroup: failed to open /acct/uid_10094/pid_3642/cgroup.procs: No such file or directory
03-17 06:44:27.409  1017  1041 W libprocessgroup: failed to open /acct/uid_10022/pid_3659/cgroup.procs: No such file or directory
,03-17 06:44:27.409  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-17 06:44:27.409  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.409  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 06:44:27.409  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:27.409  3963  4008 I AMMetaDataParserService: Resource data:2131165197
,03-17 06:44:27.409  3963  4008 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
,03-17 06:44:27.409  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:27.419  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:27.429  3963  4008 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 06:44:27.439  3963  4008 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 06:44:27.449  1017  3038 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:27.489  3963  4008 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 06:44:27.509  1017  1532 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:27.509  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 06:44:27.519  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:27.519  1017  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:27.519  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.519  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
03-17 06:44:27.519  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-17 06:44:27.519  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.519  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:27.519  3963  4008 I AMMetaDataParserService: Resource data:2131165197
,03-17 06:44:27.529  3963  4008 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
,03-17 06:44:27.529  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:27.539  3963  4008 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 06:44:27.569  3963  4008 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 06:44:27.579  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:27.579  1017  1348 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:27.589  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 06:44:27.589  3963  4008 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 06:44:27.589  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,03-17 06:44:27.589  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:27.589  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:27.589  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:27.589  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:27.619  3963  4008 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-17 06:44:27.649  3963  4008 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:27.649  3963  4008 I AMMetaDataParserService: Resource data:2131099648
,03-17 06:44:27.659  3963  4008 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 06:44:27.659  3963  4008 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:44:27.659  3963  4008 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 06:44:27.659  3963  4008 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 06:44:27.659  3963  4008 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:44:27.659  3963  4008 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
,03-17 06:44:27.659  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:27.679  3963  4008 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-17 06:44:27.699  3963  4008 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-17 06:44:27.719  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-17 06:44:27.719  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-17 06:44:27.719  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-17 06:44:27.719  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
03-17 06:44:27.719  3963  4008 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 06:44:27.759  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,03-17 06:44:27.759  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.759  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.769  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.769  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.779  1017  3038 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:27.779  1017  1029 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4512 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,03-17 06:44:27.789  4512  4512 E Zygote  : MountEmulatedStorage(),
03-17 06:44:27.789  4512  4512 E Zygote  : v2
,03-17 06:44:27.789  4512  4512 I libpersona: KNOX_SDCARD checking this for 10072
03-17 06:44:27.789  4512  4512 I libpersona: KNOX_SDCARD not a persona,
,03-17 06:44:27.789  4512  4512 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:27.799  4512  4512 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:27.799  4512  4512 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 06:44:27.799  1017  1151 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:27.799  1017  1532 D ActivityManager: startService callerProcessName:com.android.email, calleePkgName: com.android.email
,03-17 06:44:27.799  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.809  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:27.809  1017  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:27.809  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-17 06:44:27.819  4512  4512 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:27.819  4512  4512 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:27.839  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
,03-17 06:44:27.839  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:27.849  3963  4008 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:27.849  3963  4008 I AMMetaDataParserService: Resource data:2131165220
,03-17 06:44:27.859  3963  4008 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 06:44:27.859  3963  4008 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-17 06:44:27.859  3963  4008 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 06:44:27.869  3963  4008 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 06:44:27.869  3963  4008 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:27.869  3963  4008 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 06:44:27.869  3963  4008 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
,03-17 06:44:27.869  3963  4008 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:27.869  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.879  3963  4008 I GFX raster: took 0.919480ms for 96*96 texture 0
,03-17 06:44:27.879  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8aa0130 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a9fe60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.879  1017  1348 D ActivityManager: startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,03-17 06:44:27.879  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.879  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.879  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.879  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.899  4533  4533 E Zygote  : MountEmulatedStorage(),
03-17 06:44:27.899  4533  4533 E Zygote  : v2
03-17 06:44:27.899  4533  4533 I libpersona: KNOX_SDCARD checking this for 10146
03-17 06:44:27.899  4533  4533 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:27.899  4533  4533 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:27.899  4533  4533 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 06:44:27.899  1017  1348 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4533 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-17 06:44:27.899  4533  4533 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:27.909  1017  1348 I ActivityManager: Killing 3701:com.samsung.android.MtpApplication/1000 (adj 15): empty #31,
,03-17 06:44:27.909  1017  1348 I ActivityManager: Killing 3678:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #32,
,03-17 06:44:27.919  3963  4008 I AMMetaDataParserService: Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,03-17 06:44:27.939  4533  4533 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:27.939  4533  4533 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:27.959  4512  4512 D BadgeProvider: onCreate
,03-17 06:44:27.959  4512  4512 D BadgeProvider: DatabaseHelper
,03-17 06:44:27.979  4512  4522 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 06:44:27.999  3963  4008 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.999  4533  4533 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 06:44:27.999  3963  4008 I GFX raster: took 0.752292ms for 96*96 texture 0
,03-17 06:44:27.999  3963  4008 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a9ff80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ab43e8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:28.009  1489  1489 D Launcher.Model: reloadBadges entered.
,03-17 06:44:28.009  4512  4522 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 06:44:28.009  4512  4522 D BadgeProvider: sendNotify, [notify] : null
,03-17 06:44:28.009  4512  4522 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,03-17 06:44:28.009  4512  4522 D BadgeProvider: update, [BadgeCount] : badgecount=0
,03-17 06:44:28.009  4512  4522 D BadgeProvider: update, [UpdateCount] : 1
,03-17 06:44:28.029  3963  4008 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.,settings.wifi.WifiSecSetupActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 06:44:28.049  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3701/cgroup.procs: No such file or directory
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 06:44:28.049  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3678/cgroup.procs: No such file or directory
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.039  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-17 06:44:28.129  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-17 06:44:28.129  1017  1532 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.139  1017  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-17 06:44:28.139  1017  1534 I ActivityManager: Killing 3708:com.sec.factory.camera/1000 (adj 15): empty #31
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.209  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3708/cgroup.procs: No such file or directory,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog,
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
,03-17 06:44:28.049  3963  4008 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-17 06:44:28.229  1017  3038 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:28.229  1017  1504 D ActivityManager: startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
,03-17 06:44:28.229  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 06:44:28.239  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.239  1017  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:28.239  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-17 06:44:28.239  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 06:44:28.239  1017  1534 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,03-17 06:44:28.239  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.249  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.249  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.249  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.249  4269  4316 W dex2oat : Verification of void maps.k.b$b.a(byte[], byte[]) took 125.662ms
,03-17 06:44:28.259  1017  1534 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4550 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:28.259  4550  4550 E Zygote  : MountEmulatedStorage()
03-17 06:44:28.259  4550  4550 E Zygote  : v2
03-17 06:44:28.259  4550  4550 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:28.259  4550  4550 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:28.259  4550  4550 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:28.269  4550  4550 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:28.269  4550  4550 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:28.279  4269  4315 W dex2oat : Verification of void maps.k.b$f.a(byte[], byte[]) took 106.213ms,
03-17 06:44:28.279  1017  1263 I ActivityManager: Killing 3422:com.sec.pcw.device/1000 (adj 15): empty #31,
,03-17 06:44:28.299  4550  4550 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:28.299  4550  4550 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:28.309  1017  1030 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
,03-17 06:44:28.309  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{3a51d692 u0 com.samsung.android.providers.context/.ContextService}
,03-17 06:44:28.319  4486  4531 I Process : Sending signal. PID: 4486 SIG: 9
,03-17 06:44:28.319  3823  3897 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-17 06:44:28.339  1017  1523 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,03-17 06:44:28.339  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.339  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:28.339  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:28.339  1017  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.359  4269  4269 W dex2oat : Verification of void maps.k.b$h.a(byte[], byte[]) took 106.443ms
,03-17 06:44:28.359  4570  4570 E Zygote  : MountEmulatedStorage(),
03-17 06:44:28.359  4570  4570 E Zygote  : v2
03-17 06:44:28.359  4570  4570 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:28.359  4570  4570 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:28.369  1017  1523 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4570 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:28.369   254   254 E lowmemorykiller: Error writing /proc/4486/oom_score_adj; errno=22
,03-17 06:44:28.369  1017  1523 I ActivityManager: Killing 3730:com.wssnps/1000 (adj 15): empty #31
,03-17 06:44:28.379  4533  4556 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,03-17 06:44:28.379  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3422/cgroup.procs: No such file or directory
,03-17 06:44:28.389  4570  4570 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:28.389  4570  4570 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:28.389  4570  4570 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:28.409  1017  1030 W ActivityManager: getTasks: caller 10146 does not hold GET_TASKS; limiting output
,03-17 06:44:28.409  4570  4570 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:28.409  4570  4570 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:28.419  4533  4556 I Process : Sending signal. PID: 4533 SIG: 9
,03-17 06:44:28.429  1017  1030 I ActivityManager: Process com.android.email (pid 4486)(adj 11) has died(54,1083)
,03-17 06:44:28.449  4570  4570 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 06:44:28.449  4570  4570 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,03-17 06:44:28.449  4570  4570 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 06:44:28.449  4570  4570 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-17 06:44:28.449  1017  1504 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 06:44:28.449   254   254 E lowmemorykiller: Error writing /proc/4533/oom_score_adj; errno=22
,03-17 06:44:28.459  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:28.459  1017  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:28.459  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 06:44:28.469  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 06:44:28.469  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 06:44:28.469  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.469  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:28.469  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 06:44:28.469   254   254 E lowmemorykiller: Error writing /proc/4533/oom_score_adj; errno=22
,03-17 06:44:28.469  3577  3577 I Hs20UtilService: Starting #2
,03-17 06:44:28.469  3577  3597 I Hs20UtilService: Message received 5011
,03-17 06:44:28.479  4570  4570 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 06:44:28.479  4570  4570 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 06:44:28.479  4570  4570 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 06:44:28.479  4570  4570 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-17 06:44:28.479  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.example.hello, hostingType: broadcast
,03-17 06:44:28.479  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.479  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.479  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:28.479  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.499  4586  4586 E Zygote  : MountEmulatedStorage(),
,03-17 06:44:28.499  4586  4586 E Zygote  : v2
03-17 06:44:28.499  4586  4586 I libpersona: KNOX_SDCARD checking this for 10174
,03-17 06:44:28.499  4586  4586 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:28.499  4586  4586 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:28.509   254   254 E lowmemorykiller: Error writing /proc/4533/oom_score_adj; errno=22,
03-17 06:44:28.509  1017  1488 I ActivityManager: Start proc com.example.hello for broadcast com.example.hello/io.jxcore.node.ConnectivityChangeListener: pid=4586 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,03-17 06:44:28.509  4586  4586 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:28.519  4586  4586 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 06:44:28.529  4586  4586 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:28.529  4586  4586 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:28.539  1017  1534 I ActivityManager: Process com.android.exchange (pid 4533)(adj 11) has died(54,1083)
,03-17 06:44:28.549  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{259da5ea u0 com.android.settings/.wifi.WifiCredService}
,03-17 06:44:28.589  1017  1097 V AlarmManager: waitForAlarm result :4
,03-17 06:44:28.679  4586  4586 D jxcore_app_log: JniHelper::setJavaVM(0xb7fc8450), pthread_self() = -1225257272
,03-17 06:44:28.679  4586  4586 E JX-Cordova: JXcore wasn't initialized yet
,03-17 06:44:28.679  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.679  1017  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:28.689  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.689  1017  1532 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 06:44:28.689  1017  1532 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,03-17 06:44:28.689  1017  1532 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-17 06:44:28.689  1017  1532 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 06:44:28.689  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.689  1017  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:28.689  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.699  1017  1263 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:28.699  1017  1263 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:28.699  1017  1263 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.709  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.709  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:28.709  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.739  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:28.739  1017  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:28.739  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.739  1017  1348 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:28.739  1017  1348 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.739  1017  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:28.749  1017  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.749  1818  4602 E MDM     : [232] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 06:44:28.749  1017  1534 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.749  1017  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:28.749  1017  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.759  1017  1488 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:28.759  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,03-17 06:44:28.759  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.759  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:28.759  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.769  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.769  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:28.769  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.779  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:28.779  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:28.779  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.789  1017  1532 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:28.789  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 06:44:28.789  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.789  1017  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:28.789  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.789  3946  4603 D LocationInitializer: Restart initialization of location
,03-17 06:44:28.799  1017  1501 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 06:44:28.799  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 06:44:28.809  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:28.809  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:28.809  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.819  1017  1041 W ProcessCpuTracker: Skipping unknown process pid 4533
,03-17 06:44:28.829  3123  3438 I jxcore-log: INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
03-17 06:44:28.829  3123  3438 I jxcore-log: 
,03-17 06:44:28.829  3123  3438 I jxcore-log: INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-17 06:44:28.829  3123  3438 I jxcore-log: 
,03-17 06:44:28.849  3123  3438 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 06:44:28.849  3123  3438 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 06:44:28.849  3123  3438 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 06:44:28.849  3123  3438 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 06:44:28.849  3123  3438 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 06:44:28.849  3123  3438 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 06:44:28.849  3123  3438 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 06:44:28.849  3123  3438 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 06:44:28.849  3123  3438 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-17 06:44:28.849  3123  3438 I jxcore-log: INFO thaliMobileNativeWrapper Method networkChanged registered to native
03-17 06:44:28.849  3123  3438 I jxcore-log: 
,03-17 06:44:28.859  3123  3438 I jxcore-log: INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
03-17 06:44:28.859  3123  3438 I jxcore-log: 
,03-17 06:44:28.969  1017  1534 I art     : Explicit concurrent mark sweep GC freed 27872(1515KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/40MB, paused 2.611ms total 157.040ms
,03-17 06:44:28.979  4269  4269 I dex2oat : dex2oat took 5.052s (threads: 4)
,03-17 06:44:29.019  3946  4254 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
03-17 06:44:29.019  3946  4254 D DexOptUtils: Set odex to world readable.
,03-17 06:44:29.019  3946  4254 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
,03-17 06:44:29.039  1464  1473 D TP/SmsProvider: query,matched:0, calling pid = 3946
,03-17 06:44:29.039  1464  1473 D TP/SmsProvider: match 0:Elapsed time : 4.217 ms
,03-17 06:44:29.039  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-17 06:44:29.039  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,03-17 06:44:29.049  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.049  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:29.049  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.059  1017  3038 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:29.059  1017  3038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,03-17 06:44:29.059  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.059  1017  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:29.059  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.069  3946  3956 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@359fc3db)
,03-17 06:44:29.079  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,03-17 06:44:29.079  1818  1818 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 06:44:29.089  1464  1758 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 3946
,03-17 06:44:29.099  1818  1818 D a       : Opening database auth.proximity.permit_store...
,03-17 06:44:29.109  1017  1534 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.109  1017  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:29.109  1017  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.129  1017  1263 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:29.139  1017  1263 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:29.139  1017  1263 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:29.139  1017  1263 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.139  1464  1476 D TP/SmsProvider: query,matched:0, calling pid = 3946
,03-17 06:44:29.139  1464  1476 D TP/SmsProvider: match 0:Elapsed time : 1.220 ms
,03-17 06:44:29.149  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3730/cgroup.procs: No such file or directory
,03-17 06:44:29.169  1464  3131 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 3946
,03-17 06:44:29.179  1017  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 06:44:29.179  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,03-17 06:44:29.179  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:29.179  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:29.179  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.189  1017  1348 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:29.189  1017  1348 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,03-17 06:44:29.189  1017  1348 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.189  1017  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:29.189  1017  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.199  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.199  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:29.199  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.209  1818  1818 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:29.219  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:29.219  1017  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:29.219  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.229  1017  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 06:44:29.229  1017  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,03-17 06:44:29.229  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.229  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:29.229  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.239  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.239  1017  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:29.239  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 06:44:29.259  1017  1348 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 06:44:29.259  1017  1348 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 06:44:29.259  1017  1348 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.259  1017  1348 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:29.259  1017  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 06:44:29.269  3577  3577 I Hs20UtilService: Starting #3
,03-17 06:44:29.269  3577  3597 I Hs20UtilService: Message received 5011
,03-17 06:44:29.269  1017  1143 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 06:44:29.269  1017  1143 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 06:44:29.269  1017  1143 E WifiNative-wlan0: invaild command id : 215
,03-17 06:44:29.269  1818  2096 W GCoreFlp: No location to return for getLastLocation()
,03-17 06:44:29.269  1818  4614 W FusedLocationProvider: location=null
,03-17 06:44:29.299  3946  4613 W IcingInternalCorpora: getNumBytesRead when not calculated.
,03-17 06:44:29.299  4570  4570 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 06:44:29.299  4570  4570 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,03-17 06:44:29.299  4570  4570 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 06:44:29.299  4570  4570 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-17 06:44:29.319  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,03-17 06:44:29.319  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 06:44:29.319  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED,
,03-17 06:44:29.319  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-17 06:44:29.319  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false,
03-17 06:44:29.319  1316  1316 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 06:44:29.319  1017  1263 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast,
,03-17 06:44:29.329  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:29.329  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:29.329  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:29.329  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:29.339  1017  1263 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4626 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 06:44:29.339  4626  4626 E Zygote  : MountEmulatedStorage(),
03-17 06:44:29.339  4626  4626 I libpersona: KNOX_SDCARD checking this for 10068
03-17 06:44:29.339  4626  4626 E Zygote  : v2
,03-17 06:44:29.339  4626  4626 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:29.349  4626  4626 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:29.349  4626  4626 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:29.349  4626  4626 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 06:44:29.369  4626  4626 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:29.369  4626  4626 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:29.379  4626  4626 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 06:44:29.399  4626  4626 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-17 06:44:29.399  4626  4626 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,03-17 06:44:29.429  4626  4626 D FileShare-Client: Outbound.stopDelayTimer - 
,03-17 06:44:29.439  3879  3879 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-17 06:44:29.439  1017  1534 I ActivityManager: Killing 3775:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,03-17 06:44:29.449  1017  1534 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 06:44:29.449  1017  1534 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,03-17 06:44:29.449  1017  1534 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,03-17 06:44:29.449  1017  1534 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 06:44:29.469  1017  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:29.469  1818  4641 E MDM     : [247] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 06:44:29.469  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:29.469  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:29.469  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.469  1017  1523 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:29.479  1017  1523 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0,
,03-17 06:44:29.479  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.479  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:29.479  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 06:44:29.479  3946  4642 D LocationInitializer: Restart initialization of location
,03-17 06:44:29.479  1017  1348 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 06:44:29.479  1017  1348 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 06:44:29.479  1017  1348 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.479  1017  1348 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:29.479  1017  1348 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.489  1818  1818 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 06:44:29.499  1017  1523 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:29.499  1017  1523 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,03-17 06:44:29.499  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.499  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:29.499  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.509  1818  1818 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:29.509  1017  1523 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:29.509  1017  1523 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,03-17 06:44:29.509  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:29.509  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:29.509  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:29.519  1017  1532 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 06:44:29.529  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 06:44:29.529  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:29.529  1017  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:29.529  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 06:44:29.529  3577  3577 I Hs20UtilService: Starting #4
,03-17 06:44:29.529  1818  2096 W GCoreFlp: No location to return for getLastLocation()
,03-17 06:44:29.529  1818  4643 W FusedLocationProvider: location=null
,03-17 06:44:29.529  3577  3597 I Hs20UtilService: Message received 5007
,03-17 06:44:29.529  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 06:44:29.539  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 06:44:29.539  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 06:44:29.539  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-17 06:44:29.539  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 06:44:29.539  1316  1316 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 06:44:29.559  1017  1151 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-17 06:44:29.559  1017  1151 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 06:44:29.559  1017  1151 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:29.559  1017  1151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:29.559  1017  1151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 06:44:29.559  3577  3577 I Hs20UtilService: Starting #5
,03-17 06:44:29.559  3577  3597 I Hs20UtilService: Message received 5007
,03-17 06:44:29.559  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 06:44:29.559  1316  1316 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 06:44:29.569  1017  1041 W libprocessgroup: failed to open /acct/uid_10100/pid_3775/cgroup.procs: No such file or directory
,03-17 06:44:29.579  1017  1501 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 06:44:29.579  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 06:44:29.579  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.579  1017  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:29.579  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 06:44:29.579  3577  3577 I Hs20UtilService: Starting #6
,03-17 06:44:29.579  3577  3597 I Hs20UtilService: Message received 5007
,03-17 06:44:29.579  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 06:44:29.589  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 06:44:29.589  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 06:44:29.589  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-17 06:44:29.589  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,03-17 06:44:29.589  1316  1316 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 06:44:29.599  1017  1532 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 06:44:29.599  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 06:44:29.599  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.599  1017  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:29.599  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 06:44:29.609  3577  3577 I Hs20UtilService: Starting #7
,03-17 06:44:29.609  3577  3597 I Hs20UtilService: Message received 5007
,03-17 06:44:29.609  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 06:44:29.609  1316  1316 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 06:44:29.619  1017  1504 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,03-17 06:44:29.629  1017  1348 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-17 06:44:29.629  1017  1348 D SecContentProvider2: mCursor = null
,03-17 06:44:29.629  1017  1029 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-17 06:44:29.629  1017  1029 D SecContentProvider2: mCursor = null
,03-17 06:44:29.639  1017  1532 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,03-17 06:44:29.639  1017  1532 D SecContentProvider2: mCursor = null
,03-17 06:44:29.639  1017  3038 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
03-17 06:44:29.639  1017  3038 D SecContentProvider2: mCursor = null
,03-17 06:44:29.639  1017  1523 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
,03-17 06:44:29.639  1017  1523 D SecContentProvider2: mCursor = null
,03-17 06:44:29.649  1017  1533 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
,03-17 06:44:29.649  1017  1533 D SecContentProvider2: mCursor = null
,03-17 06:44:29.649  1017  1151 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,03-17 06:44:29.649  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 06:44:29.649  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:29.649  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:29.649  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:29.659  4646  4646 E Zygote  : MountEmulatedStorage()
,03-17 06:44:29.659  4646  4646 E Zygote  : v2
03-17 06:44:29.669  4646  4646 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:29.669  4646  4646 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:29.669  4646  4646 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:29.669  4646  4646 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 06:44:29.669  4646  4646 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:29.669  1017  1151 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4646 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 06:44:29.689  4646  4646 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:29.689  4646  4646 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:29.709  1017  1504 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 52093
,03-17 06:44:29.709  1017  1504 D PowerManagerService: [s] UserActivityState : 2 -> 1
03-17 06:44:29.709  1017  1504 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
03-17 06:44:29.709  1017  1504 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{1000}) (elapsedTime=3421)
,03-17 06:44:29.709   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,03-17 06:44:29.719  4646  4646 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-17 06:44:29.719  4646  4646 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-17 06:44:29.719  4646  4646 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 06:44:29.729  1017  1533 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,03-17 06:44:29.729  4646  4646 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 06:44:29.729  4646  4646 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 06:44:29.729  4646  4646 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 06:44:29.729  4646  4646 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
03-17 06:44:29.729  1183  1183 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 06:44:29.739  1017  1534 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=17, mSplitNum[2]=26, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=34
03-17 06:44:29.739  1017  1534 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,03-17 06:44:29.739  1017  1534 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,03-17 06:44:29.739  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:29.739  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:29.739  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:29.739  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:29.749  4663  4663 E Zygote  : MountEmulatedStorage()
,03-17 06:44:29.759  4663  4663 E Zygote  : v2
03-17 06:44:29.759  4663  4663 I libpersona: KNOX_SDCARD checking this for 10111
,03-17 06:44:29.759  4663  4663 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:29.759  4663  4663 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:29.759  4663  4663 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:29.759  4663  4663 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 06:44:29.759  1017  1534 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4663 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:29.759  1017  1042 I ActivityManager: Killing 3855:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,03-17 06:44:29.769  3602  3602 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 06:44:29 GMT+01:00 2016
,03-17 06:44:29.769  1741  1741 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 06:44:29.769  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-17 06:44:29.779  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 06:44:29.779  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:29.779  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:29.779  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 06:44:29.779  4663  4663 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:29.779  4663  4663 D ActivityThread: Added TimaKeyStore provider,
,03-17 06:44:29.779  4570  4570 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 06:44:29.779  4570  4570 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 06:44:29.779  4570  4570 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 06:44:29.789  4570  4570 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-17 06:44:29.789  1327  1345 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,03-17 06:44:29.789  3602  3602 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 06:44:29.799  1017  1534 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,03-17 06:44:29.799  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:29.799  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:29.799  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:29.799  1017  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:29.809  4678  4678 E Zygote  : MountEmulatedStorage()
03-17 06:44:29.809  4678  4678 E Zygote  : v2
03-17 06:44:29.809  4678  4678 I libpersona: KNOX_SDCARD checking this for 10159
03-17 06:44:29.809  4678  4678 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:29.809  4678  4678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:29.819  4678  4678 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:29.819  4678  4678 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-17 06:44:29.819  1017  1534 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4678 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 06:44:29.829  1741  1741 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-17 06:44:29.829  1741  1741 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
03-17 06:44:29.829  1741  1741 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-17 06:44:29.829  1741  1741 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-17 06:44:29.829  3602  3602 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 06:44:29.839  3602  3602 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 06:44:29.839  3602  3602 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 06:44:29.839  1741  1741 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 06:44:29.849  3602  4685 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 06:44:29.849  1741  1741 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 06:44:29.849  1017  1533 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,03-17 06:44:29.849  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:29.849  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:29.849  3602  4685 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
03-17 06:44:29.849  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:29.849  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:29.859  4678  4678 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:29.859  4678  4678 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:29.859  3602  4685 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false,
,03-17 06:44:29.859  3602  4685 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START,
,03-17 06:44:29.869  3602  4685 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START ,
,03-17 06:44:29.869  4694  4694 E Zygote  : MountEmulatedStorage()
03-17 06:44:29.869  4694  4694 E Zygote  : v2
03-17 06:44:29.869  4694  4694 I libpersona: KNOX_SDCARD checking this for 10081
03-17 06:44:29.869  4694  4694 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:29.869  4694  4694 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:29.869  1017  1533 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4694 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:44:29.879  3602  4685 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,03-17 06:44:29.879  4694  4694 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:29.879  3602  4685 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
03-17 06:44:29.879  4694  4694 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-17 06:44:29.889  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3855/cgroup.procs: No such file or directory
,03-17 06:44:29.899  3602  3602 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 06:44:29.899   302   302 I art     : Explicit concurrent mark sweep GC freed 8727(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 24.275ms
,03-17 06:44:29.909  4694  4694 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:29.919  4694  4694 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:29.919   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.468ms
,03-17 06:44:29.939   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 18.146ms
,03-17 06:44:29.949  3268  4710 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 06:44:29.949  3268  4710 I DBG_POLICYDM: [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,03-17 06:44:29.949  3268  4710 E DBG_POLICYDM: [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,03-17 06:44:29.989  3268  4710 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 06:44:29.989  3268  4710 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 06:44:29.989  3268  4710 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 06:44:29.989  3268  4710 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 06:44:29.989  3268  4710 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 06:44:29.999  3268  4710 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 06:44:29.999  4133  4133 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,03-17 06:44:29.999  3268  4710 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 06:44:29.999  3268  4710 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-17 06:44:30.009  3268  4710 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,03-17 06:44:30.009  4161  4161 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,03-17 06:44:30.009  4161  4161 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-17 06:44:30.009  4161  4161 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-17 06:44:30.029  4161  4161 I SA      : [SLFUCHKMGR] constructor called
,03-17 06:44:30.039  3268  4710 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 06:44:30.039  4161  4161 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-17 06:44:30.039  4161  4161 I SA      : [OR] == isSIMCardReady false ==
,03-17 06:44:30.109  4161  4161 I SA      : [SCU] == networkStateCheck == true
,03-17 06:44:30.109  4161  4161 I SA      : [DM] getCountryCodeFromCSC : PL
,03-17 06:44:30.109  4161  4161 I SA      : isChinaCountryCode : false
03-17 06:44:30.109  4161  4161 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-17 06:44:30.109  4161  4161 I SA      : [OR] == networkStateCheck true ==
,03-17 06:44:30.129  3946  4715 I iu.SyncManager: SYNC; picasa accounts
,03-17 06:44:30.169  4663  4663 I MusicStore: Database version: 108
,03-17 06:44:30.239  3946  3946 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-17 06:44:30.239  4161  4161 I SA      : [OR] GetMyCountryZoneTask
,03-17 06:44:30.239  4161  4161 I SA      : [OR] onReceive END
,03-17 06:44:30.239  3946  3946 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-17 06:44:30.239  1017  1534 I ActivityManager: Killing 3823:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-17 06:44:30.249  1237  1237 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-17 06:44:30.249  1017  1533 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 06:44:30.249  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 06:44:30.249  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:30.249  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:30.249  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 06:44:30.259  1017  3038 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,03-17 06:44:30.259  1017  3038 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,03-17 06:44:30.259  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:30.259  1017  3038 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:30.259  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 06:44:30.259   257   440 I SurfaceFlinger: id=12 Removed Uoast (8/9)
,03-17 06:44:30.259   257  1099 I SurfaceFlinger: id=12 Removed Uoast (-2/9)
,03-17 06:44:30.279  1017  1151 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 06:44:30.279  1017  1151 D SecContentProvider2: mCursor = null
,03-17 06:44:30.289  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 06:44:30.289  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 06:44:30.289  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:30.289  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:30.289  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:30.299  1017  1151 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,03-17 06:44:30.299  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:30.299  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:30.299  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:30.299  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:30.309  4723  4723 E Zygote  : MountEmulatedStorage(),
03-17 06:44:30.309  4723  4723 I libpersona: KNOX_SDCARD checking this for 10010
03-17 06:44:30.309  4723  4723 E Zygote  : v2
,03-17 06:44:30.309  4723  4723 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:30.309  4723  4723 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:30.319  4723  4723 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:30.319  4723  4723 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 06:44:30.329  1017  1151 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4723 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 06:44:30.339  4723  4723 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:30.339  4723  4723 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:30.349   287   287 E SMD     : DCD OFF
,03-17 06:44:30.349  4161  4721 I SA      : [SRS] prepareGetMyCountryZone
,03-17 06:44:30.359  4161  4721 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 06:44:30.359  4161  4721 I SA      : [SSP] query invoked
,03-17 06:44:30.369  3946  4715 I iu.UploadsManager: num queued entries: 0
03-17 06:44:30.369  4161  4721 I SA      : [TPMU] GetMccFromDB : null
03-17 06:44:30.369  4161  4721 I SA      : [SCU] getMccFromPreferece mcc = 260
03-17 06:44:30.369  4161  4721 I SA      : [TPM] isNoProxy(default) : true
,03-17 06:44:30.369  3946  4715 I iu.UploadsManager: num updated entries: 0
,03-17 06:44:30.379  3946  4715 I iu.SyncManager: NEXT; no task
03-17 06:44:30.379  4161  4721 E File    : fail readDirectory() errno=2
,03-17 06:44:30.409  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,03-17 06:44:30.409  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:30.409  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:30.409  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:30.409  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:30.419  4663  4663 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 06:44:30.419  4663  4663 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 06:44:30.419  4741  4741 E Zygote  : MountEmulatedStorage(),
03-17 06:44:30.419  4741  4741 E Zygote  : v2
03-17 06:44:30.419  4741  4741 I libpersona: KNOX_SDCARD checking this for 10113
03-17 06:44:30.419  4741  4741 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:30.419  4741  4741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:30.429  4741  4741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:30.429  4741  4741 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:30.429  1017  1488 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4741 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:30.429  1017  1041 W libprocessgroup: failed to open /acct/uid_10031/pid_3823/cgroup.procs: No such file or directory
,03-17 06:44:30.449  4741  4741 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:30.449  4741  4741 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:30.459  4663  4663 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 06:44:30.519  4663  4663 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 06:44:30.519  4663  4663 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3fd0d2f1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 06:44:30.519  4663  4663 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 06:44:30.519  4663  4663 D AndroidMusic: GMSCore installation verified
,03-17 06:44:30.589  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 06:44:30.589  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:30.589  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:30.599  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:30.599  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:30.599  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:30.599  4723  4723 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-17 06:44:30.649  1017  1533 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 06:44:30.649  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,03-17 06:44:30.649  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:30.649  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:30.649  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 06:44:30.659  4663  4663 I ConfigStore: Config Database version: 1
,03-17 06:44:30.759   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 06:44:30.759   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:30.759  4663  4663 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 06:44:30.769   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 06:44:30.769   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:30.769  4663  4663 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 06:44:30.769   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 06:44:30.769   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:30.769  4663  4663 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 06:44:30.799  4723  4723 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-17 06:44:30.799  1017  1534 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:30.799  1017  1534 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-17 06:44:30.809  1017  1523 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,03-17 06:44:30.809  1017  1523 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,03-17 06:44:30.819  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:30.819  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:30.819  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 06:44:30.839  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 06:44:30.839  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,03-17 06:44:30.849  1017  1029 W ActivityManager: userId = 0, bbcId = -10000,
03-17 06:44:30.849  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:30.849  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 06:44:30.869  1017  1501 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 06:44:30.879  1017  1263 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 06:44:30.879  1017  1532 I AudioService: getStreamVolume 3 index 0
,03-17 06:44:30.889  4663  4663 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-17 06:44:30.899  4663  4663 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-17 06:44:30.909  4663  4663 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 06:44:30.939  1017  1501 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 06:44:30.939  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 06:44:30.939  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:30.939  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:30.939  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 06:44:30.939  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 06:44:30.949  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,03-17 06:44:30.949  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:30.949  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:30.949  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 06:44:30.949  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 06:44:30.949  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,03-17 06:44:30.949  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:30.959  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:30.959  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 06:44:30.959  1017  1348 I ActivityManager: Killing 3963:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-17 06:44:30.969  1017  1534 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 06:44:30.979  4663  4663 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 06:44:30.979  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,03-17 06:44:30.979  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:30.989  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:30.989  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:30.989  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:31.009  4766  4766 E Zygote  : MountEmulatedStorage()
03-17 06:44:31.009  4766  4766 E Zygote  : v2
03-17 06:44:31.009  4766  4766 I libpersona: KNOX_SDCARD checking this for 10002
03-17 06:44:31.009  4766  4766 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:31.009  4766  4766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 06:44:31.009  4766  4766 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:31.009  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4766 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 06:44:31.019  4766  4766 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 06:44:31.019  1017  1532 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps,
03-17 06:44:31.019  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,03-17 06:44:31.019  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:31.019  1017  1532 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 06:44:31.019  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-17 06:44:31.029  4723  4723 D hcjo    : AutoUpdateManager:IDLE:execute
,03-17 06:44:31.039  4723  4723 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-17 06:44:31.039  4723  4723 D InitializeManagerStateMachine: exit::IDLE
,03-17 06:44:31.039  4723  4723 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-17 06:44:31.039  4723  4723 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
03-17 06:44:31.039  4723  4723 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-17 06:44:31.039  4723  4723 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-17 06:44:31.039  4723  4723 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-17 06:44:31.039  4723  4723 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-17 06:44:31.039  4723  4723 D InitializeManagerStateMachine: entry::SUCCESS
03-17 06:44:31.039  4723  4723 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-17 06:44:31.049  1017  1501 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
03-17 06:44:31.049  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-17 06:44:31.049  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:31.049  1017  1501 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:31.049  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-17 06:44:31.059  4723  4723 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,03-17 06:44:31.059  4663  4663 W GoogleHttpClient: Failed to load SSLCertificateSocketFactory from package
03-17 06:44:31.059  4663  4663 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,03-17 06:44:31.059  4663  4663 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,03-17 06:44:31.059  1017  1488 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 06:44:31.059  1017  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 06:44:31.059  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:31.059  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:31.059  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 06:44:31.069   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 06:44:31.069   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:31.069  4741  4781 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 06:44:31.069  4766  4766 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:31.069  4766  4766 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:31.079  4723  4723 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,03-17 06:44:31.079  4723  4723 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,03-17 06:44:31.079  4723  4723 D InitializeManagerStateMachine: exit::SUCCESS
03-17 06:44:31.079  4723  4723 D InitializeManagerStateMachine: entry::IDLE
,03-17 06:44:31.089   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 06:44:31.089   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:31.089  4741  4781 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 06:44:31.099  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3963/cgroup.procs: No such file or directory
,03-17 06:44:31.109   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 06:44:31.109   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:31.109  1017  1533 I ActivityManager: Killing 3805:com.google.android.gm/u0a101 (adj 15): empty #31
,03-17 06:44:31.119  1017  1533 I ActivityManager: Killing 3759:com.samsung.android.sm/1000 (adj 15): empty #32
,03-17 06:44:31.119  4741  4787 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 06:44:31.119   256   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 06:44:31.119   256   524 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:31.119  4741  4787 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 06:44:31.169  1017  1501 I ActivityManager: Killing 4002:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,03-17 06:44:31.179  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,03-17 06:44:31.179  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:31.179  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:31.179  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:31.179  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:31.189  1017  1488 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4790 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:31.189  4790  4790 E Zygote  : MountEmulatedStorage()
,03-17 06:44:31.189  4790  4790 E Zygote  : v2
,03-17 06:44:31.199  4790  4790 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 06:44:31.199  4790  4790 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:31.199  4790  4790 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:31.199  4790  4790 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:31.199  4790  4790 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:31.229  4790  4790 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:31.229  4790  4790 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:31.239  1017  1041 W libprocessgroup: failed to open /acct/uid_10101/pid_3805/cgroup.procs: No such file or directory
,03-17 06:44:31.249  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_3759/cgroup.procs: No such file or directory
,03-17 06:44:31.249  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4002/cgroup.procs: No such file or directory
,03-17 06:44:31.279  4790  4790 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 06:44:31.359   312   312 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 06:44:31.369  1017  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:31.369  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:31.369  1017  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:31.369  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-17 06:44:31.389  4741  4741 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 06:44:31.409  4741  4741 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3792-3794)
,03-17 06:44:31.409  4741  4741 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 06:44:31.419  4790  4790 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 06:44:31.429  4741  4741 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33ed5bdc}
,03-17 06:44:31.429  4741  4741 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 06:44:31.429  4741  4741 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 06:44:31.429  4790  4790 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 06:44:31.429  4790  4790 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-17 06:44:31.439  4790  4790 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 06:44:31.439  4790  4790 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-17 06:44:31.439  4790  4790 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 06:44:31.449  1017  2712 D SSRM:n  : SIOP:: AP = 390
,03-17 06:44:31.449  4741  4741 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 06:44:31.459  4741  4741 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:44:31.459  4741  4741 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 06:44:31.489  4741  4741 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-17 06:44:31.489  4741  4741 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,03-17 06:44:31.499  4741  4741 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,03-17 06:44:31.499  4741  4741 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 06:44:31.499  4741  4741 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 06:44:31.499  4741  4741 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 06:44:31.499  4741  4741 I Adreno-EGL: Local Branch: 
03-17 06:44:31.499  4741  4741 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 06:44:31.499  4741  4741 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 06:44:31.499  4741  4741 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 06:44:31.519  1017  1533 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-17 06:44:31.519  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:31.519  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:31.519  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:31.519  1017  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:31.539  4825  4825 E Zygote  : MountEmulatedStorage(),
03-17 06:44:31.539  4825  4825 E Zygote  : v2
03-17 06:44:31.539  4825  4825 I libpersona: KNOX_SDCARD checking this for 10009
03-17 06:44:31.539  4825  4825 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:31.539  4825  4825 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:31.539  4825  4825 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:31.539  4825  4825 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 06:44:31.549  1017  1533 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4825 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 06:44:31.569  4825  4825 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:31.569  4825  4825 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:31.589  4741  4847 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-17 06:44:31.599  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 06:44:31.599  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:31.599  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:31.599  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:31.599  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:31.599  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:31.619  4741  4741 I NSApplication: Starting up...
,03-17 06:44:31.639  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,03-17 06:44:31.639  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:31.639  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:31.639  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:31.639  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:31.649  4852  4852 E Zygote  : MountEmulatedStorage()
,03-17 06:44:31.659  1017  1030 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4852 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-17 06:44:31.659  4852  4852 E Zygote  : v2,
03-17 06:44:31.659  4852  4852 I libpersona: KNOX_SDCARD checking this for 10120
03-17 06:44:31.659  4852  4852 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:31.659  4852  4852 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:31.659  4852  4852 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:31.659  4852  4852 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:31.679  4852  4852 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:31.679  4852  4852 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:31.709  1017  3038 I ActivityManager: Killing 4225:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,03-17 06:44:31.709  1017  3038 I ActivityManager: Killing 4194:com.samsung.helphub/1000 (adj 15): empty #32
,03-17 06:44:31.709  4852  4852 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 06:44:31.739  4825  4825 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 06:44:31.749  4825  4825 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 06:44:31.749  4825  4825 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 06:44:31.759  4825  4825 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 06:44:31.759  1017  1533 I ActivityManager: Killing 4247:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-17 06:44:31.809  4161  4721 I SA      : [RC New] Execute method=[GET] start
,03-17 06:44:31.829  1017  1348 I art     : Explicit concurrent mark sweep GC freed 21780(1368KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 2.842ms total 162.904ms
,03-17 06:44:31.859  1017  2828 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:44:31.869  4161  4721 I SA      : [RC New] Security=[true]
,03-17 06:44:31.869  4161  4721 I System.out: Thread-615(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 06:44:31.869  4161  4721 I System.out: Thread-615(ApacheHTTPLog):isSBSettingEnabled false
03-17 06:44:31.869  4161  4721 I System.out: Thread-615(ApacheHTTPLog):isShipBuild true
03-17 06:44:31.869  4161  4721 I System.out: Thread-615(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 06:44:31.869  4161  4721 I System.out: Thread-615(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 06:44:31.869   274   977 D EnterpriseController: uids 10041
03-17 06:44:31.869   274   977 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 06:44:31.869   274   977 D Netd    : getNetworkForDns: using netid 502 for uid 10041
,03-17 06:44:31.929  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4225/cgroup.procs: No such file or directory
,03-17 06:44:31.929  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4247/cgroup.procs: No such file or directory
,03-17 06:44:31.929  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4194/cgroup.procs: No such file or directory
,03-17 06:44:32.059  4373  4373 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-17 06:44:32.069  4373  4373 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
03-17 06:44:32.069  4373  4373 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 06:44:32.069  1017  1348 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,03-17 06:44:32.069  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.069  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.069  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.069  1017  1348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.079  4876  4876 E Zygote  : MountEmulatedStorage()
03-17 06:44:32.079  4876  4876 E Zygote  : v2
03-17 06:44:32.079  4876  4876 I libpersona: KNOX_SDCARD checking this for 10145
03-17 06:44:32.079  4876  4876 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:32.079  4876  4876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:32.089  1017  1348 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=4876 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-17 06:44:32.089  1017  1348 I ActivityManager: Killing 4271:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,03-17 06:44:32.089  4876  4876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:32.089  4876  4876 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:32.119  4876  4876 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:32.119  4876  4876 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:32.129  4876  4876 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 06:44:32.139  4876  4876 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
03-17 06:44:32.139  4876  4876 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.,
03-17 06:44:32.139  4876  4876 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
03-17 06:44:32.139  4876  4876 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:44:32.189  1017  1533 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:32.199  1017  1488 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:32.239  1017  1501 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:32.249  1017  1534 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:32.299  4512  4521 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 06:44:32.299  1017  1041 W libprocessgroup: failed to open /acct/uid_10107/pid_4271/cgroup.procs: No such file or directory
,03-17 06:44:32.309  1017  1348 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:32.309  4512  4521 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,03-17 06:44:32.309  4512  4521 D BadgeProvider: sendNotify, [notify] : null
03-17 06:44:32.309  1489  1489 D Launcher.Model: reloadBadges entered.
,03-17 06:44:32.309  4512  4521 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,03-17 06:44:32.319  4512  4521 D BadgeProvider: update, [BadgeCount] : badgecount=0
,03-17 06:44:32.319  4512  4521 D BadgeProvider: update, [UpdateCount] : 1
03-17 06:44:32.319  1017  1532 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:32.319  1017  1504 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:32.329  1017  1263 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:32.329  1017  1263 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 06:44:32.329  1017  1263 I ActivityManager: Killing 4053:com.android.vending/u0a28 (adj 15): empty #31
,03-17 06:44:32.339  1017  1017 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
,03-17 06:44:32.339  1017  1017 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-17 06:44:32.349  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,03-17 06:44:32.349  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.349  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.349  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.349  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.359  4899  4899 E Zygote  : MountEmulatedStorage()
,03-17 06:44:32.359  4899  4899 E Zygote  : v2
03-17 06:44:32.359  4899  4899 I libpersona: KNOX_SDCARD checking this for 10062
03-17 06:44:32.359  4899  4899 I libpersona: KNOX_SDCARD not a persona,
,03-17 06:44:32.359   312   312 I ServiceManager: Waiting for service AtCmdFwd...
03-17 06:44:32.359  4899  4899 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:32.359  4899  4899 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:32.369  1017  1042 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4899 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:44:32.369  4899  4899 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:32.379  1818  1818 I ConfigService: onDestroy
,03-17 06:44:32.379  1017  3038 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-17 06:44:32.379  4825  4825 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 06:44:32.379  1017  3038 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 06:44:32.379  1017  3038 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:32.379  1017  3038 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:32.379  1017  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 06:44:32.389  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 06:44:32.389  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 06:44:32.389  1327  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 06:44:32.399  1327  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 06:44:32.409  1327  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 06:44:32.409  4899  4899 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:32.409  4899  4899 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:32.409  1327  1327 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,03-17 06:44:32.409  1327  1327 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 06:44:32.409  1327  1327 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-17 06:44:32.419  4825  4825 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-17 06:44:32.419  1327  1327 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 06:44:32.419  1327  1327 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 06:44:32.419  1327  1327 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 06:44:32.419  1327  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 06:44:32.419  1017  1533 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,03-17 06:44:32.419  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 06:44:32.419  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:32.419  1017  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:32.419  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 06:44:32.429  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 06:44:32.429  3602  3602 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Mar 17 06:44:32 GMT+01:00 2016
,03-17 06:44:32.429  1017  1532 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-17 06:44:32.429  1017  1532 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 06:44:32.429  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 06:44:32.429  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 06:44:32.429  1327  1327 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 06:44:32.439  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:32.439  1017  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:32.439  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 06:44:32.439  1327  1327 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 06:44:32.449  3602  3602 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 06:44:32.449  4161  4161 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,03-17 06:44:32.459  4570  4570 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 06:44:32.459  4570  4570 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 06:44:32.459  4570  4570 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 06:44:32.459  1327  1327 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 06:44:32.459  1017  1263 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,03-17 06:44:32.459  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.459  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.459  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.459  1017  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.479  1327  1327 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET,
03-17 06:44:32.479  1327  1327 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
03-17 06:44:32.479  1017  1263 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4918 uid=10157 gids={50157, 9997} abi=armeabi-v7a,
,03-17 06:44:32.489  4918  4918 E Zygote  : MountEmulatedStorage(),
03-17 06:44:32.489  4918  4918 E Zygote  : v2
,03-17 06:44:32.489  4918  4918 I libpersona: KNOX_SDCARD checking this for 10157
,03-17 06:44:32.489  4918  4918 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:32.489  4899  4899 I ExternalOEMControlProvider: onCreate
,03-17 06:44:32.489  4918  4918 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:32.489  4918  4918 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:32.489  4918  4918 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:32.499  3602  3602 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 06:44:32.509  1017  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 06:44:32.509  1017  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
03-17 06:44:32.509  3602  3602 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 06:44:32.509  1017  1533 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:32.509  1017  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:32.509  1017  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:32.519  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,03-17 06:44:32.529  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.529  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.529  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.529  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.529  3602  3602 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 06:44:32.529  4918  4918 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:32.529  4918  4918 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:32.539  4935  4935 E Zygote  : MountEmulatedStorage()
,03-17 06:44:32.539  4935  4935 E Zygote  : v2
03-17 06:44:32.539  4935  4935 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:32.539  4935  4935 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:32.539  4935  4935 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:32.539  1017  1488 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=4935 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:32.539  4935  4935 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:32.539  4935  4935 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:32.549  3602  4917 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-17 06:44:32.549  3602  4917 I KLMS-2.5.183: : KLMSIntentService(): TIME_CHANGED
,03-17 06:44:32.549  3602  4917 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().START : Thu Mar 17 06:44:32 GMT+01:00 2016
,03-17 06:44:32.569  4935  4935 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:32.569  4935  4935 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:32.569  1017  1488 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,03-17 06:44:32.569  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.569  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.569  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.569  1017  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.569  4899  4928 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-17 06:44:32.569  3602  4917 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().END
,03-17 06:44:32.579  1017  1041 W libprocessgroup: failed to open /acct/uid_10028/pid_4053/cgroup.procs: No such file or directory
,03-17 06:44:32.579  4918  4918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:32.589  4950  4950 E Zygote  : MountEmulatedStorage()
03-17 06:44:32.589  4950  4950 E Zygote  : v2
03-17 06:44:32.589  4950  4950 I libpersona: KNOX_SDCARD checking this for 10046
03-17 06:44:32.589  4950  4950 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:32.589  4950  4950 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:32.589  4950  4950 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 06:44:32.589  4950  4950 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 06:44:32.599  1017  1488 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4950 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,03-17 06:44:32.599  1183  1183 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 06:44:32.599  1183  1183 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:32.599  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:32.599  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:32.599  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:32.599  1183  1183 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:32.609   302   302 I art     : Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 646us total 22.617ms
03-17 06:44:32.619  3602  3602 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 06:44:32.629  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,03-17 06:44:32.629   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.515ms
03-17 06:44:32.629  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.629  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.629  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.629  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.639  4950  4950 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:32.639  4950  4950 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:32.639  4935  4935 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:32.649   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.272ms
,03-17 06:44:32.669  4965  4965 E Zygote  : MountEmulatedStorage(),
03-17 06:44:32.669  4965  4965 E Zygote  : v2
03-17 06:44:32.669  4965  4965 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 06:44:32.669  4965  4965 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:32.669  4965  4965 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 06:44:32.669  1017  1029 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4965 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:32.669  4965  4965 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 06:44:32.669  4965  4965 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:32.679  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 06:44:32.679  1017  1030 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 06:44:32.689  1017  1523 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 06:44:32.689  1017  1523 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 06:44:32.689  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:32.689  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:32.689  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:32.689  1017  1151 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 06:44:32.699  1017  1348 I ActivityManager: Killing 4326:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 06:44:32.699  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 06:44:32.719  4965  4965 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:32.719  4965  4965 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:32.719  4950  4950 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-17 06:44:32.719  4950  4950 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 06:44:32.719  4950  4950 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 06:44:32.719  4950  4950 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:32.719  4950  4950 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:44:32.719  4950  4950 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 06:44:32.729  1741  1741 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-17 06:44:32.729  1741  1741 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 06:44:32.729  1017  3038 I ActivityManager: Killing 4399:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-17 06:44:32.729  1017  3038 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,03-17 06:44:32.739  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.739  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.739  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:32.739  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:32.749  4981  4981 E Zygote  : MountEmulatedStorage(),
03-17 06:44:32.749  4981  4981 E Zygote  : v2
03-17 06:44:32.749  4981  4981 I libpersona: KNOX_SDCARD checking this for 10085
03-17 06:44:32.749  4981  4981 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:32.749  4981  4981 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:32.749  4981  4981 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 06:44:32.749  1017  3038 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4981 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:44:32.759  4981  4981 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:32.769  4950  4950 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,03-17 06:44:32.779  4965  4965 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458193472782
03-17 06:44:32.779  4965  4965 D         : TimeServiceNative: User Time to be set is 1458193472782
03-17 06:44:32.779  4965  4965 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-17 06:44:32.779  4965  4965 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-17 06:44:32.779  4965  4965 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458193472782
,03-17 06:44:32.779  4965  4965 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-17 06:44:32.779   315   554 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-17 06:44:32.779   315  4996 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458193472782
03-17 06:44:32.779   315  4996 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458193472782, operation = 0
03-17 06:44:32.779   315  4996 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/16/70 3:49:46
03-17 06:44:32.779   315  4996 D QC-time-services: Daemon:Value read from RTC seconds = 22304986000
03-17 06:44:32.779   315  4996 D QC-time-services: Daemon:new time 1458193472782 
03-17 06:44:32.779   315  4996 D QC-time-services: Daemon: delta 1435888486782 genoff 1435888486782 
03-17 06:44:32.779   315  4996 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1435888486782 to memory
03-17 06:44:32.779   315  4996 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-17 06:44:32.779   315  4996 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 06:44:32.779  4981  4981 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:32.779  4981  4981 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:32.799  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4326/cgroup.procs: No such file or directory
,03-17 06:44:32.799  1017  1041 W libprocessgroup: failed to open /acct/uid_10131/pid_4399/cgroup.procs: No such file or directory
,03-17 06:44:32.799  4981  4981 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-17 06:44:32.799  4981  4981 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 06:44:32.809  4981  4981 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 06:44:32.809  4981  4981 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 06:44:32.809  4981  4981 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:32.809  4981  4981 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-17 06:44:32.809   315  4996 D QC-time-services: Updating the TOD offset
03-17 06:44:32.809   315  4996 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1435888486782 to memory
03-17 06:44:32.809   315  4996 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-17 06:44:32.809   315  4996 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 06:44:32.819   315  4996 E QC-time-services: Daemon:Update to modem bit set
03-17 06:44:32.819  4965  4965 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-17 06:44:32.819   315  4996 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-17 06:44:32.819   315  4996 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1119923686782
,03-17 06:44:32.819   315   552 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-17 06:44:32.819   315   554 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
03-17 06:44:32.819  1017  1151 I ActivityManager: Killing 4464:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-17 06:44:32.839  1017  1348 I ActivityManager: Killing 4550:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 06:44:32.869  1017  1348 D SettingsProvider: name = next_alarm_formatted
,03-17 06:44:32.869  1017  1348 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:32.869  1017  1348 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 06:44:32.879  1017  1348 D SettingsProvider: selectionArgs: false
03-17 06:44:32.879  1017  1348 D SettingsProvider: selectionArgs: 10085
03-17 06:44:32.879  1017  1348 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:32.879  1017  1348 D SettingsProvider: ret = -1
,03-17 06:44:32.889  1017  1042 I ActivityManager: Waited long enough for: ServiceRecord{2873495d u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-17 06:44:32.929  1017  1041 W libprocessgroup: failed to open /acct/uid_10139/pid_4464/cgroup.procs: No such file or directory
,03-17 06:44:32.929  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4550/cgroup.procs: No such file or directory
,03-17 06:44:32.939  4950  4950 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 115.950ms
,03-17 06:44:32.959  4161  4721 I SA      : [RC New] [v2liruge] api execute + 1098
,03-17 06:44:32.969  4161  4721 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,03-17 06:44:32.969  4161  4721 I System.out: AsyncTask #1 calls detatch()
,03-17 06:44:32.969  4161  4721 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,03-17 06:44:32.979  4161  4721 I SA      : [OCP] update openData : PL
,03-17 06:44:32.979  4161  4721 I SA      : [TPMU] getNetworkMcc : 
,03-17 06:44:32.979  4161  4721 I SA      : [SCU] saveMccToPreferece Start
,03-17 06:44:32.979  4161  4721 I SA      : [SCU] RegionMCC : 260
,03-17 06:44:32.979  4161  4721 I SA      : [SSP] query invoked
,03-17 06:44:32.979  4161  4721 I SA      : [TPMU] GetMccFromDB : null
,03-17 06:44:32.979  4161  4721 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-17 06:44:32.989  4981  4981 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 105.496ms
,03-17 06:44:32.999  4161  4721 I SA      : [SCU] saveMccToPreferece End
,03-17 06:44:32.999  4161  4721 I SA      : [RC New] executeRequest [v2liruge] end. 1182
,03-17 06:44:32.999  4161  4721 I SA      : [RC New] Execute end
,03-17 06:44:32.999  4161  4161 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-17 06:44:32.999  4161  4161 I SA      : [OR] GetMyCountryZoneTask Success
,03-17 06:44:32.999  1017  1523 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,03-17 06:44:32.999  1017  1523 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,03-17 06:44:32.999  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:32.999  1017  1523 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 06:44:32.999  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-17 06:44:33.019  4950  4999 D Mms/ArtClassLoader: init before art
,03-17 06:44:33.029  4950  4950 D Mms/TelephonyPermission: start operation mode monitor
,03-17 06:44:33.039  4950  4950 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 06:44:33.039  4950  4950 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-17 06:44:33.039  4950  4950 D Mms/TelephonyPermission: isDefault true
,03-17 06:44:33.039  4950  4950 D Mms/MmsApp: onCreate() com.android.mms
,03-17 06:44:33.079  4950  4950 D Mms/MmsApp: [start]    initCountryIso consume time = 314.266823
,03-17 06:44:33.079  1017  1534 D CountryDetector: The first listener is added
,03-17 06:44:33.089  4950  4950 D Mms/MmsApp: [end]    initCountryIso consume time = 10.645104
03-17 06:44:33.089  4950  4950 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.122187
,03-17 06:44:33.089  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-17 06:44:33.089  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:33.099  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:33.099  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:33.099  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:33.099  4950  4950 D Mms/MmsConfig: before partial update
,03-17 06:44:33.109  5002  5002 E Zygote  : MountEmulatedStorage()
,03-17 06:44:33.109  5002  5002 I libpersona: KNOX_SDCARD checking this for 10094
,03-17 06:44:33.109  5002  5002 E Zygote  : v2
03-17 06:44:33.109  5002  5002 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:33.109  5002  5002 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 06:44:33.109  1017  1030 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5002 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
03-17 06:44:33.109  1017  1030 I ActivityManager: Killing 4626:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,03-17 06:44:33.109  5002  5002 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:33.109  5002  5002 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:33.129  4950  4950 D Mms/MmsConfig: Load Resize quality : 80
,03-17 06:44:33.129  4950  4950 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-17 06:44:33.129  4950  4950 D EasySignUpManager_1.0.1: isAuth is false
,03-17 06:44:33.139  4950  4950 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-17 06:44:33.139  1464  3131 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4950
,03-17 06:44:33.139  1464  3131 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.922 ms
,03-17 06:44:33.139  5002  5002 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:33.149  5002  5002 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:33.159  4950  4950 D EasySignUpManager_1.0.1: isAuth is false
,03-17 06:44:33.159  4950  4950 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-17 06:44:33.169  4950  4950 E CscParser: mps_code.dat does not exist
,03-17 06:44:33.169  4950  4950 E CscParser: customer_path =/system/csc/customer.xml
,03-17 06:44:33.169  4950  4950 E CscParser: fileName + /system/csc/customer.xml
,03-17 06:44:33.169  5002  5002 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,03-17 06:44:33.179  5002  5002 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 06:44:33.179  4950  4950 E CscParser: mps_code.dat does not exist
03-17 06:44:33.179  4950  4950 E CscParser: customer_path =/system/csc/customer.xml
03-17 06:44:33.179  4950  4950 E CscParser: fileName + /system/csc/customer.xml
,03-17 06:44:33.179  5002  5002 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-17 06:44:33.179  1017  1030 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,03-17 06:44:33.179  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 06:44:33.179  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:33.179  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:33.179  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 06:44:33.189  1017  1041 W libprocessgroup: failed to open /acct/uid_10068/pid_4626/cgroup.procs: No such file or directory
,03-17 06:44:33.189  5002  5002 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-17 06:44:33.189  4950  4950 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-17 06:44:33.189  1017  3038 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,03-17 06:44:33.189  4950  4950 D Mms/MmsConfig:  enable multiwindow = true
,03-17 06:44:33.199  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:33.199  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:33.199  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:33.199  1017  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:33.199  5002  5002 D elm:15183: ElmAgentService : onCreate()
,03-17 06:44:33.199  5002  5018 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,03-17 06:44:33.199  5002  5018 D elm:15183: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,03-17 06:44:33.209  5002  5002 D elm:15183: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,03-17 06:44:33.209  5002  5002 D elm:15183: ModuleBase.ModifySetAlarm()
,03-17 06:44:33.209  5020  5020 E Zygote  : MountEmulatedStorage()
03-17 06:44:33.209  5020  5020 E Zygote  : v2
03-17 06:44:33.209  5020  5020 I libpersona: KNOX_SDCARD checking this for 10134
03-17 06:44:33.209  5020  5020 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:33.209  5020  5020 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:33.209  5020  5020 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:33.219  5020  5020 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-17 06:44:33.219  4950  4950 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-17 06:44:33.219  1017  3038 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5020 uid=10134 gids={50134, 9997} abi=armeabi-v7a
03-17 06:44:33.219  4950  4950 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-17 06:44:33.229  5002  5002 D elm:15183: MDMBridge.getInstance()
03-17 06:44:33.229  1017  1534 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 55613
03-17 06:44:33.229  5002  5002 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 06:44:33.229  5002  5002 D elm:15183: ElmAgentService : onDestroy().
03-17 06:44:33.229  1017  1534 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
03-17 06:44:33.229  1017  1534 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10054}) (elapsedTime=3509)
,03-17 06:44:33.239  1017  1523 I ActivityManager: Killing 3879:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,03-17 06:44:33.239  4950  4950 D Mms/MmsConfig: [end]    init() consume time = 148.579844
,03-17 06:44:33.239  5020  5020 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:33.239  5020  5020 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:33.239  4950  4950 D Mms/Contact: [start]    init() consume time = 2.144531
,03-17 06:44:33.259  5020  5020 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:33.259  5020  5020 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-17 06:44:33.269  4950  4950 D Mms/Contact: [end]    init consume time = 23.358177
,03-17 06:44:33.269  1464  1473 D TP/MmsSmsProvider: query,matched:13, calling pid = 4950
,03-17 06:44:33.289  4950  5037 D Mms/DraftCache: [start]    rebuildCache consume time = 19.600365
,03-17 06:44:33.289  1464  1473 D TP/MmsSmsProvider: match 13:Elapsed time : 11.409 ms
,03-17 06:44:33.289  4950  4950 D Mms/MethodReflector: getSubId is called
03-17 06:44:33.289  4950  4950 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 06:44:33.289  1464  1701 D TP/MmsSmsProvider: query,matched:12, calling pid = 4950
,03-17 06:44:33.299  1464  1701 D TP/MmsSmsProvider: match 12:Elapsed time : 2.295 ms
,03-17 06:44:33.299  4950  4950 D Mms/MethodReflector: getTelephonyProperty is called
,03-17 06:44:33.299  4950  4950 D Mms/DownloadManager: roaming -> false (slotId = 0)
,03-17 06:44:33.299  4950  4950 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
,03-17 06:44:33.299  4950  4950 D Mms/DownloadManager: auto download without roaming -> true
,03-17 06:44:33.299  4950  4950 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,03-17 06:44:33.309  4950  5037 D Mms/DraftCache: [end]    rebuildCache consume time = 21.663125
,03-17 06:44:33.309  4950  4950 D Mms/MethodReflector: getSubId is called
,03-17 06:44:33.309  4950  4950 D Mms/MethodReflector: getDefaultSmsSubId is called
03-17 06:44:33.309  4950  4950 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-17 06:44:33.309  4950  4950 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
03-17 06:44:33.309  4950  4950 D Mms/MethodReflector: getTelephonyProperty is called
03-17 06:44:33.309  4950  4950 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-17 06:44:33.309  4950  4950 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-17 06:44:33.309  4950  4950 D Mms/DownloadManager: auto download without roaming -> true
03-17 06:44:33.309  4950  4950 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-17 06:44:33.309  4950  4950 D Mms/DownloadManager: auto download during roaming secondary -> false
03-17 06:44:33.309  4950  4950 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 06:44:33.319  1017  1263 I ActivityManager: Killing 4646:com.sec.pcw.device/1000 (adj 15): empty #31
,03-17 06:44:33.329  1017  1533 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 06:44:33.329  1017  1533 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4290, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-17 06:44:33.329  1017  1533 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
03-17 06:44:33.329  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 06:44:33.329  1017  1017 I MotionRecognitionService: Plugged
,03-17 06:44:33.329  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 06:44:33.339  1183  1183 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 06:44:33.339  1183  1183 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 06:44:33.349  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 06:44:33.349  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 06:44:33.349   287   287 E SMD     : DCD OFF
,03-17 06:44:33.359   312   312 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 06:44:33.369  4950  4950 D ComposerPerformance: 1458193473372 ms / [DONE] Composer constructor
,03-17 06:44:33.369  2627  2627 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 06:44:33.369  4950  4950 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-17 06:44:33.369  2627  2708 D HeadsetStateMachine: Disconnected process message: 10
,03-17 06:44:33.369  4950  4950 I Mms/ReservationManager: ReservationManager()
,03-17 06:44:33.369  4950  4950 I Mms/ReservationManager: resetAfterConnected()
,03-17 06:44:33.379  1464  3131 D TP/MmsSmsProvider: query,matched:7, calling pid = 4950
,03-17 06:44:33.379  4950  5039 D Mms/Conversation: [start]    init() consume time = 69.79474
,03-17 06:44:33.379  1464  3131 D TP/MmsSmsProvider: match 7:Elapsed time : 4.276 ms
,03-17 06:44:33.379  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-17 06:44:33.379  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 06:44:33.379  1183  1183 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-17 06:44:33.379  4950  4950 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 06:44:33.389  1464  1473 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-17 06:44:33.389  1464  1473 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 06:44:33.389  1464  1473 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
03-17 06:44:33.389  4950  4950 D Mms/MmsApp: [end]    onCreate() consume time = 10.886666
,03-17 06:44:33.389  4950  4950 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
03-17 06:44:33.389  1464  1473 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-17 06:44:33.389  4950  4950 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
03-17 06:44:33.389  1017  1488 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
03-17 06:44:33.389  1464  1473 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:33.389  1464  1473 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:33.389  1464  1473 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:33.389  1464  1473 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:33.389  1464  1473 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:33.389  1464  1473 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 06:44:33.399  4950  4950 D Mms/MethodReflector: getSubId is called
03-17 06:44:33.399  4950  4950 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 06:44:33.399  4950  4950 D Mms/MethodReflector: getTelephonyProperty is called
03-17 06:44:33.399  4950  4950 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 06:44:33.399  4950  4950 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 06:44:33.399  4950  4950 D Mms/DownloadManager: auto download without roaming -> true
03-17 06:44:33.399  4950  4950 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-17 06:44:33.399  4950  4950 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 06:44:33.399  1017  1488 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:33.399  1017  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:33.399  1017  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 06:44:33.399  1017  1488 I ActivityManager: Killing 3900:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,03-17 06:44:33.409  1464  1473 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-17 06:44:33.409  1464  1473 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 06:44:33.409  1017  1041 W libprocessgroup: failed to open /acct/uid_10069/pid_3879/cgroup.procs: No such file or directory
,03-17 06:44:33.419  4950  5039 D Mms/Conversation: [end]    init consume time = 26.953542
,03-17 06:44:33.419  4950  5039 D Mms/MessagingNotification: [start]    init() consume time = 0.125052
,03-17 06:44:33.419  4950  5039 D Mms/MessagingNotification: [end]    init consume time = 3.554896
,03-17 06:44:33.419  4950  5040 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 4.836927
,03-17 06:44:33.429  1464  3131 D TP/MmsSmsProvider: query,matched:0, calling pid = 4950
,03-17 06:44:33.429  1464  3131 V TP/MmsSmsProvider: getSimpleConversations entered.
,03-17 06:44:33.429  1017  1534 D ActivityManager: startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
03-17 06:44:33.429  1017  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,03-17 06:44:33.429  1017  1534 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:33.429  1017  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:33.429  1017  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 06:44:33.429  1464  3131 D TP/MmsSmsProvider: match 0:Elapsed time : 4.035 ms
,03-17 06:44:33.429  1464  1476 D TP/MmsSmsProvider: query,matched:400, calling pid = 4950
,03-17 06:44:33.439  1017  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:33.439  1017  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:33.439  1017  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 06:44:33.439  4950  5041 D Mms/Synchronizer: [start]    doSync consume time = 12.338542
,03-17 06:44:33.449  1464  1701 D TP/MmsSmsProvider: update, matched:300, calling pid = 4950
,03-17 06:44:33.449  1464  1701 V TP/MmsSmsProvider: syncDBData start
,03-17 06:44:33.449  1464  1701 V TP/MmsSmsProvider: syncDBData sms end
,03-17 06:44:33.449  1464  1701 V TP/MmsSmsProvider: syncDBData mms end
,03-17 06:44:33.449  1464  1701 V TP/MmsSmsProvider: syncDBData end
,03-17 06:44:33.449  4950  5040 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 0.003542
,03-17 06:44:33.449  4950  5041 D Mms/Synchronizer: [end]    doSync consume time = 13.878958
,03-17 06:44:33.449  4950  4999 D Mms/ArtClassLoader: init [DONE] art
,03-17 06:44:33.469  1017  1151 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-17 06:44:33.469  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:33.469  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:33.469  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:33.469  1017  1151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:33.489  5043  5043 E Zygote  : MountEmulatedStorage()
03-17 06:44:33.489  5043  5043 E Zygote  : v2
03-17 06:44:33.489  5043  5043 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:33.489  5043  5043 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:33.489  5043  5043 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:33.489  5043  5043 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:33.489  5043  5043 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:33.489  1017  1151 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5043 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:33.499  4950  5039 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-17 06:44:33.509  1464  1476 D TP/SmsProvider: query,matched:26, calling pid = 4950
,03-17 06:44:33.509  1464  1476 D TP/SmsProvider: match 26:Elapsed time : 1.111 ms
,03-17 06:44:33.519  5043  5043 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:33.519  5043  5043 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:33.529  1660  1684 I art     : Explicit concurrent mark sweep GC freed 4059(164KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.881ms total 23.355ms
,03-17 06:44:33.529  1464  1758 D TP/MmsSmsProvider: query,matched:6, calling pid = 4950
,03-17 06:44:33.529  1464  1758 D TP/MmsSmsProvider: match 6:Elapsed time : 2.053 ms
,03-17 06:44:33.549  1017  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_4646/cgroup.procs: No such file or directory
03-17 06:44:33.549  1017  1041 W libprocessgroup: failed to open /acct/uid_10032/pid_3900/cgroup.procs: No such file or directory
,03-17 06:44:33.559  5043  5043 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-17 06:44:33.569  1017  1348 D SecContentProvider2: uri = 14 selection = getSealedState
,03-17 06:44:33.569  1017  1348 D SecContentProvider2: mCursor = null
,03-17 06:44:33.569  1017  1151 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 06:44:33.569  1017  1151 D SecContentProvider2: mCursor = null
,03-17 06:44:33.569  5043  5043 V MTPRx   : sealedState: false
03-17 06:44:33.569  5043  5043 V MTPRx   : sealedUsbMassStorageState: false
03-17 06:44:33.569  5043  5043 E MTPRx   : check value of boot_completed is1
03-17 06:44:33.569  5043  5043 E MTPRx   : check booting is completed_sys.boot_completed
,03-17 06:44:33.569  1017  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,03-17 06:44:33.569  5043  5043 E MTPRx   : Sd-Card path/storage/extSdCard
,03-17 06:44:33.579  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:33.579  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:33.579  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:33.579  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:33.589  5043  5043 E MTPRx   : Status for mount/Unmount :removed,
03-17 06:44:33.589  5043  5043 E MTPRx   : SDcard is not available
,03-17 06:44:33.589  5059  5059 E Zygote  : MountEmulatedStorage()
03-17 06:44:33.589  5059  5059 E Zygote  : v2
03-17 06:44:33.589  5059  5059 I libpersona: KNOX_SDCARD checking this for 10025
,03-17 06:44:33.589  5059  5059 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:33.589  5059  5059 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:33.589  5059  5059 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 06:44:33.589  5059  5059 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:33.589  1017  1029 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5059 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,03-17 06:44:33.599  5043  5043 W MTPRx   : value of connected istrue
03-17 06:44:33.599  5043  5043 W MTPRx   : value of configured istrue
03-17 06:44:33.599  5043  5043 W MTPRx   : value of mtpEnabled istrue
03-17 06:44:33.599  5043  5043 W MTPRx   : value of ptpEnabled isfalse
,03-17 06:44:33.609  5043  5043 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-17 06:44:33.609  5043  5043 E MTPRx   : mFirstTime: false
,03-17 06:44:33.619  5059  5059 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:33.619  5059  5059 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:33.619  1017  1534 I ActivityManager: Killing 4103:com.sec.android.soagent/u0a34 (adj 15): empty #31
,03-17 06:44:33.629  5043  5043 D         : MTP: reading debug level property
,03-17 06:44:33.629  5043  5043 E MTPJNIInterface: Getting CryptionKey from JAVA
,03-17 06:44:33.629  5043  5043 E MTPRx   : currentUserId is 0
,03-17 06:44:33.639  5043  5043 E MTPRx   : Start observing USB_STATE_MATCH 
,03-17 06:44:33.639  5043  5043 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
03-17 06:44:33.639  5043  5043 E MTPRx   : is_Privatemode is NOT 1
,03-17 06:44:33.639  5059  5059 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 06:44:33.639  1017  3038 D SettingsProvider: name = boot_time_connected
,03-17 06:44:33.659  5043  5043 E MTPRx   : Sending NORMAL_BOOT to stack,
03-17 06:44:33.659  5043  5043 E MTPJNIInterface: noti = 17
,03-17 06:44:33.669  1017  1488 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 06:44:33.669  1017  1501 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-17 06:44:33.679  5043  5043 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-17 06:44:33.679  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
03-17 06:44:33.679  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-17 06:44:33.679  1017  1017 I ValidateNoPeople: mEvictionCount: 0
,03-17 06:44:33.689  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:33.689  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:33.689  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 06:44:33.689  4950  4950 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-17 06:44:33.689  4950  4950 D Mms/Contact: performUpdate:widgetCount=0
,03-17 06:44:33.689  1017  1501 D SettingsProvider: name = mtp_running_status
,03-17 06:44:33.699  4950  5078 D Mms/ContactsCache: [start]    invalidate() consume time = 246.604687
03-17 06:44:33.699  4950  5078 D Mms/ContactsCache: [end]    invalidate() consume time = 0.159167
,03-17 06:44:33.709  1017  1533 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 06:44:33.709  5043  5043 E MTPRx   : else part ... so first time!!!
,03-17 06:44:33.719  5043  5043 E MTPPlaObsrvr: inside setContext()
,03-17 06:44:33.719  5043  5043 E MTPPlaObsrvr:  inside createplafiles
03-17 06:44:33.719  1183  1183 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:33.739  1017  1041 W libprocessgroup: failed to open /acct/uid_10034/pid_4103/cgroup.procs: No such file or directory
,03-17 06:44:33.769   257   435 I SurfaceFlinger: id=13 Removed Uoast (8/8)
,03-17 06:44:33.779   257   440 I SurfaceFlinger: id=13 Removed Uoast (-2/8)
,03-17 06:44:33.839  1017  1488 I art     : Explicit concurrent mark sweep GC freed 14784(811KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/40MB, paused 2.501ms total 142.714ms,
,03-17 06:44:33.849  5059  5059 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-17 06:44:33.859  5043  5043 E MTPPlaObsrvr: playlist count is0
03-17 06:44:33.859  5043  5043 E MTPPlaObsrvr:  inside try branch createplafiles
,03-17 06:44:33.859  5043  5043 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-17 06:44:33.869  5043  5043 E MTPPlaObsrvr: Inside registerContentObserver
,03-17 06:44:33.869  5043  5043 E MtpAdbObserver: inside setContext()
03-17 06:44:33.869  5043  5043 E MtpAdbObserver: Inside registerContentObserver
03-17 06:44:33.869  5043  5043 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-17 06:44:33.869  1017  1501 D ActivityManager: startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
03-17 06:44:33.869  1017  1501 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-17 06:44:33.869  1017  1501 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:33.869  1017  1501 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:33.869  1017  1501 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 06:44:33.869  1017  1488 D SettingsProvider: name = mtp_running_status
,03-17 06:44:33.869  1017  1504 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 06:44:33.879  5043  5043 E MtpService: onCreate.
,03-17 06:44:33.879  1017  1534 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-17 06:44:33.879  1017  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-17 06:44:33.879  1017  1534 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:33.879  1017  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:33.879  1017  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 06:44:33.879  4950  5039 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-17 06:44:33.889  5043  5079 V MtpMediaDBManager: inside deleteAllDB
,03-17 06:44:33.889  1237  1237 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-17 06:44:33.889  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:33.889  1017  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:33.889  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,03-17 06:44:33.899  1017  1532 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:33.899  1017  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,03-17 06:44:33.899  1017  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-17 06:44:33.909  5043  5043 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-17 06:44:33.909  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-17 06:44:33.909  5043  5043 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-17 06:44:33.909  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,03-17 06:44:33.909  5043  5043 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-17 06:44:33.909  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-17 06:44:33.909  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-17 06:44:33.909  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:33.909  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 06:44:33.909  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-17 06:44:33.909  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-17 06:44:33.909  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-17 06:44:33.919  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,03-17 06:44:33.919  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,03-17 06:44:33.919  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-17 06:44:33.919  1818  1818 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-17 06:44:33.919  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-17 06:44:33.919  5043  5079 V MtpMediaDBManager: inside Thread updateDB
,03-17 06:44:33.919  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-17 06:44:33.919  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-17 06:44:33.919  5043  5043 E MtpService: onStartCommand.
,03-17 06:44:33.919  5059  5059 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-17 06:44:33.929  5043  5043 W MTPRx   : calling native method
03-17 06:44:33.929  5043  5043 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-17 06:44:33.929  5043  5080 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-17 06:44:33.929  5043  5043 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-17 06:44:33.929  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:33.929  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 06:44:33.929  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-17 06:44:33.929  5043  5043 E MTPJNIInterface: noti = 10
03-17 06:44:33.929  5043  5043 E MtpService: onStartCommand.
,03-17 06:44:33.929  5043  5043 W MTPRx   : calling native method
03-17 06:44:33.929  5043  5080 E MtpService: handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-17 06:44:33.939  1017  1523 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 06:44:33.939  5043  5043 E MTPRx   : Checking the driver time out
03-17 06:44:33.939  5043  5043 E MTPJNIInterface: noti = 2
03-17 06:44:33.939  5043  5043 D         : deleting sockets before message queue initialization
,03-17 06:44:33.939  5043  5043 D         : event handler thread is created, so set the flag
,03-17 06:44:33.939  5043  5043 E MTPRx   : called native method
03-17 06:44:33.939  5043  5043 E MTPJNIInterface: setting Media scanner status0
03-17 06:44:33.939  5043  5043 E MTPJNIInterface: After setting Media scanner status0
,03-17 06:44:33.939  1017  1523 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:33.939  1017  1523 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:33.939  1017  1523 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:33.939  5043  5081 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,03-17 06:44:33.939  5043  5043 W MTPRx   : notification from stack 1
,03-17 06:44:33.939  5043  5079 E MtpMediaDBManager: count : 27
,03-17 06:44:33.949  5043  5081 E MTPJNIInterface: Getting media scanner status0
,03-17 06:44:33.949  5043  5081 E MTPJNIInterface: DeviceName is A5-1
,03-17 06:44:33.969  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,03-17 06:44:33.979  1183  1183 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
03-17 06:44:33.979  1183  1183 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,03-17 06:44:33.979  5043  5079 W MtpMediaDBManager: sending db update complete noti to stack
03-17 06:44:33.979  5043  5079 E MTPJNIInterface: noti = 29
,03-17 06:44:33.979  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-17 06:44:33.979  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:33.979  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:33.979  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:33.979  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:33.999  1017  1029 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5083 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-17 06:44:33.999  5083  5083 E Zygote  : MountEmulatedStorage()
03-17 06:44:33.999  5083  5083 I libpersona: KNOX_SDCARD checking this for 10003
03-17 06:44:33.999  5083  5083 E Zygote  : v2
03-17 06:44:33.999  5083  5083 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:33.999  5083  5083 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 06:44:34.009  5083  5083 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 06:44:34.009  5043  5081 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 06:44:34.009  5043  5081 E MTPJNIInterface: SDcard is not available,
,03-17 06:44:34.009  5083  5083 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:34.029  5043  5081 E         : lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
03-17 06:44:34.029  5083  5083 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:34.029  5083  5083 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:34.029  5043  5081 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-17 06:44:34.039  5043  5081 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 06:44:34.039  5043  5081 E MTPJNIInterface: SDcard is not available
03-17 06:44:34.039  5043  5081 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 06:44:34.039  5043  5081 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-17 06:44:34.039  5043  5081 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 06:44:34.039  5043  5081 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 06:44:34.039  5043  5081 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 06:44:34.039  5043  5081 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 06:44:34.039  5043  5081 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 06:44:34.039  5043  5081 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-17 06:44:34.039  5043  5043 W MTPRx   : notification from stack 2
,03-17 06:44:34.039  5043  5098 D         : [mtp_init_device] Library open with 32 bits.
03-17 06:44:34.039  5043  5098 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
03-17 06:44:34.039  5043  5098 E         : [mtp_init_device 702]  After open the MTP fd = 33 and line = 702...
03-17 06:44:34.039  5043  5098 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-17 06:44:34.039  5043  5098 E         :  [sua_support_present:1287] returning false 
03-17 06:44:34.039  5043  5098 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
