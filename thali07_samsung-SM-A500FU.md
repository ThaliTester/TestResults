#### Test 5038801932cd575_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
D/PersonaManagerService( 1017): ACTION_BOOT_COMPLETED
--------- beginning of system
D/UsbStorageNotification( 1017): boot completed
E/PersonaManagerServiceHandler( 1017):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
D/KnoxKeyguardUpdateMonitor( 1017): onBootComplete
D/GpsLocationProvider( 1017): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
D/GpsLocationProvider_ex( 1017): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1017): set_capabilities_callback: 55u
I/libmdmdetect( 1017): ESOC framework not supported
I/libmdmdetect( 1017): Found internal modem: modem
E/PerMgrLib( 1017): Peripheral manager is not supported on this device
E/Geofence_Adapter( 1017): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1017): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1017): BOOT_COMPLETED native_cleanup 
D/qmi_secgps_clnt( 1017): qmi_secgps_client_init()
I/KnoxKeyguardUpdateMonitor( 1017): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1017): onTrustChanged user:0, enable:false
D/KeyguardViewMediator( 1179): onTrustChanged( Showing = false , userId = 0 )
D/StorageNotification( 1179): boot completed
I/i       ( 1017): No model
D/WIFI    ( 1017): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/FactoryTest( 1017): Not factory mode
D/FactoryTest( 1017): Not factory mode. isFactoryMode() returend false
D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
D/w       ( 1017): isUserBuild = true
D/qmi_secgps_clnt( 1017): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
D/PhoneStatusBar( 1179): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
D/StatusBarManagerService( 1017): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2664): MountEmulatedStorage()
E/Zygote  ( 2664): v2
I/SELinux ( 2664): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/SSRM:n  ( 1017): SIOP:: AP = 390
I/libpersona( 2664): KNOX_SDCARD checking this for 10099
I/libpersona( 2664): KNOX_SDCARD not a persona
I/SELinux ( 2664): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2664): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2664 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
D/TimaKeyStoreProvider( 2664): TimaSignature is unavailable
D/ActivityThread( 2664): Added TimaKeyStore provider
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
E/ActivityThread( 2664): Failed to find provider info for flipboard.auth.internal.debug
E/ActivityThread( 2664): Failed to find provider info for flipboard.auth.internal
I/splitIntent( 1017): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=88, mSplitNum[1]=125, mSplitNum[2]=162, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 51 receivers.size=198
I/splitIntent( 1017): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
I/DrmEventReceiver( 1017): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1017): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
I/DrmEventReceiver( 1017): DrmEventReceiver : beginStartingService
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
I/System.out( 1017): start Service
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/qmi_secgps_clnt( 1017): SECGPS: Set XTRA enable : 1
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1017): SECGPS: Set GNSS RF CONFIG : 1
D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1017): SECGPS: Set CERT TYPE : 15
D/qmi_secgps_clnt( 1017): SECGPS: send a qmi message to secgps_server OK
V/DownloadManager( 1224): onReceive intent + android.intent.action.BOOT_COMPLETED
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
E/Zygote  ( 2685): MountEmulatedStorage()
I/libpersona( 2685): KNOX_SDCARD checking this for 10085
E/Zygote  ( 2685): v2
I/libpersona( 2685): KNOX_SDCARD not a persona
I/SELinux ( 2685): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2685 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/SELinux ( 2685): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2685): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2685): TimaSignature is unavailable
D/ActivityThread( 2685): Added TimaKeyStore provider
E/Zygote  ( 2698): MountEmulatedStorage()
E/Zygote  ( 2698): v2
I/libpersona( 2698): KNOX_SDCARD checking this for 1000
I/libpersona( 2698): KNOX_SDCARD not a persona
I/SELinux ( 2698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2698 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
E/SELinux ( 2698): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SensorService( 1017): [SO] currT = 30751040000, prevT = 30331038000, diff = 420002000, [0.172 0.096 10.190]
D/ActivityManager( 1017): retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
D/SensorService( 1017): [SO] 0.172 0.096 10.190
D/SensorService( 1017): [SO] [100 -> 255]
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1017): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
E/LocSvc_ApiV02( 1017): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
E/LocSvc_ApiV02( 1017): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1017): mCursor = null
D/MediaScannerReceiver( 1224): action: android.intent.action.BOOT_COMPLETED
D/WVMDrmPlugIn(  282): WVMDrmPlugin::onInitialize : 3295
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
D/WVMDrmPlugIn(  282): WVMDrmPlugin::onSetOnInfoListener : add 3295
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/TimaKeyStoreProvider( 2698): TimaSignature is unavailable
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/ActivityThread( 2698): Added TimaKeyStore provider
I/DrmEventService( 1017): action event :android.intent.action.BOOT_COMPLETED
W/ResourcesManager( 2685): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2685): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2685): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2685): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 2685): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2685): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
I/TimaServiceEventReceiver( 1017): TimaServiceEventReceiver : onReceive
I/ANDROID_DRM_FRWORKS_DrmManager(  282): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
W/CursorWrapperInner( 2284): Cursor finalized without prior close()
E/CscReceiver( 1468): onReceive android.intent.action.BOOT_COMPLETED
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/CscUpdateService( 1468): onStart
I/libpersona( 2720): KNOX_SDCARD checking this for 10003
E/CscUpdateService( 1468): costomer file is exists : it has been preconfiged.
I/libpersona( 2720): KNOX_SDCARD not a persona
I/CscUpdateService( 1468): set_CSC_version
E/CscParser( 1468): update(): xml file exist
E/Zygote  ( 2720): MountEmulatedStorage()
E/Zygote  ( 2720): v2
I/SELinux ( 2720): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2720): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2720): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2720 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/CscUtil ( 1468): isWifiOnly = false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/System.out( 1468): HandDataNode = null
I/CscUpdateService( 1468): PATH_CSCNAME =CustomerDataSet.CSCName
D/TimaKeyStoreProvider( 2720): TimaSignature is unavailable
I/CscUpdateService( 1468): This is normal boot : CSC not updated
D/ActivityThread( 2720): Added TimaKeyStore provider
E/Zygote  ( 2737): MountEmulatedStorage()
I/libpersona( 2737): KNOX_SDCARD checking this for 10160
E/Zygote  ( 2737): v2
I/libpersona( 2737): KNOX_SDCARD not a persona
I/SELinux ( 2737): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
E/CscParser( 1468): update(): xml file exist
I/SELinux ( 2737): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2737 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
E/SELinux ( 2737): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CscGPS  ( 1468): CSCGPS.updateParameters
D/CscGPS  ( 1468): supl host : null
D/CscGPS  ( 1468): SUPL Host is null or invalid
D/CscGPS  ( 1468): supl_ver : null
D/CscGPS  ( 1468): SUPL Ver is null or invalid
D/CscGPS  ( 1468): supl port : null
D/CscGPS  ( 1468): SUPL PORT is null or invalid
D/CscGPS  ( 1468): LPP : null
D/CscGPS  ( 1468): LPP is null or invalid
D/CscGPS  ( 1468): CSC don't have any AGPS value.
I/CscUpdateService( 1468): same CSC Version
D/CscUtil ( 1468): Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
D/MediaScannerService( 1224): !@start scanning volume internal: [/system/media, /oem/media]
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/MtpService( 1224): updating state; isCurrentUser=true, mMtpLocked=false
D/TimaKeyStoreProvider( 2737): TimaSignature is unavailable
D/ActivityThread( 2737): Added TimaKeyStore provider
D/TP/MmsProvider( 1468): Update uri=content://mms, match=0
D/TP/MmsProvider( 1468): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1468): need read changed broadcast:false
I/Mms:transaction( 2284): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2284): [start]    nonBlockingUpdateMessageIndicator() consume time = 2409.985781
I/Mms/ReservationManager( 2284): resetAfterConnected()
D/Mms/MessagingNotification( 2284): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2284): isDefault true
D/TP/MmsSmsProvider( 1468): query,matched:7, calling pid = 2284
D/TP/MmsProvider( 1468): Query uri=content://mms, match=0, calling pid = 2284
W/ResourcesManager( 2737): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1468): match 7:Elapsed time : 7.313 ms
I/Mms/ReservationManager( 2284): getReservedSendMessageCount(): retMessageCount=0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2755): MountEmulatedStorage()
I/libpersona( 2755): KNOX_SDCARD checking this for 10048
E/Zygote  ( 2755): v2
I/libpersona( 2755): KNOX_SDCARD not a persona
I/SELinux ( 2755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2755): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2755 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/TP/MmsSmsProvider( 1468): query,matched:200, calling pid = 2284
D/TP/MmsSmsProvider( 1468): match 200:Elapsed time : 1.506 ms
D/Mms/SmsReceiverService( 2284): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/Mms/TelephonyPermission( 2284): isDefault true
D/Mms/SmsReceiverService( 2284): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2284): [start]    handleBootCompleted() consume time = 60.660677
D/TP/MmsSmsProvider( 1468): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1468): deleteConversation threadId: 9223372036854775806
D/TP/SmsProvider( 1468): query,matched:0, calling pid = 2284
D/TimaKeyStoreProvider( 2755): TimaSignature is unavailable
D/ActivityThread( 2755): Added TimaKeyStore provider
D/TP/SmsProvider( 1468): match 0:Elapsed time : 2.671 ms
D/TP/MmsSmsProvider( 1468): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1468): updateThread(), thread_id = 9223372036854775806
V/TP/MmsSmsDatabaseHelper( 1468): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1468): (284) automatic index on im_threads(normal_thread_id)
D/TP/SmsProvider( 1468): query,matched:51, calling pid = 2284
E/SQLiteLog( 1224): (283) recovered 265 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
D/TP/SmsProvider( 1468): match 51:Elapsed time : 1.958 ms
D/TP/MmsSmsProvider( 1468): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1468): need read changed broadcast:false
W/ResourcesManager( 2755): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2755): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2755): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
D/Mms/Conversation( 2284): deleteTempConversation(),deleted=0
D/SmsProvider( 1468): Update uri=content://sms/outbox, match=8
D/Mms/MessagingNotification( 2284): isBlockingModeEnabled() = false, Zen mode = 0
D/TP/MmsSmsProvider( 1468): need read changed broadcast:false
D/Mms/SmsReceiverService( 2284): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2284): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2284): [SIM-1]sendFirstQueuedMessage()
D/TP/SmsProvider( 1468): query,matched:26, calling pid = 2284
D/TP/SmsProvider( 1468): match 26:Elapsed time : 4.767 ms
D/Mms/SmsReceiver( 2284): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2284): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2284): isDefault true
D/TP/MmsProvider( 1468): Query uri=content://mms, match=0, calling pid = 2284
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/BadgeProvider( 1583): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/SecureStorage( 2720): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
D/SettingsProvider( 1017): name = block_emergency_message
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10048
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
W/ActivityManager( 1017): getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/SMD     (  291): DCD OFF
I/ActivityManager( 1017): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2774 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 2774): MountEmulatedStorage()
E/Zygote  ( 2774): v2
I/libpersona( 2774): KNOX_SDCARD checking this for 1000
I/libpersona( 2774): KNOX_SDCARD not a persona
I/SELinux ( 2774): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2774): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2774): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
I/WifiCredService( 1306): onCreate
D/[0]UMC:UMCContentProvider( 2737): @onCreate
D/TimaKeyStoreProvider( 2774): TimaSignature is unavailable
D/ActivityThread( 2774): Added TimaKeyStore provider
D/[0]UMC:Core( 2737): onCreate(): 
E/USB_UICC(  300): Timeout! No signal received. Retry num = 25
D/[0]UMC:Core( 2737): @isManagedProfileUser
D/[0]UMC:Core( 2737): userId: 0
D/[0]UMC:Core( 2737): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 2737): userInfo.isManagedProfile() : false
D/WifiTimerReceiver( 1306): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1306): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1306): Action boot completed received
D/Launcher.Model( 1493): reloadBadges entered.
D/BadgeProvider( 1583): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1583): sendNotify, [notify] : null
D/BadgeProvider( 1583): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1583): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1583): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 2284): setBadgeCount(), count=0
D/Mms/MessagingNotification( 2284): remove alarm
D/NearbySettings( 1306): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1306): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1306): MountReceiver.onReceive - Create mPrefHandler
D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
D/SettingsProvider( 1017): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
D/Mms/MessagingNotification( 2284): updateAllHistoryAsRead()
D/[0]UMC:DeviceInfo( 2737): USA==US==
E/SQLiteLog( 2774): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
D/SettingsProvider( 1017): name = next_alarm_formatted
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10085
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/TP/SmsProvider( 1468): query,matched:0, calling pid = 2284
D/TP/SmsProvider( 1468): match 0:Elapsed time : 1.648 ms
D/Mms/MessagingNotification( 2284): [end]    nonBlockingUpdateMessageIndicator() consume time = 267.340989
D/DSM     ( 2774): [Lines:107] Normal booted
D/DSM     ( 2774): [Lines:114] Boot completed
I/SecureStorage( 2720): [INFO]: SPID(0x00000000)This device supports Secure Storage
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
I/SecureStorage(  402): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2720
I/SecureStorage(  402): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 2720): [INFO]: SPID(0x00000000)SS Daemon is running
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10085
I/SecureStorage( 2720): [INFO]: SPID(0x00000000)Processing data
I/ActivityManager( 1017): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2800 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 2800): MountEmulatedStorage()
E/Zygote  ( 2800): v2
I/libpersona( 2800): KNOX_SDCARD checking this for 1000
I/libpersona( 2800): KNOX_SDCARD not a persona
I/SELinux ( 2800): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SecureStorage(  402): [INFO]: SPID(0x00000000)Credentials: uid 10003, gid 10003, pid 2720
I/SecureStorage(  402): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
I/SELinux ( 2800): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2800): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/NearbySettings( 1306): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/art     ( 1468): Explicit concurrent mark sweep GC freed 39043(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 7MB/12MB, paused 989us total 246.220ms
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
I/NearbySettings( 1306): MountReceiver.onReceive - Internal Path
D/SSRM:a  ( 1017): DeviceInfo:: 000000000000
D/SSRM:a  ( 1017): SettingsAirViewInfo:: 000000000
D/SettingsProvider( 1017): name = personal_mode_enabled
D/MediaScanner( 1224): Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/USER_AGENT( 2737): UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
D/TimaKeyStoreProvider( 2800): TimaSignature is unavailable
D/ActivityThread( 2800): Added TimaKeyStore provider
W/ResourcesManager( 2800): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1468): query,matched:200, calling pid = 2284
D/TP/MmsSmsProvider( 1468): match 200:Elapsed time : 2.894 ms
D/[0]UMC:AdminManager( 2737): init - start
D/[0]UMC:AdminManager( 2737): loadAdmins
D/TP/SmsProvider( 1468): query,matched:0, calling pid = 2284
D/TP/SmsProvider( 1468): match 0:Elapsed time : 1.898 ms
D/TP/SmsProvider( 1468): query,matched:51, calling pid = 2284
D/TP/SmsProvider( 1468): match 51:Elapsed time : 2.333 ms
W/ActivityThread( 2800): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/[0]UMC:AdminManager( 2737): init - end
D/GSLBManager( 2737): migrateStoredUrlFromOldPref
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
I/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
D/Mms/MessagingNotification( 2284): isBlockingModeEnabled() = false, Zen mode = 0
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
W/ResourcesManager( 1468): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1468): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/GSLBManager( 2737):  key : segd-api
D/GSLBManager( 2737):  value : https://eu-segd-api.secb2b.com:443/v2
I/SmartcardBootCompleteReceiver( 1306): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1306): Received intent with action - android.intent.action.BOOT_COMPLETED
W/art     ( 2685): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 124.031ms
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/BadgeProvider( 1583): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
I/SmartcardBootCompleteReceiver( 1306): Broadcast sent with current lockscreen type
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/GSLBManager( 2737):  key : umc-cdn
D/GSLBManager( 2737):  value : 
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 2800): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/LcdtestApp( 2800): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
D/GSLBManager( 2737):  key : segp-api
D/GSLBManager( 2737):  value : 
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/GSLBManager( 2737):  key : myknoxapi
D/GSLBManager( 2737):  value : 
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2820 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 2820): MountEmulatedStorage()
I/libpersona( 2820): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2820): v2
I/libpersona( 2820): KNOX_SDCARD not a persona
I/SELinux ( 2820): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2820): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2820): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/GSLBManager( 2737): migrateStoredUrlFromOldPref : Finished Migrating
D/[0]UMC:UMCAdmin( 2737): deactivateUMCAdminIfNotRequired : -1
D/TimaKeyStoreProvider( 2820): TimaSignature is unavailable
I/ActivityManager( 1017): Killing 1197:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
D/ActivityThread( 2820): Added TimaKeyStore provider
I/art     (  307): Explicit concurrent mark sweep GC freed 8771(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 32ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 17.702ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 772us total 17.715ms
D/[SBeam] ( 1306): SBeamEnabler.initPreferenceForSbeam : 0
I/SettingSearch/SearchIntentReceiver( 1306): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1306): search setting db init!!
E/[0]UMC:Utils( 2737): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2737): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2737): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2737): isContainer : 0
V/MediaScanner( 1224): processDirectory :  /system/media
D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 2737): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2737): isContainer : 0
D/[0]UMC:UMCAdmin( 2737): deactivateUMCAdmin - UMC App Admin deactivated
D/AndroidRuntime( 2816): 
D/AndroidRuntime( 2816): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2816): CheckJNI is OFF
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 2816): readGMSProperty: start
D/AndroidRuntime( 2816): readGMSProperty: already setted!!
D/AndroidRuntime( 2816): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2816): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2816): readGMSProperty: end
D/AndroidRuntime( 2816): addProductProperty: start
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
I/SettingSearch/SearchIntentReceiver( 1306): BOOT_COMPLETED call InitSerachDBThread thread start!
D/[0]UMC:GuardService( 2737): @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
D/[0]UMC:CoreReceiver( 2737): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2737):  check PreETag 
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2840): MountEmulatedStorage()
E/Zygote  ( 2840): v2
I/ActivityManager( 1017): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=2840 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 2840): KNOX_SDCARD checking this for 1000
I/libpersona( 2840): KNOX_SDCARD not a persona
I/SELinux ( 2840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 2840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2840): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_1197/cgroup.procs: No such file or directory
D/[0]UMC:CoreReceiver( 2737): bulk enrolled package: null
V/[0]UMC:ProfileStorage( 2737): Enter loadList
D/[0]UMC:CoreReceiver( 2737): handleAutoEnrollmentAndUMCAdminDeactivation
D/[0]UMC:UMCAdmin( 2737): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 2737): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2737): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2737): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2737): isContainer : 0
D/TimaKeyStoreProvider( 2840): TimaSignature is unavailable
D/ActivityThread( 2840): Added TimaKeyStore provider
V/MediaScanner( 1224):  prescan time: 658ms (DB items: 141)
V/MediaScanner( 1224):     scan time: 101ms (Caching mode: true), (makeEntry time: 64ms ~63%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1224): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1224):    total time: 759ms
V/MediaScanner( 1224): checked files: 133  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1224): checkDefaultSounds
D/MediaScanner( 1224): system alarm_alert  : Vwiurug_etwofi5wgg
D/EnterpriseDeviceManagerService( 1017): isManagedProfileUser(): userId = 0
E/[0]UMC:UMCAdmin( 2737): No active admin owned by uid 10160
D/[0]UMC:UMCAdmin( 2737): isContainer : 0
D/[0]UMC:UMCAdmin( 2737): deactivateUMCAdmin - UMC App Admin deactivated
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/MediaScanner( 1224): OK. alarm_alert is already exist in setting DB.
W/ResourcesManager( 2840): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     ( 1017): Explicit concurrent mark sweep GC freed 56146(3MB) AllocSpace objects, 20(506KB) LOS objects, 33% free, 26MB/39MB, paused 2.372ms total 173.640ms
E/Zygote  ( 2864): MountEmulatedStorage()
I/libpersona( 2864): KNOX_SDCARD checking this for 10150
E/Zygote  ( 2864): v2
I/libpersona( 2864): KNOX_SDCARD not a persona
I/SELinux ( 2864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/MediaScanner( 1224): system notification_sound  : K_Oprkltf5wgg
I/SELinux ( 2864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2864): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/MediaScanner( 1224): OK. notification_sound is already exist in setting DB.
I/ActivityManager( 1017): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=2864 uid=10150 gids={50150, 9997} abi=armeabi-v7a
D/MediaScanner( 1224): system ringtone  : Wmfi_lpf_pwirywu5wgg
I/DIAGMON_AGENT( 2820): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
D/MediaScanner( 1224): OK. ringtone is already exist in setting DB.
E/AffinityControl( 2816): AffinityControl: registerfunction enter
D/TimaKeyStoreProvider( 2864): TimaSignature is unavailable
D/ActivityThread( 2864): Added TimaKeyStore provider
D/FactoryTestApp( 2571): [DummyFtClient$mBroadcastReceiver](2571) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2571): [DummyFtClient$mBroadcastReceiver](2571) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/MediaScannerService( 1224): !@done scanning volume internal
D/FactoryTestApp( 2571): [DummyFtClient$mBroadcastReceiver](2571) ACTION_MEDIA_SCANNER_FINISHED = Ignored
D/Launcher.Model( 1493): reloadBadges entered.
D/BadgeProvider( 1583): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1583): sendNotify, [notify] : null
D/BadgeProvider( 1583): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1583): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1583): update, [UpdateCount] : 1
D/AndroidRuntime( 2816): Calling main entry com.android.commands.am.Am
D/[0]UMC:ByodSetupStarter( 2737): Container ID : 0
D/MediaScannerService( 1224): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/Mms/MessagingNotification( 2284): setBadgeCount(), count=0
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
V/[0]UMC:Utils( 2737): checkAppScreen() : com.sec.android.app.launcher
I/[0]UMC:Core( 2737): shutdown
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
D/[0]UMC:GuardService( 2737): @GuardService - stopService Result = true
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
D/Mms/MessagingNotification( 2284): remove alarm
I/art     ( 2737): System.exit called, status: 0
I/AndroidRuntime( 2737): VM exiting with result code 0, cleanup skipped.
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1017): Focused application set to: xxxx
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
D/InputDispatcher( 1017): Focus left window: 1493
D/Launcher.HomeView( 1493): onPause
D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 2816): Shutting down VM
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, iello
I/ActivityManager( 1017): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2737)(adj 0) has died(202,1008)
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1285): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1285): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/Zygote  ( 2885): MountEmulatedStorage()
E/Zygote  ( 2885): v2
I/libpersona( 2885): KNOX_SDCARD checking this for 10174
I/libpersona( 2885): KNOX_SDCARD not a persona
I/SELinux ( 2885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/FOTA    ( 2840): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2885 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/Mms/MessagingNotification( 2284): updateAllHistoryAsRead()
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
I/SELinux ( 2885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2885): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/MediaProvider( 1224): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1224): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1224): savePlaylistTableInBulkDeleter finished
D/comsamsunglog( 1285): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1285): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1285): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1285): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1285): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/MediaScanner( 1224): Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
V/ActivityThread( 1493): updateVisibility : ActivityRecord{3b3a7b03 token=android.os.BinderProxy@101825eb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/TimaKeyStoreProvider( 2885): TimaSignature is unavailable
D/ActivityThread( 2885): Added TimaKeyStore provider
D/SettingsProvider( 1017): name = aw_daemon_service_key_version_check
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10162
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/DIAGMON_AGENT( 2820): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
I/DIAGMON_AGENT( 2820): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
D/TP/SmsProvider( 1468): query,matched:0, calling pid = 2284
D/TP/SmsProvider( 1468): match 0:Elapsed time : 1.035 ms
I/ActivityManager( 1017): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=2902 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 1405:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
E/Zygote  ( 2902): MountEmulatedStorage()
E/Zygote  ( 2902): v2
I/libpersona( 2902): KNOX_SDCARD checking this for 1000
I/libpersona( 2902): KNOX_SDCARD not a persona
I/DIAGMON_AGENT( 2820): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10162
I/DIAGMON_AGENT( 2820): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2820): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 2820): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/SELinux ( 2902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/SELinux ( 2902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/DBG_DM  ( 2840): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
E/SELinux ( 2902): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 2816): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/Launcher.HomeView( 1493): onStop
D/Launcher( 1493): onTrimMemory. Level: 20
V/ActivityThread( 1493): updateVisibility : ActivityRecord{3b3a7b03 token=android.os.BinderProxy@101825eb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/DBG_DM  ( 2840): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/DBG_DM  ( 2840): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,D/PersonaManager( 1017): isKioskContainerExistOnDevice
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR,
D/daemonapp( 1285): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1285): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1017): [SO] activate (ident=0xb9197920, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/daemonapp( 1285): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!,
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 2902): TimaSignature is unavailable
,D/ActivityThread( 2902): Added TimaKeyStore provider
,E/Zygote  ( 2919): MountEmulatedStorage(),
E/Zygote  ( 2919): v2,
I/ActivityManager( 1017): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=2919 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/libpersona( 2919): KNOX_SDCARD checking this for 1000
I/libpersona( 2919): KNOX_SDCARD not a persona
D/SensorManager( 1017): unregisterListener ::   ,
I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 66000000(ns)
I/SELinux ( 2919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/SensorService( 1017): [SO] changed settle time [1]
D/SensorService( 1017): [SO] setDelay [66000000]
D/SensorService( 1017): [SO] activate (ident=0xb9107620, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/SELinux ( 2919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2919): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/MediaScanner( 1224): processDirectory :  /storage/emulated/0
E/USB_UICC(  300): Timeout! No signal received. Retry num = 26
D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1448315159894
D/Mms/SmsReceiverService( 2284): [end]    handleBootCompleted() consume time = 915.54776
,D/MediaScanner( 1224): Skipping:
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1448336700000
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1285): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
D/MediaScanner( 1224): 7klwibgf7fvntblfd7(75ebcf7
,I/ActivityManager( 1017): Killing 1388:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
,D/MediaScanner( 1224): Skipping:
D/MediaScanner( 1224): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,D/daemonapp( 1285): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1448336700000
,D/TimaKeyStoreProvider( 2919): TimaSignature is unavailable
D/ActivityThread( 2919): Added TimaKeyStore provider
,W/ResourcesManager( 2902): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,V/AlarmManager( 1017): waitForAlarm result :8
I/SecureStorage(  402): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
I/WebViewFactory( 2885): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_1405/cgroup.procs: No such file or directory
,V/MediaScanner( 1224): processDirectory :  /storage/extSdCard
W/MediaScanner( 1224): Error opening directory, reason : Permission denied.
W/MediaScanner( 1224): 7klwibgf7fxlKdCbid7
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,V/MediaScanner( 1224):  prescan time: 247ms (DB items: 27)
V/MediaScanner( 1224):     scan time: 103ms (Caching mode: true), (makeEntry time: 44ms ~42%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1224): postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1224):    total time: 353ms
V/MediaScanner( 1224): checked files: 10  directories : 17  (I: 0, U: 0)
,I/LibraryLoader( 2885): Time to load native libraries: 1 ms (timestamps 2258-2259)
I/LibraryLoader( 2885): Expected native library version number "",actual native library version number ""
,D/FactoryTestApp( 2571): [DummyFtClient$mBroadcastReceiver](2571) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2571): [DummyFtClient$mBroadcastReceiver](2571) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,D/FactoryTestApp( 2571): [DummyFtClient$sendBootCompletedAndFinish](2571) ...
D/FactoryTestApp( 2571): [Support$Values.getString](2571) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2571): [ModuleCommon$isConnectionModeNone](2571) mConnectionMode = gsm
D/FactoryTestApp( 2571): [IPCWriterToSecPhoneService$ResponseWriter](2571) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2571): [IPCWriterToSecPhoneService$connectToSecPhoneService](2571)  
D/MediaScannerService( 1224): !@done scanning volume external
D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/accuweather( 1566): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
D/accuweather( 1566): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1566): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock,
D/accuweather( 1566): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1566): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1566): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1566): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1566): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1566): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1566): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 22 46
,I/SecureStorage( 2720): [INFO]: SPID(0x00000001)Processing data has been completed
,I/SecureStorage( 2720): [INFO]: SPID(0x00000001)Skip using SecureStorageExceptionJNI
,D/SensorService( 1017): [SO] currT = 32291059000, prevT = 31951107000, diff = 339952000, [0.192 0.096 10.228]
D/SensorService( 1017): [SO] 0.192 0.096 10.228
D/SensorService( 1017): [SO] 0.192 0.096 10.228
D/SensorService( 1017): [SO] [100 -> 255]
,W/libprocessgroup( 1017): failed to open /acct/uid_10096/pid_1388/cgroup.procs: No such file or directory
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 156
,D/daemonapp( 1285): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1448336700000
,I/DBG_DM  ( 2840): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 2840): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 2840): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 2840): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 2840): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_DM  ( 2840): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,I/DBG_DM  ( 2840): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,D/OverheatReceiver( 1179): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1179): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1179): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1179): isSafeMode = false
,I/DBG_DM  ( 2840): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 2840): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 2840): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,D/BootupListener( 1468): intent.getAction() = android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 2840): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,D/SettingsProvider( 1017): name = internet_call_settings_visibility
,I/DBG_DM  ( 2840): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1001
I/DBG_DM  ( 2840): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
I/DBG_DM  ( 2840): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/DBG_DM  ( 2840): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
D/SettingsProvider( 1017): ret = -1
D/PhoneUtilsCommon( 1468): isSupportVoLTE is false.
I/DBG_DM  ( 2840): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
I/DBG_DM  ( 2840): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DBG_DM  ( 2840): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/Telecom ( 1434): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
I/DBG_DM  ( 2840): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,I/DBG_DM  ( 2840): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DBG_DM  ( 2840): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,I/DBG_DM  ( 2840): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/Telecom ( 1434): InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/iu.UploadsManager( 1853): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 2571): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2840): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,W/ContextImpl( 2840): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 ,
,E/Zygote  ( 2941): MountEmulatedStorage()
I/libpersona( 2941): KNOX_SDCARD checking this for 10012
E/Zygote  ( 2941): v2
I/libpersona( 2941): KNOX_SDCARD not a persona
I/SELinux ( 2941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 2941): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1017): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=2941 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
V/WebViewChromiumFactoryProvider( 2885): Binding Chromium to main looper Looper (main, tid 1) {23d2214a}
,I/LibraryLoader( 2885): Expected native library version number "",actual native library version number ""
,I/chromium( 2885): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0,
I/Telecom ( 1434): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
I/Telecom ( 1434): InCallController: Unbinding from InCallService unbind
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/comdaemonstockapp( 1285): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 1285): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/TimaKeyStoreProvider( 2941): TimaSignature is unavailable
,D/ActivityThread( 2941): Added TimaKeyStore provider
,I/BrowserStartupController( 2885): Initializing chromium process, singleProcess=true
,W/art     ( 2885): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2885): ApplicationContext is null in ApplicationStatus
,E/Zygote  ( 2958): MountEmulatedStorage()
E/Zygote  ( 2958): v2
I/libpersona( 2958): KNOX_SDCARD checking this for 10086
I/libpersona( 2958): KNOX_SDCARD not a persona
,I/SELinux ( 2958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 2958): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2958 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/chromium( 2885): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
,D/TimaKeyStoreProvider( 2958): TimaSignature is unavailable
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/8)
D/ActivityThread( 2958): Added TimaKeyStore provider
,E/Zygote  ( 2973): MountEmulatedStorage(),
E/Zygote  ( 2973): v2
I/libpersona( 2973): KNOX_SDCARD checking this for 10003
I/libpersona( 2973): KNOX_SDCARD not a persona
,I/SELinux ( 2973): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 2973): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=2973 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
E/SELinux ( 2973): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 2840): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,I/FactoryTestApp( 2571): [IPCWriterToSecPhoneService$onServiceConnected](2571) connected done
,D/FactoryTestApp( 2571): [IPCWriterToSecPhoneService$write](2571) Send Response Message to SecPhone
,D/FactoryTestApp( 2571): [IPCWriterToSecPhoneService$write](2571) Response ��
,D/TimaKeyStoreProvider( 2973): TimaSignature is unavailable
,D/ActivityThread( 2973): Added TimaKeyStore provider
,W/ResourcesManager( 2941): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2941): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AT_Distributor(  325): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/FactoryTestApp( 2571): [IPCWriterToSecPhoneService$handleMessage](2571) Send BOOTING COMPLETED done
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/chromium( 2885): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2885): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2885): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2885): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2885): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2885): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2885): Local Branch: 
I/Adreno-EGL( 2885): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2885): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2885):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/MultiDex( 2941): VM with version 2.1.0 has multidex support
I/MultiDex( 2941): install
I/MultiDex( 2941): VM has multidex support, MultiDex support library is disabled.
,I/DBG_DM  ( 2840): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,I/iu.UploadsManager( 1853): End new media; added: 0, uploading: 0, time: 149 ms
,V/JNIHelp ( 2941): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ContextImpl( 1885): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,V/audio_hw_primary(  283): adev_get_parameters: enter: keys - call_forwarding
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/audio_hw_extn(  283): audio_extn_get_parameters: returns 
V/msm8974_platform(  283): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  283): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  283): key: 'call_forwarding' value: ''
,V/InCall  ( 1895): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1895): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1895): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/SecUISvc( 1885): Service started flags 0 startId 1
,D/ScoverManager( 1895): serviceVersion : 16908288,
D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1895): InCallUtils - isCoverClosed false
D/AT_Distributor(  325): SetAtdStatus(), 1_1_0
,D/AT_Distributor(  325): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
I/Telecom ( 1434): ProximitySensorManager: Proximity wake lock already released
D/SecUISvc( 1885): Thread created.
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/InCall  ( 1895): InCallUtils - isCoverClosed false
,I/InCall  ( 1895): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1895): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS,
D/InCall  ( 1895): InCallPresenter -  - dismissCoverDialog()...
,I/InCall  ( 1895): CallSContextMotion - stopPutDownListening
,D/InCall  ( 1895): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
I/libpersona( 3005): KNOX_SDCARD checking this for 10028
E/Zygote  ( 3005): MountEmulatedStorage()
I/libpersona( 3005): KNOX_SDCARD not a persona
E/Zygote  ( 3005): v2
I/SELinux ( 3005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/PhoneStatusBarView( 1179): setCallBackground:0
,I/SELinux ( 3005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3005): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,I/ActivityManager( 1017): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3005 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/InCall  ( 1895): InCallUtils - isCoverClosed false
,W/ActivityThread( 2941): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 2941): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e8da075: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2941): Installed default security provider GmsCore_OpenSSL
,D/TimaKeyStoreProvider( 3005): TimaSignature is unavailable
,D/ActivityThread( 3005): Added TimaKeyStore provider
,D/BluetoothAdapter( 2885): 228808087: getState() :  mService = null. Returning STATE_OFF
,D/UserAnalysis.PlaceProvider( 2973): PlaceProvider onCreate()
,I/ActivityManager( 1017): Killing 1653:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,D/UserAnalysis.SecureDbManager( 2973): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 2973): SecurePlaceDbHelper() 
D/UserAnalysis( 2973): Create SecureDbHelper
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3028): MountEmulatedStorage(),
E/Zygote  ( 3028): v2
I/libpersona( 3028): KNOX_SDCARD checking this for 10009
I/libpersona( 3028): KNOX_SDCARD not a persona
,I/SELinux ( 3028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3028 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3028): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/VideoCallManager( 1895): Instantiating VideoCallManager
,E/        ( 1895): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1895): took 2.595000ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1895): took 5.405313ms for 0*0 texture 0
,E/UpdateRequestReceiver( 2958): ignoring update request
D/TimaKeyStoreProvider( 3028): TimaSignature is unavailable
,I/GFX raster( 1895): took 12.013646ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1895): Bitmap=0xb8d71758 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8d71028 counterpartCT=4 counterpartW=176 counterparth=144
,D/ActivityThread( 3028): Added TimaKeyStore provider
,E/        ( 1895): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1895): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1895): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1895): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1895): Local Branch: 
I/Adreno-EGL( 1895): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1895): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1895):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/UpdateRequestReceiver( 2958): ignoring update request
,D/IntelligenceServiceApplication( 2973): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 2973): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/BluetoothHeadset( 2720): BTStateChangeCB is registed
,D/BluetoothHeadset( 2720): doBind(): CallingUid(myUserHandle) = 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/GFX GPU raster( 1895): eglCreateImageKHR: EGL_SUCCESS
,E/Zygote  ( 3048): MountEmulatedStorage(),
I/libpersona( 3048): KNOX_SDCARD checking this for 10060
E/Zygote  ( 3048): v2
I/libpersona( 3048): KNOX_SDCARD not a persona
,I/SELinux ( 3048): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/glCompressedTexImage2D( 1895): took 0.452291ms for 320*61440 texture 37809
,I/SELinux ( 3048): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3048): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/UpdateRequestReceiver( 2958): ignoring update request
,I/ActivityManager( 1017): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3048 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/draw setup( 1895): took 10.546874ms for 320*240 texture 37809
,E/GFX GPU raster( 1895): drawn
,I/ActivityManager( 1017): Killing 1536:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,I/GFX GPU raster ASTC( 1895): took 42.022759ms for 320*240 texture 12
I/GFX raster( 1895): took 42.104008ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1895): Bitmap=0xb8d716d8 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8d71240 counterpartCT=4 counterpartW=320 counterparth=240
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,D/IntelligenceServiceApplication( 2973): no applications having user consent for prediction
E/BluetoothHeadset( 2720): BluetoothHeadset service is binded
,I/art     (  307): Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 26.573ms
E/        ( 1895): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,D/BluetoothA2dp( 2720): doBind(): CallingUid(myUserHandle) = 0
I/GFX GPU raster( 1895): eglCreateImageKHR: EGL_SUCCESS
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,I/glCompressedTexImage2D( 1895): took 0.515469ms for 480*122880 texture 37813,
I/draw setup( 1895): took 1.131407ms for 480*640 texture 37813
E/GFX GPU raster( 1895): drawn
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,D/TimaKeyStoreProvider( 3048): TimaSignature is unavailable
D/ActivityThread( 3048): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 804us total 19.438ms
,I/GFX GPU raster ASTC( 1895): took 7.693281ms for 480*640 texture 12
I/GFX raster( 1895): took 7.767084ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1895): Bitmap=0xb8d71240 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8f9e8f0 counterpartCT=4 counterpartW=480 counterparth=640
,D/BluetoothAdapter( 2720): 1018407504: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2720): 1018407504: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2720): 1018407504: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2720): 1018407504: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2720): 1018407504: getState() :  mService = null. Returning STATE_OFF
,E/UpdateRequestReceiver( 2958): ignoring update request
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 18.222ms
,E/UpdateRequestReceiver( 2958): ignoring update request
,E/UpdateRequestReceiver( 2958): ignoring update request
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/        ( 1895): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1895): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1895): took 0.349636ms for 440*116864 texture 37809,
I/draw setup( 1895): took 1.188021ms for 440*330 texture 37809,
E/GFX GPU raster( 1895): drawn
,I/GFX GPU raster ASTC( 1895): took 4.870625ms for 440*330 texture 12
I/GFX raster( 1895): took 4.941198ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1895): Bitmap=0xb8fa2b48 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8fa2f08 counterpartCT=4 counterpartW=440 counterparth=330
,E/Zygote  ( 3070): MountEmulatedStorage()
I/libpersona( 3070): KNOX_SDCARD checking this for 10094
E/Zygote  ( 3070): v2
I/libpersona( 3070): KNOX_SDCARD not a persona
I/SELinux ( 3070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3070 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Killing 2088:com.vlingo.midas/u0a31 (adj 15): empty #31
E/SELinux ( 3070): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 1895): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1895): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1895): took 0.432917ms for 480*163840 texture 37811
I/draw setup( 1895): took 1.038229ms for 480*640 texture 37811
E/GFX GPU raster( 1895): drawn
,D/TimaKeyStoreProvider( 3070): TimaSignature is unavailable
,D/ActivityThread( 3070): Added TimaKeyStore provider
,I/GFX GPU raster ASTC( 1895): took 6.111405ms for 480*640 texture 12
I/GFX raster( 1895): took 6.184479ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1895): Bitmap=0xb8fe2518 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb8f9e6a8 counterpartCT=4 counterpartW=480 counterparth=640
,I/DBG_DM  ( 2840): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,W/libprocessgroup( 1017): failed to open /acct/uid_10138/pid_1653/cgroup.procs: No such file or directory
,D/elm:15183( 3070): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15183( 3070): ELMEngine.ELMEngine( context ).
,D/elm:15183( 3070): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 3070): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15183( 3070): ElmAgentService : onCreate()
,D/elm:15183( 3070): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 3070): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15183( 3070): BootCompletedState : startBootCompleted() call
,D/elm:15183( 3070): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15183( 3070): Get License : 0
D/elm:15183( 3070): ElmAgentService : onDestroy().
,V/EmergencyMode( 1421): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,W/art     ( 2885): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager( 1017): Killing 2112:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1017): failed to open /acct/uid_10057/pid_1536/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10031/pid_2088/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,V/PlaceDetection v1.0.19 ( 2973): [PlaceDetection::stopService] Service stopped.
,I/DBG_DM  ( 2840): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 2840): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 2840): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,E/USB_UICC(  300): Timeout! No signal received. Retry num = 27
,I/ActivityManager( 1017): Killing 2127:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,E/        ( 1895): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1895): took 2.185469ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1895): took 7.566979ms for 0*0 texture 0
,I/GFX raster( 1895): took 11.704323ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1895): Bitmap=0xb8fa2ac8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8f9c108 counterpartCT=4 counterpartW=176 counterparth=144
,E/        ( 1895): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1895): took 2.252135ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1895): took 6.227550ms for 0*0 texture 0
,I/GFX raster( 1895): took 10.559999ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1895): Bitmap=0xb8f9c170 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8f9c2f8 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1895): registerListener
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManagerWhiteLists( 1017): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1017): registerListenerCallback : binder = android.os.BinderProxy@23a5fd5b, pid : 1895, uid : 1001, type : 1
,I/sCloudBackupApp( 3048): sCloudBackupApp Version Info : 4.04.8.KK_APP
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3100): MountEmulatedStorage()
E/Zygote  ( 3100): v2
I/libpersona( 3100): KNOX_SDCARD checking this for 10062
I/libpersona( 3100): KNOX_SDCARD not a persona
,I/SELinux ( 3100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
W/AwContents( 2885): onDetachedFromWindow called when already detached. Ignoring
,I/SELinux ( 3100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3100): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1017): failed to open /acct/uid_10050/pid_2112/cgroup.procs: No such file or directory
,D/PhoneWindow( 2885): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 2885): *FMB* installDecor flags : 8456448
,I/ActivityManager( 1017): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3100 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 1508:com.android.printspooler/u0a136 (adj 15): empty #31
D/SystemWebViewEngine( 2885): CordovaWebView is running on device made by: samsung
W/art     ( 2885): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2885): Attempt to remove local handle scope entry from IRT, ignoring
D/InCall  ( 1895): InCallPresenter -  - Finished InCallPresenter.setUp
V/PlaceDetection v1.0.19 ( 2973): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/UserAnalysis.MyPlaceDbPreference( 2973): Constructor Preference
D/TimaKeyStoreProvider( 3100): TimaSignature is unavailable
D/ActivityThread( 3100): Added TimaKeyStore provider
,I/DBG_POLICYDM( 2919): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 2919): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 2919): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 2919): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/DBG_POLICYDM( 2919): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 2919): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 2919): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,D/OpenGLRenderer( 2885): Render dirty regions requested: true
I/DBG_POLICYDM( 2919): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 2919): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 2919): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 2919): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/chromium( 2885): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/DBG_POLICYDM( 2919): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 2919): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 2919): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,D/PhoneWindow( 2885): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 2885): *FMB* isFloatingMenuEnabled return false
,I/DBG_POLICYDM( 2919): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 2919): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,I/DBG_POLICYDM( 2919): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 2919): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,W/libprocessgroup( 1017): failed to open /acct/uid_10113/pid_2127/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 2919): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 2919): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,W/libprocessgroup( 1017): failed to open /acct/uid_10136/pid_1508/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 2919): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,I/DBG_POLICYDM( 2919): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,D/InputDispatcher( 1017): Focus entered window: 2885
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2885): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 2885): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2885): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 2885): Enabling debug mode 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3127): MountEmulatedStorage()
E/Zygote  ( 3127): v2
I/libpersona( 3127): KNOX_SDCARD checking this for 1000
I/libpersona( 3127): KNOX_SDCARD not a persona
,I/ExternalOEMControlProvider( 3100): onCreate
,I/SELinux ( 3127): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3127): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3127): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3127 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2302:com.sec.android.omc/1000 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 2263:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #32
,I/ActivityManager( 1017): Killing 1706:com.google.android.partnersetup/u0a15 (adj 15): empty #33
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1179): There is/are notification(s) 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1017): Displayed Component not be shown by security: +1s667ms
,I/Timeline( 2885): Timeline: Activity_idle id: android.os.BinderProxy@1f01a2c6 time:33528
,I/SamsungIME( 1787): getCurrentCandidateView
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{2160b7a8 u0 com.example.hello/.MainActivity t228} time:33547
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3127): TimaSignature is unavailable
,D/ActivityThread( 3127): Added TimaKeyStore provider
,E/Zygote  ( 3145): MountEmulatedStorage()
E/Zygote  ( 3145): v2
I/libpersona( 3145): KNOX_SDCARD checking this for 1000
I/libpersona( 3145): KNOX_SDCARD not a persona
,I/SELinux ( 3145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3145): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3145 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2315:com.sec.modem.settings/1000 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2263/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3145): TimaSignature is unavailable
,D/ActivityThread( 3145): Added TimaKeyStore provider
,W/ResourcesManager( 3145): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/DBG_FMMDM( 3127): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_FMMDM( 3127): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3127): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3127): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 3005): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/Zygote  ( 3162): MountEmulatedStorage()
E/Zygote  ( 3162): v2
I/libpersona( 3162): KNOX_SDCARD checking this for 1000
I/libpersona( 3162): KNOX_SDCARD not a persona
,I/SELinux ( 3162): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3162 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 3162): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3162): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 2919): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 2919): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 2919): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,D/TimaKeyStoreProvider( 3162): TimaSignature is unavailable
,D/ActivityThread( 3162): Added TimaKeyStore provider
,E/DBG_POLICYDM( 2919): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,V/EmergencyMode( 1421): [EmergencyBase] setBootTime
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2302/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10015/pid_1706/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2315/cgroup.procs: No such file or directory
,V/EmergencyMode( 1421): [EmergencyFactory] No Recovery State, kill my self.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/SamsungIME( 1787): Dismiss ExpandCandiate
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 19814(1023KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/39MB, paused 2.659ms total 158.921ms,
,E/Zygote  ( 3179): MountEmulatedStorage(),
I/libpersona( 3179): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3179): v2
I/libpersona( 3179): KNOX_SDCARD not a persona
D/SettingsProvider( 1017): name = PREVIOUS_SYS_TIME,
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
I/ActivityManager( 1017): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3179 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10062
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/SELinux ( 3179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SurfaceFlinger(  257): id=10 Removed iello (7/8),
I/SurfaceFlinger(  257): id=10 Removed iello (-2/8)
I/SELinux ( 3179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3179): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/SettingsProvider( 1017): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10062
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,D/TimaKeyStoreProvider( 3179): TimaSignature is unavailable
,D/ActivityThread( 3179): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/ServiceMode( 3145): received = ACTION_BOOT_COMPLETED
,I/ServiceMode( 3145): setReferenceIsDumpState : 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3197): MountEmulatedStorage()
I/libpersona( 3197): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3197): v2
I/libpersona( 3197): KNOX_SDCARD not a persona
I/SELinux ( 3197): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3197 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2332:com.sec.tcpdumpservice/1000 (adj 15): empty #31
I/SELinux ( 3197): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/SamsungIME( 1787): getDebugLevel  : 0x4f4c
E/SELinux ( 3197): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,I/PCWCLIENTTRACE_LOG( 3162): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3162): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3162): new DMDBOpenHelper instance
,D/TimaKeyStoreProvider( 3197): TimaSignature is unavailable
,D/ActivityThread( 3197): Added TimaKeyStore provider
,D/PCWCLIENTTRACE_DMContentProvider( 3162): [URIMatcher] - result : 2
,W/BindingManager( 2885): Cannot call determinedVisibility() - never saw a connection for the pid: 2885
,I/DBG_FMMDM( 3127): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3127): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3127): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3214): MountEmulatedStorage()
E/Zygote  ( 3214): v2
I/libpersona( 3214): KNOX_SDCARD checking this for 1000
I/libpersona( 3214): KNOX_SDCARD not a persona
I/SELinux ( 3214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3214 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3214): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 2420:com.wsomacp/u0a25 (adj 15): empty #31
I/ActivityManager( 1017): Killing 2347:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #32
,I/CameraApp( 3179): CameraApp.onCreate()... mFeature : null
I/testFeature( 3179): Feature.Feature(context)
I/testFeature( 3179): Feature.readInternalDefaultXml()
I/testFeature( 3179): ResetFeatureValue
I/CameraFirmware_broadcast( 3179): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3179): CameraApp.getAppFeature()...
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/NPS_WSSNPS( 3197): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3197): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,D/TimaKeyStoreProvider( 3214): TimaSignature is unavailable
,D/ActivityThread( 3214): Added TimaKeyStore provider
,E/Zygote  ( 3229): MountEmulatedStorage()
E/Zygote  ( 3229): v2
I/libpersona( 3229): KNOX_SDCARD checking this for 10100
I/libpersona( 3229): KNOX_SDCARD not a persona
,I/SELinux ( 3229): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3229 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 2438:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/SELinux ( 3229): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3229): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3197): [] Service onCreate!!
,D/TimaKeyStoreProvider( 3229): TimaSignature is unavailable
I/chromium( 2885): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/ActivityThread( 3229): Added TimaKeyStore provider
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3245): MountEmulatedStorage()
I/libpersona( 3245): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3245): v2
I/libpersona( 3245): KNOX_SDCARD not a persona
I/SELinux ( 3245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3245): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3245 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/NPS_WSSNPS( 3197): [50.150321] NpsServiceTask Start
,I/ActivityManager( 1017): Killing 2465:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2332/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10131/pid_2347/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10025/pid_2420/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3245): TimaSignature is unavailable
,D/ActivityThread( 3245): Added TimaKeyStore provider
,D/PackageIntentReceiver( 3229): ACTION_BOOT_COMPLETED
,I/DBG_FMMDS( 3214): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,D/PackageIntentReceiver( 3229): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,I/ActivityManager( 1017): Killing 2486:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,D/NPS_WSSNPS( 3197): [50.150321] smlDBHelper
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DBG_FMMDS( 3214): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,I/GoogleHttpClient( 1670): GMS http client unavailable, use old client
,E/Zygote  ( 3274): MountEmulatedStorage()
I/libpersona( 3274): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3274): v2
I/libpersona( 3274): KNOX_SDCARD not a persona
,I/SELinux ( 3274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3274): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3274 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SMD     (  291): DCD OFF
D/Finsky  ( 3005): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/PCWCLIENTTRACE_DMContentProvider( 3162): [URIMatcher] - result : 2
,I/art     (  307): Explicit concurrent mark sweep GC freed 8798(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 677us total 25.895ms
,D/SettingsProvider( 1017): name = access_control_enabled
,E/DBG_FMMDS( 3214): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
E/USB_UICC(  300): Timeout! No signal received. Retry num = 28
,I/NPS_WSSNPS( 3197): [50.150321] AsyncBulkFlagCheck
,D/TimaKeyStoreProvider( 3274): TimaSignature is unavailable
,D/ActivityThread( 3274): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 17.365ms
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SamsungIME( 1787): getDebugLevel  : 0x4f4c
,W/libprocessgroup( 1017): failed to open /acct/uid_10044/pid_2438/cgroup.procs: No such file or directory
,I/DBG_DM  ( 2840): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,W/libprocessgroup( 1017): failed to open /acct/uid_10139/pid_2486/cgroup.procs: No such file or directory
I/NPS_WSSNPS( 3197): [50.150321] IsRemain_AsyncBulkCheck
,W/libprocessgroup( 1017): failed to open /acct/uid_10142/pid_2465/cgroup.procs: No such file or directory
,E/Tethering( 1017): No numeric data
,I/NPS_WSSNPS( 3197): [50.150321] IsRemain_Asyncing nothing
W/ContextImpl( 3197): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 686us total 17.238ms
,I/DBG_FMMDS( 3214): [50.18.150420][Line:43][xdbDBInit] 
,I/SamsungIME( 1787): KeybaordView init() : load resources
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
E/Zygote  ( 3293): MountEmulatedStorage()
E/Zygote  ( 3293): v2
I/libpersona( 3293): KNOX_SDCARD checking this for 10069
,I/libpersona( 3293): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3293 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3293): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,I/SELinux ( 3293): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/Tethering( 1017): No numeric data
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,E/SELinux ( 3293): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/Tethering( 1017): No numeric data
,D/NPS_WSSNPS( 3197): [50.150321] Service onDestroy
I/NPS_WSSNPS( 3197): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3197): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 3197): [50.150321] smlBREmailDelete
I/NPS_WSSNPS( 3197): [50.150321] smlBRNetworkDelete
I/NPS_WSSNPS( 3197): [50.150321] smlBRCallLogDelete
,I/NPS_WSSNPS( 3197): [50.150321] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3197): [50.150321] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3197): [50.150321] smlBRSMemoDelete
,D/TimaKeyStoreProvider( 3293): TimaSignature is unavailable
,I/NPS_WSSNPS( 3197): [50.150321] cpuBooster release : false
D/ActivityThread( 3293): Added TimaKeyStore provider
,D/JsMessageQueue( 2885): Set native->JS mode to OnlineEventsBridgeMode
,D/NPS_WSSNPS( 3197): [50.150321] dsServerSocket close
,I/ActivityManager( 1017): Killing 2254:com.sec.android.app.mt/1000 (adj 15): empty #31
,E/AndroidProtocolHandler( 2885): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/FileShare-Server( 3293): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/[SBeam] ( 1306): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1306): SBeamEnabler.isSBeamSupported : EXIST
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/SamsungIME( 1787): getCurrentKeyboard,
I/SamsungIME( 1787): getTextKeyboard
,I/ActivityManager( 1017): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3310 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 3310): MountEmulatedStorage()
E/Zygote  ( 3310): v2
,I/libpersona( 3310): KNOX_SDCARD checking this for 1000,
I/SELinux ( 3310): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 3310): KNOX_SDCARD not a persona
,W/Settings( 3005): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SELinux ( 3310): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2254/cgroup.procs: No such file or directory
E/SELinux ( 3310): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Settings( 3005): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,E/Tethering( 1017): No numeric data
,D/TimaKeyStoreProvider( 3310): TimaSignature is unavailable
,D/ActivityThread( 3310): Added TimaKeyStore provider
,E/Tethering( 1017): No numeric data
,D/SamsungIME( 1787): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/DBG_FMMDS( 3214): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,W/NotificationAccessSettings( 1306): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,D/KnoxSetupWizardDbHelper( 3310): dbMigrationFlag : false
,D/Volley  ( 3005): [386] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1017): Killing 2551:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/Volley  ( 3005): [393] DiskBasedCache.clear: Cache cleared.
,W/ResourcesManager( 1306): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 3005): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3005): [1] 2.run: Finished loading 1 libraries.
,V/GLSUser ( 1670): [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,D/ShortcutReceiver( 3310):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2551/cgroup.procs: No such file or directory
,I/DBG_FMMDS( 3214): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3214): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,D/ScoverManager( 1306): serviceVersion : 16908288
,I/DBG_FMMDS( 3214): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3214): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3214): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3214): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,V/GmsCoreStatsServiceLauncher( 1853): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,D/KnoxShortcutUtil( 3310): getIsShortcutMigrationFor_2_3_0_Done true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ShortcutReceiver( 3310):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 3310):  shortcut migration not required 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/NotificationStore( 1670): System rebooted after Notification storage file was last written
I/NotificationStore( 1670): Deleting the file
,E/Zygote  ( 3340): MountEmulatedStorage(),
E/Zygote  ( 3340): v2
I/libpersona( 3340): KNOX_SDCARD checking this for 1000,
I/SELinux ( 3340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 3340): KNOX_SDCARD not a persona
,I/SELinux ( 3340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3340 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3340): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2536:com.android.calendar/u0a135 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 2603:com.android.keychain/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3340): TimaSignature is unavailable
D/ActivityThread( 3340): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/FOTA_Client( 3028): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/jxcore_app_log( 2885): JniHelper::setJavaVM(0xb89cd450), pthread_self() = -1192090008
,D/JX-Cordova( 2885): jxcore cordova android initializing
,D/PersistentNotificationBroadcastReceiver( 1670): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/FOTA_Client( 3028): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/KnoxSetupWizardClient( 3340): isShipMode : 1
I/KnoxSetupWizardClient( 3340): onReceive : android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3364): MountEmulatedStorage(),
E/Zygote  ( 3364): v2
I/libpersona( 3364): KNOX_SDCARD checking this for 10014
,I/libpersona( 3364): KNOX_SDCARD not a persona
,I/SELinux ( 3364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3364): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3364 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2664:flipboard.boxer.app/u0a99 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2603/cgroup.procs: No such file or directory
,W/jxcore-log( 2885): Initializing JXcore engine
W/jxcore-log( 2885): JXcore engine is ready
,W/jxcore-log( 2885): Starting JXcore engine
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3379): MountEmulatedStorage(),
,E/Zygote  ( 3379): v2
I/libpersona( 3379): KNOX_SDCARD checking this for 1000
I/SELinux ( 3379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 3379): KNOX_SDCARD not a persona
,I/SELinux ( 3379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3379): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3379 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2182:flipboard.app/u0a98 (adj 15): empty #31
,I/ActivityManager( 1017): Killing 2698:com.sec.usbsettings/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3364): TimaSignature is unavailable
,D/ActivityThread( 3364): Added TimaKeyStore provider
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,D/Finsky  ( 3005): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ContextImpl( 1017): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,D/TimaKeyStoreProvider( 3379): TimaSignature is unavailable
,D/ActivityThread( 3379): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3396): MountEmulatedStorage()
E/Zygote  ( 3396): v2
I/libpersona( 3396): KNOX_SDCARD checking this for 1000
I/libpersona( 3396): KNOX_SDCARD not a persona
,I/SELinux ( 3396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3396 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 3396): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Finsky  ( 3005): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/audit   ( 1850): type=1400 msg=audit(1448315162.666:203): avc:  denied  { ioctl } for  pid=2885 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1850):  SEPF_SM-A500FU_5.0.2_0027
E/audit   ( 1850): type=1300 msg=audit(1448315162.666:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=4 a3=be87bd58 items=0 ppid=307 ppcomm=main pid=2885 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1850): type=1320 msg=audit(1448315162.666:203): 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/TimaKeyStoreProvider( 3396): TimaSignature is unavailable
,D/ActivityThread( 3396): Added TimaKeyStore provider
,V/OneTimeInitializerReceiver( 3364): OneTimeInitializerReceiver.onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/System.err( 3340): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 3340): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3340): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3340): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3340): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3340): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3340): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/OneTimeService( 3364): OneTimeService.onHandleIntent
,E/Zygote  ( 3418): MountEmulatedStorage()
E/Zygote  ( 3418): v2
I/libpersona( 3418): KNOX_SDCARD checking this for 10015
I/libpersona( 3418): KNOX_SDCARD not a persona
,I/SELinux ( 3418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3418): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1017): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3418 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2284:com.android.mms/u0a46 (adj 15): empty #31
,D/StatusChecker( 3379): onReceive : android.intent.action.BOOT_COMPLETED
,I/ActivityManager( 1017): Killing 2755:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3418): TimaSignature is unavailable
,D/ActivityThread( 3418): Added TimaKeyStore provider
,I/StatusChecker( 3379): onReceive : net.mt.init : DONE
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_2536/cgroup.procs: No such file or directory
,E/Zygote  ( 3436): MountEmulatedStorage()
E/Zygote  ( 3436): v2
I/libpersona( 3436): KNOX_SDCARD checking this for 10116
I/libpersona( 3436): KNOX_SDCARD not a persona
,I/SELinux ( 3436): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3436): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3436): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3436 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 2774:com.sec.dsm.system/1000 (adj 15): empty #31
,W/jxcore-log( 2885): Platform android
W/jxcore-log( 2885): 
,W/jxcore-log( 2885): Process ARCH arm
W/jxcore-log( 2885): 
,D/TimaKeyStoreProvider( 3436): TimaSignature is unavailable
,D/ActivityThread( 3436): Added TimaKeyStore provider
,V/Finsky  ( 3005): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/ContextImpl( 3396): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/jxcore-log( 2885): JXcore Cordova bridge is ready!
I/jxcore-log( 2885): 
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/jxcore-log( 2885): JXcore engine is started
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/InstanceID/Rpc( 1853): Found 10012
,E/USB_UICC(  300): Timeout! No signal received. Retry num = 29
,I/DBG_DM  ( 2840): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
E/Zygote  ( 3452): MountEmulatedStorage()
I/libpersona( 3452): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3452): v2
I/libpersona( 3452): KNOX_SDCARD not a persona
,I/SELinux ( 3452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/CountryDetector( 1017): No listener is left
E/SELinux ( 3452): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3452 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/PageBuddyNotiSvc( 3436): Intent received : action=android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/jxcore-log( 2885): >> samsung-SM-A500FU
E/jxcore-log( 2885): 
,I/jxcore-log( 2885): Total memory 1983787008
I/jxcore-log( 2885): 
,I/jxcore-log( 2885): Free memory 147771392
I/jxcore-log( 2885): 
I/jxcore-log( 2885): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2885): 
I/jxcore-log( 2885): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2885): 
,D/TimaKeyStoreProvider( 3452): TimaSignature is unavailable
,D/ActivityThread( 3452): Added TimaKeyStore provider
,I/jxcore-log( 2885): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2885): 
,I/jxcore-log( 2885): Size 720 1280
I/jxcore-log( 2885): 
,I/jxcore-log( 2885): Screen Brightness 5
I/jxcore-log( 2885): 
,E/jxcore-log( 2885): Dummy Error Log.
E/jxcore-log( 2885): 
,W/ContextImpl( 3436): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/PageBuddyNotiSvc( 3436): onCreate mCpBitFlag=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/LockPatternUtils( 1306): isSmartCardAuthenticationAvailable: false
,W/ResourcesManager( 3452): Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,E/Zygote  ( 3469): MountEmulatedStorage()
I/libpersona( 3469): KNOX_SDCARD checking this for 10125
E/Zygote  ( 3469): v2
I/libpersona( 3469): KNOX_SDCARD not a persona
,I/SELinux ( 3469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,I/SELinux ( 3469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3469): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3469 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/Settings_Utils( 1306): isSupportVNFestival SM-A500FU XEO
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 3469): TimaSignature is unavailable
,W/libprocessgroup( 1017): failed to open /acct/uid_10099/pid_2664/cgroup.procs: No such file or directory
,D/ActivityThread( 3469): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2698/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2774/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10048/pid_2755/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10046/pid_2284/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10098/pid_2182/cgroup.procs: No such file or directory
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3469): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3469): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3469): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 3492): MountEmulatedStorage(),
I/libpersona( 3492): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3492): v2
I/libpersona( 3492): KNOX_SDCARD not a persona
,I/SELinux ( 3492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,E/SELinux ( 3492): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3492 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 8788(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 801us total 22.571ms
,D/TimaKeyStoreProvider( 3492): TimaSignature is unavailable
D/ActivityThread( 3492): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 688us total 18.030ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 742us total 17.926ms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3492): onCreate
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/QuickConnect( 3469): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 3469): Util.setSCRunningSetting - [value]0
,E/Zygote  ( 3508): MountEmulatedStorage()
E/Zygote  ( 3508): v2
I/libpersona( 3508): KNOX_SDCARD checking this for 10019
,I/libpersona( 3508): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3508 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3508): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/SELinux ( 3508): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3508): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1017): name = scon_is_running
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10125
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 3508): TimaSignature is unavailable
,D/ActivityThread( 3508): Added TimaKeyStore provider
I/Hs20UtilService( 3492): Starting #1
,I/Hs20UtilService( 3492): Message received 5003
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/QuickConnect( 3469): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/QuickConnect( 3469): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3528): MountEmulatedStorage()
I/libpersona( 3528): KNOX_SDCARD checking this for 10131
,E/Zygote  ( 3528): v2
I/libpersona( 3528): KNOX_SDCARD not a persona
I/SELinux ( 3528): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3528 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 3528): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Killing 2800:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,E/SELinux ( 3528): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3528): TimaSignature is unavailable
,D/ActivityThread( 3528): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3508): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Nov 23 22:46:03 GMT+01:00 2015
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/RlzPingService( 3418): Setting next ping for 1448919963334
,E/TLC_TZ_KEYSTORE: ( 1017): Inside TZ_KEYSTORE_initialize()
D/TimaService( 1017): TIMA: in getTimaVersion
I/TLC_TZ_KEYSTORE: ( 1017): creating new keystore context...
D/TimaService( 1017): TIMA3: KeyStore3_init
I/TLC_TZ_KEYSTORE: ( 1017): initializing ccm context...
D/TimaService( 1017): TIMA: in getTimaVersion
I/TLC_TZ_KEYSTORE: ( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TZ_KEYSTORE: ( 1017): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_key, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 1088 = 0x440
I/TZ: qc_tlc_communication( 1017): max_message_size = 2176 = 0x880
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x880
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,I/FactoryTestApp( 2571): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2991)  
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:2, health:2, present:true, voltage: 4182, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/KLMS-2.5.183: ( 3508): KLMSAbstractReciever(): onReceive().END.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 8
I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
I/TLC_TZ_KEYSTORE: ( 1017): ctx = 0xb9050760, comm = 0xb91fc510, sendmsg = 0xa130b000, recvmsg = 0xa130b440
I/TZ_init: ( 1017): TZ_init: sending initialization request...
E/TZ_init: ( 1017): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 1017): trustlet initialization failed
I/TZ_init: ( 1017): TZ_init_START...
D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
V/EmergencyMode( 1421): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1421): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/PowerUI ( 1179): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1179): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,I/ActivityManager( 1017): Killing 2685:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/TZ_init: ( 1017): TZ_init_with_data: sending initialization request...
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/TZ_init: ( 1017): TZ_init: successful initialization
D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 8
,E/TLC_TZ_KEYSTORE: ( 1017): Count : 1, Ret : 0
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Zygote  ( 3547): MountEmulatedStorage()
,I/ActivityManager( 1017): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3547 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
E/Zygote  ( 3547): v2
W/ResourcesManager( 3528): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3528): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3528): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3528): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/libpersona( 3547): KNOX_SDCARD checking this for 10022
I/libpersona( 3547): KNOX_SDCARD not a persona
I/KLMS-2.5.183: ( 3508): KLMSIntentService(): onCreate()
I/SELinux ( 3547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/KLMS-2.5.183: ( 3508): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SELinux ( 3547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,V/VibratorService( 1017): hasVibrator - useVibetonz: true
,I/KLMS-2.5.183: ( 3508): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/SELinux ( 3547): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): BOOT_COMPLETED
,I/ActivityManager( 1017): Killing 2820:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3547): TimaSignature is unavailable
,D/ActivityThread( 3547): Added TimaKeyStore provider
,D/FileApkUtils( 1853): Spent 119ms computing apk sha1.
,D/FileApkUtils( 1853): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 1853): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3396): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3396): Resource data:2131165186
,D/DexOptUtils( 1853): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
D/DexOptUtils( 1853): Lollipop platform, using <isa> directory.
,D/DexOptUtils( 1853): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 1853): Primary ABI of odexing process is armeabi-v7a
,I/KLMS-2.5.183: ( 3508): KLMSIntentService(): onDestroy()
,W/ResourcesManager( 3396): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3396): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,I/AMMetaDataParserService( 3396): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,I/jxcore-log( 2885): getBuffer is called!!!!
I/jxcore-log( 2885): 
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2800/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2820/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10085/pid_2685/cgroup.procs: No such file or directory
,W/ContextImpl( 3452): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,I/AMMetaDataParserService( 3396): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3396): Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510,
,D/SBrowserFeatureFlag( 3528): initialized in static block : loadCscFeatureValue() succeed! ,
I/ActivityManager( 1017): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3567 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 3567): MountEmulatedStorage(),
E/Zygote  ( 3567): v2
I/libpersona( 3567): KNOX_SDCARD checking this for 1000,
I/libpersona( 3567): KNOX_SDCARD not a persona
,I/SELinux ( 3567): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 3567): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
W/ContextImpl( 3396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserSer,vice( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
E/SELinux ( 3567): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3576): MountEmulatedStorage()
I/libpersona( 3576): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3576): v2
I/libpersona( 3576): KNOX_SDCARD not a persona
I/SELinux ( 3576): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3576): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3576): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3576 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/dex2oat ( 3564): ----------------------------------------------------
I/dex2oat ( 3564): <SS>: S T A R T I N G . . .
I/dex2oat ( 3564): <SS>: Zip is absent. Canceled.
I/ActivityManager( 1017): Killing 2864:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,I/dex2oat ( 3564): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=39 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/TimaKeyStoreProvider( 3567): TimaSignature is unavailable
,D/ActivityThread( 3567): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3576): TimaSignature is unavailable
,D/ActivityThread( 3576): Added TimaKeyStore provider
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 25163(1373KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/39MB, paused 2.297ms total 178.997ms
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131034113
,W/ResourcesManager( 3396): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3396): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ManifestProvider( 3528): onCreate()
,I/GFX construct_block_size_descriptor_2d second part( 3396): took 2.429531ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3396): took 6.068490ms for 0*0 texture 0
,I/GFX raster( 3396): took 9.726302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d9f3e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d9f3a8 counterpartCT=4 counterpartW=96 counterparth=96
,E/NetworkSettingsReceiver( 3528): onReceive: android.intent.action.BOOT_COMPLETED
,W/SEAMService( 1017):  hashset_to_int_array returning null
,I/AMMetaDataParserService( 3396): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3567): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/SEAMService( 1017):  hashset_to_int_array returning null
,E/SQLiteLog( 3452): (284) automatic index on seams_container_info(seams_container_id)
,E/SQLiteLog( 3452): (284) automatic index on seams_container_info(sp_id)
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/SEAMService( 1017):  hashset_to_int_array returning null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 1583:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 3567): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/GCM     ( 1853): COMPAT: Multi user not supported
,E/Zygote  ( 3607): MountEmulatedStorage()
,E/Zygote  ( 3607): v2
I/libpersona( 3607): KNOX_SDCARD checking this for 1000
I/libpersona( 3607): KNOX_SDCARD not a persona
,I/SELinux ( 3607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3607 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SBrowserFeatureFlag( 3528): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@1c69a384
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
E/MTPRx   ( 3576): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
D/SBrowserFeatureFlag( 3528): initialize : initSupportedPkg() succeed! 
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/VerificationLog( 3528): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/F_PHONE ( 3567): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3567): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3607): TimaSignature is unavailable
,D/ActivityThread( 3607): Added TimaKeyStore provider
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedState
D/SecContentProvider2( 1017): mCursor = null
,I/GFX raster( 3396): took 0.901875ms for 96*96 texture 0
,D/SecContentProvider2( 1017): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1017): mCursor = null
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d9f3e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d9f3a8 counterpartCT=4 counterpartW=96 counterparth=96
,D/GCM     ( 1670): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,V/MTPRx   ( 3576): sealedState: false
V/MTPRx   ( 3576): sealedUsbMassStorageState: false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3607): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 3628): MountEmulatedStorage()
E/Zygote  ( 3628): v2
I/libpersona( 3628): KNOX_SDCARD checking this for 10135
,I/libpersona( 3628): KNOX_SDCARD not a persona
I/SELinux ( 3628): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3628): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3628): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3628 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3396): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10150/pid_2864/cgroup.procs: No such file or directory
I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BluetoothBDAdrressReceiver( 3607): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3607): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1017): failed to open /acct/uid_10072/pid_1583/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,D/SettingsProvider( 1017): name = mtp_usb_connection_status
,D/TimaKeyStoreProvider( 3628): TimaSignature is unavailable
,D/ActivityThread( 3628): Added TimaKeyStore provider
,E/USB_UICC(  300): Timeout! No signal received. Retry num = 30
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/GFX construct_block_size_descriptor_2d second part( 3396): took 2.417448ms for 0*0 texture 0
,D/SettingsProvider( 1017): name = media_player_mode
,D/F_PHONE ( 3567): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 3567): default registerAction()
I/F_PHONE ( 3567): [[com.sec.bcservice]] sendPendingMessage()
,E/Zygote  ( 3649): MountEmulatedStorage()
,I/libpersona( 3649): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3649): v2
I/libpersona( 3649): KNOX_SDCARD not a persona
,I/SELinux ( 3649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3649): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GFX generate_partition_tables( 3396): took 8.109896ms for 0*0 texture 0
,I/GFX raster( 3396): took 11.516302ms for 96*96 texture 0
I/ActivityManager( 1017): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3649 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d9f3a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da40d0 counterpartCT=4 counterpartW=96 counterparth=96
W/ResourcesManager( 1468): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ActivityManager( 1017): Killing 2902:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/DBG_DM  ( 2840): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,D/BluetoothBDTestService( 1468): onCreate()
,E/BluetoothBDTestService( 1468): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1468): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1468): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,I/AMMetaDataParserService( 3396): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/SettingsProvider( 1017): name = mtp_usb_conditions_met
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = mtp_running_status
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/SettingsProvider( 1017): name = media_mount_count
,D/TimaKeyStoreProvider( 3649): TimaSignature is unavailable
,D/ActivityThread( 3649): Added TimaKeyStore provider
,W/ResourcesManager( 3628): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3628): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3628): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/GCoreUlr( 1853): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,E/USB_UICC(  300): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  300): usb_uicc_init_qmi failed ! 
I/USB_UICC(  300): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  300): usb_uicc_cleanup, Issuing QMI deinit ... 
,D/SettingsProvider( 1017): name = mtp_sync_alive
,I/CheckinService( 1853): Disabling old GoogleServicesFramework version
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.614948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8da89f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da8b58 counterpartCT=4 counterpartW=96 counterparth=96
,D/SettingsProvider( 1017): name = sdcard_launch
,I/AMMetaDataParserService( 3396): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ResourcesManager( 3649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,D/SystemUpdateService( 1853): onCreate
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.841771ms for 96*96 texture 0
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8da5418 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da5580 counterpartCT=4 counterpartW=96 counterparth=96
,D/SystemUpdateService( 1853): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/AMMetaDataParserService( 3396): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/GCoreUlr( 1694): DispatchingService.onCreate()
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/SettingsProvider( 1017): name = boot_time_connected
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2902/cgroup.procs: No such file or directory
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/ConfigService( 1670): onCreate
,I/ConfigFetchService( 1853): onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/SettingsProvider( 1017): name = mtp_open_session
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,D/daemonapp( 1285): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.662187ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d9f958 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da5cf8 counterpartCT=4 counterpartW=96 counterparth=96
,V/AuthZen ( 1853): Handling intent: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/AuthZenEventHandler( 1853): Handling event: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/PCWCLIENTTRACE_PushUtil( 3162): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3162): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3162): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3162): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3162): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3162): ACTION_BOOTUP - Push type: [SPP, GCM]
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.675208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8da8d90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da8e38 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/PCWCLIENTTRACE_PCWHandler( 3162): [ensureRegistration] - netwrok is not available. action ignored
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.519427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8da4630 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da46d8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3396): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KnoxUsageLogPro( 3649): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131034113
,I/AMMetaDataParserService( 3396): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.944738ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d9f3e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8da5330 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 3697): MountEmulatedStorage()
,E/Zygote  ( 3697): v2
I/libpersona( 3697): KNOX_SDCARD checking this for 10031
I/libpersona( 3697): KNOX_SDCARD not a persona
,I/SELinux ( 3697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3697 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 3697): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 2919:com.policydm/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3396): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KnoxUsageLogPro( 3649): savePreference: key = previous_sys_time value = 1448315164277
,E/Zygote  ( 3708): MountEmulatedStorage(),
E/Zygote  ( 3708): v2,
I/libpersona( 3708): KNOX_SDCARD checking this for 10042
I/SELinux ( 3708): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 3708): KNOX_SDCARD not a persona
D/TimaKeyStoreProvider( 3697): TimaSignature is unavailable
D/ActivityThread( 3697): Added TimaKeyStore provider
,I/SELinux ( 3708): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3708): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3708 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/KnoxUsageLogPro( 3649): premStatus:2
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.804219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d9f3e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8da5580 counterpartCT=4 counterpartW=96 counterparth=96
,I/KnoxUsageLogPro( 3649): isEulaShown : false
I/KnoxUsageLogPro( 3649): KnoxUsageReceiver onReceive : not Processible, just return
,D/TimaKeyStoreProvider( 3708): TimaSignature is unavailable
,D/ActivityThread( 3708): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3396): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/KnoxUsageLogPro( 3649): savePreference: key = previous_elapsed_time value = 36510
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3730): MountEmulatedStorage()
E/Zygote  ( 3730): v2
I/libpersona( 3730): KNOX_SDCARD checking this for 10139
I/libpersona( 3730): KNOX_SDCARD not a persona
,I/SELinux ( 3730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/art     ( 1670): Explicit concurrent mark sweep GC freed 20490(1195KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 10MB/16MB, paused 947us total 45.642ms
E/SELinux ( 3730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/LockPatternUtils( 1306): isSmartCardAuthenticationAvailable: false
I/ActivityManager( 1017): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3730 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.647969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d9f3a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da75b0 counterpartCT=4 counterpartW=96 counterparth=96
I/art     (  307): Explicit concurrent mark sweep GC freed 8749(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 26.747ms
,D/TimaKeyStoreProvider( 3730): TimaSignature is unavailable
,D/ActivityThread( 3730): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_2919/cgroup.procs: No such file or directory
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 821us total 18.159ms
,I/AMMetaDataParserService( 3396): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ResourcesManager( 3730): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3730): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3730): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3730): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3730): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1017): Killing 2973:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 687us total 18.852ms
,W/ResourcesManager( 3697): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 3708): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CheckinService( 1853): Checking schedule, now: 1448315164452 next: 1448792533386
,I/CheckinService( 1853): active receiver: disabled
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/BaseAppContext( 1853): Using Auth Proxy for data requests.
,I/GFX raster( 3396): took 0.619010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8da89f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da4230 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3396): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1853): [ChannelManager] Attempting to channel bind connection HttpClient.
,D/ChimeraCfgMgr( 1853): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/art     ( 1694): Explicit concurrent mark sweep GC freed 12471(769KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 10MB/17MB, paused 1.164ms total 77.697ms
,W/libprocessgroup( 1017): failed to open /acct/uid_10003/pid_2973/cgroup.procs: No such file or directory
E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.825417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8da5418 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da4478 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1853): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/SystemUpdateService( 1853): cancelUpdate (empty URL)
,I/SystemUpdateService( 1853): active receiver: disabled
,I/AMMetaDataParserService( 3396): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/CalendarProvider2( 3708): CalendarProvider2.onCreate() called
,I/GCoreUlr( 1694): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.625834ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d64f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d657e8 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/ConfigFetchService( 1853): service connected
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/ActivityManager( 1017): Killing 3048:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,D/ChimeraCfgMgr( 1853): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/AuthZen ( 1853): Fetching signing key...
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/GFX raster( 3396): took 0.851303ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8ad9c18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d69db8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Zygote  ( 3763): MountEmulatedStorage()
E/Zygote  ( 3763): v2
I/libpersona( 3763): KNOX_SDCARD checking this for 10145
I/libpersona( 3763): KNOX_SDCARD not a persona
,I/SELinux ( 3763): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3763 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/AuthZen ( 1853): Signing key fetched successfully!,
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/BaseAppContext( 1853): Using Auth Proxy for data requests.
,I/SELinux ( 3763): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3763): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 3770): MountEmulatedStorage(),
E/Zygote  ( 3770): v2,
,I/libpersona( 3770): KNOX_SDCARD checking this for 10104
I/libpersona( 3770): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3770 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 3770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3770): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/AuthZen ( 1853): Starting Enrollment...
,I/VlingoApplication( 3697): VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3792 uid=10150 gids={50150, 9997} abi=armeabi-v7a
W/libprocessgroup( 1017): failed to open /acct/uid_10060/pid_3048/cgroup.procs: No such file or directory
,E/Zygote  ( 3792): MountEmulatedStorage()
E/Zygote  ( 3792): v2
I/libpersona( 3792): KNOX_SDCARD checking this for 10150
I/libpersona( 3792): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider( 3763): TimaSignature is unavailable
,D/ActivityThread( 3763): Added TimaKeyStore provider
D/AuthZen ( 1853): getting auth token. Attempt 0
,I/SELinux ( 3792): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,I/Kids    ( 1853): [KidAccountFixer] No network connection
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,I/SELinux ( 3792): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SELinux ( 3792): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3770): TimaSignature is unavailable
E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityThread( 3770): Added TimaKeyStore provider
I/GFX raster( 3396): took 0.593594ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8a2b960 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d66320 counterpartCT=4 counterpartW=96 counterparth=96
,D/BluetoothAdapter( 3697): 1010087717: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3697): 1010087717: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3697): 1010087717: getState() :  mService = null. Returning STATE_OFF
,I/VlingoAndroidCore( 3697): AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,I/AMMetaDataParserService( 3396): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3396): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3396): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3396): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131034112
,I/AMMetaDataParserService( 3396): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.818438ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d66490 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d868e8 counterpartCT=4 counterpartW=96 counterparth=96
,E/SMD     (  291): DCD OFF
,D/TimaKeyStoreProvider( 3792): TimaSignature is unavailable
D/ActivityThread( 3792): Added TimaKeyStore provider
I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3396): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,W/ResourcesManager( 3763): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3763): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3763): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3763): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3763): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.706094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d66490 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d657e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 2840): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/ConfigFetchService( 1853): ConfigApi connection successful.
,W/ResourcesManager( 3770): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SystemUpdateService( 1853): onDestroy
,I/AMMetaDataParserService( 3396): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,D/PackageManager( 1017): [MSG] MCS_UNBIND
,I/ActivityManager( 1017): Killing 2958:com.google.android.configupdater/u0a86 (adj 15): empty #31
,I/GLSActivity( 1670): [ac] getting account id
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.802604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d69db8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d66320 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.745834ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d64f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d868e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/GLSUser ( 1670): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1670): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GLSUser ( 1670): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,W/libprocessgroup( 1017): failed to open /acct/uid_10086/pid_2958/cgroup.procs: No such file or directory
,D/VlingoApplication( 3697): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,D/VlingoApplication( 3697): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/DialogFlow( 3697): initQueue()
,I/GLSUser ( 1670): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,I/GLSUser ( 1670): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/GLSUser ( 1670): [GLSUser] Extracting token using key: Auth
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/GLSActivity( 1670): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1670): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3818): MountEmulatedStorage(),
E/Zygote  ( 3818): v2
I/libpersona( 3818): KNOX_SDCARD checking this for 10032
I/SELinux ( 3818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 3818): KNOX_SDCARD not a persona
I/SELinux ( 3818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3818 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3070:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,E/SELinux ( 3818): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3818): TimaSignature is unavailable
,D/ActivityThread( 3818): Added TimaKeyStore provider
,D/FactoryTestApp( 2571): [DummyFtClient$onDestroy](2571) Destroy DummyFtClient service
,D/FactoryTestApp( 2571): [Support$Values.getString](2571) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2571): [ModuleCommon$isConnectionModeNone](2571) mConnectionMode = gsm
,I/FactoryTestApp( 2571): [ModuleCommon$isRunningFtClient](2571) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2571): [DummyFtClient$onDestroy](2571) kill process
,I/Process ( 2571): Sending signal. PID: 2571 SIG: 9
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1017): Process com.sec.factory (pid 2571)(adj 0) has died(58,1101)
,W/libprocessgroup( 1017): failed to open /acct/uid_10094/pid_3070/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3835): MountEmulatedStorage()
E/Zygote  ( 3835): v2
I/libpersona( 3835): KNOX_SDCARD checking this for 10033
I/libpersona( 3835): KNOX_SDCARD not a persona
,I/SELinux ( 3835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3835 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 3835): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 2042:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3835): TimaSignature is unavailable
,D/ActivityThread( 3835): Added TimaKeyStore provider
,E/AuthZen ( 1853): Error getting auth token
E/AuthZen ( 1853): com.google.android.gms.auth.ad: BadAuthentication
E/AuthZen ( 1853): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.p.a(SourceFile:318)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1853): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1853): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AuthZen ( 1853): Failed to do enrollment for account: thalitester@gmail.com
E/AuthZen ( 1853): com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
E/AuthZen ( 1853): 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
E/AuthZen ( 1853): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AuthZen ( 1853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AuthZen ( 1853): 	at android.os.Looper.loop(Looper.java:145)
E/AuthZen ( 1853): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/libprocessgroup( 1017): failed to open /acct/uid_10012/pid_2042/cgroup.procs: No such file or directory
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 27130(1639KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 26MB/40MB, paused 2.356ms total 151.255ms
,D/SecurityLogAgent:SEDenialService( 1017): Got CLOSE_WRITE Event sk.log
,D/SecurityLogAgent:SEDenialService( 1017): Got CLOSE_WRITE Event sk.log
,D/SecurityLogAgent:SEDenialService( 1017): Got CLOSE_WRITE Event sk.log
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,D/a       ( 1853): Opening database auth.proximity.permit_store...
,I/ActivityManager( 1017): Killing 3100:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,D/AuthZenTransactionCache( 1853): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1853): Clearing transaction cache
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131034113
,I/AMMetaDataParserService( 3396): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.942760ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d66320 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d657e8 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1017): failed to open /acct/uid_10062/pid_3100/cgroup.procs: No such file or directory
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
I/AMMetaDataParserService( 3396): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/ActivityManager( 1017): Killing 3127:com.fmm.dm/1000 (adj 15): empty #31
,I/SettingSearch/SearchIntentReceiver( 1306): InitSerachDBThread thread end!
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.957865ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d66320 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d868e8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3835): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3835): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3835): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3
,I/AMMetaDataParserService( 3396): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ResourcesManager( 3835): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3835): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3835): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3835): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3835): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 3835): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.607500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d657e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d868e8 counterpartCT=4 counterpartW=96 counterparth=96
,W/art     ( 3763): Verification of boolean com.android.email.activity.MessageListItemOuterContainer.onTouchEvent(android.view.MotionEvent) took 144.003ms
,I/AMMetaDataParserService( 3396): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/GCoreUlr( 1694): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/DBG_DM  ( 2840): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,I/GCoreUlr( 1694): Unbound from all location providers
,I/dex2oat ( 3564): dex2oat took 2.399s (threads: 4)
,D/DexOptUtils( 1853): Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
D/DexOptUtils( 1853): Set odex to world readable.
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3127/cgroup.procs: No such file or directory
D/DexOptUtils( 1853): Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
D/FileApkUtils( 1853): Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3396): took 0.602135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d66490 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d868e8 counterpartCT=4 counterpartW=96 counterparth=96
,D/GmsModuleFndr( 1853): Beginning GMS chimera module scan
,I/AMMetaDataParserService( 3396): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/GCoreUlr( 1694): DispatchingService.onDestroy()
,I/GCoreUlr( 1694): Unbound from all location providers
,I/Babel_SMS( 3770): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 3770): MmsConfig.loadMmsSettings
,I/Babel_SMS( 3770): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel_SMS( 3770): MmsConfig.loadFromDatabase
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3863): MountEmulatedStorage()
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=3863 uid=10072 gids={50072, 9997} abi=armeabi-v7a
E/Zygote  ( 3863): v2
I/libpersona( 3863): KNOX_SDCARD checking this for 10072
I/libpersona( 3863): KNOX_SDCARD not a persona
I/SELinux ( 3863): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3863): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3863): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3863): TimaSignature is unavailable
,D/ActivityThread( 3863): Added TimaKeyStore provider
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3396): took 0.948021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8da5418 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d868e8 counterpartCT=4 counterpartW=96 counterparth=96
,D/GmsModuleFndr( 1853): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 1853): Beginning module configuration check
,D/ChimeraCfgMgr( 1853): Module APKs unchanged, check complete
,E/Babel_SMS( 3770): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 3770): MmsConfig.loadFromResources
,E/Babel_SMS( 3770): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 3770): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/AMMetaDataParserService( 3396): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BadgeProvider( 3863): onCreate
,D/BadgeProvider( 3863): DatabaseHelper
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.838854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d64f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d868e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/BadgeProvider( 3863): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 3863): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3863): sendNotify, [notify] : null
D/BadgeProvider( 3863): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3863): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 3863): update, [UpdateCount] : 1
,D/Launcher.Model( 1493): reloadBadges entered.
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.808437ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8ad9c18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d868e8 counterpartCT=4 counterpartW=96 counterparth=96
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  283): getCameraInfo: X
,W/QCamera2Factory(  283): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  283): getCameraInfo: X
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3396): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/art     ( 3770): Suspending all threads took: 7.782ms
,I/CalendarProvider2( 3708): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1017): Killing 3145:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/Settings( 3770): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/GFX raster( 3396): took 0.551875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8a2b960 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d57b60 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3396): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity,
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/libpersona( 3898): KNOX_SDCARD checking this for 10146
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.searchable
I/libpersona( 3898): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
W/ContextImpl( 3396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
E/Zygote  ( 3898): MountEmulatedStorage()
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
E/Zygote  ( 3898): v2
I/AMMetaDataParserService( 3396): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
I/SELinux ( 3898): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3898): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3898): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=3898 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/Babel_Crash( 3770): startup - clean
,I/ActivityManager( 1017): Killing 3179:com.sec.factory.camera/1000 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
I/ActivityManager( 1017): Killing 3197:com.wssnps/1000 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/Babel   ( 3770): deleted: false for 0
,D/TimaKeyStoreProvider( 3898): TimaSignature is unavailable
,D/ActivityThread( 3898): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,W/ResourcesManager( 3898): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131165203
,I/Process ( 3763): Sending signal. PID: 3763 SIG: 9,
,W/ResourcesManager( 3396): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3396): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3145/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3197/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3179/cgroup.procs: No such file or directory
,I/Process ( 3835): Sending signal. PID: 3835 SIG: 9
,W/ResourcesManager( 3818): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3818): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3396): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/ActivityManager( 1017): Process com.sec.android.app.sns3 (pid 3835)(adj 0) has died(55,1126)
,I/GFX construct_block_size_descriptor_2d second part( 3396): took 2.839792ms for 0*0 texture 0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/GFX generate_partition_tables( 3396): took 10.073645ms for 0*0 texture 0
,I/GFX raster( 3396): took 13.730833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d827c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8d83e48 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3818): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3396): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,E/Zygote  ( 3916): MountEmulatedStorage()
,E/Zygote  ( 3916): v2
I/libpersona( 3916): KNOX_SDCARD checking this for 10034
I/libpersona( 3916): KNOX_SDCARD not a persona
,I/SELinux ( 3916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3916 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
I/SELinux ( 3916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Process com.android.email (pid 3763)(adj 9) has died(52,1127)
,E/SELinux ( 3916): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.794740ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb90ff7b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb90ff858 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3396): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,D/TimaKeyStoreProvider( 3916): TimaSignature is unavailable
,D/ActivityThread( 3916): Added TimaKeyStore provider
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.764844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb90ff7b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9100ab8 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/System.out( 3697): INFO:Resource not found:/Common.properties Using default values
,I/AMMetaDataParserService( 3396): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,E/Zygote  ( 3934): MountEmulatedStorage()
I/libpersona( 3934): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3934): v2
I/libpersona( 3934): KNOX_SDCARD not a persona
I/SELinux ( 3934): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 3934): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=3934 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 3934): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3947): MountEmulatedStorage(),
E/Zygote  ( 3947): v2
I/libpersona( 3947): KNOX_SDCARD checking this for 10145
I/SELinux ( 3947): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/libpersona( 3947): KNOX_SDCARD not a persona
I/SELinux ( 3947): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 3947): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=3947 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,W/VideoCapabilities( 3770): Unrecognized profile 2130706433 for video/avc
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3396): took 0.791979ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb90ff7b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d43100 counterpartCT=4 counterpartW=96 counterparth=96
W/AudioCapabilities( 3770): Unsupported mime audio/evrc
,D/TimaKeyStoreProvider( 3934): TimaSignature is unavailable
W/AudioCapabilities( 3770): Unsupported mime audio/qcelp
D/ActivityThread( 3934): Added TimaKeyStore provider
I/AMMetaDataParserService( 3396): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
W/AudioCapabilities( 3770): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 3770): Unsupported mime audio/mpeg-L2
D/TimaKeyStoreProvider( 3947): TimaSignature is unavailable
D/ActivityThread( 3947): Added TimaKeyStore provider
,W/AudioCapabilities( 3770): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3770): Unsupported mime audio/x-ima
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/ActivityManager( 1017): Killing 3214:com.fmm.ds/1000 (adj 15): empty #31
I/GFX raster( 3396): took 0.624323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d43100 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9103178 counterpartCT=4 counterpartW=96 counterparth=96
,W/AudioCapabilities( 3770): Unsupported mime audio/qcelp
W/AudioCapabilities( 3770): Unsupported mime audio/evrc
I/AMMetaDataParserService( 3396): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,V/AlarmManager( 1017): waitForAlarm result :4
,W/VideoCapabilities( 3770): Unsupported mime video/wvc1
,W/VideoCapabilities( 3770): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3770): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/ResourcesManager( 3947): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/VideoCapabilities( 3770): Unsupported mime video/wvc1
,W/ResourcesManager( 3947): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/VideoCapabilities( 3770): Unsupported mime video/x-ms-wmv
W/ResourcesManager( 3947): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 3947): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3947): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.607812ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d43100 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9102fd0 counterpartCT=4 counterpartW=96 counterparth=96
,W/VideoCapabilities( 3770): Unsupported mime video/x-ms-wmv7
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 3770): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3770): Unsupported mime video/mp43
,W/VideoCapabilities( 3770): Unsupported mime video/sorenson,
,I/AMMetaDataParserService( 3396): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
W/ContextImpl( 3396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,E/Zygote  ( 3968): MountEmulatedStorage()
I/libpersona( 3968): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3968): v2
I/libpersona( 3968): KNOX_SDCARD not a persona
I/SELinux ( 3968): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 3968): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3968): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/VideoCapabilities( 3770): Unsupported mime video/mp4v-esdp
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=3968 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3229:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3968): TimaSignature is unavailable
D/ActivityThread( 3968): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 785us total 28.035ms
,I/VideoCapabilities( 3770): Unsupported profile 4 for video/mp4v-es
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 17.277ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 17.071ms
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/Zygote  ( 3984): MountEmulatedStorage(),
E/Zygote  ( 3984): v2
I/libpersona( 3984): KNOX_SDCARD checking this for 1000
I/libpersona( 3984): KNOX_SDCARD not a persona
I/SELinux ( 3984): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=3984 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 3984): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 3984): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 3245:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3984): TimaSignature is unavailable
,D/ActivityThread( 3984): Added TimaKeyStore provider
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131099648
,W/VideoCapabilities( 3770): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3770): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3770): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 3396): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3396): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.868125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb92ac7e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb92acac0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SecurityLogAgent( 3968): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 3968): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 3968): StateMachine : Current State = 1
D/SecurityLogAgent( 3968): BootReceiver : completed task. Failed to return wakelock . 
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4002 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a,
,I/ActivityManager( 1017): Killing 3274:com.samsung.helphub/1000 (adj 15): empty #31,
,E/Zygote  ( 4002): MountEmulatedStorage()
,E/Zygote  ( 4002): v2
I/libpersona( 4002): KNOX_SDCARD checking this for 10152
I/libpersona( 4002): KNOX_SDCARD not a persona
,W/VideoCapabilities( 3770): Unrecognized profile 2130706433 for video/avc
,I/SELinux ( 4002): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4002): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4002): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3984): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
I/AMMetaDataParserService( 3396): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
I/DBG_POLICYDM( 3984): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
I/DBG_POLICYDM( 3984): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 3984): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3984): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 3984): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/TimaKeyStoreProvider( 4002): TimaSignature is unavailable
,D/ActivityThread( 4002): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3984): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
I/DBG_POLICYDM( 3984): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 3984): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 3984): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3214/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 3984): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/DBG_DM  ( 2840): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,I/DBG_POLICYDM( 3984): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
I/DBG_POLICYDM( 3984): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3984): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,W/libprocessgroup( 1017): failed to open /acct/uid_10100/pid_3229/cgroup.procs: No such file or directory
,I/GFX construct_block_size_descriptor_2d second part( 3396): took 2.871667ms for 0*0 texture 0
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3245/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3274/cgroup.procs: No such file or directory
,I/GFX generate_partition_tables( 3396): took 8.805260ms for 0*0 texture 0
,I/GFX raster( 3396): took 12.749064ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d57b60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8d63d70 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 3984): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3984): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/AMMetaDataParserService( 3396): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/vclib   ( 3770): onServiceConnected
,W/Babel   ( 3770): Attempted to change video mute state without an active call.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3984): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3396): took 0.637344ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d58d68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8d69db8 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 4002): (284) automatic index on shooting_modes(title_id)
,I/AMMetaDataParserService( 3396): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/Zygote  ( 4024): MountEmulatedStorage()
I/libpersona( 4024): KNOX_SDCARD checking this for 10035
E/Zygote  ( 4024): v2
I/libpersona( 4024): KNOX_SDCARD not a persona
,I/SELinux ( 4024): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4024): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4024 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4024): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 3293:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 3984): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.654010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8da93e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d66490 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TimaKeyStoreProvider( 4024): TimaSignature is unavailable
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4024): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3984): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3984): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.654792ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8ad9c18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d657e8 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4040): MountEmulatedStorage(),
E/Zygote  ( 4040): v2
I/libpersona( 4040): KNOX_SDCARD checking this for 10041
I/libpersona( 4040): KNOX_SDCARD not a persona,
,I/SELinux ( 4040): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4040 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 3310:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,I/SELinux ( 4040): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
E/SELinux ( 4040): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,I/DBG_POLICYDM( 3984): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.730833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d64f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89d51e8 counterpartCT=4 counterpartW=96 counterparth=96
,E/DBG_POLICYDM( 3984): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/AMMetaDataParserService( 3396): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,E/Zygote  ( 4055): MountEmulatedStorage()
I/libpersona( 4055): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4055): v2
I/libpersona( 4055): KNOX_SDCARD not a persona
,I/SELinux ( 4055): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/ActivityManager( 1017): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4055 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4055): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131099648
E/SELinux ( 4055): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3396): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3396): took 0.748958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb92ac7e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d87368 counterpartCT=4 counterpartW=96 counterparth=96
,D/BadgeProvider( 3863): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/AMMetaDataParserService( 3396): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 4040): TimaSignature is unavailable
,D/ActivityThread( 4040): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4055): TimaSignature is unavailable
,D/ActivityThread( 4055): Added TimaKeyStore provider
,W/ActivityManager( 1017): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,W/libprocessgroup( 1017): failed to open /acct/uid_10069/pid_3293/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3310/cgroup.procs: No such file or directory
,I/Process ( 3898): Sending signal. PID: 3898 SIG: 9
,I/ActivityManager( 1017): Killing 3340:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,D/BadgeProvider( 3863): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3863): sendNotify, [notify] : null
D/BadgeProvider( 3863): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 3863): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 3863): update, [UpdateCount] : 1
,D/Launcher.Model( 1493): reloadBadges entered.
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.644062ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d57b60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8d657e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/GFX raster( 3396): took 0.670000ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d58d68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8d66490 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4076 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,E/Zygote  ( 4076): MountEmulatedStorage()
E/Zygote  ( 4076): v2
I/libpersona( 4076): KNOX_SDCARD checking this for 1101
I/libpersona( 4076): KNOX_SDCARD not a persona
I/SELinux ( 4076): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3396): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/SPPClientService( 4024): [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
E/SPPClientService( 4024): [SystemStateMoniter] Current Time : 39473
,I/SELinux ( 4076): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4076): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 3028:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
E/SPPClientService( 4024): ============PushLog. commonIsShipBuild. stop!
,I/ActivityManager( 1017): Process com.android.exchange (pid 3898)(adj 15) has died(32,1131)
E/SPPClientService( 4024): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 4024): PushLog.txt file is not deleted.
,D/SPPClientService( 4024): PushLog.txt file is not deleted.
D/SPPClientService( 4024): ============PushLog. stop!
,D/TimaKeyStoreProvider( 4076): TimaSignature is unavailable
,D/ActivityThread( 4076): Added TimaKeyStore provider
,W/ResourcesManager( 4076): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,V/SmartcardService( 4076): main Received broadcast,
V/SmartcardService( 4076): Starting smartcard service after boot completed
,E/Zygote  ( 4093): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4093 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 4093): v2
I/libpersona( 4093): KNOX_SDCARD checking this for 10166
I/SELinux ( 4093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/libpersona( 4093): KNOX_SDCARD not a persona
I/SELinux ( 4093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
D/ActivityManager( 1017): retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
E/SELinux ( 4093): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3340/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10009/pid_3028/cgroup.procs: No such file or directory
,I/ActivityManager( 1017): Killing 2941:com.google.android.gms:car/u0a12 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.683230ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8da93e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d69db8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TimaKeyStoreProvider( 4093): TimaSignature is unavailable
,D/ActivityThread( 4093): Added TimaKeyStore provider
,E/Zygote  ( 4109): MountEmulatedStorage(),
E/Zygote  ( 4109): v2
I/libpersona( 4109): KNOX_SDCARD checking this for 1000
E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/libpersona( 4109): KNOX_SDCARD not a persona
I/GFX raster( 3396): took 0.648490ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8ad9c18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d87bf0 counterpartCT=4 counterpartW=96 counterparth=96,
I/SELinux ( 4109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
I/ActivityManager( 1017): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=4109 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 4109): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SA      ( 4040): [SSP] onCreated
,D/TimaKeyStoreProvider( 4109): TimaSignature is unavailable
,D/ActivityThread( 4109): Added TimaKeyStore provider
,W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,W/ActivityManager( 1017): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 10999ms
,W/ContextImpl( 4109): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3396): took 0.744010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d64f98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d5b388 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
,E/Zygote  ( 4128): MountEmulatedStorage()
E/Zygote  ( 4128): v2
I/libpersona( 4128): KNOX_SDCARD checking this for 10157
I/libpersona( 4128): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4128 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,W/libprocessgroup( 1017): failed to open /acct/uid_10012/pid_2941/cgroup.procs: No such file or directory
,I/SELinux ( 4128): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/SELinux ( 4128): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4128): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131099648
,I/SA      ( 4040): [TPM] There is no property file
,I/AMMetaDataParserService( 3396): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3396): took 0.688958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb92ac7e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da5b60 counterpartCT=4 counterpartW=96 counterparth=96,
,I/SA      ( 4040): [SCU] isHaveSA() - false
D/TimaKeyStoreProvider( 4128): TimaSignature is unavailable
,D/ActivityThread( 4128): Added TimaKeyStore provider
,I/SA      ( 4040): [TPM] getModelProperty : null
I/SA      ( 4040): [TPM] getCSCProperty : null
I/SA      ( 4040): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4040): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4040): [DM] TFT FEATURE: false
,I/AMMetaDataParserService( 3396): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 4128): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog( 1670): (10) POSIX Error : 11 SQLite Error : 3850
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4143): MountEmulatedStorage(),
E/Zygote  ( 4143): v2
I/libpersona( 4143): KNOX_SDCARD checking this for 10159
I/libpersona( 4143): KNOX_SDCARD not a persona
,I/SELinux ( 4143): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4143 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 3005:com.android.vending/u0a28 (adj 15): empty #31
I/SELinux ( 4143): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,E/SELinux ( 4143): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/SA      ( 4040): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4040): [DM] init START
,I/SA      ( 4040): [DM] This device is not a Vodafone
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.631875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d57b60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8d87bf0 counterpartCT=4 counterpartW=96 counterparth=96
D/TimaKeyStoreProvider( 4143): TimaSignature is unavailable
,D/ActivityThread( 4143): Added TimaKeyStore provider
,W/ResourceType( 4040): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4040): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4040): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4040): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4040): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4040): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4040): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4040): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4040): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4040): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4040): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4040): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4040): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4040): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4040): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4040): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4040): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
I/AMMetaDataParserService( 3396): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ResourceType( 4040): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4040): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4040): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4040): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4040): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4040): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4040): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4040): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4040): [SCU] isHaveSA() - false
I/SA      ( 4040): support phone number id : false
I/SA      ( 4040): [DM] Supports Ref Jpn : true
,I/SA      ( 4040): [DM] init END
,I/SA      ( 4040): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,I/SA      ( 4040): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityManager( 1017): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
I/GFX raster( 3396): took 0.621302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d58d68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8b29888 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4040): [OR] onReceive END
,I/AMMetaDataParserService( 3396): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/Intent to TravelDirActivity( 4143): inside TravelBroadcastReceiver
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3396): took 0.658176ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8da93e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d69db8 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1017): Killing 3379:com.sec.android.app.mt/1000 (adj 15): empty #31
,I/SA      ( 4040): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4040): [ODM] queryOpenData(key= GEO_IP )
,I/AMMetaDataParserService( 3396): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.636980ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8ad9c18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a2b960 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4040): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4040): [LBE] REF_JPN : true
I/SA      ( 4040): [BDC] create
,I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520,
,I/SA      ( 4040): [DBMV2] getEmailID
,I/SA      ( 4040): [DBMV2] getDataV02ForItems
,I/SA      ( 4040): [SSP] query invoked
,I/SA      ( 4040): [SCU] get signed id from samsung account2.0 DB.
,I/SA      ( 4040): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4040): [BDC] destroy
,I/ActivityManager( 1017): Killing 3364:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10028/pid_3005/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_3379/cgroup.procs: No such file or directory
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3396): took 0.740054ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d7fed8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d43c20 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3396): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131099648
,I/AMMetaDataParserService( 3396): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.687656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d57ee0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d86480 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4093): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4093): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3396): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.625520ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d81bc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8d57b60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,V/JNIHelp ( 4093): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_3364/cgroup.procs: No such file or directory
,E/SMD     (  291): DCD OFF
,W/ActivityThread( 4093): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4093): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ef3f157: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4093): Installed default security provider GmsCore_OpenSSL
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3396): took 0.645156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d66490 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8d86480 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_DM  ( 2840): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/AMMetaDataParserService( 3396): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/BluetoothAdapter( 2885): disable()
,I/GFX raster( 3396): took 0.729584ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d82e88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d69db8 counterpartCT=4 counterpartW=96 counterparth=96
,E/BluetoothManagerService( 1017): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1017): mCursor = null
,I/AMMetaDataParserService( 3396): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/WifiService( 1017): setWifiEnabled: false pid=2885, uid=10174
,D/SettingsProvider( 1017): name = wifi_on
,I/jxcore-log( 2885): ****TEST TOOK:  5046  ms ****
I/jxcore-log( 2885): 
,I/jxcore-log( 2885): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2885): 
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3396): took 2.117344ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8ad9c18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da93e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.933126ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d7fed8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d66320 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131099648
,I/AMMetaDataParserService( 3396): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.845885ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d57ee0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d82e18 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.719947ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d81bc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8d69db8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.631823ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d66490 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8d64f98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ResourcesManager( 4093): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4093): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3396): took 0.648646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d82e88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d66320 counterpartCT=4 counterpartW=96 counterparth=96
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/AMMetaDataParserService( 3396): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.681927ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8ad9c18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8da93e8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/dex2oat ( 4175): ----------------------------------------------------
I/dex2oat ( 4175): <SS>: S T A R T I N G . . .
I/dex2oat ( 4175): <SS>: Zip is absent. Canceled.
I/dex2oat ( 4175): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads125747978.jar --oat-fd=28 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads125747978.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/YouTube MDX( 4093): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/dex2oat ( 4175): dex2oat took 37.231ms (threads: 4)
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3396): took 0.707969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d7fed8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d86378 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3396): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/SSRM:n  ( 1017): SIOP:: AP = 410
,D/AndroidRuntime( 4169): 
D/AndroidRuntime( 4169): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4169): CheckJNI is OFF,
D/AndroidRuntime( 4169): readGMSProperty: start
D/AndroidRuntime( 4169): readGMSProperty: already setted!!
D/AndroidRuntime( 4169): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4169): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4169): readGMSProperty: end
D/AndroidRuntime( 4169): addProductProperty: start
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131099648
,I/AMMetaDataParserService( 3396): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.684427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d57ee0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d86480 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4093): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/AffinityControl( 4169): AffinityControl: registerfunction enter
,E/Zygote  ( 4205): MountEmulatedStorage()
I/libpersona( 4205): KNOX_SDCARD checking this for 10012
E/Zygote  ( 4205): v2
I/libpersona( 4205): KNOX_SDCARD not a persona
I/SELinux ( 4205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
I/SELinux ( 4205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
E/SELinux ( 4205): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=4205 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/AndroidRuntime( 4169): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 1017): START PACKAGE DELETE: observer{875721699},
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true,
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1017): !@killApplicatoin: 10174, uninstall pkg,
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10174 user=-1: uninstall pkg
I/ActivityManager( 1017): Killing 2885:com.example.hello/u0a174 (adj 0): stop com.example.hello cause uninstall pkg
,I/art     (  307): Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 646us total 30.361ms
,W/ActivityManager( 1017): Force removing ActivityRecord{2160b7a8 u0 com.example.hello/.MainActivity t228}: app died, no saved state
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/FocusedStackFrame( 1017): Set to : 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 2885
,D/TimaKeyStoreProvider( 4205): TimaSignature is unavailable
,D/ActivityThread( 4205): Added TimaKeyStore provider
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.777188ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d81bc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8d58d68 counterpartCT=4 counterpartW=96 counterparth=96
I/SurfaceFlinger(  257): id=11 Removed NainActivit (6/7)
I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/7)
I/AMMetaDataParserService( 3396): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1017): mDVFSHelper.acquire()
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 881us total 32.815ms,
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 598us total 16.587ms
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.618229ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d66490 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8d82e18 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3396): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/PackageSettings( 1017): Skipping PackageSetting{256b6706 com.test.thalitest/10175} due to missing metadata
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.719584ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d82e88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d57b60 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.784375ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8ad9c18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d64f98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1017): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1017): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.741406ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb8d7fed8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d69db8 counterpartCT=4 counterpartW=96 counterparth=96
,D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
I/AMMetaDataParserService( 3396): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
D/SensorService( 1017): [SO] activate (ident=0xb9107620, enabled=0)
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10174 user=0: pkg removed
,D/SensorManager( 1017): unregisterListener ::   
,I/Sensors ( 1017): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/Launcher( 1493): onRestart, Launcher: 476685188
,D/SensorService( 1017): [SO] changed settle time [0]
,D/SensorService( 1017): [SO] setDelay [200000000]
W/ResourcesManager( 4205): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4205): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SensorService( 1017): [SO] activate (ident=0xb9213d10, enabled=1)
D/SensorService( 1017): [SO] AR_init
I/Sensors ( 1017): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
W/ContextImpl( 3396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 co,m.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
D/SensorManager( 1017): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
I/MultiDex( 4205): VM with version 2.1.0 has multidex support
I/MultiDex( 4205): install
I/MultiDex( 4205): VM has multidex support, MultiDex support library is disabled.
W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/Launcher( 1493): onStart, Launcher: 476685188
D/Launcher.HomeView( 1493): onStart
D/Launcher( 1493): onResume, Launcher: 476685188
D/SettingsProvider( 1017): name = kids_home_mode
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10007
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/Launcher.HomeView( 1493): onResume
D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1787): mOCRHelper is null
,W/ResourcesManager( 1468): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/RegisteredComponentCache( 1453): Collect Tech packages for Knox
,D/PersonaManager( 1453): isKioskContainerExistOnDevice
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131165197
,W/ResourcesManager( 3396): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3396): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/JNIHelp ( 4205): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/AMMetaDataParserService( 3396): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,I/AMMetaDataParserService( 3396): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ActivityThread( 4205): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4205): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e8da075: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4205): Installed default security provider GmsCore_OpenSSL
,D/SensorService( 1017): [SO] Reset Rotation Old [100], Init [1]
,I/AMMetaDataParserService( 3396): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3396): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622,
D/RCPManagerService( 1017): PackageReceiver onReceive()
I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0,
D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1017): PackageRemovalReceiver::onReceive Enter
D/PersonaManager( 1453): isKioskContainerExistOnDevice
D/OTPFW   ( 1017): OtpDbHelper::getInstance New instance created
D/OTPFW   ( 1017): DBIntegrity::getInstance - New instance created
,D/RegisteredServicesCache( 1453): empty dynamic service,
,D/OTPFW   ( 1017): PackageRemovalReceiver::onReceive deleting token for Pkg = com.example.hello uid = 10174 container id = 0
,I/OTPFW   ( 1017): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1017): ProvisionData::getAllEntries Table is empty
,I/DBG_DM  ( 2840): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10174
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131165197
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10174
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
D/TaskPersister( 1017): removeObsoleteFile: deleting file=228_task.xml
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.example.hello
D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,I/AMMetaDataParserService( 3396): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,I/AMMetaDataParserService( 3396): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3396): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 42171(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 27MB/40MB, paused 5.523ms total 248.713ms
,I/art     ( 1017): WaitForGcToComplete blocked for 209.098ms for cause Explicit
,I/AMMetaDataParserService( 3396): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/PackageManager( 1017): delete codoeFile: 
,I/AASA_removePackage( 1017): UID=10174 Target=com.example.hello
D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10174, packageName = com.example.hello
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1017): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1017): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/PackageManager( 1017): result of delete: 1{875721699}
,D/AndroidRuntime( 4169): Shutting down VM
,I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131165197
,I/AMMetaDataParserService( 3396): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,I/AMMetaDataParserService( 3396): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3396): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3396): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3396): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3396): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3396): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3396): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
,I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
W/ContextImpl( 3396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/SensorService( 1017): [SO] currT = 41371037000, prevT = 40911037000, diff = 460000000, [0.172 0.096 10.228],
D/SensorService( 1017): [SO] 0.172 0.096 10.228
D/SensorService( 1017): [SO] [100 -> 255]
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 7869(502KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/39MB, paused 2.121ms total 147.484ms
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,D/MenuAppsGridFragment( 1493): onResume
W/GeofencerStateMachine( 1694): Ignoring removeGeofence because network location is disabled.
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
D/ActivityManager( 1017): handle home activity for 0
I/WallpaperManagerService( 1017): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1017): post home show event for user 0
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/WallpaperManagerService( 1017):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1017): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1017): no available spell checker services found
I/SurfaceFlinger(  257): id=12 createSurf (720x1280),1 flag=4, Mauncher
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3396): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3396): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131099648
,D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ResourcesManager( 3396): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/InputDispatcher( 1017): Focus entered window: 1493
I/AMMetaDataParserService( 3396): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1493): log_dcs ThreadedRenderer::initialize entered! 
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Launcher( 1493): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/AMMetaDataParserService( 3396): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4093): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4093): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 2885 uid 10174
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/AMMetaDataParserService( 3396): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/PanelView( 1179): There is/are notification(s) 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 4093): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,I/ActivityManager( 1017): Killing 3469:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,W/ContextImpl( 3396): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/SamsungIME( 1787): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/InstanceID/Rpc( 4093): Found 10012
,W/art     ( 4169): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/OpenGLRenderer( 1493): SFEffectCache::get: create texture(0xa09c5724): name, size, mSize = 35, 146964, 329124
,D/PersonaManager( 1017): isKioskContainerExistOnDevice,
,D/CustomFrequencyManagerService( 1017): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3396): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3396): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3396): getResourcePackageName:assistant
I/AMMetaDataParserService( 3396): Resource data:2131165220
,W/ResourcesManager( 3396): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3396): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3396): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3396): getResourceTypeNamexml
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.694635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb94a3328 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb94a3058 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75),
,I/AMMetaDataParserService( 3396): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ContextImpl( 4093): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/ActivityManager( 1017): Displayed Component not be shown by security: +692ms
,E/        ( 3396): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3396): took 0.631408ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3396): Bitmap=0xb94a3178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb94b5c78 counterpartCT=4 counterpartW=96 counterparth=96
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/AMMetaDataParserService( 3396): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/SQLiteLog( 3396): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 3396): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3396): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3396): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3396): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3396): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3396): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3396): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3396): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3396): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3396): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3396): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3396): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3396): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3396): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3396): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3396): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3396): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3396): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3396): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3396): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3396): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3396): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3396): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 3396): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3396): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3396): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3396): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3396): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3396): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3396): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 3396): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3396): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3396): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 3396): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 3396): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3396): ,	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3396): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
W/System.err( 3396): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3396): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1017): Killing 3396:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/ActivityManager( 1017): retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/UsbSettingsManager( 1017): clearDefaults: com.example.hello
I/CrashAnrDetector( 1017): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1017): failed to open /acct/uid_10125/pid_3469/cgroup.procs: No such file or directory

```
