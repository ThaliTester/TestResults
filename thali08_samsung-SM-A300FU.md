#### Test 62754403d2f0346_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-17 13:26:05.538  2135  2789 W DriveInitializer: Awaiting to be initialized
03-17 13:26:05.538  2878  2878 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:05.538  2878  2878 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:05.538  2135  2895 W DriveInitializer: Background init thread started
03-17 13:26:05.568  1018  2877 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
03-17 13:26:05.578  1018  2877 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
03-17 13:26:05.578  1018  2874 D qmi_secgps_clnt: qmi_secgps_client_init()
03-17 13:26:05.588  1018  2874 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
03-17 13:26:05.588  1018  2874 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
03-17 13:26:05.588  1018  2874 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
03-17 13:26:05.608  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:05.608  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:05.608  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
--------- beginning of system
03-17 13:26:05.608  2878  2878 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
03-17 13:26:05.618  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{1065c78b u0 com.samsung.hs20settings/.WifiHs20UtilityService}
03-17 13:26:05.618   258   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
03-17 13:26:05.618   258   529 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 13:26:05.618  2135  2895 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
03-17 13:26:05.618  1018  1573 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=126, mSplitNum[2]=164, mBgSplitQueueNum=3 divideNum= 37 r.nextReceiver= 50 receivers.size=201
03-17 13:26:05.618  1018  1573 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
03-17 13:26:05.628  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.628  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.628  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.628  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:05.638  2903  2903 E Zygote  : MountEmulatedStorage()
03-17 13:26:05.638  2903  2903 E Zygote  : v2
03-17 13:26:05.638  2903  2903 I libpersona: KNOX_SDCARD checking this for 10097
03-17 13:26:05.638  2903  2903 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:05.638  2903  2903 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:05.638  2903  2903 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:05.638  1018  1573 I ActivityManager: Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2903 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:05.638  2903  2903 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 13:26:05.648  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.648  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.648  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.648  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.658  2916  2916 E Zygote  : MountEmulatedStorage()
03-17 13:26:05.658  2916  2916 E Zygote  : v2
03-17 13:26:05.658  2916  2916 I libpersona: KNOX_SDCARD checking this for 10081
03-17 13:26:05.658  2916  2916 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:05.658  2916  2916 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:05.658  2916  2916 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:05.668  2916  2916 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:05.668  1018  1044 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2916 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:05.668  2903  2903 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:05.668  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.668  2903  2903 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:05.668  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.668  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.668  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.688   305   305 I art     : Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 994us total 21.034ms
03-17 13:26:05.688  2916  2916 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:05.688  2916  2916 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:05.708   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.588ms
03-17 13:26:05.728   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 648us total 16.969ms
03-17 13:26:05.738  2935  2935 E Zygote  : MountEmulatedStorage()
03-17 13:26:05.738  2935  2935 E Zygote  : v2
03-17 13:26:05.738  1018  1044 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2935 uid=1101 gids={41101, 9997} abi=armeabi-v7a
03-17 13:26:05.738  2935  2935 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:05.738  2935  2935 I libpersona: KNOX_SDCARD checking this for 1101
03-17 13:26:05.738  2935  2935 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:05.738  2935  2935 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:05.738  2935  2935 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:05.748  1018  2874 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
03-17 13:26:05.748  1018  2877 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 13:26:05.758  1018  2877 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 13:26:05.758  1018  2877 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
03-17 13:26:05.758  1018  2874 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
03-17 13:26:05.758  1018  2874 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 13:26:05.768  1018  2877 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 13:26:05.768  1018  2874 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
03-17 13:26:05.768  1018  2877 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 13:26:05.778  2935  2935 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:05.778  2935  2935 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:05.778  1018  2874 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
03-17 13:26:05.778  2916  2916 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:05.778  2916  2916 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:05.778  2916  2916 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:05.778  2916  2916 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:05.778  2916  2916 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-17 13:26:05.788  1018  2877 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 13:26:05.788  1018  2874 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
03-17 13:26:05.788  1018  2874 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 13:26:05.788  1018  2874 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-17 13:26:05.788  1018  2874 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 13:26:05.788  1018  2874 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
03-17 13:26:05.798  1018  2874 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 13:26:05.798  1018  2874 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
03-17 13:26:05.798  2935  2935 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
03-17 13:26:05.818  2935  2935 V SmartcardService: main Received broadcast
03-17 13:26:05.818  2935  2935 V SmartcardService: Starting smartcard service after boot completed
03-17 13:26:05.818  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:05.818  1018  2826 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:05.818  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
03-17 13:26:05.828  1018  1241 I ActivityManager: Killing 2011:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
03-17 13:26:05.828  1018  1569 I ActivityManager: Killing 1786:com.android.vending/u0a26 (adj 15): empty #31
03-17 13:26:05.838  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:05.838  1018  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:05.838  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-17 13:26:05.848  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.848  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.848  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.848  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.848  1215  1215 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-17 13:26:05.848  1018  2877 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 13:26:05.848  1018  2874 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
03-17 13:26:05.848  1018  2877 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
03-17 13:26:05.848  1018  2877 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-17 13:26:05.858  1018  2874 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
03-17 13:26:05.868  2954  2954 E Zygote  : MountEmulatedStorage()
03-17 13:26:05.868  2954  2954 E Zygote  : v2
03-17 13:26:05.868  2954  2954 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:05.868  2954  2954 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:05.868  2954  2954 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:05.868  1018  1327 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2954 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:05.868  2954  2954 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:05.868  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:05.868  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:05.868  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 13:26:05.878  2954  2954 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:05.888  1018  1577 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 13:26:05.888  1018  1577 D SecContentProvider2: mCursor = null
03-17 13:26:05.898  1018  1043 W libprocessgroup: failed to open /acct/uid_10134/pid_2011/cgroup.procs: No such file or directory
03-17 13:26:05.898  1018  1043 W libprocessgroup: failed to open /acct/uid_10026/pid_1786/cgroup.procs: No such file or directory
03-17 13:26:05.918  2954  2954 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:05.918  2954  2954 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:05.948  2954  2954 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
03-17 13:26:05.948  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:05.948  1018  1573 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:05.948  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
03-17 13:26:05.958  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.958  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.958  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.958  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.958  1215  1215 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 13:26:05.968  2972  2972 E Zygote  : MountEmulatedStorage()
03-17 13:26:05.968  2972  2972 E Zygote  : v2
03-17 13:26:05.968  2972  2972 I libpersona: KNOX_SDCARD checking this for 10153
03-17 13:26:05.968  2972  2972 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:05.968  2972  2972 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:05.968  2972  2972 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:05.978  2972  2972 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:05.978  1018  1327 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2972 uid=10153 gids={50153, 9997} abi=armeabi-v7a
03-17 13:26:05.978  1018  1577 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 13:26:05.978  1018  1577 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 13:26:05.978  1018  1577 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:26:05.978  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 13:26:05.978  1018  1018 I MotionRecognitionService: Plugged
03-17 13:26:05.978  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-17 13:26:05.988  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:26:05.988  1174  1174 D PowerUI : Cable  true --> true mBootCompleted : true
03-17 13:26:05.988  1174  1174 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-17 13:26:05.988  1435  1435 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:26:05.988  1435  1435 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 13:26:05.998  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:26:05.998  2656  2741 D HeadsetStateMachine: Disconnected process message: 10
03-17 13:26:06.008  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:26:06.008  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:26:06.008  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:26:06.008  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:26:06.008  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:26:06.008  1174  1174 D SViewCoverView: level :100 plugged : 2
03-17 13:26:06.018  2972  2972 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.018  2972  2972 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.038  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.038  1018  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:06.038  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 13:26:06.048  1018  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.048  1018  1241 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:06.048  1018  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 13:26:06.048  2972  2972 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:06.068  2135  2895 W DriveInitializer: Background init thread ended
03-17 13:26:06.088  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.088  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.088  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.088  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.098  3000  3000 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.098  3000  3000 E Zygote  : v2
03-17 13:26:06.098  3000  3000 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:06.098  3000  3000 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.098  3000  3000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:06.108  1018  1139 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3000 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:06.108  3000  3000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:06.108  1018  1139 I ActivityManager: Killing 2217:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
03-17 13:26:06.108  3000  3000 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.128  3000  3000 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.128  3000  3000 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.158  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.158  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.158  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.158  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.158  1215  2996 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-17 13:26:06.178  1018  1575 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3015 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-17 13:26:06.178  3015  3015 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.178  3015  3015 I libpersona: KNOX_SDCARD checking this for 10155
03-17 13:26:06.178  3015  3015 E Zygote  : v2
03-17 13:26:06.178  3015  3015 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.178  3015  3015 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:06.178  1018  1575 I ActivityManager: Killing 2236:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
03-17 13:26:06.178  3015  3015 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:06.178  3015  3015 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.188  2903  2903 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
03-17 13:26:06.188  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.188  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:06.188  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 13:26:06.198  2903  2903 E ActivityThread: Failed to find provider info for flipboard.auth.internal
03-17 13:26:06.208  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.208  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:06.208  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-17 13:26:06.208  1477  1486 D TP/MmsProvider: Update uri=content://mms, match=0
03-17 13:26:06.208  1477  1486 D TP/MmsProvider: update , handleReadChangedBroadcast
03-17 13:26:06.208  1477  1486 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 13:26:06.208  1018  1018 I DrmEventReceiver: DrmEventReceiver : onReceive
03-17 13:26:06.208  1018  1018 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
03-17 13:26:06.218  1018  1018 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-17 13:26:06.218  1018  1018 I System.out: start Service
03-17 13:26:06.218  1215  1215 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-17 13:26:06.218  2420  2420 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-17 13:26:06.218  2420  2420 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 4444.178853
03-17 13:26:06.218  2420  2420 I Mms/ReservationManager: resetAfterConnected()
03-17 13:26:06.228  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-17 13:26:06.228  3015  3015 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.228  3015  3015 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.228  1018  1498 D SettingsProvider: name = next_alarm_formatted
03-17 13:26:06.228  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.228  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:06.228  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:06.228  1018  1498 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:06.228  1018  1498 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:06.228  1018  1498 D SettingsProvider: selectionArgs: false
03-17 13:26:06.228  1018  1498 D SettingsProvider: selectionArgs: 10081
03-17 13:26:06.228  1018  1498 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:06.228  1018  1498 D SettingsProvider: ret = -1
03-17 13:26:06.228  2420  3032 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 13:26:06.228  2420  3032 D Mms/TelephonyPermission: isDefault true
03-17 13:26:06.238  1477  1487 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2420
03-17 13:26:06.238  1477  1811 D TP/MmsSmsProvider: query,matched:7, calling pid = 2420
03-17 13:26:06.238  1477  1811 D TP/MmsSmsProvider: match 7:Elapsed time : 1.550 ms
03-17 13:26:06.248  1018  1498 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10081
03-17 13:26:06.268   284   508 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 1376
03-17 13:26:06.268   284   508 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 1376
03-17 13:26:06.268  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 13:26:06.268  2420  2420 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
03-17 13:26:06.278  1477  1811 D TP/MmsSmsProvider: query,matched:200, calling pid = 2420
03-17 13:26:06.278  1477  1811 D TP/MmsSmsProvider: match 200:Elapsed time : 1.198 ms
03-17 13:26:06.278  1018  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.278  1018  1241 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:06.278  1018  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-17 13:26:06.288  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.288  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.288  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.288  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.288  3015  3015 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 13:26:06.298  1018  1043 W libprocessgroup: failed to open /acct/uid_10064/pid_2217/cgroup.procs: No such file or directory
03-17 13:26:06.298  1018  1043 W libprocessgroup: failed to open /acct/uid_10065/pid_2236/cgroup.procs: No such file or directory
03-17 13:26:06.298  3042  3042 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.298  3042  3042 E Zygote  : v2
03-17 13:26:06.298  3042  3042 I libpersona: KNOX_SDCARD checking this for 10043
03-17 13:26:06.298  3042  3042 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.298  3042  3042 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:06.308  3042  3042 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:06.308  1018  1030 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3042 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 13:26:06.308  3042  3042 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.318  1477  1487 D TP/SmsProvider: query,matched:0, calling pid = 2420
03-17 13:26:06.318  1477  1487 D TP/SmsProvider: match 0:Elapsed time : 2.146 ms
03-17 13:26:06.328  2420  2420 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-17 13:26:06.328  2420  3049 D Mms/TelephonyPermission: isDefault true
03-17 13:26:06.328  2420  3049 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-17 13:26:06.328  2420  3049 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 109.255677
03-17 13:26:06.338  3042  3042 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.338  3042  3042 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.368  1018  3058 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
03-17 13:26:06.368  1018  1018 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
03-17 13:26:06.368  1679  1853 I art     : Explicit concurrent mark sweep GC freed 7377(364KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 779us total 34.388ms
03-17 13:26:06.378   284  3040 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-17 13:26:06.388  1018  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.388  1018  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:06.388  1018  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:06.398  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.398  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:06.398  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:06.398  1477  1477 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-17 13:26:06.408  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.408  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:06.408  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-17 13:26:06.408  2916  2916 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 141.838ms
03-17 13:26:06.418  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.418  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.418  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.418  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.428  2933  2933 D AndroidRuntime: 
03-17 13:26:06.428  2933  2933 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 13:26:06.428  2933  2933 D AndroidRuntime: CheckJNI is OFF
03-17 13:26:06.428  2933  2933 D AndroidRuntime: readGMSProperty: start
03-17 13:26:06.428  2933  2933 D AndroidRuntime: readGMSProperty: already setted!!
03-17 13:26:06.428  2933  2933 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 13:26:06.428  2933  2933 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 13:26:06.428  2933  2933 D AndroidRuntime: readGMSProperty: end
03-17 13:26:06.428  2933  2933 D AndroidRuntime: addProductProperty: start
03-17 13:26:06.438  1018  1571 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3061 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
03-17 13:26:06.438  3061  3061 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.438   298   298 E USB_UICC: Timeout! No signal received. Retry num = 30
03-17 13:26:06.438  3061  3061 E Zygote  : v2
03-17 13:26:06.438  3061  3061 I libpersona: KNOX_SDCARD checking this for 10002
03-17 13:26:06.438  3061  3061 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.448  3061  3061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:06.448  3061  3061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:06.448  3061  3061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.458  3042  3042 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 13:26:06.458  3042  3042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:06.458  3042  3042 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 13:26:06.468  3061  3061 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.478  3061  3061 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.488   316   316 I ServiceManager: Waiting for service AtCmdFwd...
03-17 13:26:06.528  1018  1241 I art     : Explicit concurrent mark sweep GC freed 34025(1726KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/33MB, paused 2.424ms total 179.217ms
03-17 13:26:06.528  1477  1811 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-17 13:26:06.538  1477  1811 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
03-17 13:26:06.538  1477  1477 D CscUpdateService: onStart
03-17 13:26:06.538  1477  1477 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-17 13:26:06.538  1477  1477 I CscUpdateService: set_CSC_version
03-17 13:26:06.538  1477  1477 E CscParser: update(): xml file exist
03-17 13:26:06.538   298   298 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 13:26:06.538   298   298 E USB_UICC: usb_uicc_init_qmi failed ! 
03-17 13:26:06.538   298   298 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 13:26:06.538   298   298 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-17 13:26:06.548  1215  2996 E SQLiteLog: (283) recovered 378 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
03-17 13:26:06.558  1477  1811 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 13:26:06.558  1477  1811 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
03-17 13:26:06.558  1477  1811 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
03-17 13:26:06.558  1477  1811 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:06.558  1477  1811 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:06.558  1477  1811 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:06.558  1477  1811 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:06.558  1477  1811 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:06.558  1477  1811 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:06.558  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.558  1477  1487 I art     : Explicit concurrent mark sweep GC freed 34451(2MB) AllocSpace objects, 5(80KB) LOS objects, 44% free, 4MB/8MB, paused 6.335ms total 234.401ms
03-17 13:26:06.558  1018  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:06.558  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 13:26:06.568  1018  1575 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.568  1018  1575 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:06.568  1018  1575 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 13:26:06.568  1477  1811 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-17 13:26:06.568  1477  1811 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 13:26:06.568  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.568  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.568  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.568  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.578  1477  1477 I CscUtil : isWifiOnly = false
03-17 13:26:06.588  3080  3080 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.588  3080  3080 E Zygote  : v2
03-17 13:26:06.588  3080  3080 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:06.588  3080  3080 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.588  3080  3080 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:06.588  3080  3080 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:06.588  1018  1573 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3080 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:06.588  1477  1477 I System.out: HandDataNode = null
03-17 13:26:06.588  1477  1477 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
03-17 13:26:06.598  3080  3080 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.598  1018  1327 D SettingsProvider: name = block_emergency_message
03-17 13:26:06.598  1018  1327 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:06.598  1018  1327 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:06.598  1018  1327 D SettingsProvider: selectionArgs: false
03-17 13:26:06.598  1018  1327 D SettingsProvider: selectionArgs: 10043
03-17 13:26:06.598  1018  1327 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:06.598  1018  1327 D SettingsProvider: ret = -1
03-17 13:26:06.598  2420  3049 D Mms/Conversation: deleteTempConversation(),deleted=0
03-17 13:26:06.598  1018  1030 W ActivityManager: getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
03-17 13:26:06.598  1477  1477 I CscUpdateService: This is normal boot : CSC not updated
03-17 13:26:06.608  1477  3077 D TP/SmsProvider: query,matched:51, calling pid = 2420
03-17 13:26:06.608  3015  3015 D [0]UMC:Core: onCreate(): 
03-17 13:26:06.608  1477  3088 E CscParser: update(): xml file exist
03-17 13:26:06.618  1477  3077 D TP/SmsProvider: match 51:Elapsed time : 9.569 ms
03-17 13:26:06.618  3080  3080 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.618  3080  3080 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.628  1477  3088 D CscGPS  : CSCGPS.updateParameters
03-17 13:26:06.628  1477  3088 D CscGPS  : supl host : null
03-17 13:26:06.628  1477  3088 D CscGPS  : SUPL Host is null or invalid
03-17 13:26:06.628  1477  3088 D CscGPS  : supl_ver : null
03-17 13:26:06.628  1477  3088 D CscGPS  : SUPL Ver is null or invalid
03-17 13:26:06.628  1477  3088 D CscGPS  : supl port : null
03-17 13:26:06.628  1477  3088 D CscGPS  : SUPL PORT is null or invalid
03-17 13:26:06.628  1477  3088 D CscGPS  : LPP : null
03-17 13:26:06.628  1477  3088 D CscGPS  : LPP is null or invalid
03-17 13:26:06.628  1477  3088 D CscGPS  : CSC don't have any AGPS value.
03-17 13:26:06.628  1477  1477 I CscUpdateService: same CSC Version
03-17 13:26:06.628  1477  1477 D CscUtil : Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 13:26:06.628  1477  1811 D SmsProvider: Update uri=content://sms/outbox, match=8
03-17 13:26:06.628  1477  1811 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 13:26:06.638  2420  3032 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 13:26:06.638  2420  3049 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-17 13:26:06.638  2420  3049 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-17 13:26:06.638  2420  3049 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
03-17 13:26:06.638  1477  3077 D TP/SmsProvider: query,matched:26, calling pid = 2420
03-17 13:26:06.638  1477  3077 D TP/SmsProvider: match 26:Elapsed time : 1.049 ms
03-17 13:26:06.638  1629  1639 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 13:26:06.648  2420  3049 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 13:26:06.658  2420  3049 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 13:26:06.658  2420  3049 D Mms/TelephonyPermission: isDefault true
03-17 13:26:06.658  1477  1487 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2420
03-17 13:26:06.668  3015  3015 D [0]UMC:DeviceInfo: USA==US==
03-17 13:26:06.668  1477  1486 D TP/MmsSmsProvider: query,matched:200, calling pid = 2420
03-17 13:26:06.668  1477  1486 D TP/MmsSmsProvider: match 200:Elapsed time : 1.598 ms
03-17 13:26:06.678  1477  1487 D TP/SmsProvider: query,matched:0, calling pid = 2420
03-17 13:26:06.678  1477  1487 D TP/SmsProvider: match 0:Elapsed time : 1.270 ms
03-17 13:26:06.688  1477  1486 D TP/SmsProvider: query,matched:51, calling pid = 2420
03-17 13:26:06.688  1477  1486 D TP/SmsProvider: match 51:Elapsed time : 2.869 ms
03-17 13:26:06.698  2420  3049 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 13:26:06.698  1499  1499 D Launcher.Model: reloadBadges entered.
03-17 13:26:06.698  1629  1639 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 13:26:06.698  1629  1639 D BadgeProvider: sendNotify, [notify] : null
03-17 13:26:06.698  1629  1639 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 13:26:06.698  1629  1639 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 13:26:06.698  1629  1639 D BadgeProvider: update, [UpdateCount] : 1
03-17 13:26:06.698  2420  3032 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 13:26:06.708  3015  3015 D USER_AGENT: UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
03-17 13:26:06.708  3015  3015 D [0]UMC:AdminManager: init - start
03-17 13:26:06.708  2420  3032 D Mms/MessagingNotification: remove alarm
03-17 13:26:06.718  1629  1647 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 13:26:06.718  3080  3080 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-17 13:26:06.718  1477  1811 D TP/SmsProvider: query,matched:0, calling pid = 2420
03-17 13:26:06.718  1477  1811 D TP/SmsProvider: match 0:Elapsed time : 2.816 ms
03-17 13:26:06.728  2420  3104 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 13:26:06.728  2420  3032 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 396.725572
03-17 13:26:06.728  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.728  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:06.728  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
03-17 13:26:06.738  3015  3015 D [0]UMC:AdminManager: loadAdmins
03-17 13:26:06.738  1303  1303 I WifiCredService: onCreate
03-17 13:26:06.748  3080  3080 D DSM     : [Lines:107] Normal booted
03-17 13:26:06.748  3080  3080 D DSM     : [Lines:114] Boot completed
03-17 13:26:06.758  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.758  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.758  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.758  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.758  1215  2996 D MediaScanner: Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 13:26:06.768  1629  3103 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 13:26:06.768  3114  3114 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.768  3114  3114 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:06.768  3114  3114 E Zygote  : v2
03-17 13:26:06.768  3114  3114 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.768  1499  1499 D Launcher.Model: reloadBadges entered.
03-17 13:26:06.768  1629  3103 D BadgeProvider: sendNotify, [notify] : null
03-17 13:26:06.768  1629  3103 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 13:26:06.768  1629  3103 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 13:26:06.768  1018  2825 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3114 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:06.768  3015  3015 D [0]UMC:AdminManager: init - end
03-17 13:26:06.768  3015  3015 D GSLBManager: migrateStoredUrlFromOldPref
03-17 13:26:06.768  1629  3103 D BadgeProvider: update, [UpdateCount] : 1
03-17 13:26:06.768  3114  3114 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:06.778  1303  1303 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 13:26:06.778  1303  1303 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 13:26:06.778  1303  1303 D MY_TAG  : Action boot completed received
03-17 13:26:06.778  3114  3114 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:06.778  3114  3114 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.778  2420  3049 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 13:26:06.778  2420  3049 D Mms/MessagingNotification: remove alarm
03-17 13:26:06.778  1303  1303 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-17 13:26:06.788  1018  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 13:26:06.788  1018  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 13:26:06.788  1018  1131 E WifiNative-wlan0: invaild command id : 215
03-17 13:26:06.788  3015  3015 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
03-17 13:26:06.788  3015  3015 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-17 13:26:06.788  3015  3015 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
03-17 13:26:06.788  3015  3015 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 13:26:06.788  3015  3015 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 13:26:06.788  3015  3015 D [0]UMC:UMCAdmin: isContainer : 0
03-17 13:26:06.798  1018  1031 I ActivityManager: Killing 2251:com.vlingo.midas/u0a28 (adj 15): empty #31
03-17 13:26:06.798  2420  3123 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 13:26:06.808  3114  3114 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.808  1477  1486 D TP/SmsProvider: query,matched:0, calling pid = 2420
03-17 13:26:06.808  3114  3114 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.808  1477  1486 D TP/SmsProvider: match 0:Elapsed time : 2.183 ms
03-17 13:26:06.818  2420  3049 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 93.453282
03-17 13:26:06.818  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-17 13:26:06.818  1018  1571 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-17 13:26:06.828  1303  2215 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-17 13:26:06.828  1018  2825 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
03-17 13:26:06.828  3114  3114 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 13:26:06.828  1215  2996 V MediaScanner: processDirectory :  /system/media
03-17 13:26:06.828  1018  1139 I ActivityManager: Killing 1515:com.android.printspooler/u0a132 (adj 15): empty #31
03-17 13:26:06.838  3015  3015 E [0]UMC:UMCAdmin: No active admin owned by uid 10155
03-17 13:26:06.838  3015  3015 D [0]UMC:UMCAdmin: isContainer : 0
03-17 13:26:06.838  3015  3015 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-17 13:26:06.838  1303  1303 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-17 13:26:06.838  1303  1303 I NearbySettings: MountReceiver.onReceive - Internal Path
03-17 13:26:06.848  3015  3015 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-17 13:26:06.848  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 13:26:06.848  3015  3015 D [0]UMC:CoreReceiver:  check PreETag 
03-17 13:26:06.878  3114  3114 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 13:26:06.888  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
03-17 13:26:06.888  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
03-17 13:26:06.888  3114  3114 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
03-17 13:26:06.898  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-17 13:26:06.908  1018  1043 W libprocessgroup: failed to open /acct/uid_10028/pid_2251/cgroup.procs: No such file or directory
03-17 13:26:06.908  1018  1043 W libprocessgroup: failed to open /acct/uid_10132/pid_1515/cgroup.procs: No such file or directory
03-17 13:26:06.918  3015  3015 D [0]UMC:ByodSetupStarter: Container ID : 0
03-17 13:26:06.918  3015  3015 V [0]UMC:Utils: checkAppScreen() : com.sec.android.app.launcher
03-17 13:26:06.918  3015  3015 I [0]UMC:Core: shutdown
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 13:26:06.918  3015  3015 I art     : System.exit called, status: 0
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 13:26:06.918  3015  3015 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-17 13:26:06.918  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-17 13:26:06.928  3114  3114 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-17 13:26:06.928  1018  1577 D SettingsProvider: name = personal_mode_enabled
03-17 13:26:06.938  3114  3114 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-17 13:26:06.938  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.938  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.938  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.938  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.948  3138  3138 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.948  3138  3138 E Zygote  : v2
03-17 13:26:06.948  3138  3138 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:06.948  3138  3138 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.948  3138  3138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:06.948  3138  3138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:06.958  3138  3138 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.958  1018  1489 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3138 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:06.958  1215  2996 V MediaScanner:  prescan time: 580ms (DB items: 138)
03-17 13:26:06.958  1215  2996 V MediaScanner:     scan time: 158ms (Caching mode: true), (makeEntry time: 18ms ~11%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 13:26:06.958  1215  2996 V MediaScanner: postscan time: 1ms (bulkDeleter : 0), (delete DeadThumbnail time : 1ms)
03-17 13:26:06.958  1215  2996 V MediaScanner:    total time: 739ms
03-17 13:26:06.958  1215  2996 V MediaScanner: checked files: 130  directories : 6  (I: 0, U: 0)
03-17 13:26:06.958  1018  1489 I ActivityManager: Killing 2277:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
03-17 13:26:06.958  1215  2996 D MediaScanner: checkDefaultSounds
03-17 13:26:06.958  1215  2996 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
03-17 13:26:06.968  1018  1498 I ActivityManager: Killing 2334:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
03-17 13:26:06.978  3138  3138 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.978  3138  3138 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.988  1215  2996 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-17 13:26:06.988  1215  2996 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
03-17 13:26:06.988  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 13:26:06.998  1215  2996 D MediaScanner: OK. notification_sound is already exist in setting DB.
03-17 13:26:06.998  1018  2826 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3015)(adj 0) has died(49,667)
03-17 13:26:06.998  1215  2996 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
03-17 13:26:07.008  1215  2996 D MediaScanner: OK. ringtone is already exist in setting DB.
03-17 13:26:07.008  2629  2629 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2629) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 13:26:07.008  1215  2996 D MediaScannerService: !@done scanning volume internal
03-17 13:26:07.008  2629  2629 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2629) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-17 13:26:07.018  1215  2996 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
03-17 13:26:07.008  2629  2629 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2629) ACTION_MEDIA_SCANNER_FINISHED = Ignored
03-17 13:26:07.018  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 13:26:07.018  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 13:26:07.018  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 13:26:07.018  1215  2996 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 13:26:07.028  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 13:26:07.028  1215  2996 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
03-17 13:26:07.028  1018  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.028  1018  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:07.028  1018  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-17 13:26:07.028  1215  2996 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
03-17 13:26:07.028  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-17 13:26:07.038  1823  1823 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
03-17 13:26:07.038  1823  1823 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 13:26:07.038  1823  1823 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 13:26:07.038  1018  1043 W libprocessgroup: failed to open /acct/uid_10045/pid_2277/cgroup.procs: No such file or directory
03-17 13:26:07.038  1823  1823 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 13:26:07.038  1823  1823 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 13:26:07.038  1823  1823 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 13:26:07.038  1823  1823 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
03-17 13:26:07.038  1215  2996 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 13:26:07.038  1215  2996 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 13:26:07.038  1215  2996 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-17 13:26:07.048  1215  2996 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
03-17 13:26:07.048  1215  2996 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 13:26:07.048  1477  1477 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 13:26:07.048  1018  1031 D SettingsProvider: name = aw_daemon_service_key_version_check
03-17 13:26:07.048  1477  1477 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:07.048  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:07.048  1477  1477 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:07.048  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:07.048  1477  1477 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:07.048  1018  1031 D SettingsProvider: selectionArgs: false
03-17 13:26:07.048  1477  1477 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:07.048  1018  1031 D SettingsProvider: selectionArgs: 10157
03-17 13:26:07.048  1477  1477 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 13:26:07.048  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:07.048  1018  1031 D SettingsProvider: ret = -1
03-17 13:26:07.058  1215  2996 D MediaScanner: Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 13:26:07.058  1018  1031 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10157
03-17 13:26:07.058  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-17 13:26:07.068  2933  2933 E AffinityControl: AffinityControl: registerfunction enter
03-17 13:26:07.068  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 13:26:07.068  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
03-17 13:26:07.068  1303  1303 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 13:26:07.068  1303  1303 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-17 13:26:07.078  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 13:26:07.078  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 13:26:07.078  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
03-17 13:26:07.078  1823  1823 D daemonapp: [MSC_Daemo,n]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-17 13:26:07.088  1823  1823 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
03-17 13:26:07.088  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 13:26:07.088  1215  2996 V MediaScanner: processDirectory :  /storage/emulated/0
03-17 13:26:07.088  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458217567100
03-17 13:26:07.088  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458239160000
03-17 13:26:07.088  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-17 13:26:07.088  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
03-17 13:26:07.088  1215  2996 D MediaScanner: Skipping:
03-17 13:26:07.088  1215  2996 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
03-17 13:26:07.088  1823  1823 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458239160000
03-17 13:26:07.108  1215  2996 D MediaScanner: Skipping:
03-17 13:26:07.108  1215  2996 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-17 13:26:07.108  1215  2996 V MediaScanner: processDirectory :  /storage/extSdCard
03-17 13:26:07.108  1215  2996 W MediaScanner: Error opening directory, reason : Permission denied.
03-17 13:26:07.108  1215  2996 W MediaScanner: 7klwibgf7fxlKdCbid7
03-17 13:26:07.108  1215  2996 V MediaScanner:  prescan time: 38ms (DB items: 26)
03-17 13:26:07.108  1215  2996 V MediaScanner:     scan time: 24ms (Caching mode: true), (makeEntry time: 11ms ~45%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 13:26:07.108  1215  2996 V MediaScanner: postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 13:26:07.108  1215  2996 V MediaScanner:    total time: 64ms
03-17 13:26:07.108  1215  2996 V MediaScanner: checked files: 10  directories : 16  (I: 0, U: 0)
03-17 13:26:07.128  3138  3138 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
03-17 13:26:07.138  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
03-17 13:26:07.138  1303  1303 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
03-17 13:26:07.138  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 45
03-17 13:26:07.138  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458239160000
03-17 13:26:07.138  2933  2933 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 13:26:07.148  1215  2996 D MediaScannerService: !@done scanning volume external
03-17 13:26:07.148  2629  2629 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2629) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 13:26:07.148  2629  2629 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2629) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-17 13:26:07.158  2629  2629 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2629) ...
03-17 13:26:07.158  2629  2629 D FactoryTestApp: [Support$Values.getString](2629) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 13:26:07.158  2629  2629 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2629) mConnectionMode = gsm
03-17 13:26:07.158  2629  2629 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2629) Create IPCWriterToSecPhoneService
03-17 13:26:07.158  2629  2629 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2629)  
03-17 13:26:07.158  2629  2629 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
03-17 13:26:07.158  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.158  1018  2826 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:07.158  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-17 13:26:07.168  1823  1823 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-17 13:26:07.168  1823  1823 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
03-17 13:26:07.178  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.178  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.178  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.178  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.188  3161  3161 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.188  3161  3161 E Zygote  : v2
03-17 13:26:07.188  3161  3161 I libpersona: KNOX_SDCARD checking this for 10161
03-17 13:26:07.188  3161  3161 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:07.198  3161  3161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:07.198  1018  1489 E PersonaManagerService: inState():  stateMachine is null !!
03-17 13:26:07.198  1018  1489 I PersonaManagerService: PersonaId don't exist
03-17 13:26:07.198  1018  1489 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 13:26:07.198  1018  1571 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3161 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:07.198  3161  3161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:07.198  1303  1303 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
03-17 13:26:07.198  3161  3161 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 13:26:07.208  1018  1489 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 13:26:07.218   305   305 I art     : Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 23.825ms
03-17 13:26:07.228  1018  1489 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 13:26:07.228  1018  1489 W ActivityManager: mDVFSHelper.acquire()
03-17 13:26:07.228  1303  1303 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-17 13:26:07.228  1303  1303 I SettingSearch/SearchIntentReceiver: search setting db init!!
03-17 13:26:07.228  1018  1489 D FocusedStackFrame: Set to : 0
03-17 13:26:07.228  3161  3161 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:07.228  1303  1303 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-17 13:26:07.228  3161  3161 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:07.238   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 17.083ms
03-17 13:26:07.238  1018  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 13:26:07.238  1018  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 13:26:07.238  1018  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 13:26:07.238  1018  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 13:26:07.248   259   259 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 13:26:07.248  1499  1499 D Launcher.HomeView: onPause
03-17 13:26:07.248   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 16.877ms
03-17 13:26:07.258  1499  1499 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 13:26:07.268  1018  1489 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 13:26:07.268  1018  1489 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 13:26:07.268  1018  1489 D InputDispatcher: Focused application set to: xxxx
03-17 13:26:07.268  1018  1489 D InputDispatcher: Focus left window: 1499
03-17 13:26:07.268  2933  2933 D AndroidRuntime: Shutting down VM
03-17 13:26:07.268  2629  2629 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2629) connected done
03-17 13:26:07.268  2629  2629 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2629) Send Response Message to SecPhone
03-17 13:26:07.268  2629  2629 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2629) Response ��
03-17 13:26:07.268  1303  3177 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
03-17 13:26:07.278  3138  3138 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
03-17 13:26:07.278   311  1076 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 13:26:07.278  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:07.278  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 13:26:07.278  2629  2629 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2629) Send BOOTING COMPLETED done
03-17 13:26:07.288  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.288  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.288  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.288  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.288  3138  3138 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
03-17 13:26:07.308  3179  3179 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.308  3179  3179 E Zygote  : v2
03-17 13:26:07.308  3179  3179 I libpersona: KNOX_SDCARD checking this for 10167
03-17 13:26:07.308  3179  3179 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:07.308  1018  1139 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3179 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 13:26:07.308  3179  3179 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:07.318  3179  3179 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:07.318  3179  3179 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 13:26:07.318  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.318  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.318  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.318  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.338  3189  3189 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.338  3189  3189 E Zygote  : v2
03-17 13:26:07.338  3189  3189 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:07.338  3189  3189 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:07.348  1018  1573 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3189 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:07.348  3179  3179 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:07.348  3179  3179 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:07.358  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.358  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.358  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.358  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.368  3138  3138 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
03-17 13:26:07.368  3138  3138 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 13:26:07.368  3138  3138 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-17 13:26:07.368  3189  3189 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:07.368  3138  3138 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
03-17 13:26:07.368  3200  3200 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.368  3189  3189 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:07.368  3200  3200 E Zygote  : v2
03-17 13:26:07.368  3200  3200 I libpersona: KNOX_SDCARD checking this for 10146
03-17 13:26:07.368  3189  3189 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:07.368  3200  3200 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:07.368  3200  3200 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:07.368  1018  2825 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3200 uid=10146 gids={50146, 9997} abi=armeabi-v7a
03-17 13:26:07.368  1018  1327 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:07.368  1018  1327 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 13:26:07.368  1018  1327 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:07.378  3200  3200 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:07.378  3200  3200 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 13:26:07.378  1018  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 13:26:07.378   311  1076 D AT_Distributor: SetAtdStatus(), 1_1_0
03-17 13:26:07.378   311  1076 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 13:26:07.388  1018  1327 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:26:07.398  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:07.398  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:07.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:07.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:07.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:07.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:07.408  1018  1018 D SensorService: [SO] activate (ident=0xb7b22538, enabled=0)
03-17 13:26:07.408  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 13:26:07.408  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-17 13:26:07.408  3189  3189 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:07.408  3189  3189 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:07.408  1018  1018 D SensorManager: unregisterListener ::   
03-17 13:26:07.408  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-17 13:26:07.418  1018  1018 D SensorService: [SO] changed settle time [1]
03-17 13:26:07.418  1018  1018 D SensorService: [SO] setDelay [66000000]
03-17 13:26:07.418  1018  1018 D SensorService: [SO] activate (ident=0xb7b22538, enabled=1)
03-17 13:26:07.418  1018  1018 D SensorService: [SO] AR_init
03-17 13:26:07.418  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-17 13:26:07.418  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-17 13:26:07.428  3200  3200 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:07.428  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.428  1499  1499 V ActivityThread: updateVisibility : ActivityRecord{199b3e57 token=android.os.BinderProxy@13dc13c7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 13:26:07.428  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.428  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.428  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.428  3200  3200 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:07.428  1499  1499 D Launcher.HomeView: onStop
03-17 13:26:07.428  1499  1499 V ActivityThread: updateVisibility : ActivityRecord{199b3e57 token=android.os.BinderProxy@13dc13c7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 13:26:07.428  1499  1499 D Launcher: onTrimMemory. Level: 20
03-17 13:26:07.448  3189  3189 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:07.448  3224  3224 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.448  3224  3224 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:07.448  3224  3224 E Zygote  : v2
03-17 13:26:07.448  3224  3224 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:07.448  3224  3224 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:07.448  3224  3224 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:07.448  3224  3224 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:07.468   290   290 E SMD     : DCD OFF
03-17 13:26:07.468  1018  1031 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3224 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:07.478  2933  2933 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 13:26:07.488  1018  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-17 13:26:07.488  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.488  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.488  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.488  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.488  3224  3224 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:07.488  3224  3224 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:07.488   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:26:07.498  3240  3240 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.498  3240  3240 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:07.498  3240  3240 E Zygote  : v2
03-17 13:26:07.498  3240  3240 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.508  3240  3240 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:07.508  1018  1139 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3240 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 13:26:07.508  3240  3240 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:07.508  3240  3240 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:07.518  2656  2747 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-17 13:26:07.528  3224  3224 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:07.538  2656  2747 D BluetoothMediaBrowser: no now playing list
03-17 13:26:07.538  2656  2747 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-17 13:26:07.548  3240  3240 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.548  3240  3240 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.548  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.548  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.548  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.548  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.558  1018  1041 D SensorService: [SO] currT = 37331055000, prevT = 37011106000, diff = 319949000, [-0.460 0.211 9.883]
,03-17 13:26:07.558  1018  1041 D SensorService: [SO] -0.460 0.211 9.883
03-17 13:26:07.558  1018  1041 D SensorService: [SO] [100 -> 255]
,03-17 13:26:07.578  3255  3255 E Zygote  : MountEmulatedStorage()
,03-17 13:26:07.578  3255  3255 E Zygote  : v2
03-17 13:26:07.578  3255  3255 I libpersona: KNOX_SDCARD checking this for 10082
03-17 13:26:07.578  3255  3255 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.578  3255  3255 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:07.578  1018  1489 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3255 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
,03-17 13:26:07.578  3255  3255 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:07.578  1018  1489 I ActivityManager: Killing 1670:com.google.android.partnersetup/u0a14 (adj 15): empty #31
03-17 13:26:07.578  3255  3255 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:07.608  3255  3255 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.608  3255  3255 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.628  3161  3239 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 13:26:07.628  3161  3239 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 13:26:07.648  3179  3179 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-17 13:26:07.658  3179  3179 I LibraryLoader: Loading: webviewchromium
,03-17 13:26:07.658  3179  3179 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7433-7437)
03-17 13:26:07.658  3179  3179 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 13:26:07.698  1018  1043 W libprocessgroup: failed to open /acct/uid_10014/pid_1670/cgroup.procs: No such file or directory
,03-17 13:26:07.718  3161  3239 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 13:26:07.768  3161  3239 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 13:26:07.778  3161  3239 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fbb7a44: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-17 13:26:07.778  3161  3239 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 13:26:07.838   259  1040 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-17 13:26:07.838   259  1040 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-17 13:26:07.838  3224  3224 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 13:26:07.838  1018  1575 I art     : Explicit concurrent mark sweep GC freed 17304(867KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.523ms total 143.416ms
,03-17 13:26:07.858  3179  3179 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3af07e8f}
,03-17 13:26:07.858  3179  3179 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 13:26:07.858  3179  3179 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 13:26:07.868  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.868  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.868  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.868  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.868  3255  3255 E UpdateRequestReceiver: ignoring update request
,03-17 13:26:07.878  3280  3280 E Zygote  : MountEmulatedStorage(),
03-17 13:26:07.878  3280  3280 E Zygote  : v2
03-17 13:26:07.878  3280  3280 I libpersona: KNOX_SDCARD checking this for 10008
03-17 13:26:07.878  3280  3280 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.878  3280  3280 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 13:26:07.888  3280  3280 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 13:26:07.888  3179  3179 I BrowserStartupController: Initializing chromium process, renderers=0
03-17 13:26:07.888  3280  3280 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 13:26:07.888  1018  1031 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3280 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:07.888  3179  3179 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:26:07.898  3255  3255 E UpdateRequestReceiver: ignoring update request
,03-17 13:26:07.908  3280  3280 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.908  3280  3280 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.908  3179  3179 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-17 13:26:07.918  3179  3179 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
03-17 13:26:07.918  3179  3179 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,03-17 13:26:07.928  3255  3255 E UpdateRequestReceiver: ignoring update request
,03-17 13:26:07.938  3255  3255 E UpdateRequestReceiver: ignoring update request
,03-17 13:26:07.938  3179  3179 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 13:26:07.938  3179  3179 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 13:26:07.938  3179  3179 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 13:26:07.938  3179  3179 I Adreno-EGL: Local Branch: 
03-17 13:26:07.938  3179  3179 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 13:26:07.938  3179  3179 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 13:26:07.938  3179  3179 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-17 13:26:07.948  3255  3255 E UpdateRequestReceiver: ignoring update request
03-17 13:26:07.968  3255  3255 E UpdateRequestReceiver: ignoring update request
,03-17 13:26:07.968  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.968  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.968  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.968  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.968  3240  3240 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-17 13:26:07.978  3240  3240 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 13:26:07.978  3323  3323 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.978  3323  3323 E Zygote  : v2
03-17 13:26:07.978  3323  3323 I libpersona: KNOX_SDCARD checking this for 10088
03-17 13:26:07.978  3323  3323 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.978  3323  3323 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:07.988  1018  1498 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3323 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:07.988  3323  3323 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:07.988  3323  3323 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 13:26:07.988  3240  3318 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 13:26:07.998  3240  3240 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-17 13:26:07.998  3240  3318 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-17 13:26:07.998  3224  3224 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 13:26:07.998  3240  3240 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 13:26:07.998  3240  3240 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-17 13:26:08.008  3240  3240 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-17 13:26:08.008  3240  3240 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-17 13:26:08.008  3240  3240 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,03-17 13:26:08.018  3240  3318 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-17 13:26:08.018  3323  3323 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.018  3323  3323 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.028  3240  3240 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 13:26:08.028  3224  3224 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-17 13:26:08.028  3240  3240 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 13:26:08.038  3224  3224 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-17 13:26:08.038   258   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 13:26:08.038   258   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:08.038  3161  3161 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 13:26:08.048  3240  3240 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-17 13:26:08.048  3240  3240 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 13:26:08.048  3240  3240 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-17 13:26:08.108  3179  3309 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-17 13:26:08.108  3179  3179 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-17 13:26:08.158  3240  3251 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:08.158  3240  3251 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:08.158  3240  3251 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 13:26:08.168  3240  3249 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:08.168  3240  3249 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:08.168  3240  3249 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 13:26:08.228  3224  3224 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-17 13:26:08.238  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.238  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.238  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.238  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.238  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-17 13:26:08.238  3224  3224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-17 13:26:08.238  3179  3179 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,03-17 13:26:08.248  3355  3355 E Zygote  : MountEmulatedStorage()
,03-17 13:26:08.248  3355  3355 E Zygote  : v2
03-17 13:26:08.248  3355  3355 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:08.248  3355  3355 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:08.248  3355  3355 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:08.248  3179  3179 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 13:26:08.248  1018  1139 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3355 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:08.258  3355  3355 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 13:26:08.258  3355  3355 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:08.258  1018  1139 I ActivityManager: Killing 2452:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,03-17 13:26:08.258  1018  1139 I ActivityManager: Killing 2436:com.sec.tcpdumpservice/1000 (adj 15): empty #32
03-17 13:26:08.258  1018  1139 I ActivityManager: Killing 2404:com.sec.modem.settings/1000 (adj 15): empty #33
,03-17 13:26:08.268  1018  1575 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:08.268  1018  1575 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-17 13:26:08.268  1018  1575 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 13:26:08.268  3179  3179 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 13:26:08.268  3179  3179 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 13:26:08.268  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.268  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.268  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.268  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.278  3179  3179 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 13:26:08.288  3367  3367 E Zygote  : MountEmulatedStorage(),
03-17 13:26:08.288  3367  3367 E Zygote  : v2
03-17 13:26:08.288  3367  3367 I libpersona: KNOX_SDCARD checking this for 10088
03-17 13:26:08.288  3367  3367 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:08.288  3367  3367 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:08.288  1018  1575 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3367 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:08.288  3367  3367 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:08.288  1018  1571 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:08.288  3367  3367 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 13:26:08.288  1018  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:08.288  1018  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 13:26:08.298  3179  3179 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 13:26:08.298  3179  3179 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:26:08.298  3355  3355 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:08.298  3355  3355 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:08.308  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 13:26:08.308  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-17 13:26:08.318  3240  3318 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-17 13:26:08.318  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-17 13:26:08.328  3240  3318 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 13:26:08.328  1174  1174 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-17 13:26:08.328  1174  1174 D OverheatReceiver: into the SAFE_MODE_ACTION
03-17 13:26:08.328  1174  1174 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-17 13:26:08.328  1174  1174 D OverheatReceiver: isSafeMode = false
,03-17 13:26:08.338  1477  1477 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
03-17 13:26:08.338  1018  1573 D SettingsProvider: name = internet_call_settings_visibility
03-17 13:26:08.338  1018  1573 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:08.338  1018  1573 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:08.338  1018  1573 D SettingsProvider: selectionArgs: false
03-17 13:26:08.338  1018  1573 D SettingsProvider: selectionArgs: 1001
03-17 13:26:08.338  1018  1573 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:08.338  1018  1573 D SettingsProvider: ret = -1
,03-17 13:26:08.338  1477  1477 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 13:26:08.348  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 13:26:08.348  3224  3224 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-17 13:26:08.348  3367  3367 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.348  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
03-17 13:26:08.348  3367  3367 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.348  3224  3224 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-17 13:26:08.348  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-17 13:26:08.348  3224  3224 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-17 13:26:08.348  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-17 13:26:08.358  3224  3224 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-17 13:26:08.358  1018  2826 I ActivityManager: Killing 2469:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 13:26:08.358  3224  3224 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,03-17 13:26:08.358  3224  3331 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-17 13:26:08.368  3240  3318 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 13:26:08.368  3240  3318 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-17 13:26:08.368  3224  3224 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-17 13:26:08.368  3179  3392 D OpenGLRenderer: Render dirty regions requested: true
03-17 13:26:08.368  3240  3318 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-17 13:26:08.378  1018  2825 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 13:26:08.378  3224  3224 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
03-17 13:26:08.378  1018  2825 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 13:26:08.378  1018  2825 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 13:26:08.378  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 13:26:08.378  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 13:26:08.378  3224  3224 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-17 13:26:08.378  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
03-17 13:26:08.378  3179  3179 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 13:26:08.378  3179  3179 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 13:26:08.378  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-17 13:26:08.388  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-17 13:26:08.398  3224  3224 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 13:26:08.398  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2404/cgroup.procs: No such file or directory
03-17 13:26:08.398  1018  1043 W libprocessgroup: failed to open /acct/uid_10127/pid_2452/cgroup.procs: No such file or directory
,03-17 13:26:08.428  3224  3331 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 13:26:08.428  3224  3331 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-17 13:26:08.428  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:08.428  1018  2825 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:08.428  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 13:26:08.428  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2436/cgroup.procs: No such file or directory
,03-17 13:26:08.428  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2469/cgroup.procs: No such file or directory
,03-17 13:26:08.438  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-17 13:26:08.448  1444  1444 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-17 13:26:08.448  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.448  1018  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:08.448  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 13:26:08.458  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.458  1018  2825 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:08.458  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 13:26:08.458  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.458  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.458  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.458  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.458   259   259 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 13:26:08.468  3398  3398 E Zygote  : MountEmulatedStorage(),
,03-17 13:26:08.478  3398  3398 E Zygote  : v2
03-17 13:26:08.478  3398  3398 I libpersona: KNOX_SDCARD checking this for 10052
03-17 13:26:08.478  3398  3398 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:08.478  3398  3398 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 13:26:08.478  3398  3398 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 13:26:08.478  3398  3398 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:08.478  1018  2826 D InputDispatcher: Focus entered window: 3179
,03-17 13:26:08.488  1018  1498 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3398 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
,03-17 13:26:08.488  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:08.488  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 13:26:08.488   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 13:26:08.488  3179  3179 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 13:26:08.488  3179  3392 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 13:26:08.498  3355  3355 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
03-17 13:26:08.498  3179  3392 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 13:26:08.498  3179  3392 D OpenGLRenderer: Enabling debug mode 0
,03-17 13:26:08.508   305   305 I art     : Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 614us total 26.925ms
,03-17 13:26:08.508  3398  3398 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.518  3398  3398 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.518  1018  1241 I ActivityManager: Killing 2514:com.wsomacp/u0a23 (adj 15): empty #31
,03-17 13:26:08.528   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 651us total 17.274ms
,03-17 13:26:08.538  3240  3318 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 13:26:08.548   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 569us total 17.167ms,
,03-17 13:26:08.588  1018  1043 W libprocessgroup: failed to open /acct/uid_10023/pid_2514/cgroup.procs: No such file or directory
,03-17 13:26:08.658  1018  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.658  1018  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.658  1018  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.658  1018  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.658  1018  1498 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 13:26:08.658  3323  3323 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 13:26:08.658  3355  3355 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 13:26:08.658  3355  3355 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 13:26:08.658  3355  3355 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 13:26:08.658  3224  3331 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-17 13:26:08.668  1018  1031 E Tethering: No numeric data
,03-17 13:26:08.668  3240  3318 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 13:26:08.668  1018  1569 E Tethering: No numeric data
,03-17 13:26:08.678  1018  3424 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-17 13:26:08.678  3425  3425 E Zygote  : MountEmulatedStorage()
03-17 13:26:08.678  3425  3425 E Zygote  : v2
03-17 13:26:08.678  3425  3425 I libpersona: KNOX_SDCARD checking this for 10014
03-17 13:26:08.678  3425  3425 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:08.678  3425  3425 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:08.678  1174  1174 I StatusBar: Icon Only
03-17 13:26:08.678  3240  3318 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 13:26:08.678  3425  3425 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:08.688  1174  1174 D PanelView: There is/are notification(s) 
,03-17 13:26:08.688  3240  3318 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-17 13:26:08.688  3425  3425 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 13:26:08.688  3240  3319 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-17 13:26:08.688  3240  3318 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 13:26:08.688  1018  3429 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:08.688  1018  1577 E Tethering: No numeric data
,03-17 13:26:08.698  3240  3318 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
,03-17 13:26:08.698  1018  1241 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3425 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a,
,03-17 13:26:08.698  1018  1498 E Tethering: No numeric data,
03-17 13:26:08.698  3179  3179 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b61c2aa time:38477
03-17 13:26:08.708  1444  1444 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
03-17 13:26:08.698  3240  3318 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/13:26:08
03-17 13:26:08.708  3240  3318 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
03-17 13:26:08.708  3240  3318 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
03-17 13:26:08.708  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.708  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.708  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.708  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.718  1018  1139 E Tethering: No numeric data,
,03-17 13:26:08.718  3240  3319 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 13:26:08.718  1018  1571 E Tethering: No numeric data
,03-17 13:26:08.718  3425  3425 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.728  3425  3425 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.728  1018  1498 D LocationManagerService: getProviders()=[passive]
,03-17 13:26:08.728  3240  3319 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 13:26:08.738  3240  3319 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 13:26:08.738  3444  3444 E Zygote  : MountEmulatedStorage()
,03-17 13:26:08.738  3444  3444 E Zygote  : v2
03-17 13:26:08.738  3240  3319 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
03-17 13:26:08.738  3444  3444 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:08.738  3444  3444 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:08.738  3444  3444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:08.738  1018  1030 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3444 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:08.738  3240  3319 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
03-17 13:26:08.738  3240  3319 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
03-17 13:26:08.738  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.738  1018  2825 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:08.738  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
03-17 13:26:08.738  3444  3444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:08.738  3240  3319 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
03-17 13:26:08.738  3444  3444 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:08.748  3240  3319 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
03-17 13:26:08.748  3240  3319 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 13:26:08.758  1018  1050 I ActivityManager: Displayed Component not be shown by security: +1s477ms
,03-17 13:26:08.758  1018  1050 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 13:26:08.768  1018  1050 W ActivityManager: mDVFSHelper.release()
03-17 13:26:08.768  1018  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8c58821 u0 com.test.thalitest/.MainActivity t11} time:38541
03-17 13:26:08.768  1018  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:08.778  3240  3319 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 13:26:08.778  3444  3444 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.788  3444  3444 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.848  3444  3444 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-17 13:26:08.848  3444  3444 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 13:26:08.848  3444  3444 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 13:26:08.858  3398  3462 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 13:26:08.858  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:08.858  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:08.858  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 13:26:08.868  3444  3455 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 13:26:08.878  3355  3355 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 13:26:08.878  3355  3355 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 13:26:08.878  3355  3355 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 13:26:08.878  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.878  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.878  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.878  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.888  3466  3466 E Zygote  : MountEmulatedStorage(),
03-17 13:26:08.888  3466  3466 E Zygote  : v2
03-17 13:26:08.888  3466  3466 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:08.888  3466  3466 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:08.898  3466  3466 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:08.898  3466  3466 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 13:26:08.898  3466  3466 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:08.898  1018  1571 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3466 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 13:26:08.898  1018  1571 I ActivityManager: Killing 2564:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
03-17 13:26:08.898  3240  3318 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 13:26:08.918  3323  3323 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-17 13:26:08.938  3466  3466 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.938  3466  3466 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.958  3224  3331 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-17 13:26:08.978  3323  3323 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-17 13:26:08.998   259   430 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-17 13:26:08.998   259   437 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-17 13:26:09.008  3240  3319 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-17 13:26:09.008  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:09.008  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:09.008  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube,
,03-17 13:26:09.008  1882  1882 I SamsungIME: getCurrentCandidateView
03-17 13:26:09.008  3224  3331 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 13:26:09.018  3224  3331 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-17 13:26:09.018  3224  3331 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 13:26:09.028  1303  3177 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 13:26:09.028  1303  3177 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 13:26:09.028  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.028  1018  1043 W libprocessgroup: failed to open /acct/uid_10139/pid_2564/cgroup.procs: No such file or directory
03-17 13:26:09.028  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:09.028  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 13:26:09.038  3323  3323 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-17 13:26:09.048  3323  3323 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-17 13:26:09.048  3240  3318 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-17 13:26:09.048  3240  3318 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 13:26:09.048  1018  1139 I ActivityManager: Killing 2581:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,03-17 13:26:09.068  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:09.078  1018  1030 E Tethering: No numeric data
,03-17 13:26:09.078  3323  3323 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-17 13:26:09.088  1018  1573 E Tethering: No numeric data
,03-17 13:26:09.088  1018  1031 E Tethering: No numeric data
,03-17 13:26:09.098   285   285 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
,03-17 13:26:09.098   285   285 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 13:26:09.098   285   285 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 13:26:09.098   285   285 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 13:26:09.098   285   285 I str_params: key: 'call_forwarding' value: ''
,03-17 13:26:09.098  1935  1935 V InCall  : ProximitySensor -  - screenonImmediately: false
,03-17 13:26:09.098  1935  1935 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-17 13:26:09.098  3466  3466 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
03-17 13:26:09.098  1935  1935 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-17 13:26:09.098  1935  1935 D ScoverManager: serviceVersion : 16908288
,03-17 13:26:09.098  1018  2826 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 13:26:09.108  3466  3466 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 13:26:09.118  1018  1043 W libprocessgroup: failed to open /acct/uid_10135/pid_2581/cgroup.procs: No such file or directory
,03-17 13:26:09.118  1935  1935 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-17 13:26:09.118  1018  1030 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 13:26:09.118  1935  1935 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-17 13:26:09.118  1935  1935 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-17 13:26:09.118  1444  1444 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-17 13:26:09.128  1018  2754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 13:26:09.128  1018  1571 E Tethering: No numeric data,
03-17 13:26:09.128  1935  1935 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
03-17 13:26:09.128  1935  1935 D InCall  : InCallPresenter -  - dismissCoverDialog()...,
,03-17 13:26:09.138  1935  1935 I InCall  : CallSContextMotion - stopPutDownListening
,03-17 13:26:09.138  1935  1935 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 13:26:09.138  3323  3323 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 13:26:09.148  3444  3455 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 13:26:09.148  1018  2825 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 13:26:09.148  1935  1935 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-17 13:26:09.148  3466  3466 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 13:26:09.148  1174  1174 D PhoneStatusBarView: setCallBackground:0
,03-17 13:26:09.148  3161  3161 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 13:26:09.178  3179  3179 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-17 13:26:09.178  3466  3466 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 13:26:09.188  3323  3323 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 13:26:09.188  1882  1882 D SamsungIME: Dismiss ExpandCandiate
,03-17 13:26:09.188  1018  1510 V VibratorService: hasVibrator - useVibetonz: true
,03-17 13:26:09.198  1303  3177 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 13:26:09.198  1935  1935 D VideoCallManager: Instantiating VideoCallManager
,03-17 13:26:09.198  1018  1139 V VibratorService: hasVibrator - useVibetonz: true
,03-17 13:26:09.208  1018  1498 V VibratorService: hasVibrator - useVibetonz: true
,03-17 13:26:09.208  3240  3319 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-17 13:26:09.228  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 13:26:09.228  1935  1935 I GFX construct_block_size_descriptor_2d second part: took 2.422604ms for 0*0 texture 0
,03-17 13:26:09.228  1935  1935 I GFX generate_partition_tables: took 5.110000ms for 0*0 texture 0,
,03-17 13:26:09.238  1303  3177 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 13:26:09.238  1935  1935 I GFX raster: took 11.649533ms for 176*144 texture 0
03-17 13:26:09.238  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76c3a98 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb76c3368 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 13:26:09.268  1882  1882 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 13:26:09.278  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-17 13:26:09.278  1935  1935 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 13:26:09.278  1935  1935 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 13:26:09.278  1935  1935 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 13:26:09.278  1935  1935 I Adreno-EGL: Local Branch: 
03-17 13:26:09.278  1935  1935 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 13:26:09.278  1935  1935 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 13:26:09.278  1935  1935 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 13:26:09.278  3240  3319 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 13:26:09.298  3179  3453 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-17 13:26:09.298  3179  3453 I chromium: 
,03-17 13:26:09.298  3240  3319 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 13:26:09.308  1935  1935 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 13:26:09.318  1935  1935 I glCompressedTexImage2D: took 0.439114ms for 320*61440 texture 37809
,03-17 13:26:09.318  1018  1139 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:09.328  1935  1935 I draw setup: took 11.000261ms for 320*240 texture 37809
03-17 13:26:09.328  1935  1935 E GFX GPU raster: drawn
,03-17 13:26:09.328  1935  1935 I GFX GPU raster ASTC: took 43.625469ms for 320*240 texture 12
03-17 13:26:09.328  1935  1935 I GFX raster: took 43.715260ms for 320*240 texture 0
03-17 13:26:09.328  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76c3a18 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb76c3580 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 13:26:09.338  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 13:26:09.348  1935  1935 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 13:26:09.348  1935  1935 I glCompressedTexImage2D: took 0.313125ms for 480*122880 texture 37813
03-17 13:26:09.348  1935  1935 I draw setup: took 0.630990ms for 480*640 texture 37813
03-17 13:26:09.348  1935  1935 E GFX GPU raster: drawn
,03-17 13:26:09.358  1935  1935 I GFX GPU raster ASTC: took 15.500885ms for 480*640 texture 12
,03-17 13:26:09.358  1935  1935 I GFX raster: took 15.577136ms for 480*640 texture 0
03-17 13:26:09.358  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76c3580 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7904fd8 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 13:26:09.388  1303  3177 D ScoverManager: serviceVersion : 16908288
,03-17 13:26:09.388  3466  3466 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 13:26:09.388  3179  3511 D jxcore_app_log: JniHelper::setJavaVM(0xb7318448), pthread_self() = -1213898224
,03-17 13:26:09.398  3466  3466 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-17 13:26:09.398  3466  3466 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 13:26:09.398  3323  3323 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,03-17 13:26:09.408  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-17 13:26:09.408  1935  1935 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 13:26:09.408  3466  3466 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-17 13:26:09.408  1935  1935 I glCompressedTexImage2D: took 0.359532ms for 440*116864 texture 37809
03-17 13:26:09.408  1935  1935 I draw setup: took 0.742760ms for 440*330 texture 37809
03-17 13:26:09.408  1935  1935 E GFX GPU raster: drawn
,03-17 13:26:09.408  1935  1935 I GFX GPU raster ASTC: took 5.079063ms for 440*330 texture 12
03-17 13:26:09.408  1935  1935 I GFX raster: took 5.171771ms for 440*330 texture 0
03-17 13:26:09.408  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7904fb8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb7905388 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 13:26:09.418  3466  3466 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 13:26:09.418  3466  3466 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED,
,03-17 13:26:09.418  3179  3511 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 13:26:09.418  3179  3511 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 13:26:09.418  3179  3511 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
,03-17 13:26:09.418  3179  3511 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 13:26:09.418  3179  3511 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 13:26:09.418  3179  3511 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29963181 added. We now have 1 listener(s)
,03-17 13:26:09.418  3466  3466 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 13:26:09.428  1018  1139 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:09.428  1018  1031 I AudioService: getStreamVolume 3 index 0
,03-17 13:26:09.438  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 13:26:09.438  1935  1935 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 13:26:09.438  1935  1935 I glCompressedTexImage2D: took 0.480156ms for 480*163840 texture 37811
03-17 13:26:09.438  1935  1935 I draw setup: took 0.844740ms for 480*640 texture 37811
03-17 13:26:09.438  1935  1935 E GFX GPU raster: drawn
,03-17 13:26:09.448  1935  1935 I GFX GPU raster ASTC: took 6.065833ms for 480*640 texture 12
03-17 13:26:09.448  1935  1935 I GFX raster: took 6.148906ms for 480*640 texture 0
03-17 13:26:09.448  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7904df8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7917e20 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 13:26:09.448  3398  3462 W GAV2    : Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 13:26:09.458  3398  3462 W GAV2    : Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,03-17 13:26:09.458  3398  3490 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 13:26:09.478  3179  3511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,03-17 13:26:09.478  3179  3511 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,03-17 13:26:09.488  3179  3511 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,03-17 13:26:09.488  3179  3511 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 13:26:09.488  3179  3511 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 13:26:09.488  1882  1882 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 13:26:09.498  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 13:26:09.498  1935  1935 I GFX construct_block_size_descriptor_2d second part: took 2.418594ms for 0*0 texture 0
,03-17 13:26:09.508  3179  3511 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 13:26:09.508  3179  3511 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 13:26:09.508  3179  3511 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 13:26:09.508  3179  3511 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-17 13:26:09.508  3179  3511 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 13:26:09.508  3179  3511 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 13:26:09.508  3179  3511 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 13:26:09.508  3179  3511 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 13:26:09.508  3179  3511 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 13:26:09.508  3179  3511 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 13:26:09.508  3179  3511 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68ce414 added. We now have 1 listener(s)
,03-17 13:26:09.508  3179  3511 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 13:26:09.508  1935  1935 I GFX generate_partition_tables: took 7.680156ms for 0*0 texture 0
,03-17 13:26:09.508  1935  1935 I GFX raster: took 12.144844ms for 176*144 texture 0
03-17 13:26:09.508  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb78f4f08 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7917e40 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 13:26:09.518  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 13:26:09.518  1935  1935 I GFX construct_block_size_descriptor_2d second part: took 2.366614ms for 0*0 texture 0
,03-17 13:26:09.528  1935  1935 I GFX generate_partition_tables: took 6.298230ms for 0*0 texture 0,
03-17 13:26:09.528  1935  1935 I GFX raster: took 10.792188ms for 176*144 texture 0
03-17 13:26:09.528  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7905468 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7919b30 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 13:26:09.528  3280  3280 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 13:26:09.538  1935  1935 D ScoverManager: registerListener
,03-17 13:26:09.538  1018  1031 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 13:26:09.538  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.538  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.538  1018  1573 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 13:26:09.538  1018  1573 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@235756a2, pid : 1935, uid : 1001, type : 1
,03-17 13:26:09.538  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.538  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.538  3179  3511 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 13:26:09.538  3179  3511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-17 13:26:09.538  3179  3511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-17 13:26:09.548  3179  3511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 13:26:09.548  3179  3511 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 13:26:09.558  3527  3527 E Zygote  : MountEmulatedStorage(),
03-17 13:26:09.558  3527  3527 E Zygote  : v2
03-17 13:26:09.558  3527  3527 I libpersona: KNOX_SDCARD checking this for 10090
03-17 13:26:09.558  3527  3527 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:09.558  3527  3527 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:09.558  3527  3527 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:09.558  3527  3527 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 13:26:09.558  1018  1575 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3527 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,03-17 13:26:09.568  1018  1575 I ActivityManager: Killing 2389:com.sec.android.app.mt/1000 (adj 15): empty #31
03-17 13:26:09.578  3179  3511 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-17 13:26:09.578  3280  3280 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
03-17 13:26:09.578  1882  1882 I SamsungIME: KeybaordView init() : load resources
03-17 13:26:09.588  3179  3511 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
03-17 13:26:09.588  1935  1935 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
03-17 13:26:09.598  1018  1577 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.598  1018  1577 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:09.598  1018  1577 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
03-17 13:26:09.598  3280  3280 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 13:26:09.608  3179  3511 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 13:26:09.608  3179  3511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 13:26:09.608  3179  3511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 13:26:09.608  3179  3511 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 13:26:09.608  3179  3511 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 13:26:09.608  3179  3511 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 13:26:09.608  3179  3511 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 13:26:09.608  3179  3511 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 13:26:09.608  3179  3511 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 13:26:09.608  3179  3511 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 13:26:09.608  3179  3179 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 13:26:09.608   258   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 13:26:09.608   258   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:09.608  3161  3161 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 13:26:09.608   258   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 13:26:09.608   258   529 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 13:26:09.618  3179  3179 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 13:26:09.618  3161  3161 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 13:26:09.618   258   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 13:26:09.618   258   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:09.618  3161  3161 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 13:26:09.628  1018  1571 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:09.628  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.628  1018  2826 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:09.628  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:09.648  3527  3527 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:09.648  3527  3527 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:09.648  1018  1327 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:09.668  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2389/cgroup.procs: No such file or directory
,03-17 13:26:09.678  1882  1882 I SamsungIME: getCurrentKeyboard
03-17 13:26:09.678  1882  1882 I SamsungIME: getTextKeyboard
,03-17 13:26:09.688  3179  3179 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 13:26:09.688  1018  1327 I AudioService: getStreamVolume 3 index 0
,03-17 13:26:09.708  3398  3398 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-17 13:26:09.748  3323  3525 I System.out: Thread-439(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 13:26:09.758  3280  3280 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 13:26:09.758  1882  1882 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 13:26:09.758  3323  3525 I System.out: Thread-439(ApacheHTTPLog):isSBSettingEnabled false,
03-17 13:26:09.758  3323  3525 I System.out: Thread-439(ApacheHTTPLog):isShipBuild true,
03-17 13:26:09.758  3323  3525 I System.out: Thread-439(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-17 13:26:09.768  3323  3525 I System.out: Thread-439(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 13:26:09.768  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.768  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.768  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.768  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.788   280   955 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 13:26:09.788   280   955 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-17 13:26:09.798  3561  3561 E Zygote  : MountEmulatedStorage()
03-17 13:26:09.798  3561  3561 E Zygote  : v2
03-17 13:26:09.798  3561  3561 I libpersona: KNOX_SDCARD checking this for 10013
03-17 13:26:09.798  3561  3561 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:09.798  3561  3561 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:09.798  1018  1573 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3561 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,03-17 13:26:09.798  3561  3561 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:09.798  3561  3561 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 13:26:09.798  1018  1573 I ActivityManager: Killing 1608:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
03-17 13:26:09.798  3527  3527 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
03-17 13:26:09.808  3527  3527 D elm:15121: ELMEngine.ELMEngine( context ).
,03-17 13:26:09.808  3527  3527 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-17 13:26:09.818  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.818  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:09.818  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:09.818  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.818  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:09.818  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 13:26:09.818  3398  3398 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
03-17 13:26:09.818  3398  3398 I ContactLabelSupplier: get() : Execute runnable (UI thread)
,03-17 13:26:09.818  3527  3527 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 13:26:09.828  3398  3463 I ContactLabelSupplier: get() : OptedIn = false
,03-17 13:26:09.838  3561  3561 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:09.838  3561  3561 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:09.848  3527  3527 D elm:15121: ElmAgentService : onCreate()
,03-17 13:26:09.848  1435  1435 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 13:26:09.878  3527  3578 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 13:26:09.878  3527  3527 D elm:15121: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-17 13:26:09.878  3527  3527 D elm:15121: BootCompletedState : startBootCompleted() call
,03-17 13:26:09.898  3527  3527 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 13:26:09.898  1018  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:09.928  3527  3527 I elm:15121: Get License : 0
,03-17 13:26:09.928  3527  3527 D elm:15121: ElmAgentService : onDestroy().
,03-17 13:26:09.928  1018  1575 I ActivityManager: Killing 2613:com.android.calendar/u0a131 (adj 15): empty #31
,03-17 13:26:09.928  1018  1575 I ActivityManager: Killing 2677:com.android.keychain/1000 (adj 15): empty #31
,03-17 13:26:09.948  1018  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.948  1018  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:09.948  1018  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 13:26:09.968  2755  2843 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 13:26:09.978  1018  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:09.978  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.978  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.978  3561  3561 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 13:26:09.978  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.978  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.988  1303  3177 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 13:26:09.998  3591  3591 E Zygote  : MountEmulatedStorage()
03-17 13:26:09.998  3591  3591 E Zygote  : v2
03-17 13:26:09.998  3591  3591 I libpersona: KNOX_SDCARD checking this for 10055
03-17 13:26:09.998  3591  3591 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:09.998  3591  3591 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:09.998  3591  3591 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:09.998  1018  1571 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3591 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,03-17 13:26:09.998  3591  3591 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:09.998  1435  1435 V EmergencyMode: [EmergencyBase] setBootTime
,03-17 13:26:09.998  1435  1435 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 13:26:10.008  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:10.008  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:10.008  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 13:26:10.018  1303  3177 D Settings_Utils: isSupportVNFestival SM-A300FU XEO
,03-17 13:26:10.018  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:10.018  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:10.018  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:10.028  3591  3591 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.028  3591  3591 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.028  3561  3604 V OneTimeService: OneTimeService.onHandleIntent
,03-17 13:26:10.038  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.038  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.038  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.038  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.038  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_1608/cgroup.procs: No such file or directory
03-17 13:26:10.038  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2677/cgroup.procs: No such file or directory
03-17 13:26:10.038  1018  1043 W libprocessgroup: failed to open /acct/uid_10131/pid_2613/cgroup.procs: No such file or directory
,03-17 13:26:10.048  3610  3610 E Zygote  : MountEmulatedStorage()
,03-17 13:26:10.048  3610  3610 E Zygote  : v2
03-17 13:26:10.048  3610  3610 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:10.048  3610  3610 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:10.048  3610  3610 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:10.058  3610  3610 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 13:26:10.058  1018  1571 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3610 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:10.058  3610  3610 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:10.058  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:10.058  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:10.058  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:10.058  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 13:26:10.078  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.078  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:10.078  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:10.088  1303  3177 W ResourceType: Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,03-17 13:26:10.088  3610  3610 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.088  3610  3610 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.098  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.098  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:10.098  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:10.098  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.098  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:10.098  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:10.108  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.108  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:10.108  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:10.118  1303  3177 W ResourceType: Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,03-17 13:26:10.128  1018  1510 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.138  1018  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:10.138  1018  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:10.138  3161  3588 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
03-17 13:26:10.138  3161  3588 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 13:26:10.138  3161  3588 I System.out: Thread-445(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 13:26:10.138  3161  3588 I System.out: Thread-445(ApacheHTTPLog):isSBSettingEnabled false
,03-17 13:26:10.138  3161  3588 I System.out: Thread-445(ApacheHTTPLog):isShipBuild true
03-17 13:26:10.138  3161  3588 I System.out: Thread-445(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 13:26:10.138  3161  3588 I System.out: Thread-445(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 13:26:10.138  3161  3600 W MessageQueue: Handler (android.os.Handler) {11463fca} sending message to a Handler on a dead thread
03-17 13:26:10.138  3161  3600 W MessageQueue: java.lang.IllegalStateException: Handler (android.os.Handler) {11463fca} sending message to a Handler on a dead thread
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at ffw.a(SourceFile:327)
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at guw.a(SourceFile:120)
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at guf.c(SourceFile:26)
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at gui.run(SourceFile:297)
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:10.138  3161  3600 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:26:10.148  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.148  1018  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:10.148  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:10.158   280   955 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 13:26:10.158   280   955 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,03-17 13:26:10.168  1018  1575 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.168  1018  1575 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:10.168  1018  1575 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:10.178  3610  3610 I CameraApp: CameraApp.onCreate()... mFeature : null
03-17 13:26:10.178  3610  3610 I testFeature: Feature.Feature(context)
03-17 13:26:10.178  3610  3610 I testFeature: Feature.readInternalDefaultXml()
03-17 13:26:10.178  3610  3610 I testFeature: ResetFeatureValue
,03-17 13:26:10.178  3610  3610 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 13:26:10.178  3610  3610 I CameraApp: CameraApp.getAppFeature()...
,03-17 13:26:10.178  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.188  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:10.188  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:10.188  1538  1538 I Hs20UtilService: Starting #4
,03-17 13:26:10.188  1538  1606 I Hs20UtilService: Message received 5003
,03-17 13:26:10.188  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.188  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.188  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.188  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.198  3634  3634 E Zygote  : MountEmulatedStorage(),
03-17 13:26:10.198  3634  3634 E Zygote  : v2
,03-17 13:26:10.198  3634  3634 I libpersona: KNOX_SDCARD checking this for 10095
03-17 13:26:10.198  3634  3634 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:10.198  1018  1569 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3634 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
03-17 13:26:10.208  3634  3634 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:10.208  3634  3634 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:10.208  3634  3634 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:10.228  1924  1924 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:10.248  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.248  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.248  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.248  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.248  1018  2865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:10.248  3634  3634 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.248  3634  3634 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.258  3649  3649 E Zygote  : MountEmulatedStorage()
03-17 13:26:10.258  3649  3649 E Zygote  : v2
03-17 13:26:10.258  3649  3649 I libpersona: KNOX_SDCARD checking this for 10018
03-17 13:26:10.258  3649  3649 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:10.258  3649  3649 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:10.258  3649  3649 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:10.258  1018  1569 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3649 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
03-17 13:26:10.268  3649  3649 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:10.268  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.268  1018  2826 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:10.268  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-17 13:26:10.278  2629  3178 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3178)  
,03-17 13:26:10.298  3649  3649 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.298  3649  3649 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.378  1018  1241 I ActivityManager: Killing 2721:com.android.chrome/u0a77 (adj 15): empty #31
,03-17 13:26:10.378  1018  1241 I ActivityManager: Killing 2769:com.android.email/u0a141 (adj 15): empty #32
,03-17 13:26:10.388  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 13:26:10.388  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:10.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:10.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:10.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:10.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:10.398  3591  3591 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 13:26:10.418  1018  1498 I ActivityManager: Killing 1640:com.android.defcontainer/u0a3 (adj 15): empty #31
,03-17 13:26:10.428  1018  1139 I art     : Explicit concurrent mark sweep GC freed 22715(1267KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 22MB/33MB, paused 7.381ms total 217.178ms
,03-17 13:26:10.428  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:10.428  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:10.428  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-17 13:26:10.438  1924  1924 D SecUISvc: Service started flags 0 startId 1
,03-17 13:26:10.438  1924  3664 D SecUISvc: Thread created.
,03-17 13:26:10.458  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.458  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.458  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.458  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.468   290   290 E SMD     : DCD OFF,
,03-17 13:26:10.488  3667  3667 E Zygote  : MountEmulatedStorage()
03-17 13:26:10.488  3667  3667 I libpersona: KNOX_SDCARD checking this for 10026
03-17 13:26:10.488  3667  3667 E Zygote  : v2
03-17 13:26:10.488  3667  3667 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:10.488  3667  3667 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 13:26:10.498  1018  1030 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3667 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:10.498  3667  3667 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:10.498  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:10.498  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:10.498  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:10.498  3667  3667 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:10.518  1018  1571 I ActivityManager: Killing 2533:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,03-17 13:26:10.538  3425  3425 I RlzPingService: Setting next ping for 1458822370549
,03-17 13:26:10.538  3667  3667 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.538  3667  3667 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.548  3591  3591 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 13:26:10.548  3591  3591 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 13:26:10.548  3591  3591 D UserAnalysis: Create SecureDbHelper
,03-17 13:26:10.558  3179  3543 W jxcore-log: Initializing JXcore engine
03-17 13:26:10.558  3179  3543 W jxcore-log: JXcore engine is ready
,03-17 13:26:10.568  1018  1043 W libprocessgroup: failed to open /acct/uid_10077/pid_2721/cgroup.procs: No such file or directory
03-17 13:26:10.568  1018  1043 W libprocessgroup: failed to open /acct/uid_10141/pid_2769/cgroup.procs: No such file or directory
,03-17 13:26:10.578  1018  1575 I ActivityManager: Killing 2878:com.mobeam.barcodeService/1000 (adj 15): empty #31
,03-17 13:26:10.588  3649  3649 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 13:26:10 GMT+01:00 2016
,03-17 13:26:10.588  1018  1577 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.588  1018  1577 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:10.588  1018  1577 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 13:26:10.608  3649  3649 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-17 13:26:10.608  3634  3634 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,03-17 13:26:10.618  3591  3591 D IntelligenceServiceApplication: onCreate()
,03-17 13:26:10.618  3591  3591 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 13:26:10.618  1018  1043 W libprocessgroup: failed to open /acct/uid_10003/pid_1640/cgroup.procs: No such file or directory
,03-17 13:26:10.628  1018  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.628  1018  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.628  1018  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.628  1018  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.628  3649  3649 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-17 13:26:10.628  3591  3591 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 13:26:10.628  3649  3649 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 13:26:10.638  1886  1886 E audit   : type=1400 msg=audit(1458217570.638:205): avc:  denied  { ioctl } for  pid=3543 comm="Thread-418" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-17 13:26:10.648  1886  1886 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:10.648  1886  1886 E audit   : type=1300 msg=audit(1458217570.638:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=92e7f8f8 items=0 ppid=305 ppcomm=main pid=3543 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-418" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 13:26:10.648  1886  1886 E audit   : type=1320 msg=audit(1458217570.638:205): 
,03-17 13:26:10.648  1018  1577 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3684 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a,
,03-17 13:26:10.658  3684  3684 E Zygote  : MountEmulatedStorage(),
03-17 13:26:10.658  3684  3684 I libpersona: KNOX_SDCARD checking this for 10020
03-17 13:26:10.658  3684  3684 E Zygote  : v2
03-17 13:26:10.658  3684  3684 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:10.658  3684  3684 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:10.658  3179  3543 W jxcore-log: Starting JXcore engine,
,03-17 13:26:10.658  3684  3684 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:10.658  3684  3684 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:10.658  1018  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.658  1018  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.658  1018  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.658  1018  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.658  3649  3649 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 13:26:10.668  3649  3683 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 13:26:10.678  3649  3683 I KLMS-2.5.123: : KLMSIntentService(): BOOT_COMPLETED
,03-17 13:26:10.678   305   305 I art     : Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 622us total 33.610ms
,03-17 13:26:10.688  3634  3634 E SQLiteLog: (284) automatic index on titles(filter_id)
,03-17 13:26:10.688  3684  3684 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:10.688  3684  3684 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:10.688  1018  1043 W libprocessgroup: failed to open /acct/uid_10039/pid_2533/cgroup.procs: No such file or directory
,03-17 13:26:10.698   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 16.720ms
,03-17 13:26:10.718   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.827ms
,03-17 13:26:10.718  1018  1489 V VibratorService: hasVibrator - useVibetonz: true
,03-17 13:26:10.728  3700  3700 E Zygote  : MountEmulatedStorage()
03-17 13:26:10.728  3700  3700 I libpersona: KNOX_SDCARD checking this for 10056
03-17 13:26:10.728  3700  3700 E Zygote  : v2
03-17 13:26:10.728  3700  3700 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:10.728  3700  3700 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:10.738  3700  3700 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:10.738  1018  1577 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3700 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 13:26:10.738  3700  3700 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:10.748  3634  3634 I FilterProviderReceiver: onReceive in FilterProviderReceiver
03-17 13:26:10.748  3634  3634 I FilterProviderReceiver: onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,03-17 13:26:10.748  3591  3591 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 13:26:10.758  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.758  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.758  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.758  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.778  3711  3711 E Zygote  : MountEmulatedStorage(),
03-17 13:26:10.778  3711  3711 I libpersona: KNOX_SDCARD checking this for 10098
03-17 13:26:10.778  3711  3711 E Zygote  : v2
03-17 13:26:10.778  3711  3711 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:10.778  3711  3711 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:10.778  3711  3711 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 13:26:10.778  3161  3588 I System.out: Thread-445 calls detatch()
,03-17 13:26:10.788  1018  1498 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3711 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,03-17 13:26:10.788  1018  1498 I ActivityManager: Killing 2903:flipboard.boxer.app/u0a97 (adj 15): empty #31
,03-17 13:26:10.788  3711  3711 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:10.788  3179  3543 W jxcore-log: Platform android
03-17 13:26:10.788  3179  3543 W jxcore-log: 
,03-17 13:26:10.788  3179  3543 W jxcore-log: Process ARCH arm
03-17 13:26:10.788  3179  3543 W jxcore-log: 
,03-17 13:26:10.788  1018  1241 I ActivityManager: Killing 2935:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 13:26:10.788  3700  3700 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.788  3700  3700 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.828  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2878/cgroup.procs: No such file or directory
,03-17 13:26:10.828  3711  3711 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.828  3711  3711 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.878  3649  3649 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-17 13:26:10.898  3591  3591 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 13:26:10.898  3591  3591 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 13:26:10.918  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.918  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.918  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.918  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.938  3739  3739 E Zygote  : MountEmulatedStorage()
03-17 13:26:10.938  3739  3739 E Zygote  : v2
03-17 13:26:10.938  3739  3739 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:10.938  3739  3739 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:10.938  3739  3739 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:10.948  1018  2825 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3739 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 13:26:10.948  3739  3739 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:10.948  3739  3739 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:10.948  3711  3711 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 13:26:10.978  3739  3739 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.978  3739  3739 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.978  3711  3711 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-17 13:26:10.988  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.988  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.988  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.988  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.998  3756  3756 E Zygote  : MountEmulatedStorage()
03-17 13:26:10.998  3756  3756 E Zygote  : v2
03-17 13:26:10.998  3756  3756 I libpersona: KNOX_SDCARD checking this for 10099
03-17 13:26:10.998  3756  3756 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:10.998  3756  3756 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:11.008  3756  3756 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 13:26:11.008  1018  1489 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3756 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:11.008  3756  3756 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:11.008  1018  1489 I ActivityManager: Killing 2972:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,03-17 13:26:11.018  1303  3177 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 13:26:11.028  3756  3756 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.028  3756  3756 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.038  3667  3667 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 13:26:11.048  3739  3739 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-17 13:26:11.048  1018  1575 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 13:26:11.048  1018  1575 D SecContentProvider2: mCursor = null
,03-17 13:26:11.048  1018  1043 W libprocessgroup: failed to open /acct/uid_1101/pid_2935/cgroup.procs: No such file or directory
,03-17 13:26:11.048  1018  1327 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 13:26:11.048  1018  1327 D SecContentProvider2: mCursor = null
,03-17 13:26:11.048  3739  3739 V MTPRx   : sealedState: false
03-17 13:26:11.048  3739  3739 V MTPRx   : sealedUsbMassStorageState: false
,03-17 13:26:11.058  1018  1573 D SettingsProvider: name = mtp_usb_connection_status
,03-17 13:26:11.058  1018  1043 W libprocessgroup: failed to open /acct/uid_10097/pid_2903/cgroup.procs: No such file or directory
,03-17 13:26:11.058  3179  3543 I jxcore-log: JXcore Cordova bridge is ready!
03-17 13:26:11.058  3179  3543 I jxcore-log: 
,03-17 13:26:11.058  3179  3543 W jxcore-log: JXcore engine is started
03-17 13:26:11.058  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 13:26:11.058  1018  1327 D SettingsProvider: name = media_player_mode
,03-17 13:26:11.068  3179  3511 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 13:26:11.068  1018  1043 W libprocessgroup: failed to open /acct/uid_10153/pid_2972/cgroup.procs: No such file or directory
,03-17 13:26:11.078  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.078  1018  1498 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 13:26:11.088  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.098  3179  3543 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 13:26:11.098  3179  3543 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 13:26:11.108  1018  1510 D SettingsProvider: name = mtp_running_status
,03-17 13:26:11.108  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.118  3179  3179 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-17 13:26:11.118  1018  1575 D FocusedStackFrame: Set to : 0
,03-17 13:26:11.118  1018  1575 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 13:26:11.118  1018  1575 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,03-17 13:26:11.118  1018  1575 D InputDispatcher: Focused application set to: xxxx
,03-17 13:26:11.118  1018  1575 D InputDispatcher: Focus left window: 3179
,03-17 13:26:11.128  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 13:26:11.128  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:26:11.128   259  1040 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (126 us)
,03-17 13:26:11.158  3179  3511 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 40ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 13:26:11.158  1018  1569 D SettingsProvider: name = media_mount_count
,03-17 13:26:11.158  1018  2826 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-17 13:26:11.168  1018  2826 W ActivityManager: mDVFSHelper.acquire()
,03-17 13:26:11.168  1018  2826 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:11.168  1018  2826 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:11.168  1018  2826 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 13:26:11.168  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.178  1018  1498 D SettingsProvider: name = mtp_sync_alive
,03-17 13:26:11.178  3323  3525 I System.out: pool-10-thread-1 calls detatch()
,03-17 13:26:11.188  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.188  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-17 13:26:11.188  1018  1018 D SensorService: [SO] activate (ident=0xb7b22538, enabled=0)
03-17 13:26:11.188  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 13:26:11.188  1499  1499 D Launcher: onRestart, Launcher: 947942571
,03-17 13:26:11.198  1499  1499 D Launcher: onStart, Launcher: 947942571
03-17 13:26:11.198  1499  1499 D Launcher.HomeView: onStart
,03-17 13:26:11.198  1499  1499 D Launcher: onResume, Launcher: 947942571
,03-17 13:26:11.198  3700  3700 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.7.KK_APP
,03-17 13:26:11.198  1018  1139 D SettingsProvider: name = kids_home_mode
03-17 13:26:11.198  1018  1139 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:11.198  1018  1139 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:11.198  1018  1139 D SettingsProvider: selectionArgs: false
03-17 13:26:11.198  1018  1139 D SettingsProvider: selectionArgs: 10006
03-17 13:26:11.198  1018  1139 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:11.198  1018  1139 D SettingsProvider: ret = -1
,03-17 13:26:11.198  1499  1499 D Launcher.HomeView: onResume
,03-17 13:26:11.208  1018  1573 D SettingsProvider: name = sdcard_launch
,03-17 13:26:11.208  1018  1018 D SensorManager: unregisterListener ::   
,03-17 13:26:11.208  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-17 13:26:11.208  1018  1018 D SensorService: [SO] changed settle time [0]
,03-17 13:26:11.208  1018  1018 D SensorService: [SO] setDelay [200000000]
03-17 13:26:11.208  1018  1018 D SensorService: [SO] activate (ident=0xb7b22538, enabled=1)
03-17 13:26:11.208  1018  1018 D SensorService: [SO] AR_init
03-17 13:26:11.208  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 13:26:11.208  1499  1499 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 13:26:11.208  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.208  1499  1499 D MenuAppsGridFragment: onResume
,03-17 13:26:11.208  1018  1489 D ActivityManager: handle home activity for 0
03-17 13:26:11.208  1018  1489 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,03-17 13:26:11.208  1018  1489 D KnoxTimeoutHandler: post home show event for user 0
03-17 13:26:11.208  1018  1489 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 13:26:11.208  1018  1489 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 13:26:11.208  1018  1489 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 13:26:11.208  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
03-17 13:26:11.208  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 13:26:11.218  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 13:26:11.218  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 13:26:11.218  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 13:26:11.218   259   259 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=4, Mauncher
,03-17 13:26:11.218  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.218  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.218  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.218  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.218  1018  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 13:26:11.228  1018  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 13:26:11.228  3785  3785 E Zygote  : MountEmulatedStorage()
,03-17 13:26:11.228  3785  3785 E Zygote  : v2
03-17 13:26:11.228  3785  3785 I libpersona: KNOX_SDCARD checking this for 10058
03-17 13:26:11.228  3785  3785 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.228  3785  3785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 13:26:11.238  1018  1510 D InputDispatcher: Focus entered window: 1499
,03-17 13:26:11.238  1499  1499 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 13:26:11.238  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:11.238  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:26:11.238  1018  1569 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3785 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:11.238  3785  3785 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:11.238  1018  1569 I ActivityManager: Killing 3000:com.sec.usbsettings/1000 (adj 15): empty #31
03-17 13:26:11.238  3785  3785 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:11.238  2656  2713 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 13:26:11.258  1018  1498 D SettingsProvider: name = boot_time_connected
,03-17 13:26:11.268  1499  1499 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 13:26:11.268  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.278  1018  1241 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 13:26:11.278  1174  1174 I StatusBar: Icon Only
03-17 13:26:11.278  1174  1174 D PanelView: There is/are notification(s) 
,03-17 13:26:11.288  1018  3796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:11.288  3179  3179 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 13:26:11.288  1882  1882 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 13:26:11.298  3785  3785 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.298  3785  3785 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.308  1499  1499 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@13dc13c7 time:41083
,03-17 13:26:11.308  1018  1050 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:11.318  1018  1510 D SettingsProvider: name = mtp_open_session
,03-17 13:26:11.328  1018  1050 I ActivityManager: Displayed Component not be shown by security: +159ms
,03-17 13:26:11.338  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.348  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3000/cgroup.procs: No such file or directory
,03-17 13:26:11.348  3667  3667 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-17 13:26:11.378  3667  3667 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 13:26:11.378  3667  3667 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 13:26:11.388  3444  3444 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 13:26:11.388  3444  3444 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 13:26:11.388  3444  3444 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 13:26:11.388  3444  3444 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-17 13:26:11.388  3444  3444 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 13:26:11.388  3444  3444 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 13:26:11.408  1018  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 13:26:11.418  3444  3444 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 13:26:11.428  3785  3785 I ExternalOEMControlProvider: onCreate
,03-17 13:26:11.438  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.438  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.438  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.438  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.448  3444  3444 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 13:26:11.458  1018  1498 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3813 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:11.458  3813  3813 E Zygote  : MountEmulatedStorage()
03-17 13:26:11.458  3813  3813 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:11.458  3813  3813 E Zygote  : v2
03-17 13:26:11.458  3813  3813 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.458  3813  3813 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:11.458  3813  3813 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:11.458  3813  3813 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:11.468  1018  2825 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-17 13:26:11.468  1018  2825 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:11.468  1018  2825 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:11.468  1018  2825 D SettingsProvider: selectionArgs: false
03-17 13:26:11.468  1018  2825 D SettingsProvider: selectionArgs: 10058
03-17 13:26:11.468  1018  2825 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:11.468  1018  2825 D SettingsProvider: ret = -1
,03-17 13:26:11.478  3444  3444 I ReactiveServiceManager: Supported : 1
,03-17 13:26:11.478  1018  1573 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-17 13:26:11.478  1018  1573 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 13:26:11.488  1018  2825 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-17 13:26:11.488  1018  1571 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-17 13:26:11.488  1018  1571 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:11.488  1018  1571 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:11.488  1018  1571 D SettingsProvider: selectionArgs: false
03-17 13:26:11.488  1018  1571 D SettingsProvider: selectionArgs: 10058
03-17 13:26:11.488  1018  1571 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:11.488  1018  1571 D SettingsProvider: ret = -1
,03-17 13:26:11.498  1303  3177 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 13:26:11.498  1018  2826 I ActivityManager: Killing 2292:flipboard.app/u0a96 (adj 15): empty #31
,03-17 13:26:11.498  1303  3177 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 13:26:11.498  3813  3813 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.498  1018  1571 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
03-17 13:26:11.498  3813  3813 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:11.508  1018  1577 I ActivityManager: Killing 2420:com.android.mms/u0a41 (adj 15): empty #31
,03-17 13:26:11.508  3667  3780 D Volley  : [506] g.b: Cache cleared.
,03-17 13:26:11.518  3667  3772 D Volley  : [500] g.b: Cache cleared.
03-17 13:26:11.518  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.518  1303  3177 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 13:26:11.518  1018  1573 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 13:26:11.528  3667  3829 D Ads     : Skipping gmscore version check
,03-17 13:26:11.528  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.528  1018  1573 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 13:26:11.528  1018  1573 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-17 13:26:11.528  1018  1573 E terrier : handleString: Failed to handle string(-4)
03-17 13:26:11.528  1018  1573 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-17 13:26:11.538  3444  3444 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 13:26:11.538  3444  3444 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 13:26:11.538  1018  1575 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1174 (0x0)
,03-17 13:26:11.538  3444  3444 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 13:26:11.538  3444  3444 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 13:26:11.538  3444  3444 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 13:26:11.538  3444  3444 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 13:26:11.538  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:11.538  1018  2826 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:11.538  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 13:26:11.538  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.538  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.538  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.538  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.548  3831  3831 E Zygote  : MountEmulatedStorage()
,03-17 13:26:11.558  3831  3831 E Zygote  : v2
03-17 13:26:11.558  3831  3831 I libpersona: KNOX_SDCARD checking this for 10028
03-17 13:26:11.558  3831  3831 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.558  3831  3831 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:11.558  1018  2825 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3831 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a,
03-17 13:26:11.558  3831  3831 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:11.558  1018  1030 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 13:26:11.558  3831  3831 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 13:26:11.558  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:11.558  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:11.558  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:11.568  1018  1575 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:11.568  1018  1575 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:11.568  1018  1575 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
03-17 13:26:11.568  3667  3667 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
03-17 13:26:11.568  3667  3667 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-17 13:26:11.568  3667  3667 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-17 13:26:11.598  3831  3831 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.598  3831  3831 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.598  3667  3667 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
,03-17 13:26:11.598  1018  1327 D CountryDetector: No listener is left
,03-17 13:26:11.608  1018  1041 D SensorService: [SO] currT = 41381116000, prevT = 40911080000, diff = 470036000, [-0.479 0.211 9.902]
03-17 13:26:11.608  1018  1041 D SensorService: [SO] -0.479 0.211 9.902
03-17 13:26:11.608  1018  1041 D SensorService: [SO] [100 -> 255]
,03-17 13:26:11.608  1018  1043 W libprocessgroup: failed to open /acct/uid_10096/pid_2292/cgroup.procs: No such file or directory
,03-17 13:26:11.608  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:11.608  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:11.608  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 13:26:11.608  1018  1043 W libprocessgroup: failed to open /acct/uid_10041/pid_2420/cgroup.procs: No such file or directory
,03-17 13:26:11.638  3813  3813 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 13:26:11.658  1018  1044 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7,
03-17 13:26:11.658  1018  1044 W ActivityManager: mDVFSHelper.release()
,03-17 13:26:11.658  1018  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:11.738  3813  3813 I ServiceMode: received = ACTION_BOOT_COMPLETED
,03-17 13:26:11.738  3813  3813 I ServiceMode: setReferenceIsDumpState : 0
,03-17 13:26:11.748  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.748  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.748  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.748  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.758  3852  3852 E Zygote  : MountEmulatedStorage()
03-17 13:26:11.758  3852  3852 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:11.758  3852  3852 E Zygote  : v2
03-17 13:26:11.758  3852  3852 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.758  3852  3852 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:11.758  1018  1031 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3852 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:11.768  1018  1031 I ActivityManager: Killing 3042:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,03-17 13:26:11.768  1018  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f7a5dd0 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:41541
,03-17 13:26:11.768  3852  3852 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:11.768   259   437 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-17 13:26:11.768  3852  3852 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:11.768   259  1040 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 13:26:11.778  1018  1044 I ActivityManager: Killing 2916:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,03-17 13:26:11.788  3852  3852 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.798  3852  3852 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.858  3852  3852 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-17 13:26:11.858  3852  3852 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:11.868  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:11.868  1018  2826 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:11.868  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 13:26:11.868  3852  3852 D NPS_WSSNPS: [] Service onCreate!!
,03-17 13:26:11.868  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.868  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.868  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.868  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.878  3872  3872 E Zygote  : MountEmulatedStorage(),
03-17 13:26:11.878  3872  3872 E Zygote  : v2
03-17 13:26:11.878  3872  3872 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:11.878  3872  3872 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.878  3872  3872 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:11.888  1018  1489 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3872 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 13:26:11.888  3872  3872 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:11.888  3756  3756 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-17 13:26:11.888  3852  3878 D NPS_WSSNPS: [] NpsServiceTask Start
03-17 13:26:11.888  3872  3872 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:11.898  1018  1043 W libprocessgroup: failed to open /acct/uid_10043/pid_3042/cgroup.procs: No such file or directory
03-17 13:26:11.898  1018  1043 W libprocessgroup: failed to open /acct/uid_10081/pid_2916/cgroup.procs: No such file or directory
,03-17 13:26:11.908  3756  3867 I Gmail   : getAccountsCursor
,03-17 13:26:11.918  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:11.918  1018  2825 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:11.918  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 13:26:11.918  3872  3872 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.918  3872  3872 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.928  3852  3852 D NPS_WSSNPS: [50.150321] smlDBHelper
,03-17 13:26:11.928  2135  3841 D FileApkUtils: Optimizing (staging complete)
,03-17 13:26:11.938  2135  3841 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
,03-17 13:26:11.938  2135  3841 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-17 13:26:11.938  3179  3179 W ScreenOrientationListener: Removing an inexistent observer!
,03-17 13:26:11.948  3667  3667 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-17 13:26:11.958  3831  3831 I System.out: Inside onCreate() of WakeupTriggerProvide
,03-17 13:26:11.958  3831  3831 I System.out: Inside WakeupProvider
,03-17 13:26:11.958  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:11.998  1018  1577 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:11.998  1018  1577 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:11.998  1018  1577 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 13:26:11.998  3179  3179 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@181aab2 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:26:11.998  3179  3179 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@181aab2 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:11.998  3179  3179 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:26:12.008  3179  3179 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@32f364bd that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:26:12.008  3179  3179 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@32f364bd that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:12.008  3179  3179 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:26:12.008  2135  3841 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
03-17 13:26:12.008  1018  1571 D SettingsProvider: name = access_control_enabled
,03-17 13:26:12.008  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.008  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.008  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.008  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.028  3901  3901 E Zygote  : MountEmulatedStorage()
,03-17 13:26:12.028  3901  3901 E Zygote  : v2
,03-17 13:26:12.028  3901  3901 I libpersona: KNOX_SDCARD checking this for 10065
03-17 13:26:12.028  3901  3901 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:12.028  3852  3852 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-17 13:26:12.028  3901  3901 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:12.028  3901  3901 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 13:26:12.028  1018  1569 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3901 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 13:26:12.038  1018  1569 I ActivityManager: Killing 3080:com.sec.dsm.system/1000 (adj 15): empty #31
,03-17 13:26:12.038  3901  3901 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:12.038  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.038  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:12.038  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 13:26:12.048  1018  2826 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 13:26:12.048  3852  3903 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-17 13:26:12.048  3852  3903 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
,03-17 13:26:12.048  3852  3903 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-17 13:26:12.048  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.048  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:12.048  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 13:26:12.058  3852  3852 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-17 13:26:12.068  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
03-17 13:26:12.068  3852  3852 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-17 13:26:12.068  3852  3852 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
03-17 13:26:12.068  1018  1498 I ActivityManager: Killing 1629:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
03-17 13:26:12.068  3852  3852 I NPS_WSSNPS: [50.150321] smlBREmailDelete
03-17 13:26:12.068  3852  3852 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete,
03-17 13:26:12.068  3852  3852 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete,
,03-17 13:26:12.068  3852  3852 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
,03-17 13:26:12.078  3852  3852 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
,03-17 13:26:12.078  3852  3852 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
,03-17 13:26:12.078  3901  3901 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.078  3901  3901 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.078  3852  3852 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-17 13:26:12.088  3852  3852 D NPS_WSSNPS: [50.150321] dsServerSocket close
,03-17 13:26:12.088  3240  3318 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:12.088  1018  1139 I ActivityManager: Killing 3114:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-17 13:26:12.098  1018  1575 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 13:26:12.098  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.098  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:12.098  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:12.098  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:12.098  3756  3917 E Gmail   : Error finding the version of the Email provider.....
03-17 13:26:12.098  3756  3917 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 13:26:12.098  3756  3917 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 13:26:12.098  3756  3917 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
03-17 13:26:12.098  3756  3917 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-17 13:26:12.098  3756  3917 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 13:26:12.098  3756  3917 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:12.098  3756  3917 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:12.098  3756  3917 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 13:26:12.098  3756  3917 W EmailMigration: We do not support migrating this version of the Email provider.
,03-17 13:26:12.108  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:12.108  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:12.108  1018  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.108  1018  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:12.108  1018  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 13:26:12.118  1018  1327 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 13:26:12.128  1018  1327 I ActivityManager: Killing 3138:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-17 13:26:12.138  3831  3831 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,03-17 13:26:12.148  3240  3318 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 13:26:12.148  3240  3318 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
03-17 13:26:12.148  3901  3901 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 13:26:12.148  3240  3318 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 13:26:12.148  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3080/cgroup.procs: No such file or directory
03-17 13:26:12.148  3240  3318 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 13:26:12.148  3240  3318 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 13:26:12.158  3240  3318 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 13:26:12.158  3240  3318 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 13:26:12.158  3756  3920 I Gmail   : Observing account changes for notifications
,03-17 13:26:12.168  1018  1575 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.168  1018  1575 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:12.168  1018  1575 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:12.168  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.168  1018  2826 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:12.168  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 13:26:12.178  3756  3867 I Gmail   : getAccountsCursor
,03-17 13:26:12.178  1018  1043 W libprocessgroup: failed to open /acct/uid_10068/pid_1629/cgroup.procs: No such file or directory
03-17 13:26:12.178  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3114/cgroup.procs: No such file or directory
,03-17 13:26:12.178  2629  2629 D FactoryTestApp: [DummyFtClient$onDestroy](2629) Destroy DummyFtClient service
,03-17 13:26:12.178  1018  1571 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.178  1018  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:12.178  1018  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:12.188  2629  2629 D FactoryTestApp: [Support$Values.getString](2629) id=MODEL_COMMUNICATION_MODE, value=gsm
,03-17 13:26:12.188  2629  2629 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2629) mConnectionMode = gsm
03-17 13:26:12.188  2629  2629 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2629) RUNNING_FTCLIENT : false
03-17 13:26:12.188  2629  2629 D FactoryTestApp: [DummyFtClient$onDestroy](2629) kill process
03-17 13:26:12.188  2629  2629 I Process : Sending signal. PID: 2629 SIG: 9
,03-17 13:26:12.188  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3138/cgroup.procs: No such file or directory
,03-17 13:26:12.198  1018  1573 I ActivityManager: Process com.sec.factory (pid 2629)(adj 0) has died(43,641)
,03-17 13:26:12.208  1018  1510 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 13:26:12.208  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.208  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:12.208  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-17 13:26:12.218  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.218  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.218  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.218  1018  1498 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.228  1018  1498 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3925 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-17 13:26:12.238  3925  3925 E Zygote  : MountEmulatedStorage()
03-17 13:26:12.238  3925  3925 E Zygote  : v2
03-17 13:26:12.238  3925  3925 I libpersona: KNOX_SDCARD checking this for 10102
03-17 13:26:12.238  3925  3925 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:12.238  3925  3925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:12.238  1018  1510 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 13:26:12.238  3925  3925 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:12.238  3925  3925 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:12.248  3756  3756 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@32f364bd that was originally bound here
03-17 13:26:12.248  3756  3756 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@32f364bd that was originally bound here
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at com.android.emailcommon.service.H.a(SourceFile:181)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at com.android.emailcommon.service.H.mb(SourceFile:224)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at com.android.email.service.n.j(SourceFile:160)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:171)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at com.android.email.provider.b.F(SourceFile:115)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:12.248  3756  3756 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:26:12.248  3831  3831 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
03-17 13:26:12.248  1018  1573 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@2af671a0
,03-17 13:26:12.258  1679  3924 I GoogleHttpClient: GMS http client unavailable, use old client
,03-17 13:26:12.258  3925  3925 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.258  3925  3925 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:12.258  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:12.268   305   305 I art     : Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 32.969ms
,03-17 13:26:12.278  3925  3925 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 13:26:12.288   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.953ms
,03-17 13:26:12.298   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 17.589ms
,03-17 13:26:12.338  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.338  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:12.338  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:12.338  1900  1900 D ChimeraCfgMgr: Reading stored module config
,03-17 13:26:12.368  3831  3831 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 13:26:12.368  3831  3831 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 13:26:12.388  3831  3831 D DialogFlow: initQueue()
,03-17 13:26:12.398  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:12.398  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:12.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:12.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:12.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:12.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:12.408  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.408  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.408  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.408  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.418  3948  3948 E Zygote  : MountEmulatedStorage()
,03-17 13:26:12.418  3948  3948 E Zygote  : v2
03-17 13:26:12.418  3948  3948 I libpersona: KNOX_SDCARD checking this for 10029
03-17 13:26:12.418  3948  3948 I libpersona: KNOX_SDCARD not a persona,
,03-17 13:26:12.428  3948  3948 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:12.428  1018  1031 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3948 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
03-17 13:26:12.428  3948  3948 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:12.428  3948  3948 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:12.448  3948  3948 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.448  3948  3948 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.648  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.648  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.648  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.648  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.658  3974  3974 E Zygote  : MountEmulatedStorage(),
03-17 13:26:12.658  3974  3974 E Zygote  : v2
03-17 13:26:12.658  3974  3974 I libpersona: KNOX_SDCARD checking this for 10030
03-17 13:26:12.658  3974  3974 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:12.658  3974  3974 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 13:26:12.668  3974  3974 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:12.668  3974  3974 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-17 13:26:12.668  1018  1327 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3974 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 13:26:12.678  3974  3974 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.688  3974  3974 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.688  3925  3991 I Babel   : MmsConfig: mnc/mcc: 0/0
03-17 13:26:12.688  3925  3991 I Babel   : MmsConfig.loadMmsSettings
03-17 13:26:12.688  3925  3991 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-17 13:26:12.688  3925  3991 I Babel   : MmsConfig.loadFromDatabase
,03-17 13:26:12.738  3756  3921 E SQLiteLog: (283) recovered 95 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 13:26:12.758  1900  1900 D WearableService: callingUid 10011, callindPid: 1900
,03-17 13:26:12.768  1900  1900 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 13:26:12.818  3925  3991 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,03-17 13:26:12.818  3925  3991 I Babel   : MmsConfig.loadFromResources
,03-17 13:26:12.818  3925  3991 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,03-17 13:26:12.818  3925  3991 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-17 13:26:12.848  3925  3983 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 13:26:12.868  3925  3983 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 13:26:12.868  3925  3983 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 13:26:12.878  2135  2135 W InstanceID/Rpc: Found 10011
,03-17 13:26:12.878  3925  3983 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 13:26:12.878  3925  3983 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 13:26:12.888  3925  3983 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-17 13:26:12.888  3925  3983 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 13:26:12.898  3925  3983 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 13:26:12.898  3925  3983 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 13:26:12.908  3925  3983 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 13:26:12.928  3756  3921 E File    : fail readDirectory() errno=2,
,03-17 13:26:12.938  3925  3983 W VideoCapabilities: Unsupported mime video/x-ms-wmv,
,03-17 13:26:12.948  3756  3944 I Gmail   : notifyAccountChanged
,03-17 13:26:12.978  3925  3983 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-17 13:26:12.988  1018  1489 I art     : Explicit concurrent mark sweep GC freed 25851(1299KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 2.649ms total 184.825ms
,03-17 13:26:12.988  3756  3944 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-17 13:26:12.988  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.988  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:12.988  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 13:26:12.988  3925  3983 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 13:26:12.988  3925  3983 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 13:26:12.988  3756  3899 I Gmail   : getAccountsCursor
,03-17 13:26:12.988  3974  3974 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:12.988  3974  3974 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:12.988  3974  3974 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:12.998  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:13.018  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:13.018  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:13.028  3925  3983 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-17 13:26:13.028  3756  3944 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 13:26:13.038  3974  3974 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 13:26:13.038  3974  3974 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:13.038  3974  3974 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:13.048  1018  1575 I ActivityManager: Killing 2755:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,03-17 13:26:13.048  3925  3925 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 13:26:13.058  3925  3983 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-17 13:26:13.058  3974  3974 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-17 13:26:13.058  3974  3974 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:13.058  3925  3983 W VideoCapabilities: Unsupported mime video/mp43
,03-17 13:26:13.068  1018  1573 I ActivityManager: Killing 3189:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-17 13:26:13.068  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 13:26:13.078  3756  3944 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-17 13:26:13.078  1018  1573 I ActivityManager: Killing 3200:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,03-17 13:26:13.088  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 13:26:13.088  1018  1018 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-17 13:26:13.088  1018  1577 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.088  1018  1577 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.088  1018  1577 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.098  3756  3944 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 13:26:13.098  3925  3983 W VideoCapabilities: Unsupported mime video/sorenson
,03-17 13:26:13.108  3925  3983 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-17 13:26:13.108  1018  1241 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.108  1018  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.108  1018  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.118  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.118  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.118  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.118  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.148  1018  1043 W libprocessgroup: failed to open /acct/uid_10117/pid_2755/cgroup.procs: No such file or directory
,03-17 13:26:13.158  4001  4001 E Zygote  : MountEmulatedStorage(),
03-17 13:26:13.158  4001  4001 E Zygote  : v2
03-17 13:26:13.158  4001  4001 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:13.158  4001  4001 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:13.158  4001  4001 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:13.158  4001  4001 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:13.158  1018  1018 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=4001 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:13.158  4001  4001 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:13.158  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.158  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:13.158  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.168  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3189/cgroup.procs: No such file or directory
,03-17 13:26:13.168  1018  1043 W libprocessgroup: failed to open /acct/uid_10146/pid_3200/cgroup.procs: No such file or directory
,03-17 13:26:13.178  3925  3983 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 13:26:13.188  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.188  1018  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.198  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.198  4001  4001 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:13.198  4001  4001 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.208  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.208  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.208  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.248  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.248  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.248  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.258  3925  3925 V Babel   : babel boot account: SMS
,03-17 13:26:13.258  3925  3925 V Babel   : babel boot account: thalitester@gmail.com
,03-17 13:26:13.268  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.268  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.268  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.268  1018  2825 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.278  1679  1697 I art     : Explicit concurrent mark sweep GC freed 3919(171KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 820us total 39.226ms,
03-17 13:26:13.278  4022  4022 E Zygote  : MountEmulatedStorage()
03-17 13:26:13.278  4022  4022 E Zygote  : v2
03-17 13:26:13.278  4022  4022 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 13:26:13.278  4022  4022 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:13.278  4022  4022 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:13.278  4022  4022 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:13.288  4022  4022 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:13.288  1018  2825 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4022 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 13:26:13.288  1679  1701 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-17 13:26:13.298  1018  1577 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.298  1018  1577 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.298  1018  1577 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.308  4022  4022 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:13.308  4022  4022 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.328  1018  1098 V AlarmManager: waitForAlarm result :4
,03-17 13:26:13.338  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.338  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.338  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 13:26:13.348  1018  1577 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.348  1018  1577 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:13.348  1018  1577 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.368  1018  1098 V AlarmManager: waitForAlarm result :4
,03-17 13:26:13.388  3756  3868 I Gmail   : getAccountsCursor
,03-17 13:26:13.388  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:13.398  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 13:26:13.398  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:13.398  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:13.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:13.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:13.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:13.408  2135  4018 I Icing   : Storage manager: low false usage 2.12MB avail 9.95GB capacity 11.63GB
,03-17 13:26:13.458  3974  3974 I Process : Sending signal. PID: 3974 SIG: 9
,03-17 13:26:13.468  2135  3998 D GCM     : COMPAT: Multi user not supported
,03-17 13:26:13.468  1018  1577 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.468  1018  1577 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.468  1018  1577 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.468  4001  4001 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:13.468   290   290 E SMD     : DCD OFF
,03-17 13:26:13.468  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.468  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:13.478  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 13:26:13.478  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.478  1018  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.478  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.478  1900  1900 D GCM     : COMPAT: Multi user not supported
,03-17 13:26:13.478  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.478  1018  2826 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.478  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.488  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.488  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.488  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.488  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.498  4059  4059 E Zygote  : MountEmulatedStorage()
,03-17 13:26:13.498  4059  4059 E Zygote  : v2
03-17 13:26:13.498  4059  4059 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:13.498  4059  4059 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:13.508  4059  4059 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:13.508  1018  1510 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4059 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 13:26:13.508  4059  4059 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:13.508  4059  4059 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:13.508  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.508  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.508  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.508  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.518  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.518  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.518  1018  1489 I ActivityManager: Process com.sec.android.app.sns3 (pid 3974)(adj 0) has died(34,655)
,03-17 13:26:13.518  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.518  1018  2826 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.518  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.528  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.528  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.528  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.528  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.528  4059  4059 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:13.528  4059  4059 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.548  1018  1044 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4074 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,03-17 13:26:13.548  4074  4074 E Zygote  : MountEmulatedStorage()
03-17 13:26:13.548  4074  4074 I libpersona: KNOX_SDCARD checking this for 10031,
03-17 13:26:13.548  4074  4074 E Zygote  : v2
03-17 13:26:13.548  4074  4074 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:13.548  4074  4074 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:13.558  4074  4074 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:13.558  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.558  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.558  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:13.558  4074  4074 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:13.568  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.568  2135  3998 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 13:26:13.568  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.568  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.568  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.578  4074  4074 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:13.578  4074  4074 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.588  1018  1571 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4089 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 13:26:13.588  1018  1571 I ActivityManager: Killing 3240:com.policydm/1000 (adj 15): empty #31
,03-17 13:26:13.588  4089  4089 E Zygote  : MountEmulatedStorage()
03-17 13:26:13.588  4089  4089 E Zygote  : v2
03-17 13:26:13.588  4089  4089 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:13.588  4089  4089 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:13.588  4089  4089 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:13.588  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.588  1018  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.598  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.598  4089  4089 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:13.598  4089  4089 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:13.618  4089  4089 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:13.618  4089  4089 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.628  4059  4059 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 13:26:13.688  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3240/cgroup.procs: No such file or directory
,03-17 13:26:13.688  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.688  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.688  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.698  4089  4089 E KnoxSetupWizardClient: isShipMode : 1
03-17 13:26:13.698  4089  4089 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 13:26:13.718  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:13.728  2135  4107 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 13:26:13.728  1018  1571 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.728  1018  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:13.728  1018  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-17 13:26:13.748  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.748  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.748  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.748  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.748  2135  2135 D SystemUpdateService: onCreate
,03-17 13:26:13.758  4059  4059 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-17 13:26:13.758  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-17 13:26:13.768  4115  4115 E Zygote  : MountEmulatedStorage(),
03-17 13:26:13.768  1018  1573 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4115 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:13.768  4115  4115 E Zygote  : v2,
03-17 13:26:13.768  4115  4115 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 13:26:13.768  4115  4115 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:13.768  4115  4115 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:13.778  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.778  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 13:26:13.778  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.778  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.778  4115  4115 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:13.778  4115  4115 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 13:26:13.798  4115  4115 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:13.798  4115  4115 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.808  4124  4124 E Zygote  : MountEmulatedStorage(),
03-17 13:26:13.808  4124  4124 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:13.808  4124  4124 E Zygote  : v2
03-17 13:26:13.808  4124  4124 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:13.808  4124  4124 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:13.808  4124  4124 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:13.818  1018  1573 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4124 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:13.818  4124  4124 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:13.818  1018  1573 I ActivityManager: Killing 3255:com.google.android.configupdater/u0a82 (adj 15): empty #31
,03-17 13:26:13.818  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.818  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:13.818  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.828  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.828  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:13.828  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-17 13:26:13.838  4124  4124 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:13.838  4124  4124 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.858  3444  3457 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-17 13:26:13.858  3831  3946 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-17 13:26:13.868  4059  4059 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-17 13:26:13.868  4059  4059 I F_PHONE : default registerAction()
03-17 13:26:13.868  4059  4059 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 13:26:13.868  4089  4108 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-17 13:26:13.868  2135  2135 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 13:26:13.878  4089  4108 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-17 13:26:13.878  4089  4108 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-17 13:26:13.878  4089  4108 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-17 13:26:13.878  4089  4108 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-17 13:26:13.878  4089  4108 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-17 13:26:13.878  4089  4108 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-17 13:26:13.888  2135  4151 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 13:26:13.898  4115  4115 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 13:26:13.898  2135  2135 D ChimeraCfgMgr: Reading stored module config
,03-17 13:26:13.898  4089  4089 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-17 13:26:13.928  4089  4089 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-17 13:26:13.928  4089  4089 D ShortcutReceiver:  KnoxContainerVersion 2.3.0
03-17 13:26:13.928  4089  4089 D ShortcutReceiver:  shortcut migration not required 
,03-17 13:26:13.948  2135  4151 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-17 13:26:13.958  1018  1043 W libprocessgroup: failed to open /acct/uid_10082/pid_3255/cgroup.procs: No such file or directory
,03-17 13:26:13.958  3948  3965 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 13:26:13.988  3948  3965 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 13:26:13.988  3948  3965 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:13.988  3948  3965 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:13.998  2135  4110 I CheckinService: Checking schedule, now: 1458217574012 next: 1458299986961
,03-17 13:26:13.998  2135  4110 I CheckinService: active receiver: disabled
,03-17 13:26:14.008  4115  4115 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-17 13:26:14.008  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-17 13:26:14.008  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.008  4115  4115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
03-17 13:26:14.008  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:14.008  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-17 13:26:14.008  4001  4058 I AMMetaDataParserService: Resource data:2131165186
,03-17 13:26:14.008  4001  4058 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 13:26:14.008  4001  4058 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:14.008  4001  4058 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 13:26:14.008  4001  4058 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 13:26:14.008  4001  4058 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-17 13:26:14.008  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:14.008  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.008  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.008  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.008  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.018  2135  2135 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
03-17 13:26:14.018  4001  4058 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
03-17 13:26:14.018  2135  2135 D BootCompletedReceiver: Got an BootCompleted event.
,03-17 13:26:14.028  4154  4154 E Zygote  : MountEmulatedStorage()
,03-17 13:26:14.028  4154  4154 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:14.028  4154  4154 E Zygote  : v2
03-17 13:26:14.028  4154  4154 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:14.028  4154  4154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 13:26:14.028  1018  1489 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4154 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 13:26:14.038  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.038  1018  2825 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:14.038  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.038  4154  4154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 13:26:14.038  4154  4154 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:14.038  4001  4058 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511,
,03-17 13:26:14.048  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:14.048  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:14.048  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-17 13:26:14.048  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.048  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.048  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.048  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.068  4166  4166 E Zygote  : MountEmulatedStorage()
03-17 13:26:14.068  4166  4166 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:14.068  4166  4166 E Zygote  : v2
03-17 13:26:14.068  4166  4166 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:14.068  4166  4166 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:14.068  1018  1569 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4166 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 13:26:14.068  1018  1569 I ActivityManager: Killing 3323:com.dropbox.android/u0a88 (adj 15): empty #31
,03-17 13:26:14.068  4166  4166 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:14.078  4166  4166 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:14.078  2135  4149 I SystemUpdateService: cancelUpdate (empty URL)
03-17 13:26:14.078  2135  4149 I SystemUpdateService: active receiver: disabled
,03-17 13:26:14.078  1477  1477 D BluetoothBDTestService: onCreate()
03-17 13:26:14.078  1477  1477 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 13:26:14.078  1477  1477 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-17 13:26:14.078  1477  1477 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
03-17 13:26:14.078  1477  1477 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
,03-17 13:26:14.088  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 13:26:14.098  4124  4124 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-17 13:26:14.098  4124  4124 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-17 13:26:14.098   305   305 I art     : Explicit concurrent mark sweep GC freed 8755(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.055ms total 35.012ms
03-17 13:26:14.108  4154  4154 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:14.108  4154  4154 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:14.118  4166  4166 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:14.118  4166  4166 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:14.118   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 17.838ms
,03-17 13:26:14.128  4124  4124 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-17 13:26:14.128  4124  4181 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 13:26:14.128  4124  4181 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
03-17 13:26:14.128  2135  4151 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 13:26:14.138  4001  4058 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,03-17 13:26:14.138   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 18.195ms
,03-17 13:26:14.148  2135  2135 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-17 13:26:14.148  1018  2754 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-17 13:26:14.148  4124  4124 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 13:26:14.148  4124  4124 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
03-17 13:26:14.158  4124  4181 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-17 13:26:14.158  4124  4124 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-17 13:26:14.158  4154  4154 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataP,arserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-17 13:26:14.168  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,03-17 13:26:14.178  4001  4058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 13:26:14.178  4124  4124 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-17 13:26:14.178  4124  4124 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,03-17 13:26:14.178  4124  4124 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
03-17 13:26:14.178  4124  4124 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 13:26:14.188  4154  4154 I StatusChecker: onReceive : net.mt.init : DONE
,03-17 13:26:14.188  4124  4124 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-17 13:26:14.188  4124  4124 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 13:26:14.188  1018  2754 D SSRM:n  : SIOP:: AP = 420
,03-17 13:26:14.198  4124  4124 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-17 13:26:14.198  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.198  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.198  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.198  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.198  4124  4124 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 13:26:14.208  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,03-17 13:26:14.208  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.208  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:14.208  4001  4058 I AMMetaDataParserService: Resource data:2131034113
,03-17 13:26:14.218  1018  1030 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4190 uid=10113 gids={50113, 9997} abi=armeabi-v7a,
,03-17 13:26:14.218  1018  1030 I ActivityManager: Killing 3355:com.fmm.dm/1000 (adj 15): empty #31
,03-17 13:26:14.218  4166  4166 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,03-17 13:26:14.228  4190  4190 E Zygote  : MountEmulatedStorage(),
03-17 13:26:14.228  4190  4190 E Zygote  : v2
03-17 13:26:14.228  4190  4190 I libpersona: KNOX_SDCARD checking this for 10113
03-17 13:26:14.228  4190  4190 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:14.228  4001  4058 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:14.228  4001  4058 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:14.228  4001  4058 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:14.228  4001  4058 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 13:26:14.228  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:14.228  4190  4190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 13:26:14.238  4190  4190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 13:26:14.238  4190  4190 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 13:26:14.248  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.248  4001  4058 I GFX construct_block_size_descriptor_2d second part: took 2.901354ms for 0*0 texture 0
,03-17 13:26:14.268  4124  4124 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-17 13:26:14.268  4190  4190 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:14.268  4190  4190 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:14.278  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.278  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.278  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.278  4001  4058 I GFX generate_partition_tables: took 6.694634ms for 0*0 texture 0
03-17 13:26:14.278  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.278  4001  4058 I GFX raster: took 10.998905ms for 96*96 texture 0
03-17 13:26:14.278  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76e5060 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76e5308 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.298  1018  1043 W libprocessgroup: failed to open /acct/uid_10088/pid_3323/cgroup.procs: No such file or directory,
,03-17 13:26:14.298  4205  4205 E Zygote  : MountEmulatedStorage(),
03-17 13:26:14.298  4205  4205 E Zygote  : v2
03-17 13:26:14.298  4205  4205 I libpersona: KNOX_SDCARD checking this for 10032
03-17 13:26:14.298  4205  4205 I libpersona: KNOX_SDCARD not a persona,
,03-17 13:26:14.298  4205  4205 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 13:26:14.298  4205  4205 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:14.308  4205  4205 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-17 13:26:14.308  4001  4058 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 13:26:14.308  1018  1030 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4205 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 13:26:14.308  1018  1030 I ActivityManager: Killing 3367:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,03-17 13:26:14.318  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.318  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:14.318  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.318  1018  1573 I ActivityManager: Killing 3466:com.fmm.ds/1000 (adj 15): empty #31
,03-17 13:26:14.328  3398  3508 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 13:26:14.328  4205  4205 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:14.328  4205  4205 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:14.348  1018  1241 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 13:26:14.358  4166  4166 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-17 13:26:14.358  2135  4151 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-17 13:26:14.358  4166  4166 I KnoxUsageLogPro: premStatus:2
,03-17 13:26:14.358  4166  4166 I KnoxUsageLogPro: isEulaShown : false
03-17 13:26:14.358  4166  4166 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-17 13:26:14.368  4166  4221 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458217574382
,03-17 13:26:14.378  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.388  4001  4058 I GFX raster: took 0.875521ms for 96*96 texture 0
03-17 13:26:14.388  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76e5060 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76f3df8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.398  4001  4058 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 13:26:14.408  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:14.408  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:14.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:14.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:14.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:14.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:14.408  4124  4181 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 13:26:14.418  4124  4181 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 13:26:14.418  4124  4181 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 13:26:14.418  4124  4181 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-17 13:26:14.418  4124  4181 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-17 13:26:14.428  4124  4181 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 13:26:14.458  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3355/cgroup.procs: No such file or directory
,03-17 13:26:14.478  4124  4181 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 13:26:14.488  4124  4181 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 13:26:14.488  4124  4181 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
03-17 13:26:14.488  4124  4182 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 13:26:14.488  4124  4182 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 13:26:14.498  4124  4181 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 13:26:14.498  4124  4182 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 13:26:14.498  4124  4182 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
03-17 13:26:14.498  4124  4181 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
,03-17 13:26:14.498  4124  4182 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 13:26:14.508  4124  4181 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/13:26:14
,03-17 13:26:14.508  4124  4182 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 13:26:14.508  4124  4181 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-17 13:26:14.508  4124  4182 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 13:26:14.508  4124  4181 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-17 13:26:14.508  4124  4182 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-17 13:26:14.508  4124  4182 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 13:26:14.508  4124  4182 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 13:26:14.518  1018  1575 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:14.518  1018  1575 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:14.518  4166  4221 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 44144
03-17 13:26:14.518  1018  1575 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.518  4190  4190 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-17 13:26:14.528  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3466/cgroup.procs: No such file or directory
,03-17 13:26:14.528  1018  1043 W libprocessgroup: failed to open /acct/uid_10088/pid_3367/cgroup.procs: No such file or directory
,03-17 13:26:14.528  4190  4190 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-17 13:26:14.538  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.538  4001  4058 I GFX construct_block_size_descriptor_2d second part: took 2.251042ms for 0*0 texture 0
,03-17 13:26:14.538  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:14.538  1018  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:14.538  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-17 13:26:14.548  4001  4058 I GFX generate_partition_tables: took 7.448333ms for 0*0 texture 0
,03-17 13:26:14.548  4001  4058 I GFX raster: took 10.664896ms for 96*96 texture 0
03-17 13:26:14.548  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76f0700 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76f07f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.548  4190  4190 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-17 13:26:14.548  4001  4058 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 13:26:14.558  4124  4182 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 13:26:14.558  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.558  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.558  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.558  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.568  4233  4233 E Zygote  : MountEmulatedStorage(),
03-17 13:26:14.578  4233  4233 E Zygote  : v2,
03-17 13:26:14.578  4233  4233 I libpersona: KNOX_SDCARD checking this for 10121
03-17 13:26:14.578  4233  4233 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:14.578  4233  4233 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:14.578  4233  4233 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 13:26:14.578  4233  4233 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:14.578  1018  1327 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4233 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 13:26:14.598  4124  4181 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 13:26:14.598  2135  4151 I AuthZen : Fetching signing key...
,03-17 13:26:14.608  4233  4233 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:14.608  4233  4233 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:14.618  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.618  4001  4058 I GFX raster: took 0.598906ms for 96*96 texture 0
,03-17 13:26:14.618  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76edf18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76ee080 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.628  4233  4233 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:14.628  4233  4233 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 13:26:14.628  4233  4233 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 13:26:14.638  4001  4058 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 13:26:14.638  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.638  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:14.638  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.638  3831  3848 W art     : Suspending all threads took: 15.599ms
,03-17 13:26:14.648  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:14.648  4001  4058 I GFX raster: took 1.067812ms for 96*96 texture 0
03-17 13:26:14.648  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76f32d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76f3438 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.658  4001  4058 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 13:26:14.668  2135  2135 D SystemUpdateService: onDestroy
,03-17 13:26:14.688  2135  4151 I AuthZen : Signing key fetched successfully!
,03-17 13:26:14.688  1900  4251 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-17 13:26:14.688  4124  4182 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-17 13:26:14.698  2135  4151 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 13:26:14.728  1679  1853 I art     : Explicit concurrent mark sweep GC freed 3582(138KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 1.116ms total 24.861ms
,03-17 13:26:14.728   280   955 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 13:26:14.728   280   955 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-17 13:26:14.748  4124  4181 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-17 13:26:14.748  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.748  4001  4058 I GFX raster: took 0.633802ms for 96*96 texture 0
03-17 13:26:14.748  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76f0350 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76b7170 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.758  4124  4181 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 13:26:14.758  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 13:26:14.758  2135  2163 W art     : Suspending all threads took: 12.246ms
,03-17 13:26:14.768  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.768  4001  4058 I GFX raster: took 0.701511ms for 96*96 texture 0
,03-17 13:26:14.768  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76d2ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76d3970 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.778  4001  4058 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 13:26:14.778  4205  4257 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-17 13:26:14.778  4205  4257 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-17 13:26:14.778  2135  4112 I EventLogService: Aggregate from 1458215226078 (log), 1458215226078 (data)
,03-17 13:26:14.788  4205  4205 E SPPClientService: [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,03-17 13:26:14.798  2135  4151 D a       : Opening database auth.proximity.permit_store...
,03-17 13:26:14.798  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.798  4001  4058 I GFX raster: took 0.536094ms for 96*96 texture 0
,03-17 13:26:14.798  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76d44a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76b7170 counterpartCT=4 counterpartW=96 counterparth=96
03-17 13:26:14.808  4233  4233 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-17 13:26:14.808  2135  4151 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
03-17 13:26:14.808  2135  4151 D AuthZenTransactionCache: Clearing transaction cache
,03-17 13:26:14.808  1018  1031 D SettingsProvider: name = scon_is_running
03-17 13:26:14.808  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:14.808  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:14.808  1018  1031 D SettingsProvider: selectionArgs: false
03-17 13:26:14.808  1018  1031 D SettingsProvider: selectionArgs: 10121
03-17 13:26:14.808  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:14.808  1018  1031 D SettingsProvider: ret = -1
03-17 13:26:14.808  4001  4058 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 13:26:14.808  1900  1900 I GCoreUlr: DispatchingService.onCreate()
,03-17 13:26:14.818  1018  1031 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-17 13:26:14.818  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-17 13:26:14.818  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.818  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:14.818  4001  4058 I AMMetaDataParserService: Resource data:2131034113
,03-17 13:26:14.818  4001  4058 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
,03-17 13:26:14.818  4124  4182 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-17 13:26:14.828  4233  4233 D QuickConnect: Utils.setQCRunningSetting - set : 0
,03-17 13:26:14.828  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:14.828  4233  4233 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-17 13:26:14.828  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.828  4001  4058 I GFX raster: took 0.949583ms for 96*96 texture 0
03-17 13:26:14.828  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76d4170 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76d3970 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.828  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:14.838  4233  4233 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 13:26:14.838  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.838  4001  4058 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
03-17 13:26:14.838  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.838  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.838  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.848  4124  4182 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 13:26:14.858  1018  1030 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4258 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
03-17 13:26:14.858  1018  1030 I ActivityManager: Killing 3280:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,03-17 13:26:14.868  4258  4258 E Zygote  : MountEmulatedStorage(),
03-17 13:26:14.868  4258  4258 E Zygote  : v2
03-17 13:26:14.868  4258  4258 I libpersona: KNOX_SDCARD checking this for 10127
03-17 13:26:14.868  4258  4258 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:14.868  4258  4258 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 13:26:14.878  4258  4258 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:14.878  4258  4258 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:14.878  4124  4182 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 13:26:14.898  2135  4018 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-17 13:26:14.908  4258  4258 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:14.908  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 13:26:14.908  4258  4258 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:14.928  4205  4257 D SPPClientService: PushLog.txt file is not deleted.
,03-17 13:26:14.928  4205  4257 D SPPClientService: PushLog.txt file is not deleted.
03-17 13:26:14.928  4205  4257 D SPPClientService: ============PushLog. stop!
,03-17 13:26:14.938  4258  4258 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 13:26:14.938  4258  4258 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:14.948  4258  4258 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 13:26:14.948  4258  4258 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:14.958  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.958  4001  4058 I GFX raster: took 0.845937ms for 96*96 texture 0
,03-17 13:26:14.958  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76d4170 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7404ab0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.968  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:14.978  4001  4058 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 13:26:14.978  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.978  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.978  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.978  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.978  1018  1043 W libprocessgroup: failed to open /acct/uid_10008/pid_3280/cgroup.procs: No such file or directory
,03-17 13:26:14.998  4278  4278 E Zygote  : MountEmulatedStorage(),
03-17 13:26:14.998  4278  4278 E Zygote  : v2
03-17 13:26:14.998  4278  4278 I libpersona: KNOX_SDCARD checking this for 10036
03-17 13:26:14.998  4278  4278 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:14.998  4278  4278 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:14.998  4278  4278 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:14.998  1018  1569 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4278 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:14.998  1018  1569 I ActivityManager: Killing 3527:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,03-17 13:26:14.998  4278  4278 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 13:26:15.028  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.028  4001  4058 I GFX raster: took 0.643385ms for 96*96 texture 0
03-17 13:26:15.028  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76e5060 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76d3970 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.038  1900  4250 I GCM     : GCM config loaded
,03-17 13:26:15.038  4001  4058 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 13:26:15.048  4278  4278 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:15.048  4278  4278 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:15.058  1900  4270 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-17 13:26:15.088  1900  1911 I art     : Explicit concurrent mark sweep GC freed 21180(1519KB) AllocSpace objects, 27(431KB) LOS objects, 39% free, 9MB/15MB, paused 4.703ms total 174.023ms
,03-17 13:26:15.088  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-17 13:26:15.108  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.108  4001  4058 I GFX raster: took 0.636667ms for 96*96 texture 0
03-17 13:26:15.108  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7404ab0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76d3970 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.118  4001  4058 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 13:26:15.128  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.128  4001  4058 I GFX raster: took 0.843855ms for 96*96 texture 0
,03-17 13:26:15.128  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76f32d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76b7170 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.138  1018  1043 W libprocessgroup: failed to open /acct/uid_10090/pid_3527/cgroup.procs: No such file or directory
,03-17 13:26:15.138  4001  4058 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 13:26:15.178  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.178  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:15.178  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:15.188  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.188  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:15.188  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:15.268  1018  2865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:15.268  1018  1577 I art     : Explicit concurrent mark sweep GC freed 34453(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 24MB/36MB, paused 2.575ms total 175.309ms
,03-17 13:26:15.278  4258  4258 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-17 13:26:15.288  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.288  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:15.288  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:15.308  4258  4258 D ManifestProvider: onCreate()
,03-17 13:26:15.318  4258  4258 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-17 13:26:15.358  4258  4258 W System.err: java.lang.NoSuchMethodException: isEnabled []
,03-17 13:26:15.358  4258  4258 W System.err: 	at java.lang.Class.getMethod(Class.java:665)
,03-17 13:26:15.358  4258  4258 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
03-17 13:26:15.358  4258  4258 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
03-17 13:26:15.358  4258  4258 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
03-17 13:26:15.358  4258  4258 W System.err: 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
03-17 13:26:15.358  4258  4258 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
03-17 13:26:15.358  4258  4258 W System.err: 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
03-17 13:26:15.358  4258  4258 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 13:26:15.358  4258  4258 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 13:26:15.358  4258  4258 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 13:26:15.358  4258  4258 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:15.358  4258  4258 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:15.358  4258  4258 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:26:15.358  4258  4258 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:15.358  4258  4258 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:15.358  4258  4258 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:15.358  4258  4258 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 13:26:15.368  4258  4258 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@388074ab
,03-17 13:26:15.368  4258  4258 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
03-17 13:26:15.368  4258  4258 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-17 13:26:15.378  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.378  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.378  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.378  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.388  4306  4306 E Zygote  : MountEmulatedStorage(),
,03-17 13:26:15.388  4306  4306 E Zygote  : v2
03-17 13:26:15.388  4306  4306 I libpersona: KNOX_SDCARD checking this for 10131
03-17 13:26:15.388  4306  4306 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:15.388  4306  4306 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:15.398  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-17 13:26:15.398  4001  4058 I GFX raster: took 0.638490ms for 96*96 texture 0
03-17 13:26:15.398  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76f0350 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76d3970 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.398  1018  1139 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4306 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
03-17 13:26:15.398  1018  1139 I ActivityManager: Killing 3561:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,03-17 13:26:15.398  4306  4306 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:15.398  4306  4306 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:15.408  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 13:26:15.418  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.418  4001  4058 I GFX raster: took 0.694792ms for 96*96 texture 0
03-17 13:26:15.418  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76d2ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76b7170 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.418  4306  4306 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:15.418  4306  4306 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:15.428  4001  4058 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 13:26:15.428  4278  4278 I SA      : [SSP] onCreated
,03-17 13:26:15.438  4306  4306 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
03-17 13:26:15.438  4306  4306 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:15.438  4306  4306 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:15.458  1900  1900 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,03-17 13:26:15.468  1900  4270 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-17 13:26:15.468  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.468  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:15.468  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:15.488  1900  2192 W GCoreFlp: No location to return for getLastLocation()
,03-17 13:26:15.488  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:15.488  1900  2194 W FusedLocationProvider: location=null
,03-17 13:26:15.498  1900  4270 I GCoreUlr: Unbound from all location providers
03-17 13:26:15.498  1900  4270 I GCoreUlr: Place inference reporting - stopped
,03-17 13:26:15.508  1018  1043 W libprocessgroup: failed to open /acct/uid_10013/pid_3561/cgroup.procs: No such file or directory
03-17 13:26:15.508  1018  1575 I ActivityManager: Killing 3591:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,03-17 13:26:15.518  1900  2192 W GCoreFlp: No location to return for getLastLocation()
,03-17 13:26:15.518  1900  1917 W FusedLocationProvider: location=null
,03-17 13:26:15.518  4278  4278 I SA      : [TPM] There is no property file
,03-17 13:26:15.518  1900  1900 I GCoreUlr: DispatchingService.onDestroy()
03-17 13:26:15.518  1900  1900 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-17 13:26:15.528  4278  4278 I SA      : [SCU] isHaveSA() - false
,03-17 13:26:15.528  4278  4278 I SA      : [TPM] getModelProperty : null
03-17 13:26:15.528  4278  4278 I SA      : [TPM] getCSCProperty : null
,03-17 13:26:15.528  4278  4278 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-17 13:26:15.528  4278  4278 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-17 13:26:15.528  4278  4278 I SA      : [DM] TFT FEATURE: false
,03-17 13:26:15.528  1900  1900 I GCoreUlr: Unbound from all location providers
,03-17 13:26:15.538  1900  1900 I GCoreUlr: Place inference reporting - stopped
,03-17 13:26:15.548  4278  4278 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,03-17 13:26:15.548  4278  4278 I SA      : [DM] init START
,03-17 13:26:15.548  4278  4278 I SA      : [DM] This device is not a Vodafone
,03-17 13:26:15.568  1823  1833 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:15.568  4278  4278 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,03-17 13:26:15.568  4278  4278 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
03-17 13:26:15.568  4278  4278 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
03-17 13:26:15.568  4278  4278 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,03-17 13:26:15.568  4278  4278 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,03-17 13:26:15.578  4278  4278 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,03-17 13:26:15.578  4278  4278 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,03-17 13:26:15.578  4278  4278 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-17 13:26:15.578  1900  1900 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
03-17 13:26:15.578  4278  4278 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,03-17 13:26:15.578  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.578  4001  4058 I GFX raster: took 0.527083ms for 96*96 texture 0
03-17 13:26:15.578  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76d44a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76cd478 counterpartCT=4 counterpartW=96 counterparth=96
03-17 13:26:15.578  4278  4278 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
03-17 13:26:15.588  1018  1571 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,03-17 13:26:15.588  1018  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,03-17 13:26:15.588  1018  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
03-17 13:26:15.588  4278  4278 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,03-17 13:26:15.598  4278  4278 I SA      : [SCU] isHaveSA() - false
03-17 13:26:15.598  4278  4278 I SA      : support phone number id : false
03-17 13:26:15.598  4278  4278 I SA      : [DM] Supports Ref Jpn : true
,03-17 13:26:15.598  4278  4278 I SA      : [DM] init END
,03-17 13:26:15.598  4001  4058 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 13:26:15.598  4278  4278 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
03-17 13:26:15.598  4278  4278 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-17 13:26:15.598  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:15.598  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:15.598  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:15.608  4001 , 4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: Resource data:2131034112
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-17 13:26:15.608  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:15.608  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.608  4001  4058 I GFX raster: took 0.628698ms for 96*96 texture 0
03-17 13:26:15.608  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7404ab0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76b7170 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.608  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.608  1018  1569 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,03-17 13:26:15.618  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-17 13:26:15.618  4001  4058 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-17 13:26:15.618  4278  4278 I SA      : [OR] onReceive END
,03-17 13:26:15.618  1018  1043 W libprocessgroup: failed to open /acct/uid_10055/pid_3591/cgroup.procs: No such file or directory
,03-17 13:26:15.628  1018  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.628  1018  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.628  1018  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.628  1018  1577 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.638  4278  4278 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 13:26:15.638  4278  4278 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-17 13:26:15.648  4278  4278 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-17 13:26:15.648  4278  4278 I SA      : [LBE] REF_JPN : true
03-17 13:26:15.648  4278  4278 I SA      : [BDC] create
,03-17 13:26:15.648  4333  4333 E Zygote  : MountEmulatedStorage()
,03-17 13:26:15.648  4333  4333 I libpersona: KNOX_SDCARD checking this for 10037
03-17 13:26:15.648  4333  4333 E Zygote  : v2
03-17 13:26:15.648  4333  4333 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:15.648  4333  4333 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:15.648  4333  4333 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:15.648  1018  1577 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4333 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:15.648  4333  4333 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 13:26:15.658  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:15.658  1018  2826 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:15.658  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 13:26:15.658  1018  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:15.658  1018  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:15.658  1018  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:15.668  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.668  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.668  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.668  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.668  4278  4278 I SA      : [DBMV2] getEmailID
,03-17 13:26:15.668  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:15.668  4333  4333 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:15.668  4333  4333 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:15.678  4278  4278 I SA      : [DBMV2] getDataV02ForItems
03-17 13:26:15.678  4278  4278 I SA      : [SSP] query invoked
,03-17 13:26:15.678  4001  4058 I GFX raster: took 0.663853ms for 96*96 texture 0
03-17 13:26:15.678  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7404ab0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76cd478 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.678  4348  4348 E Zygote  : MountEmulatedStorage()
,03-17 13:26:15.678  4348  4348 E Zygote  : v2
03-17 13:26:15.678  4348  4348 I libpersona: KNOX_SDCARD checking this for 10135
03-17 13:26:15.678  4348  4348 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:15.678  4348  4348 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:15.678  4348  4348 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:15.678  4348  4348 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:15.678  4001  4058 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-17 13:26:15.688  4278  4278 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-17 13:26:15.688  1018  1031 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4348 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-17 13:26:15.688  4278  4278 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-17 13:26:15.698  4278  4278 I SA      : [BDC] destroy
,03-17 13:26:15.718  4348  4348 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:15.718  4348  4348 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:15.728  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{14695618 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,03-17 13:26:15.738  4333  4333 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-17 13:26:15.738  4348  4348 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 13:26:15.738  4348  4348 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:15.738  4348  4348 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 13:26:15.738  4348  4348 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-17 13:26:15.738  4348  4348 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:15.758  1018  1489 I ActivityManager: Killing 3610:com.sec.factory.camera/1000 (adj 15): empty #31
,03-17 13:26:15.818  1018  1498 I ActivityManager: Killing 3634:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,03-17 13:26:15.838  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.838  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.838  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.838  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.848  4333  4333 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-17 13:26:15.848  1018  1571 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4368 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-17 13:26:15.848  4368  4368 E Zygote  : MountEmulatedStorage()
,03-17 13:26:15.848  4368  4368 E Zygote  : v2
03-17 13:26:15.848  4368  4368 I libpersona: KNOX_SDCARD checking this for 10141
03-17 13:26:15.848  4368  4368 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:15.848  4368  4368 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 13:26:15.858  4368  4368 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:15.868  4368  4368 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:15.868  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:15.868  4001  4058 I GFX raster: took 0.779062ms for 96*96 texture 0
03-17 13:26:15.868  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76b7170 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76cb850 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.888  4001  4058 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-17 13:26:15.898  4368  4368 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:15.898  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:15.898  4001  4058 I GFX raster: took 0.805105ms for 96*96 texture 0
03-17 13:26:15.898  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76f0350 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76cd478 counterpartCT=4 counterpartW=96 counterparth=96
03-17 13:26:15.898  4368  4368 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:15.908  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3610/cgroup.procs: No such file or directory
03-17 13:26:15.908  1018  1043 W libprocessgroup: failed to open /acct/uid_10095/pid_3634/cgroup.procs: No such file or directory
,03-17 13:26:15.908  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-17 13:26:15.928  4368  4368 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 13:26:15.928  4368  4368 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:15.928  4368  4368 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:15.928  4368  4368 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:15.968  1018  1098 V AlarmManager: waitForAlarm result :8
,03-17 13:26:16.028  1018  1498 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:26:16.028  1018  1498 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-17 13:26:16.028  1018  1498 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 13:26:16.028  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:26:16.038  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 13:26:16.038  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:26:16.038  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 13:26:16.038  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false,
,03-17 13:26:16.038  1435  1435 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 13:26:16.038  1435  1435 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:26:16.048  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 13:26:16.048  2656  2741 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:26:16.058  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:26:16.058  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:26:16.058  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:26:16.068  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 13:26:16.068  1174  1174 D SViewCoverView: level :100 plugged : 2
,03-17 13:26:16.068  1018  1139 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:16.078  1018  2826 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:16.098  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-17 13:26:16.108  1018  1571 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:16.118  1018  1510 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsun,g.contacts.emergency.EmergencyMessageContactCreateActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
,03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: Resource data:2131034113
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 13:26:16.128  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
03-17 13:26:16.128  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.128  4001  4058 I GFX raster: took 0.838074ms for 96*96 texture 0
,03-17 13:26:16.128  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76d4170 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76ed2e8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.148  4001  4058 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 13:26:16.148  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.158  4001  4058 I GFX raster: took 0.892135ms for 96*96 texture 0
03-17 13:26:16.158  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76d4170 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76cb850 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.158  4001  4058 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 13:26:16.178  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.178  4001  4058 I GFX raster: took 1.046510ms for 96*96 texture 0
03-17 13:26:16.178  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76e5060 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76cd478 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.188  4001  4058 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 13:26:16.208  1018  2825 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:16.208  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.208  4001  4058 I GFX raster: took 0.618593ms for 96*96 texture 0
,03-17 13:26:16.208  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76b9240 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76cd478 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.208  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.218  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.218  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.218  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.218  1018  1575 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:16.218  4001  4058 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 13:26:16.228  4403  4403 E Zygote  : MountEmulatedStorage()
03-17 13:26:16.228  4403  4403 E Zygote  : v2
03-17 13:26:16.228  4403  4403 I libpersona: KNOX_SDCARD checking this for 10068
03-17 13:26:16.228  4403  4403 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:16.228  4403  4403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:16.238  1018  1489 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4403 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
03-17 13:26:16.238  4403  4403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:16.238  4403  4403 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 13:26:16.238  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.238  1018  2826 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:16.238  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-17 13:26:16.248  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.248  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:16.248  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 13:26:16.258  4403  4403 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:16.258  4403  4403 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.268  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.268  4001  4058 I GFX raster: took 0.829896ms for 96*96 texture 0
03-17 13:26:16.268  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76d44a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7404ab0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.278  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.278  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.278  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.278  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.278  4001  4058 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 13:26:16.288  4423  4423 E Zygote  : MountEmulatedStorage()
03-17 13:26:16.288  4423  4423 E Zygote  : v2
03-17 13:26:16.288  4423  4423 I libpersona: KNOX_SDCARD checking this for 10142
03-17 13:26:16.288  4423  4423 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:16.288  4423  4423 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:16.288  4423  4423 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:16.288  1018  1139 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4423 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 13:26:16.298  4423  4423 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 13:26:16.298  1018  1139 I ActivityManager: Killing 3425:com.google.android.partnersetup/u0a14 (adj 15): empty #31,
,03-17 13:26:16.318  4423  4423 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:16.318  4423  4423 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.318  4403  4403 D BadgeProvider: onCreate
03-17 13:26:16.318  4403  4403 D BadgeProvider: DatabaseHelper
,03-17 13:26:16.328   305   305 I art     : Explicit concurrent mark sweep GC freed 8681(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 693us total 32.927ms
,03-17 13:26:16.338  1018  1241 I ActivityManager: Killing 3684:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,03-17 13:26:16.348  4423  4423 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 13:26:16.348  2135  4018 I Icing   : Internal init done: storage state 0
,03-17 13:26:16.348   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.121ms total 20.445ms
03-17 13:26:16.348  4403  4411 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 13:26:16.368   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 18.858ms
,03-17 13:26:16.378  4403  4411 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 13:26:16.378  1018  1052 D PowerManagerService: [s] UserActivityState : 1 -> 2
03-17 13:26:16.378  4403  4411 D BadgeProvider: sendNotify, [notify] : null
03-17 13:26:16.378  1018  1052 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
03-17 13:26:16.378  4403  4411 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 13:26:16.378  1018  1052 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:16.378  4403  4411 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 13:26:16.378  4403  4411 D BadgeProvider: update, [UpdateCount] : 1
,03-17 13:26:16.378  1499  1499 D Launcher.Model: reloadBadges entered.
,03-17 13:26:16.388  2135  4018 I Icing   : Post-init done
,03-17 13:26:16.388  1018  1052 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 13:26:16.398  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.398  1018  2825 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:16.398  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:16.408  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:16.408  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:16.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:16.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:16.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:16.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:16.408  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.408  1018  1052 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
03-17 13:26:16.408  1018  1052 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:16.408  1018  1158 D lights  : lcd : 15 +
03-17 13:26:16.408  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:16.408  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:16.418  1018  1498 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 13:26:16.418  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.428  4001  4058 I GFX raster: took 0.806771ms for 96*96 texture 0
03-17 13:26:16.428  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76f0350 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76d31b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.428  1018  1158 D lights  : lcd : 15 -
03-17 13:26:16.428  1018  1052 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
,03-17 13:26:16.428  1018  1052 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:16.428  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 13:26:16.438  1018  1043 W libprocessgroup: failed to open /acct/uid_10014/pid_3425/cgroup.procs: No such file or directory
,03-17 13:26:16.468  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.468  4001  4058 I GFX raster: took 0.706302ms for 96*96 texture 0
,03-17 13:26:16.468  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76b7170 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76cd478 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.468  1018  1139 W ActivityManager: getTasks: caller 10141 does not hold GET_TASKS; limiting output
,03-17 13:26:16.468   290   290 E SMD     : DCD OFF
,03-17 13:26:16.478  1018  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.478  1018  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:16.478  1018  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:16.478  4368  4419 I Process : Sending signal. PID: 4368 SIG: 9
,03-17 13:26:16.478  1018  1030 I ActivityManager: Killing 3700:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,03-17 13:26:16.478  4001  4058 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 13:26:16.488  1018  1569 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:16.488  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.488  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:16.488  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-17 13:26:16.498  1018  1577 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.498  1018  1577 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:16.498  1018  1577 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:16.498  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.498  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.498  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.498  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.508  4442  4442 E Zygote  : MountEmulatedStorage()
,03-17 13:26:16.508  4442  4442 E Zygote  : v2
03-17 13:26:16.508  4442  4442 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:16.508  4442  4442 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:16.518  4442  4442 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:16.518  1018  1573 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4442 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:16.518  4442  4442 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:16.518  4442  4442 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:16.518  1018  1577 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!,
03-17 13:26:16.518   256   256 E lowmemorykiller: Error writing /proc/4368/oom_score_adj; errno=22
,03-17 13:26:16.528  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.528  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:16.528  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:16.538  4423  4443 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,03-17 13:26:16.538  4442  4442 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:16.538  1018  1043 W libprocessgroup: failed to open /acct/uid_10020/pid_3684/cgroup.procs: No such file or directory
03-17 13:26:16.538  4442  4442 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.538   256   256 E lowmemorykiller: Error writing /proc/4368/oom_score_adj; errno=22
03-17 13:26:16.538  1018  1571 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
03-17 13:26:16.538  1018  1571 I ActivityManager: Killing 3711:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
03-17 13:26:16.538  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.548  4001  4058 I GFX raster: took 0.571614ms for 96*96 texture 0
03-17 13:26:16.548  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7404ab0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76d31b0 counterpartCT=4 counterpartW=96 counterparth=96
03-17 13:26:16.548  1018  1498 W ActivityManager: getTasks: caller 10142 does not hold GET_TASKS; limiting output
,03-17 13:26:16.548   256   256 E lowmemorykiller: Error writing /proc/4368/oom_score_adj; errno=22
,03-17 13:26:16.548  4001  4058 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
03-17 13:26:16.548  4423  4443 I Process : Sending signal. PID: 4423 SIG: 9
,03-17 13:26:16.558  1018  1569 I ActivityManager: Process com.android.email (pid 4368)(adj 11) has died(41,626)
,03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-17 13:26:16.568  4001  4058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 13:26:16.568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-17 13:26:16.,568  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-17 13:26:16.578  1018  1241 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.578  1018  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:16.578  1018  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
,03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange,
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-17 13:26:16.588  4001  4058 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
,03-17 13:26:16.588  4001  4058 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-17 13:26:16.588  4001  4058 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-17 13:26:16.588  4001  4058 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
,03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:16.578  4001  4058 I AMMetaDataParserService: Resource data:2131165203
03-17 13:26:16.588  4001  4058 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-17 13:26:16.588  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
03-17 13:26:16.588  1018  1575 I ActivityManager: Process com.android.exchange (pid 4423)(adj 9) has died(43,626)
,03-17 13:26:16.588  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-17 13:26:16.588  4001  4058 I GFX construct_block_size_descriptor_2d second part: took 3.546979ms for 0*0 texture 0
,03-17 13:26:16.598  1018  1043 W libprocessgroup: failed to open /acct/uid_10056/pid_3700/cgroup.procs: No such file or directory
,03-17 13:26:16.598  1018  1043 W libprocessgroup: failed to open /acct/uid_10098/pid_3711/cgroup.procs: No such file or directory
,03-17 13:26:16.608  4001  4058 I GFX generate_partition_tables: took 17.195417ms for 0*0 texture 0
,03-17 13:26:16.608  4001  4058 I GFX raster: took 21.325261ms for 80*80 texture 0
03-17 13:26:16.608  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb789f120 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb789fde0 counterpartCT=4 counterpartW=80 counterparth=80
,03-17 13:26:16.618  4001  4058 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-17 13:26:16.618  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.618  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.618  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.618  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.628  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-17 13:26:16.628  4001  4058 I GFX construct_block_size_descriptor_2d second part: took 2.332344ms for 0*0 texture 0
,03-17 13:26:16.638  4459  4459 E Zygote  : MountEmulatedStorage()
03-17 13:26:16.638  4459  4459 E Zygote  : v2
03-17 13:26:16.638  4459  4459 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:16.638  4459  4459 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:16.638  4459  4459 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:16.638  4001  4058 I GFX generate_partition_tables: took 5.343180ms for 0*0 texture 0
,03-17 13:26:16.638  4001  4058 I GFX raster: took 8.730109ms for 80*80 texture 0
03-17 13:26:16.638  4459  4459 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:16.638  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76cf848 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb76cf8f0 counterpartCT=4 counterpartW=80 counterparth=80
,03-17 13:26:16.638  4459  4459 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:16.648  4001  4058 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 13:26:16.658  1018  1569 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4459 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 13:26:16.658  4459  4459 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:16.658  4459  4459 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.668  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-17 13:26:16.668  4001  4058 I GFX raster: took 0.699948ms for 80*80 texture 0
03-17 13:26:16.668  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76cf848 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb76c6c68 counterpartCT=4 counterpartW=80 counterparth=80
,03-17 13:26:16.678  4001  4058 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 13:26:16.698  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-17 13:26:16.698  4001  4058 I GFX raster: took 0.725678ms for 80*80 texture 0
,03-17 13:26:16.708  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76cf848 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb76edb20 counterpartCT=4 counterpartW=80 counterparth=80
,03-17 13:26:16.708  4001  4058 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 13:26:16.718  4459  4459 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 13:26:16.718  4459  4459 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,03-17 13:26:16.718  4459  4459 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 13:26:16.718  4459  4459 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-17 13:26:16.718  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.718  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.718  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.718  1018  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.728  4475  4475 E Zygote  : MountEmulatedStorage(),
03-17 13:26:16.728  4475  4475 E Zygote  : v2
03-17 13:26:16.728  4475  4475 I libpersona: KNOX_SDCARD checking this for 10148,
03-17 13:26:16.728  4475  4475 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:16.728  4475  4475 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:16.728  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
03-17 13:26:16.728  4001  4058 I GFX raster: took 0.647812ms for 80*80 texture 0
,03-17 13:26:16.728  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76edb20 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7374188 counterpartCT=4 counterpartW=80 counterparth=80
,03-17 13:26:16.728  4475  4475 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:16.738  4475  4475 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:16.738  1018  1489 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4475 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,03-17 13:26:16.738  4001  4058 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577,
,03-17 13:26:16.758  4475  4475 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:16.758  4475  4475 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.758  4001  4058 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
03-17 13:26:16.758  4001  4058 I GFX raster: took 0.634583ms for 80*80 texture 0
03-17 13:26:16.758  4001  4058 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76edb20 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb76ed7e0 counterpartCT=4 counterpartW=80 counterparth=80
,03-17 13:26:16.758  4001  4058 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature,
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-17 13:26:16.768  4001  4058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll,
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity,
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
,03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
,03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup,
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-17 13:26:16.768  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-17 13:26:16.798  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-17 13:26:16.798  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-17 13:26:16.798  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-17 13:26:16.798  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-17 13:26:16.798  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-17 13:26:16.798  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:16.798  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 13:26:16.798  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 13:26:16.798  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:16.798  4001  4058 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:16.798  4001  4058 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-17 13:26:16.798  4001  4058 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:16.798  4001  4058 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:16.798  4001  4058 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 13:26:16.798  4001  4058 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:16.798  4001  4058 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:16.798  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:16.808  4001  4058 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:16.818  4475  4475 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-17 13:26:16.828  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.828  1018  2825 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:16.828  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,03-17 13:26:16.838  4001  4058 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:16.838  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.838  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.838  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.838  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.848  4001  4058 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:16.848  4492  4492 E Zygote  : MountEmulatedStorage(),
03-17 13:26:16.848  4492  4492 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:16.848  4492  4492 E Zygote  : v2
03-17 13:26:16.848  4492  4492 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:16.848  4492  4492 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:16.858  1018  1571 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4492 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 13:26:16.858  4492  4492 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:16.858  4492  4492 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:16.868  4001  4058 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:16.868  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.868  1018  2826 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:16.868  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 13:26:16.878  1018  1510 I ActivityManager: Killing 3739:com.samsung.android.MtpApplication/1000 (adj 15): empty #31,
,03-17 13:26:16.888  3756  3871 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 13:26:16.888  4492  4492 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:16.888  4492  4492 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.898  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:16.908  4001  4058 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:16.908  1018  1510 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 13:26:16.918  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-17 13:26:16.918  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-17 13:26:16.918  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:16.918  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:16.918  4001  4058 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:16.918  1018  1510 I ActivityManager: Killing 3785:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,03-17 13:26:16.918  4001  4058 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:16.918  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:16.918  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.918  1018  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:16.918  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:16.918  4001  4058 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:16.928  4001  4058 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:16.938  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.938  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:16.938  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:16.948  1538  1538 I Hs20UtilService: Starting #5
,03-17 13:26:16.948  1538  1606 I Hs20UtilService: Message received 5007
,03-17 13:26:16.948  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 13:26:16.948  1303  1303 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:16.958  4001  4058 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:16.968  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.968  1018  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:16.968  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:16.968  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.968  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:16.968  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,03-17 13:26:16.968  4001  4058 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:16.978  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 13:26:16.978  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 13:26:16.978  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:16.978  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:16.978  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:16.988  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 13:26:16.988  1823  1823 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,03-17 13:26:16.988  4001  4058 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:16.988  1823  1823 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 13:26:16.988  1823  1823 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-17 13:26:16.998  1823  1823 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,03-17 13:26:16.998  1823  1823 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 13:26:16.998  1823  1823 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 13:26:16.998  1823  1823 D daemonapp: [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,03-17 13:26:16.998  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-17 13:26:16.998  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-17 13:26:16.998  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-17 13:26:16.998  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-17 13:26:16.998  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:16.998  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:16.998  4001  4058 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:16.998  4001  4058 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:16.998  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:16.998  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 13:26:16.998  4001  4058 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:16.998  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 13:26:17.018  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 13:26:17.018  1018  1098 V AlarmManager: waitForAlarm result :4
03-17 13:26:17.018  4001  4058 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:17.028  1823  1823 D daemonapp: [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,03-17 13:26:17.028  1018  1098 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.028  1018  1098 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.028  1018  1098 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.028  1018  1098 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.038  4510  4510 E Zygote  : MountEmulatedStorage()
,03-17 13:26:17.038  4510  4510 E Zygote  : v2
03-17 13:26:17.038  4510  4510 I libpersona: KNOX_SDCARD checking this for 10117
03-17 13:26:17.038  4510  4510 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:17.038  4510  4510 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 13:26:17.048  4510  4510 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:17.048  1018  1098 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService: pid=4510 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-17 13:26:17.048  4001  4058 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-17 13:26:17.048  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.048  1018  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.048  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.058  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.058  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.058  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.058  4510  4510 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:17.058  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.058  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.058  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-17 13:26:17.068  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.068  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.068  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.078  4001  4058 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
03-17 13:26:17.078  4510  4510 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:17.078  4510  4510 D ActivityThread: Added TimaKeyStore provider,
03-17 13:26:17.078  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.088  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.088  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.088  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.088  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:17.088  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.098  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.098  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.098  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.098  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:17.098  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-17 13:26:17.108  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.108  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.108  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.108  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.108  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.108  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.118  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.118  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.118  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.118  4510  4510 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:17.118  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.118  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.118  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.118  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.118  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.118  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.128  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.128  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.128  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.128  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.128  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.128  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.128  4001  4058 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:17.128  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.128  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.128  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.138  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.138  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.138  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.138  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.138  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.138  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.138  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.138  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.138  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.148  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.148  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.148  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.148  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.148  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.148  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.148  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.148  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.148  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.158  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.158  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.158  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.158  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.158  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.158  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.158  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.158  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.158  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.168  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.168  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.168  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.168  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.168  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.168  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.168  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.168  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.168  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.178  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.178  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.178  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.188  1018  1575 W ActivityManager: userId = 0, bbcId = -10000,
,03-17 13:26:17.188  1018  1575 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
03-17 13:26:17.188  1018  1575 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
03-17 13:26:17.188  1538  1538 I Hs20UtilService: Starting #6
03-17 13:26:17.188  1538  1606 I Hs20UtilService: Message received 5007
,03-17 13:26:17.188  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
03-17 13:26:17.188  1303  1303 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
03-17 13:26:17.188  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 13:26:17.188  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-17 13:26:17.188  1303  1303 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,03-17 13:26:17.188  1303  1303 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:17.208  1018  1241 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.208  1018  1241 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.208  1018  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:17.208  1303  1303 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 13:26:17.208  1538  1538 I Hs20UtilService: Starting #7
,03-17 13:26:17.208  1303  1303 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:17.208  1538  1606 I Hs20UtilService: Message received 5007
,03-17 13:26:17.228  1018  1510 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0,
,03-17 13:26:17.238  1018  2826 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-17 13:26:17.238  1018  2826 D SecContentProvider2: mCursor = null
,03-17 13:26:17.238  1018  1327 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-17 13:26:17.238  1018  1327 D SecContentProvider2: mCursor = null
,03-17 13:26:17.238  1018  1569 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,03-17 13:26:17.238  1018  1569 D SecContentProvider2: mCursor = null
,03-17 13:26:17.238  1018  1139 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,03-17 13:26:17.238  1018  1139 D SecContentProvider2: mCursor = null
,03-17 13:26:17.248  1018  1571 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-17 13:26:17.248  1018  1571 D SecContentProvider2: mCursor = null
,03-17 13:26:17.248  1018  1241 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
03-17 13:26:17.248  1018  1241 D SecContentProvider2: mCursor = null
,03-17 13:26:17.258  4333  4333 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-17 13:26:17.258  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.258  1018  1573 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.258  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 13:26:17.258  1018  1030 I ActivityManager: Killing 3444:com.sec.pcw.device/1000 (adj 15): empty #31
,03-17 13:26:17.278  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.278  1018  1498 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:17.278  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.288  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,03-17 13:26:17.288  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.288  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:17.288  4001  4058 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:17.288  4001  4058 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:17.288  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:17.298  4001  4058 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:17.308  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.308  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.308  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.308   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,03-17 13:26:17.308  4001  4058 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:17.318  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.318  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.318  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.318  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.328  1018  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-17 13:26:17.328  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:17.328  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.338  4001  4058 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:17.348  1018  1030 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,03-17 13:26:17.348  1018  1052 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
,03-17 13:26:17.348  1018  1052 D DisplayPowerController: animation target = 31, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:17.348  1018  1052 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 13:26:17.358  4001  4058 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:17.358  1018  1052 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
03-17 13:26:17.358  1018  1158 D lights  : lcd : 31 +
,03-17 13:26:17.358  1018  1052 D DisplayPowerController: animation target = 31, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:17.368  1174  1174 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 13:26:17.368  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.368  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.368  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
03-17 13:26:17.368  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.378  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.378  1018  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:17.378  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-17 13:26:17.378  1018  1158 D lights  : lcd : 31 -
,03-17 13:26:17.378  1018  1052 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
,03-17 13:26:17.378  1018  1052 D DisplayPowerController: animation target = 31, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:17.378  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.378  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.378  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.388  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.388  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.388  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.388  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.388  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.388  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:17.398  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.398  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.398  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 13:26:17.398  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3739/cgroup.procs: No such file or directory
,03-17 13:26:17.398  1018  1043 W libprocessgroup: failed to open /acct/uid_10058/pid_3785/cgroup.procs: No such file or directory
03-17 13:26:17.398  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3444/cgroup.procs: No such file or directory
,03-17 13:26:17.428  4001  4058 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:17.428  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.428  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.428  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.428  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.438  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-17 13:26:17.438  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.438  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:17.438  4001  4058 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:17.438  4001  4058 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:17.438  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:17.438  4001  4058 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:17.448  4533  4533 E Zygote  : MountEmulatedStorage()
,03-17 13:26:17.448  4533  4533 E Zygote  : v2
,03-17 13:26:17.448  4533  4533 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:17.448  4533  4533 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:17.448  4533  4533 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:17.448  1477  4530 D SIP     : [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,03-17 13:26:17.458  4533  4533 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 13:26:17.458  1018  1569 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4533 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-17 13:26:17.458  4533  4533 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:17.468  1477  4530 E File    : fail readDirectory() errno=2
,03-17 13:26:17.468  4001  4058 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:17.478  4001  4058 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:17.498  4001  4058 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:17.498  4533  4533 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:17.498  4533  4533 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:17.518  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:17.548  4001  4058 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:17.548  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
03-17 13:26:17.548  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.548  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:17.548  4001  4058 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:17.548  4001  4058 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:17.548  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
03-17 13:26:17.548  4533  4533 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 13:26:17.548  4533  4533 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-17 13:26:17.548  4533  4533 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 13:26:17.558  4001  4058 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:17.568  4001  4058 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:17.578  4533  4533 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 13:26:17.578  4533  4533 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 13:26:17.578  4533  4533 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 13:26:17.578  4533  4533 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:17.578  1018  1569 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
03-17 13:26:17.578  1018  1569 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,03-17 13:26:17.578  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.578  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.578  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.578  1018  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.578  4001  4058 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:17.598  4558  4558 E Zygote  : MountEmulatedStorage(),
03-17 13:26:17.598  4558  4558 E Zygote  : v2
03-17 13:26:17.598  4558  4558 I libpersona: KNOX_SDCARD checking this for 10108
03-17 13:26:17.598  4558  4558 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:17.598  1018  1569 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4558 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:17.598  4558  4558 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:17.608  4558  4558 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:17.608  4001  4058 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:17.608  4558  4558 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:17.618  3649  3649 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 13:26:17 GMT+01:00 2016
,03-17 13:26:17.618  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.618  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.618  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.618  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.628  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:17.628  4558  4558 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:17.628  4558  4558 D ActivityThread: Added TimaKeyStore provider,
03-17 13:26:17.638  1764  1764 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 13:26:17.638  1018  1044 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=4567 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,03-17 13:26:17.638  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.638  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.638  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 13:26:17.648  4567  4567 E Zygote  : MountEmulatedStorage()
,03-17 13:26:17.648  4567  4567 E Zygote  : v2
03-17 13:26:17.648  4567  4567 I libpersona: KNOX_SDCARD checking this for 10141
,03-17 13:26:17.648  4567  4567 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:17.648  4567  4567 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:17.648  4567  4567 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:17.648  4567  4567 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:17.658  3649  3649 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-17 13:26:17.668  1823  1833 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,03-17 13:26:17.668  4001  4058 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:17.678  1764  1764 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-17 13:26:17.678  1764  1764 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
03-17 13:26:17.678  1764  1764 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-17 13:26:17.678  1764  1764 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity,
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-17 13:26:17.698  4001  4058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
,03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
,03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
,03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
,03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
,03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog,
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
,03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
,03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
,03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity,
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
,03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-17 13:26:17.698  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
03-17 13:26:17.698  3649  3649 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-17 13:26:17.708  1018  1031 I art     : Explicit concurrent mark sweep GC freed 33959(1955KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 24MB/36MB, paused 12.069ms total 173.822ms
03-17 13:26:17.708  3649  3649 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 13:26:17.718  4567  4567 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:17.718  4567  4567 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:17.718  3649  3649 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 13:26:17.728  3649  4585 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 13:26:17.728  1764  1764 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 13:26:17.728  3649  4585 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-17 13:26:17.738  4124  4124 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:17.738  1764  1764 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 13:26:17.748  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-17 13:26:17.748  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.748  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:17.748  4001  4058 I AMMetaDataParserService: Resource data:2131165197
,03-17 13:26:17.748  3649  4585 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-17 13:26:17.748  3649  4585 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,03-17 13:26:17.748  1018  2826 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.758  1018  2826 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.758  1018  2826 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.758  1018  2826 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.758  4001  4058 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:17.758  4001  4058 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:17.758  4001  4058 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:17.758  4001  4058 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 13:26:17.758  4001  4058 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 13:26:17.758  4001  4058 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 13:26:17.758  4001  4058 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:17.758  4001  4058 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 13:26:17.758  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:17.768  3649  4585 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,03-17 13:26:17.768  4567  4567 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 13:26:17.768  4590  4590 E Zygote  : MountEmulatedStorage()
03-17 13:26:17.768  4590  4590 I libpersona: KNOX_SDCARD checking this for 10077
03-17 13:26:17.768  4590  4590 E Zygote  : v2
03-17 13:26:17.768  4590  4590 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:17.768  4567  4567 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:17.768  4567  4567 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:17.768  4567  4567 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:17.778  4590  4590 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:17.778  4590  4590 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:17.778  4590  4590 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-17 13:26:17.788  1018  2826 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4590 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:17.828  4590  4590 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:17.828  4590  4590 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:17.828  4124  4589 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 13:26:17.828  4124  4589 I DBG_POLICYDM: [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,03-17 13:26:17.838  3649  4585 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END ,
,03-17 13:26:17.848  4124  4589 E DBG_POLICYDM: [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... ,
,03-17 13:26:17.848  4124  4181 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:17.848  3649  4585 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,03-17 13:26:17.858  4001  4058 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625,
,03-17 13:26:17.858  4205  4205 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false,
03-17 13:26:17.868  3649  3649 I KLMS-2.5.123: : KLMSIntentService(): onDestroy(),
,03-17 13:26:17.878  4278  4278 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,03-17 13:26:17.878  4278  4278 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-17 13:26:17.878  4278  4278 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-17 13:26:17.888  4001  4058 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 13:26:17.898  4124  4589 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO,
,03-17 13:26:17.908  4124  4181 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] ,
,03-17 13:26:17.918  4124  4181 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy,
,03-17 13:26:17.918  4124  4181 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
03-17 13:26:17.918  4124  4181 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
03-17 13:26:17.918  4124  4181 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
03-17 13:26:17.918  4124  4181 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 13:26:17.928  4124  4181 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 13:26:17.938  1018  2825 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:17.938  1018  1139 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:17.948  1018  1571 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:17.958  1018  1498 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:17.998  1018  1241 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:18.008  1018  1575 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:18.008  4124  4589 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 13:26:18.008  4124  4589 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 13:26:18.008  4124  4589 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 13:26:18.018  4124  4589 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 13:26:18.018  4124  4589 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 13:26:18.018  4124  4589 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 13:26:18.018  4124  4589 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 13:26:18.018  4124  4589 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-17 13:26:18.018  4124  4589 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-17 13:26:18.018  4403  4413 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 13:26:18.028  4124  4589 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,03-17 13:26:18.038  4124  4589 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 13:26:18.038  4124  4589 I DBG_POLICYDM: [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,03-17 13:26:18.058  1499  1499 D Launcher.Model: reloadBadges entered.
,03-17 13:26:18.058  4403  4413 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 13:26:18.058  4403  4413 D BadgeProvider: sendNotify, [notify] : null
03-17 13:26:18.058  4403  4413 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 13:26:18.058  4403  4413 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 13:26:18.058  4403  4413 D BadgeProvider: update, [UpdateCount] : 1
,03-17 13:26:18.098  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,03-17 13:26:18.128  4278  4278 I SA      : [SLFUCHKMGR] constructor called
,03-17 13:26:18.128  4278  4278 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 13:26:18.128  4278  4278 I SA      : [OR] == isSIMCardReady false ==
,03-17 13:26:18.158  1018  1489 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 13:26:18.198  4558  4558 I MusicStore: Database version: 104
,03-17 13:26:18.198  4278  4278 I SA      : [SCU] == networkStateCheck == true
,03-17 13:26:18.198  4278  4278 I SA      : [DM] getCountryCodeFromCSC : PL
,03-17 13:26:18.208  4278  4278 I SA      : isChinaCountryCode : false
03-17 13:26:18.208  4278  4278 I SA      : [SCU] is ChinestModel Data Restricted   : false
,03-17 13:26:18.208  4278  4278 I SA      : [OR] == networkStateCheck true ==
,03-17 13:26:18.218  1018  1573 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:18.218  1018  1498 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:18.228  4459  4459 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 13:26:18.228  4459  4459 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 13:26:18.228  4278  4278 I SA      : [OR] GetMyCountryZoneTask
,03-17 13:26:18.228  4278  4278 I SA      : [OR] onReceive END
03-17 13:26:18.228  4459  4459 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 13:26:18.228  1018  1489 I ActivityManager: Killing 3813:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-17 13:26:18.228  4459  4459 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-17 13:26:18.238  1215  1215 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:18.238  1018  1489 I ActivityManager: Killing 3667:com.android.vending/u0a26 (adj 15): empty #31
,03-17 13:26:18.248  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.248  1018  2826 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:18.248  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 13:26:18.258  1018  1577 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,03-17 13:26:18.258  1018  1577 D SecContentProvider2: mCursor = null
,03-17 13:26:18.268  4278  4622 I SA      : [SRS] prepareGetMyCountryZone
,03-17 13:26:18.278  4001  4058 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 13:26:18.288  4278  4622 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 13:26:18.288  4278  4622 I SA      : [SSP] query invoked
,03-17 13:26:18.288  4278  4622 I SA      : [TPMU] GetMccFromDB : null
,03-17 13:26:18.298  4278  4622 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-17 13:26:18.298  4278  4622 I SA      : [TPM] isNoProxy(default) : true
,03-17 13:26:18.338  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:18.338  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.338  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.338  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:18.338  4278  4622 E File    : fail readDirectory() errno=2
,03-17 13:26:18.348  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 13:26:18.358  4630  4630 E Zygote  : MountEmulatedStorage(),
03-17 13:26:18.358  4630  4630 E Zygote  : v2
03-17 13:26:18.358  4630  4630 I libpersona: KNOX_SDCARD checking this for 10110
03-17 13:26:18.358  4630  4630 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:18.358  4630  4630 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:18.368  1018  1575 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4630 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:18.368  4630  4630 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:18.368  4630  4630 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:18.368  1018  1575 I ActivityManager: Killing 3179:com.test.thalitest/u0a167 (adj 15): empty #31
,03-17 13:26:18.368  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-17 13:26:18.368  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.368  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:18.368  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:18.368  4001  4058 I AMMetaDataParserService: Resource data:2131165197
,03-17 13:26:18.368  4001  4058 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
,03-17 13:26:18.368  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:18.378  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.378  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:18.378  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:18.388  4630  4630 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:18.388  4630  4630 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:18.418  4001  4058 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 13:26:18.428  4001  4058 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 13:26:18.438  1018  1043 W libprocessgroup: failed to open /acct/uid_10026/pid_3667/cgroup.procs: No such file or directory
,03-17 13:26:18.438  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3813/cgroup.procs: No such file or directory
,03-17 13:26:18.438  1018  1043 W libprocessgroup: failed to open /acct/uid_10167/pid_3179/cgroup.procs: No such file or directory
,03-17 13:26:18.488  2135  4648 I iu.SyncManager: SYNC; picasa accounts
,03-17 13:26:18.558  2135  2135 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-17 13:26:18.568  2135  2135 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-17 13:26:18.578  4001  4058 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622,
,03-17 13:26:18.588  2135  4648 I iu.UploadsManager: num queued entries: 0
,03-17 13:26:18.588  2135  4648 I iu.UploadsManager: num updated entries: 0
,03-17 13:26:18.588  2135  4648 I iu.SyncManager: NEXT; no task
,03-17 13:26:18.598  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.598  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:18.598  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.598  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 13:26:18.598  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.598  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:18.598  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
03-17 13:26:18.608  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-17 13:26:18.608  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.608  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:18.608  4001  4058 I AMMetaDataParserService: Resource data:2131165197
,03-17 13:26:18.608  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.608  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.608  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.608  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:18.608  4001  4058 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 13:26:18.608  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:18.618  4651  4651 E Zygote  : MountEmulatedStorage(),
03-17 13:26:18.618  4651  4651 E Zygote  : v2
03-17 13:26:18.618  4651  4651 I libpersona: KNOX_SDCARD checking this for 10009
03-17 13:26:18.618  4651  4651 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:18.618  4651  4651 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:18.618  1018  1575 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4651 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 13:26:18.628  4651  4651 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:18.628  4651  4651 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,03-17 13:26:18.628  4558  4558 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
03-17 13:26:18.628  4558  4558 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 13:26:18.638  4001  4058 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 13:26:18.648   305   305 I art     : Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 29.377ms
,03-17 13:26:18.658  4651  4651 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:18.658  4651  4651 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:18.668   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 20.225ms
,03-17 13:26:18.678  4001  4058 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 13:26:18.688   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 17.004ms
,03-17 13:26:18.698  4558  4558 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 13:26:18.798  4001  4058 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 13:26:18.808  4558  4558 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 13:26:18.808  4558  4558 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@378f89f3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 13:26:18.808  4558  4558 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 13:26:18.808  4558  4558 D AndroidMusic: GMSCore installation verified
,03-17 13:26:18.838  4651  4651 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-17 13:26:18.868  4001  4058 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624,
,03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-17 13:26:18.898  4001  4058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:18.898  4001  4058 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:18.918  4001  4058 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,03-17 13:26:18.918  4001  4058 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 13:26:18.918  4001  4058 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,03-17 13:26:18.918  4001  4058 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 13:26:18.918  4001  4058 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:18.918  4001  4058 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
,03-17 13:26:18.918  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:18.928  4001  4058 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-17 13:26:18.938  1018  1571 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.938  1018  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:18.938  1018  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:18.948  4558  4558 I ConfigStore: Config Database version: 1
,03-17 13:26:18.958  4651  4651 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-17 13:26:18.958  1018  1139 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-17 13:26:18.988  4001  4058 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-17 13:26:19.008  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-17 13:26:19.008  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-17 13:26:19.008  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-17 13:26:19.008  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
03-17 13:26:19.008  4001  4058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 13:26:19.038   258   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 13:26:19.038   258   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:19.048  4630  4671 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 13:26:19.048   258   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 13:26:19.048   258   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:19.048  4630  4671 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 13:26:19.058  1018  1345 E Watchdog: !@Sync 1
,03-17 13:26:19.088  1018  1138 D SettingsProvider: name = audio_safe_volume_state
,03-17 13:26:19.098  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-17 13:26:19.098  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.098  4001  4058 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:19.098  4001  4058 I AMMetaDataParserService: Resource data:2131165220
,03-17 13:26:19.108  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-17 13:26:19.108   258   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 13:26:19.108   258   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:19.108  4558  4558 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 13:26:19.108  4001  4058 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 13:26:19.108  4001  4058 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:19.108  4001  4058 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:19.108  4001  4058 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:19.108  4001  4058 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:19.108  4001  4058 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 13:26:19.108  4001  4058 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-17 13:26:19.108  4001  4058 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:19.118  4001  4058 I AMMetaDataParserService: Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,03-17 13:26:19.128  4001  4058 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-17 13:26:19.138   258   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 13:26:19.138   258   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:19.138  4630  4679 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 13:26:19.148   258   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 13:26:19.148   258   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:19.148  4630  4679 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 13:26:19.148   258   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 13:26:19.148   258   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:19.148  4558  4558 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 13:26:19.168   258   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 13:26:19.168   258   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:19.168  4558  4558 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
,03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activi,tycom.android.settings.wifi.WifiWarningDialog
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
,03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
,03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
,03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-17 13:26:19.198  4001  4058 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.178  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-17 13:26:19.248  1018  1489 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-17 13:26:19.258  1018  1577 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.188  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-17 13:26:19.198  4001  4058 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-17 13:26:19.198  1018  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.198  1018  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:19.198  1018  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
03-17 13:26:19.238  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.238  1018  1498 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-17 13:26:19.238  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
03-17 13:26:19.238  4651  4651 D hcjo    : AutoUpdateManager:IDLE:execute
03-17 13:26:19.258  4651  4651 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
03-17 13:26:19.258  4651  4651 D InitializeManagerStateMachine: exit::IDLE
03-17 13:26:19.258  4651  4651 D InitializeManagerStateMachine: entry::NETWORK_CHECK
03-17 13:26:19.258  4651  4651 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
03-17 13:26:19.258  4651  4651 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-17 13:26:19.258  4651  4651 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-17 13:26:19.258  4651  4651 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-17 13:26:19.258  4651  4651 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-17 13:26:19.258  4651  4651 D InitializeManagerStateMachine: entry::SUCCESS
03-17 13:26:19.258  4651  4651 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
03-17 13:26:19.258  1018  1139 I AudioService: getStreamVolume 3 index 0
03-17 13:26:19.258  4558  4558 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
03-17 13:26:19.268  4651  4651 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
03-17 13:26:19.278  4651  4651 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
03-17 13:26:19.278  4651  4651 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
03-17 13:26:19.278  4651  4651 D InitializeManagerStateMachine: exit::SUCCESS
03-17 13:26:19.278  4651  4651 D InitializeManagerStateMachine: entry::IDLE
03-17 13:26:19.278  1018  2825 I ActivityManager: Killing 3852:com.wssnps/1000 (adj 15): empty #31
03-17 13:26:19.288  4558  45,58 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 13:26:19.298  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.298  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.298  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.298  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.318  4694  4694 E Zygote  : MountEmulatedStorage()
03-17 13:26:19.318  4694  4694 E Zygote  : v2
03-17 13:26:19.318  4694  4694 I libpersona: KNOX_SDCARD checking this for 10001
03-17 13:26:19.318  4694  4694 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:19.318  4694  4694 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:19.318  4694  4694 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:19.318  4694  4694 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:19.328  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4694 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:19.338  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3852/cgroup.procs: No such file or directory
,03-17 13:26:19.338  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.338  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:19.338  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-17 13:26:19.338  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.348  1018  2825 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:19.348  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.358  4694  4694 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:19.358  4694  4694 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:19.368  1018  1573 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:19.378  4558  4558 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 13:26:19.388  1018  1510 I ActivityManager: Killing 3872:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,03-17 13:26:19.408  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:19.408  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:19.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:19.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:19.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:19.408  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:19.458  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3872/cgroup.procs: No such file or directory
,03-17 13:26:19.458  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.458  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.458  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.458  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.468  4714  4714 E Zygote  : MountEmulatedStorage()
,03-17 13:26:19.468  4714  4714 E Zygote  : v2
03-17 13:26:19.468  4714  4714 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:19.468  4714  4714 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:19.468  4714  4714 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:19.478   290   290 E SMD     : DCD OFF
,03-17 13:26:19.478  4714  4714 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:19.478  1018  1327 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4714 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:19.478  4714  4714 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:19.478  1018  1327 I ActivityManager: Killing 3901:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,03-17 13:26:19.498  4714  4714 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:19.498  4714  4714 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:19.548  4630  4630 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-17 13:26:19.548  4714  4714 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 13:26:19.558  4630  4630 I LibraryLoader: Loading: webviewchromium
,03-17 13:26:19.568  4630  4630 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9337-9342)
,03-17 13:26:19.568  4630  4630 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 13:26:19.578  4630  4630 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2a71dee5}
,03-17 13:26:19.578  4630  4630 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 13:26:19.578  4630  4630 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 13:26:19.608  1018  1043 W libprocessgroup: failed to open /acct/uid_10065/pid_3901/cgroup.procs: No such file or directory
,03-17 13:26:19.608  4630  4630 I BrowserStartupController: Initializing chromium process, renderers=0
,03-17 13:26:19.608  4630  4630 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:26:19.628  4630  4630 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-17 13:26:19.628  4630  4630 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,03-17 13:26:19.628  4630  4630 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,03-17 13:26:19.648  4630  4630 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 13:26:19.648  4630  4630 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 13:26:19.648  4630  4630 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 13:26:19.648  4630  4630 I Adreno-EGL: Local Branch: 
03-17 13:26:19.648  4630  4630 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 13:26:19.648  4630  4630 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 13:26:19.648  4630  4630 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 13:26:19.658  4630  4734 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-17 13:26:19.718  4630  4630 I NSApplication: Starting up...
,03-17 13:26:19.738  4714  4714 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 13:26:19.738  1018  2825 I ActivityManager: Killing 3925:com.google.android.talk/u0a102 (adj 15): empty #31
,03-17 13:26:19.738  1018  2825 I ActivityManager: Killing 3756:com.google.android.gm/u0a99 (adj 15): empty #32
,03-17 13:26:19.768  4714  4714 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 13:26:19.768  4714  4714 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:19.768  4714  4714 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 13:26:19.768  4714  4714 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-17 13:26:19.768  4714  4714 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 13:26:19.808  4233  4233 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:19.808  4233  4233 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
03-17 13:26:19.808  4233  4233 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 13:26:19.848  4124  4146 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:19.848  4124  4146 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:19.848  4124  4146 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 13:26:19.858  4124  4137 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:19.858  4124  4137 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 13:26:19.858  4124  4137 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 13:26:19.858  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.858  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.858  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.858  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.868  1018  1043 W libprocessgroup: failed to open /acct/uid_10099/pid_3756/cgroup.procs: No such file or directory
,03-17 13:26:19.868  1018  1043 W libprocessgroup: failed to open /acct/uid_10102/pid_3925/cgroup.procs: No such file or directory
,03-17 13:26:19.878  4749  4749 E Zygote  : MountEmulatedStorage(),
03-17 13:26:19.878  4749  4749 E Zygote  : v2
03-17 13:26:19.878  4749  4749 I libpersona: KNOX_SDCARD checking this for 10008
03-17 13:26:19.878  4749  4749 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:19.878  4749  4749 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:19.878  4749  4749 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 13:26:19.878  4749  4749 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 13:26:19.878  1018  1031 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4749 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:19.898  4749  4749 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:19.898  4749  4749 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:19.958  4278  4622 I SA      : [RC New] Execute method=[GET] start
,03-17 13:26:19.968  1018  1571 I ActivityManager: Killing 3831:com.vlingo.midas/u0a28 (adj 15): empty #31
,03-17 13:26:19.988  4749  4749 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 13:26:19.998  4749  4749 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 13:26:19.998  4749  4749 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 13:26:19.998  4749  4749 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 13:26:19.998  1018  1577 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,03-17 13:26:19.998  1018  1577 I ActivityManager: Killing 4022:com.samsung.helphub/1000 (adj 15): empty #31
,03-17 13:26:20.008  1018  1018 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,03-17 13:26:20.008  1018  1018 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-17 13:26:20.008  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.008  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.008  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.008  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.018  4278  4622 I SA      : [RC New] Security=[true],
03-17 13:26:20.018  4278  4622 I System.out: Thread-640(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 13:26:20.018  4278  4622 I System.out: Thread-640(ApacheHTTPLog):isSBSettingEnabled false
,03-17 13:26:20.018  4278  4622 I System.out: Thread-640(ApacheHTTPLog):isShipBuild true
03-17 13:26:20.018  4278  4622 I System.out: Thread-640(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 13:26:20.018  4278  4622 I System.out: Thread-640(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 13:26:20.028   280   955 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 13:26:20.028   280   955 D Netd    : getNetworkForDns: using netid 502 for uid 10036
,03-17 13:26:20.028  4767  4767 E Zygote  : MountEmulatedStorage()
03-17 13:26:20.028  1018  1044 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4767 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:20.028  4767  4767 E Zygote  : v2
03-17 13:26:20.028  4767  4767 I libpersona: KNOX_SDCARD checking this for 10058
03-17 13:26:20.028  4767  4767 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:20.028  4767  4767 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:20.038  4767  4767 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:20.038  4749  4749 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 13:26:20.038  4767  4767 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 13:26:20.048  1018  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.048  1018  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:20.048  1018  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
03-17 13:26:20.048  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 13:26:20.048  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 13:26:20.048  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:20.058  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:20.058  4749  4749 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-17 13:26:20.068  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 13:26:20.068  4767  4767 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:20.068  4767  4767 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:20.068  1823  1823 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
03-17 13:26:20.068  1823  1823 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 13:26:20.068  1823  1823 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 13:26:20.068  1823  1823 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 13:26:20.068  1823  1823 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 13:26:20.068  1823  1823 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-17 13:26:20.068  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 13:26:20.078  3649  3649 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Mar 17 13:26:20 GMT+01:00 2016
03-17 13:26:20.078  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 13:26:20.078  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.078  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:20.078  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 13:26:20.078  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:20.078  1018  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:20.078  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
03-17 13:26:20.078  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 13:26:20.088  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 13:26:20.088  1823  1823 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 13:26:20.088  1823  1823 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 13:26:20.088  3649  3649 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-17 13:26:20.098  4459  4459 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 13:26:20.098  4459  4459 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 13:26:20.098  4459  4459 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 13:26:20.098  1018  1043 W libprocessgroup: failed to open /acct/uid_10028/pid_3831/cgroup.procs: No such file or directory
03-17 13:26:20.098  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4022/cgroup.procs: No such file or directory
,03-17 13:26:20.098  1823  1823 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 13:26:20.098  4278  4278 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,03-17 13:26:20.108  3649  3649 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-17 13:26:20.108  3649  3649 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 13:26:20.108  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,03-17 13:26:20.118  1823  1823 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,03-17 13:26:20.118  1823  1823 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 13:26:20.128  4767  4767 I ExternalOEMControlProvider: onCreate
,03-17 13:26:20.128  3649  3649 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 13:26:20.138  3649  4785 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-17 13:26:20.138  3649  4785 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,03-17 13:26:20.138  3649  4785 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Thu Mar 17 13:26:20 GMT+01:00 2016
,03-17 13:26:20.138  3649  4785 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,03-17 13:26:20.148  3649  3649 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-17 13:26:20.238  2954  4394 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-17 13:26:20.248  1018  1573 I art     : Explicit concurrent mark sweep GC freed 22395(1338KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 2.465ms total 138.937ms
,03-17 13:26:20.258  3224  3224 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,03-17 13:26:20.258  3224  3224 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,03-17 13:26:20.258  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.258  3224  3224 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,03-17 13:26:20.258  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.258  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.258  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.268  1018  2865 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:20.278  4788  4788 E Zygote  : MountEmulatedStorage()
03-17 13:26:20.278  4788  4788 I libpersona: KNOX_SDCARD checking this for 10153
03-17 13:26:20.278  4788  4788 E Zygote  : v2
,03-17 13:26:20.278  4788  4788 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:20.278  4788  4788 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:20.278  1018  1575 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4788 uid=10153 gids={50153, 9997} abi=armeabi-v7a
03-17 13:26:20.278  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.278  4788  4788 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:20.278  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:20.278  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:20.288  4788  4788 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:20.288  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-17 13:26:20.288  2954  2954 I Process : Sending signal. PID: 2954 SIG: 9
,03-17 13:26:20.298  4767  4787 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-17 13:26:20.298  1764  1764 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-17 13:26:20.298  1764  1764 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 13:26:20.298  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.298  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.298  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.298  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.318  4802  4802 E Zygote  : MountEmulatedStorage()
03-17 13:26:20.318  4802  4802 I libpersona: KNOX_SDCARD checking this for 10041
03-17 13:26:20.318  4802  4802 E Zygote  : v2
03-17 13:26:20.318  4802  4802 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:20.318  4802  4802 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:20.318  4802  4802 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:20.318  4802  4802 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 13:26:20.318  1018  1575 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4802 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,03-17 13:26:20.328  4788  4788 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:20.328  4788  4788 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:20.338  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.338  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.338  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.338  1018  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.348  4802  4802 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:20.348  4802  4802 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:20.358  4818  4818 E Zygote  : MountEmulatedStorage()
,03-17 13:26:20.358  4818  4818 E Zygote  : v2
03-17 13:26:20.358  4818  4818 I libpersona: KNOX_SDCARD checking this for 10081
03-17 13:26:20.358  4818  4818 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:20.358  1018  1575 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4818 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:20.358  4818  4818 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:20.358  4818  4818 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:20.368  4818  4818 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:20.368  4788  4788 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:20.378  4802  4802 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-17 13:26:20.378  4802  4802 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:20.378  4802  4802 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:20.378  4802  4802 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:20.378  4802  4802 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:20.378  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.378  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:20.378  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:20.388  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.388  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.388  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.388  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.398  4818  4818 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:20.398  4818  4818 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:20.418  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
03-17 13:26:20.418  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:20.418  4835  4835 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:20.418  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:20.418  4835  4835 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:20.418  4835  4835 E Zygote  : MountEmulatedStorage()
03-17 13:26:20.418  4835  4835 E Zygote  : v2
03-17 13:26:20.418  4835  4835 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:20.418  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:20.418  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:20.418  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:20.418  1018  1327 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4835 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
03-17 13:26:20.418  4835  4835 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:20.418  1018  1327 I ActivityManager: Killing 4001:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
03-17 13:26:20.428  4835  4835 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 13:26:20.438  1018  2826 I ActivityManager: Process com.sec.android.app.sysscope (pid 2954)(adj 0) has died(58,618)
,03-17 13:26:20.458  4835  4835 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:20.458  4835  4835 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:20.468  4818  4818 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:20.468  4818  4818 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:20.468  4818  4818 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:20.468  4818  4818 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:20.468  4818  4818 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-17 13:26:20.468  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4001/cgroup.procs: No such file or directory
,03-17 13:26:20.558  4835  4835 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458217580571
,03-17 13:26:20.558  4835  4835 D         : TimeServiceNative: User Time to be set is 1458217580571
,03-17 13:26:20.558  4835  4835 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
,03-17 13:26:20.558  4835  4835 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-17 13:26:20.558  4802  4802 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
03-17 13:26:20.558  4835  4835 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458217580571
,03-17 13:26:20.558   318   553 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-17 13:26:20.558  4835  4835 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-17 13:26:20.558   318  4850 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458217580571
03-17 13:26:20.558   318  4850 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458217580571, operation = 0
,03-17 13:26:20.558   318  4850 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/12/70 16:2:59
,03-17 13:26:20.568   318  4850 D QC-time-services: Daemon:Value read from RTC seconds = 22003379000
,03-17 13:26:20.568   318  4850 D QC-time-services: Daemon:new time 1458217580571 
03-17 13:26:20.568   318  4850 D QC-time-services: Daemon: delta 1436214201571 genoff 1436214201571 
03-17 13:26:20.568   318  4850 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214201571 to memory
03-17 13:26:20.568   318  4850 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-17 13:26:20.568   318  4850 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 13:26:20.578   318  4850 D QC-time-services: Updating the TOD offset
03-17 13:26:20.578   318  4850 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214201571 to memory
03-17 13:26:20.578   318  4850 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-17 13:26:20.578   318  4850 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 13:26:20.588   318  4850 E QC-time-services: Daemon:Update to modem bit set
03-17 13:26:20.588  4835  4835 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-17 13:26:20.588   318  4850 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-17 13:26:20.588   318  4850 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120249401571
,03-17 13:26:20.588   318   551 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-17 13:26:20.588  1018  1498 I ActivityManager: Killing 4115:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
03-17 13:26:20.588   318   553 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-17 13:26:20.598  1018  1571 D SettingsProvider: name = next_alarm_formatted
,03-17 13:26:20.598  1018  1571 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:20.598  1018  1571 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:20.598  1018  1571 D SettingsProvider: selectionArgs: false
03-17 13:26:20.598  1018  1571 D SettingsProvider: selectionArgs: 10081
03-17 13:26:20.598  1018  1571 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:20.598  1018  1571 D SettingsProvider: ret = -1
,03-17 13:26:20.618  1018  1575 I ActivityManager: Killing 4089:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-17 13:26:20.718  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4115/cgroup.procs: No such file or directory,
,03-17 13:26:20.718  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4089/cgroup.procs: No such file or directory
,03-17 13:26:20.738  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.738  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.738  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.738  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.758  4851  4851 E Zygote  : MountEmulatedStorage()
,03-17 13:26:20.758  4851  4851 E Zygote  : v2
03-17 13:26:20.758  4851  4851 I libpersona: KNOX_SDCARD checking this for 10090
03-17 13:26:20.758  4851  4851 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:20.758  4851  4851 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:20.758  1018  1031 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4851 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
,03-17 13:26:20.758  1018  1031 I ActivityManager: Killing 4154:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 13:26:20.758  4851  4851 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:20.758  4851  4851 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:20.778  4802  4866 D Mms/ArtClassLoader: init before art
03-17 13:26:20.778  4851  4851 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:20.778  4851  4851 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:20.788  1018  2825 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 50563
,03-17 13:26:20.788  4802  4802 D Mms/TelephonyPermission: start operation mode monitor
03-17 13:26:20.788  1018  2825 D PowerManagerService: [s] UserActivityState : 2 -> 1
,03-17 13:26:20.788  1018  2825 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
,03-17 13:26:20.788  1018  2825 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10049}) (elapsedTime=3444)
,03-17 13:26:20.798  4802  4802 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 13:26:20.798  4802  4802 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-17 13:26:20.798  4802  4802 D Mms/TelephonyPermission: isDefault true
,03-17 13:26:20.798  4802  4802 D Mms/MmsApp: onCreate() com.android.mms
,03-17 13:26:20.808  4851  4851 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,03-17 13:26:20.818  4851  4851 D elm:15121: ELMEngine.ELMEngine( context ).
,03-17 13:26:20.818  4851  4851 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-17 13:26:20.818  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.818  1018  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:20.818  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 13:26:20.818  4851  4851 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-17 13:26:20.818  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.818  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.818  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.818  1018  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.828  4851  4851 D elm:15121: ElmAgentService : onCreate()
,03-17 13:26:20.828  4851  4868 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,03-17 13:26:20.828  4851  4868 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,03-17 13:26:20.828  4851  4851 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
03-17 13:26:20.828  4851  4851 D elm:15121: ModuleBase.ModifySetAlarm()
03-17 13:26:20.828  4851  4851 D elm:15121: MDMBridge.getInstance()
03-17 13:26:20.828  4851  4851 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 13:26:20.838  4871  4871 E Zygote  : MountEmulatedStorage(),
03-17 13:26:20.838  4871  4871 I libpersona: KNOX_SDCARD checking this for 10130
03-17 13:26:20.838  4871  4871 E Zygote  : v2
03-17 13:26:20.838  4871  4871 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:20.838  4871  4871 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:20.838  1018  1139 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4871 uid=10130 gids={50130, 9997} abi=armeabi-v7a
03-17 13:26:20.838  4851  4851 D elm:15121: ElmAgentService : onDestroy().
,03-17 13:26:20.848  4871  4871 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:20.848  4802  4802 D Mms/MmsApp: [start]    initCountryIso consume time = 286.016823
,03-17 13:26:20.848  1018  1510 I ActivityManager: Killing 4166:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-17 13:26:20.848  4871  4871 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-17 13:26:20.868  1018  2825 D CountryDetector: The first listener is added
,03-17 13:26:20.868  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.868  1018  1327 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-17 13:26:20.868  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-17 13:26:20.878  4802  4802 D Mms/MmsApp: [end]    initCountryIso consume time = 29.56901
,03-17 13:26:20.878  4802  4802 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.773125
,03-17 13:26:20.878  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4154/cgroup.procs: No such file or directory
,03-17 13:26:20.878  4871  4871 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:20.878  4871  4871 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:20.888  4278  4622 I SA      : [RC New] [v2liruge] api execute + 870
,03-17 13:26:20.888  4278  4622 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
03-17 13:26:20.888  4278  4622 I System.out: AsyncTask #1 calls detatch()
,03-17 13:26:20.898  4802  4802 D Mms/MmsConfig: before partial update
,03-17 13:26:20.898  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4166/cgroup.procs: No such file or directory,
,03-17 13:26:20.918  4278  4622 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,03-17 13:26:20.928  4871  4871 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:20.928  4871  4871 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-17 13:26:20.948  4278  4622 I SA      : [OCP] update openData : PL
,03-17 13:26:20.958  4278  4622 I SA      : [TPMU] getNetworkMcc : 
,03-17 13:26:20.958  4278  4622 I SA      : [SCU] saveMccToPreferece Start
03-17 13:26:20.958  4278  4622 I SA      : [SCU] RegionMCC : 260
03-17 13:26:20.958  4278  4622 I SA      : [SSP] query invoked
,03-17 13:26:20.968  4278  4622 I SA      : [TPMU] GetMccFromDB : null
,03-17 13:26:20.968  4802  4802 D Mms/MmsConfig: Load Resize quality : 80
,03-17 13:26:20.968  4278  4622 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-17 13:26:20.968  4278  4622 I SA      : [SCU] saveMccToPreferece End
03-17 13:26:20.968  4278  4622 I SA      : [RC New] executeRequest [v2liruge] end. 1008
03-17 13:26:20.968  4278  4622 I SA      : [RC New] Execute end
,03-17 13:26:20.968  4278  4278 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-17 13:26:20.968  4278  4278 I SA      : [OR] GetMyCountryZoneTask Success
,03-17 13:26:20.968  4802  4802 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-17 13:26:20.968  4802  4802 D EasySignUpManager_1.0.1: isAuth is false
,03-17 13:26:20.968  4802  4802 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-17 13:26:20.968  1018  1489 I ActivityManager: Killing 4258:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,03-17 13:26:20.978  1477  1811 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4802
,03-17 13:26:20.978  1477  1811 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.624 ms
,03-17 13:26:20.988  4802  4802 D EasySignUpManager_1.0.1: isAuth is false
,03-17 13:26:20.988  4802  4802 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-17 13:26:20.998  4802  4802 E CscParser: mps_code.dat does not exist
03-17 13:26:20.998  4802  4802 E CscParser: customer_path =/system/csc/customer.xml
03-17 13:26:20.998  4802  4802 E CscParser: fileName + /system/csc/customer.xml
,03-17 13:26:20.998  4802  4802 E CscParser: mps_code.dat does not exist
,03-17 13:26:21.008  4802  4802 E CscParser: customer_path =/system/csc/customer.xml
03-17 13:26:21.008  4802  4802 E CscParser: fileName + /system/csc/customer.xml
,03-17 13:26:21.018  4802  4802 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-17 13:26:21.018  4802  4802 D Mms/MmsConfig:  enable multiwindow = false
,03-17 13:26:21.028  4802  4802 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-17 13:26:21.028  4802  4802 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-17 13:26:21.028  4802  4802 D Mms/MmsConfig: [end]    init() consume time = 155.58974
,03-17 13:26:21.038  4802  4802 D Mms/Contact: [start]    init() consume time = 2.136562
,03-17 13:26:21.048  4802  4802 D Mms/Contact: [end]    init consume time = 10.653177,
03-17 13:26:21.048  1477  1486 D TP/MmsSmsProvider: query,matched:13, calling pid = 4802
,03-17 13:26:21.048  1477  1486 D TP/MmsSmsProvider: match 13:Elapsed time : 1.110 ms
,03-17 13:26:21.048  4802  4893 D Mms/DraftCache: [start]    rebuildCache consume time = 7.217708
,03-17 13:26:21.058  1477  3849 D TP/MmsSmsProvider: query,matched:12, calling pid = 4802
,03-17 13:26:21.058  1477  3849 D TP/MmsSmsProvider: match 12:Elapsed time : 1.462 ms
,03-17 13:26:21.058  4802  4802 D Mms/MethodReflector: getSubId is called
03-17 13:26:21.058  4802  4802 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 13:26:21.058  4802  4802 D Mms/MethodReflector: getTelephonyProperty is called
03-17 13:26:21.058  4802  4802 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 13:26:21.058  4802  4802 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 13:26:21.058  4802  4802 D Mms/DownloadManager: auto download without roaming -> true
03-17 13:26:21.058  4802  4802 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
03-17 13:26:21.058  4802  4802 D Mms/MethodReflector: getSubId is called
,03-17 13:26:21.058  4802  4802 D Mms/MethodReflector: getDefaultSmsSubId is called
,03-17 13:26:21.058  4802  4802 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-17 13:26:21.058  4802  4802 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
03-17 13:26:21.058  4802  4802 D Mms/MethodReflector: getTelephonyProperty is called
03-17 13:26:21.058  4802  4802 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-17 13:26:21.058  4802  4802 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-17 13:26:21.058  4802  4802 D Mms/DownloadManager: auto download without roaming -> true
03-17 13:26:21.058  4802  4802 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-17 13:26:21.058  4802  4802 D Mms/DownloadManager: auto download during roaming secondary -> false
03-17 13:26:21.058  4802  4802 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 13:26:21.068  4802  4893 D Mms/DraftCache: [end]    rebuildCache consume time = 13.462709
,03-17 13:26:21.078  4802  4802 D ComposerPerformance: 1458217581088 ms / [DONE] Composer constructor
,03-17 13:26:21.088  4802  4895 D Mms/Conversation: [start]    init() consume time = 19.683073
,03-17 13:26:21.088  1477  1487 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-17 13:26:21.088  1477  1487 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 13:26:21.088  1477  1487 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-17 13:26:21.088  4802  4802 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-17 13:26:21.098  4802  4802 I Mms/ReservationManager: ReservationManager()
03-17 13:26:21.098  4802  4802 I Mms/ReservationManager: resetAfterConnected()
,03-17 13:26:21.098  1477  1487 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-17 13:26:21.098  1477  1487 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 13:26:21.098  1477  1487 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:21.098  1477  1487 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:21.098  1477  1487 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id),
03-17 13:26:21.098  1477  1487 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:21.098  1477  1487 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 13:26:21.098  4802  4866 D Mms/ArtClassLoader: init [DONE] art
,03-17 13:26:21.098  1018  1043 W libprocessgroup: failed to open /acct/uid_10127/pid_4258/cgroup.procs: No such file or directory
,03-17 13:26:21.098  1477  3077 D TP/MmsSmsProvider: query,matched:7, calling pid = 4802
,03-17 13:26:21.108  1477  3077 D TP/MmsSmsProvider: match 7:Elapsed time : 2.988 ms
,03-17 13:26:21.108  4802  4802 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 13:26:21.108  1477  1487 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-17 13:26:21.108  1477  1487 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 13:26:21.108  4802  4895 D Mms/Conversation: [end]    init consume time = 23.82875
,03-17 13:26:21.108  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,03-17 13:26:21.118  4802  4895 D Mms/MessagingNotification: [start]    init() consume time = 5.267239
,03-17 13:26:21.118  4802  4802 D Mms/MmsApp: [end]    onCreate() consume time = 1.856302
03-17 13:26:21.118  3224  3331 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 13:26:21.118  4802  4895 D Mms/MessagingNotification: [end]    init consume time = 1.26375,
03-17 13:26:21.118  3224  3331 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-17 13:26:21.118  3224  3331 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,03-17 13:26:21.118  1018  1031 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,03-17 13:26:21.118  4802  4802 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,03-17 13:26:21.118  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.118  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.118  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.128  4802  4802 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,03-17 13:26:21.128  1018  1031 I ActivityManager: Killing 4348:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,03-17 13:26:21.128  4802  4896 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 6.885
,03-17 13:26:21.128  4802  4802 D Mms/MethodReflector: getSubId is called
,03-17 13:26:21.128  4802  4802 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 13:26:21.128  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.128  1477  1486 D TP/MmsSmsProvider: query,matched:0, calling pid = 4802
03-17 13:26:21.128  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.128  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.128  1477  1486 V TP/MmsSmsProvider: getSimpleConversations entered.
,03-17 13:26:21.128  1477  1811 D TP/MmsSmsProvider: query,matched:400, calling pid = 4802
,03-17 13:26:21.138  1477  1486 D TP/MmsSmsProvider: match 0:Elapsed time : 2.518 ms
,03-17 13:26:21.138  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.138  1018  1018 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.138  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.138  4802  4897 D Mms/Synchronizer: [start]    doSync consume time = 12.893594
03-17 13:26:21.138  4802  4802 D Mms/MethodReflector: getTelephonyProperty is called
03-17 13:26:21.138  4802  4802 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 13:26:21.138  4802  4802 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 13:26:21.138  4802  4802 D Mms/DownloadManager: auto download without roaming -> true
03-17 13:26:21.138  4802  4802 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,03-17 13:26:21.138  4802  4802 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 13:26:21.138  3224  3331 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 13:26:21.138  1018  1571 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 13:26:21.138  1018  1571 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,03-17 13:26:21.138  1018  1571 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,03-17 13:26:21.138  1018  1571 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 13:26:21.148  3224  3331 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-17 13:26:21.148  1018  1571 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.148  1018  1571 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.148  1018  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.158  3224  3331 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,03-17 13:26:21.158  4802  4896 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 18.190781
,03-17 13:26:21.158  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,03-17 13:26:21.158  1477  1811 D TP/MmsSmsProvider: update, matched:300, calling pid = 4802
,03-17 13:26:21.158  1477  1811 V TP/MmsSmsProvider: syncDBData start
,03-17 13:26:21.158  1477  1811 V TP/MmsSmsProvider: syncDBData sms end
,03-17 13:26:21.158  1477  1811 V TP/MmsSmsProvider: syncDBData mms end
,03-17 13:26:21.158  1477  1811 V TP/MmsSmsProvider: syncDBData end
,03-17 13:26:21.158  4802  4897 D Mms/Synchronizer: [end]    doSync consume time = 5.514584
,03-17 13:26:21.158  3224  3331 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,03-17 13:26:21.168  3224  3331 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,03-17 13:26:21.168  3224  3332 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,03-17 13:26:21.168  3224  3331 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,03-17 13:26:21.168  3224  3332 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,03-17 13:26:21.168  3224  3331 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-17 13:26:21.168  4802  4895 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-17 13:26:21.168  3224  3331 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,03-17 13:26:21.178  1477  1486 D TP/SmsProvider: query,matched:26, calling pid = 4802
,03-17 13:26:21.178  1018  1030 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:21.178  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.178  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.178  1477  1486 D TP/SmsProvider: match 26:Elapsed time : 5.603 ms
,03-17 13:26:21.188  1018  1098 V AlarmManager: waitForAlarm result :4
,03-17 13:26:21.188  1477  1487 D TP/MmsSmsProvider: query,matched:6, calling pid = 4802
03-17 13:26:21.188  3224  3332 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:362673799
03-17 13:26:21.188  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.188  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.188  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.188  3224  3332 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,03-17 13:26:21.198  1477  1487 D TP/MmsSmsProvider: match 6:Elapsed time : 3.552 ms
,03-17 13:26:21.198  3224  3332 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,03-17 13:26:21.208  3224  3332 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,03-17 13:26:21.218  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.218  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.218  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.228  3224  3332 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,03-17 13:26:21.228  3224  3332 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 705624899
,03-17 13:26:21.228  3224  3224 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,03-17 13:26:21.228  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-17 13:26:21.228  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,03-17 13:26:21.238  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.238  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.238  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.238  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.238  1900  1900 D WearableService: callingUid 10011, callindPid: 1900
,03-17 13:26:21.238  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,03-17 13:26:21.238  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
03-17 13:26:21.248  3224  3332 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
03-17 13:26:21.248  3224  3224 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,03-17 13:26:21.248  3224  3224 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@347624ae
03-17 13:26:21.248  4899  4899 E Zygote  : MountEmulatedStorage()
03-17 13:26:21.248  4899  4899 E Zygote  : v2
03-17 13:26:21.248  4899  4899 I libpersona: KNOX_SDCARD checking this for 10023
03-17 13:26:21.248  4899  4899 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:21.248  4899  4899 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 13:26:21.258  1018  1571 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4899 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,03-17 13:26:21.258  4899  4899 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 13:26:21.258  4899  4899 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 13:26:21.268  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.268  1018  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.268  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.278   305   305 I art     : Explicit concurrent mark sweep GC freed 8678(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 26.857ms
,03-17 13:26:21.278  3224  3332 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
03-17 13:26:21.278  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(755/lllllIIlIIIlIlIIIllI)] UI_id:223
03-17 13:26:21.288  3224  3224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 com.wssyncmldm.llIIllllIIlllIIIIlll.handleMessage:1090 
03-17 13:26:21.288  3224  3224 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 
,03-17 13:26:21.288  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.288  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.288  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.288  3224  3224 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:51064,
03-17 13:26:21.288  1018  1139 E PersonaManagerService: inState():  stateMachine is null !!
03-17 13:26:21.288  1018  1139 I PersonaManagerService: PersonaId don't exist
03-17 13:26:21.288  4899  4899 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:21.288  1018  1139 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false,
03-17 13:26:21.288  4899  4899 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:21.298  1018  2826 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.298  1018  2826 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.298  1018  2826 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.298   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 17.017ms
,03-17 13:26:21.298  1900  4898 E MDM     : [241] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 13:26:21.298  1018  1139 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 13:26:21.298  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.298  1018  1139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.298  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
03-17 13:26:21.308  1018  1139 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:21.308  1018  1139 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 13:26:21.308  1018  1139 W ActivityManager: mDVFSHelper.acquire()
03-17 13:26:21.308   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.558ms
03-17 13:26:21.318   259   437 I SurfaceFlinger: id=13 Removed Uoast (8/8)
03-17 13:26:21.318   259  1859 I SurfaceFlinger: id=13 Removed Uoast (-2/8)
,03-17 13:26:21.318  1018  1139 D FocusedStackFrame: Set to : 0,
,03-17 13:26:21.318  1499  1499 D Launcher.HomeView: onPause
,03-17 13:26:21.318  1018  1139 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 13:26:21.318  1018  1139 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-17 13:26:21.318  1499  1499 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 13:26:21.318  1018  1139 D InputDispatcher: Focused application set to: xxxx
03-17 13:26:21.328  1018  1139 D InputDispatcher: Focus left window: 1499
,03-17 13:26:21.328  1018  1575 I ActivityManager: Killing 4442:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 13:26:21.328  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:21.328  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:26:21.328  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.328  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.328  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.338  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.338  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.338  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:21.338  2135  4914 D LocationInitializer: Restart initialization of location
,03-17 13:26:21.338  1018  1043 W libprocessgroup: failed to open /acct/uid_10135/pid_4348/cgroup.procs: No such file or directory
,03-17 13:26:21.368  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.368  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.368  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.378  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.378  1018  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.378  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.388  1018  1018 D SensorService: [SO] activate (ident=0xb7b22538, enabled=0)
03-17 13:26:21.388  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 13:26:21.388  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 13:26:21.398  1018  1018 D SensorManager: unregisterListener ::   
,03-17 13:26:21.398  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-17 13:26:21.398  1018  1018 D SensorService: [SO] changed settle time [1]
03-17 13:26:21.398  1018  1018 D SensorService: [SO] setDelay [66000000]
03-17 13:26:21.398  1018  1018 D SensorService: [SO] activate (ident=0xb7b22538, enabled=1)
03-17 13:26:21.398  1018  1018 D SensorService: [SO] AR_init
03-17 13:26:21.398  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 13:26:21.408  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.408  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.408  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.408  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 13:26:21.438  4899  4899 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-17 13:26:21.438  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4442/cgroup.procs: No such file or directory
,03-17 13:26:21.448  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2153/onResume)] 
,03-17 13:26:21.448  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2195/lllIlIlIIIllIIlIllIl)] id 223
,03-17 13:26:21.468  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-17 13:26:21.478  1018  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 13:26:21.478  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,03-17 13:26:21.478  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-17 13:26:21.478  4802  4895 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-17 13:26:21.478  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-17 13:26:21.478  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-17 13:26:21.478  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-17 13:26:21.478  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-17 13:26:21.488  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,03-17 13:26:21.488  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,03-17 13:26:21.488  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-17 13:26:21.488  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-17 13:26:21.488  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.488  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.488  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.488  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-17 13:26:21.488  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-17 13:26:21.488  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-17 13:26:21.488  4899  4899 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-17 13:26:21.498  1477  1811 D TP/SmsProvider: query,matched:0, calling pid = 2135
,03-17 13:26:21.498  1477  1811 D TP/SmsProvider: match 0:Elapsed time : 1.885 ms
,03-17 13:26:21.498  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-17 13:26:21.508  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:21.508  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-17 13:26:21.508  3224  3224 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:51286
,03-17 13:26:21.508  1018  2825 E PersonaManagerService: inState():  stateMachine is null !!
03-17 13:26:21.508  1018  2825 I PersonaManagerService: PersonaId don't exist
03-17 13:26:21.508  1018  2825 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-17 13:26:21.508  1477  3849 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2135
,03-17 13:26:21.518  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.518  1018  2825 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:21.518  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 13:26:21.518  1018  2825 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 13:26:21.518  1018  2825 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-17 13:26:21.518  1018  2825 W ActivityManager: mDVFSHelper.acquire()
,03-17 13:26:21.528  1018  2825 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 13:26:21.528  1018  2825 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 13:26:21.528  1018  2825 D InputDispatcher: Focused application set to: xxxx
,03-17 13:26:21.538  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.IIllIIIlIllIIIllIIlI(252/llllIIIllIlIIIIllllI)] 
,03-17 13:26:21.538  1018  1571 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
03-17 13:26:21.538  1018  1571 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 13:26:21.538  1018  1571 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 13:26:21.538  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 13:26:21.538  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 13:26:21.538  1018  1018 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,03-17 13:26:21.538  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2145/onPause)] 
,03-17 13:26:21.548  1018  1041 D SensorService: [SO] currT = 51321129000, prevT = 50991058000, diff = 330071000, [-0.479 0.211 9.902]
03-17 13:26:21.548  1018  1041 D SensorService: [SO] -0.479 0.211 9.902
03-17 13:26:21.548  1018  1041 D SensorService: [SO] [100 -> 255]
,03-17 13:26:21.548  1018  1030 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:21.548  1018  1030 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:21.548  1018  1030 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 13:26:21.558  1477  3077 D TP/SmsProvider: query,matched:0, calling pid = 2135
,03-17 13:26:21.568  1477  3077 D TP/SmsProvider: match 0:Elapsed time : 2.180 ms
,03-17 13:26:21.568  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{2261103c u0 com.samsung.android.providers.context/.ContextService}
,03-17 13:26:21.578  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-17 13:26:21.578  1477  1486 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2135
,03-17 13:26:21.578  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:21.608  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-17 13:26:21.608  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(75/onCreate)] Postpone Count : 24
,03-17 13:26:21.618  2135  4920 W IcingInternalCorpora: getNumBytesRead when not calculated.
,03-17 13:26:21.618  1018  1241 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:21.618  1018  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.618  1018  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.638  1900  1900 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 13:26:21.648  1900  1900 D a       : Opening database auth.proximity.permit_store...
,03-17 13:26:21.648  3224  3224 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 13:26:21.648  3224  3224 D PhoneWindow: *FMB* installDecor flags : -2139029248
,03-17 13:26:21.648  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.648  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.648  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.658  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.658  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.658  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.708  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.708  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.708  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.708  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.708  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.708  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.718  1018  1510 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.718  1018  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.718  1018  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.728  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:21.738  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{25bef104 u0 com.android.settings/.wifi.WifiCredService}
,03-17 13:26:21.738  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.738  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.738  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.738  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-17 13:26:21.748  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-17 13:26:21.748  1018  1575 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.748  1018  1575 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.748  1018  1575 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.758  1018  1571 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.758  1018  1571 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.758  1018  1571 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.758  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-17 13:26:21.758  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.758  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.758  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.768  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.768  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:21.768  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.778  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-17 13:26:21.778  1900  2192 W GCoreFlp: No location to return for getLastLocation()
,03-17 13:26:21.778  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.778  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.778  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.778  1900  4926 W FusedLocationProvider: location=null
,03-17 13:26:21.788  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.788  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.788  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.798  1018  1577 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,03-17 13:26:21.798  1018  1577 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 13:26:21.798  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.798  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.798  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.808  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-17 13:26:21.808  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-17 13:26:21.818  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:21.818  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-17 13:26:21.818  1018  1018 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-17 13:26:21.828  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 13:26:21.828  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.828  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.828  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.828  1174  2418 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:21.828  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-17 13:26:21.828  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.828  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.828  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.838  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.838  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.838  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.838  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-17 13:26:21.848  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:21.848  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.848  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.848  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-17 13:26:21.848  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-17 13:26:21.848  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.848  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.848  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.848  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.848  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.848  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.858  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-17 13:26:21.858  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.858  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.858  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 13:26:21.858  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.858  1018  1018 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.858  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.858  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-17 13:26:21.858  1018  1031 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 13:26:21.858  1018  1031 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-17 13:26:21.858  1018  1031 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-17 13:26:21.858  1018  1031 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 13:26:21.868  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.868  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.868  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.868  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:21.868  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-17 13:26:21.868  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,03-17 13:26:21.868  1018  1510 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.868  1018  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.868  1018  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.878  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-17 13:26:21.878  1018  1510 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.878  1018  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.878  1018  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.888  1018  1510 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.888  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-17 13:26:21.888  1018  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.888  1018  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.888  1174  1174 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-17 13:26:21.888  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:21.898  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 24
,03-17 13:26:21.898  1018  1577 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.898  1018  1577 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.898  1018  1577 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.898  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.898  1018  2825 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.898  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.898  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-17 13:26:21.908  1900  4935 E MDM     : [256] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 13:26:21.908  3224  3224 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
03-17 13:26:21.908  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.908  1018  2825 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.908  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.908  1174  1174 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-17 13:26:21.908  1174  1174 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
,03-17 13:26:21.908  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:21.918  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:21.918  1174  1174 I PhoneStatusBar: Icon Only
,03-17 13:26:21.918  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.918  1174  1174 I StatusBar: Icon Only
03-17 13:26:21.918  1174  1174 D PanelView: There is/are notification(s) 
03-17 13:26:21.918  1174  1174 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:26:21.918  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
03-17 13:26:21.918  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.918  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.918  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:26:21.918  1174  1174 I PhoneStatusBar: Icon Only
03-17 13:26:21.918  1174  1174 I StatusBar: Icon Only
03-17 13:26:21.918  1174  1174 D PanelView: There is/are notification(s) 
03-17 13:26:21.918  1174  1174 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:26:21.918  2135  4936 D LocationInitializer: Restart initialization of location
,03-17 13:26:21.918  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.918  1018  2825 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.918  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.918  1900  1900 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 13:26:21.928  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.928  1018  2825 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.928  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.928  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.928  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.928  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.938  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.938  1018  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.938  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.948  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
03-17 13:26:21.948  1018  1577 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.948  1018  1577 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.948  1018  1577 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.958  1900  1900 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:21.958  1018  1498 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.958  1018  1498 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 13:26:21.958  1018  1498 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.958  1018  1569 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-17 13:26:21.958  1018  1569 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 13:26:21.958  1018  2825 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:21.958  1018  2825 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:21.958  1018  2825 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.968  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-17 13:26:21.968  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 13:26:21.968  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-17 13:26:21.978  1018  1489 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.978  1018  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.978  1018  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
03-17 13:26:21.978  1174  1174 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-17 13:26:21.978  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:26:21.978  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:21.978  1174  1174 I PhoneStatusBar: Icon Only
03-17 13:26:21.978  1174  1174 I StatusBar: Icon Only
03-17 13:26:21.978  1174  1174 D PanelView: There is/are notification(s) 
03-17 13:26:21.978  1174  1174 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:26:21.978  3224  3224 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:21.978  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:21.978  1174  1174 I PhoneStatusBar: Icon Only
03-17 13:26:21.978  3224  3224 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-17 13:26:21.978  1174  1174 I StatusBar: Icon Only
,03-17 13:26:21.978  1174  1174 D PanelView: There is/are notification(s) 
03-17 13:26:21.978  1174  1174 D PanelView: kidsfalse mQsExpansionEnabled:true
03-17 13:26:21.978  3224  3224 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,03-17 13:26:21.988  3224  3224 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,03-17 13:26:21.998  1174  1174 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-17 13:26:21.998  1900  2192 W GCoreFlp: No location to return for getLastLocation()
,03-17 13:26:21.998  1900  4937 W FusedLocationProvider: location=null
,03-17 13:26:22.008  3224  4940 D OpenGLRenderer: Render dirty regions requested: true
,03-17 13:26:22.008  1018  1489 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-17 13:26:22.008  1018  1489 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 13:26:22.008  1018  1489 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 13:26:22.008  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 13:26:22.008  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 13:26:22.008  3224  3224 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 13:26:22.008  3224  3224 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 13:26:22.018  1018  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:22.018  1018  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:22.018  1018  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 13:26:22.028  1018  1139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:22.028  1018  1139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 13:26:22.028  1018  1139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:22.048   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, YUIInstallC
,03-17 13:26:22.048  1174  1174 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-17 13:26:22.048  1018  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 13:26:22.058  1018  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 13:26:22.058  1018  1030 D InputDispatcher: Focus entered window: 3224
,03-17 13:26:22.068  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.068  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.068  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.068  1018  1571 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.068  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:22.068  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:26:22.068  3224  3224 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 13:26:22.078  3224  4940 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 13:26:22.078  3224  4940 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 13:26:22.078  3224  4940 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 13:26:22.078  3224  4940 I Adreno-EGL: Local Branch: 
03-17 13:26:22.078  3224  4940 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 13:26:22.078  3224  4940 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 13:26:22.078  3224  4940 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 13:26:22.078  3224  4940 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 13:26:22.078  4942  4942 E Zygote  : MountEmulatedStorage()
,03-17 13:26:22.078  4942  4942 E Zygote  : v2
03-17 13:26:22.078  4942  4942 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:22.078  4942  4942 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:22.088  4942  4942 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 13:26:22.088  1018  1571 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4942 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 13:26:22.088  4942  4942 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 13:26:22.088  4942  4942 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:22.098  3224  4940 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-17 13:26:22.098  3224  4940 D OpenGLRenderer: Enabling debug mode 0
,03-17 13:26:22.128  4942  4942 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.128  4942  4942 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.158  4942  4942 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-17 13:26:22.168  1018  1575 D SecContentProvider2: uri = 14 selection = getSealedState
,03-17 13:26:22.168  1018  1575 D SecContentProvider2: mCursor = null
,03-17 13:26:22.168  1018  1571 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-17 13:26:22.168  1018  1571 D SecContentProvider2: mCursor = null
,03-17 13:26:22.168  1018  2825 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 13:26:22.168  4942  4942 V MTPRx   : sealedState: false
03-17 13:26:22.168  4942  4942 V MTPRx   : sealedUsbMassStorageState: false
03-17 13:26:22.168  4942  4942 E MTPRx   : check value of boot_completed is1
03-17 13:26:22.168  4942  4942 E MTPRx   : check booting is completed_sys.boot_completed
,03-17 13:26:22.178  1018  1050 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:22.178  4942  4942 E MTPRx   : Sd-Card path/storage/extSdCard
,03-17 13:26:22.178  4942  4942 E MTPRx   : Status for mount/Unmount :removed
03-17 13:26:22.178  4942  4942 E MTPRx   : SDcard is not available
,03-17 13:26:22.178  1018  1050 I ActivityManager: Displayed Component not be shown by security: +636ms (total +844ms)
,03-17 13:26:22.188  1018  4958 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:22.188  1174  1174 I StatusBar: Icon Only
,03-17 13:26:22.188  1174  1174 D PanelView: There is/are notification(s) 
,03-17 13:26:22.198  4942  4942 W MTPRx   : value of connected istrue
,03-17 13:26:22.198  4942  4942 W MTPRx   : value of configured istrue
,03-17 13:26:22.198  4942  4942 W MTPRx   : value of mtpEnabled istrue
,03-17 13:26:22.198  4942  4942 W MTPRx   : value of ptpEnabled isfalse
,03-17 13:26:22.198  4942  4942 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-17 13:26:22.198  4942  4942 E MTPRx   : mFirstTime: false
,03-17 13:26:22.208  3224  3224 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20ce7236 time:51980
,03-17 13:26:22.208  1882  1882 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 13:26:22.218  4942  4942 D         : MTP: reading debug level property
,03-17 13:26:22.218  4942  4942 E MTPJNIInterface: Getting CryptionKey from JAVA
,03-17 13:26:22.218  4942  4942 E MTPRx   : currentUserId is 0
,03-17 13:26:22.228  1018  1018 I ValidateNoPeople: mEvictionCount: 0
,03-17 13:26:22.228  4802  4802 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-17 13:26:22.238  4802  4802 D Mms/Contact: performUpdate:widgetCount=0
,03-17 13:26:22.238  4802  4961 D Mms/ContactsCache: [start]    invalidate() consume time = 1073.885051
03-17 13:26:22.238  4802  4961 D Mms/ContactsCache: [end]    invalidate() consume time = 0.178802
,03-17 13:26:22.238  4942  4942 E MTPRx   : Start observing USB_STATE_MATCH 
,03-17 13:26:22.238  4942  4942 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
03-17 13:26:22.238  4942  4942 E MTPRx   : is_Privatemode is NOT 1
,03-17 13:26:22.238  1018  1139 D SettingsProvider: name = boot_time_connected
,03-17 13:26:22.248  4942  4942 E MTPRx   : Sending NORMAL_BOOT to stack
03-17 13:26:22.248  4942  4942 E MTPJNIInterface: noti = 17
,03-17 13:26:22.258  1018  2825 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 13:26:22.258  1018  1571 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-17 13:26:22.258  4942  4942 E MTPRx   : sending MTP_ICON_ENABLED to stack,
,03-17 13:26:22.258  1018  1241 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:22.258  1018  1241 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:22.258  1018  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication,
,03-17 13:26:22.268  1018  1498 I art     : Explicit concurrent mark sweep GC freed 20499(1083KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 4.395ms total 173.599ms,
,03-17 13:26:22.268  1018  1573 D SettingsProvider: name = mtp_running_status
,03-17 13:26:22.298  1018  1510 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 13:26:22.298  4942  4942 E MTPRx   : else part ... so first time!!!
,03-17 13:26:22.298  4942  4942 E MTPPlaObsrvr: inside setContext()
03-17 13:26:22.298  4942  4942 E MTPPlaObsrvr:  inside createplafiles
,03-17 13:26:22.308  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:22.308  4942  4942 E MTPPlaObsrvr: playlist count is0
,03-17 13:26:22.318  4942  4942 E MTPPlaObsrvr:  inside try branch createplafiles
,03-17 13:26:22.318  1018  1041 D SensorService: [SO] -0.479 0.211 9.902
,03-17 13:26:22.318  4942  4942 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-17 13:26:22.318  4942  4942 E MTPPlaObsrvr: Inside registerContentObserver
,03-17 13:26:22.318  4942  4942 E MtpAdbObserver: inside setContext()
,03-17 13:26:22.318  4942  4942 E MtpAdbObserver: Inside registerContentObserver
,03-17 13:26:22.318  4942  4942 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-17 13:26:22.318  1018  1573 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:22.318  1018  1573 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:22.318  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 13:26:22.328  1018  1510 D SettingsProvider: name = mtp_running_status
,03-17 13:26:22.328  1018  1575 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 13:26:22.328  4942  4942 E MtpService: onCreate.
,03-17 13:26:22.328  4942  4964 V MtpMediaDBManager: inside deleteAllDB
,03-17 13:26:22.328  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:22.328  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:22.328  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 13:26:22.338  4942  4942 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-17 13:26:22.338  1215  1215 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-17 13:26:22.338  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.338  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.338  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.338  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.338  4942  4942 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-17 13:26:22.358  4966  4966 E Zygote  : MountEmulatedStorage()
,03-17 13:26:22.358  4966  4966 E Zygote  : v2
03-17 13:26:22.358  4966  4966 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:22.358  4966  4966 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:22.358  4966  4966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 13:26:22.358  1018  1573 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4966 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
03-17 13:26:22.358  4942  4942 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-17 13:26:22.368  4942  4942 E MtpService: onStartCommand.
,03-17 13:26:22.368  4942  4964 V MtpMediaDBManager: inside Thread updateDB
03-17 13:26:22.368  4942  4942 W MTPRx   : calling native method
03-17 13:26:22.368  4942  4942 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-17 13:26:22.368  4942  4965 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-17 13:26:22.368  4966  4966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 13:26:22.368  4966  4966 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:22.368  4942  4942 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-17 13:26:22.368  4942  4942 E MTPJNIInterface: noti = 10
03-17 13:26:22.368  4942  4942 W MTPRx   : calling native method
03-17 13:26:22.368  4942  4942 E MTPRx   : Checking the driver time out
03-17 13:26:22.368  4942  4942 E MTPJNIInterface: noti = 2
03-17 13:26:22.368  4942  4942 D         : deleting sockets before message queue initialization
,03-17 13:26:22.368  4942  4942 D         : event handler thread is created, so set the flag
,03-17 13:26:22.368  4942  4942 E MTPRx   : called native method
,03-17 13:26:22.368  4942  4964 E MtpMediaDBManager: count : 26
,03-17 13:26:22.368  4942  4942 E MTPJNIInterface: setting Media scanner status0
03-17 13:26:22.368  4942  4942 E MTPJNIInterface: After setting Media scanner status0
03-17 13:26:22.368  4942  4942 E MtpService: onStartCommand.
,03-17 13:26:22.378  4942  4973 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-17 13:26:22.378  4942  4973 E MTPJNIInterface: Getting media scanner status0
,03-17 13:26:22.378  4942  4942 W MTPRx   : notification from stack 1
,03-17 13:26:22.378  4942  4965 E MtpService: handleMessage. msg= { when=-7ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-17 13:26:22.388  4942  4973 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A3)
,03-17 13:26:22.388  4966  4966 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.398  4966  4966 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.398  4942  4964 W MtpMediaDBManager: sending db update complete noti to stack
,03-17 13:26:22.398  4942  4964 E MTPJNIInterface: noti = 29
,03-17 13:26:22.418  4942  4973 E MTPJNIInterface: Status for mount/Unmount :removed
,03-17 13:26:22.418  4942  4973 E MTPJNIInterface: SDcard is not available
,03-17 13:26:22.418  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:22.418  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:22.418  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:22.418  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:22.418  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:22.418  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:22.438  4942  4973 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-17 13:26:22.448  4942  4973 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 13:26:22.448  4942  4973 E MTPJNIInterface: SDcard is not available
,03-17 13:26:22.448  4942  4973 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 13:26:22.448  4942  4973 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-17 13:26:22.448  4942  4973 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 13:26:22.448  4942  4973 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 13:26:22.448  4942  4973 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 13:26:22.448  4942  4973 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 13:26:22.448  4942  4973 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 13:26:22.448  4942  4973 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-17 13:26:22.448  4942  4942 W MTPRx   : notification from stack 2
,03-17 13:26:22.448  4942  4982 D         : [mtp_init_device] Library open with 32 bits.
03-17 13:26:22.448  4942  4982 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,03-17 13:26:22.448  4942  4982 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-17 13:26:22.448  4942  4982 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-17 13:26:22.448  4942  4982 E         :  [sua_support_present:1287] returning false 
03-17 13:26:22.448  4942  4982 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
