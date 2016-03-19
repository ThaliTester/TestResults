#### Test 62548124d9c0fd9_thali07_samsung-SM-A500FU Logs


```
--------- beginning of system
03-19 12:52:08.257  1018  1059 D PackageManager: [MSG] MCS_UNBIND
--------- beginning of main
03-19 12:52:08.267  1018  1018 W PhoneRestrictionPolicy: Message received - msg { when=-6ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
03-19 12:52:08.267  1018  1728 I ActivityManager: Killing 1216:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
03-19 12:52:08.277  1018  1018 D KnoxMUMContainerPolicy: mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
03-19 12:52:08.277  1018  2878 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
03-19 12:52:08.277  1018  1018 I KnoxMUMContainerPolicy: MSG_REMOVE_ORPHANED_CONTAINERS received
03-19 12:52:08.277  2034  2805 I Icing   : updateResources: need to parse f{com.google.android.gms}
03-19 12:52:08.287  1018  1131 D WIFI_P2P: got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-19 12:52:08.287  1018  1131 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
03-19 12:52:08.287  1018  1018 D Tethering: Boot complete.
03-19 12:52:08.287  1018  1018 V EnterpriseBillingEngine: ACTION_BOOT_COMPLETED
03-19 12:52:08.287  1018  1018 V EnterpriseBillingEngine: handleAllprofiles - start
03-19 12:52:08.287  1018  1018 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - start - 
03-19 12:52:08.287  1018  1018 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - end - null
03-19 12:52:08.287  1018  1131 D WifiP2pService: InactiveState{ what=143415 }
03-19 12:52:08.287  1018  1131 D WifiP2pService: P2pEnabledState{ what=143415 }
03-19 12:52:08.287  1018  1131 D WifiP2pService: DefaultState{ what=143415 }
03-19 12:52:08.287  1018  1134 D ConnectivityService: Got NetworkFactory Messenger for WIFI_P2P
03-19 12:52:08.287  1018  1134 D ConnectivityService: Got NetworkFactory Messenger for WIFI
03-19 12:52:08.297  1018  1018 V EnterpriseBillingEngine: handleAllprofiles - end
03-19 12:52:08.297  1018  1132 D WIFI    : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-19 12:52:08.297  1018  1132 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
03-19 12:52:08.297  1018  1387 D RCPManagerService: exchangeData() failure , invalid userId
03-19 12:52:08.297  1018  1132 E WifiStateMachine: Blacklist file delete
03-19 12:52:08.297  1018  1018 D UsbHostNotification: boot completed
03-19 12:52:08.297  1018  1018 D UsbHostRestrictor: mBootCompletedReceiver onReceive
03-19 12:52:08.297  1018  1018 D UsbHostRestrictor: initSetUsbBlock STARTED
03-19 12:52:08.327  1018  2878 W PhoneRestrictionPolicy: cvList size 0
03-19 12:52:08.327  1018  2878 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
,03-19 12:52:08.327  1018  2878 W PhoneRestrictionPolicy: cvList size 0
03-19 12:52:08.337  1018  1018 D UsbHostRestrictor: SIM was never inserted
03-19 12:52:08.347  1018  1018 D UsbHostRestrictor: writableHostSysNode[false]
03-19 12:52:08.347  1018  1018 D UsbHostRestrictor: Can NOT Write Disable Sys Node to [ON]
03-19 12:52:08.367  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_1216/cgroup.procs: No such file or directory
03-19 12:52:08.367  1018  1018 D PersonaManagerService: ACTION_BOOT_COMPLETED
03-19 12:52:08.377  1018  1063 E PersonaManagerServiceHandler:  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
03-19 12:52:08.377  1018  1041 D SensorService: [SO] currT = 34811288000, prevT = 34391062000, diff = 420226000, [0.172 0.402 10.228]
03-19 12:52:08.377  1018  1041 D SensorService: [SO] 0.172 0.402 10.228
03-19 12:52:08.377  1018  1041 D SensorService: [SO] [100 -> 255]
03-19 12:52:08.377  1018  1063 D KnoxKeyguardUpdateMonitor: onBootComplete
03-19 12:52:08.377  1018  1018 D UsbStorageNotification: boot completed
03-19 12:52:08.387  1018  1018 I KnoxKeyguardUpdateMonitor: onTrustManagedChanged user 0, managed:false
03-19 12:52:08.387  1018  1018 I KnoxKeyguardUpdateMonitor: onTrustChanged user:0, enable:false
03-19 12:52:08.387  1200  1200 D KeyguardViewMediator: onTrustChanged( Showing = false , userId = 0 )
03-19 12:52:08.387  1018  1063 D PersonaManagerService: getPersonasForUser(): returning null!
03-19 12:52:08.387  1018  1238 D RCPManagerService: exchangeData() failure , invalid userId
03-19 12:52:08.387  1018  1043 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
03-19 12:52:08.397  1018  1043 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
03-19 12:52:08.397  1018  1043 D GpsLocationProvider_ex: BOOT_COMPLETED native_init 
03-19 12:52:08.397  1018  1043 D GpsLocationProvider: set_capabilities_callback: 55u
03-19 12:52:08.397  1018  1043 I libmdmdetect: ESOC framework not supported
03-19 12:52:08.397  1018  1043 I libmdmdetect: Found internal modem: modem
03-19 12:52:08.397  1018  1043 E PerMgrLib: Peripheral manager is not supported on this device
03-19 12:52:08.397  1018  1043 E Geofence_Adapter: I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
03-19 12:52:08.397  1018  1043 E Geofence_Adapter: I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
03-19 12:52:08.397  1018  1043 D GpsLocationProvider_ex: BOOT_COMPLETED native_cleanup 
03-19 12:52:08.397  1200  1200 D StorageNotification: boot completed
03-19 12:52:08.397  1018  1567 D qmi_secgps_clnt: qmi_secgps_client_init()
03-19 12:52:08.407  1018  1567 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
03-19 12:52:08.417  1018  1567 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
03-19 12:52:08.417  1018  1238 D StatusBarManagerService: setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
03-19 12:52:08.417  1200  1200 D PhoneStatusBar: updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
03-19 12:52:08.417  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.417  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.417  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.417  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.427  1018  1567 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
03-19 12:52:08.437  2896  2896 E Zygote  : MountEmulatedStorage()
03-19 12:52:08.437  2896  2896 E Zygote  : v2
03-19 12:52:08.437  2896  2896 I libpersona: KNOX_SDCARD checking this for 10099
03-19 12:52:08.437  2896  2896 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:08.437  1018  1031 I ActivityManager: Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2896 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-19 12:52:08.437  2896  2896 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:08.437  2896  2896 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:08.437  2896  2896 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-19 12:52:08.447  2544  2888 D PicasaService: start picasa sync
03-19 12:52:08.447  2544  2888 D PicasaService: end picasa sync
03-19 12:52:08.457  1018  1730 D RCPManagerService: exchangeData() failure , invalid userId
03-19 12:52:08.457  2896  2896 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:08.457  1018  1043 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
03-19 12:52:08.457  2896  2896 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:08.537  1018  1238 D RCPManagerService: exchangeData() failure , invalid userId
03-19 12:52:08.567  1018  1567 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
03-19 12:52:08.567  1018  1570 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-19 12:52:08.577  1018  1570 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-19 12:52:08.577  1018  1570 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
03-19 12:52:08.577  1018  1567 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
03-19 12:52:08.577  1018  1567 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-19 12:52:08.587  1018  1570 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-19 12:52:08.587  1018  1567 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
03-19 12:52:08.597  1018  1570 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-19 12:52:08.597  1018  1567 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
03-19 12:52:08.607  1018  1570 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-19 12:52:08.607  1018  1567 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
03-19 12:52:08.607  1018  1567 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-19 12:52:08.607  1018  1567 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-19 12:52:08.617  1018  1567 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-19 12:52:08.617  1018  1567 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
03-19 12:52:08.617  1018  1567 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-19 12:52:08.617  1018  1567 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
03-19 12:52:08.637  2894  2894 D AndroidRuntime: 
03-19 12:52:08.637  2894  2894 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-19 12:52:08.637  2894  2894 D AndroidRuntime: CheckJNI is OFF
03-19 12:52:08.637  2894  2894 D AndroidRuntime: readGMSProperty: start
03-19 12:52:08.637  2894  2894 D AndroidRuntime: readGMSProperty: already setted!!
03-19 12:52:08.637  2894  2894 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-19 12:52:08.637  2894  2894 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-19 12:52:08.637  2894  2894 D AndroidRuntime: readGMSProperty: end
03-19 12:52:08.637  2894  2894 D AndroidRuntime: addProductProperty: start
03-19 12:52:08.647  2896  2896 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
03-19 12:52:08.657  2896  2896 E ActivityThread: Failed to find provider info for flipboard.auth.internal
03-19 12:52:08.657  1018  1401 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=88, mSplitNum[1]=125, mSplitNum[2]=162, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 51 receivers.size=198
03-19 12:52:08.657  1018  1401 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
03-19 12:52:08.657  1018  1401 I ActivityManager: Killing 1426:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
03-19 12:52:08.667  1018  1018 I DrmEventReceiver: DrmEventReceiver : onReceive
03-19 12:52:08.667  1018  1018 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
03-19 12:52:08.667  1018  1018 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-19 12:52:08.667  1018  1018 I System.out: start Service
03-19 12:52:08.667  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-19 12:52:08.667  1018  1570 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-19 12:52:08.667  1018  1567 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
03-19 12:52:08.677  1018  1570 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
03-19 12:52:08.677  1018  1570 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-19 12:52:08.677   296   296 E USB_UICC: Timeout! No signal received. Retry num = 29
03-19 12:52:08.677  1018  1567 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
03-19 12:52:08.677  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.677  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.677  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.677  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.687  2735  2875 E SQLiteLog: (284) automatic index on view_volumes(volume_id)
03-19 12:52:08.687   317   317 I ServiceManager: Waiting for service AtCmdFwd...
03-19 12:52:08.697  1254  1254 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-19 12:52:08.697  2717  2717 E BluetoothAdapterService(1020019182): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
03-19 12:52:08.697  2717  2717 E BluetoothAdapterService(1020019182): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
03-19 12:52:08.707  2919  2919 E Zygote  : MountEmulatedStorage()
03-19 12:52:08.707  2919  2919 E Zygote  : v2
03-19 12:52:08.707  2919  2919 I libpersona: KNOX_SDCARD checking this for 10085
03-19 12:52:08.707  2919  2919 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:08.707  2919  2919 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:08.707  2919  2919 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:08.707  2919  2919 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:08.707  1018  1044 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2919 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-19 12:52:08.707  1018  2821 D SSRM:a  : DeviceInfo:: 000000000000
03-19 12:52:08.707  1018  2821 D SSRM:a  : SettingsAirViewInfo:: 000000000
03-19 12:52:08.717  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.717  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.717  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.717  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.737  2940  2940 E Zygote  : MountEmulatedStorage()
03-19 12:52:08.737  2940  2940 E Zygote  : v2
03-19 12:52:08.737  2940  2940 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:08.737  2940  2940 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:08.737  2919  2919 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:08.737  2919  2919 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:08.747  2940  2940 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:08.747  2940  2940 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:08.757  2940  2940 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:08.777   308   308 I art     : Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 37.887ms
03-19 12:52:08.787  2940  2940 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:08.787  2940  2940 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:08.797  1018  1044 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2940 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 12:52:08.797  1018  1031 I ActivityManager: Killing 1445:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31
03-19 12:52:08.807  1018  1018 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
03-19 12:52:08.807   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 23.391ms
03-19 12:52:08.817  1018  1238 D RCPManagerService: exchangeData() failure , invalid userId
03-19 12:52:08.817  2894  2894 E AffinityControl: AffinityControl: registerfunction enter
03-19 12:52:08.827   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 18.555ms
03-19 12:52:08.827  1018  1730 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
03-19 12:52:08.827  1018  1730 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:08.827  1018  1730 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:08.827  1018  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-19 12:52:08.827  2717  2802 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
03-19 12:52:08.827  2717  2802 I bluedroid: enable
03-19 12:52:08.827  1018  1393 D RCPManagerService: exchangeData() failure , invalid userId
03-19 12:52:08.837  1605  1614 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
03-19 12:52:08.837  2717  2802 I bt_hci_bdroid: init
03-19 12:52:08.847   281   514 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 3490
03-19 12:52:08.847   281   514 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 3490
03-19 12:52:08.847  2717  2802 I bt_vendor: bt-vendor : init
03-19 12:52:08.847  2717  2802 I bt_vendor: bt-vendor : get_bt_soc_type
03-19 12:52:08.847  2717  2802 E bt_vendor: get_bt_soc_type: Failed to get soc type
03-19 12:52:08.847  2717  2802 I bt_vendor: init: Local BD Address : 22:18:51:0e:f9:7c
03-19 12:52:08.847  2717  2802 D bt_userial_mct: userial_init
03-19 12:52:08.847  2717  2962 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
03-19 12:52:08.847  2717  2802 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
03-19 12:52:08.847  2717  2802 I bt_vendor: Starting hciattach daemon
03-19 12:52:08.847  2717  2802 I bt_vendor: try to set false
03-19 12:52:08.847  2717  2802 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
03-19 12:52:08.847  2717  2802 I bt_vendor: Starting hciattach daemon
03-19 12:52:08.847  2717  2802 I bt_vendor: try to set true
03-19 12:52:08.867  2894  2894 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-19 12:52:08.867  2735  2970 I BooksConfig: GmsCore Version = 7.8.99 (2134222-436)
03-19 12:52:08.877  1018  1018 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
03-19 12:52:08.877  1018  2969 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
03-19 12:52:08.877  2919  2919 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-19 12:52:08.877  2919  2919 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-19 12:52:08.877  2919  2919 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:52:08.877  2919  2919 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-19 12:52:08.877  2919  2919 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-19 12:52:08.877  2919  2919 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-19 12:52:08.887   281   281 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-19 12:52:08.887  2972  2972 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
03-19 12:52:08.887  1018  1730 E PersonaManagerService: inState():  stateMachine is null !!
03-19 12:52:08.887  1018  1730 I PersonaManagerService: PersonaId don't exist
03-19 12:52:08.887  1018  1730 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-19 12:52:08.897  1018  1140 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-19 12:52:08.897  1018  1140 D SecContentProvider2: mCursor = null
03-19 12:52:08.897  1018  1730 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-19 12:52:08.907  1018  1730 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-19 12:52:08.907  1018  1730 W ActivityManager: mDVFSHelper.acquire()
03-19 12:52:08.917  1254  1254 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-19 12:52:08.927  1018  1730 D FocusedStackFrame: Set to : 0
03-19 12:52:08.937  1018  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-19 12:52:08.937  1530  1530 D Launcher.Model: reloadBadges entered.
03-19 12:52:08.937  1605  1614 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-19 12:52:08.937  1605  1614 D BadgeProvider: sendNotify, [notify] : null
03-19 12:52:08.937  1605  1614 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-19 12:52:08.937  1605  1614 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-19 12:52:08.937  1605  1614 D BadgeProvider: update, [UpdateCount] : 1
03-19 12:52:08.937  1018  1730 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-19 12:52:08.937  1018  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-19 12:52:08.937  1018  1730 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-19 12:52:08.947  1018  1730 D InputDispatcher: Focused application set to: xxxx
03-19 12:52:08.947  1018  1730 D InputDispatcher: Focus left window: 1530
03-19 12:52:08.947  1530  1530 D Launcher.HomeView: onPause
03-19 12:52:08.947  1530  1530 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-19 12:52:08.947  2894  2894 D AndroidRuntime: Shutting down VM
03-19 12:52:08.957  1018  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-19 12:52:08.957  1018  1238 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
03-19 12:52:08.957  1018  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-19 12:52:08.957  1501  1501 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-19 12:52:08.957  2979  2979 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
03-19 12:52:08.957  1018  1238 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:08.957  1018  1238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:08.957  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_1426/cgroup.procs: No such file or directory
03-19 12:52:08.957   256   256 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-19 12:52:08.957  1018  1238 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-19 12:52:08.967  2980  2980 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
03-19 12:52:08.987  1018  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.987  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-19 12:52:08.987  1018  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.987  1018  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.987  1018  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:08.987  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-19 12:52:08.987  2982  2982 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
03-19 12:52:08.997  2983  2983 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
03-19 12:52:08.997  2984  2984 E Zygote  : MountEmulatedStorage()
03-19 12:52:08.997  2984  2984 I libpersona: KNOX_SDCARD checking this for 10160
03-19 12:52:08.997  2984  2984 E Zygote  : v2
03-19 12:52:08.997  2984  2984 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:09.007  2984  2984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:09.007  2984  2984 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:09.007  2984  2984 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:09.007  1018  1747 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2984 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-19 12:52:09.007  1018  1238 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
03-19 12:52:09.007  2987  2987 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
03-19 12:52:09.017  1018  1238 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.017  1018  1238 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:09.017  1018  1238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
03-19 12:52:09.017  1018  1728 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
03-19 12:52:09.017  1018  1728 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.017  1018  1728 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:09.017  1018  1728 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-19 12:52:09.017  1018  1555 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.017  1018  1555 D ActivityManager: retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
03-19 12:52:09.017  1018  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:09.017  1018  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-19 12:52:09.027  2984  2984 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:09.027  2993  2993 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
03-19 12:52:09.027  2984  2984 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:09.027  1018  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.027  1018  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.027  1018  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.027  1018  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.047  3005  3005 E Zygote  : MountEmulatedStorage()
03-19 12:52:09.047  3005  3005 I libpersona: KNOX_SDCARD checking this for 10174
03-19 12:52:09.047  3005  3005 E Zygote  : v2
03-19 12:52:09.047  3005  3005 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:09.047  3005  3005 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:09.047  3005  3005 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:09.047  3005  3005 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-19 12:52:09.057  1018  1140 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3005 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-19 12:52:09.057  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{10c338fa u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
03-19 12:52:09.057  1018  1043 W libprocessgroup: failed to open /acct/uid_10096/pid_1445/cgroup.procs: No such file or directory
03-19 12:52:09.067  1501  1501 D CscUpdateService: onStart
03-19 12:52:09.067  1501  1501 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-19 12:52:09.067  1501  1501 I CscUpdateService: set_CSC_version
03-19 12:52:09.067  1501  1501 E CscParser: update(): xml file exist
03-19 12:52:09.067  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.067  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.067  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.067  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.067  3005  3005 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:09.067  3005  3005 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:09.087  3020  3020 E Zygote  : MountEmulatedStorage()
03-19 12:52:09.087  3020  3020 I libpersona: KNOX_SDCARD checking this for 10003
03-19 12:52:09.087  3020  3020 E Zygote  : v2
03-19 12:52:09.087  3020  3020 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:09.087  3020  3020 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:09.087  3020  3020 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:09.097  3020  3020 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:09.097  1018  1238 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3020 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-19 12:52:09.097  1018  1392 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-19 12:52:09.097  1018  1392 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-19 12:52:09.097  1530  1530 V ActivityThread: updateVisibility : ActivityRecord{174183d6 token=android.os.BinderProxy@2a98a142 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-19 12:52:09.097  1018  1393 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-19 12:52:09.097  1018  1393 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-19 12:52:09.097  1018  1393 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-19 12:52:09.107  1530  1530 D Launcher.HomeView: onStop
03-19 12:52:09.107  1530  1530 V ActivityThread: updateVisibility : ActivityRecord{174183d6 token=android.os.BinderProxy@2a98a142 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-19 12:52:09.117  3020  3020 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:09.117  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-19 12:52:09.117  3020  3020 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:09.117  1018  1393 D PersonaManager: isKioskContainerExistOnDevice
03-19 12:52:09.127  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-19 12:52:09.127  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.127  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:09.127  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-19 12:52:09.137  1501  1501 I CscUtil : isWifiOnly = false
03-19 12:52:09.147  1501  1501 I System.out: HandDataNode = null
03-19 12:52:09.147  1501  1501 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
03-19 12:52:09.147  1018  3036 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 12:52:09.147  1254  3002 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-19 12:52:09.147  1018  3036 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-19 12:52:09.147  1018  3036 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
03-19 12:52:09.147  1501  1501 I CscUpdateService: This is normal boot : CSC not updated
03-19 12:52:09.147  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 12:52:09.147  1018  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
03-19 12:52:09.157  1501  3037 E CscParser: update(): xml file exist
03-19 12:52:09.167  1018  1747 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
03-19 12:52:09.177  2894  2894 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-19 12:52:09.177  1501  1501 I CscUpdateService: same CSC Version
03-19 12:52:09.177  1501  1501 D CscUtil : Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
,03-19 12:52:09.187  1501  3037 D CscGPS  : CSCGPS.updateParameters
03-19 12:52:09.187  1501  3037 D CscGPS  : supl host : null
03-19 12:52:09.187  1501  3037 D CscGPS  : SUPL Host is null or invalid
03-19 12:52:09.187  1501  3037 D CscGPS  : supl_ver : null
03-19 12:52:09.187  1501  3037 D CscGPS  : SUPL Ver is null or invalid
03-19 12:52:09.187  1501  3037 D CscGPS  : supl port : null
03-19 12:52:09.187  1501  3037 D CscGPS  : SUPL PORT is null or invalid
03-19 12:52:09.187  1501  3037 D CscGPS  : LPP : null
03-19 12:52:09.187  1501  3037 D CscGPS  : LPP is null or invalid
03-19 12:52:09.187  1501  3037 D CscGPS  : CSC don't have any AGPS value.
,03-19 12:52:09.187  1018  1730 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-19 12:52:09.187  1018  1730 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.187  1018  1730 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:09.187  1018  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-19 12:52:09.207  1018  1018 I MotionRecognitionService: Plugged
,03-19 12:52:09.207  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:52:09.207  2984  2984 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-19 12:52:09.207  1200  1200 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:52:09.207  1200  1200 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:52:09.217  1530  1530 D Launcher: onTrimMemory. Level: 20
,03-19 12:52:09.217  1462  1462 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 12:52:09.217  1462  1462 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:52:09.217  1200  1200 D PowerUI : Cable  true --> true mBootCompleted : true
03-19 12:52:09.217  1200  1200 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,03-19 12:52:09.227  1731  2205 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-19 12:52:09.227  1731  2205 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-19 12:52:09.227  1731  2205 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-19 12:52:09.237  2717  2717 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:52:09.237  2717  2837 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:52:09.237  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-19 12:52:09.237  1731  2205 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-19 12:52:09.237  1018  1018 D SensorService: [SO] activate (ident=0xb94c9a60, enabled=0)
,03-19 12:52:09.247  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-19 12:52:09.247  1254  3002 E SQLiteLog: (283) recovered 95 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
03-19 12:52:09.247  3040  3040 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:51:18:22 
,03-19 12:52:09.257  1018  1018 D SensorManager: unregisterListener ::   ,
03-19 12:52:09.257  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-19 12:52:09.257  3041  3041 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,03-19 12:52:09.267  1018  1018 D SensorService: [SO] changed settle time [1]
03-19 12:52:09.267  1018  1018 D SensorService: [SO] setDelay [66000000]
03-19 12:52:09.267  1018  1018 D SensorService: [SO] activate (ident=0xb94c9a60, enabled=1)
03-19 12:52:09.267  1018  1018 D SensorService: [SO] AR_init
03-19 12:52:09.267  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-19 12:52:09.267  1200  1200 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:52:09.267  1200  1200 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:52:09.267  1200  1200 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:52:09.267  1254  1254 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-19 12:52:09.277  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-19 12:52:09.277  1731  2205 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:09.287  1018  1387 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-19 12:52:09.287  1018  1387 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.287  1018  1387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:09.287  1018  1387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:52:09.287  2034  2805 I Icing   : Internal init done: storage state 0
,03-19 12:52:09.297  1501  1723 D TP/MmsProvider: Update uri=content://mms, match=0
,03-19 12:52:09.297  1501  1723 D TP/MmsProvider: update , handleReadChangedBroadcast
03-19 12:52:09.297  1501  1723 D TP/MmsSmsProvider: need read changed broadcast:false
,03-19 12:52:09.297  1018  1387 D SettingsProvider: name = next_alarm_formatted
03-19 12:52:09.297  1018  1387 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 12:52:09.297  1018  1387 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:09.297  1018  1387 D SettingsProvider: selectionArgs: false
03-19 12:52:09.297  1018  1387 D SettingsProvider: selectionArgs: 10085
03-19 12:52:09.297  1018  1387 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 12:52:09.297  1018  1387 D SettingsProvider: ret = -1
,03-19 12:52:09.307  2383  2383 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
,03-19 12:52:09.307  2383  2383 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 4183.726873
,03-19 12:52:09.307  2383  2383 I Mms/ReservationManager: resetAfterConnected()
,03-19 12:52:09.317  2717  2802 I bt_vendor: bluetooth satus is on
,03-19 12:52:09.317  2717  2965 D bt_userial_mct: userial_open(port:0)
03-19 12:52:09.317  2717  2965 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,03-19 12:52:09.317  2383  3043 D Mms/MessagingNotification: sDisableVibrateForCamera = false
,03-19 12:52:09.317  2383  3043 D Mms/TelephonyPermission: isDefault true
,03-19 12:52:09.317  2717  2965 I bt_vendor: Done intiailizing UART
,03-19 12:52:09.317  2717  2965 I bt_vendor: Done intiailizing UART
,03-19 12:52:09.317  2717  2965 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
03-19 12:52:09.317  2717  2965 I bt_vendor: Bluetooth Firmware and transport layer are initialized
03-19 12:52:09.317  1501  1522 D TP/MmsSmsProvider: query,matched:7, calling pid = 2383
,03-19 12:52:09.327  3005  3005 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,03-19 12:52:09.327  2717  3045 D bt_userial_mct: Entering userial_read_thread()
,03-19 12:52:09.327  1501  1517 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2383
,03-19 12:52:09.327  1501  1522 D TP/MmsSmsProvider: match 7:Elapsed time : 9.467 ms
,03-19 12:52:09.337  1018  1387 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,03-19 12:52:09.347  1018  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-19 12:52:09.347  2383  2383 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-19 12:52:09.347  1200  1200 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-19 12:52:09.357  3005  3005 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5785-5789)
,03-19 12:52:09.357  3005  3005 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-19 12:52:09.357  1018  1140 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,03-19 12:52:09.357  1018  1140 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.357  1018  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:09.357  1018  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-19 12:52:09.357  1501  1517 D TP/MmsSmsProvider: query,matched:200, calling pid = 2383
03-19 12:52:09.367  1501  1517 D TP/MmsSmsProvider: match 200:Elapsed time : 4.946 ms
03-19 12:52:09.367  1018  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.367  1018  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.367  1018  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.367  1018  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.377  3050  3050 E Zygote  : MountEmulatedStorage()
03-19 12:52:09.377  3050  3050 E Zygote  : v2
03-19 12:52:09.377  3050  3050 I libpersona: KNOX_SDCARD checking this for 10048
03-19 12:52:09.377  3050  3050 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:09.377  1018  1747 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3050 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-19 12:52:09.387  3005  3005 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b22c68f}
,03-19 12:52:09.387  3005  3005 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-19 12:52:09.387  3005  3005 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-19 12:52:09.397  1501  1723 D TP/SmsProvider: query,matched:0, calling pid = 2383
,03-19 12:52:09.397  1501  1723 D TP/SmsProvider: match 0:Elapsed time : 1.375 ms
03-19 12:52:09.397  2383  2383 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-19 12:52:09.397  2383  3056 D Mms/TelephonyPermission: isDefault true
03-19 12:52:09.397  2383  3056 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-19 12:52:09.397  2383  3056 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 91.900105
,03-19 12:52:09.417  2984  2984 D [0]UMC:UMCContentProvider: @onCreate
,03-19 12:52:09.417  1018  1041 D SensorService: [SO] 0.172 0.421 10.228
03-19 12:52:09.417  1018  1041 D SensorService: [SO] [100 -> 255]
,03-19 12:52:09.427  3005  3005 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-19 12:52:09.427  3005  3005 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 12:52:09.427  3005  3005 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-19 12:52:09.437  3050  3050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-19 12:52:09.437  3050  3050 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-19 12:52:09.437  3050  3050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:09.477  3050  3050 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:09.477  3050  3050 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:09.487  3005  3005 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-19 12:52:09.497  3005  3005 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-19 12:52:09.497  3005  3005 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-19 12:52:09.497  3005  3005 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-19 12:52:09.497  3005  3005 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-19 12:52:09.497  3005  3005 I Adreno-EGL: Build Date: 04/06/15 Mon
03-19 12:52:09.497  3005  3005 I Adreno-EGL: Local Branch: 
03-19 12:52:09.497  3005  3005 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-19 12:52:09.497  3005  3005 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-19 12:52:09.497  3005  3005 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-19 12:52:09.507  1731  2205 I art     : Explicit concurrent mark sweep GC freed 22393(1325KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 10MB/17MB, paused 1.349ms total 159.565ms
,03-19 12:52:09.527  2034  2805 I Icing   : Post-init done
,03-19 12:52:09.537  1731  2205 I NotificationStore: System rebooted after Notification storage file was last written
,03-19 12:52:09.537  1731  2205 I NotificationStore: Deleting the file
,03-19 12:52:09.557  1018  1031 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-19 12:52:09.557  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-19 12:52:09.557  1018  1018 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-19 12:52:09.557  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-19 12:52:09.567   256   447 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,03-19 12:52:09.567   256   442 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-19 12:52:09.577  1200  1215 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
03-19 12:52:09.577  1200  1215 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-19 12:52:09.577  2919  2919 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 137.226ms
,03-19 12:52:09.607  1200  1200 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-19 12:52:09.627  1200  1200 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-19 12:52:09.627  1200  1200 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
,03-19 12:52:09.637  1200  1200 D PersonaManager: isKioskContainerExistOnDevice
,03-19 12:52:09.637  1200  1200 D PersonaManager: isKioskContainerExistOnDevice
,03-19 12:52:09.637  1200  1200 D PanelView: There is/are notification(s) 
,03-19 12:52:09.637  1200  1200 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-19 12:52:09.637  1200  1200 D PersonaManager: isKioskContainerExistOnDevice
,03-19 12:52:09.647  1200  1200 D PanelView: There is/are notification(s) 
,03-19 12:52:09.647  1200  1200 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-19 12:52:09.667  1018  1555 I art     : Explicit concurrent mark sweep GC freed 166534(9MB) AllocSpace objects, 39(3MB) LOS objects, 33% free, 26MB/40MB, paused 2.610ms total 269.144ms
,03-19 12:52:09.677   296   296 E USB_UICC: Timeout! No signal received. Retry num = 30
,03-19 12:52:09.687  2984  2984 D [0]UMC:Core: onCreate(): 
03-19 12:52:09.687  2984  2984 D [0]UMC:Core: @isManagedProfileUser
03-19 12:52:09.687  2984  2984 D [0]UMC:Core: userId: 0
,03-19 12:52:09.687  2984  2984 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
,03-19 12:52:09.687  2984  2984 D [0]UMC:Core: userInfo.isManagedProfile() : false
03-19 12:52:09.687   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:52:09.697  1018  1393 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_HCI
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_L2CAP
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_RFCOMM
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_AVDT
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_AVRC
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_A2D
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_BNEP
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_BTM
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_GAP
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_PAN
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_SAP
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_SDP
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_GATT
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_SMP
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_BTAPP
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_BTIF
03-19 12:52:09.697  2717  2962 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,03-19 12:52:09.697  1018  1393 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.697  1018  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:09.697  1018  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:09.707  1018  1555 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,03-19 12:52:09.717  1018  1555 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:09.717  1018  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:09.717  1018  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-19 12:52:09.717  1501  1522 D TP/SmsProvider: query,matched:51, calling pid = 2383
,03-19 12:52:09.727  1200  1200 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-19 12:52:09.727  1501  1517 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
,03-19 12:52:09.727  1501  1517 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
,03-19 12:52:09.727  3050  3050 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-19 12:52:09.727  3050  3050 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-19 12:52:09.727  3050  3050 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-19 12:52:09.737  1501  1522 D TP/SmsProvider: match 51:Elapsed time : 11.108 ms
,03-19 12:52:09.737  1018  1728 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-19 12:52:09.737  1018  1728 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.737  1018  1728 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:09.737  1018  1728 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-19 12:52:09.747  3020  3083 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,03-19 12:52:09.747  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,03-19 12:52:09.747  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.747  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:09.747  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-19 12:52:09.747  1254  3002 D MediaScanner: Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-19 12:52:09.747  1018  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.747  1018  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:09.747  1018  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:09.747  1018  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:09.767  3085  3085 E Zygote  : MountEmulatedStorage()
03-19 12:52:09.767  3085  3085 E Zygote  : v2
03-19 12:52:09.767  3085  3085 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:09.767  3085  3085 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:09.767   296   296 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-19 12:52:09.767   296   296 E USB_UICC: usb_uicc_init_qmi failed ! 
03-19 12:52:09.767   296   296 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-19 12:52:09.767   296   296 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-19 12:52:09.777  1018  1728 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3085 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 12:52:09.777  1018  1747 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-19 12:52:09.777  1018  1747 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.777  1018  1747 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:09.777  1018  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:52:09.787  1018  1401 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 12:52:09.787  3085  3085 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:09.787  3085  3085 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:09.787  3085  3085 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:09.797  1018  1401 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.797  1501  1517 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-19 12:52:09.797  1501  1517 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
03-19 12:52:09.797  1018  1401 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:09.797  1018  1401 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:52:09.807  2984  2984 D [0]UMC:DeviceInfo: USA==US==
,03-19 12:52:09.827  3085  3085 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:09.827  3085  3085 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:09.827  1501  1517 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-19 12:52:09.827  1501  1517 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-19 12:52:09.827  1501  1517 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-19 12:52:09.827  1501  1517 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-19 12:52:09.827  1501  1517 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-19 12:52:09.827  1501  1517 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-19 12:52:09.827  1501  1517 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-19 12:52:09.837  2717  2962 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,03-19 12:52:09.837  3020  3083 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,03-19 12:52:09.847  1501  1517 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-19 12:52:09.847  1501  1517 D TP/MmsSmsProvider: need read changed broadcast:false
,03-19 12:52:09.847  2717  2962 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa45406e9 
03-19 12:52:09.847  2717  2962 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa45406e9 
,03-19 12:52:09.847   363   363 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 3020
03-19 12:52:09.847   363   363 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,03-19 12:52:09.847  1018  3034 D SettingsProvider: name = block_emergency_message
,03-19 12:52:09.847  1018  3034 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-19 12:52:09.847  1018  3034 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:09.847  1018  3034 D SettingsProvider: selectionArgs: false
03-19 12:52:09.847  1018  3034 D SettingsProvider: selectionArgs: 10048
,03-19 12:52:09.857  1018  3034 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 12:52:09.857  1018  3034 D SettingsProvider: ret = -1
,03-19 12:52:09.857  1018  1392 W ActivityManager: getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,03-19 12:52:09.857  1731  2205 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,03-19 12:52:09.857  1731  2205 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-19 12:52:09.857  1731  2205 I GLSUser : [GLSUser] Extracting token using key: Auth
03-19 12:52:09.857  1731  2205 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-19 12:52:09.857  3020  3083 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,03-19 12:52:09.867  2383  3056 D Mms/Conversation: deleteTempConversation(),deleted=0
,03-19 12:52:09.867  3020  3083 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
03-19 12:52:09.867  1731  2205 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:52:09.867   363   363 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 3020
03-19 12:52:09.867   363   363 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,03-19 12:52:09.877  1501  1522 I art     : Explicit concurrent mark sweep GC freed 40474(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/12MB, paused 1.599ms total 137.472ms
,03-19 12:52:09.877  1018  3034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-19 12:52:09.877  1018  3034 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:09.877  2717  2808 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
03-19 12:52:09.877  1018  3034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:09.877  1018  3034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:52:09.877  2717  2808 E bt-btif : Calling BTA_HhEnable
,03-19 12:52:09.887  2717  2808 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,03-19 12:52:09.887  2717  2808 D BluetoothAdapterProperties: Address is:7C:F9:0E:51:18:22
,03-19 12:52:09.887  1018  1747 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,03-19 12:52:09.887  1018  1747 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.887  1018  1747 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:09.887  1018  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,03-19 12:52:09.887  2717  2808 E BluetoothServiceJni: populateRssiValuesNative
03-19 12:52:09.887  2717  2808 I bluedroid: getModelRssiValues
03-19 12:52:09.887  2717  2808 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-19 12:52:09.887  2717  2808 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,03-19 12:52:09.897  1351  1351 I WifiCredService: onCreate
,03-19 12:52:09.897  2717  2808 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A5)
,03-19 12:52:09.897  1501  1723 D SmsProvider: Update uri=content://sms/outbox, match=8
,03-19 12:52:09.907  1501  1723 D TP/MmsSmsProvider: need read changed broadcast:false
,03-19 12:52:09.907  1018  1018 D SettingsProvider: name = bluetooth_name
,03-19 12:52:09.907  2383  3056 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-19 12:52:09.907  1351  1351 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-19 12:52:09.907  1351  1351 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-19 12:52:09.907  1351  1351 D MY_TAG  : Action boot completed received
,03-19 12:52:09.907  2383  3056 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
,03-19 12:52:09.917  2383  3056 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
,03-19 12:52:09.917  2717  2808 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-19 12:52:09.917  2717  2808 D BluetoothAdapterProperties: Scan Mode:20
03-19 12:52:09.917  2717  2808 D BluetoothAdapterProperties: Discoverable Timeout:120
03-19 12:52:09.917  2717  2808 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:A2:30:44
03-19 12:52:09.917  2717  2808 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
03-19 12:52:09.917  2717  2808 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,03-19 12:52:09.917  2717  2808 E bt-btif : btif_sock_init: !radio_req && !rfc_init
03-19 12:52:09.917  2717  2808 E bt-btif : btif_sock_init: !vhci_init
,03-19 12:52:09.917  2717  2808 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,03-19 12:52:09.917  2717  3045 E bt_mct  : hci lib postload completed
,03-19 12:52:09.917  2735  2970 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-19 12:52:09.917  1351  1351 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,03-19 12:52:09.927  2717  2808 D IOP_DB_BT: db_open: db_open : handle 3023761424l, read 13894 bytes onto local cache
,03-19 12:52:09.927  2717  2808 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,03-19 12:52:09.927  2717  2808 D IOP_DB_BT: db_query: result 1
03-19 12:52:09.927  2717  2808 I         : iop_db_open: iop_db_open status 0
,03-19 12:52:09.927  1018  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-19 12:52:09.927  1018  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-19 12:52:09.927  1018  1132 E WifiNative-wlan0: invaild command id : 215
,03-19 12:52:09.927  1501  1517 D TP/SmsProvider: query,matched:26, calling pid = 2383
,03-19 12:52:09.927  1501  1517 D TP/SmsProvider: match 26:Elapsed time : 1.604 ms
,03-19 12:52:09.937  2383  3043 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-19 12:52:09.937  2383  3056 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
,03-19 12:52:09.937  2383  3056 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-19 12:52:09.937  2383  3056 D Mms/TelephonyPermission: isDefault true
,03-19 12:52:09.947  2717  2808 D bte_conf: Device ID record 1 : primary
,03-19 12:52:09.947  2717  2808 D bte_conf:   vendorId            = 0075
,03-19 12:52:09.947  2717  2808 D bte_conf:   vendorIdSource      = 0001
03-19 12:52:09.947  2717  2808 D bte_conf:   product             = 0100
03-19 12:52:09.947  2717  2808 D bte_conf:   version             = 0200
03-19 12:52:09.947  2717  2808 D bte_conf:   clientExecutableURL = 
03-19 12:52:09.947  2717  2808 D bte_conf:   serviceDescription  = 
03-19 12:52:09.947  2717  2808 D bte_conf:   documentationURL    = 
,03-19 12:52:09.947  2717  2808 D bte_conf: bte_load_did_conf no section named DID2.
03-19 12:52:09.947  2717  2808 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
03-19 12:52:09.947  2717  2802 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-19 12:52:09.947  2717  2802 D BluetoothAdapterProperties: ScanMode =  20
03-19 12:52:09.947  2717  2802 D BluetoothAdapterProperties: State =  11
03-19 12:52:09.947  1605  1617 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-19 12:52:09.957  1018  1747 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
03-19 12:52:09.957  2717  2802 D BluetoothAdapterProperties: Setting state to 12
03-19 12:52:09.957  2717  2802 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
03-19 12:52:09.957  1254  3002 V MediaScanner: processDirectory :  /system/media
03-19 12:52:09.957  2717  2808 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-19 12:52:09.957  2717  2808 D BluetoothAdapterProperties: Scan Mode:21
03-19 12:52:09.957  2717  2808 D BluetoothAdapterProperties: Discoverable Timeout:120
03-19 12:52:09.957  1018  1030 D SettingsProvider: name = bluetooth_a2dp_sink_mode
03-19 12:52:09.957  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 12:52:09.957  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:09.957  1018  1030 D SettingsProvider: selectionArgs: false
03-19 12:52:09.957  1018  1030 D SettingsProvider: selectionArgs: 1002
03-19 12:52:09.957  2735  2869 E BooksSync: Soft error
03-19 12:52:09.957  2735  2869 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-19 12:52:09.957  2735  2869 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-19 12:52:09.957  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 12:52:09.957  1018  1030 D SettingsProvider: ret = -1
03-19 12:52:09.957  2735  2869 E BooksSync: Sync error
03-19 12:52:09.957  2735  2869 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-19 12:52:09.957  2735  2869 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-19 12:52:09.957  2735  2869 I BooksSync: Finished books sync
03-19 12:52:09.957  1018  1030 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-19 12:52:09.967  2717  2802 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-19 12:52:09.967  1501  1724 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2383
03-19 12:52:09.967  2717  2802 D BluetoothAdapterService: updateAdapterState state is 12
,03-19 12:52:09.977  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,03-19 12:52:09.977  1018  1043 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 25359, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-19 12:52:09.977  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.977  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:09.977  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-19 12:52:09.977  2717  2802 D BluetoothAdapterService: Autoconnection is available 
03-19 12:52:09.977  2717  2802 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
03-19 12:52:09.977  2717  2802 D BluetoothAdapterService: starting service from this receiver
,03-19 12:52:09.987  1018  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
03-19 12:52:09.987  1018  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-19 12:52:09.987  1018  1392 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,03-19 12:52:09.987  2717  2732 D BluetoothA2dp: onBluetoothStateChange: up=true
03-19 12:52:09.987  1018  1392 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:09.987  1018  1392 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:09.987  1018  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-19 12:52:09.987  1018  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
,03-19 12:52:09.987  1501  1517 D BluetoothAdapter: onBluetoothStateChange: up=true
,03-19 12:52:09.987  2717  2802 I BluetoothAdapterState: Entering On State from state = 11
,03-19 12:52:09.987  1501  1517 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-19 12:52:09.997  2717  2729 D BluetoothAdapter: onBluetoothStateChange: up=true
03-19 12:52:09.997  2717  2729 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-19 12:52:09.997  1200  1954 D BluetoothAdapter: onBluetoothStateChange: up=true
,03-19 12:52:09.997  1200  1954 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-19 12:52:09.997  1605  1617 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-19 12:52:09.997  1605  1617 D BadgeProvider: sendNotify, [notify] : null
03-19 12:52:09.997  1605  1617 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-19 12:52:09.997  1605  1617 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-19 12:52:09.997  1605  1617 D BadgeProvider: update, [UpdateCount] : 1
,03-19 12:52:09.997  1530  1530 D Launcher.Model: reloadBadges entered.
,03-19 12:52:09.997  1484  1500 D BluetoothAdapter: onBluetoothStateChange: up=true
,03-19 12:52:09.997  1484  1500 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-19 12:52:09.997  1477  2146 D BluetoothAdapter: onBluetoothStateChange: up=true
03-19 12:52:09.997  1477  2146 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-19 12:52:10.007  1655  2113 D BluetoothAdapter: onBluetoothStateChange: up=true
,03-19 12:52:10.007  1200  1200 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:10.007  1655  2113 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-19 12:52:10.007  3005  3018 D BluetoothAdapter: onBluetoothStateChange: up=true
03-19 12:52:10.007  3005  3018 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-19 12:52:10.007  3005  3005 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 12:52:10.007  2187  2204 D BluetoothAdapter: onBluetoothStateChange: up=true
03-19 12:52:10.007  2187  2204 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-19 12:52:10.007  1200  1200 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 12:52:10.007  1200  1200 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-19 12:52:10.007  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:10.007  2984  2984 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,03-19 12:52:10.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:10.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:10.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 12:52:10.017  1018  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,03-19 12:52:10.017  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-19 12:52:10.017  2383  3043 D Mms/MessagingNotification: setBadgeCount(), count=0
03-19 12:52:10.017  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
03-19 12:52:10.017  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,03-19 12:52:10.027  2383  3043 D Mms/MessagingNotification: remove alarm
,03-19 12:52:10.027  1477  1477 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@19a3981, true
,03-19 12:52:10.027  1477  1477 D BluetoothHeadset: registerMessageListener
,03-19 12:52:10.037  1200  1200 D BluetoothTile:  onBluetoothStateChange:
,03-19 12:52:10.037  1828  1828 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,03-19 12:52:10.047  1200  1200 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-19 12:52:10.047  1200  1200 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-19 12:52:10.047  1200  1200 D BluetoothTile:  getBluetoothState : 12
,03-19 12:52:10.047  2984  2984 D [0]UMC:AdminManager: init - start
,03-19 12:52:10.047  1254  3002 V MediaScanner:  prescan time: 724ms (DB items: 141)
03-19 12:52:10.047  1254  3002 V MediaScanner:     scan time: 129ms (Caching mode: true), (makeEntry time: 36ms ~27%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-19 12:52:10.047  1254  3002 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-19 12:52:10.047  1254  3002 V MediaScanner:    total time: 853ms
03-19 12:52:10.047  1254  3002 V MediaScanner: checked files: 133  directories : 6  (I: 0, U: 0)
,03-19 12:52:10.047  1254  3002 D MediaScanner: checkDefaultSounds
,03-19 12:52:10.047  1254  3002 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
,03-19 12:52:10.047  2717  2729 D HeadsetService: registerMessageListener
,03-19 12:52:10.047  1018  3036 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-19 12:52:10.057  2063  2063 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-19 12:52:10.057  2063  2063 I dhcpcd  : wlan0: no IPv6 Routers available
,03-19 12:52:10.057  1018  1238 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
03-19 12:52:10.057  3005  3005 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-19 12:52:10.057  2717  2729 D HeadsetService: registerMessageListener
03-19 12:52:10.057  2717  2837 D HeadsetStateMachine: Disconnected process message: 70
,03-19 12:52:10.057  2717  2837 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@a0a5580
03-19 12:52:10.057  1477  1477 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
03-19 12:52:10.057  1477  1477 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,03-19 12:52:10.067  1018  1728 I ActivityManager: Killing 1770:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,03-19 12:52:10.067  1200  1750 D BluetoothTile:  handleUpdatestate:false name:null
,03-19 12:52:10.067  1200  1200 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,03-19 12:52:10.067  1351  1351 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,03-19 12:52:10.067  1477  1477 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-19 12:52:10.067  2984  2984 D [0]UMC:AdminManager: loadAdmins
03-19 12:52:10.067  1477  1477 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,03-19 12:52:10.067  1477  1477 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,03-19 12:52:10.077  3005  3005 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-19 12:52:10.077  3005  3005 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-19 12:52:10.077  1018  1030 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,03-19 12:52:10.077  1200  1750 D BluetoothTile:  handleUpdatestate:false name:null
,03-19 12:52:10.077  1351  2611 V NearbySettings: MountReceiver.mPrefHandler - 7002
,03-19 12:52:10.087  1018  3036 I ActivityManager: Killing 1572:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,03-19 12:52:10.087  3005  3005 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-19 12:52:10.087  2984  2984 D [0]UMC:AdminManager: init - end
,03-19 12:52:10.087  2984  2984 D GSLBManager: migrateStoredUrlFromOldPref
,03-19 12:52:10.097  1501  1517 D TP/SmsProvider: query,matched:0, calling pid = 2383
,03-19 12:52:10.097  1501  1517 D TP/SmsProvider: match 0:Elapsed time : 1.312 ms
,03-19 12:52:10.097  1200  1750 D BluetoothTile:  handleUpdatestate:false name:null
,03-19 12:52:10.097  1501  1522 D TP/MmsSmsProvider: query,matched:200, calling pid = 2383,
03-19 12:52:10.097  2717  2837 D HeadsetStateMachine: Disconnected process message: 9
03-19 12:52:10.097  2717  2837 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6,
,03-19 12:52:10.107   282   773 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
03-19 12:52:10.107   282   773 V voice   : voice_set_parameters: enter: A2dpSuspended=false
03-19 12:52:10.107   282   773 V voice   : voice_set_parameters: exit with code(-2)
03-19 12:52:10.107   282   773 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
03-19 12:52:10.107   282   773 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-19 12:52:10.107   282   773 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-19 12:52:10.107   282   773 V audio_hw_primary: adev_set_parameters: exit
03-19 12:52:10.107  2717  2837 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,03-19 12:52:10.107  1501  1522 D TP/MmsSmsProvider: match 200:Elapsed time : 9.961 ms
,03-19 12:52:10.117  2383  3043 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 713.314374
,03-19 12:52:10.117  1018  3034 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-19 12:52:10.117  1018  3034 D SecContentProvider2: mCursor = null
,03-19 12:52:10.117  2383  3118 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-19 12:52:10.127  1501  1517 D TP/SmsProvider: query,matched:0, calling pid = 2383
,03-19 12:52:10.127  1501  1517 D TP/SmsProvider: match 0:Elapsed time : 1.126 ms
,03-19 12:52:10.137  1501  1522 D TP/SmsProvider: query,matched:51, calling pid = 2383
,03-19 12:52:10.137  1501  1522 D TP/SmsProvider: match 51:Elapsed time : 0.925 ms
,03-19 12:52:10.147  2383  3056 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-19 12:52:10.147  1605  1617 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-19 12:52:10.157  2717  2717 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,03-19 12:52:10.167  3085  3085 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,03-19 12:52:10.167  3005  3005 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 12:52:10.167  3005  3005 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 12:52:10.167  1254  3002 D MediaScanner: OK. alarm_alert is already exist in setting DB.
,03-19 12:52:10.177  1351  1351 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-19 12:52:10.177  1351  1351 I NearbySettings: MountReceiver.onReceive - Internal Path
,03-19 12:52:10.177  1018  1043 W libprocessgroup: failed to open /acct/uid_10138/pid_1770/cgroup.procs: No such file or directory
03-19 12:52:10.177  1018  1043 W libprocessgroup: failed to open /acct/uid_10057/pid_1572/cgroup.procs: No such file or directory
,03-19 12:52:10.187  1254  3002 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
,03-19 12:52:10.187  2984  2984 D GSLBManager:  key : segd-api
03-19 12:52:10.187  2984  2984 D GSLBManager:  value : https://eu-segd-api.secb2b.com:443/v2
,03-19 12:52:10.197  1018  1555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-19 12:52:10.197  1018  1387 D SettingsProvider: name = personal_mode_enabled
,03-19 12:52:10.197  1018  1555 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:10.197  1018  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:10.197  1018  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:10.197  1254  3002 D MediaScanner: OK. notification_sound is already exist in setting DB.
,03-19 12:52:10.197  1200  1200 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:10.197  1530  1530 D Launcher.Model: reloadBadges entered.
03-19 12:52:10.197  1605  1617 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-19 12:52:10.197  1605  1617 D BadgeProvider: sendNotify, [notify] : null
03-19 12:52:10.197  1605  1617 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-19 12:52:10.197  1605  1617 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-19 12:52:10.197  1605  1617 D BadgeProvider: update, [UpdateCount] : 1
,03-19 12:52:10.207  1254  3002 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
,03-19 12:52:10.207  1254  3002 D MediaScanner: OK. ringtone is already exist in setting DB.
03-19 12:52:10.207  1018  1728 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-19 12:52:10.207  1018  1728 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:10.207  1018  1728 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:10.207  1018  1728 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:10.217  2717  2717 I BluetoothPbapService: Handler(): got msg=1
,03-19 12:52:10.217  1018  1392 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-19 12:52:10.217  2383  3056 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-19 12:52:10.227  1254  3002 D MediaScannerService: !@done scanning volume internal
,03-19 12:52:10.227  2717  3127 V BluetoothPbapService: PBAP Service initSocket try: 0
,03-19 12:52:10.237  2677  2677 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2677) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,03-19 12:52:10.237  2677  2677 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2677) ACTION_MEDIA_SCANNER_FINISHED = /system/media
,03-19 12:52:10.237  2677  2677 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2677) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,03-19 12:52:10.237  2383  3056 D Mms/MessagingNotification: remove alarm
03-19 12:52:10.237  2717  3127 D BluetoothSocket: bindListen(): myUserId = 0
03-19 12:52:10.237  2717  3127 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-19 12:52:10.237  2383  3126 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-19 12:52:10.237  1254  3002 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,03-19 12:52:10.237  2717  3127 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]},
03-19 12:52:10.237  2717  3127 D BluetoothSocket: bindListen(), new LocalSocket 
03-19 12:52:10.237  2717  3127 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,03-19 12:52:10.237  2717  3127 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@286d5498
03-19 12:52:10.237  2717  3127 D BluetoothSocket: channel: 19
03-19 12:52:10.247  2717  3127 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,03-19 12:52:10.247  2717  3129 D BluetoothMapMasInstance: set MAP SDP message type : 1
,03-19 12:52:10.247  1501  1522 D TP/SmsProvider: query,matched:0, calling pid = 2383
,03-19 12:52:10.257  2717  3129 D BluetoothSocket: bindListen(): myUserId = 0
03-19 12:52:10.257  2717  3129 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-19 12:52:10.257  2717  3129 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
03-19 12:52:10.257  2717  3129 D BluetoothSocket: bindListen(), new LocalSocket 
03-19 12:52:10.257  2717  3129 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-19 12:52:10.257  2717  3129 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@be384f1
03-19 12:52:10.257  2717  3129 D BluetoothSocket: channel: 5
,03-19 12:52:10.257  3085  3085 D DSM     : [Lines:107] Normal booted
03-19 12:52:10.257  2984  2984 D GSLBManager:  key : umc-cdn
03-19 12:52:10.257  2984  2984 D GSLBManager:  value : 
03-19 12:52:10.257  3085  3085 D DSM     : [Lines:114] Boot completed
,03-19 12:52:10.257  1501  1522 D TP/SmsProvider: match 0:Elapsed time : 8.510 ms
,03-19 12:52:10.257  1254  3002 D MediaProvider: savePlaylistTableInBulkDeleter started
03-19 12:52:10.257  1254  3002 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-19 12:52:10.267  1254  3002 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,03-19 12:52:10.267  1254  3002 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-19 12:52:10.267  1254  3002 D MediaProvider: savePlaylistTableInBulkDeleter started
03-19 12:52:10.267  1254  3002 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-19 12:52:10.267  1254  3002 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
03-19 12:52:10.267  1501  1501 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-19 12:52:10.267  1501  1501 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-19 12:52:10.267  1501  1501 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-19 12:52:10.267  1501  1501 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:52:10.267  1501  1501 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-19 12:52:10.267  1501  1501 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-19 12:52:10.267  1254  3002 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-19 12:52:10.277  1018  1728 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,03-19 12:52:10.277  1018  1728 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:10.277  1018  1728 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:10.277  1018  1728 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:10.277  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:10.277  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.277  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.277  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:10.287  1254  3002 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-19 12:52:10.297  3132  3132 E Zygote  : MountEmulatedStorage()
03-19 12:52:10.297  3132  3132 I libpersona: KNOX_SDCARD checking this for 1000
,03-19 12:52:10.297  3132  3132 E Zygote  : v2
03-19 12:52:10.297  3132  3132 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:10.297  3132  3132 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:10.297  3132  3132 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:10.297  1018  1031 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3132 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 12:52:10.297  3132  3132 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:10.297  1018  1031 I ActivityManager: Killing 2187:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-19 12:52:10.307  1018  1392 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-19 12:52:10.307  2383  3056 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 194.330104
,03-19 12:52:10.307  1018  1392 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:10.307  1018  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:10.307  1018  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:10.317  1351  1351 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-19 12:52:10.317  1351  1351 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
,03-19 12:52:10.327  3005  3149 D OpenGLRenderer: Render dirty regions requested: true
,03-19 12:52:10.337  1018  1387 I ActivityManager: Killing 2212:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31,
,03-19 12:52:10.337  1018  1238 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-19 12:52:10.337  1018  1238 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-19 12:52:10.337  1018  1238 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-19 12:52:10.337  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-19 12:52:10.337  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-19 12:52:10.337  3005  3075 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-19 12:52:10.347  3132  3132 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:10.347  3005  3005 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-19 12:52:10.347  3005  3005 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-19 12:52:10.347  3132  3132 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:10.347  1254  3002 V MediaScanner: processDirectory :  /storage/emulated/0
,03-19 12:52:10.357  1254  3002 D MediaScanner: Skipping:
03-19 12:52:10.357  1254  3002 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
,03-19 12:52:10.357  2984  2984 D GSLBManager:  key : segp-api
03-19 12:52:10.357  1254  3002 D MediaScanner: Skipping:
03-19 12:52:10.357  1254  3002 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-19 12:52:10.357  2984  2984 D GSLBManager:  value : 
,03-19 12:52:10.357   256   256 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-19 12:52:10.367  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.367  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.367  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.367  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:10.367  1018  1392 D InputDispatcher: Focus entered window: 3005
,03-19 12:52:10.377  3132  3132 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-19 12:52:10.377  3150  3150 E Zygote  : MountEmulatedStorage(),
03-19 12:52:10.377  3150  3150 E Zygote  : v2
03-19 12:52:10.377  3150  3150 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:10.377  1254  3002 V MediaScanner: processDirectory :  /storage/extSdCard
03-19 12:52:10.377  3150  3150 I libpersona: KNOX_SDCARD not a persona,
03-19 12:52:10.377  1254  3002 W MediaScanner: Error opening directory, reason : Permission denied.
03-19 12:52:10.377  1254  3002 W MediaScanner: 7klwibgf7fxlKdCbid7
03-19 12:52:10.387  3150  3150 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:10.387  1351  1351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-19 12:52:10.387  1018  1030 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3150 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 12:52:10.387  3150  3150 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:10.387  3150  3150 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:10.387  1254  3002 V MediaScanner:  prescan time: 80ms (DB items: 27)
03-19 12:52:10.387  1254  3002 V MediaScanner:     scan time: 32ms (Caching mode: true), (makeEntry time: 22ms ~68%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-19 12:52:10.387  1254  3002 V MediaScanner: postscan time: 7ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-19 12:52:10.387  1254  3002 V MediaScanner:    total time: 119ms
03-19 12:52:10.387  1254  3002 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
03-19 12:52:10.387  1018  1030 I ActivityManager: Killing 1545:com.android.printspooler/u0a136 (adj 15): empty #31
,03-19 12:52:10.387  3005  3005 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-19 12:52:10.387  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-19 12:52:10.387  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-19 12:52:10.387  3005  3149 I OpenGLRenderer: Initialized EGL, version 1.4
,03-19 12:52:10.397  1254  3002 D MediaScannerService: !@done scanning volume external
,03-19 12:52:10.397  2677  2677 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2677) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-19 12:52:10.397  2677  2677 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2677) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-19 12:52:10.397  2677  2677 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2677) ...
03-19 12:52:10.397  2677  2677 D FactoryTestApp: [Support$Values.getString](2677) id=MODEL_COMMUNICATION_MODE, value=gsm
03-19 12:52:10.397  2677  2677 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2677) mConnectionMode = gsm
03-19 12:52:10.397  3005  3149 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-19 12:52:10.397  3005  3149 D OpenGLRenderer: Enabling debug mode 0
03-19 12:52:10.397  2677  2677 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2677) Create IPCWriterToSecPhoneService
03-19 12:52:10.397  2677  2677 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2677)  
,03-19 12:52:10.407  1351  1351 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-19 12:52:10.417  3150  3150 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:10.417  3150  3150 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:10.447  3150  3150 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-19 12:52:10.467  2677  2677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-19 12:52:10.467  1018  1393 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-19 12:52:10.467  1018  1393 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:10.467  1018  1393 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-19 12:52:10.467  1018  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,03-19 12:52:10.477  2677  2677 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2677) connected done
03-19 12:52:10.477  2677  2677 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2677) Send Response Message to SecPhone
03-19 12:52:10.477  2677  2677 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2677) Response ��
,03-19 12:52:10.497   313  1075 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-19 12:52:10.497  2677  2677 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2677) Send BOOTING COMPLETED done
,03-19 12:52:10.527  1351  1351 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-19 12:52:10.527  1018  1043 W libprocessgroup: failed to open /acct/uid_10031/pid_2187/cgroup.procs: No such file or directory
,03-19 12:52:10.527  1018  1043 W libprocessgroup: failed to open /acct/uid_10050/pid_2212/cgroup.procs: No such file or directory
03-19 12:52:10.527  1018  1043 W libprocessgroup: failed to open /acct/uid_10136/pid_1545/cgroup.procs: No such file or directory
,03-19 12:52:10.527  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:10.527  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.527  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.527  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:10.537  1351  1351 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
,03-19 12:52:10.537  3170  3170 E Zygote  : MountEmulatedStorage()
,03-19 12:52:10.537  3170  3170 E Zygote  : v2
03-19 12:52:10.537  3170  3170 I libpersona: KNOX_SDCARD checking this for 10086
03-19 12:52:10.537  3170  3170 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:10.547  3170  3170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-19 12:52:10.547  2984  2984 D GSLBManager:  key : myknoxapi
,03-19 12:52:10.547  1351  1351 I SettingSearch/SearchIntentReceiver: search setting db init!!
03-19 12:52:10.547  1018  1392 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3170 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,03-19 12:52:10.547  3170  3170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:10.547  3170  3170 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
03-19 12:52:10.547  2984  2984 D GSLBManager:  value : 
,03-19 12:52:10.547  1351  1351 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-19 12:52:10.557  2034  3131 I iu.UploadsManager: #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,03-19 12:52:10.557  1351  3179 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-19 12:52:10.567  1018  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.567  1018  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.567  1018  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.567  1018  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:10.577  3187  3187 E Zygote  : MountEmulatedStorage(),
03-19 12:52:10.577  3187  3187 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:10.577  3187  3187 E Zygote  : v2
03-19 12:52:10.577  3187  3187 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:10.577  3187  3187 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:10.577  3170  3170 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:10.587  3170  3170 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:10.587  3187  3187 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-19 12:52:10.587  1018  1728 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3187 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 12:52:10.587  3187  3187 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:10.597  2984  2984 D GSLBManager: migrateStoredUrlFromOldPref : Finished Migrating
,03-19 12:52:10.597  2984  2984 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-19 12:52:10.597  2984  2984 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-19 12:52:10.597  2984  2984 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,03-19 12:52:10.597  2984  2984 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
,03-19 12:52:10.597   313  1075 D AT_Distributor: SetAtdStatus(), 1_1_0
03-19 12:52:10.597   313  1075 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-19 12:52:10.597  2984  2984 D [0]UMC:UMCAdmin: isContainer : 0
,03-19 12:52:10.607  3132  3132 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-19 12:52:10.617  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.617  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.617  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.617  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:10.617  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-19 12:52:10.617  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,03-19 12:52:10.617  1018  1728 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-19 12:52:10.617  3132  3132 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
03-19 12:52:10.617  2984  2984 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-19 12:52:10.617  2984  2984 D [0]UMC:UMCAdmin: isContainer : 0
,03-19 12:52:10.627  2984  2984 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated,
03-19 12:52:10.637  1018  1401 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3202 uid=10150 gids={50150, 9997} abi=armeabi-v7a
03-19 12:52:10.637  3202  3202 E Zygote  : MountEmulatedStorage()
03-19 12:52:10.637  3202  3202 E Zygote  : v2
03-19 12:52:10.637  3202  3202 I libpersona: KNOX_SDCARD checking this for 10150
,03-19 12:52:10.637  3202  3202 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:10.637  3202  3202 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:10.637  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
03-19 12:52:10.637  3202  3202 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:10.637  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-19 12:52:10.637  3202  3202 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-19 12:52:10.637  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:10.637  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:10.637  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
03-19 12:52:10.647  2984  2984 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
03-19 12:52:10.647  2984  2984 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-19 12:52:10.647  2984  2984 D [0]UMC:CoreReceiver:  check PreETag 
03-19 12:52:10.647  3187  3187 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:10.647  3187  3187 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-19 12:52:10.657  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-19 12:52:10.667  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-19 12:52:10.677  3132  3132 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-19 12:52:10.677   287   287 E SMD     : DCD OFF
,03-19 12:52:10.677  3132  3132 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,03-19 12:52:10.687  2984  2984 D [0]UMC:CoreReceiver: bulk enrolled package: null
03-19 12:52:10.687  2984  2984 V [0]UMC:ProfileStorage: Enter loadList
03-19 12:52:10.687  2984  2984 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
03-19 12:52:10.687  2984  2984 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-19 12:52:10.687  2984  2984 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-19 12:52:10.687   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:52:10.687  2984  2984 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-19 12:52:10.687  1018  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.687  2984  2984 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-19 12:52:10.687  1018  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.687  2984  2984 D [0]UMC:UMCAdmin: isContainer : 0
,03-19 12:52:10.687  1018  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:10.687  1018  1728 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:10.707  3202  3202 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:10.707   363   363 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
03-19 12:52:10.707  3202  3202 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:10.707  3221  3221 E Zygote  : MountEmulatedStorage()
,03-19 12:52:10.707  3221  3221 E Zygote  : v2
03-19 12:52:10.707  3221  3221 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:10.707  3221  3221 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:10.707  3221  3221 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:10.717  1018  1140 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0,
03-19 12:52:10.717  1018  1728 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3221 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-19 12:52:10.717  3221  3221 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:10.717  2984  2984 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-19 12:52:10.717  2984  2984 D [0]UMC:UMCAdmin: isContainer : 0
03-19 12:52:10.717  3221  3221 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:10.727  1018  3034 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-19 12:52:10.737  1018  1728 I ActivityManager: Killing 2228:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,03-19 12:52:10.737   308   308 I art     : Explicit concurrent mark sweep GC freed 8738(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 654us total 26.427ms
,03-19 12:52:10.737  1018  3228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 12:52:10.747  3187  3187 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-19 12:52:10.757  2717  2838 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-19 12:52:10.757   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 17.841ms
,03-19 12:52:10.767  1200  1200 D PanelView: There is/are notification(s) 
03-19 12:52:10.767  1018  1050 I ActivityManager: Displayed Component not be shown by security: +1s744ms
03-19 12:52:10.767  1018  1050 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-19 12:52:10.777  1018  1050 W ActivityManager: mDVFSHelper.release()
03-19 12:52:10.777  1018  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8f45c04 u0 com.test.thalitest/.MainActivity t236} time:37210
,03-19 12:52:10.777  1018  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-19 12:52:10.777   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 18.327ms
,03-19 12:52:10.777  3005  3005 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e8baa11 time:37219
,03-19 12:52:10.787  1828  1828 I SamsungIME: getCurrentCandidateView
,03-19 12:52:10.797  2984  2984 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-19 12:52:10.797  3221  3221 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:10.797  3221  3221 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:10.817  2984  2984 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-19 12:52:10.817  2984  2984 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
03-19 12:52:10.817  2984  2984 I [0]UMC:Core: shutdown
,03-19 12:52:10.817  1018  1555 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-19 12:52:10.817  1018  1555 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:10.817  1018  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-19 12:52:10.817  1018  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-19 12:52:10.827  2984  2984 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-19 12:52:10.827  2984  2984 I art     : System.exit called, status: 0
,03-19 12:52:10.827  2984  2984 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-19 12:52:10.827  3020  3083 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,03-19 12:52:10.847  3020  3083 I SecureStorage: [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,03-19 12:52:10.857  1018  1747 I art     : Explicit concurrent mark sweep GC freed 17912(897KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/40MB, paused 2.779ms total 176.152ms
,03-19 12:52:10.867  2717  2838 D BluetoothMediaBrowser: no now playing list
03-19 12:52:10.867  2717  2838 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
03-19 12:52:10.867  3170  3170 E UpdateRequestReceiver: ignoring update request
,03-19 12:52:10.877  2034  3131 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 323 ms
,03-19 12:52:10.877  3170  3170 E UpdateRequestReceiver: ignoring update request
,03-19 12:52:10.897  1018  1043 W libprocessgroup: failed to open /acct/uid_10113/pid_2228/cgroup.procs: No such file or directory
,03-19 12:52:10.897  1018  1140 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2984)(adj 0) has died(88,1096)
,03-19 12:52:10.907  1322  1322 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-19 12:52:10.917  1828  1828 D SamsungIME: Dismiss ExpandCandiate
,03-19 12:52:10.917  1322  1322 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-19 12:52:10.927  1322  1322 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-19 12:52:10.927  1322  1322 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-19 12:52:10.927  1828  1828 I SamsungIME: getDebugLevel  : 0x4f4c
,03-19 12:52:10.927  3187  3187 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-19 12:52:10.927  1322  1322 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-19 12:52:10.937  1322  1322 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,03-19 12:52:10.937  1322  1322 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-19 12:52:10.937  1322  1322 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-19 12:52:10.937  1322  1322 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-19 12:52:10.937  1322  1322 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-19 12:52:10.937  1322  1322 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-19 12:52:10.937  1322  1322 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-19 12:52:10.937  1018  1730 D SettingsProvider: name = aw_daemon_service_key_version_check
,03-19 12:52:10.937  1018  1730 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-19 12:52:10.937  1018  1730 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:10.937  1018  1730 D SettingsProvider: selectionArgs: false
,03-19 12:52:10.937  1018  1730 D SettingsProvider: selectionArgs: 10162
,03-19 12:52:10.937  1018  1730 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 12:52:10.937  1018  1730 D SettingsProvider: ret = -1
,03-19 12:52:10.977   256   442 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-19 12:52:10.977   256  1847 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-19 12:52:10.987  3170  3170 E UpdateRequestReceiver: ignoring update request
,03-19 12:52:10.997  3221  3221 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-19 12:52:11.007  1200  1200 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 12:52:11.007  1200  1200 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-19 12:52:11.007  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 12:52:11.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 12:52:11.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 12:52:11.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 12:52:11.027  1018  1730 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-19 12:52:11.027  3170  3170 E UpdateRequestReceiver: ignoring update request
,03-19 12:52:11.037  3005  3005 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3005
,03-19 12:52:11.047  1322  1322 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-19 12:52:11.047  1200  1200 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:11.047  1322  1322 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-19 12:52:11.047  1322  1322 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-19 12:52:11.057  1322  1322 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-19 12:52:11.057  1322  1322 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-19 12:52:11.057  1322  1322 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-19 12:52:11.067  3187  3187 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-19 12:52:11.067  1322  1322 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-19 12:52:11.067  1322  1322 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-19 12:52:11.077  3170  3170 E UpdateRequestReceiver: ignoring update request
,03-19 12:52:11.077  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-19 12:52:11.087  3187  3187 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-19 12:52:11.087  3187  3187 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-19 12:52:11.087  1322  1322 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458388331080
,03-19 12:52:11.087  1322  1322 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458409920000
03-19 12:52:11.087  1322  1322 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-19 12:52:11.087  1322  1322 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-19 12:52:11.097  1322  1322 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458409920000
,03-19 12:52:11.097  1322  1322 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,03-19 12:52:11.097  1322  1322 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458409920000
,03-19 12:52:11.117  3170  3170 E UpdateRequestReceiver: ignoring update request
,03-19 12:52:11.127  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:11.127  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.127  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:11.127  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:11.147  3261  3261 E Zygote  : MountEmulatedStorage()
03-19 12:52:11.147  3261  3261 E Zygote  : v2
03-19 12:52:11.147  3261  3261 I libpersona: KNOX_SDCARD checking this for 10094
03-19 12:52:11.147  3261  3261 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:11.147  3261  3261 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:11.147  1828  1828 I SamsungIME: getDebugLevel  : 0x4f4c
,03-19 12:52:11.157  1018  1392 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3261 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-19 12:52:11.157  1018  1392 I ActivityManager: Killing 1754:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-19 12:52:11.157  3261  3261 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:11.157  3261  3261 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:11.157  1322  1322 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-19 12:52:11.157  1322  1322 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-19 12:52:11.167  1982  1982 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-19 12:52:11.177  1018  1238 D ActivityManager: retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,03-19 12:52:11.177  1018  1238 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:11.177  1018  1238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.177  1018  1238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-19 12:52:11.177  1982  1982 D SecUISvc: Service started flags 0 startId 1
,03-19 12:52:11.187  1982  3275 D SecUISvc: Thread created.
,03-19 12:52:11.187  3261  3261 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:11.187  3261  3261 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:11.187  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.187  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.187  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.187  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:11.207  1018  1401 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3278 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:52:11.207  3278  3278 E Zygote  : MountEmulatedStorage()
03-19 12:52:11.207  3278  3278 I libpersona: KNOX_SDCARD checking this for 10028
03-19 12:52:11.207  3278  3278 E Zygote  : v2
03-19 12:52:11.207  3278  3278 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:11.207  3278  3278 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:11.217  3278  3278 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:11.217  3278  3278 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-19 12:52:11.217  1828  1828 I SamsungIME: KeybaordView init() : load resources
,03-19 12:52:11.227  1018  1030 I ActivityManager: Killing 2368:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-19 12:52:11.237  1018  1043 W libprocessgroup: failed to open /acct/uid_10015/pid_1754/cgroup.procs: No such file or directory
,03-19 12:52:11.267  3187  3187 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-19 12:52:11.267  3187  3187 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-19 12:52:11.267  3187  3187 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-19 12:52:11.267  1018  1555 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-19 12:52:11.277  1018  1555 W ActivityManager: userId = 0, bbcId = -10000,
03-19 12:52:11.277  1018  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.277  1018  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-19 12:52:11.277  3278  3278 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:11.277  3278  3278 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:11.287  3221  3221 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-19 12:52:11.297  3187  3187 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-19 12:52:11.297  3187  3187 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-19 12:52:11.297  3221  3221 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-19 12:52:11.297  3187  3187 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-19 12:52:11.307  3221  3221 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-19 12:52:11.307  3221  3221 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,03-19 12:52:11.307  3221  3221 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-19 12:52:11.307  3221  3221 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-19 12:52:11.307  3020  3020 E BluetoothHeadset: BTStateChangeCB is registed
,03-19 12:52:11.307  1200  1200 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-19 12:52:11.317  1200  1200 D OverheatReceiver: into the SAFE_MODE_ACTION
03-19 12:52:11.317  1200  1200 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-19 12:52:11.317  3187  3187 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-19 12:52:11.317  1200  1200 D OverheatReceiver: isSafeMode = false
,03-19 12:52:11.317  3020  3020 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-19 12:52:11.317  3187  3187 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-19 12:52:11.317  1828  1828 I SamsungIME: getCurrentKeyboard
03-19 12:52:11.317  1828  1828 I SamsungIME: getTextKeyboard
,03-19 12:52:11.327  3187  3187 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-19 12:52:11.327  3261  3261 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
03-19 12:52:11.327  3187  3187 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-19 12:52:11.327  3261  3261 D elm:15183: ELMEngine.ELMEngine( context ).
,03-19 12:52:11.327  3187  3187 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-19 12:52:11.327  3261  3261 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-19 12:52:11.327  3187  3187 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-19 12:52:11.327  3187  3187 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-19 12:52:11.337  3187  3187 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-19 12:52:11.337  1018  1730 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-19 12:52:11.337  1018  1730 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:11.337  1018  1730 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.337  1018  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-19 12:52:11.347  3187  3187 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-19 12:52:11.347  1018  1393 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-19 12:52:11.347  3187  3254 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-19 12:52:11.347  1501  1501 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
03-19 12:52:11.347  1018  1393 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:11.347  1018  1393 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.347  1018  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-19 12:52:11.347  1018  1393 D SettingsProvider: name = internet_call_settings_visibility
03-19 12:52:11.347  1018  1393 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 12:52:11.347  1018  1393 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:11.347  1018  1393 D SettingsProvider: selectionArgs: false
03-19 12:52:11.347  1018  1393 D SettingsProvider: selectionArgs: 1001
03-19 12:52:11.347  1018  1393 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 12:52:11.347  1018  1393 D SettingsProvider: ret = -1
,03-19 12:52:11.347  1501  1501 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-19 12:52:11.347  3020  3020 E BluetoothHeadset: BluetoothHeadset service is binded
,03-19 12:52:11.357  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2368/cgroup.procs: No such file or directory
,03-19 12:52:11.367  3261  3261 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-19 12:52:11.367  3187  3254 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-19 12:52:11.367  3187  3254 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-19 12:52:11.377  1018  1140 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-19 12:52:11.377  3261  3261 D elm:15183: ElmAgentService : onCreate()
,03-19 12:52:11.387  3020  3020 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
03-19 12:52:11.387  1018  1140 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:11.387  1018  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.387  1018  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-19 12:52:11.387  1018  1140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,03-19 12:52:11.397  1018  1140 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:11.397  1018  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.397  1018  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-19 12:52:11.397  1477  1477 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-19 12:52:11.397  1018  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-19 12:52:11.397  1018  1555 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:11.397  1018  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.397  1018  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-19 12:52:11.397  1462  1462 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-19 12:52:11.407  3261  3295 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-19 12:52:11.407  1477  1477 I Telecom : InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
,03-19 12:52:11.407  1018  3036 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-19 12:52:11.407  1828  1828 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-19 12:52:11.407  3261  3261 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-19 12:52:11.407  3261  3261 D elm:15183: BootCompletedState : startBootCompleted() call
,03-19 12:52:11.417  3261  3261 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-19 12:52:11.427  1018  3036 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:11.427  1018  3036 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,03-19 12:52:11.427  1018  3036 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
,03-19 12:52:11.427  1462  1462 V EmergencyMode: [EmergencyBase] setBootTime
,03-19 12:52:11.427  1462  1462 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-19 12:52:11.437  3261  3261 I elm:15183: Get License : 0
,03-19 12:52:11.437  1018  1031 E Tethering: No numeric data
,03-19 12:52:11.437  1018  3036 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:11.437  1018  3036 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:11.437  1018  3036 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.437  1018  3036 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:11.447  3187  3187 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-19 12:52:11.457  3187  3187 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-19 12:52:11.457  1018  1392 E Tethering: No numeric data
,03-19 12:52:11.467  3298  3298 E Zygote  : MountEmulatedStorage()
03-19 12:52:11.467  3298  3298 E Zygote  : v2
03-19 12:52:11.467  3298  3298 I libpersona: KNOX_SDCARD checking this for 10012
03-19 12:52:11.467  3298  3298 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:11.467  3298  3298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:11.467  1018  3036 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=3298 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-19 12:52:11.467  3187  3187 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-19 12:52:11.467  3298  3298 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:11.467  3298  3298 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-19 12:52:11.467  1018  1555 E Tethering: No numeric data
,03-19 12:52:11.467  1018  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:11.467  1018  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.467  1018  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.467  3187  3187 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
03-19 12:52:11.467  1018  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:11.477  3187  3187 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!,
,03-19 12:52:11.477  3187  3187 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
03-19 12:52:11.477  3261  3261 D elm:15183: ElmAgentService : onDestroy().
,03-19 12:52:11.487  3307  3307 E Zygote  : MountEmulatedStorage()
03-19 12:52:11.487  3307  3307 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:11.487  3307  3307 E Zygote  : v2
03-19 12:52:11.487  3307  3307 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:11.487  1018  1747 E Tethering: No numeric data
,03-19 12:52:11.487  3307  3307 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:11.487  3298  3298 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-19 12:52:11.487  3307  3307 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:11.487  3298  3298 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:11.497  3307  3307 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-19 12:52:11.497  1018  3036 E Tethering: No numeric data
,03-19 12:52:11.497  1018  3036 E Tethering: No numeric data
,03-19 12:52:11.507  1018  1140 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3307 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 12:52:11.517  1018  1387 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-19 12:52:11.527  1018  1387 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:11.527  1018  1387 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:11.527  1018  1387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-19 12:52:11.527  1477  1477 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-19 12:52:11.527  1477  1477 I Telecom : InCallController: Unbinding from InCallService unbind
,03-19 12:52:11.537  3187  3254 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-19 12:52:11.537  3307  3307 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:11.537  3307  3307 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:11.537  1018  1730 I ActivityManager: Killing 2400:com.sec.android.omc/1000 (adj 15): empty #31
,03-19 12:52:11.557  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.557  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.557  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.557  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:11.567  3298  3298 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-19 12:52:11.567  3298  3298 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-19 12:52:11.577  3328  3328 E Zygote  : MountEmulatedStorage()
03-19 12:52:11.577  3328  3328 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:11.577  3328  3328 E Zygote  : v2
03-19 12:52:11.577  3328  3328 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:11.577  3328  3328 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-19 12:52:11.577  1018  1730 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3328 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 12:52:11.577  3328  3328 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:11.587  3328  3328 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:11.607  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.607  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.607  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:11.607  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:11.627  3005  3005 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-19 12:52:11.637  1018  1018 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3344 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-19 12:52:11.637  3344  3344 E Zygote  : MountEmulatedStorage(),
03-19 12:52:11.637  3344  3344 I libpersona: KNOX_SDCARD checking this for 10003,
03-19 12:52:11.637  3344  3344 E Zygote  : v2
03-19 12:52:11.637  3344  3344 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:11.637  3344  3344 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:11.637  3344  3344 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-19 12:52:11.637  3344  3344 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:11.647  3298  3298 I MultiDex: VM with version 2.1.0 has multidex support
03-19 12:52:11.647  3298  3298 I MultiDex: install
03-19 12:52:11.647  3298  3298 I MultiDex: VM has multidex support, MultiDex support library is disabled.
03-19 12:52:11.647   282   760 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-19 12:52:11.647   282   760 D audio_hw_extn: audio_extn_get_parameters: returns 
03-19 12:52:11.647   282   760 V msm8974_platform: platform_get_parameters: exit: returns - 
03-19 12:52:11.647   282   760 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-19 12:52:11.647   282   760 I str_params: key: 'call_forwarding' value: ''
03-19 12:52:11.647  1992  1992 V InCall  : ProximitySensor -  - screenonImmediately: false
03-19 12:52:11.647  1992  1992 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-19 12:52:11.647  1992  1992 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-19 12:52:11.667  1992  1992 D ScoverManager: serviceVersion : 16908288
03-19 12:52:11.667  1018  1730 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-19 12:52:11.667  1992  1992 D InCall  : InCallUtils - isCoverClosed false
,03-19 12:52:11.667  1018  1728 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-19 12:52:11.667  1992  1992 D InCall  : InCallUtils - isCoverClosed false
03-19 12:52:11.667  1992  1992 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-19 12:52:11.667  3328  3328 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:11.667  3328  3328 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:11.667  1477  1477 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-19 12:52:11.677  1992  1992 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-19 12:52:11.677  1992  1992 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-19 12:52:11.677  3187  3187 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected,
03-19 12:52:11.677  3187  3187 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-19 12:52:11.687  1992  1992 I InCall  : CallSContextMotion - stopPutDownListening
,03-19 12:52:11.687  1992  1992 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-19 12:52:11.687   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-19 12:52:11.717  1018  3036 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-19 12:52:11.717  1992  1992 D InCall  : InCallUtils - isCoverClosed false
,03-19 12:52:11.727  3298  3298 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-19 12:52:11.737  3344  3344 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:11.737  3344  3344 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:11.757  1200  1200 D PhoneStatusBarView: setCallBackground:0
,03-19 12:52:11.777  1018  1043 E libprocessgroup: failed to kill 1 processes for processgroup 2400
,03-19 12:52:11.797  1992  1992 D VideoCallManager: Instantiating VideoCallManager
,03-19 12:52:11.807  1992  1992 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-19 12:52:11.807  1992  1992 I GFX construct_block_size_descriptor_2d second part: took 3.144479ms for 0*0 texture 0
,03-19 12:52:11.817  1351  3179 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-19 12:52:11.817  1351  3179 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-19 12:52:11.817  1992  1992 I GFX generate_partition_tables: took 5.459479ms for 0*0 texture 0
,03-19 12:52:11.817  1992  1992 I GFX raster: took 12.430365ms for 176*144 texture 0
03-19 12:52:11.817  1992  1992 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb908a8e8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb908a1b8 counterpartCT=4 counterpartW=176 counterparth=144
,03-19 12:52:11.827  1992  1992 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-19 12:52:11.827  1992  1992 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-19 12:52:11.827  1992  1992 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-19 12:52:11.827  1992  1992 I Adreno-EGL: Build Date: 04/06/15 Mon
03-19 12:52:11.827  1992  1992 I Adreno-EGL: Local Branch: 
03-19 12:52:11.827  1992  1992 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-19 12:52:11.827  1992  1992 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-19 12:52:11.827  1992  1992 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-19 12:52:11.857  1992  1992 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS,
,03-19 12:52:11.857  3298  3298 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-19 12:52:11.857  3298  3298 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6b551f3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-19 12:52:11.857  3298  3298 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-19 12:52:11.867  1992  1992 I glCompressedTexImage2D: took 0.276458ms for 320*61440 texture 37809
,03-19 12:52:11.877  1992  1992 I draw setup: took 10.975158ms for 320*240 texture 37809
03-19 12:52:11.877  1992  1992 E GFX GPU raster: drawn
,03-19 12:52:11.877  1992  1992 I GFX GPU raster ASTC: took 44.443960ms for 320*240 texture 12
03-19 12:52:11.877  1992  1992 I GFX raster: took 44.537710ms for 320*240 texture 0
03-19 12:52:11.877  1992  1992 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb908a868 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb908a3d0 counterpartCT=4 counterpartW=320 counterparth=240
,03-19 12:52:11.877  1018  1393 E Tethering: No numeric data
,03-19 12:52:11.887  1018  1747 E Tethering: No numeric data
,03-19 12:52:11.897  1992  1992 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-19 12:52:11.897  3005  3235 D jxcore_app_log: JniHelper::setJavaVM(0xb8ce6450), pthread_self() = -1188784344
,03-19 12:52:11.897  1992  1992 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-19 12:52:11.897  1992  1992 I glCompressedTexImage2D: took 0.496094ms for 480*122880 texture 37813
03-19 12:52:11.897  1992  1992 I draw setup: took 1.072708ms for 480*640 texture 37813
,03-19 12:52:11.907  1992  1992 E GFX GPU raster: drawn
,03-19 12:52:11.907  1992  1992 I GFX GPU raster ASTC: took 8.966876ms for 480*640 texture 12
03-19 12:52:11.907  1992  1992 I GFX raster: took 9.073802ms for 480*640 texture 0
03-19 12:52:11.907  1992  1992 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb908a3d0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb92b7a80 counterpartCT=4 counterpartW=480 counterparth=640
,03-19 12:52:11.907  1018  1728 E Tethering: No numeric data
,03-19 12:52:11.917  3005  3235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-19 12:52:11.917  3005  3235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-19 12:52:11.917  3005  3235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-19 12:52:11.917  3005  3235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-19 12:52:11.917  3005  3235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-19 12:52:11.917  3005  3235 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f468c14 added. We now have 1 listener(s)
,03-19 12:52:11.927  3005  3235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:51:18:22
,03-19 12:52:11.927  3005  3235 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:51:18:22"
,03-19 12:52:11.927  3005  3235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-19 12:52:11.927  3005  3235 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-19 12:52:11.927  3005  3235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-19 12:52:11.927  3005  3235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-19 12:52:11.927  3005  3235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-19 12:52:11.927  3005  3235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:51:18:22
03-19 12:52:11.927  3005  3235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-19 12:52:11.927  3005  3235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-19 12:52:11.927  3005  3235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-19 12:52:11.927  3005  3235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-19 12:52:11.927  3005  3235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-19 12:52:11.927  3005  3235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-19 12:52:11.927  3005  3235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-19 12:52:11.927  3005  3235 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3887e203 added. We now have 1 listener(s)
,03-19 12:52:11.927  3005  3235 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-19 12:52:11.937  3020  3020 D BluetoothA2dp: Proxy object connected
,03-19 12:52:11.937  3005  3235 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-19 12:52:11.947  3005  3235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-19 12:52:11.947  3005  3235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-19 12:52:11.947  3005  3235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,03-19 12:52:11.947  3005  3235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-19 12:52:11.947  3005  3235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-19 12:52:11.947  1018  1392 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-19 12:52:11.947  1018  1392 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:11.947  3344  3344 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
03-19 12:52:11.947  3005  3235 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:51:18:22
,03-19 12:52:11.947  1018  1392 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-19 12:52:11.957  1018  1392 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-19 12:52:11.967  3005  3235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-19 12:52:11.967  3005  3235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-19 12:52:11.967  3005  3235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-19 12:52:11.967  3005  3235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-19 12:52:11.967  3005  3235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-19 12:52:11.967  3005  3235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-19 12:52:11.967  3005  3235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-19 12:52:11.967  3005  3235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-19 12:52:11.967  3005  3235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-19 12:52:11.967  3005  3235 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-19 12:52:11.967  3005  3235 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-19 12:52:11.967  3005  3005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-19 12:52:11.967  3005  3005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,03-19 12:52:11.987  1018  1387 I ActivityManager: Killing 2416:com.sec.modem.settings/1000 (adj 15): empty #31
,03-19 12:52:11.997  2034  2034 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,03-19 12:52:11.997  3005  3005 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-19 12:52:12.007  1200  1200 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 12:52:12.007  1200  1200 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-19 12:52:12.007  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:12.007  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:12.007  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:12.007  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 12:52:12.027  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.037  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.037  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.037  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.037  3187  3254 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-19 12:52:12.047  3307  3307 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-19 12:52:12.047  3344  3344 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-19 12:52:12.047  3307  3307 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-19 12:52:12.047  3344  3344 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-19 12:52:12.047  3344  3344 D UserAnalysis: Create SecureDbHelper
,03-19 12:52:12.057  3376  3376 E Zygote  : MountEmulatedStorage()
03-19 12:52:12.057  3376  3376 I libpersona: KNOX_SDCARD checking this for 10009
03-19 12:52:12.057  3376  3376 E Zygote  : v2
03-19 12:52:12.057  3376  3376 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:12.057  3376  3376 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:12.057  3376  3376 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:12.057  3376  3376 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-19 12:52:12.057  1018  1401 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3376 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:52:12.067  3307  3307 I DBG_POLICYDM: [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
,03-19 12:52:12.067  1992  1992 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-19 12:52:12.067  1992  1992 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-19 12:52:12.077  3187  3254 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-19 12:52:12.077  1992  1992 I glCompressedTexImage2D: took 0.332500ms for 440*116864 texture 37809
03-19 12:52:12.077  1992  1992 I draw setup: took 0.734270ms for 440*330 texture 37809
03-19 12:52:12.077  1992  1992 E GFX GPU raster: drawn
,03-19 12:52:12.087  1992  1992 I GFX GPU raster ASTC: took 7.106408ms for 440*330 texture 12
03-19 12:52:12.087  1992  1992 I GFX raster: took 7.187710ms for 440*330 texture 0
03-19 12:52:12.087  1992  1992 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb92bbcd8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb92bc098 counterpartCT=4 counterpartW=440 counterparth=330
,03-19 12:52:12.097  3376  3376 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:12.097  2735  2801 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-19 12:52:12.097  3187  3254 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-19 12:52:12.097  3187  3254 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-19 12:52:12.107  3376  3376 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:12.107  1992  1992 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-19 12:52:12.107  1992  1992 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-19 12:52:12.107  1992  1992 I glCompressedTexImage2D: took 0.456562ms for 480*163840 texture 37811
03-19 12:52:12.107  1992  1992 I draw setup: took 0.813073ms for 480*640 texture 37811
03-19 12:52:12.107  1992  1992 E GFX GPU raster: drawn
03-19 12:52:12.107  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2416/cgroup.procs: No such file or directory
,03-19 12:52:12.117  1992  1992 I GFX GPU raster ASTC: took 5.755156ms for 480*640 texture 12
03-19 12:52:12.117  1992  1992 I GFX raster: took 5.845573ms for 480*640 texture 0
03-19 12:52:12.117  1992  1992 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb92fb6a8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb92b7838 counterpartCT=4 counterpartW=480 counterparth=640
,03-19 12:52:12.117  1018  1730 E Tethering: No numeric data
,03-19 12:52:12.187  3344  3344 D IntelligenceServiceApplication: onCreate()
,03-19 12:52:12.187  3344  3344 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-19 12:52:12.197  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.197  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.197  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.197  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.197  3328  3328 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-19 12:52:12.197  3328  3328 I testFeature: Feature.Feature(context)
03-19 12:52:12.197  3328  3328 I testFeature: Feature.readInternalDefaultXml()
03-19 12:52:12.197  3328  3328 I testFeature: ResetFeatureValue
,03-19 12:52:12.197  3328  3328 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
,03-19 12:52:12.197  3328  3328 I CameraApp: CameraApp.getAppFeature()...
,03-19 12:52:12.207  3396  3396 E Zygote  : MountEmulatedStorage()
,03-19 12:52:12.207  3396  3396 E Zygote  : v2
03-19 12:52:12.207  3396  3396 I libpersona: KNOX_SDCARD checking this for 10060
03-19 12:52:12.207  3396  3396 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:12.207  3396  3396 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:12.207  3396  3396 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:12.217  3396  3396 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-19 12:52:12.217  1992  1992 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-19 12:52:12.217  1992  1992 I GFX construct_block_size_descriptor_2d second part: took 2.210937ms for 0*0 texture 0
03-19 12:52:12.217  1018  1392 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3396 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-19 12:52:12.217  1018  1392 I ActivityManager: Killing 2431:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,03-19 12:52:12.217  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.217  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.217  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.227  1018  1392 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.227  1992  1992 I GFX generate_partition_tables: took 7.598907ms for 0*0 texture 0
03-19 12:52:12.227  1992  1992 I GFX raster: took 11.819741ms for 176*144 texture 0
03-19 12:52:12.227  1992  1992 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb92bbc58 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb92b5298 counterpartCT=4 counterpartW=176 counterparth=144
,03-19 12:52:12.237  1992  1992 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144,
,03-19 12:52:12.237  1992  1992 I GFX construct_block_size_descriptor_2d second part: took 2.311093ms for 0*0 texture 0,
,03-19 12:52:12.247  3406  3406 E Zygote  : MountEmulatedStorage(),
03-19 12:52:12.247  3406  3406 I libpersona: KNOX_SDCARD checking this for 10100
03-19 12:52:12.247  3406  3406 E Zygote  : v2
03-19 12:52:12.247  3406  3406 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:12.247  3406  3406 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:12.247  3406  3406 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:12.247  3406  3406 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:12.247  1018  1392 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3406 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-19 12:52:12.247  3396  3396 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:12.247  3396  3396 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:12.257  1992  1992 I GFX generate_partition_tables: took 6.385053ms for 0*0 texture 0
03-19 12:52:12.257  1018  1392 I ActivityManager: Killing 2446:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
03-19 12:52:12.257  1992  1992 I GFX raster: took 10.910262ms for 176*144 texture 0
03-19 12:52:12.257  1992  1992 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb92b5300 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb92b5488 counterpartCT=4 counterpartW=176 counterparth=144
,03-19 12:52:12.257  1992  1992 D ScoverManager: registerListener
,03-19 12:52:12.267  1018  3034 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-19 12:52:12.267  1018  1140 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-19 12:52:12.267  1018  1140 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@a0a0098, pid : 1992, uid : 1001, type : 1
,03-19 12:52:12.277  1992  1992 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-19 12:52:12.287  3406  3406 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:12.287  3406  3406 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:12.317  3344  3344 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-19 12:52:12.337  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2431/cgroup.procs: No such file or directory
,03-19 12:52:12.337  1018  1043 W libprocessgroup: failed to open /acct/uid_10131/pid_2446/cgroup.procs: No such file or directory
,03-19 12:52:12.347  1018  1393 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-19 12:52:12.347  3344  3344 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-19 12:52:12.347  1018  1730 V VibratorService: hasVibrator - useVibetonz: true
,03-19 12:52:12.357  3406  3406 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-19 12:52:12.357  3406  3406 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-19 12:52:12.357  1018  1140 I ActivityManager: Killing 2509:com.wsomacp/u0a25 (adj 15): empty #31
,03-19 12:52:12.367  3278  3278 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-19 12:52:12.367  1018  3034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,03-19 12:52:12.367  1018  3034 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:12.367  1018  3034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-19 12:52:12.367  1018  3034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-19 12:52:12.377  1351  3179 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
03-19 12:52:12.377  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.377  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.377  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.377  1018  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.377  1731  3430 I GoogleHttpClient: GMS http client unavailable, use old client
03-19 12:52:12.377  1018  1392 V VibratorService: hasVibrator - useVibetonz: true
,03-19 12:52:12.387  3433  3433 E Zygote  : MountEmulatedStorage()
03-19 12:52:12.387  3433  3433 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:12.387  3433  3433 E Zygote  : v2
03-19 12:52:12.387  3433  3433 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:12.387  3433  3433 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:12.387  1018  1555 V VibratorService: hasVibrator - useVibetonz: true
03-19 12:52:12.387  3433  3433 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:12.387  1018  1730 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3433 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 12:52:12.397  3433  3433 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:12.417  3433  3433 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:12.417  3433  3433 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:12.427  1351  3179 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-19 12:52:12.427  1018  1043 W libprocessgroup: failed to open /acct/uid_10025/pid_2509/cgroup.procs: No such file or directory
,03-19 12:52:12.427  3344  3344 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-19 12:52:12.427  3344  3344 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-19 12:52:12.517  3396  3396 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-19 12:52:12.527  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.527  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.527  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.527  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.537  3458  3458 E Zygote  : MountEmulatedStorage()
,03-19 12:52:12.537  3458  3458 I libpersona: KNOX_SDCARD checking this for 10062
03-19 12:52:12.537  3458  3458 E Zygote  : v2
03-19 12:52:12.537  3458  3458 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:12.547  3458  3458 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:12.547  1351  3179 D ScoverManager: serviceVersion : 16908288
,03-19 12:52:12.547  3458  3458 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:12.547  3458  3458 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-19 12:52:12.547  1018  3034 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3458 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-19 12:52:12.557  1018  3034 I ActivityManager: Killing 2574:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,03-19 12:52:12.557  3307  3326 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO,
03-19 12:52:12.557  3307  3326 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-19 12:52:12.567  3307  3326 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true,
,03-19 12:52:12.567  3307  3327 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-19 12:52:12.567  3307  3327 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-19 12:52:12.577  3307  3327 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-19 12:52:12.577   308   308 I art     : Explicit concurrent mark sweep GC freed 8748(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 668us total 27.032ms
,03-19 12:52:12.597   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 666us total 17.666ms
,03-19 12:52:12.597  3307  3307 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-19 12:52:12.597  3307  3372 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-19 12:52:12.607  3458  3458 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:12.607  3458  3458 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:12.617   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 17.841ms
,03-19 12:52:12.617  3307  3372 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-19 12:52:12.617  3307  3307 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-19 12:52:12.627  3307  3307 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-19 12:52:12.627  3307  3307 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-19 12:52:12.627  3307  3307 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-19 12:52:12.637  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.637  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.637  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.637  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.647  3473  3473 E Zygote  : MountEmulatedStorage()
03-19 12:52:12.647  3473  3473 E Zygote  : v2
03-19 12:52:12.647  3473  3473 I libpersona: KNOX_SDCARD checking this for 1000
,03-19 12:52:12.647  3307  3307 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
03-19 12:52:12.657  3473  3473 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:12.647  3307  3307 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
03-19 12:52:12.657  1018  1387 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3473 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 12:52:12.657  1018  1387 I ActivityManager: Killing 2591:com.sec.android.app.camera/u0a139 (adj 15): empty #31
03-19 12:52:12.667  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.667  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.667  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.667  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.687  1018  1043 W libprocessgroup: failed to open /acct/uid_10142/pid_2574/cgroup.procs: No such file or directory
03-19 12:52:12.687  1018  1387 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3479 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 12:52:12.687  1018  1387 I ActivityManager: Killing 2628:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
03-19 12:52:12.657  3473  3473 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:12.687  1018  1387 I ActivityManager: Killing 2613:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #32
03-19 12:52:12.687  1018  1387 I ActivityManager: Killing 2353:com.sec.android.app.mt/1000 (adj 15): empty #33
,03-19 12:52:12.667  3307  3372 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
03-19 12:52:12.687  3479  3479 E Zygote  : MountEmulatedStorage()
03-19 12:52:12.717  3479  3479 E Zygote  : v2
03-19 12:52:12.717  3479  3479 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:12.717  3479  3479 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:12.717  3005  3368 W jxcore-log: Initializing JXcore engine
03-19 12:52:12.717  3005  3368 W jxcore-log: JXcore engine is ready
,03-19 12:52:12.717  3473  3473 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-19 12:52:12.727  3473  3473 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:12.727  3479  3479 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:12.727  3479  3479 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:12.737  3479  3479 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:12.757  3458  3458 I ExternalOEMControlProvider: onCreate
,03-19 12:52:12.787  1960  1960 E audit   : type=1400 msg=audit(1458388332.787:205): avc:  denied  { ioctl } for  pid=3368 comm="Thread-369" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-19 12:52:12.787  1960  1960 E audit   :  SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:12.787  1960  1960 E audit   : type=1300 msg=audit(1458388332.787:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=4 a3=9b12d8f8 items=0 ppid=308 ppcomm=main pid=3368 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-369" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-19 12:52:12.787  1960  1960 E audit   : type=1320 msg=audit(1458388332.787:205): 
,03-19 12:52:12.797  3479  3479 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:12.797  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.797  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.797  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:12.797  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:12.797  3479  3479 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:12.807  3473  3473 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:12.807  3473  3473 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:12.817  1018  1031 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3505 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 12:52:12.817  3005  3368 W jxcore-log: Starting JXcore engine
03-19 12:52:12.817  1018  1031 I ActivityManager: Killing 2494:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
03-19 12:52:12.817  3505  3505 E Zygote  : MountEmulatedStorage()
,03-19 12:52:12.817  3505  3505 E Zygote  : v2
03-19 12:52:12.817  3505  3505 I libpersona: KNOX_SDCARD checking this for 1000
,03-19 12:52:12.817  3505  3505 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:12.817  3505  3505 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-19 12:52:12.827  3505  3505 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-19 12:52:12.827  1018  1728 D SettingsProvider: name = PREVIOUS_SYS_TIME,
03-19 12:52:12.827  1018  1728 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 12:52:12.827  1018  1728 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
03-19 12:52:12.827  1018  1728 D SettingsProvider: selectionArgs: false
03-19 12:52:12.827  1018  1728 D SettingsProvider: selectionArgs: 10062,
03-19 12:52:12.827  1018  1728 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
,03-19 12:52:12.827  1018  1728 D SettingsProvider: ret = -1
03-19 12:52:12.837  3505  3505 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:12.847  1018  1728 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-19 12:52:12.847  1018  1401 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
,03-19 12:52:12.857  1018  2821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-19 12:52:12.857  1018  1401 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-19 12:52:12.857  1018  1401 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:12.857  1018  1401 D SettingsProvider: selectionArgs: false
03-19 12:52:12.857  1018  1401 D SettingsProvider: selectionArgs: 10062
03-19 12:52:12.857  1018  1401 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-19 12:52:12.857  1018  1401 D SettingsProvider: ret = -1
,03-19 12:52:12.867  1200  1200 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:12.877  1018  1401 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-19 12:52:12.897  1200  1200 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:12.907  3505  3505 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:12.907  3505  3505 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:12.917  3473  3473 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
,03-19 12:52:12.937  3505  3505 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-19 12:52:12.937  3307  3307 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-19 12:52:12.937  3307  3307 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-19 12:52:12.937  3307  3307 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-19 12:52:12.947  3473  3473 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-19 12:52:12.947  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2353/cgroup.procs: No such file or directory
03-19 12:52:12.947  1018  1043 W libprocessgroup: failed to open /acct/uid_10139/pid_2591/cgroup.procs: No such file or directory
03-19 12:52:12.947  1018  1043 W libprocessgroup: failed to open /acct/uid_10069/pid_2628/cgroup.procs: No such file or directory
,03-19 12:52:12.957  3307  3307 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-19 12:52:13.007  3005  3368 W jxcore-log: Platform android
03-19 12:52:13.007  3005  3368 W jxcore-log: 
,03-19 12:52:13.007  3005  3368 W jxcore-log: Process ARCH arm
03-19 12:52:13.007  3005  3368 W jxcore-log: 
,03-19 12:52:13.017  3473  3473 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-19 12:52:13.017  3473  3473 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
03-19 12:52:13.017  3473  3473 D ShortcutReceiver:  shortcut migration not required 
,03-19 12:52:13.017  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.017  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.017  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.017  1018  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.027  3307  3372 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-19 12:52:13.027  3307  3372 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-19 12:52:13.027  1200  1200 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 12:52:13.027  1200  1200 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-19 12:52:13.027  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:13.027  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:13.027  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:13.027  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:13.027  3479  3479 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-19 12:52:13.037  3532  3532 E Zygote  : MountEmulatedStorage(),
03-19 12:52:13.037  3532  3532 E Zygote  : v2
,03-19 12:52:13.037  3532  3532 I libpersona: KNOX_SDCARD checking this for 1000
,03-19 12:52:13.037  1018  1238 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3532 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-19 12:52:13.037  3532  3532 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:13.037  3532  3532 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:13.037  3505  3505 I ServiceMode: received = ACTION_BOOT_COMPLETED
,03-19 12:52:13.047  3505  3505 I ServiceMode: setReferenceIsDumpState : 0
,03-19 12:52:13.047  3532  3532 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:13.047  3307  3372 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-19 12:52:13.047  3532  3532 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.047  3307  3372 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-19 12:52:13.047  1018  1238 I ActivityManager: Killing 2693:com.android.calendar/u0a135 (adj 15): empty #31
,03-19 12:52:13.057  3278  3278 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-19 12:52:13.057  3307  3372 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-19 12:52:13.067  1018  1031 I ActivityManager: Killing 2750:com.android.keychain/1000 (adj 15): empty #31
,03-19 12:52:13.067  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.077  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.077  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.077  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.077  3479  3479 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
03-19 12:52:13.077  3479  3479 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-19 12:52:13.077  3479  3479 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-19 12:52:13.087  3307  3372 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString,
,03-19 12:52:13.087  3547  3547 E Zygote  : MountEmulatedStorage()
03-19 12:52:13.087  3547  3547 E Zygote  : v2
03-19 12:52:13.087  3547  3547 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:13.087  3547  3547 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:13.097  3547  3547 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:13.097  3547  3547 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:13.097  3547  3547 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.117  3307  3372 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-19 12:52:13.117  1018  1031 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3547 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 12:52:13.127  3307  3372 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-19 12:52:13.127  3307  3372 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-19 12:52:13.127  3307  3372 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-19 12:52:13.137  1018  1031 I ActivityManager: Killing 2848:com.android.email/u0a145 (adj 15): empty #31
,03-19 12:52:13.137  3187  3254 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-19 12:52:13.137  3307  3372 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/25/13:36:09
,03-19 12:52:13.137  3307  3372 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/19/12:52:13
,03-19 12:52:13.147  3547  3547 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:13.147  3547  3547 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.147  3307  3372 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-19 12:52:13.147  3307  3372 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-19 12:52:13.157  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.157  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.157  3532  3532 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:13.157  3532  3532 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.157  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.157  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.167  3563  3563 E Zygote  : MountEmulatedStorage(),
03-19 12:52:13.177  3563  3563 E Zygote  : v2
03-19 12:52:13.177  3563  3563 I libpersona: KNOX_SDCARD checking this for 1000
,03-19 12:52:13.177  3563  3563 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:13.177  1018  1401 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3563 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 12:52:13.177  3563  3563 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:13.177  3563  3563 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:13.177  3563  3563 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.217  3307  3373 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-19 12:52:13.217  3307  3372 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-19 12:52:13.217  3563  3563 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:13.227  3563  3563 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.227  3307  3373 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-19 12:52:13.247  1351  3179 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-19 12:52:13.247  3307  3373 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-19 12:52:13.257  3307  3373 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-19 12:52:13.257  3532  3532 E KnoxSetupWizardClient: isShipMode : 1
03-19 12:52:13.257  3532  3532 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-19 12:52:13.257  3307  3373 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-19 12:52:13.257  3307  3373 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-19 12:52:13.267  1351  3179 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-19 12:52:13.267  1018  1043 W libprocessgroup: failed to open /acct/uid_10068/pid_2613/cgroup.procs: No such file or directory
,03-19 12:52:13.267  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2494/cgroup.procs: No such file or directory
,03-19 12:52:13.277  3307  3373 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-19 12:52:13.277  3307  3373 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-19 12:52:13.277  3307  3373 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-19 12:52:13.277  3307  3373 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-19 12:52:13.287  1018  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.287  1018  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.287  1018  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.287  1018  1140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.297  1018  2879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 12:52:13.297  3563  3563 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-19 12:52:13.297  3563  3563 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-19 12:52:13.297  3563  3563 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-19 12:52:13.297  3581  3581 E Zygote  : MountEmulatedStorage()
03-19 12:52:13.297  3581  3581 E Zygote  : v2
03-19 12:52:13.297  3581  3581 I libpersona: KNOX_SDCARD checking this for 1000
,03-19 12:52:13.297  3581  3581 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:13.307  3581  3581 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:13.307  1018  1140 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3581 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 12:52:13.307  3581  3581 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:13.307  3581  3581 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:13.307  1018  1140 I ActivityManager: Killing 1191:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-19 12:52:13.317  3307  3373 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-19 12:52:13.337  3005  3368 I jxcore-log: JXcore Cordova bridge is ready!
03-19 12:52:13.337  3005  3368 I jxcore-log: 
,03-19 12:52:13.337  3005  3368 W jxcore-log: JXcore engine is started
,03-19 12:52:13.337  3547  3547 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-19 12:52:13.337  3307  3372 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
03-19 12:52:13.337  3581  3581 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:13.337  3581  3581 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.347  3547  3547 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-19 12:52:13.347  3005  3235 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-19 12:52:13.347  3563  3577 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-19 12:52:13.357  1018  1238 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-19 12:52:13.357  1018  1238 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:13.357  1018  1238 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-19 12:52:13.357  3005  3005 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-19 12:52:13.357  1018  1238 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-19 12:52:13.367  3547  3547 D NPS_WSSNPS: [] Service onCreate!!
,03-19 12:52:13.367  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.367  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.367  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.367  3005  3368 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-19 12:52:13.367  3005  3368 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
03-19 12:52:13.367  1018  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.387  3532  3578 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-19 12:52:13.387  3532  3578 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-19 12:52:13.387  3532  3578 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-19 12:52:13.387  3532  3578 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-19 12:52:13.387  3532  3578 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-19 12:52:13.387  3532  3578 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-19 12:52:13.387  3532  3578 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-19 12:52:13.387  3596  3596 E Zygote  : MountEmulatedStorage(),
03-19 12:52:13.387  3596  3596 E Zygote  : v2
03-19 12:52:13.387  3596  3596 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:13.387  3596  3596 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:13.387  3596  3596 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:13.397  3307  3373 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] ,
,03-19 12:52:13.397  3596  3596 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:13.397  3596  3596 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-19 12:52:13.397  1018  1401 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3596 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 12:52:13.407  1018  1387 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 12:52:13.407  1018  1387 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.407  1018  1387 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:13.407  1018  1387 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-19 12:52:13.407  3005  3005 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-19 12:52:13.407  3005  3005 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-19 12:52:13.417  3479  3479 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
03-19 12:52:13.417  3479  3479 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
03-19 12:52:13.427  3581  3581 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-19 12:52:13.427  3479  3479 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-19 12:52:13.427  1018  3036 D FocusedStackFrame: Set to : 0
,03-19 12:52:13.427  1018  3036 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-19 12:52:13.427  1018  3036 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-19 12:52:13.427  1018  3036 D InputDispatcher: Focused application set to: xxxx
03-19 12:52:13.427  1018  3036 D InputDispatcher: Focus left window: 3005
,03-19 12:52:13.427  3547  3547 D NPS_WSSNPS: [50.150321] smlDBHelper
,03-19 12:52:13.437  3581  3581 I StatusChecker: onReceive : net.mt.init : DONE
,03-19 12:52:13.437  3596  3596 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:13.437  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-19 12:52:13.437  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-19 12:52:13.437  3596  3596 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.437   256   447 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (269 us)
,03-19 12:52:13.457  3547  3607 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-19 12:52:13.477  3005  3005 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
03-19 12:52:13.477  3005  3235 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 60ms. Plugin should use CordovaInterface.getThreadPool().
,03-19 12:52:13.477  3005  3005 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,03-19 12:52:13.477  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.477  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.477  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.477  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.487  2677  3169 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3169)  
,03-19 12:52:13.497  3620  3620 E Zygote  : MountEmulatedStorage()
03-19 12:52:13.497  3620  3620 E Zygote  : v2
03-19 12:52:13.497  3620  3620 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:13.497  3620  3620 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:13.497  3620  3620 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:13.507  3620  3620 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-19 12:52:13.507  3620  3620 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.507  1018  3034 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3620 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-19 12:52:13.507  1018  3034 I ActivityManager: Killing 2544:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,03-19 12:52:13.517  1018  1730 I art     : Explicit concurrent mark sweep GC freed 19299(1026KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 30MB/45MB, paused 2.784ms total 166.405ms
,03-19 12:52:13.527  1018  1387 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-19 12:52:13.527  1018  1387 W ActivityManager: mDVFSHelper.acquire()
,03-19 12:52:13.527  3307  3372 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-19 12:52:13.527  3278  3278 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-19 12:52:13.527  1018  1387 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-19 12:52:13.527  1018  1387 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-19 12:52:13.527  1018  1387 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-19 12:52:13.537  3278  3278 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-19 12:52:13.547  3620  3620 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:13.547  3620  3620 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.557  1530  1530 D Launcher: onRestart, Launcher: 71208698
,03-19 12:52:13.557  1018  3036 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.557  1018  3036 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.557  1018  3036 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.557  1018  3036 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.567  3636  3636 E Zygote  : MountEmulatedStorage()
03-19 12:52:13.567  3636  3636 E Zygote  : v2
03-19 12:52:13.567  3636  3636 I libpersona: KNOX_SDCARD checking this for 10116
03-19 12:52:13.567  3636  3636 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:13.567  3636  3636 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:13.577  3636  3636 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-19 12:52:13.577  3636  3636 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.577  1018  3036 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3636 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,03-19 12:52:13.577  1018  3036 I ActivityManager: Killing 2896:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-19 12:52:13.577  1530  1530 D Launcher: onStart, Launcher: 71208698
03-19 12:52:13.577  1530  1530 D Launcher.HomeView: onStart
03-19 12:52:13.577  1530  1530 D Launcher: onResume, Launcher: 71208698
,03-19 12:52:13.587  1018  1140 D SettingsProvider: name = kids_home_mode
,03-19 12:52:13.587  1018  1140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-19 12:52:13.587  1018  1140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:13.587  1018  1140 D SettingsProvider: selectionArgs: false
03-19 12:52:13.587  1018  1140 D SettingsProvider: selectionArgs: 10007
03-19 12:52:13.587  1018  1140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
,03-19 12:52:13.587  1018  1140 D SettingsProvider: ret = -1,
03-19 12:52:13.587  1530  1530 D Launcher.HomeView: onResume
,03-19 12:52:13.597  3636  3636 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-19 12:52:13.597  3636  3636 D ActivityThread: Added TimaKeyStore provider
03-19 12:52:13.607  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-19 12:52:13.607  1018  1018 D SensorService: [SO] activate (ident=0xb94c9a60, enabled=0)
03-19 12:52:13.607  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-19 12:52:13.607  1530  1530 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-19 12:52:13.607  3547  3547 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-19 12:52:13.607  1018  1018 D SensorManager: unregisterListener ::   
,03-19 12:52:13.607  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-19 12:52:13.607  1018  1018 D SensorService: [SO] changed settle time [0]
03-19 12:52:13.607  1018  1018 D SensorService: [SO] setDelay [200000000]
03-19 12:52:13.607  1018  1018 D SensorService: [SO] activate (ident=0xb94c9a60, enabled=1)
03-19 12:52:13.607  1018  1018 D SensorService: [SO] AR_init
03-19 12:52:13.607  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-19 12:52:13.617  1018  1555 I ActivityManager: Killing 2285:flipboard.app/u0a98 (adj 15): empty #31
,03-19 12:52:13.617  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  ,
,03-19 12:52:13.637  1018  1747 D SettingsProvider: name = access_control_enabled
,03-19 12:52:13.637  3547  3654 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-19 12:52:13.637  3547  3654 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
03-19 12:52:13.637  3547  3654 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-19 12:52:13.657  1530  1530 D MenuAppsGridFragment: onResume
,03-19 12:52:13.657  1018  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.657  1018  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.657  1018  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.657  1018  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.657  3307  3373 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-19 12:52:13.677   287   287 E SMD     : DCD OFF,
,03-19 12:52:13.677  3655  3655 E Zygote  : MountEmulatedStorage(),
03-19 12:52:13.677  3655  3655 E Zygote  : v2
03-19 12:52:13.687  3655  3655 I libpersona: KNOX_SDCARD checking this for 10069
03-19 12:52:13.687  3655  3655 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:13.687  3655  3655 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:13.687  3655  3655 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-19 12:52:13.687  3655  3655 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.707   308   308 I art     : Explicit concurrent mark sweep GC freed 8817(375KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.040ms total 27.057ms
,03-19 12:52:13.707  3655  3655 D TimaKeyStoreProvider: TimaSignature is unavailable
03-19 12:52:13.717  3655  3655 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.717  3307  3373 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-19 12:52:13.727  3636  3636 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
03-19 12:52:13.727   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 18.576ms
,03-19 12:52:13.737  3307  3373 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-19 12:52:13.737  1018  1555 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3655 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-19 12:52:13.737  1018  1555 I ActivityManager: Killing 2940:com.sec.usbsettings/1000 (adj 15): empty #31
,03-19 12:52:13.737  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-19 12:52:13.737  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.737  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:13.737  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-19 12:52:13.737  3636  3636 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-19 12:52:13.747  3547  3547 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-19 12:52:13.747   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 19.265ms
,03-19 12:52:13.747  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2750/cgroup.procs: No such file or directory
03-19 12:52:13.747  1018  1043 W libprocessgroup: failed to open /acct/uid_10135/pid_2693/cgroup.procs: No such file or directory
03-19 12:52:13.747  1018  1043 W libprocessgroup: failed to open /acct/uid_10145/pid_2848/cgroup.procs: No such file or directory
03-19 12:52:13.747  1018  1043 W libprocessgroup: failed to open /acct/uid_10004/pid_1191/cgroup.procs: No such file or directory
,03-19 12:52:13.747  1018  1043 W libprocessgroup: failed to open /acct/uid_10044/pid_2544/cgroup.procs: No such file or directory
,03-19 12:52:13.757  1018  1728 D ActivityManager: handle home activity for 0
03-19 12:52:13.757  1018  1728 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-19 12:52:13.757  1018  1728 D KnoxTimeoutHandler: post home show event for user 0
03-19 12:52:13.757  1018  1728 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-19 12:52:13.757  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-19 12:52:13.757  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-19 12:52:13.757  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-19 12:52:13.757  1018  1728 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-19 12:52:13.757  1018  1728 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-19 12:52:13.757  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-19 12:52:13.757  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 12:52:13.757  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.757   256   256 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-19 12:52:13.757  3620  3620 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-19 12:52:13.757  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:13.757  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-19 12:52:13.757  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-19 12:52:13.757  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-19 12:52:13.767  3620  3620 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-19 12:52:13.767  1018  1238 D InputDispatcher: Focus entered window: 1530
,03-19 12:52:13.767  3636  3636 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
03-19 12:52:13.767  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-19 12:52:13.767  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-19 12:52:13.767  1530  1530 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-19 12:52:13.777  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.777  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.777  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:13.777  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:13.787  1530  1530 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-19 12:52:13.787  1018  3034 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-19 12:52:13.797  3547  3547 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-19 12:52:13.797  3547  3547 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-19 12:52:13.797  3547  3547 I NPS_WSSNPS: [50.150321] smlBREmailDelete
,03-19 12:52:13.797  3547  3547 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
03-19 12:52:13.797  3547  3547 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
03-19 12:52:13.797  3547  3547 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
,03-19 12:52:13.797  3547  3547 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
03-19 12:52:13.797  3547  3547 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
03-19 12:52:13.797  3547  3547 I NPS_WSSNPS: [50.150321] cpuBooster release : false
03-19 12:52:13.797  3673  3673 E Zygote  : MountEmulatedStorage()
03-19 12:52:13.797  3673  3673 I libpersona: KNOX_SDCARD checking this for 10125
03-19 12:52:13.797  3673  3673 E Zygote  : v2
03-19 12:52:13.797  3673  3673 I libpersona: KNOX_SDCARD not a persona
03-19 12:52:13.797  3673  3673 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:13.797  1018  3672 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
03-19 12:52:13.797  3005  3005 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-19 12:52:13.807  3673  3673 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:13.807  3673  3673 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:13.807  1200  1200 D PanelView: There is/are notification(s) 
,03-19 12:52:13.807  1828  1828 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-19 12:52:13.817  1018  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-19 12:52:13.817  1018  1387 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3673 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,03-19 12:52:13.817  1018  1043 W libprocessgroup: failed to open /acct/uid_10099/pid_2896/cgroup.procs: No such file or directory
03-19 12:52:13.817  1018  1043 W libprocessgroup: failed to open /acct/uid_10098/pid_2285/cgroup.procs: No such file or directory
,03-19 12:52:13.817  3655  3655 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-19 12:52:13.827  3563  3577 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-19 12:52:13.837  1530  1530 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2a98a142 time:40270
,03-19 12:52:13.837  3547  3547 D NPS_WSSNPS: [50.150321] dsServerSocket close
03-19 12:52:13.837  1018  1050 D PersonaManager: isKioskContainerExistOnDevice
,03-19 12:52:13.837  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2940/cgroup.procs: No such file or directory
,03-19 12:52:13.857  1018  1050 I ActivityManager: Displayed Component not be shown by security: +323ms
,03-19 12:52:13.857  3618  3618 D AndroidRuntime: 
03-19 12:52:13.857  3618  3618 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-19 12:52:13.857  3673  3673 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:13.857  3673  3673 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:13.857  3618  3618 D AndroidRuntime: CheckJNI is OFF
03-19 12:52:13.857  3618  3618 D AndroidRuntime: readGMSProperty: start
03-19 12:52:13.857  3618  3618 D AndroidRuntime: readGMSProperty: already setted!!,
03-19 12:52:13.857  3618  3618 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-19 12:52:13.857  3618  3618 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-19 12:52:13.857  3618  3618 D AndroidRuntime: readGMSProperty: end,
03-19 12:52:13.857  3618  3618 D AndroidRuntime: addProductProperty: start
,03-19 12:52:13.867  3620  3620 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-19 12:52:13.887  1018  1401 V VibratorService: hasVibrator - useVibetonz: true
,03-19 12:52:13.897  3278  3451 D Volley  : [406] DiskBasedCache.clear: Cache cleared.
,03-19 12:52:13.897  3278  3524 D Volley  : [413] DiskBasedCache.clear: Cache cleared.
,03-19 12:52:13.907  3620  3620 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-19 12:52:13.917  1018  1728 I ActivityManager: Killing 1605:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-19 12:52:13.917  3673  3673 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:52:13.917  3673  3673 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-19 12:52:13.917  3673  3673 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-19 12:52:13.927  1018  1393 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-19 12:52:13.927  1018  1393 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.927  1018  1393 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:13.927  1018  1393 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:52:13.937  1731  1731 V GLSUser : [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,03-19 12:52:13.937  1018  1555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
03-19 12:52:13.947  1018  1555 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.947  1018  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:13.947  1018  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:52:13.947  1018  1140 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,03-19 12:52:13.947  1018  1140 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.947  1018  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:13.947  1018  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-19 12:52:13.957  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 12:52:13.967  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.967  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:13.967  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-19 12:52:13.997  2034  2034 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,03-19 12:52:13.997  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-19 12:52:13.997  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:13.997  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:13.997  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:14.017  1018  1041 D SensorService: [SO] currT = 40451095000, prevT = 39991085000, diff = 460010000, [0.172 0.421 10.247]
03-19 12:52:14.017  1018  1041 D SensorService: [SO] 0.172 0.421 10.247
03-19 12:52:14.017  1018  1041 D SensorService: [SO] [100 -> 255]
,03-19 12:52:14.017  1200  1200 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 12:52:14.017  1200  1200 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-19 12:52:14.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 12:52:14.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:14.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:14.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 12:52:14.027  3278  3278 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-19 12:52:14.027  3278  3278 D Finsky  : [1] 2.run: Finished loading 1 libraries.
03-19 12:52:14.027  1018  1044 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-19 12:52:14.027  1018  1044 W ActivityManager: mDVFSHelper.release()
03-19 12:52:14.027  1018  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-19 12:52:14.027  1018  1043 W libprocessgroup: failed to open /acct/uid_10072/pid_1605/cgroup.procs: No such file or directory
03-19 12:52:14.027  3618  3618 E AffinityControl: AffinityControl: registerfunction enter
,03-19 12:52:14.047  3278  3278 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-19 12:52:14.047  1018  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 12:52:14.047  1018  1555 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.047  1018  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:14.047  1018  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:52:14.057  3618  3618 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-19 12:52:14.067  1018  1730 D PackageManager: START PACKAGE DELETE: observer{557957672}
03-19 12:52:14.067  1018  1730 D PackageManager: pkg{<packageName>}
03-19 12:52:14.067  1018  1730 D PackageManager: user{0}
03-19 12:52:14.067  1018  1730 D PackageManager: caller{2000}
03-19 12:52:14.067  1018  1730 D PackageManager: flags{2}
03-19 12:52:14.067  1018  1730 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-19 12:52:14.067  1018  1730 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-19 12:52:14.067  1018  1730 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-19 12:52:14.067  1018  1730 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-19 12:52:14.067  1018  1730 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-19 12:52:14.077  1018  1059 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-19 12:52:14.077  1731  1731 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-19 12:52:14.077  1018  1747 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,03-19 12:52:14.077  1018  1747 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.077  1018  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-19 12:52:14.077  1018  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,03-19 12:52:14.077  1018  1059 D ApplicationPolicy: getApplicationUninstallationEnabled
03-19 12:52:14.077  1018  1747 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:14.077  1018  1747 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
03-19 12:52:14.087  1018  1059 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-19 12:52:14.087  3620  3620 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-19 12:52:14.087  1018  1059 D PackageManager: !@killApplicatoin: 10174, uninstall pkg
,03-19 12:52:14.087  1018  1044 I ActivityManager: Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
,03-19 12:52:14.087  1018  1044 I ActivityManager: Killing 3005:com.test.thalitest/u0a174 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-19 12:52:14.107  1018  1140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 12:52:14.107  1018  1140 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.107  1018  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:14.107  1018  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:14.127  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-19 12:52:14.127  1018  1018 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
03-19 12:52:14.127  1018  1018 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 12:52:14.137  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.137  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.137  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.137  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.137  3620  3620 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-19 12:52:14.137  3620  3620 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=,
,03-19 12:52:14.137  3187  3254 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec,
,03-19 12:52:14.147  3620  3620 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-19 12:52:14.157  3620  3620 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-19 12:52:14.157  3714  3714 E Zygote  : MountEmulatedStorage()
03-19 12:52:14.157  3714  3714 E Zygote  : v2
,03-19 12:52:14.157  3714  3714 I libpersona: KNOX_SDCARD checking this for 1000,
03-19 12:52:14.157  3714  3714 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:14.157  3714  3714 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:14.157  3673  3673 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-19 12:52:14.157  3673  3673 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-19 12:52:14.157  3620  3620 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
03-19 12:52:14.157  3620  3620 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
03-19 12:52:14.157  3714  3714 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:14.157  3714  3714 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-19 12:52:14.157  1018  1018 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3714 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-19 12:52:14.167  1018  1747 I WindowState: WIN DEATH: Window{18f102db u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
,03-19 12:52:14.197  3714  3714 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:14.197  3714  3714 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:14.257   256   442 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-19 12:52:14.257   256  1847 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-19 12:52:14.267  1018  1059 W PackageSettings: Skipping PackageSetting{761c35c com.example.hello/10175} due to missing metadata
,03-19 12:52:14.267   256   447 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-19 12:52:14.287  1018  1031 D SettingsProvider: name = scon_is_running
03-19 12:52:14.287  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-19 12:52:14.287  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-19 12:52:14.287  1018  1031 D SettingsProvider: selectionArgs: false
03-19 12:52:14.287  1018  1031 D SettingsProvider: selectionArgs: 10125
03-19 12:52:14.287  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-19 12:52:14.287  1018  1031 D SettingsProvider: ret = -1
,03-19 12:52:14.287  3278  3278 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-19 12:52:14.297  1018  1031 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,03-19 12:52:14.297  1018  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14fcc093 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t235} time:40735
,03-19 12:52:14.307  1200  1200 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-19 12:52:14.307  3673  3673 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-19 12:52:14.307  1018  1059 I ActivityManager: Force stopping com.test.thalitest appid=10174 user=0: pkg removed
,03-19 12:52:14.317  3376  3376 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-19 12:52:14.317  3673  3673 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-19 12:52:14.327  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-19 12:52:14.337  1018  1059 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-19 12:52:14.347  1351  3179 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-19 12:52:14.377  1828  1828 E SamsungIME: mOCRHelper is null
,03-19 12:52:14.377  1655  2141 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-19 12:52:14.387  1018  1129 V NetworkStats: removeUidsLocked() for UIDs [10174]
03-19 12:52:14.387  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
03-19 12:52:14.387  1018  1129 V NetworkStats: performPollLocked(flags=0x3)
,03-19 12:52:14.387  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
03-19 12:52:14.387  1018  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-19 12:52:14.397  1501  1501 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-19 12:52:14.397  1018  1129 V NetworkStats: performPollLocked() took 4ms
03-19 12:52:14.397  1018  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,03-19 12:52:14.447  1018  1104 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-19 12:52:14.457  1018  1140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-19 12:52:14.467  1018  1140 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:14.467  1018  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-19 12:52:14.467  1018  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:14.467  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
03-19 12:52:14.467  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-19 12:52:14.477  1018  1387 I ActivityManager: Killing 2383:com.android.mms/u0a46 (adj 15): empty #31
,03-19 12:52:14.477  1484  1484 D RegisteredComponentCache: Collect Tech packages for Knox
,03-19 12:52:14.497  3714  3714 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-19 12:52:14.497  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.497  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.497  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.497  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.507  3735  3735 E Zygote  : MountEmulatedStorage()
,03-19 12:52:14.517  3735  3735 E Zygote  : v2
03-19 12:52:14.517  3735  3735 I libpersona: KNOX_SDCARD checking this for 10131
03-19 12:52:14.517  3735  3735 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:14.517  3735  3735 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:14.517  3735  3735 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:14.517  3735  3735 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:14.527  1018  1387 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3735 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-19 12:52:14.527  1018  1387 I ActivityManager: Killing 3050:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,03-19 12:52:14.537  1018  1387 I ActivityManager: Killing 2919:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,03-19 12:52:14.537  1018  1393 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-19 12:52:14.537  1018  1393 D SecContentProvider2: mCursor = null
,03-19 12:52:14.537  1018  1730 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,03-19 12:52:14.547  1018  1730 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:14.547  1018  1730 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 12:52:14.547  1018  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-19 12:52:14.547  1018  1728 D CountryDetector: No listener is left
,03-19 12:52:14.557  3735  3735 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:14.557  3735  3735 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:14.577  1484  1484 D PersonaManager: isKioskContainerExistOnDevice
,03-19 12:52:14.587  1018  1059 I art     : Explicit concurrent mark sweep GC freed 26512(1783KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 30MB/45MB, paused 3.481ms total 238.707ms
,03-19 12:52:14.587  3376  3376 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-19 12:52:14.597  1018  1059 D PackageManager: delete codoeFile: 
,03-19 12:52:14.607  1018  1059 D AASAuninstall: userId = 0, info.removedAppID = 10174, info.uid = 10174, packageName = com.test.thalitest
03-19 12:52:14.607  1018  1059 I AASA_removePackage: UID=10174 Target=com.test.thalitest
,03-19 12:52:14.607  1018  1059 D PackageManager: result of delete: 1{557957672}
,03-19 12:52:14.617  3618  3618 D AndroidRuntime: Shutting down VM,
,03-19 12:52:14.637  1018  1059 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-19 12:52:14.637  1018  1059 D PackageManager: userId{-1}
03-19 12:52:14.637  1018  1059 D PackageManager: andCode{true}
,03-19 12:52:14.647  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,03-19 12:52:14.647  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-19 12:52:14.647  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-19 12:52:14.647  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,03-19 12:52:14.647  1018  1018 D OTPFW   : OtpDbHelper::getInstance New instance created
,03-19 12:52:14.647  1018  1018 D OTPFW   : DBIntegrity::getInstance - New instance created
,03-19 12:52:14.647  1018  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
,03-19 12:52:14.647  1018  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-19 12:52:14.647  1018  1043 W TextServicesManagerService: no available spell checker services found
,03-19 12:52:14.657  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
,03-19 12:52:14.657  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,03-19 12:52:14.657  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-19 12:52:14.657  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-19 12:52:14.657  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-19 12:52:14.667  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-19 12:52:14.667  1018  1018 V EnterpriseBillingPolicy: uID is 10174
03-19 12:52:14.667  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
03-19 12:52:14.667  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-19 12:52:14.667  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-19 12:52:14.667  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-19 12:52:14.667  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-19 12:52:14.667  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-19 12:52:14.667  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-19 12:52:14.667  1018  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,03-19 12:52:14.667  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:14.677  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:14.677  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.677  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.677  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.677  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.677  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:14.677  3735  3735 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-19 12:52:14.677  3735  3735 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-19 12:52:14.677  3735  3735 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-19 12:52:14.677  3735  3735 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-19 12:52:14.687  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:14.687  3753  3753 E Zygote  : MountEmulatedStorage()
03-19 12:52:14.687  3753  3753 I libpersona: KNOX_SDCARD checking this for 10004
03-19 12:52:14.687  3753  3753 E Zygote  : v2
03-19 12:52:14.687  3753  3753 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:14.697  3753  3753 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:14.697  3753  3753 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:14.697  3753  3753 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:14.697  1018  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=3753 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a,
,03-19 12:52:14.707  1484  1484 D PersonaManager: isKioskContainerExistOnDevice
,03-19 12:52:14.707  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.707  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.707  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.707  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.717  3753  3753 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:14.717  3753  3753 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:14.727  3763  3763 E Zygote  : MountEmulatedStorage()
03-19 12:52:14.727  3763  3763 E Zygote  : v2
03-19 12:52:14.727  3763  3763 I libpersona: KNOX_SDCARD checking this for 1000
03-19 12:52:14.727  3763  3763 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:14.737  1018  1387 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3763 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-19 12:52:14.737  3763  3763 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-19 12:52:14.737  1351  3179 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-19 12:52:14.747  3763  3763 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:14.747  3763  3763 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-19 12:52:14.747  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-19 12:52:14.747  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-19 12:52:14.747  1018  2821 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
03-19 12:52:14.747  1018  1018 V EnterpriseBillingPolicy: uID is 10174
03-19 12:52:14.747  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
03-19 12:52:14.747  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-19 12:52:14.757  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.757  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.757  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:14.757  1018  1387 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-19 12:52:14.757  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-19 12:52:14.757  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-19 12:52:14.757  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-19 12:52:14.757  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-19 12:52:14.757  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-19 12:52:14.777  3778  3778 E Zygote  : MountEmulatedStorage()
03-19 12:52:14.777  3778  3778 E Zygote  : v2
03-19 12:52:14.777  3778  3778 I libpersona: KNOX_SDCARD checking this for 10014,
03-19 12:52:14.777  3778  3778 I libpersona: KNOX_SDCARD not a persona
,03-19 12:52:14.777  3778  3778 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-19 12:52:14.777  1018  1387 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3778 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,03-19 12:52:14.787  1018  1387 I ActivityManager: Killing 2735:com.google.android.apps.books/u0a75 (adj 15): empty #31
,03-19 12:52:14.787  3778  3778 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-19 12:52:14.787  3778  3778 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-19 12:52:14.787  1484  1484 D RegisteredServicesCache: empty dynamic service
,03-19 12:52:14.797  3735  3735 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-19 12:52:14.817  1351  3179 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-19 12:52:14.817  3735  3735 D ManifestProvider: onCreate()
,03-19 12:52:14.827  3618  3618 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-19 12:52:14.837  3763  3763 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:14.837  3763  3763 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:14.847  3778  3778 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-19 12:52:14.847  3778  3778 D ActivityThread: Added TimaKeyStore provider
,03-19 12:52:14.857  3278  3278 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-19 12:52:14.867  1351  3179 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-19 12:52:14.897  1018  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-19 12:52:14.897  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:14.897  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:14.907  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:14.907  1018  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-19 12:52:14.907  1018  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:52:14.907  1018  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-19 12:52:14.907  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:14.917  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-19 12:52:14.917  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:14.927  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
03-19 12:52:14.927  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-19 12:52:14.927  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,03-19 12:52:14.927  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-19 12:52:14.927  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-19 12:52:14.937  1018  1555 I ActivityManager: Killing 2156:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,03-19 12:52:14.937  3735  3735 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-19 12:52:14.957  3763  3763 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-19 12:52:14.967  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-19 12:52:14.967  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-19 12:52:14.967  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-19 12:52:14.967  1018  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-19 12:52:14.967  1018  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-19 12:52:14.987  1018  1043 W libprocessgroup: failed to open /acct/uid_10046/pid_2383/cgroup.procs: No such file or directory
,03-19 12:52:15.007  3735  3735 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@43e8efa
,03-19 12:52:15.007  3735  3735 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
03-19 12:52:15.007  3735  3735 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-19 12:52:15.007  1018  1171 W System.err: java.io.IOException: write failed: EBADF (Bad file number)
,03-19 12:52:15.007  1018  1171 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:502)
03-19 12:52:15.007  1018  1171 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
03-19 12:52:15.007  1018  1171 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
03-19 12:52:15.007  1018  1171 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1157)
03-19 12:52:15.007  1018  1171 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:539)
03-19 12:52:15.007  1018  1171 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file number)
03-19 12:52:15.007  1018  1171 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
03-19 12:52:15.007  1018  1171 W System.err: 	at libcore.io.Posix.write(Posix.java:223)
03-19 12:52:15.007  1018  1171 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
03-19 12:52:15.007  1018  1171 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:497)
03-19 12:52:15.007  1018  1171 W System.err: 	... 4 more
03-19 12:52:15.007  1018  1171 D skia    : ------- write threw an exception
,03-19 12:52:15.007  1018  1171 D TaskPersister: removeObsoleteFile: deleting file=236_task.xml
,03-19 12:52:15.007  1018  1171 D TaskPersister: removeObsoleteFile: deleting file=236_task_thumbnail.png
,03-19 12:52:15.017  1200  1200 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 12:52:15.017  1200  1200 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-19 12:52:15.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 12:52:15.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:15.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 12:52:15.017  1200  1200 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 12:52:15.027  1018  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:15.027  1018  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:15.027  1018  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-19 12:52:15.027  1018  1747 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
