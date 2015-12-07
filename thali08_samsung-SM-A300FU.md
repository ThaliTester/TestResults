#### Test 502422852e23b2c_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
W/PhoneRestrictionPolicy( 1015): Message received - msg { when=-1ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
D/KnoxMUMContainerPolicy( 1015): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
I/KnoxMUMContainerPolicy( 1015): MSG_REMOVE_ORPHANED_CONTAINERS received
--------- beginning of system
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.eq:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
D/WIFI_P2P( 1015): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
E/WifiStateMachine( 1015): Blacklist file delete
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/WifiP2pService( 1015): P2pDisabledState{ what=143415 }
D/WifiP2pService( 1015): DefaultState{ what=143415 }
D/ConnectivityService( 1015): Got NetworkFactory Messenger for WIFI
D/ConnectivityService( 1015): Got NetworkFactory Messenger for WIFI_P2P
W/PhoneRestrictionPolicy( 1015):  >>>> deliveryBlockedMsgs
D/Tethering( 1015): Boot complete.
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
W/PhoneRestrictionPolicy( 1015): cvList size 0
W/PhoneRestrictionPolicy( 1015):  >>>> deliveryBlockedMsgs
W/PhoneRestrictionPolicy( 1015): cvList size 0
V/EnterpriseBillingEngine( 1015): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1015): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1015): getCurrentActiveProfiles - start - 
V/EnterpriseBillingPolicyStorage( 1015): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1015): handleAllprofiles - end
D/UsbHostNotification( 1015): boot completed
I/i       ( 1015): No model
D/UsbHostRestrictor( 1015): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1015): initSetUsbBlock STARTED
D/UsbHostRestrictor( 1015): SIM was never inserted
D/UsbHostRestrictor( 1015): writableHostSysNode[false]
D/UsbHostRestrictor( 1015): Can NOT Write Disable Sys Node to [ON]
D/FactoryTest( 1015): Not factory mode
D/FactoryTest( 1015): Not factory mode. isFactoryMode() returend false
D/WIFI    ( 1015): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/PersonaManagerService( 1015): ACTION_BOOT_COMPLETED
E/PersonaManagerServiceHandler( 1015):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/KnoxKeyguardUpdateMonitor( 1015): onBootComplete
D/w       ( 1015): isUserBuild = true
D/UsbStorageNotification( 1015): boot completed
,D/StorageNotification( 1174): boot completed
I/KnoxKeyguardUpdateMonitor( 1015): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1015): onTrustChanged user:0, enable:false
D/GpsLocationProvider( 1015): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
D/GpsLocationProvider_ex( 1015): BOOT_COMPLETED native_init 
D/KeyguardViewMediator( 1174): onTrustChanged( Showing = false , userId = 0 )
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
D/GpsLocationProvider( 1015): set_capabilities_callback: 55u
E/LocSvc_api_v02( 1015): I/locClientOpen:2279]: Service instance id is -1
D/SSRM:n  ( 1015): SIOP:: AP = 400
E/Geofence_Adapter( 1015): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1015): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1015): BOOT_COMPLETED native_cleanup 
D/SSRM:a  ( 1015): DeviceInfo:: 000000000000
D/SSRM:a  ( 1015): SettingsAirViewInfo:: 000000000
D/StatusBarManagerService( 1015): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
D/PhoneStatusBar( 1174): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2602): MountEmulatedStorage()
E/Zygote  ( 2602): v2
I/libpersona( 2602): KNOX_SDCARD checking this for 1000
I/libpersona( 2602): KNOX_SDCARD not a persona
I/SELinux ( 2602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SensorService( 1015): [SO] Reset Rotation Old [100], Init [1]
I/ActivityManager( 1015): Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=2602 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 2602): TimaSignature is unavailable
D/ActivityThread( 2602): Added TimaKeyStore provider
W/ContextImpl( 2602): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
I/splitIntent( 1015): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=124, mSplitNum[2]=161, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 50 receivers.size=197
I/splitIntent( 1015): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
E/Zygote  ( 2622): MountEmulatedStorage()
E/Zygote  ( 2622): v2
I/libpersona( 2622): KNOX_SDCARD checking this for 10097
I/libpersona( 2622): KNOX_SDCARD not a persona
I/SELinux ( 2622): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/qmi_secgps_clnt( 1015): qmi_secgps_client_init()
I/ActivityManager( 1015): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2622 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2622): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2622): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/qmi_secgps_clnt( 1015): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
D/qmi_secgps_clnt( 1015): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
D/qmi_secgps_clnt( 1015): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
D/TimaKeyStoreProvider( 2622): TimaSignature is unavailable
D/ActivityThread( 2622): Added TimaKeyStore provider
I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=2635 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 2635): MountEmulatedStorage()
E/Zygote  ( 2635): v2
I/libpersona( 2635): KNOX_SDCARD checking this for 1000
I/libpersona( 2635): KNOX_SDCARD not a persona
I/SELinux ( 2635): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2635): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/SecurityLogAgent( 2483): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 2483): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 2483): StateMachine : Current State = 1
D/SecurityLogAgent( 2483): BootReceiver : completed task. Failed to return wakelock . 
E/SELinux ( 2635): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2635): TimaSignature is unavailable
D/ActivityThread( 2635): Added TimaKeyStore provider
E/Zygote  ( 2655): MountEmulatedStorage()
E/Zygote  ( 2655): v2
I/libpersona( 2655): KNOX_SDCARD checking this for 10148
I/libpersona( 2655): KNOX_SDCARD not a persona
I/SELinux ( 2655): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/SensorService( 1015): [SO] currT = 30194076000, prevT = 29701167000, diff = 492909000, [-0.421 0.019 9.864]
D/SensorService( 1015): [SO] -0.421 0.019 9.864
D/SensorService( 1015): [SO] [100 -> 255]
I/SELinux ( 2655): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=2655 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
E/SELinux ( 2655): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/LocSvc_utils_cfg( 1015): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
I/qmi_secgps_clnt( 1015): SECGPS: Set AGPS Mode : 7
D/qmi_secgps_clnt( 1015): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1015): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
D/TimaKeyStoreProvider( 2655): TimaSignature is unavailable
D/ActivityThread( 2655): Added TimaKeyStore provider
W/ResourcesManager( 2635): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1015): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/qmi_secgps_clnt( 1015): SECGPS: Set XTRA enable : 1
D/qmi_secgps_clnt( 1015): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1015): SECGPS: Set GNSS RF CONFIG : 1
D/qmi_secgps_clnt( 1015): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1015): SECGPS: Set CERT TYPE : 15
D/qmi_secgps_clnt( 1015): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1015): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
V/DownloadManager( 1222): onReceive intent + android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/SecContentProvider2( 1015): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1015): mCursor = null
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/USB_UICC(  298): Timeout! No signal received. Retry num = 24
E/LocSvc_ApiV02( 1015): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
E/LocSvc_ApiV02( 1015): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
E/LocSvc_ApiV02( 1015): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
E/SQLiteLog( 2655): (284) automatic index on shooting_modes(title_id)
D/MediaScannerReceiver( 1222): action: android.intent.action.BOOT_COMPLETED
I/KnoxUsageLogPro( 2635): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
I/KnoxUsageLogPro( 2635): premStatus:2
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/KnoxUsageLogPro( 2635): savePreference: key = previous_sys_time value = 1449497272943
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/KnoxUsageLogPro( 2635): isEulaShown : false
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/KnoxUsageLogPro( 2635): KnoxUsageReceiver onReceive : not Processible, just return
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2675): MountEmulatedStorage()
I/libpersona( 2675): KNOX_SDCARD checking this for 10081
E/Zygote  ( 2675): v2
I/libpersona( 2675): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2675 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2675): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
I/KnoxUsageLogPro( 2635): savePreference: key = previous_elapsed_time value = 30381
I/SELinux ( 2675): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2675): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2691): MountEmulatedStorage()
E/Zygote  ( 2691): v2
I/libpersona( 2691): KNOX_SDCARD checking this for 1101
I/libpersona( 2691): KNOX_SDCARD not a persona
I/SELinux ( 2691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2691): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2691 uid=1101 gids={41101, 9997} abi=armeabi-v7a
E/ActivityThread( 2622): Failed to find provider info for flipboard.auth.internal.debug
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/ActivityThread( 2622): Failed to find provider info for flipboard.auth.internal
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/TimaKeyStoreProvider( 2675): TimaSignature is unavailable
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/ActivityThread( 2675): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 2691): TimaSignature is unavailable
D/ActivityThread( 2691): Added TimaKeyStore provider
D/AndroidRuntime( 2604): 
D/AndroidRuntime( 2604): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ActivityManager( 1015): Killing 1184:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
I/DrmEventReceiver( 1015): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1015): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
I/DrmEventReceiver( 1015): DrmEventReceiver : beginStartingService
I/System.out( 1015): start Service
D/AndroidRuntime( 2604): CheckJNI is OFF
D/AndroidRuntime( 2604): readGMSProperty: start
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
D/AndroidRuntime( 2604): readGMSProperty: already setted!!
D/AndroidRuntime( 2604): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2604): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2604): readGMSProperty: end
D/AndroidRuntime( 2604): addProductProperty: start
W/ResourcesManager( 2675): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2675): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2675): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2675): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2675): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
W/ResourcesManager( 2691): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
V/SmartcardService( 2691): main Received broadcast
V/SmartcardService( 2691): Starting smartcard service after boot completed
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
I/ActivityManager( 1015): Killing 1397:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/WVMDrmPlugIn(  283): WVMDrmPlugin::onInitialize : 3652
D/WVMDrmPlugIn(  283): WVMDrmPlugin::onSetOnInfoListener : add 3652
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2711): MountEmulatedStorage()
E/Zygote  ( 2711): v2
I/libpersona( 2711): KNOX_SDCARD checking this for 1000
I/libpersona( 2711): KNOX_SDCARD not a persona
I/SELinux ( 2711): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2711): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2711): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2711 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/MediaScannerService( 1222): !@start scanning volume internal: [/system/media, /oem/media]
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/MtpService( 1222): updating state; isCurrentUser=true, mMtpLocked=false
D/TP/MmsProvider( 1450): Update uri=content://mms, match=0
D/TP/MmsProvider( 1450): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1450): need read changed broadcast:false
I/Mms:transaction( 2215): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2215): [start]    nonBlockingUpdateMessageIndicator() consume time = 3697.337863
I/Mms/ReservationManager( 2215): resetAfterConnected()
D/Mms/MessagingNotification( 2215): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2215): isDefault true
D/TP/MmsProvider( 1450): Query uri=content://mms, match=0, calling pid = 2215
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_1184/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_1397/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 2711): TimaSignature is unavailable
D/ActivityThread( 2711): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1450): query,matched:7, calling pid = 2215
D/TP/MmsSmsProvider( 1450): match 7:Elapsed time : 3.019 ms
I/DrmEventService( 1015): action event :android.intent.action.BOOT_COMPLETED
I/TimaServiceEventReceiver( 1015): TimaServiceEventReceiver : onReceive
I/ANDROID_DRM_FRWORKS_DrmManager(  283): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
I/Mms/ReservationManager( 2215): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsSmsProvider( 1450): query,matched:200, calling pid = 2215
D/TP/MmsSmsProvider( 1450): match 200:Elapsed time : 2.788 ms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/SSRM:a  ( 1015): DeviceInfo:: 000000000000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/SSRM:a  ( 1015): SettingsAirViewInfo:: 000000000
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 2711): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
E/SQLiteLog( 1222): (283) recovered 463 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
E/Zygote  ( 2736): MountEmulatedStorage()
E/Zygote  ( 2736): v2
I/libpersona( 2736): KNOX_SDCARD checking this for 10043
I/libpersona( 2736): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2736 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 2736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
E/SELinux ( 2736): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/SmsReceiverService( 2215): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Mms/TelephonyPermission( 2215): isDefault true
D/Mms/SmsReceiverService( 2215): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2215): [start]    handleBootCompleted() consume time = 95.725208
E/Zygote  ( 2753): MountEmulatedStorage()
D/TimaKeyStoreProvider( 2736): TimaSignature is unavailable
I/ActivityManager( 1015): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2753 uid=10153 gids={50153, 9997} abi=armeabi-v7a
D/ActivityThread( 2736): Added TimaKeyStore provider
E/Zygote  ( 2753): v2
I/libpersona( 2753): KNOX_SDCARD checking this for 10153
I/libpersona( 2753): KNOX_SDCARD not a persona
I/SELinux ( 2753): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2753): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2753): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/CscReceiver( 1450): onReceive android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1015): name = next_alarm_formatted
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10081
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10081
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 2736): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2736): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2736): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2753): TimaSignature is unavailable
D/ActivityThread( 2753): Added TimaKeyStore provider
E/Zygote  ( 2768): MountEmulatedStorage()
E/Zygote  ( 2768): v2
I/libpersona( 2768): KNOX_SDCARD checking this for 10002
I/libpersona( 2768): KNOX_SDCARD not a persona
I/SELinux ( 2768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2768 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
E/SELinux ( 2768): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MediaScanner( 1222): Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
W/ResourcesManager( 2753): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2768): TimaSignature is unavailable
D/ActivityThread( 2768): Added TimaKeyStore provider
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 1015): name = block_emergency_message
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10043
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
E/Zygote  ( 2784): MountEmulatedStorage()
E/Zygote  ( 2784): v2
I/libpersona( 2784): KNOX_SDCARD checking this for 1000
I/ActivityManager( 1015): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2784 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/CscUpdateService( 1450): onStart
E/CscUpdateService( 1450): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1450): set_CSC_version
E/CscParser( 1450): update(): xml file exist
I/libpersona( 2784): KNOX_SDCARD not a persona
W/ActivityManager( 1015): getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
I/SELinux ( 2784): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2784): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2784): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 2675): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 125.370ms
I/art     (  308): Explicit concurrent mark sweep GC freed 8697(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 27.856ms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/TimaKeyStoreProvider( 2784): TimaSignature is unavailable
D/ActivityThread( 2784): Added TimaKeyStore provider
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 17.915ms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/TP/MmsSmsProvider( 1450): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1450): deleteConversation threadId: 9223372036854775806
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 19.308ms
D/TP/MmsSmsProvider( 1450): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1450): updateThread(), thread_id = 9223372036854775806
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
V/TP/MmsSmsDatabaseHelper( 1450): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1450): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1450): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1450): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1450): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1450): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1450): (284) automatic index on im_threads(normal_thread_id)
I/art     ( 1450): Explicit concurrent mark sweep GC freed 33280(2MB) AllocSpace objects, 6(96KB) LOS objects, 45% free, 4MB/8MB, paused 5.105ms total 158.710ms
E/Zygote  ( 2799): MountEmulatedStorage()
I/libpersona( 2799): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2799): v2
I/libpersona( 2799): KNOX_SDCARD not a persona
I/SELinux ( 2799): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/CscUtil ( 1450): isWifiOnly = false
V/MediaScanner( 1222): processDirectory :  /system/media
D/TP/SmsProvider( 1450): query,matched:0, calling pid = 2215
I/System.out( 1450): HandDataNode = null
I/CscUpdateService( 1450): PATH_CSCNAME =CustomerDataSet.CSCName
D/TP/SmsProvider( 1450): match 0:Elapsed time : 3.182 ms
I/CscUpdateService( 1450): This is normal boot : CSC not updated
I/ActivityManager( 1015): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=2799 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/TP/MmsSmsProvider( 1450): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1450): need read changed broadcast:false
E/CscParser( 1450): update(): xml file exist
I/SELinux ( 2799): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2799): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CscGPS  ( 1450): CSCGPS.updateParameters
D/CscGPS  ( 1450): supl host : null
D/CscGPS  ( 1450): SUPL Host is null or invalid
D/CscGPS  ( 1450): supl_ver : null
D/CscGPS  ( 1450): SUPL Ver is null or invalid
D/CscGPS  ( 1450): supl port : null
D/CscGPS  ( 1450): SUPL PORT is null or invalid
D/CscGPS  ( 1450): LPP : null
D/CscGPS  ( 1450): LPP is null or invalid
D/CscGPS  ( 1450): CSC don't have any AGPS value.
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/CscUpdateService( 1450): same CSC Version
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/CscUtil ( 1450): Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1015): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2813 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 1379:com.sec.android.provider.emergencymode/u0a92 (adj 15): empty #31
E/Zygote  ( 2813): MountEmulatedStorage()
E/Zygote  ( 2813): v2
I/libpersona( 2813): KNOX_SDCARD checking this for 10155
I/libpersona( 2813): KNOX_SDCARD not a persona
I/SELinux ( 2813): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
I/SELinux ( 2813): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2813): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/WifiCredService( 1292): onCreate
D/TimaKeyStoreProvider( 2799): TimaSignature is unavailable
D/ActivityThread( 2799): Added TimaKeyStore provider
D/Mms/Conversation( 2215): deleteTempConversation(),deleted=0
D/TimaKeyStoreProvider( 2813): TimaSignature is unavailable
D/ActivityThread( 2813): Added TimaKeyStore provider
V/MediaScanner( 1222):  prescan time: 343ms (DB items: 138)
V/MediaScanner( 1222):     scan time: 101ms (Caching mode: true), (makeEntry time: 40ms ~39%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
D/WifiTimerReceiver( 1292): action: android.intent.action.BOOT_COMPLETED
V/MediaScanner( 1222): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
D/WifiTimerReceiver( 1292): extra: Bundle[mParcelledData.dataSize=84]
V/MediaScanner( 1222):    total time: 444ms
D/MY_TAG  ( 1292): Action boot completed received
V/MediaScanner( 1222): checked files: 130  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1222): checkDefaultSounds
D/MediaScanner( 1222): system alarm_alert  : Vwiurug_etwofi5wgg
D/TP/SmsProvider( 1450): query,matched:51, calling pid = 2215
D/TP/SmsProvider( 1450): match 51:Elapsed time : 1.573 ms
D/SmsProvider( 1450): Update uri=content://sms/outbox, match=8
,D/TP/MmsSmsProvider( 1450): need read changed broadcast:false
E/AffinityControl( 2604): AffinityControl: registerfunction enter
D/Mms/MessagingNotification( 2215): isBlockingModeEnabled() = false, Zen mode = 0
D/Mms/SmsReceiverService( 2215): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2215): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2215): [SIM-1]sendFirstQueuedMessage()
D/TP/SmsProvider( 1450): query,matched:26, calling pid = 2215
W/ResourcesManager( 2813): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/BadgeProvider( 1557): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/TP/SmsProvider( 1450): match 26:Elapsed time : 7.852 ms
D/Mms/SmsReceiver( 2215): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2215): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2215): isDefault true
D/TP/MmsProvider( 1450): Query uri=content://mms, match=0, calling pid = 2215
D/TP/MmsSmsProvider( 1450): query,matched:200, calling pid = 2215
D/TP/MmsSmsProvider( 1450): match 200:Elapsed time : 1.614 ms
W/libprocessgroup( 1015): failed to open /acct/uid_10092/pid_1379/cgroup.procs: No such file or directory
D/TP/SmsProvider( 1450): query,matched:0, calling pid = 2215
D/TP/SmsProvider( 1450): match 0:Elapsed time : 1.488 ms
D/TP/SmsProvider( 1450): query,matched:51, calling pid = 2215
D/TP/SmsProvider( 1450): match 51:Elapsed time : 1.612 ms
D/Mms/MessagingNotification( 2215): isBlockingModeEnabled() = false, Zen mode = 0
D/BadgeProvider( 1557): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1557): sendNotify, [notify] : null
D/BadgeProvider( 1557): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1557): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1557): update, [UpdateCount] : 1
E/SQLiteLog( 2799): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
D/AndroidRuntime( 2604): Calling main entry com.android.commands.am.Am
D/Launcher.Model( 1474): reloadBadges entered.
D/Mms/MessagingNotification( 2215): setBadgeCount(), count=0
D/Mms/MessagingNotification( 2215): remove alarm
D/NearbySettings( 1292): MountReceiver.onReceive - Create HandlerThread
D/NearbySettings( 1292): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 1292): MountReceiver.onReceive - Create mPrefHandler
D/TP/SmsProvider( 1450): query,matched:0, calling pid = 2215
D/TP/SmsProvider( 1450): match 0:Elapsed time : 1.669 ms
D/[0]UMC:Core( 2813): onCreate(): 
D/BadgeProvider( 1557): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/NearbySettings( 1292): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
V/NearbySettings( 1292): MountReceiver.mPrefHandler - 7002
D/DSM     ( 2799): [Lines:107] Normal booted
D/DSM     ( 2799): [Lines:114] Boot completed
E/USB_UICC(  298): Timeout! No signal received. Retry num = 25
D/SettingsProvider( 1015): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1015): mDVFSHelper.acquire()
I/SurfaceFlinger(  258): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
E/SMD     (  289): DCD OFF
I/SurfaceFlinger(  258): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
D/[0]UMC:DeviceInfo( 2813): USA==US==
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/FocusedStackFrame( 1015): Set to : 0
I/NearbySettings( 1292): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1292): MountReceiver.onReceive - Internal Path
I/art     ( 1015): Explicit concurrent mark sweep GC freed 49575(2MB) AllocSpace objects, 20(392KB) LOS objects, 33% free, 21MB/32MB, paused 18.226ms total 249.176ms
D/MediaScanner( 1222): OK. alarm_alert is already exist in setting DB.
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
D/Launcher.HomeView( 1474): onPause
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1015): Focused application set to: xxxx
D/MediaScanner( 1222): system notification_sound  : K_Oprkltf5wgg
D/InputDispatcher( 1015): Focus left window: 1474
D/Launcher( 1474): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/AndroidRuntime( 2604): Shutting down VM
D/Mms/MessagingNotification( 2215): [end]    nonBlockingUpdateMessageIndicator() consume time = 617.379479
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, iello
D/MediaScanner( 1222): OK. notification_sound is already exist in setting DB.
D/MediaScanner( 1222): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/USER_AGENT( 2813): UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
D/[0]UMC:AdminManager( 2813): init - start
D/MediaScanner( 1222): OK. ringtone is already exist in setting DB.
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/[0]UMC:AdminManager( 2813): loadAdmins
D/MediaScannerService( 1222): !@done scanning volume internal
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/[0]UMC:AdminManager( 2813): init - end
D/GSLBManager( 2813): migrateStoredUrlFromOldPref
E/Zygote  ( 2849): MountEmulatedStorage()
E/Zygote  ( 2849): v2
I/libpersona( 2849): KNOX_SDCARD checking this for 1000
I/libpersona( 2849): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=2849 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/MediaScannerService( 1222): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/FactoryTestApp( 2510): [DummyFtClient$mBroadcastReceiver](2510) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2510): [DummyFtClient$mBroadcastReceiver](2510) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2510): [DummyFtClient$mBroadcastReceiver](2510) ACTION_MEDIA_SCANNER_FINISHED = Ignored
I/SELinux ( 2849): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2849): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2849): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/GSLBManager( 2813): migrateStoredUrlFromOldPref : Migration Not Needed
D/[0]UMC:UMCAdmin( 2813): deactivateUMCAdminIfNotRequired : -1
E/[0]UMC:Utils( 2813): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 2813): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 2813): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 2813): isContainer : 0
D/SettingsProvider( 1015): name = personal_mode_enabled
D/EnterpriseDeviceManagerService( 1015): isManagedProfileUser(): userId = 0
E/Zygote  ( 2862): MountEmulatedStorage()
I/libpersona( 2862): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2862): v2
I/libpersona( 2862): KNOX_SDCARD not a persona
I/SELinux ( 2862): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/BadgeProvider( 1557): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1557): sendNotify, [notify] : null
D/BadgeProvider( 1557): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1557): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1557): update, [UpdateCount] : 1
I/SELinux ( 2862): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=2862 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 2862): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2849): TimaSignature is unavailable
I/ActivityManager( 1015): Killing 1528:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
D/ActivityThread( 2849): Added TimaKeyStore provider
D/Mms/MessagingNotification( 2215): updateAllHistoryAsRead()
E/[0]UMC:UMCAdmin( 2813): No active admin owned by uid 10155
D/[0]UMC:UMCAdmin( 2813): isContainer : 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/[0]UMC:UMCAdmin( 2813): deactivateUMCAdmin - UMC App Admin deactivated
D/MediaProvider( 1222): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1222): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/[0]UMC:CoreReceiver( 2813): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 2813):  check PreETag 
D/TimaKeyStoreProvider( 2862): TimaSignature is unavailable
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/ActivityThread( 2862): Added TimaKeyStore provider
D/MediaProvider( 1222): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
D/MediaProvider( 1222): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1222): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1222): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1222): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1222): savePlaylistTableInBulkDeleter finished
E/Zygote  ( 2881): MountEmulatedStorage()
E/Zygote  ( 2881): v2
D/MediaScanner( 1222): Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
I/libpersona( 2881): KNOX_SDCARD checking this for 10333
I/libpersona( 2881): KNOX_SDCARD not a persona
I/SELinux ( 2881): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2881 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 2881): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2881): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/Mms/MessagingNotification( 2215): setBadgeCount(), count=0
D/Mms/MessagingNotification( 2215): remove alarm
D/Launcher.Model( 1474): reloadBadges entered.
D/TimaKeyStoreProvider( 2881): TimaSignature is unavailable
D/ActivityThread( 2881): Added TimaKeyStore provider
D/[0]UMC:ByodSetupStarter( 2813): Container ID : 0
I/ActivityManager( 1015): Killing 1798:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
W/ResourcesManager( 2849): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
V/[0]UMC:Utils( 2813): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 2813): shutdown
V/ActivityThread( 1474): updateVisibility : ActivityRecord{2a6956a4 token=android.os.BinderProxy@f5887f2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/Mms/MessagingNotification( 2215): updateAllHistoryAsRead()
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     ( 2813): System.exit called, status: 0
I/AndroidRuntime( 2813): VM exiting with result code 0, cleanup skipped.
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1015): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/Launcher.HomeView( 1474): onStop
V/ActivityThread( 1474): updateVisibility : ActivityRecord{2a6956a4 token=android.os.BinderProxy@f5887f2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
V/MediaScanner( 1222): processDirectory :  /storage/emulated/0
W/ResourcesManager( 2862): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/art     ( 2604): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/MediaScanner( 1222): Skipping:
D/MediaScanner( 1222): 7klwibgf7fvntblfd7(75ebcf7
D/PersonaManager( 1015): isKioskContainerExistOnDevice
W/ResourcesManager( 1450): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1450): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/MediaScanner( 1222): Skipping:
D/MediaScanner( 1222): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
V/MediaScanner( 1222): processDirectory :  /storage/extSdCard
W/MediaScanner( 1222): Error opening directory, reason : Permission denied.
W/MediaScanner( 1222): 7klwibgf7fxlKdCbid7
V/MediaScanner( 1222):  prescan time: 74ms (DB items: 26)
V/MediaScanner( 1222):     scan time: 64ms (Caching mode: true), (makeEntry time: 27ms ~42%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1222): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1222):    total time: 140ms
V/MediaScanner( 1222): checked files: 10  directories : 16  (I: 0, U: 0)
W/ActivityThread( 2862): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager( 1015): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2813)(adj 0) has died(45,721)
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
D/TP/SmsProvider( 1450): query,matched:0, calling pid = 2215
I/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
D/TP/SmsProvider( 1450): match 0:Elapsed time : 14.827 ms
D/Launcher( 1474): onTrimMemory. Level: 20
D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1015): [SO] activate (ident=0xb8244600, enabled=0)
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
D/SensorManager( 1015): unregisterListener ::   
I/Sensors ( 1015): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1015): [SO] changed settle time [1]
D/SensorService( 1015): [SO] setDelay [66000000]
D/daemonapp( 1729): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/SensorService( 1015): [SO] activate (ident=0xb82ccb88, enabled=1)
D/SensorService( 1015): [SO] AR_init
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/daemonapp( 1729): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1729): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/SmartcardBootCompleteReceiver( 1292): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1292): Received intent with action - android.intent.action.BOOT_COMPLETED
D/daemonapp( 1729): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/SensorManager( 1015): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/FactoryTestApp( 2510): [DummyFtClient$mBroadcastReceiver](2510) action= = android.intent.action.MEDIA_SCANNER_FINISHED
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/FactoryTestApp( 2510): [DummyFtClient$mBroadcastReceiver](2510) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/FactoryTestApp( 2510): [DummyFtClient$sendBootCompletedAndFinish](2510) ...
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/FactoryTestApp( 2510): [Support$Values.getString](2510) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2510): [ModuleCommon$isConnectionModeNone](2510) mConnectionMode = gsm
D/FactoryTestApp( 2510): [IPCWriterToSecPhoneService$ResponseWriter](2510) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2510): [IPCWriterToSecPhoneService$connectToSecPhoneService](2510)  
D/daemonapp( 1729): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/MediaScannerService( 1222): !@done scanning volume external
W/ContextImpl( 2510): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
D/daemonapp( 1729): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/comsamsunglog( 1729): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1729): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/comsamsunglog( 1729): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/comsamsunglog( 1729): [MSC_Daemon]>>> ====================================================================================================================
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/daemonapp( 1729): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/daemonapp( 1729): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
W/libprocessgroup( 1015): failed to open /acct/uid_10052/pid_1528/cgroup.procs: No such file or directory
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
W/libprocessgroup( 1015): failed to open /acct/uid_10134/pid_1798/cgroup.procs: No such file or directory
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 2862): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/ActivityManager( 1015): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2901 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 2901): MountEmulatedStorage()
I/libpersona( 2901): KNOX_SDCARD checking this for 10082
E/Zygote  ( 2901): v2
I/libpersona( 2901): KNOX_SDCARD not a persona
I/SELinux ( 2901): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
I/SELinux ( 2901): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2901): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
D/SettingsProvider( 1015): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10157
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
I/SmartcardBootCompleteReceiver( 1292): Broadcast sent with current lockscreen type
I/LcdtestApp( 2862): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10157
D/daemonapp( 1729): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1729): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
D/TimaKeyStoreProvider( 2901): TimaSignature is unavailable
D/ActivityThread( 2901): Added TimaKeyStore provider
E/Zygote  ( 2919): MountEmulatedStorage()
I/libpersona( 2919): KNOX_SDCARD checking this for 1000
E/Zygote  ( 2919): v2
I/libpersona( 2919): KNOX_SDCARD not a persona
I/SELinux ( 2919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/SensorService( 1015): [SO] Reset Rotation Old [100], Init [1]
D/daemonapp( 1729): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1729): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1729): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
E/SELinux ( 2919): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/daemonapp( 1729): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=2919 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/FactoryTestApp( 2510): [IPCWriterToSecPhoneService$onServiceConnected](2510) connected done
I/ActivityManager( 1015): Killing 2021:com.vlingo.midas/u0a28 (adj 15): empty #31
D/FactoryTestApp( 2510): [IPCWriterToSecPhoneService$write](2510) Send Response Message to SecPhone
D/FactoryTestApp( 2510): [IPCWriterToSecPhoneService$write](2510) Response ��
E/daemonapp( 1729): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1729): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/Mms/SmsReceiverService( 2215): [end]    handleBootCompleted() consume time = 410.263125
D/daemonapp( 1729): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1449497274353
D/daemonapp( 1729): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1449518820000
D/daemonapp( 1729): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1729): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
D/AT_Distributor(  312): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
D/TimaKeyStoreProvider( 2919): TimaSignature is unavailable
D/ActivityThread( 2919): Added TimaKeyStore provider
I/ActivityManager( 1015): Killing 2071:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
D/FactoryTestApp( 2510): [IPCWriterToSecPhoneService$handleMessage](2510) Send BOOTING COMPLETED done
D/daemonapp( 1729): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1449518820000
D/daemonapp( 1729): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 12
D/daemonapp( 1729): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1449518820000
D/SensorService( 1015): [SO] -0.402 0.019 9.883
D/SensorService( 1015): [SO] [100 -> 255]
D/[SBeam] ( 1292): SBeamEnabler.initPreferenceForSbeam : 0
I/DIAGMON_AGENT( 2919): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
D/AT_Distributor(  312): SetAtdStatus(), 1_1_0
D/AT_Distributor(  312): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
I/SettingSearch/SearchIntentReceiver( 1292): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1292): search setting db init!!
W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
I/SettingSearch/SearchIntentReceiver( 1292): BOOT_COMPLETED call InitSerachDBThread thread start!
E/UpdateRequestReceiver( 2901): ignoring update request
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/WebViewFactory( 2881): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
E/UpdateRequestReceiver( 2901): ignoring update request
I/iu.UploadsManager( 1778): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
E/Zygote  ( 2942): MountEmulatedStorage()
E/Zygote  ( 2942): v2
I/libpersona( 2942): KNOX_SDCARD checking this for 10146
I/libpersona( 2942): KNOX_SDCARD not a persona
I/SELinux ( 2942): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=2942 uid=10146 gids={50146, 9997} abi=armeabi-v7a
D/comdaemonstockapp( 1729): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1729): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
I/SELinux ( 2942): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2942): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/LibraryLoader( 2881): Loading: webviewchromium
I/LibraryLoader( 2881): Time to load native libraries: 5 ms (timestamps 2002-2007)
I/LibraryLoader( 2881): Expected native library version number "",actual native library version number ""
E/UpdateRequestReceiver( 2901): ignoring update request
W/libprocessgroup( 1015): failed to open /acct/uid_10028/pid_2021/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10045/pid_2071/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 2942): TimaSignature is unavailable
D/ActivityThread( 2942): Added TimaKeyStore provider
E/Zygote  ( 2961): MountEmulatedStorage()
E/Zygote  ( 2961): v2
I/libpersona( 2961): KNOX_SDCARD checking this for 1000
I/libpersona( 2961): KNOX_SDCARD not a persona
I/SELinux ( 2961): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2961): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=2961 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 2961): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/WebViewChromiumFactoryProvider( 2881): Binding Chromium to main looper Looper (main, tid 1) {39a64950}
I/LibraryLoader( 2881): Expected native library version number "",actual native library version number ""
I/chromium( 2881): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/SensorService( 1015): [SO] -0.402 0.019 9.864
D/TimaKeyStoreProvider( 2961): TimaSignature is unavailable
E/Zygote  ( 2975): MountEmulatedStorage()
E/Zygote  ( 2975): v2
I/libpersona( 2975): KNOX_SDCARD checking this for 10161
I/libpersona( 2975): KNOX_SDCARD not a persona
I/SELinux ( 2975): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2975 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/BrowserStartupController( 2881): Initializing chromium process, renderers=0
D/ActivityThread( 2961): Added TimaKeyStore provider
W/art     ( 2881): Attempt to remove local handle scope entry from IRT, ignoring
I/SELinux ( 2975): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2975): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/UpdateRequestReceiver( 2901): ignoring update request
W/chromium( 2881): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
I/SurfaceFlinger(  258): id=7 Removed Mauncher (5/8)
I/SurfaceFlinger(  258): id=7 Removed Mauncher (-2/8)
W/chromium( 2881): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 2881): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 2881): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/TimaKeyStoreProvider( 2975): TimaSignature is unavailable
D/ActivityThread( 2975): Added TimaKeyStore provider
D/BluetoothAdapter( 2881): 973326153: getState() :  mService = null. Returning STATE_OFF
W/ResourcesManager( 2961): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/DIAGMON_AGENT( 2919): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
E/UpdateRequestReceiver( 2901): ignoring update request
I/DIAGMON_AGENT( 2919): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
E/UpdateRequestReceiver( 2901): ignoring update request
I/Adreno-EGL( 2881): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 2881): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 2881): Build Date: 04/06/15 Mon
I/Adreno-EGL( 2881): Local Branch: 
I/Adreno-EGL( 2881): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 2881): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 2881):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3009): MountEmulatedStorage()
E/Zygote  ( 3009): v2
I/libpersona( 3009): KNOX_SDCARD checking this for 10088
I/libpersona( 3009): KNOX_SDCARD not a persona
I/SELinux ( 3009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3009 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3009): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 2128:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
I/art     (  308): Explicit concurrent mark sweep GC freed 8734(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 674us total 25.185ms
I/iu.UploadsManager( 1778): End new media; added: 0, uploading: 0, time: 201 ms
I/ActivityManager( 1015): Killing 1582:com.google.android.partnersetup/u0a14 (adj 15): empty #31
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 17.094ms
D/TimaKeyStoreProvider( 3009): TimaSignature is unavailable
D/ActivityThread( 3009): Added TimaKeyStore provider
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 668us total 18.818ms
I/DIAGMON_AGENT( 2919): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
I/DIAGMON_AGENT( 2919): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2919): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 2919): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
W/libprocessgroup( 1015): failed to open /acct/uid_10110/pid_2128/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10014/pid_1582/cgroup.procs: No such file or directory
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/USB_UICC(  298): Timeout! No signal received. Retry num = 26
E/Zygote  ( 3028): MountEmulatedStorage()
E/Zygote  ( 3028): v2
I/libpersona( 3028): KNOX_SDCARD checking this for 1000
I/libpersona( 3028): KNOX_SDCARD not a persona
I/SELinux ( 3028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3028 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3028): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3028): TimaSignature is unavailable
D/ActivityThread( 3028): Added TimaKeyStore provider
I/FOTA    ( 2961): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
E/Zygote  ( 3052): MountEmulatedStorage()
E/Zygote  ( 3052): v2
I/libpersona( 3052): KNOX_SDCARD checking this for 10008
I/libpersona( 3052): KNOX_SDCARD not a persona
I/SELinux ( 3052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3052): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3052 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 2975): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2975): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 3052): TimaSignature is unavailable
D/ActivityThread( 3052): Added TimaKeyStore provider
I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3028): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 3028): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
E/Zygote  ( 3067): MountEmulatedStorage()
E/Zygote  ( 3067): v2
I/libpersona( 3067): KNOX_SDCARD checking this for 10088
I/libpersona( 3067): KNOX_SDCARD not a persona
I/SELinux ( 3067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/SELinux ( 3067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3067): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3067 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,D/TimaKeyStoreProvider( 3067): TimaSignature is unavailable
,D/ActivityThread( 3067): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3028): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,V/JNIHelp ( 2975): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 2975): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2975): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ecbd727: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2975): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager( 1015): Killing 2232:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,I/DBG_DM  ( 2961): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
W/chromium( 2881): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
I/DBG_DM  ( 2961): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
I/DBG_DM  ( 2961): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
W/chromium( 2881): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3028): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3028): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3028): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2975): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/libprocessgroup( 1015): failed to open /acct/uid_10127/pid_2232/cgroup.procs: No such file or directory
,W/art     ( 2881): Attempt to remove local handle scope entry from IRT, ignoring
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/AwContents( 2881): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 2881): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 2881): *FMB* installDecor flags : 8456448
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3009): Setting receiver enabled: false
,E/Zygote  ( 3102): MountEmulatedStorage()
I/ActivityManager( 1015): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3102 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 3102): v2
I/libpersona( 3102): KNOX_SDCARD checking this for 1000
I/libpersona( 3102): KNOX_SDCARD not a persona
I/DBG_DM  ( 2961): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
I/SELinux ( 3102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_DM  ( 2961): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State,
,W/ContextImpl( 2961): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
D/SystemWebViewEngine( 2881): CordovaWebView is running on device made by: samsung
I/ActivityManager( 1015): Killing 2265:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
I/ActivityManager( 1015): Killing 1490:com.android.printspooler/u0a132 (adj 15): empty #32
I/SELinux ( 3102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Killing 2246:com.sec.tcpdumpservice/1000 (adj 15): empty #33
,E/SELinux ( 3102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 2961): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,W/art     ( 2881): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2881): Attempt to remove local handle scope entry from IRT, ignoring
,I/DBG_DM  ( 2961): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_DM  ( 2961): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,D/TimaKeyStoreProvider( 3102): TimaSignature is unavailable
,D/ActivityThread( 3102): Added TimaKeyStore provider
,E/ActivityThread( 3009): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,I/dbxyzptlk.db240408.D.h( 3009): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,I/DBG_POLICYDM( 3028): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_DM  ( 2961): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,I/DBG_DM  ( 2961): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 2961): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 2961): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_POLICYDM( 3028): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
I/DBG_DM  ( 2961): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,I/DBG_DM  ( 2961): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_DM  ( 2961): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,I/DBG_DM  ( 2961): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,I/DBG_DM  ( 2961): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 2961): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,E/DBG_POLICYDM( 3028): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,I/DBG_DM  ( 2961): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2265/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10132/pid_1490/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2246/cgroup.procs: No such file or directory
,D/OverheatReceiver( 1174): onReceive() getAction : android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 2961): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 2961): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
I/DBG_DM  ( 2961): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,I/DBG_DM  ( 2961): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
D/OpenGLRenderer( 2881): Render dirty regions requested: true
W/ContextImpl( 2961): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
I/DBG_DM  ( 2961): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/DBG_DM  ( 2961): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/PhoneWindow( 2881): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 2881): *FMB* isFloatingMenuEnabled return false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1015): Focus entered window: 2881
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 2881): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 2881): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2881): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 2881): Enabling debug mode 0
,D/OverheatReceiver( 1174): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1174): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1174): isSafeMode = false
,I/DBG_DM  ( 2961): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,I/dbxyzptlk.db240408.D.h( 3009): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,D/BootupListener( 1450): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1015): name = internet_call_settings_visibility
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 1001
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/PhoneUtilsCommon( 1450): isSupportVoLTE is false.
I/dbxyzptlk.db240408.D.h( 3009): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,I/ActivityManager( 1015): Killing 2310:com.wsomacp/u0a23 (adj 15): empty #31
,I/DBG_FMMDM( 3102): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DM  ( 2961): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,W/libprocessgroup( 1015): failed to open /acct/uid_10023/pid_2310/cgroup.procs: No such file or directory
,E/Tethering( 1015): No numeric data
,E/Tethering( 1015): No numeric data
E/Tethering( 1015): No numeric data
,E/Tethering( 1015): No numeric data
,E/Tethering( 1015): No numeric data,
,E/Tethering( 1015): No numeric data,
,D/[SBeam] ( 1292): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1292): SBeamEnabler.isSBeamSupported : EXIST
,E/Tethering( 1015): No numeric data
,E/Tethering( 1015): No numeric data
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/Tethering( 1015): No numeric data,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1174): There is/are notification(s) 
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Tethering( 1015): No numeric data
I/Timeline( 2881): Timeline: Activity_idle id: android.os.BinderProxy@2f5014b9 time:33308
,I/DBG_FMMDM( 3102): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3102): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3102): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 27
,I/ActivityManager( 1015): Displayed Component not be shown by security: +1s833ms
,D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@7
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{39f7f19e u0 com.example.hello/.MainActivity t2} time:33323
W/ActivityManager( 1015): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/Telecom ( 1427): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3137): MountEmulatedStorage()
E/Zygote  ( 3137): v2
,I/libpersona( 3137): KNOX_SDCARD checking this for 1000
I/libpersona( 3137): KNOX_SDCARD not a persona,
I/ActivityManager( 1015): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3137 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3137): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/VibratorService( 1015): hasVibrator - useVibetonz: true,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 2961): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,I/dbxyzptlk.db240408.D.h( 3009): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
E/Zygote  ( 3153): MountEmulatedStorage()
E/Zygote  ( 3153): v2
I/libpersona( 3153): KNOX_SDCARD checking this for 10052
I/libpersona( 3153): KNOX_SDCARD not a persona
,I/SELinux ( 3153): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3153): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3153): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3137): TimaSignature is unavailable
D/ActivityThread( 3137): Added TimaKeyStore provider
,I/ActivityManager( 1015): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3153 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/Telecom ( 1427): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
W/NotificationAccessSettings( 1292): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
I/SamsungIME( 1765): getCurrentCandidateView
,V/VibratorService( 1015): hasVibrator - useVibetonz: true
,V/VibratorService( 1015): hasVibrator - useVibetonz: true
,D/breakpad( 3009): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,I/DBG_DM  ( 2961): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/TimaKeyStoreProvider( 3153): TimaSignature is unavailable
,D/ActivityThread( 3153): Added TimaKeyStore provider
,I/DBG_DM  ( 2961): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,W/ResourcesManager( 1292): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/DBG_DM  ( 2961): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/chromium( 2881): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 2881): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/PCWCLIENTTRACE_LOG( 3137): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3137): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3137): new DMDBOpenHelper instance
,D/PCWCLIENTTRACE_DMContentProvider( 3137): [URIMatcher] - result : 2
,I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
,I/com.dropbox.sync.android.a( 3009): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/DBG_FMMDM( 3102): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3102): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3102): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3176 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 3176): MountEmulatedStorage()
I/libpersona( 3176): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3176): v2
I/libpersona( 3176): KNOX_SDCARD not a persona
,I/SELinux ( 3176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1015): Killing 2331:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,E/SELinux ( 3176): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/JsMessageQueue( 2881): Set native->JS mode to OnlineEventsBridgeMode
,D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@11
,D/TimaKeyStoreProvider( 3176): TimaSignature is unavailable
,D/ActivityThread( 3176): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/ScoverManager( 1292): serviceVersion : 16908288
,D/SamsungIME( 1765): Dismiss ExpandCandiate
,E/Zygote  ( 3197): MountEmulatedStorage()
E/Zygote  ( 3197): v2
I/libpersona( 3197): KNOX_SDCARD checking this for 10014
I/libpersona( 3197): KNOX_SDCARD not a persona
,I/SELinux ( 3197): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3197): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3197): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3197 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,W/libprocessgroup( 1015): failed to open /acct/uid_10039/pid_2331/cgroup.procs: No such file or directory
,V/audio_hw_primary(  284): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  284): audio_extn_get_parameters: returns 
V/msm8974_platform(  284): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  284): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  284): key: 'call_forwarding' value: ''
,V/InCall  ( 1867): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1867): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1867): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/LocationManagerService( 1015): getProviders()=[passive]
,D/ScoverManager( 1867): serviceVersion : 16908288
D/TimaKeyStoreProvider( 3197): TimaSignature is unavailable
,D/ActivityThread( 3197): Added TimaKeyStore provider
D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1867): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
I/Telecom ( 1427): ProximitySensorManager: Proximity wake lock already released
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1867): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
I/InCall  ( 1867): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1867): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1867): InCallPresenter -  - dismissCoverDialog()...
,I/InCall  ( 1867): CallSContextMotion - stopPutDownListening
,D/InCall  ( 1867): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1867): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,I/DBG_FMMDS( 3176): [50.18.150420][Line:56][onCreate] FMMDS Application Start
I/DBG_FMMDS( 3176): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,I/SamsungIME( 1765): getDebugLevel  : 0x4f4c
,D/PhoneStatusBarView( 1174): setCallBackground:0
I/ContactAccountLoggerTas( 3153): canRun() : Opted Out
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,D/VideoCallManager( 1867): Instantiating VideoCallManager
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/PCWCLIENTTRACE_DMContentProvider( 3137): [URIMatcher] - result : 2
,E/        ( 1867): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1867): took 2.166563ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1867): took 5.095990ms for 0*0 texture 0
,I/GFX raster( 1867): took 11.205260ms for 176*144 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1867): Bitmap=0xb7e12998 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7e11698 counterpartCT=4 counterpartW=176 counterparth=144
,E/DBG_FMMDS( 3176): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/com.dropbox.sync.android.ad( 3009): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,E/        ( 1867): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1867): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1867): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1867): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1867): Local Branch: 
I/Adreno-EGL( 1867): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1867): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1867):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/art     ( 1015): Explicit concurrent mark sweep GC freed 22337(1144KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 21MB/32MB, paused 2.285ms total 145.284ms
,I/DBG_FMMDS( 3176): [50.18.150420][Line:43][xdbDBInit] ,
,I/GFX GPU raster( 1867): eglCreateImageKHR: EGL_SUCCESS,
,I/glCompressedTexImage2D( 1867): took 0.408541ms for 320*61440 texture 37809
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/chromium( 2881): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 2881): 
,E/YouTube MDX( 2975): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/draw setup( 1867): took 11.084896ms for 320*240 texture 37809
E/GFX GPU raster( 1867): drawn
,I/GFX GPU raster ASTC( 1867): took 40.452554ms for 320*240 texture 12
I/GFX raster( 1867): took 40.529377ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1867): Bitmap=0xb7e12b68 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb7e12a30 counterpartCT=4 counterpartW=320 counterparth=240
,I/SamsungIME( 1765): getDebugLevel  : 0x4f4c
,E/        ( 1867): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1867): eglCreateImageKHR: EGL_SUCCESS,
I/glCompressedTexImage2D( 1867): took 0.398073ms for 480*122880 texture 37813
I/draw setup( 1867): took 0.882813ms for 480*640 texture 37813
E/GFX GPU raster( 1867): drawn
,I/GFX GPU raster ASTC( 1867): took 8.403542ms for 480*640 texture 12
,I/GFX raster( 1867): took 8.502865ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1867): Bitmap=0xb8053c40 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8053ef0 counterpartCT=4 counterpartW=480 counterparth=640
,I/SamsungIME( 1765): KeybaordView init() : load resources
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/Velvet.VelvetFactory( 3153): refreshing search history.
,E/Zygote  ( 3229): MountEmulatedStorage()
I/libpersona( 3229): KNOX_SDCARD checking this for 10090
E/Zygote  ( 3229): v2
I/libpersona( 3229): KNOX_SDCARD not a persona
I/SELinux ( 3229): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3229 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3229): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3229): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 2362:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/        ( 1867): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
I/GFX GPU raster( 1867): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1867): took 0.350990ms for 440*116864 texture 37809
I/draw setup( 1867): took 0.879844ms for 440*330 texture 37809
E/GFX GPU raster( 1867): drawn
,I/GFX GPU raster ASTC( 1867): took 4.937448ms for 440*330 texture 12
I/GFX raster( 1867): took 5.016979ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1867): Bitmap=0xb8053ef0 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb7e12a40 counterpartCT=4 counterpartW=440 counterparth=330
,D/jxcore_app_log( 2881): JniHelper::setJavaVM(0xb7a66448), pthread_self() = -1207197944
,D/JX-Cordova( 2881): jxcore cordova android initializing
,I/DBG_FMMDS( 3176): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,D/TimaKeyStoreProvider( 3229): TimaSignature is unavailable
,D/ActivityThread( 3229): Added TimaKeyStore provider
,I/DBG_FMMDS( 3176): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3176): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3176): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3176): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
E/        ( 1867): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/DBG_FMMDS( 3176): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
I/DBG_FMMDS( 3176): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
I/GFX GPU raster( 1867): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1867): took 0.462500ms for 480*163840 texture 37811
I/draw setup( 1867): took 0.965625ms for 480*640 texture 37811
E/GFX GPU raster( 1867): drawn
I/GFX GPU raster ASTC( 1867): took 6.150990ms for 480*640 texture 12
I/GFX raster( 1867): took 6.236980ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1867): Bitmap=0xb803eea0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7e11b38 counterpartCT=4 counterpartW=480 counterparth=640
,I/SamsungIME( 1765): getCurrentKeyboard
,I/SamsungIME( 1765): getTextKeyboard
,W/libprocessgroup( 1015): failed to open /acct/uid_10139/pid_2362/cgroup.procs: No such file or directory
,I/ActivityManager( 1015): Killing 2385:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,W/jxcore-log( 2881): Initializing JXcore engine
W/jxcore-log( 2881): JXcore engine is ready
,W/jxcore-log( 2881): Starting JXcore engine
,I/FOTA_Client( 3052): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 3052): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 3052): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,D/elm:15121( 3229): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 3229): ELMEngine.ELMEngine( context ).
,W/FOTA_Client( 3052): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/elm:15121( 3229): MDMBridge.setEnterpriseBridge()
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3256): MountEmulatedStorage()
,E/Zygote  ( 3256): v2
I/libpersona( 3256): KNOX_SDCARD checking this for 10013
I/libpersona( 3256): KNOX_SDCARD not a persona
,I/SELinux ( 3256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/SamsungIME( 1765): [SwiftkeyWrapper] currentLangauge : 1701729619
I/SELinux ( 3256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3256): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/        ( 1867): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/ActivityManager( 1015): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3256 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,I/GFX construct_block_size_descriptor_2d second part( 1867): took 2.560624ms for 0*0 texture 0
,I/ActivityManager( 1015): Killing 2185:com.sec.android.app.mt/1000 (adj 15): empty #31
,I/System.out( 3009): Thread-399(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 3229): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/System.out( 3009): Thread-399(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 3009): Thread-399(ApacheHTTPLog):isShipBuild true
I/System.out( 3009): Thread-399(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3009): Thread-399(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/GFX generate_partition_tables( 1867): took 7.858021ms for 0*0 texture 0
,I/GFX raster( 1867): took 12.619843ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1867): Bitmap=0xb803d7a0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8053ac8 counterpartCT=4 counterpartW=176 counterparth=144
,D/TimaKeyStoreProvider( 3256): TimaSignature is unavailable
D/ActivityThread( 3256): Added TimaKeyStore provider
,D/elm:15121( 3229): ElmAgentService : onCreate()
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10088
,E/        ( 1867): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/System.out( 3009): pool-10-thread-1 calls detatch()
,E/audit   ( 1809): type=1400 msg=audit(1449497276.746:203): avc:  denied  { ioctl } for  pid=2881 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,I/GFX construct_block_size_descriptor_2d second part( 1867): took 2.410313ms for 0*0 texture 0
E/audit   ( 1809):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1809): type=1300 msg=audit(1449497276.746:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=4 a3=beee8d58 items=0 ppid=308 ppcomm=main pid=2881 auid=4294967295 uid=10333 gid=10333 euid=10333 suid=10333 fsuid=10333 egid=10333 sgid=10333 fsgid=10333 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1809): type=1320 msg=audit(1449497276.746:203): 
D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1015): getStreamVolume 3 index 70
I/GFX generate_partition_tables( 1867): took 6.302552ms for 0*0 texture 0
I/GFX raster( 1867): took 10.790313ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1867): Bitmap=0xb8053ac8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8068a48 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1867): registerListener
,D/elm:15121( 3229): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 3229): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15121( 3229): BootCompletedState : startBootCompleted() call
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1015): registerListenerCallback : binder = android.os.BinderProxy@16903a5d, pid : 1867, uid : 1001, type : 1
,V/EmergencyMode( 1410): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,D/elm:15121( 3229): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15121( 3229): Get License : 0
,D/elm:15121( 3229): ElmAgentService : onDestroy().
,I/ActivityManager( 1015): Killing 2468:com.android.calendar/u0a131 (adj 15): empty #31
,D/InCall  ( 1867): InCallPresenter -  - Finished InCallPresenter.setUp
,V/OneTimeInitializerReceiver( 3256): OneTimeInitializerReceiver.onReceive
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2975): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2975): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2975): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,V/EmergencyMode( 1410): [EmergencyBase] setBootTime
V/EmergencyMode( 1410): [EmergencyFactory] No Recovery State, kill my self.
,W/GAV2    ( 3153): Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/OneTimeService( 3256): OneTimeService.onHandleIntent
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 28
,E/SMD     (  289): DCD OFF,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/GAV2    ( 3153): Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_2385/cgroup.procs: No such file or directory
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1015): failed to open /acct/uid_10131/pid_2468/cgroup.procs: No such file or directory
,W/jxcore-log( 2881): Platform android
W/jxcore-log( 2881): 
W/jxcore-log( 2881): Process ARCH arm
W/jxcore-log( 2881): 
,I/LockPatternUtils( 1292): isSmartCardAuthenticationAvailable: false
,E/Zygote  ( 3292): MountEmulatedStorage()
E/Zygote  ( 3292): v2
I/libpersona( 3292): KNOX_SDCARD checking this for 1000
I/libpersona( 3292): KNOX_SDCARD not a persona
,I/SELinux ( 3292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3292): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3292 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/Settings_Utils( 1292): isSupportVNFestival SM-A300FU XEO
,I/art     (  308): Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 21.387ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/ContactAccountLoggerTas( 3153): canRun() : Opted Out
,D/TimaKeyStoreProvider( 3292): TimaSignature is unavailable
D/ActivityThread( 3292): Added TimaKeyStore provider
I/jxcore-log( 2881): JXcore Cordova bridge is ready!
I/jxcore-log( 2881): 
W/jxcore-log( 2881): JXcore engine is started
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 639us total 17.429ms
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2185/cgroup.procs: No such file or directory
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 17.069ms,
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/CameraApp( 3292): CameraApp.onCreate()... mFeature : null
I/testFeature( 3292): Feature.Feature(context)
I/testFeature( 3292): Feature.readInternalDefaultXml()
I/testFeature( 3292): ResetFeatureValue
,I/CameraFirmware_broadcast( 3292): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 3292): CameraApp.getAppFeature()...
,E/Zygote  ( 3320): MountEmulatedStorage()
,E/Zygote  ( 3320): v2
I/libpersona( 3320): KNOX_SDCARD checking this for 1000
I/libpersona( 3320): KNOX_SDCARD not a persona,
,I/SELinux ( 3320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1015): Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3320 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/SELinux ( 3320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 3320): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1015): getStreamVolume 3 index 70
,I/MediaRouter( 3153): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,E/Zygote  ( 3334): MountEmulatedStorage()
E/Zygote  ( 3334): v2
I/libpersona( 3334): KNOX_SDCARD checking this for 10095
I/libpersona( 3334): KNOX_SDCARD not a persona
,W/ResourceType( 1292): Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,I/SELinux ( 3334): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3334): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3334): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourceType( 1292): Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,I/DBG_DM  ( 2961): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
I/ActivityManager( 1015): Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3334 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 2539:com.android.keychain/1000 (adj 15): empty #31
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/FavoriteContactNamesSup( 3153): get() : Execute runnable (UI thread)
,D/TimaKeyStoreProvider( 3320): TimaSignature is unavailable
,I/ContactLabelSupplier( 3153): get() : Execute runnable (UI thread)
,D/ActivityThread( 3320): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3334): TimaSignature is unavailable
,D/ActivityThread( 3334): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2539/cgroup.procs: No such file or directory
,I/ActivityManager( 1015): Killing 2602:com.mobeam.barcodeService/1000 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/jxcore-log( 2881): >> samsung-SM-A300FU
E/jxcore-log( 2881): 
,I/jxcore-log( 2881): Total memory 1451114496
I/jxcore-log( 2881): 
,I/jxcore-log( 2881): Free memory 25407488
I/jxcore-log( 2881): 
I/jxcore-log( 2881): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2881): 
I/jxcore-log( 2881): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2881): 
,E/Zygote  ( 3364): MountEmulatedStorage()
E/Zygote  ( 3364): v2
I/libpersona( 3364): KNOX_SDCARD checking this for 10055
I/libpersona( 3364): KNOX_SDCARD not a persona
,I/SELinux ( 3364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/jxcore-log( 2881): userPath [ 'www' ]
I/jxcore-log( 2881): 
I/ActivityManager( 1015): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3364 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 3364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3364): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/jxcore-log( 2881): Size 540 960
I/jxcore-log( 2881): 
,D/PreloadFilterInstaller( 3334): uses FILTER_DB_VER_1
,I/ContactLabelSupplier( 3153): get() : OptedIn = false
,I/jxcore-log( 2881): Screen Brightness 255
I/jxcore-log( 2881): 
,E/jxcore-log( 2881): Dummy Error Log.
E/jxcore-log( 2881): 
,I/Hs20UtilService( 3320): onCreate
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/SQLiteLog( 3334): (284) automatic index on titles(filter_id)
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3382): MountEmulatedStorage()
I/libpersona( 3382): KNOX_SDCARD checking this for 10018
E/Zygote  ( 3382): v2
I/libpersona( 3382): KNOX_SDCARD not a persona
,I/SELinux ( 3382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3382 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/TimaKeyStoreProvider( 3364): TimaSignature is unavailable
,D/ActivityThread( 3364): Added TimaKeyStore provider
,E/SELinux ( 3382): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Hs20UtilService( 3320): Starting #1
,I/Hs20UtilService( 3320): Message received 5003
,I/FactoryTestApp( 2510): [IPCWriterToSecPhoneService$disConnectSecPhoneService](2931)  
,I/FilterProviderReceiver( 3334): onReceive in FilterProviderReceiver
I/FilterProviderReceiver( 3334): onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2602/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3382): TimaSignature is unavailable
,D/ActivityThread( 3382): Added TimaKeyStore provider
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3399): MountEmulatedStorage()
E/Zygote  ( 3399): v2
I/libpersona( 3399): KNOX_SDCARD checking this for 10098
I/libpersona( 3399): KNOX_SDCARD not a persona
,I/SELinux ( 3399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3399): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3399 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 2483:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 2622:flipboard.boxer.app/u0a97 (adj 15): empty #31
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 3399): TimaSignature is unavailable
,D/ActivityThread( 3399): Added TimaKeyStore provider
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,I/RlzPingService( 3197): Setting next ping for 1450102077428
,I/WebViewFactory( 3153): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/UserAnalysis.PlaceProvider( 3364): PlaceProvider onCreate()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2483/cgroup.procs: No such file or directory
,I/LibraryLoader( 3153): Loading: webviewchromium
D/PackageIntentReceiver( 3399): ACTION_BOOT_COMPLETED
W/libprocessgroup( 1015): failed to open /acct/uid_10097/pid_2622/cgroup.procs: No such file or directory
,D/PackageIntentReceiver( 3399): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,I/LibraryLoader( 3153): Time to load native libraries: 5 ms (timestamps 4904-4909)
I/LibraryLoader( 3153): Expected native library version number "",actual native library version number ""
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3418): MountEmulatedStorage()
E/Zygote  ( 3418): v2
I/libpersona( 3418): KNOX_SDCARD checking this for 10099
I/libpersona( 3418): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3418 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 2635:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/UserAnalysis.SecureDbManager( 3364): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3364): SecurePlaceDbHelper() 
D/UserAnalysis( 3364): Create SecureDbHelper
,W/art     ( 3153): Attempt to remove local handle scope entry from IRT, ignoring
,D/IntelligenceServiceApplication( 3364): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3364): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 3418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/MessageQueue( 2975): Handler (android.os.Handler) {35550859} sending message to a Handler on a dead thread
W/MessageQueue( 2975): java.lang.IllegalStateException: Handler (android.os.Handler) {35550859} sending message to a Handler on a dead thread
W/MessageQueue( 2975): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 2975): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 2975): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 2975): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 2975): 	at android.os.Handler.post(Handler.java:326)
W/MessageQueue( 2975): 	at ffw.a(SourceFile:327)
W/MessageQueue( 2975): 	at guw.a(SourceFile:120)
W/MessageQueue( 2975): 	at guf.c(SourceFile:26)
W/MessageQueue( 2975): 	at gui.run(SourceFile:297)
W/MessageQueue( 2975): 	at android.os.Handler.handleCallback(Handler.java:739)
W/MessageQueue( 2975): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/MessageQueue( 2975): 	at android.os.Looper.loop(Looper.java:145)
W/MessageQueue( 2975): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 3418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3418): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 3430): MountEmulatedStorage(),
E/Zygote  ( 3430): v2,
I/libpersona( 3430): KNOX_SDCARD checking this for 10056,
I/SELinux ( 3430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/libpersona( 3430): KNOX_SDCARD not a persona
I/SELinux ( 3430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ContextImpl( 1851): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
E/SELinux ( 3430): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3430 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3382): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 07 15:07:57 GMT+01:00 2015
I/ActivityManager( 1015): Killing 2655:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,D/IntelligenceServiceApplication( 3364): no applications having user consent for prediction
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1851): Service started flags 0 startId 1
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/SecUISvc( 1851): Thread created.
,D/TimaKeyStoreProvider( 3418): TimaSignature is unavailable
,D/ActivityThread( 3418): Added TimaKeyStore provider
,E/Zygote  ( 3453): MountEmulatedStorage()
I/libpersona( 3453): KNOX_SDCARD checking this for 10026
E/Zygote  ( 3453): v2
I/libpersona( 3453): KNOX_SDCARD not a persona
,I/SELinux ( 3453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3453): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3430): TimaSignature is unavailable
D/ActivityThread( 3430): Added TimaKeyStore provider
,I/ActivityManager( 1015): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3453 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3382): KLMSAbstractReciever(): onReceive().END.
,V/VibratorService( 1015): hasVibrator - useVibetonz: true
,D/TimaKeyStoreProvider( 3453): TimaSignature is unavailable
,D/ActivityThread( 3453): Added TimaKeyStore provider
,V/PlaceDetection v1.0.19 ( 3364): [PlaceDetection::stopService] Service stopped.
,I/KLMS-2.5.123: ( 3382): KLMSIntentService(): onCreate()
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2635/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3382): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3382): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3382): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  ( 3473): MountEmulatedStorage()
E/Zygote  ( 3473): v2
I/libpersona( 3473): KNOX_SDCARD checking this for 10020
I/libpersona( 3473): KNOX_SDCARD not a persona
,I/SELinux ( 3473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/KLMS-2.5.123: ( 3382): KLMSIntentService(): BOOT_COMPLETED
,I/ActivityManager( 1015): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3473 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a,
,I/SELinux ( 3473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3473): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1015): failed to open /acct/uid_10148/pid_2655/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3473): TimaSignature is unavailable
,D/ActivityThread( 3473): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3382): KLMSIntentService(): onDestroy()
,V/PlaceDetection v1.0.19 ( 3364): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3364): Constructor Preference
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3492): MountEmulatedStorage()
E/Zygote  ( 3492): v2
I/libpersona( 3492): KNOX_SDCARD checking this for 1000
I/libpersona( 3492): KNOX_SDCARD not a persona
,I/SELinux ( 3492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3492): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3492 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 2196:com.sec.modem.settings/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3492): TimaSignature is unavailable
,D/ActivityThread( 3492): Added TimaKeyStore provider
,I/LockPatternUtils( 1292): isSmartCardAuthenticationAvailable: false
,E/MTPRx   ( 3492): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,I/jxcore-log( 2881): getBuffer is called!!!!
I/jxcore-log( 2881): 
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedState
D/SecContentProvider2( 1015): mCursor = null
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2196/cgroup.procs: No such file or directory
,D/SecContentProvider2( 1015): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1015): mCursor = null
,V/MTPRx   ( 3492): sealedState: false
V/MTPRx   ( 3492): sealedUsbMassStorageState: false
,D/SettingsProvider( 1015): name = mtp_usb_connection_status
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 29
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SettingsProvider( 1015): name = media_player_mode
,I/sCloudBackupApp( 3430): sCloudBackupApp Version Info : 4.04.7.KK_APP
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/ActivityManager( 1015): Killing 2087:flipboard.app/u0a96 (adj 15): empty #31
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10052
,E/Zygote  ( 3512): MountEmulatedStorage(),
E/Zygote  ( 3512): v2
,I/libpersona( 3512): KNOX_SDCARD checking this for 10058
I/libpersona( 3512): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3512 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 3512): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1015): Killing 2691:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,D/SettingsProvider( 1015): name = mtp_usb_conditions_met
I/SELinux ( 3512): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3512): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,W/NetworkUtils( 3153): OkHttp exception
,D/SettingsProvider( 1015): name = mtp_running_status
,I/art     (  308): Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 35.792ms
,D/TimaKeyStoreProvider( 3512): TimaSignature is unavailable
,D/ActivityThread( 3512): Added TimaKeyStore provider
,I/ContactAccountLoggerTas( 3153): canRun() : Opted Out
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 23.574ms
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1015): name = media_mount_count
,D/SettingsProvider( 1015): name = mtp_sync_alive
,I/DBG_DM  ( 2961): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 617us total 17.909ms
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1015): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/SettingsProvider( 1015): name = boot_time_connected
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/SettingsProvider( 1015): name = mtp_open_session
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,I/PCWCLIENTTRACE_PushUtil( 3137): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3137): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3137): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3137): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3137): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3137): ACTION_BOOTUP - Push type: [SPP, GCM]
,W/PCWCLIENTTRACE_PCWHandler( 3137): [ensureRegistration] - netwrok is not available. action ignored
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/BatteryService( 1015): level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 3535): MountEmulatedStorage()
E/Zygote  ( 3535): v2
I/libpersona( 3535): KNOX_SDCARD checking this for 10028
I/libpersona( 3535): KNOX_SDCARD not a persona
,I/SELinux ( 3535): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ExternalOEMControlProvider( 3512): onCreate
I/ActivityManager( 1015): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3535 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 3535): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3535): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1015): failed to open /acct/uid_1101/pid_2691/cgroup.procs: No such file or directory
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,W/libprocessgroup( 1015): failed to open /acct/uid_10096/pid_2087/cgroup.procs: No such file or directory
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/PowerUI ( 1174): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1174): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/EmergencyMode( 1410): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1410): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3551): MountEmulatedStorage()
I/libpersona( 3551): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3551): v2
I/libpersona( 3551): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3551 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Killing 2215:com.android.mms/u0a41 (adj 15): empty #31
,I/SELinux ( 3551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3551): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1015): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10058
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,D/SettingsProvider( 1015): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10058
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/TimaKeyStoreProvider( 3535): TimaSignature is unavailable
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/ActivityThread( 3535): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3551): TimaSignature is unavailable
,D/ActivityThread( 3551): Added TimaKeyStore provider
,W/ResourcesManager( 3551): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/CountryDetector( 1015): No listener is left
,I/Gmail   ( 3418): getAccountsCursor
,I/Gmail   ( 3418): Observing account changes for notifications
,W/libprocessgroup( 1015): failed to open /acct/uid_10041/pid_2215/cgroup.procs: No such file or directory
,I/ServiceMode( 3551): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3551): setReferenceIsDumpState : 0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3577): MountEmulatedStorage()
E/Zygote  ( 3577): v2
I/libpersona( 3577): KNOX_SDCARD checking this for 1000
I/libpersona( 3577): KNOX_SDCARD not a persona
,I/SELinux ( 3577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3577 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3577): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 2736:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3453): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/TimaKeyStoreProvider( 3577): TimaSignature is unavailable
,D/ActivityThread( 3577): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/NPS_WSSNPS( 3577): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3577): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3577): [] Service onCreate!!
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3596): MountEmulatedStorage()
E/Zygote  ( 3596): v2
I/libpersona( 3596): KNOX_SDCARD checking this for 1000
I/libpersona( 3596): KNOX_SDCARD not a persona
,I/SELinux ( 3596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1015): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3596 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3596): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/NPS_WSSNPS( 3577): [50.150321] NpsServiceTask Start
,W/libprocessgroup( 1015): failed to open /acct/uid_10043/pid_2736/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3596): TimaSignature is unavailable
,D/ActivityThread( 3596): Added TimaKeyStore provider
,D/NPS_WSSNPS( 3577): [50.150321] smlDBHelper
,D/SettingsProvider( 1015): name = access_control_enabled
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3615): MountEmulatedStorage()
,E/Zygote  ( 3615): v2
I/libpersona( 3615): KNOX_SDCARD checking this for 10065
,I/libpersona( 3615): KNOX_SDCARD not a persona
I/SELinux ( 3615): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3615): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3615 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 3615): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 2753:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
W/GAV2    ( 3418): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
I/ActivityManager( 1015): Killing 2784:com.sec.usbsettings/1000 (adj 15): empty #31
,W/ContextImpl( 1292): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/SettingSearch/SearchIntentReceiver( 1292): InitSerachDBThread thread end!
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NPS_WSSNPS( 3577): [50.150321] AsyncBulkFlagCheck
,D/TimaKeyStoreProvider( 3615): TimaSignature is unavailable
,D/ActivityThread( 3615): Added TimaKeyStore provider
,I/NPS_WSSNPS( 3577): [50.150321] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 3577): [50.150321] IsRemain_Asyncing nothing
,W/ContextImpl( 3577): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3577): [50.150321] Service onDestroy
,D/FileShare-Server( 3615): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/ActivityManager( 1015): Killing 2675:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,I/System.out( 3535): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 3535): Inside WakeupProvider
,W/libprocessgroup( 1015): failed to open /acct/uid_10153/pid_2753/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/NPS_WSSNPS( 3577): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 3577): [50.150321] smlBRMessageDelete
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
I/NPS_WSSNPS( 3577): [50.150321] smlBREmailDelete
I/NPS_WSSNPS( 3577): [50.150321] smlBRNetworkDelete
,I/NPS_WSSNPS( 3577): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 3577): [50.150321] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 3577): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3577): [50.150321] smlBRSMemoDelete
,I/NPS_WSSNPS( 3577): [50.150321] cpuBooster release : false
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/NPS_WSSNPS( 3577): [50.150321] dsServerSocket close
,I/ActivityManager( 1015): Killing 2799:com.sec.dsm.system/1000 (adj 15): empty #31
,I/VlingoApplication( 3535): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 30
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2784/cgroup.procs: No such file or directory
,E/Gmail   ( 3418): Error finding the version of the Email provider.....
E/Gmail   ( 3418): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3418): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3418): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3418): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3418): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3418): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 3418): We do not support migrating this version of the Email provider.
,D/BluetoothAdapter( 3535): 793777337: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3535): 793777337: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3535): 793777337: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 3535): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/Gmail   ( 3418): getAccountsCursor
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1015): failed to open /acct/uid_10081/pid_2675/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2799/cgroup.procs: No such file or directory
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 3453): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,E/SQLiteLog( 3418): (283) recovered 11 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,E/USB_UICC(  298): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  298): usb_uicc_init_qmi failed ! 
I/USB_UICC(  298): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  298): usb_uicc_cleanup, Issuing QMI deinit ... 
,W/Settings( 3453): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3453): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 26814(1489KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 22MB/33MB, paused 2.150ms total 142.487ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
I/DBG_DM  ( 2961): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,E/File    ( 3418): fail readDirectory() errno=2
,I/ActivityManager( 1015): Killing 2849:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,I/Gmail   ( 3418): notifyAccountChanged
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1015): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,I/Gmail   ( 3418): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3418): getAccountsCursor
E/Zygote  ( 3669): MountEmulatedStorage()
I/libpersona( 3669): KNOX_SDCARD checking this for 10102
E/Zygote  ( 3669): v2
I/libpersona( 3669): KNOX_SDCARD not a persona
,I/SELinux ( 3669): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3669): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3669 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/SELinux ( 3669): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3680): MountEmulatedStorage()
I/libpersona( 3680): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3680): v2
I/libpersona( 3680): KNOX_SDCARD not a persona
I/SELinux ( 3680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3680 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3669): TimaSignature is unavailable
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2849/cgroup.procs: No such file or directory
,D/ActivityThread( 3669): Added TimaKeyStore provider
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 3680): TimaSignature is unavailable
,D/ActivityThread( 3680): Added TimaKeyStore provider
,W/ActivityManager( 1015): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/ActivityThread( 3418): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@3a93365e that was originally bound here
E/ActivityThread( 3418): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@3a93365e that was originally bound here
E/ActivityThread( 3418): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3418): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3418): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3418): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3418): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3418): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3418): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3418): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3418): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3418): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3418): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3418): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3418): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3418): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/GoogleHttpClient( 1602): GMS http client unavailable, use old client
,D/VlingoApplication( 3535): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3535): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
W/ActivityManager( 1015): Unbind failed: could not find connection for android.os.BinderProxy@17e39ddd
,D/DialogFlow( 3535): initQueue()
,I/Gmail   ( 3418): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/FactoryTestApp( 2510): [DummyFtClient$onDestroy](2510) Destroy DummyFtClient service
,I/art     ( 1602): Explicit concurrent mark sweep GC freed 9408(699KB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 7MB/12MB, paused 1.415ms total 86.351ms
,D/FactoryTestApp( 2510): [Support$Values.getString](2510) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2510): [ModuleCommon$isConnectionModeNone](2510) mConnectionMode = gsm
I/FactoryTestApp( 2510): [ModuleCommon$isRunningFtClient](2510) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2510): [DummyFtClient$onDestroy](2510) kill process
I/Process ( 2510): Sending signal. PID: 2510 SIG: 9
,W/ResourcesManager( 3669): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Gmail   ( 3418): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3418): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3706): MountEmulatedStorage()
E/Zygote  ( 3706): v2
I/libpersona( 3706): KNOX_SDCARD checking this for 10029
I/libpersona( 3706): KNOX_SDCARD not a persona
,I/SELinux ( 3706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/Volley  ( 3453): [491] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3453): [498] DiskBasedCache.clear: Cache cleared.
,I/SELinux ( 3706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3706): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3706 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/Ads     ( 3453): Skipping gmscore version check
I/ActivityManager( 1015): Killing 2862:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1015): Process com.sec.factory (pid 2510)(adj 0) has died(33,692)
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 3706): TimaSignature is unavailable
D/ActivityThread( 3706): Added TimaKeyStore provider
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 3680): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2862/cgroup.procs: No such file or directory
,E/Zygote  ( 3723): MountEmulatedStorage()
,E/Zygote  ( 3723): v2
I/libpersona( 3723): KNOX_SDCARD checking this for 1000
I/SELinux ( 3723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3723): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3723 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/Finsky  ( 3453): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/SELinux ( 3723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/Finsky  ( 3453): [1] Libraries$2.run: Finished loading 1 libraries.
,E/SELinux ( 3723): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3723): TimaSignature is unavailable
,D/ActivityThread( 3723): Added TimaKeyStore provider
,W/ResourcesManager( 3723): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ContextImpl( 3723): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3741): MountEmulatedStorage()
E/Zygote  ( 3741): v2
I/libpersona( 3741): KNOX_SDCARD checking this for 10030
I/libpersona( 3741): KNOX_SDCARD not a persona
,I/SELinux ( 3741): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3741): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1015): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3741 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 3741): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 1557:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,I/F_PHONE ( 3723): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3723): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/art     ( 1778): Suspending all threads took: 9.165ms,
I/libpersona( 3755): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3755): MountEmulatedStorage()
,I/libpersona( 3755): KNOX_SDCARD not a persona
E/Zygote  ( 3755): v2
,I/SELinux ( 3755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/Finsky  ( 3453): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager( 1015): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3755 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3755): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/TimaKeyStoreProvider( 3741): TimaSignature is unavailable
,D/TimaKeyStoreProvider( 3755): TimaSignature is unavailable
D/ActivityThread( 3741): Added TimaKeyStore provider
D/ActivityThread( 3755): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 8754(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 48.883ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 36.483ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 17.707ms
,W/libprocessgroup( 1015): failed to open /acct/uid_10068/pid_1557/cgroup.procs: No such file or directory
,W/ResourcesManager( 3755): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/F_PHONE ( 3723): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3723): default registerAction()
I/F_PHONE ( 3723): [[com.sec.bcservice]] sendPendingMessage()
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BluetoothBDAdrressReceiver( 3755): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3755): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,W/ResourcesManager( 1450): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1450): onCreate()
,E/BluetoothBDTestService( 1450): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1450): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1450): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,I/Gmail   ( 3418): getAccountsCursor
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1015): waitForAlarm result :8,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DBG_DM  ( 2961): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/Finsky  ( 3453): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/Babel   ( 3669): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3669): MmsConfig.loadMmsSettings
I/Babel   ( 3669): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 3669): MmsConfig.loadFromDatabase
,D/accuweather( 1684): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1684): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1684): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
D/accuweather( 1684): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1684): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! ,
D/accuweather( 1684): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1684): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
,D/accuweather( 1684): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1684): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,E/accuweather( 1684): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 08
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/Settings( 3669): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Babel   ( 3669): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3669): MmsConfig.loadFromResources
,E/Babel   ( 3669): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3669): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,I/System.out( 3535): INFO:Resource not found:/Common.properties Using default values
,I/ActivityManager( 1015): Killing 2919:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/VideoCapabilities( 3669): Unrecognized profile 2130706433 for video/avc
,W/art     ( 3535): Suspending all threads took: 7.986ms
,W/AudioCapabilities( 3669): Unsupported mime audio/evrc
,W/AudioCapabilities( 3669): Unsupported mime audio/qcelp
,W/ResourcesManager( 3741): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3741): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3741): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/AudioCapabilities( 3669): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3669): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 3669): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3669): Unsupported mime audio/x-ima
,W/AudioCapabilities( 3669): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3669): Unsupported mime audio/evrc
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
V/Babel   ( 3669): babel boot account: SMS
V/Babel   ( 3669): babel boot account: thalitester@gmail.com
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 3669): Unsupported mime video/wvc1
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/VideoCapabilities( 3669): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3669): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 3669): Unsupported mime video/wvc1
,W/VideoCapabilities( 3669): Unsupported mime video/x-ms-wmv
E/Zygote  ( 3796): MountEmulatedStorage()
E/Zygote  ( 3796): v2
I/libpersona( 3796): KNOX_SDCARD checking this for 1000
I/libpersona( 3796): KNOX_SDCARD not a persona
I/SELinux ( 3796): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3796): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3796): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3796 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 2942:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/VideoCapabilities( 3669): Unsupported mime video/x-ms-wmv7
,D/TimaKeyStoreProvider( 3796): TimaSignature is unavailable
,W/VideoCapabilities( 3669): Unsupported mime video/x-ms-wmv8
,D/ActivityThread( 3796): Added TimaKeyStore provider
W/ResourcesManager( 3741): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3741): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3741): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/AlarmManager( 1015): waitForAlarm result :4
,W/VideoCapabilities( 3669): Unsupported mime video/mp43
,W/VideoCapabilities( 3669): Unsupported mime video/sorenson
,W/ResourcesManager( 3741): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
,W/ResourcesManager( 3741): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,V/AlarmManager( 1015): waitForAlarm result :4
,W/VideoCapabilities( 3669): Unsupported mime video/mp4v-esdp
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_2919/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10146/pid_2942/cgroup.procs: No such file or directory
,I/Icing   ( 1778): Storage manager: low false usage 2.01MB avail 8.51GB capacity 9.90GB
,I/VideoCapabilities( 3669): Unsupported profile 4 for video/mp4v-es
,D/FileApkUtils( 1778): Spent 91ms computing apk sha1.
,D/FileApkUtils( 1778): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1778): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3680): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3680): Resource data:2131165186
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3680): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3680): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3680): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3680): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3680): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3680): getResourceTypeNamexml
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3680): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,E/Zygote  ( 3819): MountEmulatedStorage(),
E/Zygote  ( 3819): v2
I/libpersona( 3819): KNOX_SDCARD checking this for 1000
I/libpersona( 3819): KNOX_SDCARD not a persona
,I/SELinux ( 3819): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3819 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
I/SELinux ( 3819): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Killing 2901:com.google.android.configupdater/u0a82 (adj 15): empty #31
,E/SELinux ( 3819): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/DexOptUtils( 1778): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad/MapsModule.apk is already optimized. Bailing.
,I/AMMetaDataParserService( 3680): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,D/FileApkUtils( 1778): Keeping up-to-date module: module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad
,D/TimaKeyStoreProvider( 3819): TimaSignature is unavailable
,D/ActivityThread( 3819): Added TimaKeyStore provider
,D/GmsModuleFndr( 1778): Beginning GMS chimera module scan
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,E/KnoxSetupWizardClient( 3819): isShipMode : 1
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
I/KnoxSetupWizardClient( 3819): onReceive : android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1015): failed to open /acct/uid_10082/pid_2901/cgroup.procs: No such file or directory
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 3680): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
W/ContextImpl( 3680): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
D/GmsModuleFndr( 1778): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 1778): Beginning module configuration check
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3706): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ShortcutReceiver( 3819):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/ChimeraCfgMgr( 1778): Module APKs unchanged, check complete
,D/KnoxShortcutUtil( 3819): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 3819):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 3819):  shortcut migration not required 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:assistant
I/AMMetaDataParserService( 3680): Resource data:2131034113
,W/ResourcesManager( 3680): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3680): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3680): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3680): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3680): getResourceTypeNamexml
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3,
,W/System.err( 3819): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub,
W/System.err( 3819): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3819): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3819): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
,W/System.err( 3819): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3819): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3819): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/GFX construct_block_size_descriptor_2d second part( 3680): took 11.820261ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3680): took 15.273802ms for 0*0 texture 0
,E/Zygote  ( 3852): MountEmulatedStorage(),
I/GFX raster( 3680): took 32.249013ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e330e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e3bf48 counterpartCT=4 counterpartW=96 counterparth=96
E/Zygote  ( 3852): v2
I/libpersona( 3852): KNOX_SDCARD checking this for 1000
I/libpersona( 3852): KNOX_SDCARD not a persona
,I/SELinux ( 3852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3852 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 3852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1015): Killing 3009:com.dropbox.android/u0a88 (adj 15): empty #31
E/SELinux ( 3852): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3680): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/TimaKeyStoreProvider( 3852): TimaSignature is unavailable
,D/ActivityThread( 3852): Added TimaKeyStore provider
,D/GCM     ( 1778): COMPAT: Multi user not supported
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.830364ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e330e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e19c10 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3706): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3706): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3706): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1602): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3680): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3680): took 2.484635ms for 0*0 texture 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
I/CheckinService( 1778): Checkin interval check for package: unspecified last checkin: 1449011761246 min interval config: 0 actual interval: 485519810
,I/GFX generate_partition_tables( 3680): took 9.920105ms for 0*0 texture 0
,I/GFX raster( 3680): took 13.428751ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7bb1410 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e21d48 counterpartCT=4 counterpartW=96 counterparth=96
I/GCoreUlr( 1778): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3680): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
I/GCoreUlr( 1617): DispatchingService.onCreate()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_DM  ( 2961): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,I/CheckinService( 1778): Disabling old GoogleServicesFramework version
,W/libprocessgroup( 1015): failed to open /acct/uid_10088/pid_3009/cgroup.procs: No such file or directory
,D/StatusChecker( 3852): onReceive : android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 3852): onReceive : net.mt.init : DONE
I/Process ( 3741): Sending signal. PID: 3741 SIG: 9
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 1778): onCreate
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3880): MountEmulatedStorage()
E/Zygote  ( 3880): v2
I/libpersona( 3880): KNOX_SDCARD checking this for 10113
I/libpersona( 3880): KNOX_SDCARD not a persona
,I/SELinux ( 3880): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3880): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1015): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3880 uid=10113 gids={50113, 9997} abi=armeabi-v7a
E/SELinux ( 3880): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 3028:com.policydm/1000 (adj 15): empty #31
,D/SystemUpdateService( 1778): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,V/AuthZen ( 1778): Handling intent: android.intent.action.BOOT_COMPLETED
,I/GFX raster( 3680): took 0.622865ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7a6d2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e19c10 counterpartCT=4 counterpartW=96 counterparth=96
,D/AuthZenEventHandler( 1778): Handling event: android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 3880): TimaSignature is unavailable
,D/ActivityThread( 3880): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3680): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/ActivityManager( 1015): Process com.sec.android.app.sns3 (pid 3741)(adj 0) has died(35,680)
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3900): MountEmulatedStorage()
E/Zygote  ( 3900): v2
I/libpersona( 3900): KNOX_SDCARD checking this for 10031
I/libpersona( 3900): KNOX_SDCARD not a persona
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SELinux ( 3900): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/GFX raster( 3680): took 0.841666ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e21d48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e21ff8 counterpartCT=4 counterpartW=96 counterparth=96
I/SELinux ( 3900): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=3900 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 3900): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3680): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3028/cgroup.procs: No such file or directory
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3900): TimaSignature is unavailable
,D/ActivityThread( 3900): Added TimaKeyStore provider
,W/art     ( 1778): Suspending all threads took: 10.195ms
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.752656ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e19c10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e21ff8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3680): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/art     ( 1778): Background sticky concurrent mark sweep GC freed 9571(894KB) AllocSpace objects, 16(256KB) LOS objects, 16% free, 7MB/8MB, paused 35.898ms total 157.350ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PageBuddyNotiSvc( 3880): Intent received : action=android.intent.action.BOOT_COMPLETED
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.911666ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e21ff8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ac0cc8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ContextImpl( 3880): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/SystemUpdateService( 1778): cancelUpdate (empty URL)
I/AMMetaDataParserService( 3680): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/SystemUpdateService( 1778): active receiver: disabled
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PageBuddyNotiSvc( 3880): onCreate mCpBitFlag=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.531614ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7bb19d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e21608 counterpartCT=4 counterpartW=96 counterparth=96
,I/CheckinService( 1778): Checking schedule, now: 1449497281413 next: 1449578688177
,I/CheckinService( 1778): active receiver: disabled
,E/Zygote  ( 3919): MountEmulatedStorage()
,I/libpersona( 3919): KNOX_SDCARD checking this for 10121
E/Zygote  ( 3919): v2
I/libpersona( 3919): KNOX_SDCARD not a persona
I/SELinux ( 3919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/AMMetaDataParserService( 3680): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3919 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 3919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3919): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1617): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:assistant
I/AMMetaDataParserService( 3680): Resource data:2131034113
,I/AMMetaDataParserService( 3680): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3680): getResourceTypeNamexml
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.813281ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e330e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e21608 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3919): TimaSignature is unavailable
,W/BaseAppContext( 1778): Using Auth Proxy for data requests.
D/ActivityThread( 3919): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3680): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.812553ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e330e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e21608 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3680): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3919): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3919): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3919): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3937): MountEmulatedStorage(),
E/Zygote  ( 3937): v2
I/libpersona( 3937): KNOX_SDCARD checking this for 1000
I/libpersona( 3937): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=3937 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 3937): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1015): Killing 3067:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,I/SELinux ( 3937): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
W/ActivityManager( 1015): userId = 0, bbcId = -10000,
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SELinux ( 3937): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3680): took 0.596718ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7bb1410 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e21608 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3937): TimaSignature is unavailable
I/AMMetaDataParserService( 3680): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
D/ActivityThread( 3937): Added TimaKeyStore provider
,D/QuickConnect( 3919): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.626823ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7a6d2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e21608 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3680): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530,
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.821719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e21d48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e21608 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3680): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/SettingsProvider( 1015): name = scon_is_running
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
D/SettingsProvider( 1015): selectionArgs: 10121
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 32017(1872KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/33MB, paused 25.236ms total 207.737ms
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.652969ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e19c10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7df2f90 counterpartCT=4 counterpartW=96 counterparth=96
,W/BackupManagerService( 1015): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 3919): Utils.setQCRunningSetting - set : 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3680): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/QuickConnect( 3919): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.679896ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e21ff8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e21608 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3680): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
I/SecKeyguardClockSingleView( 1174): Ignore. Because it is same clock text
,D/ChimeraCfgMgr( 1778): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/QuickConnect( 3919): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3961): MountEmulatedStorage()
E/Zygote  ( 3961): v2
I/libpersona( 3961): KNOX_SDCARD checking this for 10127
I/libpersona( 3961): KNOX_SDCARD not a persona
,I/ActivityManager( 1015): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3961 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 3961): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1015): Killing 3102:com.fmm.dm/1000 (adj 15): empty #31
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SELinux ( 3961): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3961): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/AuthZen ( 1778): Fetching signing key...
,I/GAV2    ( 3153): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.660625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7bb19d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7df2f90 counterpartCT=4 counterpartW=96 counterparth=96
,W/Kids    ( 1778): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 1778): [KidAccountFixer] No network connection
,D/TimaKeyStoreProvider( 3961): TimaSignature is unavailable
,D/ActivityThread( 3961): Added TimaKeyStore provider
,I/AuthZen ( 1778): Signing key fetched successfully!
,D/SystemUpdateService( 1778): onDestroy
,W/Auth    ( 1602): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/AMMetaDataParserService( 3680): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3680): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3680): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3680): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3680): getResourcePackageName:assistant
I/AMMetaDataParserService( 3680): Resource data:2131034112
,I/DBG_POLICYDM( 3937): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/AMMetaDataParserService( 3680): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3680): getResourceTypeNamexml
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3680): took 0.637240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7a6d2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e21608 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 3961): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3961): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3961): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3961): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/BaseAppContext( 1778): Using Auth Proxy for data requests.
I/DBG_POLICYDM( 3937): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup( 1015): failed to open /acct/uid_10088/pid_3067/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3102/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3680): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,W/GCoreFlp( 1617): No location to return for getLastLocation()
,W/FusedLocationProvider( 1778): location=null,
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.596146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7a6d2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7df2f90 counterpartCT=4 counterpartW=96 counterparth=96
,V/GmsCoreStatsServiceLauncher( 1778): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,I/AMMetaDataParserService( 3680): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530,
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1602): Explicit concurrent mark sweep GC freed 7413(414KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 7MB/13MB, paused 2.182ms total 63.319ms
,I/DBG_POLICYDM( 3937): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3937): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.644115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e21608 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7df2f90 counterpartCT=4 counterpartW=96 counterparth=96
D/a       ( 1778): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 1778): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1778): Clearing transaction cache
,I/DBG_POLICYDM( 3937): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/AMMetaDataParserService( 3680): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,I/DBG_POLICYDM( 3937): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 3937): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,D/PersistentNotificationBroadcastReceiver( 1602): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/DBG_POLICYDM( 3937): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,I/DBG_POLICYDM( 3937): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 3937): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/GCoreFlp( 1617): No location to return for getLastLocation()
,W/FusedLocationProvider( 1778): location=null
I/GFX raster( 3680): took 0.955572ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e19c10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7df2f90 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 3937): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3937): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3937): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3937): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,I/DBG_POLICYDM( 3937): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,W/art     ( 1778): Suspending all threads took: 8.200ms
,I/AMMetaDataParserService( 3680): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,D/SBrowserFeatureFlag( 3961): initialized in static block : loadCscFeatureValue() succeed! 
I/art     ( 1778): Background partial concurrent mark sweep GC freed 10007(830KB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 8MB/13MB, paused 11.410ms total 65.789ms
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:assistant
I/AMMetaDataParserService( 3680): Resource data:2131034113,
,I/AMMetaDataParserService( 3680): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3680): getResourceTypeNamexml
E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/DBG_DM  ( 2961): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
I/GFX raster( 3680): took 0.875783ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7df2f90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7a6d2c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 3937): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 3937): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 3937): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3680): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3990): MountEmulatedStorage()
,E/Zygote  ( 3990): v2
I/libpersona( 3990): KNOX_SDCARD checking this for 10032
I/libpersona( 3990): KNOX_SDCARD not a persona
,I/SELinux ( 3990): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3990): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1015): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=3990 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 3176:com.fmm.ds/1000 (adj 15): empty #31
E/SELinux ( 3990): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3680): took 0.870417ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7df2f90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7bb1410 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 3990): TimaSignature is unavailable
D/ActivityThread( 3990): Added TimaKeyStore provider
,D/ManifestProvider( 3961): onCreate()
,I/DBG_POLICYDM( 3937): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 3937): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/AMMetaDataParserService( 3680): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/DBG_POLICYDM( 3937): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 3937): [com.policydm.agent.XDMTask(174/xdmAgentTaskHandler)] Network Status is not ready. DM Not Initialized
,E/NetworkSettingsReceiver( 3961): onReceive: android.intent.action.BOOT_COMPLETED
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 5.674010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7a6d2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7bb1410 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3176/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3680): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/BluetoothAdapter( 2881): disable()
,E/BluetoothManagerService( 1015): Bluetooth is already disabled. DO NOT disable again.
,D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1015): mCursor = null
,D/WifiService( 1015): setWifiEnabled: false pid=2881, uid=10333
,D/SettingsProvider( 1015): name = wifi_on
,I/jxcore-log( 2881): ****TEST TOOK:  5107  ms ****
I/jxcore-log( 2881): 
,I/jxcore-log( 2881): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2881): 
,W/System.err( 3961): java.lang.NoSuchMethodException: isEnabled []
W/System.err( 3961): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 3961): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 3961): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 3961): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 3961): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 3961): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 3961): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 3961): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 3961): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 3961): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 3961): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3961): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3961): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 3961): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3961): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3961): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3961): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 3961): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@2641c18b
,D/SBrowserFeatureFlag( 3961): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 3961): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/SPPClientService( 3990): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 3990): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 3990): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,E/Zygote  ( 4012): MountEmulatedStorage()
,E/Zygote  ( 4012): v2
I/libpersona( 4012): KNOX_SDCARD checking this for 10131
I/libpersona( 4012): KNOX_SDCARD not a persona
,I/SELinux ( 4012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4012): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4012 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.635937ms for 96*96 texture 0
I/ActivityManager( 1015): Killing 3052:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7bb1410 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e2be50 counterpartCT=4 counterpartW=96 counterparth=96
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/AMMetaDataParserService( 3680): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3680): took 0.916978ms for 96*96 texture 0
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e1bbc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7bb19d8 counterpartCT=4 counterpartW=96 counterparth=96
I/GCoreUlr( 1617): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/Icing   ( 1778): updateResources: need to parse f{com.google.android.gms}
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 3990): PushLog.txt file is not deleted.
D/SPPClientService( 3990): PushLog.txt file is not deleted.
I/AMMetaDataParserService( 3680): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/SPPClientService( 3990): ============PushLog. stop!
,D/TimaKeyStoreProvider( 4012): TimaSignature is unavailable
D/ActivityThread( 4012): Added TimaKeyStore provider
,E/Zygote  ( 4029): MountEmulatedStorage()
,E/Zygote  ( 4029): v2
I/libpersona( 4029): KNOX_SDCARD checking this for 10036
I/libpersona( 4029): KNOX_SDCARD not a persona
,I/SELinux ( 4029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4029 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/GFX raster( 3680): took 0.631927ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e19c10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e2be50 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1015): Killing 3229:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,E/SELinux ( 4029): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3680): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3680): took 0.764114ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7bb19d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e2be50 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     (  308): Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 874us total 22.943ms,
D/SSRM:n  ( 1015): SIOP:: AP = 410
I/AMMetaDataParserService( 3680): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
W/libprocessgroup( 1015): failed to open /acct/uid_10008/pid_3052/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4029): TimaSignature is unavailable
,D/ActivityThread( 4029): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 648us total 18.893ms
,I/GCoreUlr( 1617): Unbound from all location providers
,W/ResourcesManager( 4012): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4012): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4012): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup( 1015): failed to open /acct/uid_10090/pid_3229/cgroup.procs: No such file or directory
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 19.711ms
,I/GCoreUlr( 1617): DispatchingService.onDestroy()
I/GCoreUlr( 1617): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1617): Unbound from all location providers
,D/daemonapp( 1729): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/AndroidRuntime( 4021): 
D/AndroidRuntime( 4021): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4021): CheckJNI is OFF
,D/AndroidRuntime( 4021): readGMSProperty: start
D/AndroidRuntime( 4021): readGMSProperty: already setted!!
D/AndroidRuntime( 4021): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4021): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4021): readGMSProperty: end
D/AndroidRuntime( 4021): addProductProperty: start
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4029): [SSP] onCreated
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/Zygote  ( 4056): MountEmulatedStorage()
E/Zygote  ( 4056): v2
I/libpersona( 4056): KNOX_SDCARD checking this for 10037
I/libpersona( 4056): KNOX_SDCARD not a persona
,I/SELinux ( 4056): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/GFX raster( 3680): took 0.557136ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e2be50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e1beb0 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1015): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4056 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4056): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/SELinux ( 4056): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3680): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
W/ContextImpl( 3680): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity,
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,D/TimaKeyStoreProvider( 4056): TimaSignature is unavailable
,D/ActivityThread( 4056): Added TimaKeyStore provider,
I/libpersona( 4074): KNOX_SDCARD checking this for 10135
E/Zygote  ( 4074): MountEmulatedStorage()
I/libpersona( 4074): KNOX_SDCARD not a persona
E/Zygote  ( 4074): v2
I/ActivityManager( 1015): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4074 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 4074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4074): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions,
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:assistant
I/AMMetaDataParserService( 3680): Resource data:2131165203
,W/ResourcesManager( 3680): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3680): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3680): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3680): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3680): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3680): getResourceTypeNamexml
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/SA      ( 4029): [TPM] There is no property file
,I/GFX construct_block_size_descriptor_2d second part( 3680): took 4.211875ms for 0*0 texture 0
,I/SA      ( 4029): [SCU] isHaveSA() - false
D/TimaKeyStoreProvider( 4074): TimaSignature is unavailable
,D/ActivityThread( 4074): Added TimaKeyStore provider
I/SA      ( 4029): [TPM] getModelProperty : null
I/SA      ( 4029): [TPM] getCSCProperty : null
,I/SA      ( 4029): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4029): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4029): [DM] TFT FEATURE: false
,W/ResourcesManager( 4056): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/SA      ( 4029): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/SA      ( 4029): [DM] init START
E/AffinityControl( 4021): AffinityControl: registerfunction enter
,I/SA      ( 4029): [DM] This device is not a Vodafone
,W/ResourcesManager( 4074): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4074): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/GFX generate_partition_tables( 3680): took 18.718855ms for 0*0 texture 0
W/ResourcesManager( 4074): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
I/GFX raster( 3680): took 23.480158ms for 80*80 texture 0
W/ResourcesManager( 4074): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e17d58 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb8188c80 counterpartCT=4 counterpartW=80 counterparth=80
W/ResourcesManager( 4074): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SMD     (  289): DCD OFF
,D/AndroidRuntime( 4021): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1015): START PACKAGE DELETE: observer{484864366}
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1015): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,I/CalendarProvider2( 4056): CalendarProvider2.onCreate() called
,I/ActivityManager( 1015): Killing 3256:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 4029): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4029): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4029): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4029): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4029): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4029): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4029): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,E/Zygote  ( 4093): MountEmulatedStorage()
,E/Zygote  ( 4093): v2
I/libpersona( 4093): KNOX_SDCARD checking this for 10141
I/libpersona( 4093): KNOX_SDCARD not a persona
,I/AMMetaDataParserService( 3680): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576,
I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4093 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 4093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ResourceType( 4029): No package identifier when getting value for resource number 0x00000000
E/SELinux ( 4093): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 4029): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 4029): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 4029): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1015): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1015): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
W/ResourceType( 4029): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
W/ResourceType( 4029): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4029): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4029): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4029): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4029): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4029): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 4029): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4029): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80,
I/GFX construct_block_size_descriptor_2d second part( 3680): took 2.526302ms for 0*0 texture 0
I/GFX generate_partition_tables( 3680): took 5.290521ms for 0*0 texture 0
D/PackageManager( 1015): !@killApplicatoin: 10333, uninstall pkg
W/ResourceType( 4029): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4029): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
I/GFX raster( 3680): took 8.827708ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e3ac10 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb818f738 counterpartCT=4 counterpartW=80 counterparth=80
W/ResourceType( 4029): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4029): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4029): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4029): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,D/TimaKeyStoreProvider( 4093): TimaSignature is unavailable
D/ActivityThread( 4093): Added TimaKeyStore provider
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
I/ActivityManager( 1015): Killing 2881:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,I/SA      ( 4029): [SCU] isHaveSA() - false
I/SA      ( 4029): support phone number id : false
I/SA      ( 4029): [DM] Supports Ref Jpn : true
I/SA      ( 4029): [DM] init END
I/AMMetaDataParserService( 3680): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
W/ActivityManager( 1015): Force removing ActivityRecord{39f7f19e u0 com.example.hello/.MainActivity t2}: app died, no saved state
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/FocusedStackFrame( 1015): Set to : 0
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 2881
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (6/7)
I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/7)
,D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3680): took 0.786354ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e3ac10 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8337d00 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3680): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,W/PackageSettings( 1015): Skipping PackageSetting{5bde278 com.test.thalitest/10326} due to missing metadata
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/DBG_DM  ( 2961): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/GFX raster( 3680): took 1.546355ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb7e3ac10 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb81888e0 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3680): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1015): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1015): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3680): took 0.614739ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb8335458 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8335500 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3680): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/Launcher( 1474): onRestart, Launcher: 641843595
,I/SA      ( 4029): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4029): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4029): [OR] onReceive END
I/ActivityManager( 1015): Force stopping com.example.hello appid=10333 user=0: pkg removed
,E/        ( 3680): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3680): took 0.657135ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3680): Bitmap=0xb8335458 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8338178 counterpartCT=4 counterpartW=80 counterparth=80
,I/SA      ( 4029): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4029): [ODM] queryOpenData(key= GEO_IP )
,I/AMMetaDataParserService( 3680): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,W/ResourcesManager( 4093): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/SA      ( 4029): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4029): [LBE] REF_JPN : true
I/SA      ( 4029): [BDC] create
,W/ResourcesManager( 4093): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4093): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4093): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3680): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
W/ContextImpl( 3680): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
,D/Launcher( 1474): onStart, Launcher: 641843595
,D/Launcher.HomeView( 1474): onStart
,D/Launcher( 1474): onResume, Launcher: 641843595
,I/art     ( 3706): Explicit concurrent mark sweep GC freed 19475(1053KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 3MB/5MB, paused 697us total 35.366ms
,D/SettingsProvider( 1015): name = kids_home_mode
,D/SettingsProvider( 1015): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1015): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1015): selectionArgs: false
W/libprocessgroup( 1015): failed to open /acct/uid_10013/pid_3256/cgroup.procs: No such file or directory
D/SettingsProvider( 1015): selectionArgs: 10006
D/SecContentProvider( 1015): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1015): ret = -1
,D/Launcher.HomeView( 1474): onResume
,D/Launcher( 1474): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,I/SA      ( 4029): [DBMV2] getEmailID
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1617): Ignoring removeGeofence because network location is disabled.
,I/SA      ( 4029): [DBMV2] getDataV02ForItems
,I/SA      ( 4029): [SSP] query invoked
,W/ResourcesManager( 1450): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/RCPManagerService( 1015): PackageReceiver onReceive()
E/SamsungIME( 1765): mOCRHelper is null
,I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,V/AlarmManager( 1015): waitForAlarm result :8
,I/SA      ( 4029): [SCU] get signed id from samsung account2.0 DB.
,D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
,I/SA      ( 4029): [SCU] get signed id from samsung account1.0 DB.
,D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms,
,W/TextServicesManagerService( 1015): no available spell checker services found
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3680): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3680): getResourcePackageName:assistant
I/AMMetaDataParserService( 3680): Resource data:2131099648
,I/SA      ( 4029): [BDC] destroy
,W/ResourcesManager( 3680): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3680): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3680): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3680): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3680): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/MenuAppsGridFragment( 1474): onResume
I/AMMetaDataParserService( 3680): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3680): getResourceTypeNamexml
,I/ActivityManager( 1015): Killing 3292:com.sec.factory.camera/1000 (adj 15): empty #31
,D/ActivityManager( 1015): handle home activity for 0
,I/WallpaperManagerService( 1015): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1015): post home show event for user 0
D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,I/SurfaceFlinger(  258): id=12 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1015): Focus entered window: 1474
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 1474): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,I/AMMetaDataParserService( 3680): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/Launcher( 1474): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 1015): Got RemoteException sending setActive(false) notification to pid 2881 uid 10333
,D/SamsungIME( 1765): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,I/AMMetaDataParserService( 3680): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/RegisteredServicesCache( 1436): empty dynamic service
,I/AMMetaDataParserService( 3680): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/Icing   ( 1778): Internal init done: storage state 0
,W/OpenGLRenderer( 1474): SFEffectCache::get: create texture(0xa18d7724): name, size, mSize = 34, 84660, 216788
,D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1015): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1015): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  pkgName : ACTIVITY_RESUME_BOOSTER@11
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 31798(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 22MB/33MB, paused 3.149ms total 352.912ms
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10333
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
I/ActivityManager( 1015): Displayed Component not be shown by security: +434ms
,I/GAV2    ( 3418): Thread[GAThread,5,main]: No campaign data found.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/TaskPersister( 1015): removeObsoleteFile: deleting file=2_task.xml
,D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{27523422 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/Icing   ( 1778): Post-init done
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1015): delete codoeFile: 
,D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10333, packageName = com.example.hello
I/AASA_removePackage( 1015): UID=10333 Target=com.example.hello
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/PackageManager( 1015): result of delete: 1{484864366}
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AndroidRuntime( 4021): Shutting down VM
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/UsbSettingsManager( 1015): clearDefaults: com.example.hello
,I/CrashAnrDetector( 1015): onPackageRemoved : com.example.hello
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_3292/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3680): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,V/EnterpriseBillingPolicy( 1015): uID is 10333
,D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
D/SensorService( 1015): [SO] activate (ident=0xb82ccb88, enabled=0)
,I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,W/art     ( 4021): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorManager( 1015): unregisterListener ::   
,I/Sensors ( 1015): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1015): [SO] changed settle time [0]
D/SensorService( 1015): [SO] setDelay [200000000]
D/SensorService( 1015): [SO] activate (ident=0xb8335cf0, enabled=1)
D/SensorService( 1015): [SO] AR_init
I/Sensors ( 1015): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1015): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1015):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1015): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
,D/CustomFrequencyManagerService( 1015): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1015  tag : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3680): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/PanelView( 1174): There is/are notification(s) 
,I/AMMetaDataParserService( 3680): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3680): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3680): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3680): getResourcePackageName:assistant
I/AMMetaDataParserService( 3680): Resource data:2131099648
,I/AMMetaDataParserService( 3680): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3680): getResourceTypeNamexml
,I/AMMetaDataParserService( 3680): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 3680): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/ActivityManager( 1015): Killing 3334:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,I/Choreographer( 1474): Skipped 31 frames!  The application may be doing too much work on its main thread.
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{bb59af5 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:41431
,D/WallpaperManager( 1474): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1474): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/Timeline( 1474): Timeline: Activity_idle id: android.os.BinderProxy@f5887f2 time:41455
,E/Zygote  ( 4134): MountEmulatedStorage()
,I/libpersona( 4134): KNOX_SDCARD checking this for 10068
E/Zygote  ( 4134): v2
I/libpersona( 4134): KNOX_SDCARD not a persona
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4134 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,I/SELinux ( 4134): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4134): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4134): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 4134): TimaSignature is unavailable,
D/ActivityThread( 4134): Added TimaKeyStore provider
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,W/libprocessgroup( 1015): failed to open /acct/uid_10095/pid_3334/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3680): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,V/AlarmManager( 1015): waitForAlarm result :4
W/FileUtils( 2711): Failed to chmod(/data/data/com.sec.android.app.sysscope/databases/SysScope.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/AMMetaDataParserService( 3680): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/SQLiteLog( 3680): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 3680): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 3680): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3680): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 3680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 3680): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3680): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 3680): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 3680): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 3680): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 3680): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 3680): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3680): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3680): ,	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 3680): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 3680): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 3680): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3680): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3680): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 3680): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 3680): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 3680): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
,W/System.err( 3680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 3680): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 3680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 3680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 3680): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 3680): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 3680): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
,W/System.err( 3680): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 3680): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 3680): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 3680): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 3680): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 3680): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 3680): 	,at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
W/System.err( 3680): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 3680): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3680): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3680): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/SensorService( 1015): [SO] Reset Rotation Old [100], Init [1]
,E/Zygote  ( 4155): MountEmulatedStorage()
,I/libpersona( 4155): KNOX_SDCARD checking this for 10142
,E/Zygote  ( 4155): v2
I/libpersona( 4155): KNOX_SDCARD not a persona
,I/DBG_DM  ( 2961): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/ActivityManager( 1015): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4155 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,I/SELinux ( 4155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4155): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 2711): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30),
,E/SQLiteDatabase( 2711): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2711): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2711): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 2711): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,I/ActivityManager( 1015): Killing 3364:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
I/ActivityManager( 1015): Killing 3197:com.google.android.partnersetup/u0a14 (adj 15): empty #32
,I/ActivityManager( 1015): Killing 3399:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
D/BadgeProvider( 4134): onCreate
,E/SQLiteDatabase( 2711): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2711): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2711): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2711): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2711): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2711): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpe,nHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2711): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2711): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
D/BadgeProvider( 4134): DatabaseHelper
E/SQLiteDatabase( 2711): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2711): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2711): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2711): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2711): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2711): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2711): 	at java.lang.Thread.run(Thread.java:818)
D/TimaKeyStoreProvider( 4155): TimaSignature is unavailable
D/ActivityThread( 4155): Added TimaKeyStore provider
E/SQLiteLog( 4134): (28) failed to open "/data/user/0/com.sec.android.provider.badge/databases/badge.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 4134): Failed to open database '/data/user/0/com.sec.android.provider.badge/databases/badge.db'.
E/SQLiteDatabase( 4134): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4134): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4134): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4134): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 4134): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 4134): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4134): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 4134): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4134): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4134): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4134): 	at com.sec.android.provider.badge.BadgeProvider.query(BadgeProvider.java:145)
E/SQLiteDatabase( 4134): 	at android.content.ContentProvider.query(ContentProvider.java:993)
E/SQLiteDatabase( 4134): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase( 4134): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 4134): 	at android.os.Binder.execTransact(Binder.java:461)
E/DatabaseUtils( 4134): Writing exception to parcel
E/DatabaseUtils( 4134): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 4134): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 4134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/DatabaseUtils( 4134): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/DatabaseUtils( 4134): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/DatabaseUtils( 4134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/DatabaseUtils( 4134): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/DatabaseUtils( 4134): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/DatabaseUtils( 4134): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/DatabaseUtils( 4134): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/DatabaseUtils( 4134): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/DatabaseUtils( 4134): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/DatabaseUtils( 4134): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 4134): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 4134): 	at com.sec.android.provider.badge.BadgeProvider.query(BadgeProvider.java:145)
E/DatabaseUtils( 4134): 	at android.content.ContentProvider.query(ContentProvider.java:993)
E/DatabaseUtils( 4134): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils( 4134): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 4134): 	at android.os.Binder.execTransact(Binder.java:461)
E/SQLiteLog( 2711): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2711): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2711): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2711): 	at java.lang.Thread.run(Thread.java:818)
W/ResourcesManager( 4155): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
E/SQLiteLog( 2711): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2711): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2711): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2711): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2711): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/BadgeNotification( 4093): getId() android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2711): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2711): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2711): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2711): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2711): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2711): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2711): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2711): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 2711): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2711): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2711): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 2711): (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 2711): Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
E/SQLiteDatabase( 2711): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 2711): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 2711): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 2711): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
E/SQLiteDatabase( 2711): 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2711): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2711): 	at java.lang.Thread.run(Thread.java:818)
D/BadgeProvider( 4134): insert, [uri] : content://com.sec.badge/apps [ContentValues] : extraData=base_extra_badge package=com.android.email badgecount=0 class=com.android.email.activity.Welcome
D/BadgeProvider( 4134): insert, [args] : com.sec.android.provider.badge.BadgeProvider$SqlArguments@20914e02
E/SQLiteLog( 4134): (28) failed to open "/data/user/0/com.sec.android.provider.badge/databases/badge.db" with flag (131138) and mode_t (0) due to error (30)

```
