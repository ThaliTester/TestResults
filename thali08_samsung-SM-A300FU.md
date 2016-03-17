#### Test 62509094764c200_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-17 06:44:13.669  2864  2864 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:13.669  2864  2864 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
--------- beginning of system
03-17 06:44:13.669  1019  1044 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2864 uid=1101 gids={41101, 9997} abi=armeabi-v7a
03-17 06:44:13.679  1019  2811 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
03-17 06:44:13.679  1019  2811 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
03-17 06:44:13.689  1019  2811 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
03-17 06:44:13.689  2864  2864 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.689  2864  2864 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.689  2850  2850 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.689  2850  2850 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.689  1019  1080 I ActivityManager: Killing 1559:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
03-17 06:44:13.699  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.699  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:13.699  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 06:44:13.709  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.709  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:13.709  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 06:44:13.719  2864  2864 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
03-17 06:44:13.719  2850  2850 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 06:44:13.719  2850  2850 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:44:13.719  2850  2850 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:13.719  2850  2850 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:13.719  2850  2850 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-17 06:44:13.739  1238  1238 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-17 06:44:13.739  2864  2864 V SmartcardService: main Received broadcast
03-17 06:44:13.739  2864  2864 V SmartcardService: Starting smartcard service after boot completed
03-17 06:44:13.739  1019  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.739  1019  1517 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:13.739  1019  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 06:44:13.749  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.749  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:13.749  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
03-17 06:44:13.749  1019  1480 I ActivityManager: Killing 2038:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
03-17 06:44:13.769  1019  1506 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 06:44:13.769  1019  1506 D SecContentProvider2: mCursor = null
03-17 06:44:13.769  1019  2811 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
03-17 06:44:13.769  1019  2814 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,03-17 06:44:13.779  1019  1543 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.779  1019  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:13.779  1019  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-17 06:44:13.779  1019  2814 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 06:44:13.779  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.779  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.779  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.779  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.779  1019  2814 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
03-17 06:44:13.779  1019  2811 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
03-17 06:44:13.789  1019  2811 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 06:44:13.789  1019  2814 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 06:44:13.789  1019  2811 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
03-17 06:44:13.789  2894  2894 E Zygote  : MountEmulatedStorage()
03-17 06:44:13.789  2894  2894 E Zygote  : v2
03-17 06:44:13.789  2894  2894 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:13.789  2894  2894 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:13.799  1019  2814 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 06:44:13.799  1019  2811 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
03-17 06:44:13.799  1019  1032 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2894 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 06:44:13.809  1019  2814 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 06:44:13.809  1019  2811 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
03-17 06:44:13.809  1019  2811 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 06:44:13.809  1019  2811 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-17 06:44:13.809  1019  2811 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 06:44:13.809  1019  2811 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
03-17 06:44:13.819  1019  2811 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 06:44:13.819  1019  2811 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
03-17 06:44:13.819  1238  1238 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 06:44:13.819   327   327 I art     : Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 644us total 19.545ms
03-17 06:44:13.829  2894  2894 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:13.829  2894  2894 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:13.829  2894  2894 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:13.839   327   327 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.574ms
03-17 06:44:13.849   327   327 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 16.672ms
03-17 06:44:13.859  2894  2894 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.859  2894  2894 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.869  1019  2814 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 06:44:13.869  1019  2811 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
03-17 06:44:13.869  1019  2814 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
03-17 06:44:13.869  1019  2814 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-17 06:44:13.879  1019  2811 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
03-17 06:44:13.899  2894  2894 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
03-17 06:44:13.909  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.909  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:13.909  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
03-17 06:44:13.909  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.909  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.909  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.909  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:13.909  1019  1043 W libprocessgroup: failed to open /acct/uid_10134/pid_2038/cgroup.procs: No such file or directory
03-17 06:44:13.909  1019  1043 W libprocessgroup: failed to open /acct/uid_10052/pid_1559/cgroup.procs: No such file or directory
03-17 06:44:13.929  2914  2914 E Zygote  : MountEmulatedStorage()
03-17 06:44:13.929  2914  2914 E Zygote  : v2
03-17 06:44:13.929  2914  2914 I libpersona: KNOX_SDCARD checking this for 10153
03-17 06:44:13.929  2914  2914 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:13.929  2914  2914 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:13.929  1019  1216 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2914 uid=10153 gids={50153, 9997} abi=armeabi-v7a
03-17 06:44:13.929  2914  2914 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:13.929  2914  2914 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:13.939  2836  2836 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
03-17 06:44:13.939  2836  2836 E ActivityThread: Failed to find provider info for flipboard.auth.internal
03-17 06:44:13.949  1019  1542 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.949  1019  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:13.949  1019  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 06:44:13.949  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:13.949  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:13.949  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 06:44:13.949  1019  1032 I ActivityManager: Killing 2185:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
03-17 06:44:13.959   343   343 I ServiceManager: Waiting for service AtCmdFwd...
03-17 06:44:13.959  1019  1019 I DrmEventReceiver: DrmEventReceiver : onReceive
03-17 06:44:13.959  1019  1019 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
03-17 06:44:13.959  1019  1019 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-17 06:44:13.959  1019  1019 I System.out: start Service
03-17 06:44:13.959  2914  2914 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:13.969  2914  2914 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:13.969  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-17 06:44:13.989  2914  2914 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:13.989  1019  1506 D SettingsProvider: name = next_alarm_formatted
03-17 06:44:13.989  1019  1506 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:13.989  1019  1506 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:13.989  1019  1506 D SettingsProvider: selectionArgs: false
03-17 06:44:13.989  1019  1506 D SettingsProvider: selectionArgs: 10081
03-17 06:44:13.989  1019  1506 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:13.989  1019  1506 D SettingsProvider: ret = -1
03-17 06:44:14.009  1019  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.009  1019  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.009  1019  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.009  1019  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.029  2932  2932 E Zygote  : MountEmulatedStorage()
03-17 06:44:14.029  2932  2932 E Zygote  : v2
03-17 06:44:14.029  2932  2932 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:14.029  2932  2932 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:14.029  2932  2932 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:14.029  2932  2932 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:14.029  1019  1517 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2932 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 06:44:14.029  1019  1517 I ActivityManager: Killing 2200:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
03-17 06:44:14.039  2932  2932 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:14.049   285   502 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 2150
03-17 06:44:14.049   285   502 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 2150
03-17 06:44:14.059  1019  1506 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10081
03-17 06:44:14.059  2932  2932 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:14.059  2932  2932 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:14.059  1238  2930 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-17 06:44:14.059  1019  2947 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
03-17 06:44:14.069  1019  1019 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
03-17 06:44:14.069  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 06:44:14.069   285   285 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-17 06:44:14.089  1019  1539 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:14.089  1019  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:14.089  1019  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 06:44:14.089  1238  1238 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-17 06:44:14.099  1459  1459 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-17 06:44:14.099  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:14.109  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:14.109  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-17 06:44:14.119  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.119  1459  1473 D TP/MmsProvider: Update uri=content://mms, match=0
03-17 06:44:14.119  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.119  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.119  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.119  1459  1473 D TP/MmsProvider: update , handleReadChangedBroadcast
03-17 06:44:14.119  1459  1473 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 06:44:14.129  1459  1459 D CscUpdateService: onStart
03-17 06:44:14.129  1019  1043 W libprocessgroup: failed to open /acct/uid_10064/pid_2185/cgroup.procs: No such file or directory
03-17 06:44:14.129  1459  1459 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-17 06:44:14.129  1459  1459 I CscUpdateService: set_CSC_version
03-17 06:44:14.129  1459  1459 E CscParser: update(): xml file exist
03-17 06:44:14.149  2952  2952 E Zygote  : MountEmulatedStorage()
03-17 06:44:14.149  2952  2952 E Zygote  : v2
03-17 06:44:14.149  2952  2952 I libpersona: KNOX_SDCARD checking this for 10002
03-17 06:44:14.149  2952  2952 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:14.149  2952  2952 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:14.149  2952  2952 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:14.159  2952  2952 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:14.159  1019  1342 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2952 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
03-17 06:44:14.159  2387  2387 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-17 06:44:14.159  2387  2387 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 3844.204061
03-17 06:44:14.169  2387  2387 I Mms/ReservationManager: resetAfterConnected()
03-17 06:44:14.169  1459  1459 I CscUtil : isWifiOnly = false
03-17 06:44:14.169  1019  1043 W libprocessgroup: failed to open /acct/uid_10065/pid_2200/cgroup.procs: No such file or directory
03-17 06:44:14.169  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.169  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.169  1459  1459 I System.out: HandDataNode = null
03-17 06:44:14.169  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.169  1459  1459 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
03-17 06:44:14.169  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.169  1238  2930 E SQLiteLog: (283) recovered 352 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
03-17 06:44:14.169  1459  1459 I CscUpdateService: This is normal boot : CSC not updated
03-17 06:44:14.179  1459  1472 D TP/MmsSmsProvider: query,matched:7, calling pid = 2387
03-17 06:44:14.179  1459  1472 D TP/MmsSmsProvider: match 7:Elapsed time : 1.827 ms
03-17 06:44:14.179  2387  2961 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 06:44:14.179  2387  2961 D Mms/TelephonyPermission: isDefault true
03-17 06:44:14.179  1459  2963 E CscParser: update(): xml file exist
03-17 06:44:14.189  1019  1342 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2970 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-17 06:44:14.189  1019  1342 I ActivityManager: Killing 2215:com.vlingo.midas/u0a28 (adj 15): empty #31
03-17 06:44:14.199  1459  2963 D CscGPS  : CSCGPS.updateParameters
03-17 06:44:14.199  2970  2970 I libpersona: KNOX_SDCARD checking this for 10155
03-17 06:44:14.199  1459  2963 D CscGPS  : supl host : null
03-17 06:44:14.199  2970  2970 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:14.199  2970  2970 E Zygote  : MountEmulatedStorage()
03-17 06:44:14.199  2970  2970 E Zygote  : v2
03-17 06:44:14.199  1459  2963 D CscGPS  : SUPL Host is null or invalid
03-17 06:44:14.199  1459  2963 D CscGPS  : supl_ver : null
03-17 06:44:14.199  1459  2963 D CscGPS  : SUPL Ver is null or invalid
03-17 06:44:14.199  1459  2963 D CscGPS  : supl port : null
03-17 06:44:14.199  1459  2963 D CscGPS  : SUPL PORT is null or invalid
03-17 06:44:14.199  1459  2963 D CscGPS  : LPP : null
03-17 06:44:14.199  1459  2963 D CscGPS  : LPP is null or invalid
03-17 06:44:14.199  1459  2963 D CscGPS  : CSC don't have any AGPS value.
03-17 06:44:14.199  2952  2952 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:14.199  2970  2970 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:14.199  2387  2387 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
03-17 06:44:14.199  2952  2952 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:14.209  1459  1473 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2387
03-17 06:44:14.209  2970  2970 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:14.209  2850  2850 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 136.565ms
03-17 06:44:14.209  2970  2970 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:14.209  1459  1459 I CscUpdateService: same CSC Version
03-17 06:44:14.209  1459  1459 D CscUtil : Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 06:44:14.209  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:14.209  1019  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:14.209  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-17 06:44:14.219  1238  2930 D MediaScanner: Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 06:44:14.239  2970  2970 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:14.239  2970  2970 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:14.239  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.239  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.239  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.239  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.259  2987  2987 E Zygote  : MountEmulatedStorage()
03-17 06:44:14.259  2987  2987 I libpersona: KNOX_SDCARD checking this for 10043
03-17 06:44:14.259  2987  2987 E Zygote  : v2
03-17 06:44:14.259  2987  2987 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:14.259  2987  2987 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:14.269  2987  2987 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:14.269  2987  2987 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:14.269  1019  1342 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2987 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 06:44:14.279  1459  2142 D TP/MmsSmsProvider: query,matched:200, calling pid = 2387
03-17 06:44:14.289  1459  2142 D TP/MmsSmsProvider: match 200:Elapsed time : 1.271 ms
03-17 06:44:14.289  1238  2930 V MediaScanner: processDirectory :  /system/media
03-17 06:44:14.289  2970  2970 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 06:44:14.289  2387  2387 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-17 06:44:14.289  2387  2986 D Mms/TelephonyPermission: isDefault true
03-17 06:44:14.289  2387  2986 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-17 06:44:14.289  2387  2986 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 127.401094
03-17 06:44:14.299  2987  2987 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:14.299  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 06:44:14.299  2987  2987 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:14.299  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:14.299  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:14.299  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:14.299  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:14.299  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:14.309  1459  1472 D TP/SmsProvider: query,matched:0, calling pid = 2387
03-17 06:44:14.309  1459  1472 D TP/SmsProvider: match 0:Elapsed time : 1.775 ms
03-17 06:44:14.329  2987  2987 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 06:44:14.329  2987  2987 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:14.329  2987  2987 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 06:44:14.329  2903  2903 D AndroidRuntime: 
03-17 06:44:14.329  2903  2903 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 06:44:14.339  2903  2903 D AndroidRuntime: CheckJNI is OFF
03-17 06:44:14.339  2903  2903 D AndroidRuntime: readGMSProperty: start
03-17 06:44:14.339  2903  2903 D AndroidRuntime: readGMSProperty: already setted!!
03-17 06:44:14.339  2903  2903 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 06:44:14.339  2903  2903 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 06:44:14.339  2903  2903 D AndroidRuntime: readGMSProperty: end
03-17 06:44:14.339  2903  2903 D AndroidRuntime: addProductProperty: start
03-17 06:44:14.349  1019  1216 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:14.349  1019  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:14.349  1019  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 06:44:14.349  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:14.349  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:14.349  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 06:44:14.349  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.349  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.349  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.349  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.359  1459  2142 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-17 06:44:14.359  1459  2142 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
03-17 06:44:14.369  1459  2142 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 06:44:14.369  1459  2142 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
03-17 06:44:14.369  3003  3003 E Zygote  : MountEmulatedStorage()
03-17 06:44:14.369  3003  3003 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:14.369  3003  3003 E Zygote  : v2
03-17 06:44:14.369  3003  3003 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:14.369  3003  3003 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:14.369  3003  3003 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:14.369  1459  2142 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
03-17 06:44:14.369  3003  3003 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:14.369  1459  2142 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:14.369  1459  2142 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:14.369  1459  2142 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:14.369  1459  2142 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:14.369  1459  2142 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:14.379  1019  1342 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3003 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 06:44:14.379  1459  2142 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:14.389  1459  2142 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-17 06:44:14.389  1459  2142 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 06:44:14.389  2387  2986 D Mms/Conversation: deleteTempConversation(),deleted=0
03-17 06:44:14.399  3003  3003 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:14.399  3003  3003 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:14.409  2970  2970 D [0]UMC:Core: onCreate(): 
03-17 06:44:14.419   309   309 E USB_UICC: Timeout! No signal received. Retry num = 29
03-17 06:44:14.419  1019  1480 D SettingsProvider: name = block_emergency_message
03-17 06:44:14.419  1019  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:14.419  1019  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:14.419  1019  1480 D SettingsProvider: selectionArgs: false
03-17 06:44:14.419  1019  1480 D SettingsProvider: selectionArgs: 10043
03-17 06:44:14.419  1019  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:14.419  1019  1480 D SettingsProvider: ret = -1
03-17 06:44:14.419  1019  1342 W ActivityManager: getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
03-17 06:44:14.439  1019  1043 W libprocessgroup: failed to open /acct/uid_10028/pid_2215/cgroup.procs: No such file or directory
03-17 06:44:14.479  1459  1863 D SmsProvider: Update uri=content://sms/outbox, match=8
03-17 06:44:14.479  1459  1863 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 06:44:14.489  1459  1472 I art     : Explicit concurrent mark sweep GC freed 39413(2MB) AllocSpace objects, 11(176KB) LOS objects, 45% free, 4MB/8MB, paused 7.964ms total 170.360ms
03-17 06:44:14.489  1238  2930 V MediaScanner:  prescan time: 177ms (DB items: 138)
03-17 06:44:14.489  1238  2930 V MediaScanner:     scan time: 210ms (Caching mode: true), (makeEntry time: 47ms ~22%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 06:44:14.489  1238  2930 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 06:44:14.489  1238  2930 V MediaScanner:    total time: 387ms
03-17 06:44:14.489  1238  2930 V MediaScanner: checked files: 130  directories : 6  (I: 0, U: 0)
03-17 06:44:14.489  1238  2930 D MediaScanner: checkDefaultSounds
03-17 06:44:14.499  1238  2930 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
03-17 06:44:14.499  1019  1542 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:14.499  1019  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:14.499  1019  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
03-17 06:44:14.499  2387  2986 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-17 06:44:14.499  2387  2986 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-17 06:44:14.499  2387  2986 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
03-17 06:44:14.509  1313  1313 I WifiCredService: onCreate
03-17 06:44:14.519  3003  3003 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-17 06:44:14.519  1459  1472 D TP/SmsProvider: query,matched:26, calling pid = 2387
03-17 06:44:14.519  2970  2970 D [0]UMC:DeviceInfo: USA==US==
03-17 06:44:14.529  1459  1473 D TP/SmsProvider: query,matched:51, calling pid = 2387
03-17 06:44:14.529  1459  1472 D TP/SmsProvider: match 26:Elapsed time : 1.857 ms
03-17 06:44:14.529  1459  1473 D TP/SmsProvider: match 51:Elapsed time : 1.924 ms
03-17 06:44:14.529  2387  2961 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 06:44:14.539  2387  2986 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 06:44:14.539  2387  2986 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 06:44:14.539  2387  2986 D Mms/TelephonyPermission: isDefault true
03-17 06:44:14.539  1613  1623 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 06:44:14.549  1459  1472 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2387
03-17 06:44:14.559  1313  1313 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 06:44:14.559  1313  1313 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 06:44:14.559  1313  1313 D MY_TAG  : Action boot completed received
03-17 06:44:14.559  1459  2142 D TP/MmsSmsProvider: query,matched:200, calling pid = 2387
03-17 06:44:14.559  2970  2970 D USER_AGENT: UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
03-17 06:44:14.569  1313  1313 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-17 06:44:14.569  1459  2142 D TP/MmsSmsProvider: match 200:Elapsed time : 2.756 ms
03-17 06:44:14.569  1019  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 06:44:14.569  1019  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 06:44:14.569  1019  1132 E WifiNative-wlan0: invaild command id : 215
03-17 06:44:14.569  2970  2970 D [0]UMC:AdminManager: init - start
03-17 06:44:14.569  1613  1623 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 06:44:14.569  1481  1481 D Launcher.Model: reloadBadges entered.
03-17 06:44:14.569  1613  1623 D BadgeProvider: sendNotify, [notify] : null
03-17 06:44:14.569  1613  1623 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 06:44:14.569  1613  1623 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 06:44:14.569  1613  1623 D BadgeProvider: update, [UpdateCount] : 1
03-17 06:44:14.579  2970  2970 D [0]UMC:AdminManager: loadAdmins
03-17 06:44:14.579  2387  2961 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 06:44:14.579  2387  2961 D Mms/MessagingNotification: remove alarm
03-17 06:44:14.589  3003  3003 D DSM     : [Lines:107] Normal booted
03-17 06:44:14.589  3003  3003 D DSM     : [Lines:114] Boot completed
03-17 06:44:14.589  2970  2970 D [0]UMC:AdminManager: init - end
03-17 06:44:14.589  2970  2970 D GSLBManager: migrateStoredUrlFromOldPref
03-17 06:44:14.599  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-17 06:44:14.609  1019  1480 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-17 06:44:14.609  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.609  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.609  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.609  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.619  2970  2970 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
03-17 06:44:14.619  2970  2970 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-17 06:44:14.619  3033  3033 E Zygote  : MountEmulatedStorage()
03-17 06:44:14.619  3033  3033 E Zygote  : v2
03-17 06:44:14.619  3033  3033 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:14.619  3033  3033 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:14.619  1313  2183 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-17 06:44:14.619  3033  3033 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:14.629  1019  1216 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3033 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 06:44:14.629  3033  3033 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:14.629  1019  1216 I ActivityManager: Killing 2240:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
03-17 06:44:14.629  3033  3033 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:14.629  2970  2970 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
03-17 06:44:14.629  2387  3031 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 06:44:14.629  2970  2970 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 06:44:14.629  2970  2970 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 06:44:14.629  2970  2970 D [0]UMC:UMCAdmin: isContainer : 0
03-17 06:44:14.639  1459  1473 D TP/SmsProvider: query,matched:0, calling pid = 2387
03-17 06:44:14.639  1459  1473 D TP/SmsProvider: match 0:Elapsed time : 1.970 ms
03-17 06:44:14.649  1313  1313 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-17 06:44:14.649  1313  1313 I NearbySettings: MountReceiver.onReceive - Internal Path
03-17 06:44:14.689  3033  3033 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:14.699  3033  3033 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:14.699  1019  1043 W libprocessgroup: failed to open /acct/uid_10045/pid_2240/cgroup.procs: No such file or directory
03-17 06:44:14.699  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 06:44:14.699  1459  2142 D TP/SmsProvider: query,matched:0, calling pid = 2387
03-17 06:44:14.699  1459  2142 D TP/SmsProvider: match 0:Elapsed time : 2.210 ms
03-17 06:44:14.699  1019  1342 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
03-17 06:44:14.709  2970  2970 E [0]UMC:UMCAdmin: No active admin owned by uid 10155
03-17 06:44:14.709  2970  2970 D [0]UMC:UMCAdmin: isContainer : 0
03-17 06:44:14.709  1019  1506 D SettingsProvider: name = personal_mode_enabled
03-17 06:44:14.709  2970  2970 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-17 06:44:14.719  2387  2961 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 425.974115
03-17 06:44:14.719  3033  3033 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 06:44:14.729  2970  2970 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-17 06:44:14.729  2970  2970 D [0]UMC:CoreReceiver:  check PreETag 
,03-17 06:44:14.729  1459  1863 D TP/SmsProvider: query,matched:51, calling pid = 2387
03-17 06:44:14.729  1459  1863 D TP/SmsProvider: match 51:Elapsed time : 2.504 ms
03-17 06:44:14.739  2387  2986 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 06:44:14.739  1019  1032 I art     : Explicit concurrent mark sweep GC freed 136630(7MB) AllocSpace objects, 6(1986KB) LOS objects, 33% free, 22MB/33MB, paused 42.013ms total 239.092ms
03-17 06:44:14.749  1613  3030 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 06:44:14.749  3033  3033 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 06:44:14.759  2970  2970 D [0]UMC:ByodSetupStarter: Container ID : 0
03-17 06:44:14.759  2970  2970 V [0]UMC:Utils: checkAppScreen() : com.sec.android.app.launcher
03-17 06:44:14.759  2970  2970 I [0]UMC:Core: shutdown
03-17 06:44:14.759  2970  2970 I art     : System.exit called, status: 0
03-17 06:44:14.759  2970  2970 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
03-17 06:44:14.759  1238  2930 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-17 06:44:14.769  1238  2930 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
03-17 06:44:14.779  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 06:44:14.779  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
03-17 06:44:14.779  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
03-17 06:44:14.779  3033  3033 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
03-17 06:44:14.789  2903  2903 E AffinityControl: AffinityControl: registerfunction enter
03-17 06:44:14.799  1238  2930 D MediaScanner: OK. notification_sound is already exist in setting DB.
03-17 06:44:14.799  1238  2930 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
03-17 06:44:14.799  1613  3030 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 06:44:14.799  1613  3030 D BadgeProvider: sendNotify, [notify] : null
03-17 06:44:14.799  1613  3030 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 06:44:14.799  1613  3030 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 06:44:14.799  1613  3030 D BadgeProvider: update, [UpdateCount] : 1
03-17 06:44:14.799  1238  2930 D MediaScanner: OK. ringtone is already exist in setting DB.
03-17 06:44:14.799  1481  1481 D Launcher.Model: reloadBadges entered.
03-17 06:44:14.809  1238  2930 D MediaScannerService: !@done scanning volume internal
03-17 06:44:14.809  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-17 06:44:14.809  2576  2576 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2576) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 06:44:14.809  2576  2576 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2576) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-17 06:44:14.809  2576  2576 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2576) ACTION_MEDIA_SCANNER_FINISHED = Ignored
03-17 06:44:14.819  2387  2986 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 06:44:14.819  1459  1459 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 06:44:14.819  1459  1459 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 06:44:14.819  1459  1459 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:44:14.819  1459  1459 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:14.819  1459  1459 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:14.819  1459  1459 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 06:44:14.819  2903  2903 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 06:44:14.819  1238  2930 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
03-17 06:44:14.829  1019  1517 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2970)(adj 0) has died(42,684)
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-17 06:44:14.829  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-17 06:44:14.839  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-17 06:44:14.839  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-17 06:44:14.839  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-17 06:44:14.839  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-17 06:44:14.839  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 06:44:14.839  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-17 06:44:14.839  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-17 06:44:14.839  3033  3033 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-17 06:44:14.839  2387  2986 D Mms/MessagingNotification: remove alarm
03-17 06:44:14.839  3033  3033 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-17 06:44:14.849  1019  1542 E PersonaManagerService: inState():  stateMachine is null !!
03-17 06:44:14.849  1019  1542 I PersonaManagerService: PersonaId don't exist
03-17 06:44:14.849  1019  1542 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 06:44:14.849  1019  1542 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 06:44:14.859  1803  1803 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 06:44:14.859  1803  1803 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 06:44:14.859  1803  1803 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 06:44:14.859  1238  2930 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 06:44:14.859  1238  2930 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
03-17 06:44:14.859  1803  1803 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 06:44:14.859  1238  2930 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
03-17 06:44:14.859  1238  2930 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 06:44:14.859  1238  2930 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 06:44:14.859  1238  2930 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-17 06:44:14.859  1238  2930 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
03-17 06:44:14.869  1803  1803 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-17 06:44:14.869  1238  2930 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 06:44:14.869  1019  1542 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 06:44:14.869  1803  1803 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
03-17 06:44:14.869  1019  1542 W ActivityManager: mDVFSHelper.acquire()
03-17 06:44:14.869  1803  1803 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 06:44:14.869  1803  1803 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 06:44:14.869  1803  1803 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 06:44:14.869  1803  1803 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 06:44:14.869  1803  1803 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 06:44:14.869  1803  1803 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
03-17 06:44:14.869  1238  2930 D MediaScanner: Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 06:44:14.869  1019  1542 D FocusedStackFrame: Set to : 0
03-17 06:44:14.879  1019  1542 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 06:44:14.879  1481  1481 D Launcher.HomeView: onPause
03-17 06:44:14.879  1019  1542 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 06:44:14.879  1019  1542 D InputDispatcher: Focused application set to: xxxx
03-17 06:44:14.879  1019  1542 D InputDispatcher: Focus left window: 1481
03-17 06:44:14.879  1019  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 06:44:14.879  1019  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 06:44:14.879  2903  2903 D AndroidRuntime: Shutting down VM
03-17 06:44:14.879  2387  3054 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 06:44:14.879  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 06:44:14.879  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.879  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.879  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.879  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.889  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 06:44:14.889  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 06:44:14.889  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 06:44:14.889  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 06:44:14.899   259   259 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 06:44:14.899  3059  3059 E Zygote  : MountEmulatedStorage()
03-17 06:44:14.899  3059  3059 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:14.899  3059  3059 E Zygote  : v2
03-17 06:44:14.899  3059  3059 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:14.899  1238  2930 V MediaScanner: processDirectory :  /storage/emulated/0
03-17 06:44:14.899  3059  3059 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:14.899  3059  3059 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:14.899  1238  2930 D MediaScanner: Skipping:
03-17 06:44:14.899  1019  1342 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3059 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 06:44:14.899  1238  2930 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
03-17 06:44:14.899  3059  3059 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:14.909  1019  1342 I ActivityManager: Killing 1500:com.android.printspooler/u0a132 (adj 15): empty #31
03-17 06:44:14.909  1019  1480 I ActivityManager: Killing 2299:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
03-17 06:44:14.919  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.919  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.919  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.919  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.919  1238  2930 D MediaScanner: Skipping:
03-17 06:44:14.919  1238  2930 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-17 06:44:14.919  1238  2930 V MediaScanner: processDirectory :  /storage/extSdCard
03-17 06:44:14.919  1238  2930 W MediaScanner: Error opening directory, reason : Permission denied.
03-17 06:44:14.919  1238  2930 W MediaScanner: 7klwibgf7fxlKdCbid7
03-17 06:44:14.929  1238  2930 V MediaScanner:  prescan time: 31ms (DB items: 26)
03-17 06:44:14.929  1238  2930 V MediaScanner:     scan time: 21ms (Caching mode: true), (makeEntry time: 12ms ~57%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 06:44:14.929  1238  2930 V MediaScanner: postscan time: 6ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 06:44:14.929  1238  2930 V MediaScanner:    total time: 58ms
03-17 06:44:14.929  1238  2930 V MediaScanner: checked files: 10  directories : 16  (I: 0, U: 0)
03-17 06:44:14.939  3059  3059 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:14.939  3071  3071 E Zygote  : MountEmulatedStorage()
03-17 06:44:14.939  3071  3071 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:14.939  3059  3059 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:14.939  3071  3071 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:14.939  3071  3071 E Zygote  : v2
03-17 06:44:14.939  3071  3071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:14.939  3071  3071 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:14.949  3071  3071 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:14.949  1019  1342 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3071 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 06:44:14.949  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.949  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.949  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.949  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:14.959   343   343 I ServiceManager: Waiting for service AtCmdFwd...
03-17 06:44:14.969  3089  3089 E Zygote  : MountEmulatedStorage()
03-17 06:44:14.969  3089  3089 I libpersona: KNOX_SDCARD checking this for 10167
03-17 06:44:14.969  3089  3089 E Zygote  : v2
03-17 06:44:14.969  3089  3089 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:14.969  3089  3089 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:14.979  3089  3089 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:14.979  3089  3089 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 06:44:14.979  1019  1506 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 06:44:14.979  1019  1506 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4301, temperature: 245, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 06:44:14.979  1019  1506 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 06:44:14.989  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 06:44:14.989  3071  3071 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:14.989  3071  3071 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:14.999  1019  1032 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3089 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 06:44:14.999  3089  3089 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:14.999  3089  3089 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:14.999  1238  2930 D MediaScannerService: !@done scanning volume external
03-17 06:44:14.999  1019  1543 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 06:44:14.999  1019  1543 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 06:44:14.999  1019  1543 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 06:44:15.009  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 06:44:15.019  1019  1543 D PersonaManager: isKioskContainerExistOnDevice
03-17 06:44:15.029  1313  1313 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 06:44:15.029  1313  1313 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-17 06:44:15.029  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{10c406c4 token=android.os.BinderProxy@c16949d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 06:44:15.029  1481  1481 D Launcher.HomeView: onStop
03-17 06:44:15.039  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{10c406c4 token=android.os.BinderProxy@c16949d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 06:44:15.039  1481  1481 D Launcher: onTrimMemory. Level: 20
03-17 06:44:15.039  1019  1342 D SettingsProvider: name = aw_daemon_service_key_version_check
03-17 06:44:15.039  1019  1342 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:15.039  1019  1342 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:15.039  1019  1342 D SettingsProvider: selectionArgs: false
03-17 06:44:15.039  1019  1342 D SettingsProvider: selectionArgs: 10157
03-17 06:44:15.039  1019  1043 W libprocessgroup: failed to open /acct/uid_10110/pid_2299/cgroup.procs: No such file or directory
03-17 06:44:15.039  1019  1342 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:15.039  1019  1342 D SettingsProvider: ret = -1
03-17 06:44:15.039  1459  3020 D TP/SmsProvider: query,matched:0, calling pid = 2387
03-17 06:44:15.049  1019  1342 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10157
03-17 06:44:15.049  2576  2576 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2576) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 06:44:15.049  1019  1043 W libprocessgroup: failed to open /acct/uid_10132/pid_1500/cgroup.procs: No such file or directory
03-17 06:44:15.059  1803  1803 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-17 06:44:15.059  1459  3020 D TP/SmsProvider: match 0:Elapsed time : 13.887 ms
03-17 06:44:15.059  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 06:44:15.059  2576  2576 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2576) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-17 06:44:15.069  1803  1803 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
03-17 06:44:15.069  1313  1313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
03-17 06:44:15.069  2576  2576 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2576) ...
03-17 06:44:15.069  2576  2576 D FactoryTestApp: [Support$Values.getString](2576) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 06:44:15.069  2576  2576 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2576) mConnectionMode = gsm
03-17 06:44:15.069  2576  2576 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2576) Create IPCWriterToSecPhoneService
03-17 06:44:15.069  2576  2576 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2576)  
03-17 06:44:15.069  1803  1803 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 06:44:15.079  1803  1803 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 06:44:15.079  2576  2576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
03-17 06:44:15.079  1803  1803 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
03-17 06:44:15.079  1803  1803 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-17 06:44:15.079  1313  1313 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
03-17 06:44:15.079  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:15.079  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:15.079  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-17 06:44:15.089  3071  3071 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:44:15.089  1803  1803 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
03-17 06:44:15.089  1803  1803 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 06:44:15.089  1803  1803 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458193455101
03-17 06:44:15.089  1803  1803 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458215040000
03-17 06:44:15.099  2903  2903 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 06:44:15.099  1803  1803 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-17 06:44:15.099  1803  1803 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
03-17 06:44:15.109  1019  1019 I MotionRecognitionService: Plugged
03-17 06:44:15.109  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
03-17 06:44:15.109  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 06:44:15.109  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 06:44:15.109  1418  1418 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 06:44:15.109  1418  1418 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 06:44:15.109  1174  1174 D PowerUI : Cable  true --> true mBootCompleted : true
03-17 06:44:15.109  1174  1174 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,03-17 06:44:15.119  2617  2617 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 06:44:15.119  2617  2712 D HeadsetStateMachine: Disconnected process message: 10
,03-17 06:44:15.129  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 06:44:15.129  1019  1019 D SensorService: [SO] activate (ident=0xb83903b8, enabled=0)
03-17 06:44:15.129  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 06:44:15.129  2387  2986 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 412.014791
,03-17 06:44:15.129  1803  1803 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458215040000
,03-17 06:44:15.139  1803  1803 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,03-17 06:44:15.139  1803  1803 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458215040000
03-17 06:44:15.139  1019  1019 D SensorManager: unregisterListener ::   
03-17 06:44:15.139  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 06:44:15.139  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-17 06:44:15.139  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 06:44:15.139  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 06:44:15.139  1174  1174 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 06:44:15.139  1174  1174 D SViewCoverView: level :100 plugged : 2
,03-17 06:44:15.139  1019  1019 D SensorService: [SO] changed settle time [1]
,03-17 06:44:15.139  1019  1019 D SensorService: [SO] setDelay [66000000]
03-17 06:44:15.139  1019  1019 D SensorService: [SO] activate (ident=0xb83903b8, enabled=1)
03-17 06:44:15.139  1019  1019 D SensorService: [SO] AR_init
03-17 06:44:15.139  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 06:44:15.149  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 06:44:15.149  2576  2576 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2576) connected done
03-17 06:44:15.149  2576  2576 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2576) Send Response Message to SecPhone
03-17 06:44:15.149  2576  2576 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2576) Response ��
,03-17 06:44:15.159   337  1076 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 06:44:15.159  2576  2576 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2576) Send BOOTING COMPLETED done
,03-17 06:44:15.169  1803  1803 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,03-17 06:44:15.169  1803  1803 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 06:44:15.169  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.169  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.169  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.169  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.179  3109  3109 E Zygote  : MountEmulatedStorage()
,03-17 06:44:15.179  3109  3109 E Zygote  : v2
03-17 06:44:15.179  3109  3109 I libpersona: KNOX_SDCARD checking this for 10082
03-17 06:44:15.179  3109  3109 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:15.179  3109  3109 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:15.189  1019  1539 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3109 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
,03-17 06:44:15.189  3109  3109 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:15.189  1019  1539 I ActivityManager: Killing 1642:com.google.android.partnersetup/u0a14 (adj 15): empty #31
03-17 06:44:15.189  3109  3109 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:15.189  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.189  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.189  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.189  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.199  3059  3059 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 06:44:15.199   327   327 I art     : Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 664us total 20.143ms
,03-17 06:44:15.209  3109  3109 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:15.209  3109  3109 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.209  1313  1313 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-17 06:44:15.219  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 06:44:15.219   327   327 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.881ms
,03-17 06:44:15.239   327   327 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.755ms
,03-17 06:44:15.249  3125  3125 E Zygote  : MountEmulatedStorage(),
03-17 06:44:15.249  3125  3125 E Zygote  : v2
03-17 06:44:15.249  3125  3125 I libpersona: KNOX_SDCARD checking this for 10161
03-17 06:44:15.249  3125  3125 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:15.259  3125  3125 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 06:44:15.259  3125  3125 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:15.259  1019  1539 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3125 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 06:44:15.259  3125  3125 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 06:44:15.269   337  1076 D AT_Distributor: SetAtdStatus(), 1_1_0
03-17 06:44:15.269   337  1076 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 06:44:15.269  3089  3089 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-17 06:44:15.289  1019  1041 D SensorService: [SO] currT = 36062074000, prevT = 35702243000, diff = 359831000, [-0.460 0.192 9.902]
03-17 06:44:15.289  1019  1041 D SensorService: [SO] -0.460 0.192 9.902
03-17 06:44:15.289  1019  1041 D SensorService: [SO] [100 -> 255]
,03-17 06:44:15.299  3089  3089 I LibraryLoader: Loading: webviewchromium
,03-17 06:44:15.299  1313  1313 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-17 06:44:15.299  1313  1313 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-17 06:44:15.299  3089  3089 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 6069-6075)
03-17 06:44:15.299  3089  3089 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 06:44:15.299  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 06:44:15.299  1313  1313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-17 06:44:15.299  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:15.299  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:15.299  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:15.299  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:15.299  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:15.309  1313  3140 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-17 06:44:15.319  3125  3125 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:15.319  1019  1043 W libprocessgroup: failed to open /acct/uid_10014/pid_1642/cgroup.procs: No such file or directory
,03-17 06:44:15.319  3125  3125 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.319  1019  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.319  1019  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.319  1019  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.319  1019  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.339  3145  3145 E Zygote  : MountEmulatedStorage()
03-17 06:44:15.339  3145  3145 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:15.339  3145  3145 E Zygote  : v2
,03-17 06:44:15.339  3145  3145 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:15.339  3089  3089 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d859e9c}
03-17 06:44:15.339  3089  3089 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 06:44:15.339  1019  1542 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3145 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 06:44:15.339  3089  3089 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 06:44:15.349  3145  3145 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:15.349  3145  3145 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:15.349  3145  3145 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:15.349  2617  2716 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-17 06:44:15.349  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.349  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.349  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.349  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.369  3059  3059 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 06:44:15.379  3145  3145 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:15.379  3145  3145 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.379  3089  3089 I BrowserStartupController: Initializing chromium process, renderers=0
03-17 06:44:15.379  3089  3089 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 06:44:15.389  3160  3160 I libpersona: KNOX_SDCARD checking this for 10146
03-17 06:44:15.389  3160  3160 E Zygote  : MountEmulatedStorage()
03-17 06:44:15.389  3160  3160 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:15.389  3160  3160 E Zygote  : v2
03-17 06:44:15.389  1019  1543 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3160 uid=10146 gids={50146, 9997} abi=armeabi-v7a
,03-17 06:44:15.389  3160  3160 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:15.389  3160  3160 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:15.399  3160  3160 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 06:44:15.399  3059  3059 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 06:44:15.399  2617  2716 D BluetoothMediaBrowser: no now playing list
03-17 06:44:15.399  2617  2716 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-17 06:44:15.409  3089  3089 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
03-17 06:44:15.409  3145  3145 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:15.409  3089  3089 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
03-17 06:44:15.419  3089  3089 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,03-17 06:44:15.419   309   309 E USB_UICC: Timeout! No signal received. Retry num = 30
,03-17 06:44:15.429  3160  3160 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:15.429  3160  3160 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.449  3089  3089 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 06:44:15.449  3089  3089 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 06:44:15.449  3089  3089 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 06:44:15.449  3089  3089 I Adreno-EGL: Local Branch: 
03-17 06:44:15.449  3089  3089 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 06:44:15.449  3089  3089 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 06:44:15.449  3089  3089 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 06:44:15.459   259   452 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-17 06:44:15.459   259   773 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-17 06:44:15.519  3059  3059 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-17 06:44:15.529  3059  3059 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,03-17 06:44:15.529  3059  3059 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-17 06:44:15.529  3059  3059 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 06:44:15.569  3109  3109 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:15.579   309   309 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 06:44:15.579   309   309 E USB_UICC: usb_uicc_init_qmi failed ! 
03-17 06:44:15.579   309   309 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 06:44:15.579   309   309 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-17 06:44:15.589  3109  3109 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:15.589  3125  3189 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 06:44:15.589  3125  3189 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 06:44:15.589  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{2a34867c u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-17 06:44:15.619  3125  3189 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...,
,03-17 06:44:15.669  3109  3109 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:15.679  3109  3109 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:15.689  3125  3189 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 06:44:15.689  3125  3189 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3696d830: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 06:44:15.689  3125  3189 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 06:44:15.689  3109  3109 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:15.699  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.699  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.699  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.699  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.709  3145  3145 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 06:44:15.709  3109  3109 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:15.719  3209  3209 E Zygote  : MountEmulatedStorage()
03-17 06:44:15.719  3209  3209 E Zygote  : v2
03-17 06:44:15.719  3209  3209 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:15.719  3209  3209 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:15.719  3209  3209 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:15.719  1019  1506 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3209 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 06:44:15.719  3209  3209 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:15.719  3209  3209 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 06:44:15.719  1019  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.719  1019  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 06:44:15.719  1019  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.719  1019  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.739  3223  3223 E Zygote  : MountEmulatedStorage()
03-17 06:44:15.739  3223  3223 I libpersona: KNOX_SDCARD checking this for 10088
03-17 06:44:15.739  3223  3223 E Zygote  : v2
03-17 06:44:15.739  3223  3223 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:15.739  3223  3223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:15.739  1019  1542 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3223 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:15.739  3223  3223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:15.739  3223  3223 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 06:44:15.779  3223  3223 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:15.779  3223  3223 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.779  3145  3145 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 06:44:15.789  3209  3209 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:15.789  3209  3209 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.789  3145  3145 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-17 06:44:15.789  3145  3145 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-17 06:44:15.809  3089  3185 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-17 06:44:15.959  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.959  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.959  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:15.959  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:15.959   343   343 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 06:44:15.969  3249  3249 E Zygote  : MountEmulatedStorage(),
03-17 06:44:15.969  3249  3249 E Zygote  : v2
03-17 06:44:15.969  3249  3249 I libpersona: KNOX_SDCARD checking this for 10008
03-17 06:44:15.969  3249  3249 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:15.969  3249  3249 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:15.969  1019  1539 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3249 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:44:15.979  3249  3249 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 06:44:15.979  3249  3249 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 06:44:15.989  3209  3209 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-17 06:44:15.989  3209  3209 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 06:44:15.999  3249  3249 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:15.999  3249  3249 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:15.999  3209  3257 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-17 06:44:15.999  3209  3209 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
03-17 06:44:16.009  3209  3209 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
03-17 06:44:16.009  3209  3209 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
03-17 06:44:16.009  3209  3209 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-17 06:44:16.009  3209  3209 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
03-17 06:44:16.009  3209  3209 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,03-17 06:44:16.009  3209  3209 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 06:44:16.009  3209  3209 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
03-17 06:44:16.019  3209  3209 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-17 06:44:16.019  3209  3209 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
03-17 06:44:16.019  3089  3089 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-17 06:44:16.019  3209  3209 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-17 06:44:16.069  3209  3257 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-17 06:44:16.089  3209  3257 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-17 06:44:16.109  1019  1342 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:16.109  1019  1342 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-17 06:44:16.109  1019  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 06:44:16.119  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.119  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.119  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.119  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.119  3145  3145 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-17 06:44:16.119  3145  3145 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-17 06:44:16.119  3145  3145 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-17 06:44:16.129   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 06:44:16.129   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:16.129  3089  3089 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 06:44:16.129  3125  3125 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
03-17 06:44:16.129  3272  3272 E Zygote  : MountEmulatedStorage()
03-17 06:44:16.129  3272  3272 E Zygote  : v2
03-17 06:44:16.129  3272  3272 I libpersona: KNOX_SDCARD checking this for 10088
03-17 06:44:16.129  3272  3272 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:16.129  3272  3272 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:16.139  1019  1342 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3272 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:44:16.139  1019  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:16.139  1019  1080 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,03-17 06:44:16.139  1019  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 06:44:16.139  3272  3272 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:16.139  3272  3272 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 06:44:16.139  3145  3145 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
03-17 06:44:16.139  3089  3089 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 06:44:16.139  3145  3145 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-17 06:44:16.139  3145  3145 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!,
,03-17 06:44:16.149  3145  3145 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 06:44:16.159  3145  3145 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-17 06:44:16.159  1174  1174 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-17 06:44:16.159  3089  3089 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-17 06:44:16.159  3089  3089 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 06:44:16.159  3145  3145 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-17 06:44:16.169  3145  3145 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-17 06:44:16.169  3089  3089 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 06:44:16.169  3145  3145 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-17 06:44:16.169  3145  3145 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-17 06:44:16.169  3145  3145 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-17 06:44:16.179  1174  1174 D OverheatReceiver: into the SAFE_MODE_ACTION
03-17 06:44:16.179  1174  1174 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-17 06:44:16.179  3272  3272 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:16.179  1174  1174 D OverheatReceiver: isSafeMode = false
,03-17 06:44:16.179  3272  3272 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:16.179  3089  3089 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:44:16.179  3089  3089 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:44:16.189  3145  3145 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-17 06:44:16.189  1459  1459 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-17 06:44:16.189  3145  3240 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-17 06:44:16.199  3145  3145 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,03-17 06:44:16.199  1019  1032 D SettingsProvider: name = internet_call_settings_visibility
,03-17 06:44:16.199  1019  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:16.199  1019  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:16.199  1019  1032 D SettingsProvider: selectionArgs: false
03-17 06:44:16.199  1019  1032 D SettingsProvider: selectionArgs: 1001
03-17 06:44:16.199  1019  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:16.199  1019  1032 D SettingsProvider: ret = -1
,03-17 06:44:16.199  1459  1459 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 06:44:16.199  3145  3145 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-17 06:44:16.209  3145  3240 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 06:44:16.219  3145  3240 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-17 06:44:16.219  3145  3145 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-17 06:44:16.219  1019  1216 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:16.219  1019  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:16.219  1019  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
03-17 06:44:16.219  3145  3145 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-17 06:44:16.219  3145  3145 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-17 06:44:16.239  3145  3145 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-17 06:44:16.239  3145  3145 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-17 06:44:16.239  3209  3257 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 06:44:16.249  3209  3257 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 06:44:16.249  3145  3145 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
03-17 06:44:16.249  3089  3300 D OpenGLRenderer: Render dirty regions requested: true
,03-17 06:44:16.259  1019  1342 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 06:44:16.259  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 06:44:16.259  1019  1342 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 06:44:16.259  1019  1342 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 06:44:16.259  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 06:44:16.269  3089  3089 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 06:44:16.269  3089  3089 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 06:44:16.279  3145  3145 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-17 06:44:16.279  1428  1428 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-17 06:44:16.279  1019  1216 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:16.279  1019  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:16.279  1019  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 06:44:16.289  1019  1542 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:16.289  1019  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:16.289  1019  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 06:44:16.289  3223  3223 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
03-17 06:44:16.289   259   259 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 06:44:16.299  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.299  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.299  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.299  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.309  1019  1544 D InputDispatcher: Focus entered window: 3089
,03-17 06:44:16.309  3303  3303 E Zygote  : MountEmulatedStorage()
03-17 06:44:16.309  3303  3303 E Zygote  : v2
03-17 06:44:16.309  3303  3303 I libpersona: KNOX_SDCARD checking this for 10052
03-17 06:44:16.309  3303  3303 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:16.309  3303  3303 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:16.319  3303  3303 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:16.319  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 06:44:16.319  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 06:44:16.319  3303  3303 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 06:44:16.319  3089  3089 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 06:44:16.319  3089  3300 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 06:44:16.319  1019  1506 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3303 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-17 06:44:16.319  3209  3257 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 06:44:16.329  3089  3300 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 06:44:16.329  3089  3300 D OpenGLRenderer: Enabling debug mode 0
,03-17 06:44:16.329  3209  3257 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
03-17 06:44:16.329  3209  3242 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 06:44:16.329  3209  3257 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
03-17 06:44:16.329  3209  3242 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 06:44:16.339  1019  1506 I ActivityManager: Killing 2371:com.sec.modem.settings/1000 (adj 15): empty #31
,03-17 06:44:16.339   296   296 E SMD     : DCD OFF
,03-17 06:44:16.339  3209  3242 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 06:44:16.349  3145  3240 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
03-17 06:44:16.349  3303  3303 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:16.349  3303  3303 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:16.359  3209  3222 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 06:44:16.359  3209  3222 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 06:44:16.369  3209  3222 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 06:44:16.369  3209  3257 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 06:44:16.449  1019  1080 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 06:44:16.459  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.459  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.459  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.459  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.469  3209  3257 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
03-17 06:44:16.469  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2371/cgroup.procs: No such file or directory
,03-17 06:44:16.479  3328  3328 E Zygote  : MountEmulatedStorage()
03-17 06:44:16.479  3328  3328 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:16.479  3328  3328 E Zygote  : v2
03-17 06:44:16.479  3328  3328 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:16.479  3328  3328 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:16.479  1019  3327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:44:16.479  3209  3257 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
03-17 06:44:16.479  3328  3328 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:16.479  1174  1174 I StatusBar: Icon Only
03-17 06:44:16.479  3209  3257 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
03-17 06:44:16.479  1174  1174 D PanelView: There is/are notification(s) 
,03-17 06:44:16.479  3328  3328 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:16.479  3209  3257 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
03-17 06:44:16.479  3209  3258 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 06:44:16.489  1019  1342 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3328 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 06:44:16.489  1019  1342 I ActivityManager: Killing 2435:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-17 06:44:16.489  1019  1342 I ActivityManager: Killing 2412:com.sec.tcpdumpservice/1000 (adj 15): empty #32
03-17 06:44:16.489  1019  1342 I ActivityManager: Killing 2400:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #33
,03-17 06:44:16.489  3209  3257 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
,03-17 06:44:16.489  1019  3335 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-17 06:44:16.489  3089  3089 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@578261b time:37269
03-17 06:44:16.499  3209  3257 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/06:44:16
,03-17 06:44:16.499  3209  3258 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 06:44:16.499  1428  1428 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
03-17 06:44:16.499  3209  3258 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
03-17 06:44:16.509  3209  3257 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
03-17 06:44:16.509  3209  3257 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-17 06:44:16.509  3209  3258 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 06:44:16.509  3209  3258 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 06:44:16.509  3209  3258 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 06:44:16.519  1019  1050 I ActivityManager: Displayed Component not be shown by security: +1s567ms
,03-17 06:44:16.519  3328  3328 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:16.519  1019  1050 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
03-17 06:44:16.519  3328  3328 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:16.519  1019  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 06:44:16.519  1019  1050 D CustomFrequencyManagerService: FrequencyrequestList.getNextMaxCPUCoreRequest, index: 1
,03-17 06:44:16.519  1019  1050 W ActivityManager: mDVFSHelper.release()
,03-17 06:44:16.519  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2be521c0 u0 com.test.thalitest/.MainActivity t11} time:37297
,03-17 06:44:16.519  3209  3258 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 06:44:16.529  3209  3258 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-17 06:44:16.529  3209  3258 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 06:44:16.529  3223  3223 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-17 06:44:16.529  3209  3258 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 06:44:16.589  3328  3328 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-17 06:44:16.619  3209  3257 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 06:44:16.639  3223  3223 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-17 06:44:16.649  3223  3223 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-17 06:44:16.649  1857  1857 I SamsungIME: getCurrentCandidateView
,03-17 06:44:16.649  3223  3223 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-17 06:44:16.649  3145  3240 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-17 06:44:16.669  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2435/cgroup.procs: No such file or directory
,03-17 06:44:16.669  1019  1043 W libprocessgroup: failed to open /acct/uid_10127/pid_2400/cgroup.procs: No such file or directory
03-17 06:44:16.669  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2412/cgroup.procs: No such file or directory
,03-17 06:44:16.679  3209  3258 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 06:44:16.709  3328  3328 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 06:44:16.709  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.709  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.709  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.709  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.709  3328  3328 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 06:44:16.709  3328  3328 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 06:44:16.709  3145  3240 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 06:44:16.719  3209  3257 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1,
,03-17 06:44:16.719  3352  3352 E Zygote  : MountEmulatedStorage()
03-17 06:44:16.719  3352  3352 E Zygote  : v2
03-17 06:44:16.719  3352  3352 I libpersona: KNOX_SDCARD checking this for 10014
03-17 06:44:16.719  3352  3352 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:16.719  3352  3352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:16.729  3352  3352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 06:44:16.729  1019  1342 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3352 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a,
,03-17 06:44:16.729  3352  3352 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:16.739  3145  3240 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-17 06:44:16.739  3145  3240 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 06:44:16.739  3209  3257 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
03-17 06:44:16.739  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.739  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.739  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.739  1019  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.749  3209  3258 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] ,
,03-17 06:44:16.759  3369  3369 E Zygote  : MountEmulatedStorage()
,03-17 06:44:16.759  3369  3369 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:16.759  3369  3369 E Zygote  : v2
03-17 06:44:16.759  3369  3369 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:16.759  3369  3369 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:16.759  3369  3369 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 06:44:16.759  3369  3369 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:16.769  1019  1539 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3369 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-17 06:44:16.769  3223  3223 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
03-17 06:44:16.769  3352  3352 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:16.769  3352  3352 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:16.789  1019  1080 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:16.789  1019  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:16.789  1019  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 06:44:16.789   327   327 I art     : Explicit concurrent mark sweep GC freed 8707(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 26.569ms
,03-17 06:44:16.789  3223  3223 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 06:44:16.799  3369  3369 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:16.799  3369  3369 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:16.809  1857  1857 D SamsungIME: Dismiss ExpandCandiate
,03-17 06:44:16.809   327   327 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 18.144ms
,03-17 06:44:16.819  1019  1543 D LocationManagerService: getProviders()=[passive]
,03-17 06:44:16.819  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 06:44:16.829   327   327 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 17.435ms
,03-17 06:44:16.839   286   699 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
,03-17 06:44:16.839   286   699 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 06:44:16.839   286   699 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 06:44:16.839   286   699 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 06:44:16.839   286   699 I str_params: key: 'call_forwarding' value: ''
,03-17 06:44:16.839  1934  1934 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 06:44:16.849  1934  1934 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-17 06:44:16.849  1934  1934 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-17 06:44:16.859  1934  1934 D ScoverManager: serviceVersion : 16908288
,03-17 06:44:16.859  1019  1517 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 06:44:16.859   259   773 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-17 06:44:16.859   259   441 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-17 06:44:16.859  3223  3223 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 06:44:16.879  1934  1934 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-17 06:44:16.879  1428  1428 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-17 06:44:16.879  1019  1543 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 06:44:16.879  1934  1934 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-17 06:44:16.879  1934  1934 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-17 06:44:16.879  1934  1934 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-17 06:44:16.889  1934  1934 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-17 06:44:16.889  1934  1934 I InCall  : CallSContextMotion - stopPutDownListening
,03-17 06:44:16.919  3369  3369 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-17 06:44:16.919  3369  3369 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 06:44:16.919  3369  3369 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 06:44:16.929  3369  3382 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 06:44:16.939  3303  3390 I Velvet.VelvetFactory: refreshing internal icing corpora
,03-17 06:44:16.939  3303  3390 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 06:44:16.939  1019  1543 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:16.939  1019  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:16.939  1019  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 06:44:16.959   343   343 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 06:44:16.959  3328  3328 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 06:44:16.959  3328  3328 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 06:44:16.959  3328  3328 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 06:44:16.969  1019  1542 I ActivityManager: Killing 2528:com.sec.android.app.camera/u0a135 (adj 15): empty #31
03-17 06:44:16.969  1019  1542 I ActivityManager: Killing 2511:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #32
,03-17 06:44:16.969  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.969  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.969  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:16.969  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:16.969  1934  1934 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 06:44:16.979  1174  1174 D PhoneStatusBarView: setCallBackground:0
,03-17 06:44:16.979  1857  1857 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 06:44:16.979  3397  3397 E Zygote  : MountEmulatedStorage()
03-17 06:44:16.979  3397  3397 E Zygote  : v2
03-17 06:44:16.979  3397  3397 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:16.979  3397  3397 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:16.979  3397  3397 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:16.989  1019  1480 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3397 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 06:44:16.989  3397  3397 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:16.989  3397  3397 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:16.989  1019  1031 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 06:44:16.989  1934  1934 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-17 06:44:17.009  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:17.009  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:17.009  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 06:44:17.019  3397  3397 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 06:44:17.019  3397  3397 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:17.029  3209  3258 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-17 06:44:17.049  3303  3390 I Velvet.VelvetFactory: refreshing search history.
,03-17 06:44:17.049  1934  1934 D VideoCallManager: Instantiating VideoCallManager
,03-17 06:44:17.069  3209  3258 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 06:44:17.069  1019  1032 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 06:44:17.079  1019  1043 W libprocessgroup: failed to open /acct/uid_10139/pid_2511/cgroup.procs: No such file or directory
,03-17 06:44:17.079  3209  3258 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 06:44:17.079  1019  1043 W libprocessgroup: failed to open /acct/uid_10135/pid_2528/cgroup.procs: No such file or directory
,03-17 06:44:17.079  1019  1542 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 06:44:17.079  1019  1080 I AudioService: getStreamVolume 3 index 0
,03-17 06:44:17.089  3397  3397 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 06:44:17.089  3303  3303 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-17 06:44:17.089  3397  3397 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 06:44:17.099  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:17.099  1019  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:17.099  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:17.119  1934  1934 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 06:44:17.119  1934  1934 I GFX construct_block_size_descriptor_2d second part: took 2.894375ms for 0*0 texture 0
,03-17 06:44:17.129  1934  1934 I GFX generate_partition_tables: took 5.303021ms for 0*0 texture 0
,03-17 06:44:17.129  1934  1934 I GFX raster: took 12.375885ms for 176*144 texture 0
03-17 06:44:17.129  1934  1934 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb80d8548 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb80d7e18 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 06:44:17.139  3303  3303 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
03-17 06:44:17.139  3303  3303 I ContactLabelSupplier: get() : Execute runnable (UI thread)
,03-17 06:44:17.139  3089  3089 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 06:44:17.149  1934  1934 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-17 06:44:17.149  1934  1934 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 06:44:17.149  1934  1934 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 06:44:17.149  1934  1934 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 06:44:17.149  1934  1934 I Adreno-EGL: Local Branch: 
03-17 06:44:17.149  1934  1934 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 06:44:17.149  1934  1934 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 06:44:17.149  1934  1934 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 06:44:17.169  3223  3223 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,03-17 06:44:17.179  1934  1934 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 06:44:17.189  1934  1934 I glCompressedTexImage2D: took 0.477395ms for 320*61440 texture 37809,
,03-17 06:44:17.199  1934  1934 I draw setup: took 11.107657ms for 320*240 texture 37809,
03-17 06:44:17.199  1934  1934 E GFX GPU raster: drawn
,03-17 06:44:17.199  1934  1934 I GFX GPU raster ASTC: took 44.490521ms for 320*240 texture 12
03-17 06:44:17.199  1934  1934 I GFX raster: took 44.563958ms for 320*240 texture 0
03-17 06:44:17.199  1934  1934 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb80d84c8 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb80d8030 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 06:44:17.209  1857  1857 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 06:44:17.209  1934  1934 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 06:44:17.219  3089  3347 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-17 06:44:17.219  3089  3347 I chromium: 
,03-17 06:44:17.219  1934  1934 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 06:44:17.219  1934  1934 I glCompressedTexImage2D: took 0.366667ms for 480*122880 texture 37813
03-17 06:44:17.219  1934  1934 I draw setup: took 0.901405ms for 480*640 texture 37813
03-17 06:44:17.219  1934  1934 E GFX GPU raster: drawn
,03-17 06:44:17.229  1934  1934 I GFX GPU raster ASTC: took 8.273959ms for 480*640 texture 12
03-17 06:44:17.229  1934  1934 I GFX raster: took 8.354011ms for 480*640 texture 0
03-17 06:44:17.229  1934  1934 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb80d8030 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8319a88 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 06:44:17.239  1857  1857 I SamsungIME: KeybaordView init() : load resources
,03-17 06:44:17.289  1857  1857 I SamsungIME: getCurrentKeyboard
03-17 06:44:17.289  1857  1857 I SamsungIME: getTextKeyboard
,03-17 06:44:17.319  1934  1934 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-17 06:44:17.319  1934  1934 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS,
03-17 06:44:17.319  1934  1934 I glCompressedTexImage2D: took 0.355989ms for 440*116864 texture 37809
03-17 06:44:17.319  1934  1934 I draw setup: took 0.715521ms for 440*330 texture 37809
03-17 06:44:17.319  1934  1934 E GFX GPU raster: drawn
,03-17 06:44:17.329  1934  1934 I GFX GPU raster ASTC: took 5.007083ms for 440*330 texture 12,
03-17 06:44:17.329  1934  1934 I GFX raster: took 5.199426ms for 440*330 texture 0
03-17 06:44:17.329  1934  1934 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8319a68 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8319e38 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 06:44:17.359  1857  1857 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 06:44:17.369  1934  1934 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 06:44:17.379  1934  1934 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 06:44:17.379  1934  1934 I glCompressedTexImage2D: took 0.467448ms for 480*163840 texture 37811
03-17 06:44:17.379  1934  1934 I draw setup: took 0.904791ms for 480*640 texture 37811
03-17 06:44:17.379  1934  1934 E GFX GPU raster: drawn
,03-17 06:44:17.379  3303  3390 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-17 06:44:17.379  1019  1480 I art     : Explicit concurrent mark sweep GC freed 23079(1217KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 22MB/33MB, paused 12.839ms total 262.771ms
,03-17 06:44:17.379  1019  1029 I art     : WaitForGcToComplete blocked for 15.299ms for cause HeapTrim
,03-17 06:44:17.379  1019  1480 E Tethering: No numeric data
,03-17 06:44:17.389  1934  1934 I GFX GPU raster ASTC: took 7.034948ms for 480*640 texture 12
03-17 06:44:17.389  1934  1934 I GFX raster: took 7.110209ms for 480*640 texture 0
03-17 06:44:17.389  1934  1934 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83198a8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb832c8d0 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 06:44:17.389  1019  1342 E Tethering: No numeric data
,03-17 06:44:17.399  3369  3382 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 06:44:17.399  1019  1216 E Tethering: No numeric data
,03-17 06:44:17.399  1019  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:17.399  1019  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:17.399  1019  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
03-17 06:44:17.399  1019  1544 E Tethering: No numeric data
03-17 06:44:17.419  1019  1480 E Tethering: No numeric data
03-17 06:44:17.419  3303  3414 I ContactAccountLoggerTas: canRun() : Opted Out
03-17 06:44:17.419  1019  1342 E Tethering: No numeric data
03-17 06:44:17.419  3089  3429 D jxcore_app_log: JniHelper::setJavaVM(0xb7d2d448), pthread_self() = -1203257144
03-17 06:44:17.429  1934  1934 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 06:44:17.429  1934  1934 I GFX construct_block_size_descriptor_2d second part: took 2.488177ms for 0*0 texture 0
03-17 06:44:17.429  3397  3397 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
03-17 06:44:17.439  3089  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 06:44:17.439  3089  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 06:44:17.439  3089  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 06:44:17.439  3089  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 06:44:17.439  3089  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 06:44:17.439  3089  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d7d7fa6 added. We now have 1 listener(s)
03-17 06:44:17.439  1934  1934 I GFX generate_partition_tables: took 7.530156ms for 0*0 texture 0
03-17 06:44:17.439  1934  1934 I GFX raster: took 11.989063ms for 176*144 texture 0
03-17 06:44:17.439  1934  1934 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83099b8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb832c8f0 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 06:44:17.439  3089  3429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,03-17 06:44:17.449  3089  3429 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,03-17 06:44:17.449  3089  3429 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-17 06:44:17.449  3089  3429 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 06:44:17.449  3089  3429 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 06:44:17.449  3397  3397 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 06:44:17.449  3089  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 06:44:17.449  3089  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 06:44:17.449  3089  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 06:44:17.449  3089  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-17 06:44:17.449  3089  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 06:44:17.449  3089  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 06:44:17.449  3089  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 06:44:17.449  3089  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 06:44:17.449  3089  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 06:44:17.449  3089  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 06:44:17.449  3089  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8b503d added. We now have 1 listener(s)
,03-17 06:44:17.449  3089  3429 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-17 06:44:17.459  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.459  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.459  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.459  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.459  1934  1934 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 06:44:17.459  1019  1487 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 06:44:17.459  1934  1934 I GFX construct_block_size_descriptor_2d second part: took 3.140417ms for 0*0 texture 0
,03-17 06:44:17.469  3089  3429 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 06:44:17.469  3089  3429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 06:44:17.469  3089  3429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 06:44:17.469  3089  3429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 06:44:17.469  3089  3429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 06:44:17.469  1934  1934 I GFX generate_partition_tables: took 7.129896ms for 0*0 texture 0
,03-17 06:44:17.469  1934  1934 I GFX raster: took 12.685262ms for 176*144 texture 0
03-17 06:44:17.469  1934  1934 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8319f18 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb832e5e0 counterpartCT=4 counterpartW=176 counterparth=144
03-17 06:44:17.469  3435  3435 E Zygote  : MountEmulatedStorage()
03-17 06:44:17.469  3435  3435 I libpersona: KNOX_SDCARD checking this for 10055
03-17 06:44:17.469  3435  3435 E Zygote  : v2
03-17 06:44:17.469  3435  3435 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:17.469  3435  3435 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:17.479  1313  3140 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 06:44:17.479  3435  3435 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:17.479  1934  1934 D ScoverManager: registerListener
,03-17 06:44:17.479  3435  3435 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:17.479  1313  3140 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
03-17 06:44:17.479  1019  1539 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 06:44:17.479  1019  1543 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH,
03-17 06:44:17.479  1019  1543 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@1da746c3, pid : 1934, uid : 1001, type : 1
03-17 06:44:17.479  1019  1216 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3435 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,03-17 06:44:17.489  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.489  3303  3390 I LibraryLoader: Loading: webviewchromium
,03-17 06:44:17.489  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.489  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.489  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.489  3303  3390 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 8260-8266)
03-17 06:44:17.489  3303  3390 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 06:44:17.509  3452  3452 E Zygote  : MountEmulatedStorage(),
03-17 06:44:17.509  3452  3452 E Zygote  : v2
03-17 06:44:17.509  3452  3452 I libpersona: KNOX_SDCARD checking this for 10090
03-17 06:44:17.509  3452  3452 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:17.509  3452  3452 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:17.509  1019  2721 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 06:44:17.519  3452  3452 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 06:44:17.519  1019  1216 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3452 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-17 06:44:17.519  3452  3452 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:17.519  3089  3429 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 06:44:17.519  1019  1542 I ActivityManager: Killing 2539:com.wsomacp/u0a23 (adj 15): empty #31
,03-17 06:44:17.519  1019  1031 E Tethering: No numeric data
,03-17 06:44:17.519  3435  3435 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:17.529  3435  3435 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:17.529  1934  1934 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 06:44:17.539  3089  3429 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,03-17 06:44:17.539  1019  1342 E Tethering: No numeric data
,03-17 06:44:17.549  1019  1543 E Tethering: No numeric data
,03-17 06:44:17.549  3452  3452 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:17.559  3452  3452 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:17.559  3089  3429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 06:44:17.559  3089  3429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 06:44:17.559  3089  3429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 06:44:17.559  3089  3429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 06:44:17.559  3089  3429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 06:44:17.559  3089  3429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 06:44:17.559  3089  3429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 06:44:17.559  3089  3429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 06:44:17.559  3089  3429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 06:44:17.559  3089  3429 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 06:44:17.569  3089  3089 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 06:44:17.569  3125  3125 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 06:44:17.569  3303  3390 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:44:17.579  3089  3089 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 06:44:17.589  3303  3460 I UpdateIcingCorporaServi: Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,03-17 06:44:17.599  1019  1544 E Tethering: No numeric data
,03-17 06:44:17.619  1019  1043 W libprocessgroup: failed to open /acct/uid_10023/pid_2539/cgroup.procs: No such file or directory
,03-17 06:44:17.639  1019  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:17.639  1019  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 06:44:17.639  1019  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 06:44:17.639  3397  3397 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 06:44:17.649  3089  3089 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 06:44:17.689  3435  3435 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 06:44:17.699  3452  3452 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 06:44:17.699  3452  3452 D elm:15121: ELMEngine.ELMEngine( context ).
,03-17 06:44:17.699  3452  3452 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-17 06:44:17.699  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:17.699  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:17.699  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 06:44:17.709  3452  3452 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 06:44:17.709  3452  3452 D elm:15121: ElmAgentService : onCreate()
,03-17 06:44:17.709  3452  3480 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) },
,03-17 06:44:17.709  3452  3452 D elm:15121: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-17 06:44:17.709  3452  3452 D elm:15121: BootCompletedState : startBootCompleted() call
,03-17 06:44:17.719  3452  3452 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 06:44:17.729  3452  3452 I elm:15121: Get License : 0
,03-17 06:44:17.729  3452  3452 D elm:15121: ElmAgentService : onDestroy().
,03-17 06:44:17.739  1019  1480 I ActivityManager: Killing 2355:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 06:44:17.739  1019  1080 V VibratorService: hasVibrator - useVibetonz: true
,03-17 06:44:17.739  3435  3435 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 06:44:17.739  3435  3435 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 06:44:17.739  3435  3435 D UserAnalysis: Create SecureDbHelper
,03-17 06:44:17.749  1418  1418 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 06:44:17.759  3397  3397 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 06:44:17.759  3089  3104 I art     : Background sticky concurrent mark sweep GC freed 28564(1802KB) AllocSpace objects, 6(96KB) LOS objects, 7% free, 7MB/7MB, paused 28.850ms total 98.620ms
,03-17 06:44:17.759  3397  3397 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 06:44:17.769  1313  3140 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 06:44:17.769  3397  3397 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-17 06:44:17.769  3397  3397 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 06:44:17.769  3397  3397 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-17 06:44:17.769  1834  1834 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:17.769  1834  1834 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:17.779  1019  1032 V VibratorService: hasVibrator - useVibetonz: true
,03-17 06:44:17.779  1019  1480 V VibratorService: hasVibrator - useVibetonz: true
,03-17 06:44:17.789  1019  1342 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:17.789  1019  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:17.789  1019  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 06:44:17.789  1019  1517 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 06:44:17.799  1019  1539 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 06:44:17.799  3435  3435 D IntelligenceServiceApplication: onCreate()
,03-17 06:44:17.809  1019  1517 I AudioService: getStreamVolume 3 index 0
,03-17 06:44:17.809  1313  3140 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 06:44:17.839  3397  3397 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 06:44:17.839  1418  1418 V EmergencyMode: [EmergencyBase] setBootTime
03-17 06:44:17.839  1418  1418 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 06:44:17.839  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.839  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.849  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.849  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.859  3493  3493 E Zygote  : MountEmulatedStorage()
03-17 06:44:17.859  3493  3493 E Zygote  : v2
03-17 06:44:17.859  3493  3493 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:17.859  3493  3493 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:17.859  3493  3493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:17.859  1019  1544 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3493 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 06:44:17.859  3493  3493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:17.859  3493  3493 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:17.859  3435  3435 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 06:44:17.869  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.869  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.869  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:17.869  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:17.889  3503  3503 E Zygote  : MountEmulatedStorage(),
03-17 06:44:17.889  3503  3503 E Zygote  : v2
03-17 06:44:17.889  3503  3503 I libpersona: KNOX_SDCARD checking this for 10056,
03-17 06:44:17.889  3503  3503 I libpersona: KNOX_SDCARD not a persona,
,03-17 06:44:17.889  3503  3503 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 06:44:17.889  1019  1544 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3503 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
,03-17 06:44:17.889  1019  1544 I ActivityManager: Killing 1795:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-17 06:44:17.889  3223  3433 I System.out: Thread-424(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 06:44:17.899  1019  1487 W ActivityManager: userId = 0, bbcId = -10000,
03-17 06:44:17.899  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:17.899  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:17.899  3503  3503 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:17.899  3145  3240 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 06:44:17.899  3503  3503 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:17.919   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 06:44:17.919   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:17.919  3493  3493 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:17.919  3493  3493 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:17.929  1019  1080 I ActivityManager: Killing 2592:com.android.calendar/u0a131 (adj 15): empty #31
,03-17 06:44:17.939  3125  3125 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 06:44:17.949  1313  3140 D ScoverManager: serviceVersion : 16908288
03-17 06:44:17.949   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 06:44:17.949   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:17.949  3503  3503 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:17.949  3125  3125 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 06:44:17.949  3503  3503 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:17.949  3223  3433 I System.out: Thread-424(ApacheHTTPLog):isSBSettingEnabled false
,03-17 06:44:17.949  3223  3433 I System.out: Thread-424(ApacheHTTPLog):isShipBuild true
03-17 06:44:17.949  3223  3433 I System.out: Thread-424(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 06:44:17.949  3223  3433 I System.out: Thread-424(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 06:44:17.959   258   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 06:44:17.959   258   513 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 06:44:17.959  3125  3125 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 06:44:17.959  1019  1543 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:17.959  1019  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:17.959  1019  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:17.959   343   343 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 06:44:17.969  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2355/cgroup.procs: No such file or directory
,03-17 06:44:17.979   281  1007 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 06:44:17.979   281  1007 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-17 06:44:17.979  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:17.979  1019  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:17.979  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-17 06:44:17.989  3249  3249 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 06:44:17.989  3249  3249 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 06:44:17.999  3249  3249 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 06:44:18.009  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.009  1019  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:18.009  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 06:44:18.049  3249  3249 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 06:44:18.049  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.049  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.049  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.049  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.059  3540  3540 E Zygote  : MountEmulatedStorage(),
03-17 06:44:18.059  3540  3540 E Zygote  : v2
03-17 06:44:18.059  3540  3540 I libpersona: KNOX_SDCARD checking this for 10013,
03-17 06:44:18.059  3540  3540 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:18.069  1019  1342 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3540 uid=10013 gids={50013, 9997} abi=armeabi-v7a
03-17 06:44:18.069  3540  3540 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:18.069  1019  1342 I ActivityManager: Killing 2639:com.android.keychain/1000 (adj 15): empty #31
,03-17 06:44:18.069  3540  3540 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 06:44:18.069  3540  3540 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:18.089  3493  3493 I CameraApp: CameraApp.onCreate()... mFeature : null
03-17 06:44:18.089  3493  3493 I testFeature: Feature.Feature(context)
,03-17 06:44:18.099  3493  3493 I testFeature: Feature.readInternalDefaultXml()
03-17 06:44:18.099  3493  3493 I testFeature: ResetFeatureValue
,03-17 06:44:18.099  3540  3540 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.099  3540  3540 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.109  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_1795/cgroup.procs: No such file or directory
,03-17 06:44:18.109  1019  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.109  1019  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:18.109  1019  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:18.109  3435  3435 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 06:44:18.129  3493  3493 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 06:44:18.129  3493  3493 I CameraApp: CameraApp.getAppFeature()...
,03-17 06:44:18.139  1019  1543 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 06:44:18.139  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.139  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.139  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.139  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.149  2576  3107 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3107)  
,03-17 06:44:18.149  3540  3540 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 06:44:18.149  3562  3562 E Zygote  : MountEmulatedStorage()
03-17 06:44:18.149  3562  3562 I libpersona: KNOX_SDCARD checking this for 10095
03-17 06:44:18.149  3562  3562 E Zygote  : v2
03-17 06:44:18.149  3562  3562 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:18.149  3562  3562 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:18.159  3562  3562 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:18.159  3562  3562 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:18.159  1019  1032 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3562 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,03-17 06:44:18.159  1019  1032 I ActivityManager: Killing 2674:com.android.chrome/u0a77 (adj 15): empty #31
,03-17 06:44:18.179  1019  1080 I ActivityManager: Killing 2481:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,03-17 06:44:18.189  3562  3562 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.189  3435  3435 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 06:44:18.189  3562  3562 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.209  1019  1080 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:18.209  1019  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:18.209  1019  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 06:44:18.219  3435  3435 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 06:44:18.219  3435  3435 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 06:44:18.229   281  1007 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 06:44:18.229   281  1007 D Netd    : getNetworkForDns: using netid 502 for uid 10052
,03-17 06:44:18.229  1019  1043 W libprocessgroup: failed to open /acct/uid_10131/pid_2592/cgroup.procs: No such file or directory
,03-17 06:44:18.229  3503  3503 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.7.KK_APP
,03-17 06:44:18.249  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.249  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.249  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.249  1019  1342 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.259  3540  3585 V OneTimeService: OneTimeService.onHandleIntent
,03-17 06:44:18.269  3590  3590 E Zygote  : MountEmulatedStorage()
,03-17 06:44:18.269  3590  3590 E Zygote  : v2
03-17 06:44:18.269  1019  1342 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3590 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:18.269  3590  3590 I libpersona: KNOX_SDCARD checking this for 10058
03-17 06:44:18.269  3590  3590 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:18.269  3590  3590 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:18.269  3590  3590 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:18.279  3590  3590 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:18.289  1019  1517 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.289  1019  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:18.289  1019  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:18.289  3303  3390 I qtaguid : Tagging socket 42 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
,03-17 06:44:18.319  3590  3590 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.319  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 06:44:18.319  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:18.319  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:18.319  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:18.319  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:18.319  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:18.319  1019  2794 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:44:18.319  3590  3590 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.319  1019  1543 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:18.319  1019  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:18.319  1019  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:18.329  1019  1539 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.329  1019  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 06:44:18.329  1019  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:18.339  1019  1342 I ActivityManager: Killing 2723:com.android.email/u0a141 (adj 15): empty #31
,03-17 06:44:18.349  1019  1539 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:18.349  1019  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:18.349  1019  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:18.349  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:18.349  1019  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:18.349  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:18.359  1019  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:18.359  1019  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:18.359  1019  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:18.369  1019  1031 I ActivityManager: Killing 1572:com.android.defcontainer/u0a3 (adj 15): empty #31
,03-17 06:44:18.379  3562  3562 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,03-17 06:44:18.389  2126  3526 I Icing   : Storage manager: low false usage 2.11MB avail 9.95GB capacity 11.63GB
,03-17 06:44:18.429  3562  3562 E SQLiteLog: (284) automatic index on titles(filter_id)
,03-17 06:44:18.439  1019  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:18.439  1019  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:18.439  1019  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:18.449  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.449  1019  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 06:44:18.459  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 06:44:18.459  3562  3562 I FilterProviderReceiver: onReceive in FilterProviderReceiver
03-17 06:44:18.459  3562  3562 I FilterProviderReceiver: onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,03-17 06:44:18.459  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.459  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.459  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.459  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.469  3590  3590 I ExternalOEMControlProvider: onCreate
,03-17 06:44:18.469  3125  3588 W MessageQueue: Handler (android.os.Handler) {b169ab5} sending message to a Handler on a dead thread
03-17 06:44:18.469  3125  3588 W MessageQueue: java.lang.IllegalStateException: Handler (android.os.Handler) {b169ab5} sending message to a Handler on a dead thread
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at ffw.a(SourceFile:327)
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at guw.a(SourceFile:120)
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at guf.c(SourceFile:26)
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at gui.run(SourceFile:297)
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:18.469  3125  3588 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 06:44:18.479  1313  3140 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 06:44:18.489  3089  3469 W jxcore-log: Initializing JXcore engine
03-17 06:44:18.489  3089  3469 W jxcore-log: JXcore engine is ready
,03-17 06:44:18.489  3616  3616 E Zygote  : MountEmulatedStorage(),
,03-17 06:44:18.489  3616  3616 E Zygote  : v2
03-17 06:44:18.489  3616  3616 I libpersona: KNOX_SDCARD checking this for 10098
03-17 06:44:18.489  3616  3616 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:18.489  3616  3616 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 06:44:18.499  3616  3616 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:18.499  3616  3616 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:18.499  1019  1480 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3616 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 06:44:18.509  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.509  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:18.509  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:18.519  3125  3607 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
03-17 06:44:18.519  3125  3607 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 06:44:18.519  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.519  1019  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 06:44:18.519  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 06:44:18.519  3125  3607 I System.out: Thread-451(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 06:44:18.529  3616  3616 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.529  3616  3616 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.529  1834  1834 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:18.529  1834  1834 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 06:44:18.529  3125  3607 I System.out: Thread-451(ApacheHTTPLog):isSBSettingEnabled false
03-17 06:44:18.529  3125  3607 I System.out: Thread-451(ApacheHTTPLog):isShipBuild true
03-17 06:44:18.529  3125  3607 I System.out: Thread-451(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 06:44:18.529  3125  3607 I System.out: Thread-451(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 06:44:18.539   281  1007 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 06:44:18.539   281  1007 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,03-17 06:44:18.539  1313  3140 D Settings_Utils: isSupportVNFestival SM-A300FU XEO
,03-17 06:44:18.559  1889  1889 E audit   : type=1400 msg=audit(1458193458.559:205): avc:  denied  { ioctl } for  pid=3469 comm="Thread-407" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 06:44:18.559  1889  1889 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:18.559  1889  1889 E audit   : type=1300 msg=audit(1458193458.559:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9367b8f8 items=0 ppid=327 ppcomm=main pid=3469 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-407" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 06:44:18.559  1889  1889 E audit   : type=1320 msg=audit(1458193458.559:205): 
,03-17 06:44:18.569  1313  3140 W ResourceType: Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,03-17 06:44:18.579  3089  3469 W jxcore-log: Starting JXcore engine
,03-17 06:44:18.589  1019  1216 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.589  1019  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:18.589  1019  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 06:44:18.589  1728  1728 I Hs20UtilService: Starting #4
,03-17 06:44:18.599  1019  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.599  1019  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.599  1019  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.599  1019  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.609  1313  3140 W ResourceType: Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,03-17 06:44:18.619  3635  3635 E Zygote  : MountEmulatedStorage()
03-17 06:44:18.619  3635  3635 I libpersona: KNOX_SDCARD checking this for 10018
03-17 06:44:18.619  3635  3635 E Zygote  : v2
03-17 06:44:18.619  3635  3635 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:18.629  1728  1788 I Hs20UtilService: Message received 5003
,03-17 06:44:18.629  3635  3635 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 06:44:18.629  3635  3635 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 06:44:18.629  3635  3635 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:18.639  1019  1542 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3635 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,03-17 06:44:18.649  1905  1905 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:18.649  3616  3616 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 06:44:18.649  1019  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.649  1019  1080 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:18.649  1019  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-17 06:44:18.659  3616  3616 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-17 06:44:18.659  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2639/cgroup.procs: No such file or directory
03-17 06:44:18.659  1019  1043 W libprocessgroup: failed to open /acct/uid_10077/pid_2674/cgroup.procs: No such file or directory
03-17 06:44:18.659  1019  1043 W libprocessgroup: failed to open /acct/uid_10039/pid_2481/cgroup.procs: No such file or directory
,03-17 06:44:18.659  1019  1043 W libprocessgroup: failed to open /acct/uid_10003/pid_1572/cgroup.procs: No such file or directory
03-17 06:44:18.659  1019  1043 W libprocessgroup: failed to open /acct/uid_10141/pid_2723/cgroup.procs: No such file or directory
,03-17 06:44:18.659  1905  1905 D SecUISvc: Service started flags 0 startId 1
,03-17 06:44:18.659  1905  3645 D SecUISvc: Thread created.
,03-17 06:44:18.669  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 06:44:18.669  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.669  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.669  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.669  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
,03-17 06:44:18.669  3303  3390 I qtaguid : Untagging socket 46
,03-17 06:44:18.669  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
,03-17 06:44:18.669  3303  3390 I qtaguid : Untagging socket 46
,03-17 06:44:18.669  3635  3635 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:18.669  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
,03-17 06:44:18.679  3303  3390 I qtaguid : Untagging socket 46
,03-17 06:44:18.679  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
03-17 06:44:18.679  3303  3390 I qtaguid : Untagging socket 46
,03-17 06:44:18.679  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
,03-17 06:44:18.679  3303  3390 I qtaguid : Untagging socket 46
,03-17 06:44:18.679  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
03-17 06:44:18.679  3303  3390 I qtaguid : Untagging socket 46
03-17 06:44:18.679  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
03-17 06:44:18.679  3303  3390 I qtaguid : Untagging socket 46
,03-17 06:44:18.679  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
,03-17 06:44:18.679  3303  3390 I qtaguid : Untagging socket 46
03-17 06:44:18.679  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
03-17 06:44:18.679  3303  3390 I qtaguid : Untagging socket 46
03-17 06:44:18.679  3635  3635 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.679  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
,03-17 06:44:18.679  3303  3390 I qtaguid : Untagging socket 46
,03-17 06:44:18.679  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
03-17 06:44:18.679  3303  3390 I qtaguid : Untagging socket 46
03-17 06:44:18.679  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
,03-17 06:44:18.689  3303  3390 I qtaguid : Untagging socket 46
03-17 06:44:18.689  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
03-17 06:44:18.689  3303  3390 I qtaguid : Untagging socket 46
,03-17 06:44:18.689  3653  3653 E Zygote  : MountEmulatedStorage(),
03-17 06:44:18.689  3653  3653 I libpersona: KNOX_SDCARD checking this for 10099
03-17 06:44:18.689  3653  3653 E Zygote  : v2
03-17 06:44:18.689  3653  3653 I libpersona: KNOX_SDCARD not a persona,
,03-17 06:44:18.689  3653  3653 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 06:44:18.689  3653  3653 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:18.699  3653  3653 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:18.709  1019  1506 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3653 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:18.709  1019  1506 I ActivityManager: Killing 2815:com.mobeam.barcodeService/1000 (adj 15): empty #31
,03-17 06:44:18.719  3089  3469 W jxcore-log: Platform android
03-17 06:44:18.719  3089  3469 W jxcore-log: 
03-17 06:44:18.719  3089  3469 W jxcore-log: Process ARCH arm
03-17 06:44:18.719  3089  3469 W jxcore-log: 
,03-17 06:44:18.729  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 06:44:18.729  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.729  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.729  1019  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-17 06:44:18.739   327   327 I art     : Explicit concurrent mark sweep GC freed 8684(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 35.954ms
,03-17 06:44:18.759   327   327 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 19.528ms
,03-17 06:44:18.769  3653  3653 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.769  3653  3653 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.779   327   327 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 16.674ms
,03-17 06:44:18.789  3670  3670 E Zygote  : MountEmulatedStorage()
03-17 06:44:18.789  3670  3670 E Zygote  : v2
03-17 06:44:18.789  3670  3670 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:18.789  3670  3670 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:18.789  3670  3670 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 06:44:18.799  3670  3670 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:18.799  1019  1506 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3670 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 06:44:18.799  3670  3670 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:18.799  1019  1506 I ActivityManager: Killing 2836:flipboard.boxer.app/u0a97 (adj 15): empty #31
,03-17 06:44:18.799  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:18.799  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:18.799  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:18.849  1019  1031 D SettingsProvider: name = PREVIOUS_SYS_TIME
,03-17 06:44:18.849  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 06:44:18.849  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 06:44:18.849  3670  3670 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:18.849  1019  1031 D SettingsProvider: selectionArgs: false
03-17 06:44:18.849  1019  1031 D SettingsProvider: selectionArgs: 10058
,03-17 06:44:18.849  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-17 06:44:18.859  1019  1031 D SettingsProvider: ret = -1
,03-17 06:44:18.859  3670  3670 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:18.859  1019  1517 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.859  1019  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 06:44:18.859  1019  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:18.869  3303  3390 I qtaguid : Tagging socket 46 with tag 100000000{1,0} for uid -1, pid: 3303, getuid(): 10052
,03-17 06:44:18.879  1019  1031 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-17 06:44:18.879  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:18.889  1019  1080 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
,03-17 06:44:18.889  1019  1080 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:18.889  1019  1080 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:18.889  1019  1080 D SettingsProvider: selectionArgs: false
03-17 06:44:18.889  1019  1080 D SettingsProvider: selectionArgs: 10058
03-17 06:44:18.889  1019  1080 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:18.889  1019  1080 D SettingsProvider: ret = -1
,03-17 06:44:18.889  1019  1342 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:18.899  1019  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:18.899  1019  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:18.909  1019  1080 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-17 06:44:18.919  3145  3240 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 06:44:18.919  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:18.929  3352  3352 I RlzPingService: Setting next ping for 1458798258940
,03-17 06:44:18.939  3635  3635 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 06:44:18 GMT+01:00 2016
,03-17 06:44:18.939  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:18.939  1019  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:18.939  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 06:44:18.939  3303  3390 W GAV2    : Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 06:44:18.939  3635  3635 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-17 06:44:18.939  3303  3390 W GAV2    : Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
03-17 06:44:18.939  3303  3414 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 06:44:18.939  3303  3414 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 06:44:18.949  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.949  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.949  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:18.949  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:18.949  3635  3635 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-17 06:44:18.949  3635  3635 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 06:44:18.959  3635  3635 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 06:44:18.959  3693  3693 E Zygote  : MountEmulatedStorage()
03-17 06:44:18.959  3693  3693 I libpersona: KNOX_SDCARD checking this for 10020
03-17 06:44:18.959  3693  3693 E Zygote  : v2
03-17 06:44:18.959  3693  3693 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:18.959  3693  3693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:18.969  3693  3693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:18.969  1019  1216 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3693 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,03-17 06:44:18.969  3693  3693 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:18.969  3635  3692 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 06:44:18.979  3089  3469 I jxcore-log: JXcore Cordova bridge is ready!
03-17 06:44:18.979  3089  3469 I jxcore-log: 
,03-17 06:44:18.979  3089  3469 W jxcore-log: JXcore engine is started
,03-17 06:44:18.989  3089  3429 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 06:44:18.989  3670  3670 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 06:44:18.999  3089  3089 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-17 06:44:18.999  2126  3684 D FileApkUtils: Optimizing (staging complete)
,03-17 06:44:18.999  2126  3684 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
,03-17 06:44:18.999  2126  3684 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-17 06:44:19.009  3635  3692 I KLMS-2.5.123: : KLMSIntentService(): BOOT_COMPLETED
,03-17 06:44:19.009  3089  3469 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 06:44:19.009  3089  3469 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 06:44:19.019  3693  3693 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:19.019  3693  3693 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:19.019  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2815/cgroup.procs: No such file or directory
03-17 06:44:19.019  1019  1043 W libprocessgroup: failed to open /acct/uid_10097/pid_2836/cgroup.procs: No such file or directory
,03-17 06:44:19.029  3089  3089 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 06:44:19.029  3089  3089 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-17 06:44:19.029  1019  1080 D FocusedStackFrame: Set to : 0
03-17 06:44:19.029  1019  1080 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 06:44:19.029  1019  1080 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 06:44:19.029  1019  1080 D InputDispatcher: Focused application set to: xxxx
03-17 06:44:19.029  1019  1080 D InputDispatcher: Focus left window: 3089
03-17 06:44:19.039  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 06:44:19.039  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 06:44:19.039  2126  3684 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
03-17 06:44:19.039   259   441 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (473 us)
,03-17 06:44:19.059  1019  1342 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-17 06:44:19.069  3089  3429 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 37ms. Plugin should use CordovaInterface.getThreadPool().
03-17 06:44:19.069  1019  1342 W ActivityManager: mDVFSHelper.acquire()
,03-17 06:44:19.069  1019  1342 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 06:44:19.069  1019  1342 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 06:44:19.069  1019  1342 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 06:44:19.079  1481  1481 D Launcher: onRestart, Launcher: 630982792
,03-17 06:44:19.089  3670  3670 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-17 06:44:19.089  3670  3670 I ServiceMode: setReferenceIsDumpState : 0
,03-17 06:44:19.089  1481  1481 D Launcher: onStart, Launcher: 630982792
03-17 06:44:19.089  1481  1481 D Launcher.HomeView: onStart
,03-17 06:44:19.089  1481  1481 D Launcher: onResume, Launcher: 630982792
03-17 06:44:19.089  1019  1539 D SettingsProvider: name = kids_home_mode
03-17 06:44:19.089  1019  1539 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:19.089  1019  1539 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:19.089  1019  1539 D SettingsProvider: selectionArgs: false
03-17 06:44:19.089  1019  1539 D SettingsProvider: selectionArgs: 10006
03-17 06:44:19.089  1019  1539 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:19.089  1019  1539 D SettingsProvider: ret = -1
,03-17 06:44:19.089  1481  1481 D Launcher.HomeView: onResume
,03-17 06:44:19.089  3125  3607 I System.out: Thread-451 calls detatch()
,03-17 06:44:19.099  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.099  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.099  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.099  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.099  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 06:44:19.109  1019  1539 V VibratorService: hasVibrator - useVibetonz: true
,03-17 06:44:19.119  3717  3717 E Zygote  : MountEmulatedStorage()
,03-17 06:44:19.119  3717  3717 E Zygote  : v2
03-17 06:44:19.119  3717  3717 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:19.119  3717  3717 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:19.129  3717  3717 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 06:44:19.129  3717  3717 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:19.129  3717  3717 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:19.129  1019  1544 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3717 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 06:44:19.129  1019  1544 I ActivityManager: Killing 2864:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 06:44:19.139  1019  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:19.139  1019  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:19.139  1019  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:19.159  3635  3635 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-17 06:44:19.169  1019  1019 D SensorService: [SO] activate (ident=0xb83903b8, enabled=0)
03-17 06:44:19.169  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-17 06:44:19.169  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 06:44:19.179  3223  3433 I System.out: pool-10-thread-1 calls detatch()
,03-17 06:44:19.179  1481  1481 D MenuAppsGridFragment: onResume
,03-17 06:44:19.189  1019  1019 D SensorManager: unregisterListener ::   
,03-17 06:44:19.189  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-17 06:44:19.189  1019  1542 D ActivityManager: handle home activity for 0
03-17 06:44:19.189  1019  1542 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 06:44:19.189  1019  1542 D KnoxTimeoutHandler: post home show event for user 0
03-17 06:44:19.189  1019  1542 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 06:44:19.189  1019  1542 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 06:44:19.189  1019  1542 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 06:44:19.189  1019  1019 D SensorService: [SO] changed settle time [0]
03-17 06:44:19.189  1019  1019 D SensorService: [SO] setDelay [200000000]
03-17 06:44:19.189  1019  1019 D SensorService: [SO] activate (ident=0xb83903b8, enabled=1)
03-17 06:44:19.189  1019  1019 D SensorService: [SO] AR_init
03-17 06:44:19.189  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 06:44:19.199   259   259 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=4, Mauncher,
03-17 06:44:19.199  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
03-17 06:44:19.199  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 06:44:19.199  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 06:44:19.199  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 06:44:19.199  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 06:44:19.199  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.199  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.199  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.199  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.199  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 06:44:19.199  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 06:44:19.209  3717  3717 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 06:44:19.209  3717  3717 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:19.209  1019  1342 D InputDispatcher: Focus entered window: 1481
03-17 06:44:19.209  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 06:44:19.209  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 06:44:19.219  3733  3733 E Zygote  : MountEmulatedStorage()
03-17 06:44:19.219  3733  3733 E Zygote  : v2
03-17 06:44:19.219  3733  3733 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:19.219  3733  3733 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:19.219  3733  3733 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:19.219  1019  1031 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3733 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 06:44:19.219  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 06:44:19.219  3733  3733 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:19.229  3733  3733 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:19.229  1019  1031 I ActivityManager: Killing 2258:flipboard.app/u0a96 (adj 15): empty #31
,03-17 06:44:19.239  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 06:44:19.239  1019  1543 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 06:44:19.249  3089  3089 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 06:44:19.249  1019  3740 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:44:19.259  1857  1857 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 06:44:19.269  1019  1216 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:19.269  1019  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:19.269  1019  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:19.289  1174  1174 I StatusBar: Icon Only
03-17 06:44:19.289  1174  1174 D PanelView: There is/are notification(s) 
,03-17 06:44:19.299  3303  3390 I ContactLabelSupplier: get() : OptedIn = false
,03-17 06:44:19.299  1481  1481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c16949d time:40075
,03-17 06:44:19.309  3733  3733 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:19.309  1019  1539 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:19.309  1019  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:19.309  1019  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
03-17 06:44:19.319  3733  3733 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:19.319  1019  1050 D PersonaManager: isKioskContainerExistOnDevice
,03-17 06:44:19.339  3715  3715 D AndroidRuntime: 
03-17 06:44:19.339  3715  3715 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 06:44:19.339  1019  1050 I ActivityManager: Displayed Component not be shown by security: +276ms
,03-17 06:44:19.349   296   296 E SMD     : DCD OFF
,03-17 06:44:19.349  3715  3715 D AndroidRuntime: CheckJNI is OFF
,03-17 06:44:19.349  3715  3715 D AndroidRuntime: readGMSProperty: start
03-17 06:44:19.349  3715  3715 D AndroidRuntime: readGMSProperty: already setted!!
03-17 06:44:19.349  3715  3715 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 06:44:19.349  3715  3715 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 06:44:19.349  3715  3715 D AndroidRuntime: readGMSProperty: end
03-17 06:44:19.349  3715  3715 D AndroidRuntime: addProductProperty: start
,03-17 06:44:19.349  2617  2706 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 06:44:19.379  1019  1517 I ActivityManager: Killing 2914:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,03-17 06:44:19.379  1019  1043 W libprocessgroup: failed to open /acct/uid_1101/pid_2864/cgroup.procs: No such file or directory
,03-17 06:44:19.399  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 06:44:19.439  1019  1043 W libprocessgroup: failed to open /acct/uid_10096/pid_2258/cgroup.procs: No such file or directory
03-17 06:44:19.439  1019  1043 W libprocessgroup: failed to open /acct/uid_10153/pid_2914/cgroup.procs: No such file or directory
,03-17 06:44:19.479  1313  3140 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 06:44:19.489  3715  3715 E AffinityControl: AffinityControl: registerfunction enter
,03-17 06:44:19.509  3733  3733 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
03-17 06:44:19.509  3733  3733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:19.509  1019  1342 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:19.509  1019  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:19.509  1019  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: Timeout on service connection
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: java.lang.Throwable
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.http.e.a(:com.google.android.gms:97)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.http.g.a(:com.google.android.gms:146)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:757)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:665)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.auth.j.a.a(:com.google.android.gms:77)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.auth.j.a.a(:com.google.android.gms:114)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:115)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.gms.auth.o.a(:com.google.android.gms:118)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at com.google.android.b.b.onTransact(:com.google.android.gms:63)
03-17 06:44:19.519  1834  2143 W GoogleHttpServiceClient: 	at android.os.Binder.execTransact(Binder.java:461)
03-17 06:44:19.519  3715  3715 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-17 06:44:19.519  3733  3733 D NPS_WSSNPS: [] Service onCreate!!
,03-17 06:44:19.529  3717  3717 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
03-17 06:44:19.529  1019  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.529  1019  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.529  1019  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.529  1019  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.539  3765  3765 E Zygote  : MountEmulatedStorage(),
03-17 06:44:19.539  3765  3765 E Zygote  : v2
,03-17 06:44:19.539  3765  3765 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:19.539  3765  3765 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:19.539  1019  1342 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-17 06:44:19.539  1019  1342 D PackageManager: START PACKAGE DELETE: observer{615362702}
03-17 06:44:19.539  1019  1342 D PackageManager: pkg{<packageName>}
03-17 06:44:19.539  1019  1342 D PackageManager: user{0}
03-17 06:44:19.539  1019  1342 D PackageManager: caller{2000}
03-17 06:44:19.539  1019  1342 D PackageManager: flags{2}
03-17 06:44:19.539  1019  1342 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-17 06:44:19.539  1019  1342 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-17 06:44:19.539  1019  1342 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 06:44:19.539  1019  1342 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-17 06:44:19.539  3765  3765 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 06:44:19.549  1019  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER,
03-17 06:44:19.549  1019  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-17 06:44:19.549  1019  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,03-17 06:44:19.549  1019  1080 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3765 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 06:44:19.549  3765  3765 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:19.549  3765  3765 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:19.549  1019  1216 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 06:44:19.549  1019  1216 D SecContentProvider2: mCursor = null
,03-17 06:44:19.559  1834  1834 D ChimeraCfgMgr: Reading stored module config
,03-17 06:44:19.559  3733  3774 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-17 06:44:19.559  1019  1542 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 06:44:19.559  1019  1542 D SecContentProvider2: mCursor = null
,03-17 06:44:19.559  3717  3717 V MTPRx   : sealedState: false
03-17 06:44:19.559  1019  1044 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
03-17 06:44:19.559  3717  3717 V MTPRx   : sealedUsbMassStorageState: false
,03-17 06:44:19.569  1019  1044 W ActivityManager: mDVFSHelper.release()
03-17 06:44:19.569  1019  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
03-17 06:44:19.569  1019  1080 D SettingsProvider: name = mtp_usb_connection_status
,03-17 06:44:19.569  3765  3765 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:19.579  3765  3765 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:19.589  1834  2143 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,03-17 06:44:19.589  1834  2143 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 06:44:19.589  1834  2143 I System.out: (HTTPLog)-Static: isShipBuild true
03-17 06:44:19.589  1834  2143 I System.out: (HTTPLog)-Thread-173-1063267774: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 06:44:19.589  1834  2143 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 06:44:19.589  1019  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
03-17 06:44:19.589   281  1007 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 06:44:19.589   281  1007 D Netd    : getNetworkForDns: using netid 502 for uid 10011
03-17 06:44:19.589  1019  1539 D SettingsProvider: name = media_player_mode
,03-17 06:44:19.599  1019  1041 D SensorService: [SO] currT = 40371331000, prevT = 39911090000, diff = 460241000, [-0.460 0.192 9.883]
03-17 06:44:19.599  1019  1041 D SensorService: [SO] -0.460 0.192 9.883
03-17 06:44:19.599  1019  1041 D SensorService: [SO] [100 -> 255]
03-17 06:44:19.599  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 06:44:19.599  1019  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-17 06:44:19.599  1019  1031 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 06:44:19.609  1019  1058 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
03-17 06:44:19.609  3733  3733 D NPS_WSSNPS: [50.150321] smlDBHelper
03-17 06:44:19.609  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:19.629  1019  1480 D SettingsProvider: name = mtp_running_status
,03-17 06:44:19.639  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:19.639  3733  3733 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-17 06:44:19.639  1834  1834 D WearableService: callingUid 10011, callindPid: 1834
,03-17 06:44:19.649  1019  1539 D SettingsProvider: name = media_mount_count
,03-17 06:44:19.649  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:19.649  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
03-17 06:44:19.649  1019  1044 I ActivityManager: Killing 3089:com.test.thalitest/u0a167 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-17 06:44:19.669  1834  2143 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 06:44:19.669  1834  2143 I qtaguid : Tagging socket 54 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1834, getuid(): 10011
,03-17 06:44:19.679  1019  1517 D SettingsProvider: name = mtp_sync_alive
,03-17 06:44:19.689  3733  3785 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-17 06:44:19.689  3733  3785 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
,03-17 06:44:19.689  3733  3785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-17 06:44:19.699  1019  1487 D SettingsProvider: name = sdcard_launch
,03-17 06:44:19.709  1019  1032 D SettingsProvider: name = boot_time_connected
,03-17 06:44:19.719  1019  1487 I WindowState: WIN DEATH: Window{1a795f03 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-17 06:44:19.739  1019  1544 D SettingsProvider: name = mtp_open_session
,03-17 06:44:19.749   259   441 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-17 06:44:19.749   259   773 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 06:44:19.749  1834  2143 I qtaguid : Tagging socket 67 with tag 3000040100000000{805307393,0} for uid 10011, pid: 1834, getuid(): 10011
,03-17 06:44:19.749   259  1161 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 06:44:19.779  1019  1058 W PackageSettings: Skipping PackageSetting{2a4228ae com.example.hello/10168} due to missing metadata
,03-17 06:44:19.819  1834  1834 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
03-17 06:44:19.819  1019  1342 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:19.819  1019  1342 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:19.819  1019  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 06:44:19.819  1019  1517 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-17 06:44:19.819  3733  3733 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-17 06:44:19.829  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{664215a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:40601
,03-17 06:44:19.829  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:19.829  3209  3257 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 06:44:19.829  3733  3733 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-17 06:44:19.829  3733  3733 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-17 06:44:19.829  3733  3733 I NPS_WSSNPS: [50.150321] smlBREmailDelete
,03-17 06:44:19.839  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:19.839  3733  3733 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
,03-17 06:44:19.839  3733  3733 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
03-17 06:44:19.839  3733  3733 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
03-17 06:44:19.839  3733  3733 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
,03-17 06:44:19.839  2126  2126 W InstanceID/Rpc: Found 10011
03-17 06:44:19.839  3733  3733 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
,03-17 06:44:19.839  3733  3733 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-17 06:44:19.849  1019  1058 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-17 06:44:19.849  3369  3369 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 06:44:19.849  3369  3369 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 06:44:19.849  3369  3369 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 06:44:19.849  3369  3369 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-17 06:44:19.849  3369  3369 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 06:44:19.849  3369  3369 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 06:44:19.859  3653  3788 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-17 06:44:19.869  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:19.869  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 06:44:19.879  1174  1174 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:19.879  3369  3369 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 06:44:19.889  1019  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-17 06:44:19.899  1019  1506 D SettingsProvider: name = access_control_enabled
,03-17 06:44:19.909  3209  3257 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 06:44:19.919  3209  3257 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 06:44:19.919  3209  3257 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 06:44:19.919  3145  3240 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 06:44:19.919  3209  3257 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 06:44:19.919  3209  3257 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 06:44:19.929  3209  3257 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 06:44:19.929  3369  3369 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 06:44:19.929  3209  3257 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
03-17 06:44:19.929  1019  1102 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 06:44:19.939  1834  2166 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 06:44:19.939  1857  1857 E SamsungIME: mOCRHelper is null
,03-17 06:44:19.949  1019  1517 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 06:44:19.949  1459  1459 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 06:44:19.949  3369  3369 I ReactiveServiceManager: Supported : 1
,03-17 06:44:19.949  3733  3733 D NPS_WSSNPS: [50.150321] dsServerSocket close
,03-17 06:44:19.949  1019  1480 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-17 06:44:19.949  1019  1480 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 06:44:19.959  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.959  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.959  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.959  1019  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:19.969  1019  1019 D RCPManagerService: PackageReceiver onReceive(),
,03-17 06:44:19.969  3795  3795 E Zygote  : MountEmulatedStorage()
03-17 06:44:19.969  3795  3795 E Zygote  : v2
,03-17 06:44:19.969  3795  3795 I libpersona: KNOX_SDCARD checking this for 10065
03-17 06:44:19.969  3795  3795 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:19.969  3795  3795 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:44:19.969  1019  1544 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3795 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:44:19.979  1019  1544 I ActivityManager: Killing 2932:com.sec.usbsettings/1000 (adj 15): empty #31
,03-17 06:44:19.979  3795  3795 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:19.979  3795  3795 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:19.979  1019  1544 I ActivityManager: Killing 2387:com.android.mms/u0a41 (adj 15): empty #31
,03-17 06:44:19.989  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-17 06:44:19.989  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-17 06:44:19.999  1019  1480 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 06:44:20.019  1019  1480 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 06:44:20.019  1019  1480 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-17 06:44:20.019  1019  1480 E terrier : handleString: Failed to handle string(-4)
03-17 06:44:20.019  1019  1480 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-17 06:44:20.019  3795  3795 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:20.019  3795  3795 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.019  3369  3369 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 06:44:20.019  3369  3369 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 06:44:20.039  3369  3369 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 06:44:20.039  3369  3369 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 06:44:20.039  3369  3369 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,03-17 06:44:20.039  3369  3369 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 06:44:20.049  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
03-17 06:44:20.049  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-17 06:44:20.059  1019  1043 W TextServicesManagerService: no available spell checker services found
,03-17 06:44:20.079  1444  1444 D RegisteredServicesCache: empty dynamic service
,03-17 06:44:20.109  1834  2143 D GCM     : COMPAT: Multi user not supported
,03-17 06:44:20.119  2576  2576 D FactoryTestApp: [DummyFtClient$onDestroy](2576) Destroy DummyFtClient service
,03-17 06:44:20.119  1019  1342 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 06:44:20.119  1019  1342 D SecContentProvider2: mCursor = null
,03-17 06:44:20.119  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.119  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.129  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.129  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.129  1019  1517 D CountryDetector: No listener is left
,03-17 06:44:20.139  3817  3817 E Zygote  : MountEmulatedStorage()
03-17 06:44:20.139  3817  3817 E Zygote  : v2
03-17 06:44:20.139  3817  3817 I libpersona: KNOX_SDCARD checking this for 10028
03-17 06:44:20.139  3817  3817 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.139  3817  3817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:20.139  1019  1044 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3817 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,03-17 06:44:20.149  3817  3817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:20.149  3817  3817 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:20.159  1019  1542 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.159  1019  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.159  1019  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.179  3653  3823 I Gmail   : getAccountsCursor
,03-17 06:44:20.179  1019  1480 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 06:44:20.189  1019  1539 I ActivityManager: Killing 2850:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,03-17 06:44:20.199  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-17 06:44:20.199  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-17 06:44:20.199  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-17 06:44:20.199  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-17 06:44:20.199  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 06:44:20.199  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 06:44:20.199  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 06:44:20.199  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 06:44:20.199  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 06:44:20.199  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-17 06:44:20.199  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 06:44:20.199  2576  2576 D FactoryTestApp: [Support$Values.getString](2576) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 06:44:20.199  2576  2576 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2576) mConnectionMode = gsm
03-17 06:44:20.199  2576  2576 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2576) RUNNING_FTCLIENT : false
03-17 06:44:20.199  2576  2576 D FactoryTestApp: [DummyFtClient$onDestroy](2576) kill process
03-17 06:44:20.199  2576  2576 I Process : Sending signal. PID: 2576 SIG: 9
,03-17 06:44:20.219  3795  3795 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 06:44:20.219  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:20.229  1654  1830 I art     : Explicit concurrent mark sweep GC freed 3060(120KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 728us total 22.143ms
,03-17 06:44:20.229  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:20.229  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.229  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 06:44:20.229  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:20.239  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.239  1019  1542 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 06:44:20.239  1019  1506 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 06:44:20.239  3817  3817 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:20.239  3817  3817 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.249  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:20.249  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 06:44:20.289  3653  3653 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 06:44:20.319  1019  2721 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-17 06:44:20.319  1019  1480 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.319  1019  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.319  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.319  1834  1834 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:20.329  1019  1543 W art     : Suspending all threads took: 8.544ms
,03-17 06:44:20.369  1019  1543 I art     : Explicit concurrent mark sweep GC freed 50232(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 24MB/37MB, paused 21.249ms total 347.672ms
,03-17 06:44:20.369  1019  1058 I art     : WaitForGcToComplete blocked for 51.966ms for cause Explicit
,03-17 06:44:20.369  3653  3835 I Gmail   : Observing account changes for notifications
,03-17 06:44:20.389  1019  1160 D TaskPersister: removeObsoleteFile: deleting file=11_task.xml
03-17 06:44:20.389  1019  1160 D TaskPersister: removeObsoleteFile: deleting file=11_task_thumbnail.png
,03-17 06:44:20.389  1019  1129 V NetworkStats: removeUidsLocked() for UIDs [10167]
03-17 06:44:20.389  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 06:44:20.389  1019  1129 V NetworkStats: performPollLocked(flags=0x3)
,03-17 06:44:20.389  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
,03-17 06:44:20.389  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 06:44:20.399  1019  1129 V NetworkStats: performPollLocked() took 14ms
03-17 06:44:20.399  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 06:44:20.439  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,03-17 06:44:20.439  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-17 06:44:20.439  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 06:44:20.439  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 06:44:20.439  1019  3838 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.439  1019  3838 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.439  1019  3838 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.439  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 06:44:20.439  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 06:44:20.439  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 06:44:20.439  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 06:44:20.439  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 06:44:20.449  1019  1342 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 06:44:20.449  1019  3813 I ActivityManager: Process com.sec.factory (pid 2576)(adj 0) has died(64,668)
,03-17 06:44:20.459  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 06:44:20.469  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 06:44:20.479  1019  1517 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.479  1019  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 06:44:20.479  1019  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.599  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 06:44:20.599  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:20.599  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:20.599  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.599  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.599  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.609  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.609  1019  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.609  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 06:44:20.609  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 06:44:20.609  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 06:44:20.619  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:20.619  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:44:20.619  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:20.619  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:20.629  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:20.659  1019  1216 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.659  1019  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.659  1019  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.669  1019  1480 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1174 (0x0)
,03-17 06:44:20.679  1019  1080 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 06:44:20.679  1019  1342 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.679  1019  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.679  1019  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 06:44:20.679  3817  3817 I System.out: Inside onCreate() of WakeupTriggerProvide
,03-17 06:44:20.679  3817  3817 I System.out: Inside WakeupProvider
,03-17 06:44:20.679  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
03-17 06:44:20.679  1313  3140 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
03-17 06:44:20.679  1019  1019 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-17 06:44:20.689  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.689  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.689  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.689  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.699  3848  3848 E Zygote  : MountEmulatedStorage()
,03-17 06:44:20.699  3848  3848 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:20.699  3848  3848 E Zygote  : v2
03-17 06:44:20.699  3848  3848 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.699  3848  3848 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:20.699  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:20.699  3848  3848 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:20.709  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 06:44:20.709  1019  1019 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3848 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 06:44:20.709  3848  3848 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:20.709  1313  3140 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 06:44:20.709  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 06:44:20.709  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 06:44:20.719  1019  1480 I ActivityManager: Killing 2987:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,03-17 06:44:20.719  1019  1058 I art     : Explicit concurrent mark sweep GC freed 16930(1082KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 5.258ms total 351.458ms
,03-17 06:44:20.739  3848  3848 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:20.739  3848  3848 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.749  1313  3140 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 06:44:20.759  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 06:44:20.759  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 06:44:20.759  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 06:44:20.769  3303  3414 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 06:44:20.769  1019  1058 D PackageManager: delete codoeFile: 
,03-17 06:44:20.769  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 06:44:20.769  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 06:44:20.779  1019  1058 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-17 06:44:20.779  1019  1058 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-17 06:44:20.779  1019  1058 D PackageManager: result of delete: 1{615362702}
,03-17 06:44:20.779  1019  1342 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.779  1019  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 06:44:20.779  1019  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.779  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 06:44:20.779  3715  3715 D AndroidRuntime: Shutting down VM
,03-17 06:44:20.789  1019  3813 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.789  1019  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.789  1019  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.789  3653  3868 E Gmail   : Error finding the version of the Email provider.....
03-17 06:44:20.789  3653  3868 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 06:44:20.789  3653  3868 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 06:44:20.789  3653  3868 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
03-17 06:44:20.789  3653  3868 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-17 06:44:20.789  3653  3868 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 06:44:20.789  3653  3868 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:20.789  3653  3868 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:20.789  3653  3868 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 06:44:20.789  3653  3868 W EmailMigration: We do not support migrating this version of the Email provider.
,03-17 06:44:20.789  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-17 06:44:20.789  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-17 06:44:20.789  1834  1834 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:20.789  1019  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 06:44:20.789  1019  1058 D PackageManager: userId{-1}
03-17 06:44:20.789  1019  1058 D PackageManager: andCode{true}
,03-17 06:44:20.799  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2932/cgroup.procs: No such file or directory
,03-17 06:44:20.799  1834  1834 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:20.799  1019  1043 W libprocessgroup: failed to open /acct/uid_10041/pid_2387/cgroup.procs: No such file or directory
,03-17 06:44:20.799  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.799  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.799  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.799  1019  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.809  3870  3870 E Zygote  : MountEmulatedStorage()
03-17 06:44:20.809  3870  3870 E Zygote  : v2
03-17 06:44:20.809  3870  3870 I libpersona: KNOX_SDCARD checking this for 10003
03-17 06:44:20.809  3870  3870 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.819  3870  3870 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:20.819  3870  3870 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:20.819  3870  3870 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:20.829  1019  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=3870 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-17 06:44:20.829  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.829  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.829  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.839  1019  1480 W ActivityManager: userId = 0, bbcId = -10000,
03-17 06:44:20.839  1019  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.839  1019  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 06:44:20.839  2126  3834 D GCM     : COMPAT: Multi user not supported
,03-17 06:44:20.839  1019  1342 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.839  1019  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.839  1019  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.839  3653  3823 I Gmail   : getAccountsCursor
,03-17 06:44:20.849  3817  3817 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,03-17 06:44:20.859  1019  1080 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.859  1019  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.859  1019  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.859  1019  1542 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.859  1019  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.859  1019  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.869  1019  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.869  1019  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.869  1019  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 06:44:20.869  3870  3870 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:20.869  3870  3870 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.869  1019  1342 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.869  2126  3526 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-17 06:44:20.869  1019  1342 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.869  1019  1342 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.879  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.879  1019  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.879  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.899  1019  1216 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.899  1019  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:20.899  1019  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-17 06:44:20.899  1019  1517 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 06:44:20.909  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.909  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.909  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.909  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.919  3145  3240 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 06:44:20.919  3889  3889 E Zygote  : MountEmulatedStorage()
03-17 06:44:20.919  3889  3889 E Zygote  : v2
03-17 06:44:20.919  3889  3889 I libpersona: KNOX_SDCARD checking this for 10102
03-17 06:44:20.919  3889  3889 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.929  3889  3889 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 06:44:20.929  3889  3889 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 06:44:20.929  1019  1543 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3889 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-17 06:44:20.929  3889  3889 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 06:44:20.929  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.929  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 06:44:20.929  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.929  1019  1043 W libprocessgroup: failed to open /acct/uid_10081/pid_2850/cgroup.procs: No such file or directory
,03-17 06:44:20.929  1019  1043 W libprocessgroup: failed to open /acct/uid_10043/pid_2987/cgroup.procs: No such file or directory
,03-17 06:44:20.939  1019  3813 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,03-17 06:44:20.939  3817  3817 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,03-17 06:44:20.939  3653  3653 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@28cadd7e that was originally bound here
03-17 06:44:20.939  3653  3653 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@28cadd7e that was originally bound here
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at com.android.emailcommon.service.H.a(SourceFile:181)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at com.android.emailcommon.service.H.mb(SourceFile:224)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at com.android.email.service.n.j(SourceFile:160)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:171)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at com.android.email.provider.b.F(SourceFile:115)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:20.939  3653  3653 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 06:44:20.939  1019  1517 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@3a17ecd2
,03-17 06:44:20.949  3889  3889 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:20.949  3889  3889 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.959  3848  3848 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:20.959  1019  1517 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:20.959  1019  1517 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:20.959  1019  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 06:44:20.969  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 06:44:20.969  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.969  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.969  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.969  3889  3889 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 06:44:20.989  3907  3907 E Zygote  : MountEmulatedStorage(),
03-17 06:44:20.989  3907  3907 E Zygote  : v2
03-17 06:44:20.989  3907  3907 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:20.989  3907  3907 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:20.989  3907  3907 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:20.989  1019  1216 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3907 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
03-17 06:44:20.999  3715  3715 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 06:44:20.999  3907  3907 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:20.999  3907  3907 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:21.009   327   327 I art     : Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 23.809ms
,03-17 06:44:21.019  1019  1080 I ActivityManager: Killing 3003:com.sec.dsm.system/1000 (adj 15): empty #31
,03-17 06:44:21.029   327   327 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 18.387ms
,03-17 06:44:21.029  2126  3899 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 06:44:21.039  3907  3907 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.039  3907  3907 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.049   327   327 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 16.741ms
,03-17 06:44:21.059  3907  3907 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 06:44:21.079  1654  3888 I GoogleHttpClient: GMS http client unavailable, use old client,
,03-17 06:44:21.099  1019  1517 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:21.099  1019  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:21.099  1019  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:21.109  2126  3925 I CheckinService: Checking schedule, now: 1458193461117 next: 1458299986961
,03-17 06:44:21.109  2126  3925 I CheckinService: active receiver: disabled
,03-17 06:44:21.139  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3003/cgroup.procs: No such file or directory
,03-17 06:44:21.139  3817  3817 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 06:44:21.139  3817  3817 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 06:44:21.149  3817  3817 D DialogFlow: initQueue()
,03-17 06:44:21.159  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.159  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.159  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.159  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.169  3907  3907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:21.169  3930  3930 E Zygote  : MountEmulatedStorage()
,03-17 06:44:21.169  3930  3930 E Zygote  : v2
03-17 06:44:21.169  3930  3930 I libpersona: KNOX_SDCARD checking this for 10029
03-17 06:44:21.169  3930  3930 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:21.179  3930  3930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 06:44:21.179  3930  3930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 06:44:21.179  1019  1216 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3930 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
03-17 06:44:21.179  1019  1216 I ActivityManager: Killing 3033:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-17 06:44:21.179  3930  3930 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:21.179  1019  3833 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.179  1019  3833 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.179  1019  3833 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-17 06:44:21.189  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.189  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.189  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.189  1019  3813 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.189  3907  3907 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-17 06:44:21.189  3907  3907 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-17 06:44:21.199  3945  3945 E Zygote  : MountEmulatedStorage()
03-17 06:44:21.199  3945  3945 E Zygote  : v2
03-17 06:44:21.199  3945  3945 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:21.199  3945  3945 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:21.199  3945  3945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:21.199  3945  3945 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:44:21.209  1019  3813 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3945 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 06:44:21.209  3945  3945 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:21.209  1019  1539 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.209  1019  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.209  1019  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-17 06:44:21.209  3930  3930 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:21.209  3930  3930 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.219  1019  1487 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.219  1019  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:21.219  1019  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:21.219  2126  2126 D ChimeraCfgMgr: Reading stored module config
,03-17 06:44:21.229  1019  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.229  1019  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:21.229  1019  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:21.239  2126  3834 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 06:44:21.239  1019  1544 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.239  1019  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:21.239  1019  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:21.239  3907  3907 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-17 06:44:21.239  3907  3907 I F_PHONE : default registerAction()
03-17 06:44:21.239  3907  3907 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 06:44:21.239  3945  3945 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:21.239  3945  3945 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.259  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3033/cgroup.procs: No such file or directory
,03-17 06:44:21.259  3945  3945 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 06:44:21.279  3945  3945 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-17 06:44:21.279  3945  3945 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:21.279  1019  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:21.279  1019  1080 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.279  1019  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-17 06:44:21.289  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.289  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.289  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.289  1019  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.289  1459  1459 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 06:44:21.299  3963  3963 E Zygote  : MountEmulatedStorage(),
03-17 06:44:21.299  1459  1459 D BluetoothBDTestService: onCreate()
03-17 06:44:21.299  1459  1459 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED,
03-17 06:44:21.299  3963  3963 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:21.299  3963  3963 E Zygote  : v2
03-17 06:44:21.299  3963  3963 I libpersona: KNOX_SDCARD not a persona,
03-17 06:44:21.299  1459  1459 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr,
03-17 06:44:21.299  1459  1459 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
03-17 06:44:21.299  3963  3963 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:21.299  3963  3963 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 06:44:21.309  1019  1216 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3963 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-17 06:44:21.309  3963  3963 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:21.329  3963  3963 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.329  3963  3963 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.339  3963  3963 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:21.389  1019  1543 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 06:44:21.409  3963  3963 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-17 06:44:21.409  3963  3963 I KnoxUsageLogPro: premStatus:2
,03-17 06:44:21.409  3963  3963 I KnoxUsageLogPro: isEulaShown : false
,03-17 06:44:21.409  3963  3963 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-17 06:44:21.409  3963  3980 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458193461422
,03-17 06:44:21.409  1019  1543 I ActivityManager: Killing 1613:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,03-17 06:44:21.439  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 06:44:21.439  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:21.439  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:21.439  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:21.439  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:21.439  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:21.459  2126  2126 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-17 06:44:21.459  2126  2126 D BootCompletedReceiver: Got an BootCompleted event.
,03-17 06:44:21.469  2126  2126 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-17 06:44:21.479  2126  2126 D SystemUpdateService: onCreate
,03-17 06:44:21.499  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.499  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.499  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.499  1019  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.509  3990  3990 E Zygote  : MountEmulatedStorage(),
03-17 06:44:21.509  3990  3990 I libpersona: KNOX_SDCARD checking this for 10030
03-17 06:44:21.509  3990  3990 E Zygote  : v2
03-17 06:44:21.509  3990  3990 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:21.509  3990  3990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:44:21.519  1019  1543 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3990 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 06:44:21.519  1019  1543 I ActivityManager: Killing 3059:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-17 06:44:21.519  3990  3990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:44:21.519  3990  3990 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 06:44:21.519  1019  1517 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.519  1019  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:21.519  1019  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:21.539  1019  1043 W libprocessgroup: failed to open /acct/uid_10068/pid_1613/cgroup.procs: No such file or directory
,03-17 06:44:21.539  3990  3990 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.539  3990  3990 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.559  2126  2126 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 06:44:21.569  2126  4009 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 06:44:21.599  2126  4009 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-17 06:44:21.609  3963  3980 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 42186
,03-17 06:44:21.639  2126  4009 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 06:44:21.659  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3059/cgroup.procs: No such file or directory
,03-17 06:44:21.659  2126  4008 I SystemUpdateService: cancelUpdate (empty URL)
03-17 06:44:21.659  2126  4008 I SystemUpdateService: active receiver: disabled
,03-17 06:44:21.669  1019  3813 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.669  1019  3813 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:21.669  1019  3813 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:21.719  3889  4015 I Babel   : MmsConfig: mnc/mcc: 0/0
,03-17 06:44:21.719  3889  4015 I Babel   : MmsConfig.loadMmsSettings
03-17 06:44:21.719  2126  4009 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-17 06:44:21.719  3889  4015 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-17 06:44:21.719  3889  4015 I Babel   : MmsConfig.loadFromDatabase
,03-17 06:44:21.769  3889  3906 W art     : Suspending all threads took: 18.253ms
,03-17 06:44:21.829  3889  4012 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 06:44:21.839  3889  4012 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 06:44:21.839  3889  4012 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 06:44:21.839  3889  4015 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,03-17 06:44:21.839  3889  4015 I Babel   : MmsConfig.loadFromResources
,03-17 06:44:21.839  3889  4012 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 06:44:21.839  3889  4012 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 06:44:21.849  3889  4015 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,03-17 06:44:21.849  3889  4015 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-17 06:44:21.849  3889  4012 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-17 06:44:21.849  3889  4012 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 06:44:21.859  3889  4012 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 06:44:21.859  3889  4012 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 06:44:21.859  1019  3833 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.859  1019  3833 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 06:44:21.859  1019  3833 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:21.899  3369  3379 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-17 06:44:21.919  3145  3240 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 06:44:21.939  3889  4012 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 06:44:21.949  3889  3889 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 06:44:21.959  2126  4009 I AuthZen : Fetching signing key...
,03-17 06:44:21.959  2126  2126 D SystemUpdateService: onDestroy
,03-17 06:44:21.959  3889  4012 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 06:44:21.999  3990  3990 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 30
,03-17 06:44:21.999  3990  3990 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 30
,03-17 06:44:21.999  3990  3990 W System.err: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
,03-17 06:44:22.009  3990  3990 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
,03-17 06:44:22.009  3990  3990 W System.err: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
,03-17 06:44:22.009  3990  3990 W System.err: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
,03-17 06:44:22.009  3990  3990 W System.err: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
,03-17 06:44:22.009  3990  3990 W System.err: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
03-17 06:44:22.009  3990  3990 W System.err: 	at com.sec.android.app.sns3.agent.db.SnsDBWrapper.onDelete(SnsDBWrapper.java:44)
,03-17 06:44:22.019  3990  3990 W System.err: 	at com.sec.android.app.sns3.agent.db.SnsSvcContentProvider.deleteSSOAccount(SnsSvcContentProvider.java:192)
03-17 06:44:22.019  3990  3990 W System.err: 	at com.sec.android.app.sns3.agent.db.SnsSvcContentProvider.initSSOAccounts(SnsSvcContentProvider.java:86)
03-17 06:44:22.019  3990  3990 W System.err: 	at com.sec.android.app.sns3.agent.db.SnsSvcContentProvider.onCreate(SnsSvcContentProvider.java:68)
03-17 06:44:22.019  3990  3990 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
03-17 06:44:22.019  3990  3990 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
03-17 06:44:22.019  3990  3990 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
03-17 06:44:22.019  3990  3990 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
03-17 06:44:22.019  3990  3990 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
,03-17 06:44:22.019  3990  3990 W System.err: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 06:44:22.019  3990  3990 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 06:44:22.019  3990  3990 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:22.019  3990  3990 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:22.019  3990  3990 W System.err: ,	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:44:22.019  3990  3990 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:44:22.019  3990  3990 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:44:22.019  3990  3990 W System.err: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:44:22.019  3990  3990 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 06:44:22.019  2126  3526 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-17 06:44:22.019  1654  3690 I art     : Explicit concurrent mark sweep GC freed 3943(167KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 819us total 27.256ms
,03-17 06:44:22.029  3990  3990 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-17 06:44:22.029  3990  3990 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:22.029  3990  3990 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 06:44:22.039  2126  4009 I AuthZen : Signing key fetched successfully!
,03-17 06:44:22.049  1654  1674 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-17 06:44:22.049  2126  4009 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 06:44:22.059  3889  4012 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-17 06:44:22.069  2126  3526 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml
,03-17 06:44:22.079  2126  4009 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/keys.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 06:44:22.079  2126  4009 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/keys.db'.
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.keyservice.j.c(:com.google.android.gms:228)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:186)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:153)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:103)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:258)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:209)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:202)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.a.a(:com.google.android.gms:148)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(:com.google.android.gms:30)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:22.079  2126  4009 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: Couldn't open keys.db for writing (will try read-only):
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.data,base.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.keyservice.j.c(:com.google.android.gms:228)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:186)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:153)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.b.d.a(:com.google.android.gms:103)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:258)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:209)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(:com.google.android.gms:202)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.a.a(:com.google.android.gms:148)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(:com.google.android.gms:30)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:22.079  2126  4009 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 06:44:22.079  2126  4009 W SQLiteOpenHelper: Opened keys.db in read-only mode
,03-17 06:44:22.079  3889  4012 W VideoCapabilities: Unsupported mime video/wvc1

```
