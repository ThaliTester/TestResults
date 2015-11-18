#### Test 5107482134e3b48_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
E/SELinux ( 2670): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
--------- beginning of system
I/ActivityManager( 1017): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2670 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
D/TimaKeyStoreProvider( 2670): TimaSignature is unavailable
D/ActivityThread( 2670): Added TimaKeyStore provider
E/LocSvc_utils_cfg( 1017): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
I/qmi_secgps_clnt( 1017): SECGPS: Set AGPS Mode : 7
D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/qmi_secgps_clnt( 1017): SECGPS: Set XTRA enable : 1
D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1017): SECGPS: Set GNSS RF CONFIG : 1
D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1017): SECGPS: Set CERT TYPE : 15
D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
E/LocSvc_ApiV02( 1017): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
E/ActivityThread( 2670): Failed to find provider info for flipboard.auth.internal.debug
E/ActivityThread( 2670): Failed to find provider info for flipboard.auth.internal
I/splitIntent( 1017): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=89, mSplitNum[1]=126, mSplitNum[2]=163, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 52 receivers.size=199
I/splitIntent( 1017): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
I/DrmEventReceiver( 1017): DrmEventReceiver : onReceive
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
I/DrmEventReceiver( 1017): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
I/DrmEventReceiver( 1017): DrmEventReceiver : beginStartingService
I/System.out( 1017): start Service
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
V/DownloadManager( 1227): onReceive intent + android.intent.action.BOOT_COMPLETED
D/SensorService( 1017): [SO] currT = 30741496000, prevT = 30281128000, diff = 460368000, [0.172 0.077 10.190]
D/SensorService( 1017): [SO] 0.172 0.077 10.190
D/SensorService( 1017): [SO] [100 -> 255]
E/Zygote  ( 2692): MountEmulatedStorage()
I/libpersona( 2692): KNOX_SDCARD checking this for 10085
E/Zygote  ( 2692): v2
I/libpersona( 2692): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2692 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2692): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/SELinux ( 2692): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2692): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Zygote  ( 2702): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2702 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 2702): v2
D/ActivityManager( 1017): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
I/libpersona( 2702): KNOX_SDCARD checking this for 1000
I/SELinux ( 2702): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 2702): KNOX_SDCARD not a persona
I/SELinux ( 2702): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2702): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/TimaKeyStoreProvider( 2692): TimaSignature is unavailable
D/ActivityThread( 2692): Added TimaKeyStore provider
D/WVMDrmPlugIn(  282): WVMDrmPlugin::onInitialize : 1633
D/WVMDrmPlugIn(  282): WVMDrmPlugin::onSetOnInfoListener : add 1633
D/TimaKeyStoreProvider( 2702): TimaSignature is unavailable
D/ActivityThread( 2702): Added TimaKeyStore provider
D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1017): mCursor = null
I/DrmEventService( 1017): action event :android.intent.action.BOOT_COMPLETED
D/MediaScannerReceiver( 1227): action: android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
W/ResourcesManager( 2692): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2692): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2692): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2692): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2692): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2692): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
I/TimaServiceEventReceiver( 1017): TimaServiceEventReceiver : onReceive
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/ANDROID_DRM_FRWORKS_DrmManager(  282): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
E/CscReceiver( 1470): onReceive android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2728): MountEmulatedStorage()
E/Zygote  ( 2728): v2
I/libpersona( 2728): KNOX_SDCARD checking this for 10160
I/libpersona( 2728): KNOX_SDCARD not a persona
I/SELinux ( 2728): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2728): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2728 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
E/SELinux ( 2728): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/CscUpdateService( 1470): onStart
E/CscUpdateService( 1470): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1470): set_CSC_version
E/CscParser( 1470): update(): xml file exist
E/Zygote  ( 2742): MountEmulatedStorage()
E/Zygote  ( 2742): v2
I/libpersona( 2742): KNOX_SDCARD checking this for 10003
I/libpersona( 2742): KNOX_SDCARD not a persona
I/SELinux ( 2742): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 2728): TimaSignature is unavailable
I/SELinux ( 2742): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityThread( 2728): Added TimaKeyStore provider
E/SELinux ( 2742): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2742 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
I/CscUtil ( 1470): isWifiOnly = false
I/System.out( 1470): HandDataNode = null
I/CscUpdateService( 1470): PATH_CSCNAME =CustomerDataSet.CSCName
I/CscUpdateService( 1470): This is normal boot : CSC not updated
D/TimaKeyStoreProvider( 2742): TimaSignature is unavailable
W/ResourcesManager( 2728): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/ActivityThread( 2742): Added TimaKeyStore provider
E/CscParser( 1470): update(): xml file exist
D/CscGPS  ( 1470): CSCGPS.updateParameters
D/CscGPS  ( 1470): supl host : null
D/CscGPS  ( 1470): SUPL Host is null or invalid
D/CscGPS  ( 1470): supl_ver : null
D/CscGPS  ( 1470): SUPL Ver is null or invalid
D/CscGPS  ( 1470): supl port : null
D/CscGPS  ( 1470): SUPL PORT is null or invalid
D/CscGPS  ( 1470): LPP : null
D/CscGPS  ( 1470): LPP is null or invalid
D/CscGPS  ( 1470): CSC don't have any AGPS value.
D/MediaScannerService( 1227): !@start scanning volume internal: [/system/media, /oem/media]
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
E/SMD     (  288): DCD OFF
D/TP/MmsProvider( 1470): Update uri=content://mms, match=0
D/TP/MmsProvider( 1470): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1470): need read changed broadcast:false
D/MtpService( 1227): updating state; isCurrentUser=true, mMtpLocked=false
I/Mms:transaction( 2291): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2291): [start]    nonBlockingUpdateMessageIndicator() consume time = 2261.383176
I/Mms/ReservationManager( 2291): resetAfterConnected()
D/Mms/MessagingNotification( 2291): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2291): isDefault true
I/CscUpdateService( 1470): same CSC Version
D/CscUtil ( 1470): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
D/TP/MmsProvider( 1470): Query uri=content://mms, match=0, calling pid = 2291
D/TP/MmsSmsProvider( 1470): query,matched:7, calling pid = 2291
D/TP/MmsSmsProvider( 1470): match 7:Elapsed time : 2.446 ms
I/Mms/ReservationManager( 2291): getReservedSendMessageCount(): retMessageCount=0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1470): query,matched:200, calling pid = 2291
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1470): match 200:Elapsed time : 2.161 ms
E/Zygote  ( 2763): MountEmulatedStorage()
E/Zygote  ( 2763): v2
I/libpersona( 2763): KNOX_SDCARD checking this for 10048
I/libpersona( 2763): KNOX_SDCARD not a persona
I/SELinux ( 2763): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2763): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2763 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 2763): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/USB_UICC(  297): Timeout! No signal received. Retry num = 25
D/Mms/SmsReceiverService( 2291): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/Mms/TelephonyPermission( 2291): isDefault true
D/Mms/SmsReceiverService( 2291): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2291): [start]    handleBootCompleted() consume time = 50.311979
D/TimaKeyStoreProvider( 2763): TimaSignature is unavailable
D/ActivityThread( 2763): Added TimaKeyStore provider
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
W/ResourcesManager( 2763): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2763): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2763): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
I/SecureStorage( 2742): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
D/[0]UMC:UMCContentProvider( 2728): @onCreate
D/TP/MmsSmsProvider( 1470): getThreadUnReadCount unreadCount=0 imUnreadCount=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1470): deleteConversation threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1470): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1470): updateThread(), thread_id = 9223372036854775806
V/TP/MmsSmsDatabaseHelper( 1470): sUpgradeVersion = 0, db.getVersion() = 81
D/[0]UMC:Core( 2728): onCreate(): 
E/SQLiteLog( 1470): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1470): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1470): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1470): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1470): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1470): (284) automatic index on im_threads(normal_thread_id)
D/[0]UMC:Core( 2728): @isManagedProfileUser
D/[0]UMC:Core( 2728): userId: 0
E/Zygote  ( 2780): MountEmulatedStorage()
I/libpersona( 2780): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2780): v2
I/libpersona( 2780): KNOX_SDCARD not a persona
I/SELinux ( 2780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/TP/MmsSmsProvider( 1470): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1470): need read changed broadcast:false
I/SELinux ( 2780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2780): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[0]UMC:Core( 2728): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2728): userInfo.isManagedProfile() : false
E/SQLiteLog( 1227): (283) recovered 230 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
I/ActivityManager( 1017): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2780 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/Mms/Conversation( 2291): deleteTempConversation(),deleted=0
I/art     ( 1470): Explicit concurrent mark sweep GC freed 39144(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 7MB/12MB, paused 1.337ms total 119.452ms
D/TP/SmsProvider( 1470): query,matched:0, calling pid = 2291
D/TP/SmsProvider( 1470): match 0:Elapsed time : 1.300 ms
D/SmsProvider( 1470): Update uri=content://sms/outbox, match=8
D/TP/SmsProvider( 1470): query,matched:51, calling pid = 2291
D/SettingsProvider( 1017): name = block_emergency_message
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10048
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/ActivityManager( 1017): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
D/TimaKeyStoreProvider( 2780): TimaSignature is unavailable
D/ActivityThread( 2780): Added TimaKeyStore provider
D/TP/SmsProvider( 1470): match 51:Elapsed time : 9.233 ms
D/[0]UMC:DeviceInfo( 2728): USA==US==
D/TP/MmsSmsProvider( 1470): need read changed broadcast:false
I/SecureStorage( 2742): [INFO]: SPID(0x00000000)This device supports Secure Storage
D/Mms/SmsReceiverService( 2291): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2291): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2291): [SIM-1]sendFirstQueuedMessage()
I/SecureStorage(  397): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2742
I/SecureStorage(  397): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 2742): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecureStorage( 2742): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  397): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2742
I/SecureStorage(  397): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
D/TP/SmsProvider( 1470): query,matched:26, calling pid = 2291
D/Mms/MessagingNotification( 2291): isBlockingModeEnabled() = false, Zen mode = 0
D/TP/SmsProvider( 1470): match 26:Elapsed time : 1.322 ms
D/BadgeProvider( 1570): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/Mms/SmsReceiver( 2291): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2291): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2291): isDefault true
D/TP/MmsProvider( 1470): Query uri=content://mms, match=0, calling pid = 2291
D/TP/MmsSmsProvider( 1470): query,matched:200, calling pid = 2291
D/TP/MmsSmsProvider( 1470): match 200:Elapsed time : 1.330 ms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
I/WifiCredService( 1298): onCreate
D/TP/SmsProvider( 1470): query,matched:0, calling pid = 2291
D/TP/SmsProvider( 1470): match 0:Elapsed time : 1.873 ms
D/BadgeProvider( 1570): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1570): sendNotify, [notify] : null
D/BadgeProvider( 1570): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1570): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1570): update, [UpdateCount] : 1
D/Launcher.Model( 1493): reloadBadges entered.
D/Mms/MessagingNotification( 2291): setBadgeCount(), count=0
D/Mms/MessagingNotification( 2291): remove alarm
D/SettingsProvider( 1017): name = next_alarm_formatted
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10085
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/WifiTimerReceiver( 1298): action: android.intent.action.BOOT_COMPLETED
D/TP/SmsProvider( 1470): query,matched:51, calling pid = 2291
D/WifiTimerReceiver( 1298): extra: Bundle[mParcelledData.dataSize=84]
D/TP/SmsProvider( 1470): query,matched:0, calling pid = 2291
D/MY_TAG  ( 1298): Action boot completed received
D/TP/SmsProvider( 1470): match 0:Elapsed time : 2.646 ms
D/TP/SmsProvider( 1470): match 51:Elapsed time : 2.713 ms
D/Mms/MessagingNotification( 2291): [end]    nonBlockingUpdateMessageIndicator() consume time = 237.520521
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
E/SQLiteLog( 2780): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
D/Mms/MessagingNotification( 2291): updateAllHistoryAsRead()
D/Mms/MessagingNotification( 2291): isBlockingModeEnabled() = false, Zen mode = 0
I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
D/BadgeProvider( 1570): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/NearbySettings( 1298): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1298): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1298): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 1298): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
V/NearbySettings( 1298): MountReceiver.mPrefHandler - 7002
D/SettingsProvider( 1017): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
D/USER_AGENT( 2728): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
D/[0]UMC:AdminManager( 2728): init - start
D/[0]UMC:AdminManager( 2728): loadAdmins
D/BadgeProvider( 1570): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/Launcher.Model( 1493): reloadBadges entered.
D/BadgeProvider( 1570): sendNotify, [notify] : null
D/BadgeProvider( 1570): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1570): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1570): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 2291): setBadgeCount(), count=0
D/Mms/MessagingNotification( 2291): remove alarm
D/Mms/MessagingNotification( 2291): updateAllHistoryAsRead()
D/[0]UMC:AdminManager( 2728): init - end
D/GSLBManager( 2728): migrateStoredUrlFromOldPref
D/TP/SmsProvider( 1470): query,matched:0, calling pid = 2291
D/TP/SmsProvider( 1470): match 0:Elapsed time : 1.940 ms
D/Mms/SmsReceiverService( 2291): [end]    handleBootCompleted() consume time = 93.075364
D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
D/MediaScanner( 1227): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/DSM     ( 2780): [Lines:107] Normal booted
D/DSM     ( 2780): [Lines:114] Boot completed
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/NearbySettings( 1298): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1298): MountReceiver.onReceive - Internal Path
E/Zygote  ( 2809): MountEmulatedStorage()
I/libpersona( 2809): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2809): v2
I/libpersona( 2809): KNOX_SDCARD not a persona
I/SELinux ( 2809): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2809 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 2809): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2809): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 1197:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
D/GSLBManager( 2728):  key : segd-api
D/GSLBManager( 2728):  value : https://eu-segd-api.secb2b.com:443/v2
V/MediaScanner( 1227): processDirectory :  /system/media
D/SettingsProvider( 1017): name = personal_mode_enabled
D/GSLBManager( 2728):  key : umc-cdn
D/GSLBManager( 2728):  value : 
D/TimaKeyStoreProvider( 2809): TimaSignature is unavailable
D/ActivityThread( 2809): Added TimaKeyStore provider
D/GSLBManager( 2728):  key : segp-api
D/GSLBManager( 2728):  value : 
V/MediaScanner( 1227):  prescan time: 415ms (DB items: 141)
V/MediaScanner( 1227):     scan time: 36ms (Caching mode: true), (makeEntry time: 21ms ~58%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 451ms
V/MediaScanner( 1227): checked files: 133  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1227): checkDefaultSounds
D/MediaScanner( 1227): system alarm_alert  : Vwiurug_etwofi5wgg
,W/ResourcesManager( 2809): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1470): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/MediaScanner( 1227): OK. alarm_alert is already exist in setting DB.
D/MediaScanner( 1227): system notification_sound  : K_Oprkltf5wgg
D/MediaScanner( 1227): OK. notification_sound is already exist in setting DB.
D/MediaScanner( 1227): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/GSLBManager( 2728):  key : myknoxapi
D/GSLBManager( 2728):  value : 
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_1197/cgroup.procs: No such file or directory
I/SmartcardBootCompleteReceiver( 1298): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1298): Received intent with action - android.intent.action.BOOT_COMPLETED
W/ContextImpl( 1298): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
I/SmartcardBootCompleteReceiver( 1298): Broadcast sent with current lockscreen type
W/art     ( 2692): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 147.898ms
D/GSLBManager( 2728): migrateStoredUrlFromOldPref : Finished Migrating
D/[0]UMC:UMCAdmin( 2728): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 2728): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2728): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2728): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2728): isContainer : 0
D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 2728): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2728): isContainer : 0
D/[0]UMC:UMCAdmin( 2728): deactivateUMCAdmin - UMC App Admin deactivated
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
D/[SBeam] ( 1298): SBeamEnabler.initPreferenceForSbeam : 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/[0]UMC:GuardService( 2728): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
I/SettingSearch/SearchIntentReceiver( 1298): action : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2728): Intent : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1298): search setting db init!!
D/[0]UMC:CoreReceiver( 2728):  check PreETag 
W/ContextImpl( 1298): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
I/SettingSearch/SearchIntentReceiver( 1298): BOOT_COMPLETED call InitSerachDBThread thread start!
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/art     ( 1017): Explicit concurrent mark sweep GC freed 59453(3MB) AllocSpace objects, 19(442KB) LOS objects, 33% free, 26MB/39MB, paused 2.335ms total 165.534ms
W/ActivityThread( 2809): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
E/Zygote  ( 2831): MountEmulatedStorage()
E/Zygote  ( 2831): v2
I/libpersona( 2831): KNOX_SDCARD checking this for 1000
I/libpersona( 2831): KNOX_SDCARD not a persona
I/SELinux ( 2831): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2831): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2831): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[0]UMC:CoreReceiver( 2728): bulk enrolled package: null
I/ActivityManager( 1017): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=2831 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
V/[0]UMC:ProfileStorage( 2728): Enter loadList
D/[0]UMC:CoreReceiver( 2728): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2728): deactivateUMCAdminIfNotRequired : -1
D/MediaScanner( 1227): OK. ringtone is already exist in setting DB.
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
I/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
E/[0]UMC:Utils( 2728): Admin not found in package com.samsung.knoxpb.mdm
I/art     (  304): Explicit concurrent mark sweep GC freed 8760(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 25.396ms
E/[0]UMC:Utils( 2728): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2728): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2728): isContainer : 0
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 959us total 19.652ms
D/TimaKeyStoreProvider( 2831): TimaSignature is unavailable
D/ActivityThread( 2831): Added TimaKeyStore provider
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 19.410ms
D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 2728): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2728): isContainer : 0
D/[0]UMC:UMCAdmin( 2728): deactivateUMCAdmin - UMC App Admin deactivated
D/FactoryTestApp( 2578): [DummyFtClient$mBroadcastReceiver](2578) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2578): [DummyFtClient$mBroadcastReceiver](2578) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2578): [DummyFtClient$mBroadcastReceiver](2578) ACTION_MEDIA_SCANNER_FINISHED = Ignored
D/MediaScannerService( 1227): !@done scanning volume internal
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/[0]UMC:ByodSetupStarter( 2728): Container ID : 0
E/Zygote  ( 2849): MountEmulatedStorage()
I/libpersona( 2849): KNOX_SDCARD checking this for 10150
E/Zygote  ( 2849): v2
I/libpersona( 2849): KNOX_SDCARD not a persona
I/SELinux ( 2849): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/ResourcesManager( 2831): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SELinux ( 2849): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2849): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 2824): 
D/AndroidRuntime( 2824): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/AndroidRuntime( 2824): CheckJNI is OFF
D/AndroidRuntime( 2824): readGMSProperty: start
D/AndroidRuntime( 2824): readGMSProperty: already setted!!
D/AndroidRuntime( 2824): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2824): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2824): readGMSProperty: end
D/AndroidRuntime( 2824): addProductProperty: start
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 2809): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/ActivityManager( 1017): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=2849 uid=10150 gids={50150, 9997} abi=armeabi-v7a
D/MediaScannerService( 1227): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
V/[0]UMC:Utils( 2728): checkAppScreen() : com.sec.android.app.launcher
I/[0]UMC:Core( 2728): shutdown
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/[0]UMC:GuardService( 2728): @GuardService - stopService Result = true
I/LcdtestApp( 2809): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
I/art     ( 2728): System.exit called, status: 0
I/AndroidRuntime( 2728): VM exiting with result code 0, cleanup skipped.
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2866 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
I/ActivityManager( 1017): Killing 1389:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
E/Zygote  ( 2866): MountEmulatedStorage()
E/Zygote  ( 2866): v2
I/libpersona( 2866): KNOX_SDCARD checking this for 1000
I/libpersona( 2866): KNOX_SDCARD not a persona
I/SELinux ( 2866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2866): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2849): TimaSignature is unavailable
D/ActivityThread( 2849): Added TimaKeyStore provider
D/MediaScanner( 1227): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2866): TimaSignature is unavailable
D/ActivityThread( 2866): Added TimaKeyStore provider
E/Zygote  ( 2888): MountEmulatedStorage()
E/Zygote  ( 2888): v2
I/libpersona( 2888): KNOX_SDCARD checking this for 1000
I/libpersona( 2888): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=2888 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 1407:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
I/SELinux ( 2888): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2888): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2888): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/AffinityControl( 2824): AffinityControl: registerfunction enter
I/ActivityManager( 1017): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2728)(adj 0) has died(194,1003)
D/daemonapp( 1287): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1287): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/SecureStorage(  397): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
D/AndroidRuntime( 2824): Calling main entry com.android.commands.am.Am
D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/TimaKeyStoreProvider( 2888): TimaSignature is unavailable
D/ActivityThread( 2888): Added TimaKeyStore provider
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
I/SecureStorage( 2742): [INFO]: SPID(0x00000001)Processing data has been completed
D/daemonapp( 1287): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
I/SecureStorage( 2742): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/comsamsunglog( 1287): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1287): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1287): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1287): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1287): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1287): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1017): mDVFSHelper.acquire()
V/MediaScanner( 1227): processDirectory :  /storage/emulated/0
D/FocusedStackFrame( 1017): Set to : 0
D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(75ebcf7
D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
W/ResourcesManager( 2888): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_1389/cgroup.procs: No such file or directory
D/Launcher.HomeView( 1493): onPause
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1493
I/FOTA    ( 2831): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
V/MediaScanner( 1227): processDirectory :  /storage/extSdCard
W/MediaScanner( 1227): Error opening directory, reason : Permission denied.
W/MediaScanner( 1227): 7klwibgf7fxlKdCbid7
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
V/MediaScanner( 1227):  prescan time: 207ms (DB items: 27)
V/MediaScanner( 1227):     scan time: 21ms (Caching mode: true), (makeEntry time: 12ms ~57%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 230ms
V/MediaScanner( 1227): checked files: 10  directories : 17  (I: 0, U: 0)
D/SettingsProvider( 1017): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10162
D/AndroidRuntime( 2824): Shutting down VM
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, iello
W/libprocessgroup( 1017): failed to open /acct/uid_10096/pid_1407/cgroup.procs: No such file or directory
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/MediaScannerService( 1227): !@done scanning volume external
E/USB_UICC(  297): Timeout! No signal received. Retry num = 26
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/Zygote  ( 2909): MountEmulatedStorage()
E/Zygote  ( 2909): v2
I/libpersona( 2909): KNOX_SDCARD checking this for 10174
I/libpersona( 2909): KNOX_SDCARD not a persona
I/SELinux ( 2909): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2909 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2909): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2909): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/ActivityThread( 1493): updateVisibility : ActivityRecord{34592c79 token=android.os.BinderProxy@3cd7001c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/FactoryTestApp( 2578): [DummyFtClient$mBroadcastReceiver](2578) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2578): [DummyFtClient$mBroadcastReceiver](2578) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2578): [DummyFtClient$sendBootCompletedAndFinish](2578) ...
D/FactoryTestApp( 2578): [Support$Values.getString](2578) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2578): [ModuleCommon$isConnectionModeNone](2578) mConnectionMode = gsm
D/FactoryTestApp( 2578): [IPCWriterToSecPhoneService$ResponseWriter](2578) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2578): [IPCWriterToSecPhoneService$connectToSecPhoneService](2578)  
I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
W/ContextImpl( 2578): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
D/daemonapp( 1287): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
D/daemonapp( 1287): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1287): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/TimaKeyStoreProvider( 2909): TimaSignature is unavailable
D/ActivityThread( 2909): Added TimaKeyStore provider
D/daemonapp( 1287): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
I/iu.UploadsManager( 1882): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
E/daemonapp( 1287): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/daemonapp( 1287): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1447834328202
D/daemonapp( 1287): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1447855920000
D/daemonapp( 1287): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1287): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1493): onStop
V/ActivityThread( 1493): updateVisibility : ActivityRecord{34592c79 token=android.os.BinderProxy@3cd7001c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/DBG_DM  ( 2831): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
I/DBG_DM  ( 2831): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/DBG_DM  ( 2831): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
D/PersonaManager( 1017): isKioskContainerExistOnDevice
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/Launcher( 1493): onTrimMemory. Level: 20
D/SensorService( 1017): [SO] 0.192 0.077 10.209
E/Zygote  ( 2929): MountEmulatedStorage()
I/libpersona( 2929): KNOX_SDCARD checking this for 10086
E/Zygote  ( 2929): v2
I/libpersona( 2929): KNOX_SDCARD not a persona
I/SELinux ( 2929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/DIAGMON_AGENT( 2866): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
I/SELinux ( 2929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2929): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2929 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
I/FactoryTestApp( 2578): [IPCWriterToSecPhoneService$onServiceConnected](2578) connected done
D/FactoryTestApp( 2578): [IPCWriterToSecPhoneService$write](2578) Send Response Message to SecPhone
D/FactoryTestApp( 2578): [IPCWriterToSecPhoneService$write](2578) Response ��
D/daemonapp( 1287): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1447855920000
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1017): [SO] activate (ident=0xb7dadf30, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/SensorManager( 1017): unregisterListener ::   
D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 12
D/daemonapp( 1287): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1447855920000
I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb7e80b10, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/AT_Distributor(  309): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/TimaKeyStoreProvider( 2929): TimaSignature is unavailable
D/ActivityThread( 2929): Added TimaKeyStore provider
W/art     ( 2824): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/FactoryTestApp( 2578): [IPCWriterToSecPhoneService$handleMessage](2578) Send BOOTING COMPLETED done
,I/WebViewFactory( 2909): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,I/LibraryLoader( 2909): Time to load native libraries: 2 ms (timestamps 2271-2273)
,I/LibraryLoader( 2909): Expected native library version number "",actual native library version number ""
,I/iu.UploadsManager( 1882): End new media; added: 0, uploading: 0, time: 202 ms
,D/AT_Distributor(  309): SetAtdStatus(), 1_1_0
D/AT_Distributor(  309): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,I/DBG_DM  ( 2831): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 2831): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 2831): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 2831): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 2831): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_DM  ( 2831): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,I/DBG_DM  ( 2831): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,D/OverheatReceiver( 1176): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1176): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1176): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1176): isSafeMode = false
I/DBG_DM  ( 2831): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
D/SensorService( 1017): [SO] 0.172 0.096 10.209
,D/SensorService( 1017): [SO] [100 -> 255]
,I/DBG_DM  ( 2831): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 2831): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_DM  ( 2831): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,I/DBG_DM  ( 2831): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,D/BootupListener( 1470): intent.getAction() = android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 2831): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,D/SettingsProvider( 1017): name = internet_call_settings_visibility
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/DBG_DM  ( 2831): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,D/PhoneUtilsCommon( 1470): isSupportVoLTE is false.
,I/DBG_DM  ( 2831): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 2831): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/DBG_DM  ( 2831): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,E/UpdateRequestReceiver( 2929): ignoring update request
,I/DBG_DM  ( 2831): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/Telecom ( 1446): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,I/DBG_DM  ( 2831): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/DBG_DM  ( 2831): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
I/DBG_DM  ( 2831): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
V/WebViewChromiumFactoryProvider( 2909): Binding Chromium to main looper Looper (main, tid 1) {36d6d60a}
I/DBG_DM  ( 2831): [com.wssyncmldm.XDMService(155/onStartCommand)] 
I/LibraryLoader( 2909): Expected native library version number "",actual native library version number ""
I/chromium( 2909): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/DBG_DM  ( 2831): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
W/ContextImpl( 2831): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
I/Telecom ( 1446): InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
E/UpdateRequestReceiver( 2929): ignoring update request
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/comdaemonstockapp( 1287): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1287): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,E/Zygote  ( 2953): MountEmulatedStorage(),
E/Zygote  ( 2953): v2
I/libpersona( 2953): KNOX_SDCARD checking this for 10012
I/libpersona( 2953): KNOX_SDCARD not a persona
I/SELinux ( 2953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=2953 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/SELinux ( 2953): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/BrowserStartupController( 2909): Initializing chromium process, singleProcess=true
,W/art     ( 2909): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2909): ApplicationContext is null in ApplicationStatus
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2831): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,D/TimaKeyStoreProvider( 2953): TimaSignature is unavailable
,D/ActivityThread( 2953): Added TimaKeyStore provider
,E/Zygote  ( 2972): MountEmulatedStorage()
E/Zygote  ( 2972): v2,
E/UpdateRequestReceiver( 2929): ignoring update request
I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=2972 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/libpersona( 2972): KNOX_SDCARD checking this for 10003
I/libpersona( 2972): KNOX_SDCARD not a persona
I/SELinux ( 2972): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/Telecom ( 1446): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,I/SELinux ( 2972): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/Telecom ( 1446): InCallController: Unbinding from InCallService unbind
,E/SELinux ( 2972): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 1956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,W/chromium( 2909): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,E/BluetoothHeadset( 2742): BTStateChangeCB is registed
,D/BluetoothHeadset( 2742): doBind(): CallingUid(myUserHandle) = 0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 2742): BluetoothHeadset service is binded
D/SecUISvc( 1956): Service started flags 0 startId 1
,D/SecUISvc( 1956): Thread created.
,E/UpdateRequestReceiver( 2929): ignoring update request
,D/BluetoothA2dp( 2742): doBind(): CallingUid(myUserHandle) = 0
W/ResourcesManager( 2953): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2953): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/chromium( 2909): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2909): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2909): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2909): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2909): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2909): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2909): Local Branch: 
I/Adreno-EGL( 2909): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2909): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2909):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/DIAGMON_AGENT( 2866): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,E/Zygote  ( 2988): MountEmulatedStorage()
E/Zygote  ( 2988): v2
I/libpersona( 2988): KNOX_SDCARD checking this for 10028
I/libpersona( 2988): KNOX_SDCARD not a persona
I/SELinux ( 2988): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/DIAGMON_AGENT( 2866): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/MultiDex( 2953): VM with version 2.1.0 has multidex support
I/MultiDex( 2953): install
I/MultiDex( 2953): VM has multidex support, MultiDex support library is disabled.
,I/SELinux ( 2988): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,I/DIAGMON_AGENT( 2866): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
I/DIAGMON_AGENT( 2866): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2866): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 2866): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/SELinux ( 2988): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2988 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,I/DBG_DM  ( 2831): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
,D/TimaKeyStoreProvider( 2988): TimaSignature is unavailable
,D/ActivityThread( 2988): Added TimaKeyStore provider
I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/8)
D/TimaKeyStoreProvider( 2972): TimaSignature is unavailable
D/ActivityThread( 2972): Added TimaKeyStore provider
E/UpdateRequestReceiver( 2929): ignoring update request
,D/BluetoothAdapter( 2742): 709575952: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 2742): 709575952: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 2742): 709575952: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 2742): 709575952: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 2742): 709575952: getState() :  mService = null. Returning STATE_OFF
,V/JNIHelp ( 2953): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/AlarmManager( 1017): waitForAlarm result :4
,E/UpdateRequestReceiver( 2929): ignoring update request
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/BluetoothAdapter( 2909): 174764612: getState() :  mService = null. Returning STATE_OFF
,E/Zygote  ( 3025): MountEmulatedStorage(),
E/Zygote  ( 3025): v2
I/libpersona( 3025): KNOX_SDCARD checking this for 10094
I/libpersona( 3025): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3025 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 1683:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31,
,I/SELinux ( 3025): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 3025): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3025): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 3033): MountEmulatedStorage(),
I/libpersona( 3033): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3033): v2
I/libpersona( 3033): KNOX_SDCARD not a persona
I/SELinux ( 3033): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/ActivityThread( 2953): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2953): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a0af035: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/DBG_DM  ( 2831): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
I/ProviderInstaller( 2953): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 3033): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3033 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3033): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/audio_hw_primary(  283): adev_get_parameters: enter: keys - call_forwarding
,D/audio_hw_extn(  283): audio_extn_get_parameters: returns 
V/msm8974_platform(  283): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  283): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  283): key: 'call_forwarding' value: ''
,V/InCall  ( 1967): ProximitySensor -  - screenonImmediately: false
,V/InCall  ( 1967): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1967): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/ScoverManager( 1967): serviceVersion : 16908288
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1967): InCallUtils - isCoverClosed false
,I/Telecom ( 1446): ProximitySensorManager: Proximity wake lock already released
D/TimaKeyStoreProvider( 3033): TimaSignature is unavailable
D/TimaKeyStoreProvider( 3025): TimaSignature is unavailable
,D/ActivityThread( 3025): Added TimaKeyStore provider
D/ActivityThread( 3033): Added TimaKeyStore provider
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1967): InCallUtils - isCoverClosed false
I/InCall  ( 1967): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1967): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1967): InCallPresenter -  - dismissCoverDialog()...
,D/UserAnalysis.PlaceProvider( 2972): PlaceProvider onCreate()
,I/DBG_DM  ( 2831): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 2831): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
I/ActivityManager( 1017): Killing 1549:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/DBG_DM  ( 2831): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/UserAnalysis.SecureDbManager( 2972): Key for secure DB is newly created
,I/InCall  ( 1967): CallSContextMotion - stopPutDownListening
,D/UserAnalysis.SecurePlaceDbHelper( 2972): SecurePlaceDbHelper() 
D/UserAnalysis( 2972): Create SecureDbHelper
D/InCall  ( 1967): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,I/ActivityManager( 1017): Killing 2087:com.vlingo.midas/u0a31 (adj 15): empty #31
,D/PhoneStatusBarView( 1176): setCallBackground:0
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1967): InCallUtils - isCoverClosed false
,D/IntelligenceServiceApplication( 2972): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 2972): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3058): MountEmulatedStorage()
,E/Zygote  ( 3058): v2
I/libpersona( 3058): KNOX_SDCARD checking this for 10060
I/libpersona( 3058): KNOX_SDCARD not a persona
,I/SELinux ( 3058): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3058 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/VideoCallManager( 1967): Instantiating VideoCallManager
,I/ActivityManager( 1017): Killing 2116:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,I/SELinux ( 3058): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3058): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 1967): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1967): took 2.374219ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1967): took 5.431146ms for 0*0 texture 0
,I/GFX raster( 1967): took 11.672032ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1967): Bitmap=0xb7982080 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7981950 counterpartCT=4 counterpartW=176 counterparth=144
,I/art     (  304): Explicit concurrent mark sweep GC freed 8738(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 21.300ms
,E/        ( 1967): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1967): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1967): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1967): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1967): Local Branch: 
I/Adreno-EGL( 1967): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1967): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1967):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/libprocessgroup( 1017): failed to open /acct/uid_10138/pid_1683/cgroup.procs: No such file or directory
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 17.822ms
,I/GFX GPU raster( 1967): eglCreateImageKHR: EGL_SUCCESS
,D/TimaKeyStoreProvider( 3058): TimaSignature is unavailable
,D/ActivityThread( 3058): Added TimaKeyStore provider
,I/glCompressedTexImage2D( 1967): took 0.394219ms for 320*61440 texture 37809
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 668us total 19.655ms
,I/draw setup( 1967): took 11.277344ms for 320*240 texture 37809
E/GFX GPU raster( 1967): drawn
,W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_1549/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10031/pid_2087/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10050/pid_2116/cgroup.procs: No such file or directory
I/GFX GPU raster ASTC( 1967): took 41.622968ms for 320*240 texture 12
I/GFX raster( 1967): took 41.687759ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1967): Bitmap=0xb7982000 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb7981b68 counterpartCT=4 counterpartW=320 counterparth=240
,E/        ( 1967): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1967): eglCreateImageKHR: EGL_SUCCESS,
,I/glCompressedTexImage2D( 1967): took 0.289636ms for 480*122880 texture 37813
I/draw setup( 1967): took 0.721823ms for 480*640 texture 37813
E/GFX GPU raster( 1967): drawn
,I/GFX GPU raster ASTC( 1967): took 6.550313ms for 480*640 texture 12
I/GFX raster( 1967): took 6.631719ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1967): Bitmap=0xb7981b68 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7baf218 counterpartCT=4 counterpartW=480 counterparth=640
,D/elm:15183( 3025): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 3025): ELMEngine.ELMEngine( context ).
,D/elm:15183( 3025): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 3025): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15183( 3025): ElmAgentService : onCreate()
,D/elm:15183( 3025): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 3025): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:15183( 3025): BootCompletedState : startBootCompleted() call
V/EmergencyMode( 1431): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,D/elm:15183( 3025): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15183( 3025): Get License : 0
D/elm:15183( 3025): ElmAgentService : onDestroy().
,I/ActivityManager( 1017): Killing 2131:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,E/        ( 1967): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1967): eglCreateImageKHR: EGL_SUCCESS,
I/glCompressedTexImage2D( 1967): took 0.310469ms for 440*116864 texture 37809
I/draw setup( 1967): took 0.808958ms for 440*330 texture 37809,
E/GFX GPU raster( 1967): drawn
,I/GFX GPU raster ASTC( 1967): took 4.787605ms for 440*330 texture 12
I/GFX raster( 1967): took 4.871823ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1967): Bitmap=0xb7bb3470 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb7bb3830 counterpartCT=4 counterpartW=440 counterparth=330
,D/IntelligenceServiceApplication( 2972): no applications having user consent for prediction
,E/Tethering( 1017): No numeric data
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 27
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/sCloudBackupApp( 3058): sCloudBackupApp Version Info : 4.04.8.KK_APP
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 1967): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1967): eglCreateImageKHR: EGL_SUCCESS
E/Zygote  ( 3081): MountEmulatedStorage()
I/libpersona( 3081): KNOX_SDCARD checking this for 10062
E/Zygote  ( 3081): v2
I/libpersona( 3081): KNOX_SDCARD not a persona
I/SELinux ( 3081): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/glCompressedTexImage2D( 1967): took 0.417656ms for 480*163840 texture 37811
I/draw setup( 1967): took 0.985469ms for 480*640 texture 37811
E/GFX GPU raster( 1967): drawn
,I/SELinux ( 3081): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3081 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 3081): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 1510:com.android.printspooler/u0a136 (adj 15): empty #31
I/GFX GPU raster ASTC( 1967): took 8.969375ms for 480*640 texture 12
,I/GFX raster( 1967): took 9.029584ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1967): Bitmap=0xb7bf2e40 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7baefd0 counterpartCT=4 counterpartW=480 counterparth=640
,D/TimaKeyStoreProvider( 3081): TimaSignature is unavailable
D/ActivityThread( 3081): Added TimaKeyStore provider
,W/art     ( 2909): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup( 1017): failed to open /acct/uid_10113/pid_2131/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10136/pid_1510/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 3033): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,W/AwContents( 2909): onDetachedFromWindow called when already detached. Ignoring
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/PhoneWindow( 2909): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 2909): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 2909): CordovaWebView is running on device made by: samsung
E/Zygote  ( 3104): MountEmulatedStorage()
E/Zygote  ( 3104): v2
I/libpersona( 3104): KNOX_SDCARD checking this for 10009
I/libpersona( 3104): KNOX_SDCARD not a persona
I/SELinux ( 3104): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/DBG_POLICYDM( 3033): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/SELinux ( 3104): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3104): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3104 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_POLICYDM( 3033): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 2972): [PlaceDetection::stopService] Service stopped.
I/DBG_POLICYDM( 3033): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,W/art     ( 2909): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2909): Attempt to remove local handle scope entry from IRT, ignoring
,E/        ( 1967): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1967): took 2.258385ms for 0*0 texture 0
,I/DBG_POLICYDM( 3033): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/GFX generate_partition_tables( 1967): took 7.372083ms for 0*0 texture 0
D/TimaKeyStoreProvider( 3104): TimaSignature is unavailable
,D/ActivityThread( 3104): Added TimaKeyStore provider
D/[SBeam] ( 1298): SBeamEnabler.isSBeamSupported : [-1]
I/GFX raster( 1967): took 11.665364ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1967): Bitmap=0xb7bb33f0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7baca30 counterpartCT=4 counterpartW=176 counterparth=144
,I/DBG_POLICYDM( 3033): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/ActivityManager( 1017): Killing 1723:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,I/DBG_POLICYDM( 3033): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 3033): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 3033): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 3033): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,I/DBG_POLICYDM( 3033): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,D/[SBeam] ( 1298): SBeamEnabler.isSBeamSupported : EXIST
,I/DBG_POLICYDM( 3033): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3033): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
I/DBG_POLICYDM( 3033): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3033): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3033): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,E/        ( 1967): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,E/Tethering( 1017): No numeric data
,I/GFX construct_block_size_descriptor_2d second part( 1967): took 2.079948ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1967): took 6.095313ms for 0*0 texture 0
,I/GFX raster( 1967): took 10.238229ms for 176*144 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1967): Bitmap=0xb7baca98 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7bacc20 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1967): registerListener
D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1017): registerListenerCallback : binder = android.os.BinderProxy@13d47e83, pid : 1967, uid : 1001, type : 1
,W/libprocessgroup( 1017): failed to open /acct/uid_10015/pid_1723/cgroup.procs: No such file or directory
V/PlaceDetection v1.0.19 ( 2972): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/UserAnalysis.MyPlaceDbPreference( 2972): Constructor Preference
I/ExternalOEMControlProvider( 3081): onCreate
E/Tethering( 1017): No numeric data
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3126): MountEmulatedStorage(),
E/Zygote  ( 3126): v2
,I/libpersona( 3126): KNOX_SDCARD checking this for 1000
I/libpersona( 3126): KNOX_SDCARD not a persona
I/SELinux ( 3126): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3126): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3126 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2269:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
E/SELinux ( 3126): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InCall  ( 1967): InCallPresenter -  - Finished InCallPresenter.setUp
,D/TimaKeyStoreProvider( 3126): TimaSignature is unavailable
,D/ActivityThread( 3126): Added TimaKeyStore provider
,W/ResourcesManager( 3126): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/OpenGLRenderer( 2909): Render dirty regions requested: true
,I/ServiceMode( 3126): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3126): setReferenceIsDumpState : 0
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/chromium( 2909): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/PhoneWindow( 2909): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 2909): *FMB* isFloatingMenuEnabled return false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3149): MountEmulatedStorage()
E/Zygote  ( 3149): v2
I/libpersona( 3149): KNOX_SDCARD checking this for 1000
I/libpersona( 3149): KNOX_SDCARD not a persona
,I/SELinux ( 3149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3149): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3149 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2308:com.sec.android.omc/1000 (adj 15): empty #31
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2269/cgroup.procs: No such file or directory
,D/InputDispatcher( 1017): Focus entered window: 2909
,D/SRIB_DCS( 2909): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 2909): Initialized EGL, version 1.4
,D/TimaKeyStoreProvider( 3149): TimaSignature is unavailable
,D/ActivityThread( 3149): Added TimaKeyStore provider
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/DBG_POLICYDM( 3033): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/OpenGLRenderer( 2909): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2909): Enabling debug mode 0
,I/DBG_POLICYDM( 3033): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 19038(982KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.594ms total 149.281ms
,I/DBG_POLICYDM( 3033): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 3033): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3033): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3033): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/SettingsProvider( 1017): name = PREVIOUS_SYS_TIME
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10062
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/ActivityManager( 1017): Waited long enough for: ServiceRecord{1cb05120 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1176): There is/are notification(s) 
,D/Finsky  ( 2988): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager( 1017): Displayed Component not be shown by security: +1s570ms
,I/Timeline( 2909): Timeline: Activity_idle id: android.os.BinderProxy@12e9386 time:33568
D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{18de7629 u0 com.example.hello/.MainActivity t228} time:33570
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/SamsungIME( 1777): getCurrentCandidateView
,D/NPS_WSSNPS( 3149): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3149): [] Service onCreate!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3176): MountEmulatedStorage()
I/libpersona( 3176): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3176): v2
I/libpersona( 3176): KNOX_SDCARD not a persona
,I/SELinux ( 3176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3176 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3176): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 2324:com.sec.modem.settings/1000 (adj 15): empty #31
,D/SamsungIME( 1777): Dismiss ExpandCandiate
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1017): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10062
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/DBG_POLICYDM( 3033): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3033): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2308/cgroup.procs: No such file or directory
,E/Zygote  ( 3188): MountEmulatedStorage()
E/Zygote  ( 3188): v2,
,I/libpersona( 3188): KNOX_SDCARD checking this for 1000
I/libpersona( 3188): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3188 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2354:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 2335:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #32
,D/NPS_WSSNPS( 3149): [50.150321] NpsServiceTask Start
,D/TimaKeyStoreProvider( 3176): TimaSignature is unavailable
,D/ActivityThread( 3176): Added TimaKeyStore provider
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,W/NotificationAccessSettings( 1298): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,W/ResourcesManager( 1298): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/NPS_WSSNPS( 3149): [50.150321] smlDBHelper
,W/art     ( 2988): Verification of android.content.Intent com.google.android.finsky.utils.NotificationManager.createDefaultClickIntent(android.content.Context, java.lang.String, java.lang.String, java.lang.String, java.lang.String) took 112.825ms
,I/SurfaceFlinger(  257): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
,I/DBG_DM  ( 2831): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2324/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2354/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10131/pid_2335/cgroup.procs: No such file or directory
,D/SettingsProvider( 1017): name = access_control_enabled
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 3188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/DBG_POLICYDM( 3033): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,I/SELinux ( 3188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3188): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/DBG_POLICYDM( 3033): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,E/Zygote  ( 3212): MountEmulatedStorage(),
E/Zygote  ( 3212): v2
I/libpersona( 3212): KNOX_SDCARD checking this for 10069
I/libpersona( 3212): KNOX_SDCARD not a persona
,I/SELinux ( 3212): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3212 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,I/SELinux ( 3212): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3212): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SamsungIME( 1777): getDebugLevel  : 0x4f4c
,D/ScoverManager( 1298): serviceVersion : 16908288
,I/ActivityManager( 1017): Killing 2407:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,W/BindingManager( 2909): Cannot call determinedVisibility() - never saw a connection for the pid: 2909
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/TimaKeyStoreProvider( 3188): TimaSignature is unavailable
,D/ActivityThread( 3188): Added TimaKeyStore provider
,I/NPS_WSSNPS( 3149): [50.150321] AsyncBulkFlagCheck
,I/NPS_WSSNPS( 3149): [50.150321] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3149): [50.150321] IsRemain_Asyncing nothing
,W/ContextImpl( 3149): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 3212): TimaSignature is unavailable
,D/ActivityThread( 3212): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3149): [50.150321] Service onDestroy
,I/NPS_WSSNPS( 3149): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3149): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 3149): [50.150321] smlBREmailDelete
,I/NPS_WSSNPS( 3149): [50.150321] smlBRNetworkDelete
D/Finsky  ( 2988): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/NPS_WSSNPS( 3149): [50.150321] smlBRCallLogDelete
,I/NPS_WSSNPS( 3149): [50.150321] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3149): [50.150321] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3149): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 3149): [50.150321] cpuBooster release : false
,I/chromium( 2909): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/SMD     (  288): DCD OFF
,D/NPS_WSSNPS( 3149): [50.150321] dsServerSocket close
,I/ActivityManager( 1017): Killing 2425:com.wsomacp/u0a25 (adj 15): empty #31
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 28
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/DBG_FMMDM( 3188): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,D/FileShare-Server( 3212): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/DBG_FMMDM( 3188): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3188): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3188): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3240): MountEmulatedStorage()
E/Zygote  ( 3240): v2
I/libpersona( 3240): KNOX_SDCARD checking this for 1000
I/libpersona( 3240): KNOX_SDCARD not a persona
,I/SELinux ( 3240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3240 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SamsungIME( 1777): getDebugLevel  : 0x4f4c
,E/SELinux ( 3240): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/LockPatternUtils( 1298): isSmartCardAuthenticationAvailable: false
,D/TimaKeyStoreProvider( 3240): TimaSignature is unavailable
,D/ActivityThread( 3240): Added TimaKeyStore provider
,I/SamsungIME( 1777): KeybaordView init() : load resources
,D/Settings_Utils( 1298): isSupportVNFestival SM-A500FU XEO
,W/libprocessgroup( 1017): failed to open /acct/uid_10044/pid_2407/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10025/pid_2425/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_LOG( 3240): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3240): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3240): new DMDBOpenHelper instance
,W/Settings( 2988): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2988): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PCWCLIENTTRACE_DMContentProvider( 3240): [URIMatcher] - result : 2
,D/Volley  ( 2988): [388] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 2988): [381] DiskBasedCache.clear: Cache cleared.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_FMMDM( 3188): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3188): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3188): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3260): MountEmulatedStorage()
E/Zygote  ( 3260): v2
I/libpersona( 3260): KNOX_SDCARD checking this for 1000
I/libpersona( 3260): KNOX_SDCARD not a persona
,I/SELinux ( 3260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3260 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3260): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2490:com.sec.android.app.camera/u0a139 (adj 15): empty #31
I/ActivityManager( 1017): Killing 2457:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #32
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/SamsungIME( 1777): getCurrentKeyboard
I/SamsungIME( 1777): getTextKeyboard
,V/GLSUser ( 1702): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/JsMessageQueue( 2909): Set native->JS mode to OnlineEventsBridgeMode
,D/TimaKeyStoreProvider( 3260): TimaSignature is unavailable
,D/ActivityThread( 3260): Added TimaKeyStore provider
,V/EmergencyMode( 1431): [EmergencyBase] setBootTime
V/EmergencyMode( 1431): [EmergencyFactory] No Recovery State, kill my self.
,D/Finsky  ( 2988): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2988): [1] 2.run: Finished loading 1 libraries.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SamsungIME( 1777): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/Zygote  ( 3278): MountEmulatedStorage()
E/Zygote  ( 3278): v2
I/libpersona( 3278): KNOX_SDCARD checking this for 1000
I/libpersona( 3278): KNOX_SDCARD not a persona
,I/SELinux ( 3278): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3278): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/AndroidProtocolHandler( 2909): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/SELinux ( 3278): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3278 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/NotificationStore( 1702): System rebooted after Notification storage file was last written
I/NotificationStore( 1702): Deleting the file
,V/GmsCoreStatsServiceLauncher( 1882): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10142/pid_2457/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10139/pid_2490/cgroup.procs: No such file or directory
,I/DBG_FMMDS( 3260): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3260): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,D/TimaKeyStoreProvider( 3278): TimaSignature is unavailable
,D/ActivityThread( 3278): Added TimaKeyStore provider
,D/PersistentNotificationBroadcastReceiver( 1702): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/PCWCLIENTTRACE_DMContentProvider( 3240): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3260): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/CameraApp( 3278): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3278): Feature.Feature(context)
I/testFeature( 3278): Feature.readInternalDefaultXml()
I/testFeature( 3278): ResetFeatureValue
,I/CameraFirmware_broadcast( 3278): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3278): CameraApp.getAppFeature()...
,I/DBG_FMMDS( 3260): [50.18.150420][Line:43][xdbDBInit] 
,D/Finsky  ( 2988): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
V/VibratorService( 1017): hasVibrator - useVibetonz: true
,E/Zygote  ( 3297): MountEmulatedStorage()
E/Zygote  ( 3297): v2
I/libpersona( 3297): KNOX_SDCARD checking this for 10100
I/libpersona( 3297): KNOX_SDCARD not a persona
,I/SELinux ( 3297): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3297): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3297 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/SELinux ( 3297): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     (  304): Explicit concurrent mark sweep GC freed 8791(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 20.869ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 18.950ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 18.777ms
,D/TimaKeyStoreProvider( 3297): TimaSignature is unavailable
D/ActivityThread( 3297): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/jxcore_app_log( 2909): JniHelper::setJavaVM(0xb75dd450), pthread_self() = -1212918752
D/JX-Cordova( 2909): jxcore cordova android initializing
,D/Finsky  ( 2988): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageIntentReceiver( 3297): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3297): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,I/ActivityManager( 1017): Killing 2260:com.sec.android.app.mt/1000 (adj 15): empty #31
,I/DBG_FMMDS( 3260): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,I/DBG_FMMDS( 3260): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3260): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,I/DBG_FMMDS( 3260): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3260): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3260): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3260): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 2909): Initializing JXcore engine,
W/jxcore-log( 2909): JXcore engine is ready
E/Zygote  ( 3324): MountEmulatedStorage(),
E/Zygote  ( 3324): v2
I/libpersona( 3324): KNOX_SDCARD checking this for 1000
I/libpersona( 3324): KNOX_SDCARD not a persona
I/SELinux ( 3324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/jxcore-log( 2909): Starting JXcore engine,
I/SELinux ( 3324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3324): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3324 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 2561:com.samsung.android.securitylogagent/1000 (adj 15): empty #31,
,I/GoogleHttpClient( 1702): GMS http client unavailable, use old client
,D/TimaKeyStoreProvider( 3324): TimaSignature is unavailable
,D/ActivityThread( 3324): Added TimaKeyStore provider
,I/DBG_DM  ( 2831): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,E/audit   ( 1938): type=1400 msg=audit(1447834330.968:203): avc:  denied  { ioctl } for  pid=2909 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3080 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1938):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1938): type=1300 msg=audit(1447834330.968:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=bed52d58 items=0 ppid=304 ppcomm=main pid=2909 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1938): type=1320 msg=audit(1447834330.968:203): 
,I/FOTA_Client( 3104): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/ActivityManager( 1017): Killing 2541:com.android.calendar/u0a135 (adj 15): empty #31
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1017): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2260/cgroup.procs: No such file or directory
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3343): MountEmulatedStorage()
E/Zygote  ( 3343): v2
I/libpersona( 3343): KNOX_SDCARD checking this for 1000
I/libpersona( 3343): KNOX_SDCARD not a persona
,I/SELinux ( 3343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3343 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3343): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 3343): TimaSignature is unavailable
,D/ActivityThread( 3343): Added TimaKeyStore provider
,W/FOTA_Client( 3104): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3359): MountEmulatedStorage()
E/Zygote  ( 3359): v2
I/libpersona( 3359): KNOX_SDCARD checking this for 10014
I/libpersona( 3359): KNOX_SDCARD not a persona
,I/SELinux ( 3359): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3359): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3359): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3359 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2614:com.android.keychain/1000 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 2670:flipboard.boxer.app/u0a99 (adj 15): empty #31
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 29
,I/art     ( 1882): Background partial concurrent mark sweep GC freed 6221(698KB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 10MB/16MB, paused 1.195ms total 141.141ms
,D/FileApkUtils( 1882): Spent 156ms computing apk sha1.
,D/FileApkUtils( 1882): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1882): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2561/cgroup.procs: No such file or directory
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/DexOptUtils( 1882): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 1882): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 1882): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1882): Primary ABI of odexing process is armeabi-v7a
,W/jxcore-log( 2909): Platform android
W/jxcore-log( 2909): 
,W/jxcore-log( 2909): Process ARCH arm
W/jxcore-log( 2909): 
,D/TimaKeyStoreProvider( 3359): TimaSignature is unavailable
,I/LockPatternUtils( 1298): isSmartCardAuthenticationAvailable: false
,D/ActivityThread( 3359): Added TimaKeyStore provider
,W/InstanceID/Rpc( 1882): Found 10012
,I/jxcore-log( 2909): JXcore Cordova bridge is ready!
I/jxcore-log( 2909): 
,W/jxcore-log( 2909): JXcore engine is started
,I/dex2oat ( 3376): ----------------------------------------------------
I/dex2oat ( 3376): <SS>: S T A R T I N G . . .
I/dex2oat ( 3376): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 3376): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=39 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
V/Finsky  ( 2988): [1] GearheadStateMonitor.onReady: sIsProjecting:false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3380): MountEmulatedStorage()
E/Zygote  ( 3380): v2
I/libpersona( 3380): KNOX_SDCARD checking this for 1000
I/libpersona( 3380): KNOX_SDCARD not a persona
,I/SELinux ( 3380): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3380): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3380 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2188:flipboard.app/u0a98 (adj 15): empty #31
,E/SELinux ( 3380): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/jxcore-log( 2909): >> samsung-SM-A500FU
E/jxcore-log( 2909): 
,I/jxcore-log( 2909): Total memory 1983787008
I/jxcore-log( 2909): 
,I/jxcore-log( 2909): Free memory 111558656
I/jxcore-log( 2909): 
I/jxcore-log( 2909): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2909): 
I/FactoryTestApp( 2578): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2938)  
,I/jxcore-log( 2909): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2909): 
,D/TimaKeyStoreProvider( 3380): TimaSignature is unavailable
,D/ActivityThread( 3380): Added TimaKeyStore provider
,I/jxcore-log( 2909): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2909): 
,I/jxcore-log( 2909): Size 720 1280
I/jxcore-log( 2909): 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,I/jxcore-log( 2909): Screen Brightness 5
I/jxcore-log( 2909): 
,E/jxcore-log( 2909): Dummy Error Log.
E/jxcore-log( 2909): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 2702:com.sec.usbsettings/1000 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_2541/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2614/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10099/pid_2670/cgroup.procs: No such file or directory
,V/OneTimeInitializerReceiver( 3359): OneTimeInitializerReceiver.onReceive
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,W/ContextImpl( 3343): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/OneTimeService( 3359): OneTimeService.onHandleIntent
,E/Zygote  ( 3400): MountEmulatedStorage()
,E/Zygote  ( 3400): v2,
I/libpersona( 3400): KNOX_SDCARD checking this for 10015
I/libpersona( 3400): KNOX_SDCARD not a persona
,I/SELinux ( 3400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3400 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 3400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3400): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3400): TimaSignature is unavailable
,D/ActivityThread( 3400): Added TimaKeyStore provider
,I/ActivityManager( 1017): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3420 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 2291:com.android.mms/u0a46 (adj 15): empty #31
,E/Zygote  ( 3420): MountEmulatedStorage()
E/Zygote  ( 3420): v2
I/libpersona( 3420): KNOX_SDCARD checking this for 1000
I/libpersona( 3420): KNOX_SDCARD not a persona
,I/SELinux ( 3420): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3420): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3420): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 3420): TimaSignature is unavailable
,D/ActivityThread( 3420): Added TimaKeyStore provider
,D/KnoxSetupWizardDbHelper( 3380): dbMigrationFlag : false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,D/CountryDetector( 1017): No listener is left
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ShortcutReceiver( 3380):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,D/GCM     ( 1882): COMPAT: Multi user not supported
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,D/KnoxShortcutUtil( 3380): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3380):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 3380):  shortcut migration not required 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/GCM     ( 1702): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1017): failed to open /acct/uid_10098/pid_2188/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2702/cgroup.procs: No such file or directory
,E/Zygote  ( 3438): MountEmulatedStorage()
,E/Zygote  ( 3438): v2
I/libpersona( 3438): KNOX_SDCARD checking this for 1000
I/libpersona( 3438): KNOX_SDCARD not a persona,
I/SELinux ( 3438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3438 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
W/libprocessgroup( 1017): failed to open /acct/uid_10046/pid_2291/cgroup.procs: No such file or directory
I/SELinux ( 3438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ResourcesManager( 3420): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3438): TimaSignature is unavailable
,D/ActivityThread( 3438): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,W/ContextImpl( 1298): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,W/ContextImpl( 1298): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/ActivityManager( 1017): Killing 2763:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,I/SettingSearch/SearchIntentReceiver( 1298): InitSerachDBThread thread end!
,I/CheckinService( 1882): Disabling old GoogleServicesFramework version
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4180, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1431): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1431): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1176): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1176): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,E/KnoxSetupWizardClient( 3438): isShipMode : 1
I/KnoxSetupWizardClient( 3438): onReceive : android.intent.action.BOOT_COMPLETED
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/TimaService( 1017): TIMA: in getTimaVersion
,D/TimaService( 1017): TIMA3: KeyStore3_init
,D/TimaService( 1017): TIMA: in getTimaVersion
E/TLC_TZ_KEYSTORE: ( 1017): Inside TZ_KEYSTORE_initialize()
I/TLC_TZ_KEYSTORE: ( 1017): creating new keystore context...
I/TLC_TZ_KEYSTORE: ( 1017): initializing ccm context...
,I/TLC_TZ_KEYSTORE: ( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1017): process = tima_key, process_strlen = 8
,I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1017): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3469): MountEmulatedStorage()
E/Zygote  ( 3469): v2
I/libpersona( 3469): KNOX_SDCARD checking this for 1000
I/libpersona( 3469): KNOX_SDCARD not a persona
,I/SELinux ( 3469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3469 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 1570:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 8
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1017): ctx = 0xb7ef4cf0, comm = 0xb7de8c48, sendmsg = 0xa17e6000, recvmsg = 0xa17e6440
I/TZ_init: ( 1017): TZ_init: sending initialization request...
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,E/TZ_init: ( 1017): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1017): trustlet initialization failed
I/TZ_init: ( 1017): TZ_init_START...
,I/TZ_init: ( 1017): TZ_init_with_data: sending initialization request...
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/TZ_init: ( 1017): TZ_init: successful initialization
D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 8
,E/TLC_TZ_KEYSTORE: ( 1017): Count : 1, Ret : 0
,I/jxcore-log( 2909): getBuffer is called!!!!
I/jxcore-log( 2909): 
,D/TimaKeyStoreProvider( 3469): TimaSignature is unavailable
,D/ActivityThread( 3469): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/art     ( 2692): Suspending all threads took: 6.947ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3487): MountEmulatedStorage(),
E/Zygote  ( 3487): v2
I/libpersona( 3487): KNOX_SDCARD checking this for 1000
I/libpersona( 3487): KNOX_SDCARD not a persona
,I/SELinux ( 3487): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3487): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3487): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3487 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/DBG_DM  ( 2831): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec,
,D/TimaKeyStoreProvider( 3487): TimaSignature is unavailable
,D/ActivityThread( 3487): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10048/pid_2763/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10072/pid_1570/cgroup.procs: No such file or directory
,I/GCoreUlr( 1882): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,E/USB_UICC(  297): Timeout! No signal received. Retry num = 30
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SystemUpdateService( 1882): onCreate
,I/GCoreUlr( 1655): DispatchingService.onCreate()
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/USB_UICC(  297): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  297): usb_uicc_init_qmi failed ! 
I/USB_UICC(  297): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  297): usb_uicc_cleanup, Issuing QMI deinit ... 
,W/ContextImpl( 3420): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 ,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 1882): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/System.err( 3438): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 3438): 	at android.os.Parcel.readException(Parcel.java:1544)
,W/System.err( 3438): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3438): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3438): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3438): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3438): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,I/CheckinService( 1882): Checking schedule, now: 1447834332395 next: 1448192721114
I/CheckinService( 1882): active receiver: disabled
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 25460(1395KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/39MB, paused 2.474ms total 197.731ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,I/SystemUpdateService( 1882): cancelUpdate (empty URL)
I/SystemUpdateService( 1882): active receiver: disabled
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Hs20UtilService( 3487): onCreate
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3343): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3343): Resource data:2131165186
,W/ResourcesManager( 3343): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,I/ConfigService( 1702): onCreate
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/ConfigFetchService( 1882): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3343): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3343): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3343): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3343): getResourceTypeNamexml
,I/ActivityManager( 1017): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3527 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 3527): MountEmulatedStorage()
E/Zygote  ( 3527): v2
I/libpersona( 3527): KNOX_SDCARD checking this for 1000
I/libpersona( 3527): KNOX_SDCARD not a persona
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/SELinux ( 3527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 3527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3527): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,I/ActivityManager( 1017): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3535 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0,
,E/Zygote  ( 3535): MountEmulatedStorage(),
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/Zygote  ( 3535): v2,
I/libpersona( 3535): KNOX_SDCARD checking this for 10019
I/libpersona( 3535): KNOX_SDCARD not a persona
D/StatusChecker( 3469): onReceive : android.intent.action.BOOT_COMPLETED,
,I/SELinux ( 3535): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3535): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3535): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3343): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509,
,V/AuthZen ( 1882): Handling intent: android.intent.action.BOOT_COMPLETED
,I/art     (  304): Explicit concurrent mark sweep GC freed 8799(375KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 11.121ms total 42.080ms
,I/StatusChecker( 3469): onReceive : net.mt.init : DONE
,I/AMMetaDataParserService( 3343): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/AuthZenEventHandler( 1882): Handling event: android.intent.action.BOOT_COMPLETED
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 598us total 17.056ms
,I/AMMetaDataParserService( 3343): Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 601us total 17.135ms
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
W/ContextImpl( 3343): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
I/Hs20UtilService( 3487): Starting #1
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Hs20UtilService( 3487): Message received 5003
D/TimaKeyStoreProvider( 3527): TimaSignature is unavailable
D/ActivityThread( 3527): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 3535): TimaSignature is unavailable
D/ActivityThread( 3535): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3565): MountEmulatedStorage()
,E/Zygote  ( 3565): v2
I/libpersona( 3565): KNOX_SDCARD checking this for 10116
I/libpersona( 3565): KNOX_SDCARD not a persona
,I/SELinux ( 3565): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3565 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 2780:com.sec.dsm.system/1000 (adj 15): empty #31
,W/SEAMService( 1017):  hashset_to_int_array returning null
W/ResourcesManager( 3527): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/SELinux ( 3565): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3565): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ConfigFetchService( 1882): service connected
,I/RlzPingService( 3400): Setting next ping for 1448439132755
,W/BaseAppContext( 1882): Using Auth Proxy for data requests.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
I/AMMetaDataParserService( 3343): Resource data:2131034113
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3343): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3343): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3343): getResourceTypeNamexml
,W/SEAMService( 1017):  hashset_to_int_array returning null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SQLiteLog( 3420): (284) automatic index on seams_container_info(seams_container_id)
,E/SQLiteLog( 3420): (284) automatic index on seams_container_info(sp_id)
,D/TimaKeyStoreProvider( 3565): TimaSignature is unavailable
,D/ActivityThread( 3565): Added TimaKeyStore provider
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3343): took 2.182708ms for 0*0 texture 0
,I/dex2oat ( 3376): dex2oat took 1.591s (threads: 4)
,I/GLSUser ( 1882): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GFX generate_partition_tables( 3343): took 6.314688ms for 0*0 texture 0
,I/GFX raster( 3343): took 9.789949ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996e78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb79af3d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2780/cgroup.procs: No such file or directory
,D/DexOptUtils( 1882): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
D/DexOptUtils( 1882): Set odex to world readable.
,D/DexOptUtils( 1882): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
,D/FileApkUtils( 1882): Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
,I/art     ( 1655): Explicit concurrent mark sweep GC freed 12559(751KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 10MB/17MB, paused 2.694ms total 74.037ms
D/ChimeraCfgMgr( 1882): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/SEAMService( 1017):  hashset_to_int_array returning null
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,D/GmsModuleFndr( 1882): Beginning GMS chimera module scan
,I/ActivityManager( 1017): Killing 2809:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/GmsModuleFndr( 1882): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 1882): Beginning module configuration check
,E/Zygote  ( 3589): MountEmulatedStorage()
I/libpersona( 3589): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3589): v2
I/libpersona( 3589): KNOX_SDCARD not a persona
I/SELinux ( 3589): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/ChimeraCfgMgr( 1882): Module APKs unchanged, check complete
I/SELinux ( 3589): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3589): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3535): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Nov 18 09:12:12 GMT+01:00 2015
I/ActivityManager( 1017): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3589 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/F_PHONE ( 3527): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/GFX raster( 3343): took 0.888490ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996e78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb79b7500 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3343): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,I/KLMS-2.5.183: ( 3535): KLMSAbstractReciever(): onReceive().END.
,I/PageBuddyNotiSvc( 3565): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/KLMS-2.5.183: ( 3535): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3535): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/TimaKeyStoreProvider( 3589): TimaSignature is unavailable
,D/ActivityThread( 3589): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3535): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ContextImpl( 3565): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,I/GFX construct_block_size_descriptor_2d second part( 3343): took 2.326980ms for 0*0 texture 0
,W/ResourcesManager( 3589): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     ( 1702): Explicit concurrent mark sweep GC freed 23763(1359KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 10MB/16MB, paused 1.074ms total 53.846ms
I/libpersona( 3610): KNOX_SDCARD checking this for 10022
E/Zygote  ( 3610): MountEmulatedStorage()
I/libpersona( 3610): KNOX_SDCARD not a persona
E/Zygote  ( 3610): v2
I/SELinux ( 3610): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3610): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3610): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3610 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,I/GLSUser ( 1882): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/BluetoothBDAdrressReceiver( 3589): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3589): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,I/GFX generate_partition_tables( 3343): took 7.694531ms for 0*0 texture 0
,I/KLMS-2.5.183: ( 3535): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/GFX raster( 3343): took 11.094947ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b3c98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b3fb8 counterpartCT=4 counterpartW=96 counterparth=96
,W/SQLiteConnectionPool( 1702): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/F_PHONE ( 3527): [[com.sec.bcservice]] onServiceConnected()
I/AMMetaDataParserService( 3343): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/F_PHONE ( 3527): default registerAction()
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2809/cgroup.procs: No such file or directory
,I/F_PHONE ( 3527): [[com.sec.bcservice]] sendPendingMessage()
I/DBG_DM  ( 2831): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
I/KLMS-2.5.183: ( 3535): KLMSIntentService(): BOOT_COMPLETED
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,I/PageBuddyNotiSvc( 3565): onCreate mCpBitFlag=0
,D/TimaKeyStoreProvider( 3610): TimaSignature is unavailable
D/ActivityThread( 3610): Added TimaKeyStore provider
,W/ResourcesManager( 1470): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1470): onCreate()
,E/BluetoothBDTestService( 1470): onStart(), extra_type: BOOT_COMPLETED
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/BluetoothBDTestService( 1470): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1470): already exist!( /efs/bluetooth/bt_addr ), file length: 17
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3343): took 0.626250ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b3e00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79af4f0 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 3632): MountEmulatedStorage()
E/Zygote  ( 3632): v2
I/libpersona( 3632): KNOX_SDCARD checking this for 10125
I/libpersona( 3632): KNOX_SDCARD not a persona
,I/SELinux ( 3632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3632 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 3632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3632): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3343): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/GCoreUlr( 1655): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/KLMS-2.5.183: ( 3535): KLMSIntentService(): onDestroy()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SMD     (  288): DCD OFF
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.827344ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b6968 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b6c78 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 3645): MountEmulatedStorage()
E/Zygote  ( 3645): v2
I/libpersona( 3645): KNOX_SDCARD checking this for 1000
I/libpersona( 3645): KNOX_SDCARD not a persona
,I/SELinux ( 3645): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3343): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
I/SELinux ( 3645): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3645): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3632): TimaSignature is unavailable
,D/ActivityThread( 3632): Added TimaKeyStore provider
,I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3645 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2692:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.639428ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b2ac0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b2d80 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3645): TimaSignature is unavailable
,D/ActivityThread( 3645): Added TimaKeyStore provider
,W/ResourcesManager( 3632): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3632): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3632): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3343): took 0.696562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b39a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79af4f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/Zygote  ( 3666): MountEmulatedStorage()
E/Zygote  ( 3666): v2
I/libpersona( 3666): KNOX_SDCARD checking this for 1000
I/libpersona( 3666): KNOX_SDCARD not a persona
I/SELinux ( 3666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3666 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2849:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
I/SELinux ( 3666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3666): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/ChimeraCfgMgr( 1882): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AuthZen ( 1882): Fetching signing key...
,D/SystemUpdateService( 1882): onDestroy
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3666): TimaSignature is unavailable
,W/ResourcesManager( 3645): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread( 3666): Added TimaKeyStore provider
,E/Zygote  ( 3682): MountEmulatedStorage()
E/Zygote  ( 3682): v2
I/libpersona( 3682): KNOX_SDCARD checking this for 10104
I/libpersona( 3682): KNOX_SDCARD not a persona
I/SELinux ( 3682): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3682 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 3682): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,D/ConfigFetchService( 1882): ConfigApi connection successful.
E/SELinux ( 3682): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/FactoryTestApp( 2578): [DummyFtClient$onDestroy](2578) Destroy DummyFtClient service
,D/FactoryTestApp( 2578): [Support$Values.getString](2578) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2578): [ModuleCommon$isConnectionModeNone](2578) mConnectionMode = gsm
I/FactoryTestApp( 2578): [ModuleCommon$isRunningFtClient](2578) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2578): [DummyFtClient$onDestroy](2578) kill process
I/Process ( 2578): Sending signal. PID: 2578 SIG: 9
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/TimaKeyStoreProvider( 3682): TimaSignature is unavailable
,D/ActivityThread( 3682): Added TimaKeyStore provider
,E/MTPRx   ( 3666): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
D/SecContentProvider2( 1017): mCursor = null
I/Kids    ( 1882): [KidAccountFixer] No network connection
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1017): mCursor = null
,V/MTPRx   ( 3666): sealedState: false
V/MTPRx   ( 3666): sealedUsbMassStorageState: false
,D/SettingsProvider( 1017): name = mtp_usb_connection_status
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/AuthZen ( 1882): Signing key fetched successfully!
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 3682): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GFX raster( 3343): took 0.539270ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b40d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b4390 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Process com.sec.factory (pid 2578)(adj 0) has died(101,1082)
,D/SettingsProvider( 1017): name = media_player_mode
W/BaseAppContext( 1882): Using Auth Proxy for data requests.
,I/AMMetaDataParserService( 3343): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,D/QuickConnect( 3632): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 3632): Util.setSCRunningSetting - [value]0
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/AuthZen ( 1882): Starting Enrollment...
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
I/AMMetaDataParserService( 3343): Resource data:2131034113
,I/AMMetaDataParserService( 3343): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3343): getResourceTypeNamexml
D/SettingsProvider( 1017): name = scon_is_running
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10125
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.812709ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996e78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb79b2560 counterpartCT=4 counterpartW=96 counterparth=96
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,D/AuthZen ( 1882): getting auth token. Attempt 0
,I/AMMetaDataParserService( 3343): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,I/QuickConnect( 3632): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/GLSActivity( 1702): [ac] getting account id
,I/KnoxUsageLogPro( 3645): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/KnoxUsageLogPro( 3645): premStatus:2
,I/KnoxUsageLogPro( 3645): isEulaShown : false
I/KnoxUsageLogPro( 3645): KnoxUsageReceiver onReceive : not Processible, just return
D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_10150/pid_2849/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10085/pid_2692/cgroup.procs: No such file or directory
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/KnoxUsageLogPro( 3645): savePreference: key = previous_sys_time value = 1447834333354
I/ActivityManager( 1017): Killing 2866:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1702): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1702): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/QuickConnect( 3632): PeriphStartReceiver.onReceive - no need to start
,D/SettingsProvider( 1017): name = mtp_running_status
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = media_mount_count
,E/Zygote  ( 3700): MountEmulatedStorage()
,E/Zygote  ( 3700): v2
I/libpersona( 3700): KNOX_SDCARD checking this for 10131
I/libpersona( 3700): KNOX_SDCARD not a persona
,I/SELinux ( 3700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3700 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 3700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Killing 2888:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
E/SELinux ( 3700): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3700): TimaSignature is unavailable
,D/ActivityThread( 3700): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1702): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,W/ResourcesManager( 3700): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3700): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3700): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3700): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SettingsProvider( 1017): name = mtp_sync_alive
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,I/GLSUser ( 1702): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,I/GLSUser ( 1702): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1702): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1702): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1702): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1017): name = sdcard_launch
I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
D/PackageManager( 1017): [MSG] MCS_UNBIND
I/ActivityManager( 1017): Killing 2972:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
D/SBrowserFeatureFlag( 3700): initialized in static block : loadCscFeatureValue() succeed! 
,D/SettingsProvider( 1017): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
,D/ManifestProvider( 3700): onCreate()
,D/SettingsProvider( 1017): name = mtp_open_session
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2866/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2888/cgroup.procs: No such file or directory
,E/NetworkSettingsReceiver( 3700): onReceive: android.intent.action.BOOT_COMPLETED
,E/SBrowserFeatureFlag( 3700): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@a6ab244
,D/SBrowserFeatureFlag( 3700): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 3700): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/AuthZen ( 1882): Error getting auth token
E/AuthZen ( 1882): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 1882): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1882): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1882): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1882): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AuthZen ( 1882): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 1882): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1882): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1882): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1882): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1882): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/Zygote  ( 3722): MountEmulatedStorage(),
E/Zygote  ( 3722): v2
,I/libpersona( 3722): KNOX_SDCARD checking this for 10135
I/libpersona( 3722): KNOX_SDCARD not a persona
,I/SELinux ( 3722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SecKeyguardClockSingleView( 1176): Ignore. Because it is same clock text
E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/SELinux ( 3722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/GFX raster( 3343): took 0.851824ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996e78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb79b43c0 counterpartCT=4 counterpartW=96 counterparth=96
E/SELinux ( 3722): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3722 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2929:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/KnoxUsageLogPro( 3645): savePreference: key = previous_elapsed_time value = 37229
,I/AMMetaDataParserService( 3343): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/TimaKeyStoreProvider( 3722): TimaSignature is unavailable
,D/ActivityThread( 3722): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_PushUtil( 3240): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3240): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 3240): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3240): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3240): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3240): ACTION_BOOTUP - Push type: [SPP, GCM]
,W/ResourcesManager( 3722): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3722): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3722): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/PCWCLIENTTRACE_PCWHandler( 3240): [ensureRegistration] - netwrok is not available. action ignored
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3739): MountEmulatedStorage()
,E/Zygote  ( 3739): v2
I/libpersona( 3739): KNOX_SDCARD checking this for 10031
I/libpersona( 3739): KNOX_SDCARD not a persona,
D/a       ( 1882): Opening database auth.proximity.permit_store...
,I/SELinux ( 3739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3739 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
D/AuthZenTransactionCache( 1882): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1882): Clearing transaction cache
,I/ActivityManager( 1017): Killing 3033:com.policydm/1000 (adj 15): empty #31
,I/SELinux ( 3739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3739): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.624531ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b3c98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7997898 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/daemonapp( 1287): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar,
,D/TimaKeyStoreProvider( 3739): TimaSignature is unavailable
,D/ActivityThread( 3739): Added TimaKeyStore provider
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.612031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b3e00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b5b98 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1655): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/AMMetaDataParserService( 3343): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/libprocessgroup( 1017): failed to open /acct/uid_10003/pid_2972/cgroup.procs: No such file or directory
,I/GCoreUlr( 1655): Unbound from all location providers
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.919219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b6968 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b6c78 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3739): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/Zygote  ( 3760): MountEmulatedStorage()
I/AMMetaDataParserService( 3343): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
E/Zygote  ( 3760): v2
,I/libpersona( 3760): KNOX_SDCARD checking this for 10042
I/libpersona( 3760): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3760 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 3760): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3760): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3760): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
I/art     (  304): Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 23.992ms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3760): TimaSignature is unavailable
D/ActivityThread( 3760): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 608us total 18.649ms
W/libprocessgroup( 1017): failed to open /acct/uid_10086/pid_2929/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3033/cgroup.procs: No such file or directory
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.629531ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b2ac0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b7510 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 21.185ms
,I/AMMetaDataParserService( 3343): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/Zygote  ( 3776): MountEmulatedStorage()
E/Zygote  ( 3776): v2
I/libpersona( 3776): KNOX_SDCARD checking this for 10139
I/libpersona( 3776): KNOX_SDCARD not a persona
I/SELinux ( 3776): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3776): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3776 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
E/SELinux ( 3776): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3343): took 0.890104ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b39a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b4390 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3776): TimaSignature is unavailable
,D/ActivityThread( 3776): Added TimaKeyStore provider
I/AMMetaDataParserService( 3343): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ResourcesManager( 3760): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 3776): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 3776): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3776): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3776): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3776): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,I/DBG_DM  ( 2831): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,I/GCoreUlr( 1655): DispatchingService.onDestroy()
,I/GCoreUlr( 1655): Unbound from all location providers
,I/VlingoApplication( 3739): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,I/ActivityManager( 1017): Killing 3058:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,D/BluetoothAdapter( 3739): 161461989: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3739): 161461989: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3739): 161461989: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 3739): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3798): MountEmulatedStorage(),
E/Zygote  ( 3798): v2
I/libpersona( 3798): KNOX_SDCARD checking this for 10145
I/libpersona( 3798): KNOX_SDCARD not a persona
,I/SELinux ( 3798): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3798 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 3798): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/CalendarProvider2( 3760): CalendarProvider2.onCreate() called
E/SELinux ( 3798): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.533854ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b40d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b5a40 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3798): TimaSignature is unavailable
,D/ActivityThread( 3798): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3343): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/Babel_SMS( 3682): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 3682): MmsConfig.loadMmsSettings
,I/Babel_SMS( 3682): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 3682): MmsConfig.loadFromDatabase
,W/ResourcesManager( 3798): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3798): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3798): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3798): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3798): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3343): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3343): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3343): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
I/AMMetaDataParserService( 3343): Resource data:2131034112
,I/AMMetaDataParserService( 3343): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3343): getResourceTypeNamexml
E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.624011ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b3e00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b6430 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,E/Babel_SMS( 3682): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 3682): MmsConfig.loadFromResources
,E/Babel_SMS( 3682): canonicalizeMccMnc: invalid mccmnc nullnull
D/VlingoApplication( 3739): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
I/Babel_SMS( 3682): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
W/libprocessgroup( 1017): failed to open /acct/uid_10060/pid_3058/cgroup.procs: No such file or directory
D/VlingoApplication( 3739): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow( 3739): initQueue()
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 27598(1716KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 26MB/39MB, paused 2.309ms total 150.026ms
,D/SecurityLogAgent:SEDenialService( 1017): Got CLOSE_WRITE Event sk.log
,D/SecurityLogAgent:SEDenialService( 1017): Got CLOSE_WRITE Event sk.log
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.636198ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b3e00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79af7f8 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3821 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 3025:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,E/Zygote  ( 3821): MountEmulatedStorage()
E/Zygote  ( 3821): v2
I/libpersona( 3821): KNOX_SDCARD checking this for 10032
I/libpersona( 3821): KNOX_SDCARD not a persona
,I/SELinux ( 3821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3821): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3343): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  283): getCameraInfo: X
,D/TimaKeyStoreProvider( 3821): TimaSignature is unavailable
,D/ActivityThread( 3821): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/libprocessgroup( 1017): failed to open /acct/uid_10094/pid_3025/cgroup.procs: No such file or directory
,W/Settings( 3682): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 3682): startup - clean
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.642084ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b3928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb75e4158 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/Babel   ( 3682): deleted: false for 0
,E/Zygote  ( 3842): MountEmulatedStorage()
E/Zygote  ( 3842): v2
I/libpersona( 3842): KNOX_SDCARD checking this for 10033
I/libpersona( 3842): KNOX_SDCARD not a persona
,I/SELinux ( 3842): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3842): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3842 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3081:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
E/SELinux ( 3842): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3842): TimaSignature is unavailable
,D/ActivityThread( 3842): Added TimaKeyStore provider
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.641719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996830 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7996e78 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,W/libprocessgroup( 1017): failed to open /acct/uid_10062/pid_3081/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/VideoCapabilities( 3682): Unrecognized profile 2130706433 for video/avc
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/AudioCapabilities( 3682): Unsupported mime audio/evrc
,W/AudioCapabilities( 3682): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3682): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3682): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 3682): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3682): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3682): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3682): Unsupported mime audio/evrc,
,W/VideoCapabilities( 3682): Unsupported mime video/wvc1
,W/VideoCapabilities( 3682): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3682): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3682): Unsupported mime video/wvc1
,W/VideoCapabilities( 3682): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3682): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 3682): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3682): Unsupported mime video/mp43
,W/VideoCapabilities( 3682): Unsupported mime video/sorenson
,W/VideoCapabilities( 3682): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 3682): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 3682): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3682): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3682): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3682): Unrecognized profile 2130706433 for video/avc
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3861): MountEmulatedStorage(),
E/Zygote  ( 3861): v2
I/libpersona( 3861): KNOX_SDCARD checking this for 10072
I/libpersona( 3861): KNOX_SDCARD not a persona,
,I/SELinux ( 3861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=3861 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,E/SELinux ( 3861): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
I/AMMetaDataParserService( 3343): Resource data:2131034113
I/AMMetaDataParserService( 3343): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3343): getResourceTypeNamexml
E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3343): took 1.161146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb75e4158 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb79b2ac0 counterpartCT=4 counterpartW=96 counterparth=96
D/TimaKeyStoreProvider( 3861): TimaSignature is unavailable
W/ResourcesManager( 3842): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3842): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread( 3861): Added TimaKeyStore provider
W/ResourcesManager( 3842): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3343): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
I/GFX raster( 3343): took 1.003750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb75e4158 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7996e78 counterpartCT=4 counterpartW=96 counterparth=96
,I/vclib   ( 3682): onServiceConnected
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/Babel   ( 3682): Attempted to change video mute state without an active call.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3343): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ResourcesManager( 3842): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3842): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3842): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  ( 3883): MountEmulatedStorage(),
E/Zygote  ( 3883): v2
,D/BadgeProvider( 3861): onCreate
D/BadgeProvider( 3861): DatabaseHelper
,I/libpersona( 3883): KNOX_SDCARD checking this for 10035,
I/libpersona( 3883): KNOX_SDCARD not a persona
,I/SELinux ( 3883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=3883 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3883): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2053:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3842): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3842): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3842): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/BadgeProvider( 3861): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3903): MountEmulatedStorage(),
I/libpersona( 3903): KNOX_SDCARD checking this for 10146
E/Zygote  ( 3903): v2
,I/libpersona( 3903): KNOX_SDCARD not a persona
,I/SELinux ( 3903): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3903): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=3903 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 3883): TimaSignature is unavailable
D/ActivityThread( 3883): Added TimaKeyStore provider
I/ActivityManager( 1017): Killing 3149:com.wssnps/1000 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 3126:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #32
,E/SELinux ( 3903): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3343): took 0.605938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996f50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79783f0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 2831): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,D/Launcher.Model( 1493): reloadBadges entered.
,D/BadgeProvider( 3861): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 3861): sendNotify, [notify] : null
,D/BadgeProvider( 3861): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3861): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 3861): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 3903): TimaSignature is unavailable
,D/ActivityThread( 3903): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3343): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ResourcesManager( 3903): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_10012/pid_2053/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3126/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3149/cgroup.procs: No such file or directory
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.599635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b3e00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b2ac0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,I/AMMetaDataParserService( 3343): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/Process ( 3798): Sending signal. PID: 3798 SIG: 9
,I/ActivityManager( 1017): Killing 3176:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,I/ActivityManager( 1017): Process com.android.email (pid 3798)(adj 9) has died(51,1119)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3921): MountEmulatedStorage(),
I/libpersona( 3921): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 3921): v2
I/libpersona( 3921): KNOX_SDCARD not a persona,
I/SELinux ( 3921): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3921): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SPPClientService( 3883): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 3883): [PushClientApplication] Push log off : This is Ship build version
,E/SELinux ( 3921): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=3921 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/SPPClientService( 3883): [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
,E/SPPClientService( 3883): [SystemStateMoniter] Current Time : 39075
,I/System.out( 3739): INFO:Resource not found:/Common.properties Using default values
,D/SPPClientService( 3883): PushLog.txt file is not deleted.
,E/Zygote  ( 3932): MountEmulatedStorage()
,E/Zygote  ( 3932): v2
I/libpersona( 3932): KNOX_SDCARD checking this for 10145
I/libpersona( 3932): KNOX_SDCARD not a persona,
I/SELinux ( 3932): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/SPPClientService( 3883): PushLog.txt file is not deleted.,
,D/SPPClientService( 3883): ============PushLog. stop!
,I/ActivityManager( 1017): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=3932 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 3932): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3932): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3176/cgroup.procs: No such file or directory
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.945207ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996e78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79783f0 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3921): TimaSignature is unavailable
,D/ActivityThread( 3921): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3932): TimaSignature is unavailable
,D/ActivityThread( 3932): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 3188:com.fmm.dm/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3343): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3932): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3932): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3932): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3932): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3932): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.669219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996830 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b2ac0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/Zygote  ( 3955): MountEmulatedStorage(),
E/Zygote  ( 3955): v2
I/libpersona( 3955): KNOX_SDCARD checking this for 10166
I/libpersona( 3955): KNOX_SDCARD not a persona,
I/SELinux ( 3955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3955): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3955 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3212:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3343): took 0.739427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79783f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b2ac0 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=3970 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3260:com.fmm.ds/1000 (adj 15): empty #31
,E/Zygote  ( 3970): MountEmulatedStorage()
E/Zygote  ( 3970): v2
I/libpersona( 3970): KNOX_SDCARD checking this for 1000
I/libpersona( 3970): KNOX_SDCARD not a persona
,I/SELinux ( 3970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
D/TimaKeyStoreProvider( 3955): TimaSignature is unavailable
D/ActivityThread( 3955): Added TimaKeyStore provider
,E/SELinux ( 3970): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/AMMetaDataParserService( 3343): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/art     (  304): Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 36.347ms
,D/TimaKeyStoreProvider( 3970): TimaSignature is unavailable
,D/ActivityThread( 3970): Added TimaKeyStore provider
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3343): took 0.548334ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b2ac0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b58b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 17.215ms
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
W/ContextImpl( 3343): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 916us total 19.370ms
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
I/AMMetaDataParserService( 3343,): Resource data:2131165203
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
W/ResourcesManager( 3343): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/RCPManagerService( 1017): exchangeData() failure , invalid userId
I/AMMetaDataParserService( 3343): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3343): getResourceTypeNamexml
D/SecurityLogAgent( 3970): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 3970): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 3970): StateMachine : Current State = 1
D/SecurityLogAgent( 3970): BootReceiver : completed task. Failed to return wakelock . 
E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX construct_block_size_descriptor_2d second part( 3343): took 2.735260ms for 0*0 texture 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3188/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10069/pid_3212/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3260/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/GFX generate_partition_tables( 3343): took 10.510466ms for 0*0 texture 0
I/GFX raster( 3343): took 14.021768ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b2408 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7996138 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4001): MountEmulatedStorage()
E/Zygote  ( 4001): v2
I/libpersona( 4001): KNOX_SDCARD checking this for 10152
I/libpersona( 4001): KNOX_SDCARD not a persona
,I/SELinux ( 4001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4001 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/AMMetaDataParserService( 3343): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,I/SELinux ( 4001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Killing 3278:com.sec.factory.camera/1000 (adj 15): empty #31
,E/SELinux ( 4001): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 1702): (10) POSIX Error : 11 SQLite Error : 3850
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3343): took 0.767917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996138 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7995728 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4001): TimaSignature is unavailable
,D/ActivityThread( 4001): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3343): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,E/SQLiteLog( 4001): (284) automatic index on shooting_modes(title_id)
,I/Process ( 3842): Sending signal. PID: 3842 SIG: 9
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3278/cgroup.procs: No such file or directory
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.825937ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996138 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7994180 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3343): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/ActivityManager( 1017): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,D/BadgeProvider( 3861): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/Process ( 3903): Sending signal. PID: 3903 SIG: 9
,D/BadgeProvider( 3861): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3861): sendNotify, [notify] : null
D/BadgeProvider( 3861): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3861): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 3861): update, [UpdateCount] : 1
D/Launcher.Model( 1493): reloadBadges entered.
,I/ActivityManager( 1017): Process com.sec.android.app.sns3 (pid 3842)(adj 0) has died(38,1127)
,I/ActivityManager( 1017): Process com.android.exchange (pid 3903)(adj 11) has died(38,1127)
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3821): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3821): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3821): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 4019): MountEmulatedStorage(),
I/libpersona( 4019): KNOX_SDCARD checking this for 10034
,E/Zygote  ( 4019): v2
I/libpersona( 4019): KNOX_SDCARD not a persona
I/SELinux ( 4019): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 4019): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4019 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 4019): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4019): TimaSignature is unavailable
,D/ActivityThread( 4019): Added TimaKeyStore provider
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3343): took 0.768230ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996138 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7992e18 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3343): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,E/Zygote  ( 4035): MountEmulatedStorage(),
I/libpersona( 4035): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4035): v2
I/libpersona( 4035): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4035 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/ResourcesManager( 3821): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 3955): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3955): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SELinux ( 4035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4035): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3343): took 0.622500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79af740 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb798d310 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/TimaKeyStoreProvider( 4035): TimaSignature is unavailable
,D/ActivityThread( 4035): Added TimaKeyStore provider
,V/JNIHelp ( 3955): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.671510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79af740 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79938a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4057): MountEmulatedStorage()
,E/Zygote  ( 4057): v2
I/libpersona( 4057): KNOX_SDCARD checking this for 1000
I/libpersona( 4057): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4057 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2953:com.google.android.gms:car/u0a12 (adj 15): empty #31
,I/SELinux ( 4057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 4057): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4057): TimaSignature is unavailable
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
D/ActivityThread( 4057): Added TimaKeyStore provider
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
W/ContextImpl( 3343): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,E/Zygote  ( 4071): MountEmulatedStorage()
E/Zygote  ( 4071): v2
I/libpersona( 4071): KNOX_SDCARD checking this for 1101
I/libpersona( 4071): KNOX_SDCARD not a persona
,I/SELinux ( 4071): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4071): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4071): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4071 uid=1101 gids={41101, 9997} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 2988:com.android.vending/u0a28 (adj 15): empty #31
,W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,D/TimaKeyStoreProvider( 4071): TimaSignature is unavailable
,D/ActivityThread( 4071): Added TimaKeyStore provider
,W/ResourcesManager( 4071): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.default_searchable
,I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3343): Resource data:2131099648
,V/SmartcardService( 4071): main Received broadcast
V/SmartcardService( 4071): Starting smartcard service after boot completed
,D/ActivityManager( 1017): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,I/ActivityManager( 1017): Killing 3297:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,W/ActivityThread( 3955): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3955): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@af0c317: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3955): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 3343): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3343): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3343): getResourceTypeNamexml
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.980469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7ebc788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ebc968 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1017): failed to open /acct/uid_10028/pid_2988/cgroup.procs: No such file or directory
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3343): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523,
,E/Zygote  ( 4088): MountEmulatedStorage()
E/Zygote  ( 4088): v2
I/libpersona( 4088): KNOX_SDCARD checking this for 1000
I/libpersona( 4088): KNOX_SDCARD not a persona
,I/SELinux ( 4088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4088): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=4088 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/libprocessgroup( 1017): failed to open /acct/uid_10100/pid_3297/cgroup.procs: No such file or directory
,I/CalendarProvider2( 3760): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX construct_block_size_descriptor_2d second part( 3343): took 2.504583ms for 0*0 texture 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
I/DBG_DM  ( 2831): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/ActivityManager( 1017): Killing 3324:com.samsung.helphub/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4088): TimaSignature is unavailable
,D/ActivityThread( 4088): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4057): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 4057): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 4057): [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
,I/GFX generate_partition_tables( 3343): took 8.892605ms for 0*0 texture 0
,I/GFX raster( 3343): took 12.383125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7631b70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb797a130 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ContextImpl( 4088): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
E/SMD     (  288): DCD OFF
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4110 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3324/cgroup.procs: No such file or directory
E/Zygote  ( 4110): MountEmulatedStorage()
I/libpersona( 4110): KNOX_SDCARD checking this for 10157
E/Zygote  ( 4110): v2
I/libpersona( 4110): KNOX_SDCARD not a persona
,I/SELinux ( 4110): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4110): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4110): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.883020ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb79a97a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/TimaKeyStoreProvider( 4110): TimaSignature is unavailable
,D/ActivityThread( 4110): Added TimaKeyStore provider
,W/ResourcesManager( 4110): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4125): MountEmulatedStorage()
I/libpersona( 4125): KNOX_SDCARD checking this for 10159
E/Zygote  ( 4125): v2
I/libpersona( 4125): KNOX_SDCARD not a persona
,I/SELinux ( 4125): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4125): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4125 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 4125): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 3104:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4125): TimaSignature is unavailable
,D/ActivityThread( 4125): Added TimaKeyStore provider
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.758698ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7ebc788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb75e4990 counterpartCT=4 counterpartW=96 counterparth=96
,I/Intent to TravelDirActivity( 4125): inside TravelBroadcastReceiver
,I/AMMetaDataParserService( 3343): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/ActivityManager( 1017): Killing 3380:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.630260ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb794ad40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb75e4b40 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.821095ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b11a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb762d978 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1017): failed to open /acct/uid_10009/pid_3104/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3380/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3343): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
I/AMMetaDataParserService( 3343): Resource data:2131099648
,I/AMMetaDataParserService( 3343): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3343): getResourceTypeNamexml
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.683073ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb76bb8e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79a97a8 counterpartCT=4 counterpartW=96 counterparth=96
,D/BluetoothAdapter( 2909): disable()
,E/BluetoothManagerService( 1017): Bluetooth is already disabled. DO NOT disable again.
,I/AMMetaDataParserService( 3343): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: false pid=2909, uid=10174
,D/SettingsProvider( 1017): name = wifi_on
,I/jxcore-log( 2909): ****TEST TOOK:  5051  ms ****
I/jxcore-log( 2909): 
,I/jxcore-log( 2909): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2909): 
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3343): took 0.634896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7631b70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb797a130 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3343): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.618750ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb79b5e60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.741354ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7ebc788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb75e4b40 counterpartCT=4 counterpartW=96 counterparth=96
,I/dex2oat ( 4148): ----------------------------------------------------
I/dex2oat ( 4148): <SS>: S T A R T I N G . . .
I/dex2oat ( 4148): <SS>: Zip is absent. Canceled.
I/dex2oat ( 4148): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1916543144.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads1916543144.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/AMMetaDataParserService( 3343): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.646979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb794ad40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb797a130 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/YouTube MDX( 3955): Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
,I/dex2oat ( 4148): dex2oat took 64.378ms (threads: 4)
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.794063ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b11a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b5598 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/DBG_POLICYDM( 4057): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4057): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 4057): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 4057): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
I/AMMetaDataParserService( 3343): Resource data:2131099648
,I/AMMetaDataParserService( 3343): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3343): getResourceTypeNamexml
,I/DBG_POLICYDM( 4057): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.690364ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb76bb8e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb797a130 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4057): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 4057): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 4057): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
I/DBG_POLICYDM( 4057): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/AMMetaDataParserService( 3343): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_POLICYDM( 4057): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 4057): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DBG_POLICYDM( 4057): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 ,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4057): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 4057): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 4057): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3343): took 0.656927ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7631b70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb75e4b40 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3343): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/DBG_POLICYDM( 4057): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/AndroidRuntime( 4146): 
D/AndroidRuntime( 4146): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4146): CheckJNI is OFF
,D/AndroidRuntime( 4146): readGMSProperty: start
D/AndroidRuntime( 4146): readGMSProperty: already setted!!
D/AndroidRuntime( 4146): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4146): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4146): readGMSProperty: end
D/AndroidRuntime( 4146): addProductProperty: start
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4057): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4166 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DBG_POLICYDM( 4057): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/ActivityManager( 1017): Killing 3359:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
E/Zygote  ( 4166): MountEmulatedStorage(),
I/DBG_POLICYDM( 4057): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
E/Zygote  ( 4166): v2
I/libpersona( 4166): KNOX_SDCARD checking this for 10041
,I/libpersona( 4166): KNOX_SDCARD not a persona
,I/SELinux ( 4166): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4166): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4166): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/DBG_POLICYDM( 4057): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,D/TimaKeyStoreProvider( 4166): TimaSignature is unavailable
,D/ActivityThread( 4166): Added TimaKeyStore provider
,D/SSRM:n  ( 1017): SIOP:: AP = 400
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
,W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3955): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_3359/cgroup.procs: No such file or directory
,E/AffinityControl( 4146): AffinityControl: registerfunction enter
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3343): took 0.626980ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb79b5e60 counterpartCT=4 counterpartW=96 counterparth=96
D/AndroidRuntime( 4146): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1017): START PACKAGE DELETE: observer{860972493}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
I/AMMetaDataParserService( 3343): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/PackageManager( 1017): !@killApplicatoin: 10174, uninstall pkg
I/ActivityManager( 1017): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1017): Killing 2909:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,I/SA      ( 4166): [SSP] onCreated
,I/WindowState( 1017): WIN DEATH: Window{6a20e73 u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/7)
,D/InputDispatcher( 1017): Focus left window: 2909,
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.789115ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7ebc788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb797a130 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/DBG_DM  ( 2831): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1017): Force removing ActivityRecord{18de7629 u0 com.example.hello/.MainActivity t228}: app died, no saved state
,D/FocusedStackFrame( 1017): Set to : 0
,I/GFX raster( 3343): took 0.630990ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb794ad40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb75e4b40 counterpartCT=4 counterpartW=96 counterparth=96
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1017): Focused application set to: xxxx
,I/AMMetaDataParserService( 3343): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.acquire()
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.717240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b11a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b5e60 counterpartCT=4 counterpartW=96 counterparth=96
,V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,I/AMMetaDataParserService( 3343): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1017): Spurious death for ProcessRecord{303afe82 2909:com.example.hello/u0a174}, curProc for 2909: null
,D/Launcher( 1493): onRestart, Launcher: 174764612
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1017): [SO] activate (ident=0xb7e80b10, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/Launcher( 1493): onStart, Launcher: 174764612
D/Launcher.HomeView( 1493): onStart
D/Launcher( 1493): onResume, Launcher: 174764612
,D/SettingsProvider( 1017): name = kids_home_mode
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10007
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
I/AMMetaDataParserService( 3343): Resource data:2131099648
,D/SettingsProvider( 1017): ret = -1
,D/Launcher.HomeView( 1493): onResume
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10174 user=0: pkg removed
,I/AMMetaDataParserService( 3343): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3343): getResourceTypeNamexml
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.688333ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb76bb8e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79575b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1017): [SO] changed settle time [0]
D/SensorService( 1017): [SO] setDelay [200000000]
D/SensorService( 1017): [SO] activate (ident=0xb7e80b10, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/AMMetaDataParserService( 3343): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,I/SA      ( 4166): [TPM] There is no property file
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.725052ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7631b70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb797a130 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,I/SA      ( 4166): [SCU] isHaveSA() - false
,I/AMMetaDataParserService( 3343): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,I/SA      ( 4166): [TPM] getModelProperty : null
,I/SA      ( 4166): [TPM] getCSCProperty : null
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SA      ( 4166): [DM] FLOATING AMOLED FEATURE: true
I/GFX raster( 3343): took 0.629479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb79b5e60 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4166): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4166): [DM] TFT FEATURE: false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/AMMetaDataParserService( 3343): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/SA      ( 4166): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4166): [DM] init START
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.990156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7ebc788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb79575b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.827969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb794ad40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb797a130 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4166): [DM] This device is not a Vodafone
,I/AMMetaDataParserService( 3343): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
E/SamsungIME( 1777): mOCRHelper is null
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,D/MenuAppsGridFragment( 1493): onResume
,D/ActivityManager( 1017): handle home activity for 0
I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1017): post home show event for user 0
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
,W/ResourcesManager( 1470): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3343): took 0.844740ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b11a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b5e60 counterpartCT=4 counterpartW=96 counterparth=96
D/RegisteredComponentCache( 1456): Collect Tech packages for Knox
D/PersonaManager( 1456): isKioskContainerExistOnDevice
W/ResourceType( 4166): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 4166): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 4166): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4166): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4166): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4166): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4166): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
I/AMMetaDataParserService( 3343): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
W/ResourceType( 4166): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4166): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4166): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75),
W/ResourceType( 4166): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
I/AMMetaDataParserService( 3343): Resource data:2131099648
I/SA      ( 4166): [SCU] isHaveSA() - false
I/SA      ( 4166): support phone number id : false
I/SA      ( 4166): [DM] Supports Ref Jpn : true
,I/SA      ( 4166): [DM] init END
,I/AMMetaDataParserService( 3343): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3343): getResourceTypeNamexml
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.686406ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb76bb8e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb75e4158 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.679584ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7631b70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb79575b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.787761ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb79b5e60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.637448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7ebc788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7945c30 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.645989ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb794ad40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b5ce8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.719166ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b11a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb75e4158 counterpartCT=4 counterpartW=96 counterparth=96
,D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
,I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1017): uID is 10174
D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/PersonaManager( 1456): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1456): empty dynamic service
I/AMMetaDataParserService( 3343): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10174
D/TaskPersister( 1017): removeObsoleteFile: deleting file=228_task.xml
,V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
I/AMMetaDataParserService( 3343): Resource data:2131099648
,I/AMMetaDataParserService( 3343): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3343): getResourceTypeNamexml
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.677604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb76bb8e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79a97a8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.629844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7631b70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb79575b8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.647396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7996598 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7945c30 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 40915(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 26MB/40MB, paused 2.915ms total 265.560ms
,I/art     ( 1017): WaitForGcToComplete blocked for 206.454ms for cause Explicit
,I/AMMetaDataParserService( 3343): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/PackageManager( 1017): delete codoeFile: 
,I/GFX raster( 3343): took 0.635312ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb7ebc788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb79b5e60 counterpartCT=4 counterpartW=96 counterparth=96
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
,I/AASA_removePackage( 1017): UID=10174 Target=com.example.hello
,D/PackageManager( 1017): result of delete: 1{860972493}
,D/AndroidRuntime( 4146): Shutting down VM
,I/AMMetaDataParserService( 3343): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.637187ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb794ad40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79a9090 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3343): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3343): took 0.725833ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3343): Bitmap=0xb79b11a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79b5ce8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3343): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
W/ContextImpl( 3343): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.widget.Widget,PreferenceActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
D/SensorService( 1017): [SO] currT = 41351101000, prevT = 40881052000, diff = 470049000, [0.172 0.096 10.209]
D/SensorService( 1017): [SO] 0.172 0.096 10.209
D/SensorService( 1017): [SO] [100 -> 255]
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 6860(457KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.181ms total 143.072ms
,W/GeofencerStateMachine( 1655): Ignoring removeGeofence because network location is disabled.
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=4, Mauncher
,I/SA      ( 4166): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 4166): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1017): Focus entered window: 1493
,I/SA      ( 4166): [OR] onReceive END
,D/SRIB_DCS( 1493): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
I/AMMetaDataParserService( 3343): Resource data:2131165197
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 2909 uid 10174
,W/ResourcesManager( 3343): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/PanelView( 1176): There is/are notification(s) 
W/ResourcesManager( 3343): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3343): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3343): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SA      ( 4166): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4166): [ODM] queryOpenData(key= GEO_IP )
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3343): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3343): getResourceTypeNamexml
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SA      ( 4166): getMccForGalaxyJpn step2 GEO_IP MCC : 260,
I/SA      ( 4166): [LBE] REF_JPN : true
I/SA      ( 4166): [BDC] create
,D/SamsungIME( 1777): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/AMMetaDataParserService( 3343): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625,
,I/AMMetaDataParserService( 3343): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623,
,W/art     ( 4146): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,I/AMMetaDataParserService( 3343): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/SA      ( 4166): [DBMV2] getEmailID
,I/SA      ( 4166): [DBMV2] getDataV02ForItems
,I/SA      ( 4166): [SSP] query invoked
,I/SA      ( 4166): [SCU] get signed id from samsung account2.0 DB.
,I/AMMetaDataParserService( 3343): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SA      ( 4166): [SCU] get signed id from samsung account1.0 DB.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SA      ( 4166): [BDC] destroy
,I/ActivityManager( 1017): Killing 3438:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3343): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3343): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3343): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3343): getResourcePackageName:assistant
I/AMMetaDataParserService( 3343): Resource data:2131165197
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3343): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3343): getResourceTypeNamexml
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3343): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/ActivityManager( 1017): Displayed Component not be shown by security: +664ms
,W/ContextImpl( 3955): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3955): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3955): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3343): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,E/SQLiteLog( 3343): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 3343): (3850) statement aborts at 19: [INSERT INTO AMData(actname,amicon,appname,id,amtitle,amstate,amintent,amlabel) VALUES (?,?,?,?,?,?,?,?)] disk I/O error
,W/InstanceID/Rpc( 3955): Found 10012
,E/SQLiteDatabase( 3343): Error inserting actname=com.sec.android.gallery3d.app.GalleryActivity amicon=[B@57684f0 appname=com.sec.android.gallery3d id=1447834337731 amtitle=Slideshow amstate=1 amintent=android.intent.action.slideshow amlabel=2131624011
E/SQLiteDatabase( 3343): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 3343): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:77)
E/SQLiteDatabase( 3343): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3343): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3343): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3343): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3343): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3343): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/FileUtils( 3955): Failed to chmod(/data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog( 3955): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 3955): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/AMMetaDataParserService( 3343): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
E/SQLiteLog( 3343): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 3343): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3343): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3343): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3343): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3343): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3343): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3343): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3343): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3343): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3343): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3343): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3343): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3343): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3343): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3343): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3343): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3343): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3343): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3343): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3343): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3343): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3343): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 3343): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3343): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3343): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.j,ava:223)
W/System.err( 3343): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 3343): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3343): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3343): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
W/System.err( 3343): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3343): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3343): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3343): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1017): Killing 3343:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1017): clearDefaults: com.example.hello
I/CrashAnrDetector( 1017): onPackageRemoved : com.example.hello
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3955): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3438/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3343/cgroup.procs: No such file or directory

```
