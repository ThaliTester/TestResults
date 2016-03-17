#### Test 63186632d456b18_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
03-17 09:49:30.190  1016  1016 W PhoneRestrictionPolicy: Message received - msg { when=-5ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
--------- beginning of system
03-17 09:49:30.190  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-17 09:49:30.190  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 09:49:30.190  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 09:49:30.190  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-17 09:49:30.200  2693  2693 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 09:49:30.200  2693  2776 D HeadsetStateMachine: Disconnected process message: 10
03-17 09:49:30.200  1016  1016 D KnoxMUMContainerPolicy: mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
03-17 09:49:30.200   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 18.708ms
03-17 09:49:30.200  1016  1016 I KnoxMUMContainerPolicy: MSG_REMOVE_ORPHANED_CONTAINERS received
03-17 09:49:30.200  1016  1077 I ActivityManager: Killing 1622:com.google.android.apps.maps/u0a107 (adj 15): empty #31
03-17 09:49:30.210  2873  2873 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:30.210  2873  2873 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:30.210  1016  1130 D WifiP2pService: InactiveState{ what=143415 }
03-17 09:49:30.210  1016  1130 D WifiP2pService: P2pEnabledState{ what=143415 }
03-17 09:49:30.210  1016  1130 D WifiP2pService: DefaultState{ what=143415 }
03-17 09:49:30.210  1016  1133 D ConnectivityService: Got NetworkFactory Messenger for WIFI_P2P
03-17 09:49:30.210  1016  1133 D ConnectivityService: Got NetworkFactory Messenger for WIFI
03-17 09:49:30.220  1016  1130 D WIFI_P2P: got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-17 09:49:30.220  1016  1131 D WIFI    : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-17 09:49:30.220  1016  1130 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
03-17 09:49:30.220  1016  1131 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
03-17 09:49:30.220  1016  1131 E WifiStateMachine: Blacklist file delete
03-17 09:49:30.220   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 21.591ms
03-17 09:49:30.230  1016  2891 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
03-17 09:49:30.240  1016  2891 W PhoneRestrictionPolicy: cvList size 0
03-17 09:49:30.240  1016  2891 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
03-17 09:49:30.240  1016  2891 W PhoneRestrictionPolicy: cvList size 0
03-17 09:49:30.240  1016  1016 D Tethering: Boot complete.
03-17 09:49:30.240  1016  1016 V EnterpriseBillingEngine: ACTION_BOOT_COMPLETED
03-17 09:49:30.240  1016  1016 V EnterpriseBillingEngine: handleAllprofiles - start
03-17 09:49:30.240  1016  1016 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - start - 
03-17 09:49:30.240   255   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
03-17 09:49:30.240   255   534 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 09:49:30.250  2084  2883 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
03-17 09:49:30.250  1016  1016 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - end - null
03-17 09:49:30.250  1016  1016 V EnterpriseBillingEngine: handleAllprofiles - end
03-17 09:49:30.250  1016  1016 D UsbHostNotification: boot completed
03-17 09:49:30.260  1016  1016 D UsbHostRestrictor: mBootCompletedReceiver onReceive
03-17 09:49:30.260  1016  1016 D UsbHostRestrictor: initSetUsbBlock STARTED
03-17 09:49:30.260  2873  2873 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 09:49:30.280  1016  1016 D UsbHostRestrictor: SIM was never inserted
03-17 09:49:30.280  1016  1016 D UsbHostRestrictor: writableHostSysNode[false]
03-17 09:49:30.280  1016  1016 D UsbHostRestrictor: Can NOT Write Disable Sys Node to [ON]
,03-17 09:49:30.300  2897  2897 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab 
03-17 09:49:30.310  2900  2900 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
03-17 09:49:30.320  1016  1038 D SensorService: [SO] currT = 35780077642, prevT = 35300074048, diff = 480003594, [0.134 0.421 10.113]
03-17 09:49:30.320  1016  1038 D SensorService: [SO] 0.134 0.421 10.113
03-17 09:49:30.320  1016  1038 D SensorService: [SO] [100 -> 255]
03-17 09:49:30.330  2693  2764 I bt_vendor: bluetooth satus is on
03-17 09:49:30.330  2693  2843 D bt_userial_mct: userial_open(port:0)
03-17 09:49:30.330  2693  2843 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
03-17 09:49:30.330  1016  1040 W libprocessgroup: failed to open /acct/uid_10107/pid_1622/cgroup.procs: No such file or directory
03-17 09:49:30.340  2693  2843 I bt_vendor: Done intiailizing UART
03-17 09:49:30.340  2693  2843 I bt_vendor: Done intiailizing UART
03-17 09:49:30.340  2693  2843 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
03-17 09:49:30.340  2693  2843 I bt_vendor: Bluetooth Firmware and transport layer are initialized
03-17 09:49:30.340  2693  2904 D bt_userial_mct: Entering userial_read_thread()
03-17 09:49:30.370  1016  1016 D PersonaManagerService: ACTION_BOOT_COMPLETED
03-17 09:49:30.370  1016  1062 E PersonaManagerServiceHandler:  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
03-17 09:49:30.370  1016  1062 D KnoxKeyguardUpdateMonitor: onBootComplete
03-17 09:49:30.370  1016  1016 I KnoxKeyguardUpdateMonitor: onTrustManagedChanged user 0, managed:false
03-17 09:49:30.370  1016  1016 I KnoxKeyguardUpdateMonitor: onTrustChanged user:0, enable:false
03-17 09:49:30.370  1016  1016 D UsbStorageNotification: boot completed
03-17 09:49:30.370  1187  1187 D KeyguardViewMediator: onTrustChanged( Showing = false , userId = 0 )
03-17 09:49:30.380  1016  1040 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
03-17 09:49:30.380  1016  1040 D GpsLocationProvider_ex: BOOT_COMPLETED native_init 
03-17 09:49:30.380  1016  1040 D GpsLocationProvider: set_capabilities_callback: 55u
03-17 09:49:30.390  1016  1057 D PackageManager: [MSG] MCS_UNBIND
03-17 09:49:30.390  1016  1548 D qmi_secgps_clnt: qmi_secgps_client_init()
03-17 09:49:30.390  1016  1040 I libmdmdetect: ESOC framework not supported
03-17 09:49:30.390  1016  1231 I ActivityManager: Killing 1504:com.android.printspooler/u0a136 (adj 15): empty #31
03-17 09:49:30.390  1016  1040 I libmdmdetect: Found internal modem: modem
03-17 09:49:30.390  1016  1040 E PerMgrLib: Peripheral manager is not supported on this device
03-17 09:49:30.390  1016  1040 E Geofence_Adapter: I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
03-17 09:49:30.390  1016  1040 E Geofence_Adapter: I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
03-17 09:49:30.390  1016  1040 D GpsLocationProvider_ex: BOOT_COMPLETED native_cleanup 
03-17 09:49:30.390  1016  1062 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 09:49:30.390  1187  1187 D StorageNotification: boot completed
03-17 09:49:30.400  1016  1548 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
03-17 09:49:30.400  1016  1548 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
03-17 09:49:30.410  1016  1548 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
03-17 09:49:30.420  1016  1521 D StatusBarManagerService: setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
03-17 09:49:30.420  1187  1187 D PhoneStatusBar: updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_HCI
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_L2CAP
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_RFCOMM
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_AVDT
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_AVRC
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_A2D
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_BNEP
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_BTM
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_GAP
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_PAN
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_SAP
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_SDP
03-17 09:49:30.420  1016  1718 D ActivityManager: startProcessLocked calleePkgName: flipboard.boxer.app, hostingType: broadcast
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_GATT
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_SMP
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_BTAPP
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_BTIF
03-17 09:49:30.420  2693  2841 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
03-17 09:49:30.420  1016  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.420  1016  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.420  1016  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.420  1016  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.440  2915  2915 E Zygote  : MountEmulatedStorage()
03-17 09:49:30.440  2915  2915 I libpersona: KNOX_SDCARD checking this for 10099
03-17 09:49:30.440  2915  2915 E Zygote  : v2
03-17 09:49:30.440  2915  2915 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:30.440  2915  2915 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 09:49:30.440  1016  1718 I ActivityManager: Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2915 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 09:49:30.440  2915  2915 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:30.450  2915  2915 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 09:49:30.460  1016  1726 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.cache.DataUpdateListenerCacheService; callingUser = 0; userId(target) = 0
03-17 09:49:30.470  2915  2915 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:30.470  2915  2915 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:30.470  1016  2786 D SSRM:a  : DeviceInfo:: 000000000000
03-17 09:49:30.470  1016  2786 D SSRM:a  : SettingsAirViewInfo:: 000000000
03-17 09:49:30.500  1016  1548 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
03-17 09:49:30.500  1016  1561 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 09:49:30.510  1016  1561 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 09:49:30.510  1016  1040 W libprocessgroup: failed to open /acct/uid_10136/pid_1504/cgroup.procs: No such file or directory
03-17 09:49:30.510  1016  1561 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
03-17 09:49:30.510  1016  1548 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
03-17 09:49:30.520  1016  1548 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 09:49:30.520  1016  1561 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 09:49:30.520  1016  1548 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
03-17 09:49:30.520  1016  1561 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 09:49:30.520  1016  1548 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
03-17 09:49:30.530  2693  2841 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
03-17 09:49:30.530  1660  1678 I art     : Explicit concurrent mark sweep GC freed 7284(360KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 769us total 23.166ms
03-17 09:49:30.530  2693  2841 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40a86e9 
03-17 09:49:30.530  2693  2841 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40a86e9 
03-17 09:49:30.540  1016  1561 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 09:49:30.540  1016  1548 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
03-17 09:49:30.540  1016  1548 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 09:49:30.540  1016  1548 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-17 09:49:30.540  1016  1548 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 09:49:30.540  1016  1548 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
03-17 09:49:30.540  1016  1548 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 09:49:30.540  1016  1548 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
03-17 09:49:30.560  2693  2767 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
03-17 09:49:30.570  2693  2767 E bt-btif : Calling BTA_HhEnable
03-17 09:49:30.570  2693  2767 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
03-17 09:49:30.570  2693  2767 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
03-17 09:49:30.570  2693  2767 E BluetoothServiceJni: populateRssiValuesNative
03-17 09:49:30.570  2693  2767 I bluedroid: getModelRssiValues
03-17 09:49:30.570  2693  2767 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-17 09:49:30.570  2693  2767 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
03-17 09:49:30.570  1016  1016 D SettingsProvider: name = bluetooth_name
03-17 09:49:30.570  2693  2767 D BluetoothAdapterProperties: Name is: A5-1
03-17 09:49:30.580  2902  2902 D AndroidRuntime: 
03-17 09:49:30.580  2902  2902 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 09:49:30.580  2902  2902 D AndroidRuntime: CheckJNI is OFF
03-17 09:49:30.580  2902  2902 D AndroidRuntime: readGMSProperty: start
03-17 09:49:30.580  2902  2902 D AndroidRuntime: readGMSProperty: already setted!!
03-17 09:49:30.580  2902  2902 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 09:49:30.580  2902  2902 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 09:49:30.580  2902  2902 D AndroidRuntime: readGMSProperty: end
03-17 09:49:30.580  2902  2902 D AndroidRuntime: addProductProperty: start
03-17 09:49:30.580  2693  2767 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-17 09:49:30.580  2693  2767 D BluetoothAdapterProperties: Scan Mode:20
03-17 09:49:30.580  2693  2767 D BluetoothAdapterProperties: Discoverable Timeout:120
03-17 09:49:30.580  2693  2767 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
03-17 09:49:30.580  2693  2767 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
03-17 09:49:30.580  2693  2767 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
03-17 09:49:30.580  2693  2767 E bt-btif : btif_sock_init: !radio_req && !rfc_init
03-17 09:49:30.580  2693  2767 E bt-btif : btif_sock_init: !vhci_init
03-17 09:49:30.580  2693  2767 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
03-17 09:49:30.590  2693  2904 E bt_mct  : hci lib postload completed
03-17 09:49:30.600  2693  2767 D IOP_DB_BT: db_open: db_open : handle 3023486992l, read 13894 bytes onto local cache
03-17 09:49:30.600  2693  2767 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
03-17 09:49:30.600  2693  2767 D IOP_DB_BT: db_query: result 1
03-17 09:49:30.600  2693  2767 I         : iop_db_open: iop_db_open status 0
03-17 09:49:30.600  1016  1561 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 09:49:30.600  1016  1548 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
03-17 09:49:30.600  1016  1561 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
03-17 09:49:30.600  1016  1561 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-17 09:49:30.600  1016  1548 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
03-17 09:49:30.610  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 09:49:30.610  1016  1328 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-17 09:49:30.610  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
03-17 09:49:30.610  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
03-17 09:49:30.620  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 09:49:30.620  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 09:49:30.620  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:30.620  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:30.620  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:30.620  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:30.650   330   330 I ServiceManager: Waiting for service AtCmdFwd...
03-17 09:49:30.670  2084  2883 W DriveInitializer: Background init thread ended
03-17 09:49:30.670  2693  2767 D bte_conf: Device ID record 1 : primary
03-17 09:49:30.670  2693  2767 D bte_conf:   vendorId            = 0075
03-17 09:49:30.670  2693  2767 D bte_conf:   vendorIdSource      = 0001
03-17 09:49:30.670  2693  2767 D bte_conf:   product             = 0100
03-17 09:49:30.670  2693  2767 D bte_conf:   version             = 0200
03-17 09:49:30.670  2693  2767 D bte_conf:   clientExecutableURL = 
03-17 09:49:30.670  2693  2767 D bte_conf:   serviceDescription  = 
03-17 09:49:30.670  2693  2767 D bte_conf:   documentationURL    = 
03-17 09:49:30.670  2693  2767 D bte_conf: bte_load_did_conf no section named DID2.
03-17 09:49:30.670  2693  2767 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
03-17 09:49:30.670  2693  2764 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-17 09:49:30.670  2693  2764 D BluetoothAdapterProperties: ScanMode =  20
03-17 09:49:30.670  2693  2764 D BluetoothAdapterProperties: State =  11
03-17 09:49:30.670  1016  1503 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
03-17 09:49:30.670  2693  2764 D BluetoothAdapterProperties: Setting state to 12
03-17 09:49:30.670  2693  2764 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
03-17 09:49:30.680  2693  2767 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-17 09:49:30.680  2693  2767 D BluetoothAdapterProperties: Scan Mode:21
03-17 09:49:30.680  2693  2767 D BluetoothAdapterProperties: Discoverable Timeout:120
03-17 09:49:30.680  1016  1328 D SettingsProvider: name = bluetooth_a2dp_sink_mode
03-17 09:49:30.680  1016  1328 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:30.680  1016  1328 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:30.680  1016  1328 D SettingsProvider: selectionArgs: false
03-17 09:49:30.680  1016  1328 D SettingsProvider: selectionArgs: 1002
03-17 09:49:30.680  1016  1328 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:30.680  1016  1328 D SettingsProvider: ret = -1
03-17 09:49:30.720  2902  2902 E AffinityControl: AffinityControl: registerfunction enter
03-17 09:49:30.750  2902  2902 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 09:49:30.750  1016  1328 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-17 09:49:30.770  2693  2764 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-17 09:49:30.770  2693  2764 D BluetoothAdapterService: updateAdapterState state is 12
03-17 09:49:30.770  1016  1718 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-17 09:49:30.770  1016  1718 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
03-17 09:49:30.770  1016  1718 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.770  1016  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:30.770  1016  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 09:49:30.780  1016  1521 E PersonaManagerService: inState():  stateMachine is null !!
03-17 09:49:30.780  1016  1521 I PersonaManagerService: PersonaId don't exist
03-17 09:49:30.780  1016  1521 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 09:49:30.780  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 09:49:30.780  1016  1717 I ActivityManager: Killing 2165:com.vlingo.midas/u0a31 (adj 15): empty #31
03-17 09:49:30.790  2693  2764 D BluetoothAdapterService: Autoconnection is available 
03-17 09:49:30.790  2693  2764 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
03-17 09:49:30.790  2693  2764 D BluetoothAdapterService: starting service from this receiver
03-17 09:49:30.790  1451  1476 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:30.790  1451  1476 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:30.790  1836  1844 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:30.790  1836  1844 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:30.790  1439  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:30.790  1439  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:30.790  1187  1219 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:30.790  1187  1219 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:30.790  2693  2705 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:30.790  2693  2705 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:30.790  2693  2708 D BluetoothA2dp: onBluetoothStateChange: up=true
03-17 09:49:30.790  1016  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:30.790  1016  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:30.790  1016  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
03-17 09:49:30.790  1463  1701 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:30.790  1463  1701 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:30.790  1016  1521 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 09:49:30.800  1016  1521 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 09:49:30.810  1016  1521 W ActivityManager: mDVFSHelper.acquire()
03-17 09:49:30.810  1016  1521 D FocusedStackFrame: Set to : 0
03-17 09:49:30.810  1487  1487 D Launcher.HomeView: onPause
03-17 09:49:30.810  1487  1487 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 09:49:30.820  1016  1521 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 09:49:30.820  1016  1521 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 09:49:30.820  1016  1521 D InputDispatcher: Focused application set to: xxxx
03-17 09:49:30.820  1016  1521 D InputDispatcher: Focus left window: 1487
03-17 09:49:30.820  1016  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 09:49:30.820  1016  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 09:49:30.820  2693  2693 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
03-17 09:49:30.820  2693  2693 I BluetoothPbapService: Handler(): got msg=1
03-17 09:49:30.820  2902  2902 D AndroidRuntime: Shutting down VM
03-17 09:49:30.830  1016  1028 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
03-17 09:49:30.830  1016  1718 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
03-17 09:49:30.830  1016  1718 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
03-17 09:49:30.830  1016  1718 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.830  1016  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:30.830  1016  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 09:49:30.830  2693  2764 I BluetoothAdapterState: Entering On State from state = 11
03-17 09:49:30.840  1016  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 09:49:30.840  1016  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 09:49:30.840  2693  2954 V BluetoothPbapService: PBAP Service initSocket try: 0
03-17 09:49:30.840  1016  1717 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.840  1016  1717 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.840  1016  1717 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.840  1016  1717 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.840  1016  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 09:49:30.840  1016  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: Unable to call onBluetoothStateChange() on callback #11
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: android.os.DeadObjectException
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: 	at android.os.BinderProxy.transact(Binder.java:511)
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: 	at android.bluetooth.IBluetoothStateChangeCallback$Stub$Proxy.onBluetoothStateChange(IBluetoothStateChangeCallback.java:84)
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.sendBluetoothStateCallback(BluetoothManagerService.java:1067)
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:2021)
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService.access$3900(BluetoothManagerService.java:105)
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1590)
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 09:49:30.850  1016  1047 E BluetoothManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
03-17 09:49:30.850   256   256 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 09:49:30.870  2957  2957 E Zygote  : MountEmulatedStorage()
03-17 09:49:30.870  2957  2957 E Zygote  : v2
03-17 09:49:30.870  2957  2957 I libpersona: KNOX_SDCARD checking this for 10155
03-17 09:49:30.870  2957  2957 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:30.880  2957  2957 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 09:49:30.880  1016  1717 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2957 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 09:49:30.880  2957  2957 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:30.880  2957  2957 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 09:49:30.890  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 09:49:30.890  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.890  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 09:49:30.890  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 09:49:30.900  2693  2954 D BluetoothSocket: bindListen(): myUserId = 0
03-17 09:49:30.900  2693  2954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-17 09:49:30.900  1016  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
03-17 09:49:30.900  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
03-17 09:49:30.910  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-17 09:49:30.910  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
03-17 09:49:30.910  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
03-17 09:49:30.910  1487  1487 V ActivityThread: updateVisibility : ActivityRecord{19b2f832 token=android.os.BinderProxy@1bb5b46b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 09:49:30.920  2957  2957 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:30.920  2957  2957 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:30.930  1439  1439 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2f326f82, true
03-17 09:49:30.930  1187  1187 D BluetoothTile:  onBluetoothStateChange:
03-17 09:49:30.930  1439  1439 D BluetoothHeadset: registerMessageListener
03-17 09:49:30.940  1187  1187 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-17 09:49:30.940  1187  1187 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-17 09:49:30.940  1187  1187 D BluetoothTile:  getBluetoothState : 12
03-17 09:49:30.940  1814  1814 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
03-17 09:49:30.940  1187  1727 D BluetoothTile:  handleUpdatestate:false name:null
03-17 09:49:30.950  2693  2954 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
03-17 09:49:30.950  2693  2954 D BluetoothSocket: bindListen(), new LocalSocket 
03-17 09:49:30.950  2693  2954 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-17 09:49:30.950  2693  2954 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3801dfe8
03-17 09:49:30.950  2693  2954 D BluetoothSocket: channel: 19
03-17 09:49:30.950  2693  2954 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
03-17 09:49:30.950  1187  1727 D BluetoothTile:  handleUpdatestate:false name:null
03-17 09:49:30.950  2693  2708 D HeadsetService: registerMessageListener
03-17 09:49:30.960  1016  1231 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 09:49:30.960  1016  1231 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 09:49:30.960  1016  1231 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 09:49:30.960  2693  2708 D HeadsetService: registerMessageListener
03-17 09:49:30.960  2693  2776 D HeadsetStateMachine: Disconnected process message: 70
03-17 09:49:30.960  1439  1439 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
03-17 09:49:30.960  1439  1439 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
03-17 09:49:30.960  2693  2776 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2e227ca6
03-17 09:49:30.960  1187  1727 D BluetoothTile:  handleUpdatestate:false name:null
03-17 09:49:30.970  1016  1521 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-17 09:49:30.970  1439  1439 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-17 09:49:30.970  1439  1439 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
03-17 09:49:30.970  1439  1439 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
03-17 09:49:30.970  1016  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
03-17 09:49:30.970  1187  1187 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-17 09:49:30.970  1487  1487 D Launcher.HomeView: onStop
03-17 09:49:30.980  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 09:49:30.980  1487  1487 V ActivityThread: updateVisibility : ActivityRecord{19b2f832 token=android.os.BinderProxy@1bb5b46b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 09:49:30.990  1016  1231 D PersonaManager: isKioskContainerExistOnDevice
03-17 09:49:31.000  1016  1503 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 09:49:31.010  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.010  1016  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 09:49:31.010  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 09:49:31.010  1016  1717 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 09:49:31.020  2693  2776 D HeadsetStateMachine: Disconnected process message: 9
03-17 09:49:31.020  2693  2776 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
03-17 09:49:31.020  1016  1717 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.020  1016  1717 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 09:49:31.020  1016  1717 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 09:49:31.040  2902  2902 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 09:49:31.040   281   682 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
03-17 09:49:31.040   281   682 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,03-17 09:49:31.040   281   682 V voice   : voice_set_parameters: exit with code(-2)
,03-17 09:49:31.040   281   682 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
03-17 09:49:31.040   281   682 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-17 09:49:31.040   281   682 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-17 09:49:31.040   281   682 V audio_hw_primary: adev_set_parameters: exit
03-17 09:49:31.050  2693  2776 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
03-17 09:49:31.050  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 09:49:31.050  1016  1016 D SensorService: [SO] activate (ident=0xb8493fa0, enabled=0)
03-17 09:49:31.050  1016  1016 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 09:49:31.050  1016  1016 D SensorManager: unregisterListener ::   
,03-17 09:49:31.050  1016  1016 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-17 09:49:31.060  1016  1016 D SensorService: [SO] changed settle time [1]
,03-17 09:49:31.060  1016  1016 D SensorService: [SO] setDelay [66000000]
,03-17 09:49:31.060  1016  1016 D SensorService: [SO] activate (ident=0xb8493fa0, enabled=1)
,03-17 09:49:31.060  1016  1016 D SensorService: [SO] AR_init
,03-17 09:49:31.060  1016  1016 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 09:49:31.060  2693  2976 D BluetoothMapMasInstance: set MAP SDP message type : 1
,03-17 09:49:31.070  1016  1016 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 09:49:31.070  2693  2976 D BluetoothSocket: bindListen(): myUserId = 0
03-17 09:49:31.070  2693  2976 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-17 09:49:31.070  2693  2976 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
03-17 09:49:31.070  2693  2976 D BluetoothSocket: bindListen(), new LocalSocket 
03-17 09:49:31.070  2693  2976 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-17 09:49:31.070  2693  2976 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@269bd32
,03-17 09:49:31.070  2693  2976 D BluetoothSocket: channel: 5
,03-17 09:49:31.080  1016  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,03-17 09:49:31.080  1016  1040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,03-17 09:49:31.080  1487  1487 D Launcher: onTrimMemory. Level: 20
,03-17 09:49:31.080  1016  1040 W libprocessgroup: failed to open /acct/uid_10031/pid_2165/cgroup.procs: No such file or directory
,03-17 09:49:31.090   308   308 E USB_UICC: Timeout! No signal received. Retry num = 30
,03-17 09:49:31.140  1016  1038 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 09:49:31.140  2957  2957 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 09:49:31.170  2957  2957 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6629-6631)
,03-17 09:49:31.170  2957  2957 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 09:49:31.180   308   308 E USB_UICC: Timeout! No signal received. Reach maximum retries!,
03-17 09:49:31.180   308   308 E USB_UICC: usb_uicc_init_qmi failed ! 
,03-17 09:49:31.180   308   308 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
,03-17 09:49:31.180   308   308 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-17 09:49:31.200  2915  2915 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
,03-17 09:49:31.210  1016  1038 D SensorService: [SO] 0.134 0.402 10.113
,03-17 09:49:31.210  2957  2957 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ca6573b}
,03-17 09:49:31.210  2957  2957 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 09:49:31.210  1016  1038 D SensorService: [SO] [100 -> 255]
03-17 09:49:31.210  2957  2957 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 09:49:31.210  2915  2915 E ActivityThread: Failed to find provider info for flipboard.auth.internal
,03-17 09:49:31.250  2957  2957 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 09:49:31.250  2957  2957 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:49:31.250  1016  1718 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
03-17 09:49:31.250  1016  1718 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,03-17 09:49:31.250  2957  2957 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 09:49:31.260  1016  1016 I DrmEventReceiver: DrmEventReceiver : onReceive
03-17 09:49:31.260  1016  1016 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,03-17 09:49:31.260  1016  1016 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-17 09:49:31.260  1016  1016 I System.out: start Service
,03-17 09:49:31.260  1016  1016 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,03-17 09:49:31.260  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
,03-17 09:49:31.260  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.260  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.260  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.260  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.270  1242  1242 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
,03-17 09:49:31.270  2957  2957 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-17 09:49:31.280  2957  2957 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
03-17 09:49:31.280  2957  2957 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,03-17 09:49:31.280  2998  2998 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.280  2998  2998 E Zygote  : v2
03-17 09:49:31.280  2998  2998 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:31.280  2998  2998 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:31.280  2998  2998 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 09:49:31.280  2957  2957 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 09:49:31.280  2957  2957 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 09:49:31.280  2957  2957 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 09:49:31.280  2957  2957 I Adreno-EGL: Local Branch: 
03-17 09:49:31.280  2957  2957 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 09:49:31.280  2957  2957 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 09:49:31.280  2957  2957 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 09:49:31.280  2998  2998 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:31.280  2998  2998 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:31.290  1016  1041 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=2998 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-17 09:49:31.290  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,03-17 09:49:31.290  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.290  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.290  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.290  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.310  3010  3010 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.310  3010  3010 E Zygote  : v2
03-17 09:49:31.310  3010  3010 I libpersona: KNOX_SDCARD checking this for 10152
03-17 09:49:31.310  3010  3010 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:31.310  3010  3010 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:31.310  3010  3010 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:31.310  3010  3010 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 09:49:31.310  1016  1041 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=3010 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
03-17 09:49:31.310  1016  1016 D ActivityManager: startService callerProcessName:android, calleePkgName: android
03-17 09:49:31.310  1016  1016 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
03-17 09:49:31.320  1016  1717 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
03-17 09:49:31.320  1016  1717 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
03-17 09:49:31.320  1016  1717 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.320  1016  1717 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:31.320  1016  1717 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 09:49:31.330  2998  2998 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:31.330  2998  2998 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:31.350  1016  1340 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 09:49:31.350  1016  1340 D SecContentProvider2: mCursor = null
03-17 09:49:31.350  1016  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,03-17 09:49:31.350   280   519 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 629
03-17 09:49:31.350   280   519 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 629
,03-17 09:49:31.350  1016  1040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,03-17 09:49:31.350  3010  3010 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:31.350  1242  1242 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 09:49:31.350  3010  3010 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:31.360  1016  3041 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
,03-17 09:49:31.370  2998  2998 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 09:49:31.370  1016  1521 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,03-17 09:49:31.370  1016  1521 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,03-17 09:49:31.370  1016  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:31.370  1016  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 09:49:31.370  1016  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 09:49:31.380  2998  2998 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-17 09:49:31.380  1016  1016 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
,03-17 09:49:31.390  2998  2998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-17 09:49:31.400  1016  1231 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media,
03-17 09:49:31.400  1016  1231 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,03-17 09:49:31.400  1016  1231 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.400  1016  1231 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:31.400  1016  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 09:49:31.400  1016  1726 D ActivityManager: startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
,03-17 09:49:31.400  1016  1726 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,03-17 09:49:31.400   280   280 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-17 09:49:31.400  1016  1726 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.400  1016  1726 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:31.400  1016  1726 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-17 09:49:31.420  1463  1463 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 09:49:31.420  1016  1503 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,03-17 09:49:31.420  1016  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.420  1016  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.420  1016  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.420  1016  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.420  1463  1463 D BluetoothBDTestService: onCreate()
,03-17 09:49:31.420  1463  1463 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-17 09:49:31.420  1463  1463 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-17 09:49:31.430  3010  3010 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
03-17 09:49:31.430  1463  1463 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
,03-17 09:49:31.430   256  1171 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-17 09:49:31.440   256   445 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-17 09:49:31.440  3046  3046 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.440  3046  3046 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:31.440  3046  3046 E Zygote  : v2
03-17 09:49:31.440  3046  3046 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:31.440  3046  3046 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:31.440  3046  3046 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:31.440  3046  3046 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 09:49:31.450  1016  1503 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3046 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 09:49:31.450  1016  1503 I ActivityManager: Killing 2192:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,03-17 09:49:31.460  1463  1463 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
,03-17 09:49:31.460  3046  3046 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:31.470  3046  3046 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:31.470  1016  1503 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
03-17 09:49:31.470  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,03-17 09:49:31.470  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.470  1016  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:31.470  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 09:49:31.470  1016  1029 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
03-17 09:49:31.470  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,03-17 09:49:31.470  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.470  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:31.470  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,03-17 09:49:31.470  1016  1077 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
,03-17 09:49:31.480  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.480  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.480  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.480  1016  1077 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.490  3062  3062 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.490  3062  3062 E Zygote  : v2
03-17 09:49:31.490  3062  3062 I libpersona: KNOX_SDCARD checking this for 10003
03-17 09:49:31.490  3062  3062 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:31.490  3062  3062 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 09:49:31.500  3062  3062 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:31.500  1016  1077 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3062 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-17 09:49:31.500  3062  3062 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:31.510  1016  1328 D ActivityManager: startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
,03-17 09:49:31.510  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.510  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.510  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.510  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.520  1242  3044 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
,03-17 09:49:31.520  1463  1463 D CscUpdateService: onStart
,03-17 09:49:31.520  1463  1463 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-17 09:49:31.520  1463  1463 I CscUpdateService: set_CSC_version
,03-17 09:49:31.520  1463  1463 E CscParser: update(): xml file exist
,03-17 09:49:31.520  3046  3046 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 09:49:31.530  3062  3062 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:31.530  3062  3062 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:31.530  3079  3079 E Zygote  : MountEmulatedStorage()
,03-17 09:49:31.530  3079  3079 E Zygote  : v2
03-17 09:49:31.530  3079  3079 I libpersona: KNOX_SDCARD checking this for 1101
03-17 09:49:31.530  3079  3079 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:31.530  3079  3079 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 09:49:31.530  3079  3079 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 09:49:31.540  3079  3079 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:31.540  1016  1328 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3079 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,03-17 09:49:31.550  1016  1040 W libprocessgroup: failed to open /acct/uid_10050/pid_2192/cgroup.procs: No such file or directory
,03-17 09:49:31.550  1463  1463 I CscUtil : isWifiOnly = false
,03-17 09:49:31.550  1463  1463 I System.out: HandDataNode = null
03-17 09:49:31.550  1463  1463 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
,03-17 09:49:31.560  1463  1463 I CscUpdateService: This is normal boot : CSC not updated
,03-17 09:49:31.560  3079  3079 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:31.560  3079  3079 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:31.560  2957  3032 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-17 09:49:31.570  1463  3088 E CscParser: update(): xml file exist
,03-17 09:49:31.580  1463  3088 D CscGPS  : CSCGPS.updateParameters
,03-17 09:49:31.580  1463  3088 D CscGPS  : supl host : null
03-17 09:49:31.580  1463  3088 D CscGPS  : SUPL Host is null or invalid
03-17 09:49:31.580  1463  3088 D CscGPS  : supl_ver : null
03-17 09:49:31.580  1463  3088 D CscGPS  : SUPL Ver is null or invalid
03-17 09:49:31.580  1463  3088 D CscGPS  : supl port : null
03-17 09:49:31.580  1463  3088 D CscGPS  : SUPL PORT is null or invalid
03-17 09:49:31.580  1463  3088 D CscGPS  : LPP : null
03-17 09:49:31.580  1463  3088 D CscGPS  : LPP is null or invalid
03-17 09:49:31.580  1463  3088 D CscGPS  : CSC don't have any AGPS value.
,03-17 09:49:31.600  1463  1463 I CscUpdateService: same CSC Version,
,03-17 09:49:31.600  1463  1463 D CscUtil : Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
,03-17 09:49:31.620  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 09:49:31.620  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 09:49:31.620  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:31.630  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:31.630  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:31.630  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:31.640  1016  1726 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 09:49:31.650   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 09:49:31.760  1016  1029 I art     : Explicit concurrent mark sweep GC freed 162004(9MB) AllocSpace objects, 21(2MB) LOS objects, 33% free, 26MB/39MB, paused 2.590ms total 248.612ms
,03-17 09:49:31.790  3046  3046 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-17 09:49:31.790  3046  3097 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458204571800
,03-17 09:49:31.790  3079  3079 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,03-17 09:49:31.800  1016  1328 D ActivityManager: bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: null
,03-17 09:49:31.800  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 09:49:31.800  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.800  1016  1328 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 09:49:31.800  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 09:49:31.800  2957  2957 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:49:31.800  1016  1726 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-17 09:49:31.800  1016  1726 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-17 09:49:31.800  1016  1726 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.810  1016  1726 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:31.810  1016  1726 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 09:49:31.810  3046  3046 I KnoxUsageLogPro: premStatus:2
03-17 09:49:31.810  1016  1503 I ActivityManager: Killing 2249:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,03-17 09:49:31.810  3046  3046 I KnoxUsageLogPro: isEulaShown : false
03-17 09:49:31.810  3046  3046 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-17 09:49:31.810  1016  1328 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,03-17 09:49:31.810  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.810  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.810  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.810  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.820  3079  3079 V SmartcardService: main Received broadcast
03-17 09:49:31.820  3079  3079 V SmartcardService: Starting smartcard service after boot completed
,03-17 09:49:31.830  3100  3100 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.830  3100  3100 E Zygote  : v2
03-17 09:49:31.830  3100  3100 I libpersona: KNOX_SDCARD checking this for 10085
03-17 09:49:31.830  3100  3100 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:31.830  3100  3100 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:31.830  3100  3100 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 09:49:31.830  1016  1328 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=3100 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 09:49:31.830  1016  1328 I ActivityManager: Killing 1650:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-17 09:49:31.830  3100  3100 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 09:49:31.840  2957  2957 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 09:49:31.840  1016  1726 D ActivityManager: startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
03-17 09:49:31.840  1016  1726 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,03-17 09:49:31.840  1016  1726 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.840  1242  1242 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-17 09:49:31.840  1016  1726 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:31.840  1016  1726 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,03-17 09:49:31.850  2957  2957 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 09:49:31.850  2957  2957 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 09:49:31.850  1016  1028 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
03-17 09:49:31.850  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,03-17 09:49:31.850  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.850  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:31.850  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 09:49:31.860  1016  1717 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,03-17 09:49:31.860  2957  2957 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 09:49:31.860  1016  1717 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.860  1016  1717 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.860  1016  1717 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.860  1016  1717 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.870  3118  3118 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.870  3118  3118 I libpersona: KNOX_SDCARD checking this for 10157
03-17 09:49:31.870  3118  3118 E Zygote  : v2
03-17 09:49:31.870  3118  3118 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:31.870  3100  3100 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:31.880  3100  3100 D ActivityThread: Added TimaKeyStore provider,
,03-17 09:49:31.880  1016  1717 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3118 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,03-17 09:49:31.900  3118  3118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:31.900  3118  3118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 09:49:31.900  3118  3118 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:31.910  3100  3100 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 09:49:31.910  2957  2957 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 09:49:31.910  2957  2957 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:49:31.910  3100  3100 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 09:49:31.910  3100  3100 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 09:49:31.910  3100  3100 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 09:49:31.910  3100  3100 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 09:49:31.910  3100  3100 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-17 09:49:31.910  1463  1702 D TP/MmsProvider: Update uri=content://mms, match=0
,03-17 09:49:31.920  1463  1702 D TP/MmsProvider: update , handleReadChangedBroadcast
03-17 09:49:31.920  1463  1702 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 09:49:31.920  3046  3097 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 37257
,03-17 09:49:31.930  2333  2333 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
,03-17 09:49:31.930  2333  2333 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 4865.073905
,03-17 09:49:31.930  2333  2333 I Mms/ReservationManager: resetAfterConnected()
,03-17 09:49:31.930  1463  1701 D TP/MmsSmsProvider: query,matched:7, calling pid = 2333
,03-17 09:49:31.930  1016  1726 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-17 09:49:31.940  1016  1726 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,03-17 09:49:31.940  1463  1701 D TP/MmsSmsProvider: match 7:Elapsed time : 2.693 ms
,03-17 09:49:31.940  3118  3118 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:31.940  1016  1726 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.940  1016  1726 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:31.940  1016  1726 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-17 09:49:31.940  3118  3118 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:31.950  1016  1040 W libprocessgroup: failed to open /acct/uid_10113/pid_2249/cgroup.procs: No such file or directory
,03-17 09:49:31.950  1016  1328 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-17 09:49:31.950  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,03-17 09:49:31.950  1016  1040 W libprocessgroup: failed to open /acct/uid_10015/pid_1650/cgroup.procs: No such file or directory
,03-17 09:49:31.950  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:31.950  1016  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 09:49:31.950  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-17 09:49:31.950  2333  3134 D Mms/MessagingNotification: sDisableVibrateForCamera = false
,03-17 09:49:31.950  2333  3134 D Mms/TelephonyPermission: isDefault true
,03-17 09:49:31.960  2333  2333 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 09:49:31.960  1463  1475 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2333
,03-17 09:49:31.960  3118  3118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 09:49:31.960  1016  1328 D ActivityManager: startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
,03-17 09:49:31.970  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.970  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.970  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.970  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.970  3062  3136 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,03-17 09:49:31.980  1242  3044 E SQLiteLog: (283) recovered 302 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,03-17 09:49:31.980  3141  3141 E Zygote  : MountEmulatedStorage()
,03-17 09:49:31.980  3141  3141 E Zygote  : v2
03-17 09:49:31.980  3141  3141 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:31.980  3141  3141 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:31.980  3141  3141 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:31.990  1016  1328 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3141 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 09:49:31.990  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:31.990  1016  1503 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
03-17 09:49:31.990  1016  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
03-17 09:49:31.990  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
03-17 09:49:31.990  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-17 09:49:31.990  3141  3141 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:31.990  3141  3141 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:32.000  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
,03-17 09:49:32.000  1463  1701 D TP/MmsSmsProvider: query,matched:200, calling pid = 2333
,03-17 09:49:32.000  1463  1701 D TP/MmsSmsProvider: match 200:Elapsed time : 1.506 ms
03-17 09:49:32.000  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.000  2957  3148 D OpenGLRenderer: Render dirty regions requested: true
03-17 09:49:32.000  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.000  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.000  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.020  3155  3155 E Zygote  : MountEmulatedStorage()
03-17 09:49:32.020  3155  3155 E Zygote  : v2
03-17 09:49:32.020  3155  3155 I libpersona: KNOX_SDCARD checking this for 10048
03-17 09:49:32.020  3155  3155 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:32.020  3155  3155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:32.020  3155  3155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:32.020  3155  3155 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:32.030  1016  1029 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3155 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 09:49:32.030  1016  1726 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 09:49:32.030  1016  1726 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 09:49:32.030  1016  1726 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 09:49:32.030  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 09:49:32.030  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 09:49:32.030  2957  2957 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 09:49:32.030  2957  2957 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 09:49:32.040  2333  2333 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-17 09:49:32.040  2333  3152 D Mms/TelephonyPermission: isDefault true
03-17 09:49:32.040  2333  3152 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-17 09:49:32.040  2333  3152 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 114.593073
,03-17 09:49:32.040  3141  3141 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:32.050  3141  3141 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:32.050   256   256 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
03-17 09:49:32.050   317   317 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 828us total 23.309ms
,03-17 09:49:32.050  3155  3155 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:32.050  1016  1521 I ActivityManager: Killing 2319:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-17 09:49:32.050  3155  3155 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:32.050   289   289 E SMD     : DCD OFF
,03-17 09:49:32.070  1463  1475 D TP/SmsProvider: query,matched:0, calling pid = 2333
,03-17 09:49:32.070   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 17.075ms
03-17 09:49:32.070  1463  1475 D TP/SmsProvider: match 0:Elapsed time : 2.608 ms
,03-17 09:49:32.070  1016  1328 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,03-17 09:49:32.070  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.070  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.070  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.070  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.070  1016  1717 D InputDispatcher: Focus entered window: 2957
,03-17 09:49:32.080  1463  1701 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-17 09:49:32.080  1463  1701 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
,03-17 09:49:32.080  1016  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 09:49:32.080  1016  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 09:49:32.080  2957  2957 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 09:49:32.080  2957  3148 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 09:49:32.090   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 17.313ms
03-17 09:49:32.090  2957  3148 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 09:49:32.090  2957  3148 D OpenGLRenderer: Enabling debug mode 0
,03-17 09:49:32.090  1463  1701 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 09:49:32.090  1463  1701 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
,03-17 09:49:32.090  3062  3136 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,03-17 09:49:32.090  1463  1701 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-17 09:49:32.090  1463  1701 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 09:49:32.090  1463  1701 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 09:49:32.090  1463  1701 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 09:49:32.100  1463  1701 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 09:49:32.100  1463  1701 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 09:49:32.100  1463  1701 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 09:49:32.100  3155  3155 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 09:49:32.100  3155  3155 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 09:49:32.100  3155  3155 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-17 09:49:32.100   391   391 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 3062
03-17 09:49:32.100   391   391 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,03-17 09:49:32.100  3062  3136 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,03-17 09:49:32.100  3062  3136 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,03-17 09:49:32.110   391   391 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 3062
03-17 09:49:32.110   391   391 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,03-17 09:49:32.110  1463  1701 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-17 09:49:32.110  3175  3175 I libpersona: KNOX_SDCARD checking this for 10159
03-17 09:49:32.110  1463  1701 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 09:49:32.110  3175  3175 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:32.110  3175  3175 E Zygote  : MountEmulatedStorage()
03-17 09:49:32.110  3175  3175 E Zygote  : v2
03-17 09:49:32.110  3175  3175 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 09:49:32.110  1016  1328 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=3175 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 09:49:32.120  3175  3175 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:32.120  1016  1328 I ActivityManager: Killing 2352:com.sec.android.omc/1000 (adj 15): empty #31
,03-17 09:49:32.120  3175  3175 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-17 09:49:32.120  2333  3152 D Mms/Conversation: deleteTempConversation(),deleted=0
,03-17 09:49:32.130  1463  1702 D TP/SmsProvider: query,matched:51, calling pid = 2333
,03-17 09:49:32.130  1463  1702 D TP/SmsProvider: match 51:Elapsed time : 1.520 ms
,03-17 09:49:32.130  1463  1475 D SmsProvider: Update uri=content://sms/outbox, match=8
,03-17 09:49:32.140  1463  1475 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 09:49:32.140  2333  3134 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 09:49:32.140  2333  3152 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-17 09:49:32.140  2333  3152 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
,03-17 09:49:32.140  2333  3152 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
,03-17 09:49:32.150  1463  1480 D TP/SmsProvider: query,matched:26, calling pid = 2333
03-17 09:49:32.150  3175  3175 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:32.150  3175  3175 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:32.150  1572  1580 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 09:49:32.160  1463  1480 D TP/SmsProvider: match 26:Elapsed time : 7.566 ms
,03-17 09:49:32.160  1016  1231 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 09:49:32.180  1016  1040 W libprocessgroup: failed to open /acct/uid_1000/pid_2319/cgroup.procs: No such file or directory
03-17 09:49:32.180  1016  1040 W libprocessgroup: failed to open /acct/uid_1000/pid_2352/cgroup.procs: No such file or directory
,03-17 09:49:32.180  1016  3191 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 09:49:32.180  1187  1187 D PanelView: There is/are notification(s) 
,03-17 09:49:32.190  1016  1049 I ActivityManager: Displayed Component not be shown by security: +1s350ms
,03-17 09:49:32.190  1016  1049 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 09:49:32.190  1016  1049 W ActivityManager: mDVFSHelper.release()
03-17 09:49:32.190  1016  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a50a3aa u0 com.test.thalitest/.MainActivity t12} time:37658
,03-17 09:49:32.190  1016  1041 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 09:49:32.200  1814  1814 I SamsungIME: getCurrentCandidateView
,03-17 09:49:32.200  1242  3044 D MediaScanner: Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 09:49:32.200  1487  1487 D Launcher.Model: reloadBadges entered.
,03-17 09:49:32.200  1572  1582 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 09:49:32.200  1572  1582 D BadgeProvider: sendNotify, [notify] : null
03-17 09:49:32.200  1572  1582 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 09:49:32.200  1572  1582 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 09:49:32.200  1572  1582 D BadgeProvider: update, [UpdateCount] : 1
03-17 09:49:32.200  2333  3152 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 09:49:32.200  2333  3152 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 09:49:32.200  2333  3152 D Mms/TelephonyPermission: isDefault true
,03-17 09:49:32.210  2957  2957 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1c046a34 time:37670
,03-17 09:49:32.210  2333  3134 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 09:49:32.210  2333  3134 D Mms/MessagingNotification: remove alarm
,03-17 09:49:32.220  1463  1475 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2333
,03-17 09:49:32.230  1016  1077 D SettingsProvider: name = block_emergency_message
03-17 09:49:32.230  1016  1077 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:32.230  1016  1077 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:32.230  1016  1077 D SettingsProvider: selectionArgs: false
03-17 09:49:32.230  1016  1077 D SettingsProvider: selectionArgs: 10048
03-17 09:49:32.230  1016  1077 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:32.230  1016  1077 D SettingsProvider: ret = -1
,03-17 09:49:32.230  1016  1718 W ActivityManager: getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,03-17 09:49:32.240  2333  3195 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 09:49:32.240  1463  1702 D TP/SmsProvider: query,matched:0, calling pid = 2333
,03-17 09:49:32.240  1463  1702 D TP/SmsProvider: match 0:Elapsed time : 3.087 ms
,03-17 09:49:32.250  3175  3175 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
,03-17 09:49:32.260  2333  3134 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 214.67776
,03-17 09:49:32.260  1016  1328 D ActivityManager: startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
,03-17 09:49:32.260  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.260  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.260  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.260  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.280  3198  3198 E Zygote  : MountEmulatedStorage()
,03-17 09:49:32.280  3198  3198 E Zygote  : v2
03-17 09:49:32.280  3198  3198 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:32.280  3198  3198 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:32.280  3198  3198 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 09:49:32.280  1016  1328 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3198 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 09:49:32.280  1016  1328 I ActivityManager: Killing 2382:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,03-17 09:49:32.290  3198  3198 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:32.290  3198  3198 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:32.310  3141  3141 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,03-17 09:49:32.310  3198  3198 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:32.310  3198  3198 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:32.340  1463  1475 I art     : Explicit concurrent mark sweep GC freed 39917(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/13MB, paused 1.066ms total 75.533ms
,03-17 09:49:32.340  1016  1328 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,03-17 09:49:32.340  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,03-17 09:49:32.340  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:32.340  1016  1328 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 09:49:32.350  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,03-17 09:49:32.350  2873  2984 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:49:32.360  1463  1475 D TP/MmsSmsProvider: query,matched:200, calling pid = 2333
,03-17 09:49:32.360  1311  1311 I WifiCredService: onCreate
,03-17 09:49:32.370  1016  1040 W libprocessgroup: failed to open /acct/uid_1000/pid_2382/cgroup.procs: No such file or directory
,03-17 09:49:32.380  1463  1475 D TP/MmsSmsProvider: match 200:Elapsed time : 18.987 ms
,03-17 09:49:32.390  3141  3141 D DSM     : [Lines:107] Normal booted
03-17 09:49:32.390  3141  3141 D DSM     : [Lines:114] Boot completed
,03-17 09:49:32.410   256  1851 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-17 09:49:32.410   256   445 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-17 09:49:32.440  1814  1814 D SamsungIME: Dismiss ExpandCandiate
,03-17 09:49:32.440  2957  2957 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2957
,03-17 09:49:32.440  1311  1311 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,03-17 09:49:32.450  1016  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
03-17 09:49:32.450  1016  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 09:49:32.450  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,03-17 09:49:32.450  1016  1131 E WifiNative-wlan0: invaild command id : 215
,03-17 09:49:32.450  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.450  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.450  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.450  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.460  1311  1311 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 09:49:32.460  1311  1311 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 09:49:32.460  1311  1311 D MY_TAG  : Action boot completed received
,03-17 09:49:32.460  1016  1097 V AlarmManager: waitForAlarm result :8
,03-17 09:49:32.460  1242  3044 V MediaScanner: processDirectory :  /system/media
,03-17 09:49:32.470  3218  3218 E Zygote  : MountEmulatedStorage(),
03-17 09:49:32.470  3218  3218 E Zygote  : v2,
03-17 09:49:32.470  3218  3218 I libpersona: KNOX_SDCARD checking this for 10160
03-17 09:49:32.470  3218  3218 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 09:49:32.470  3218  3218 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:32.470  3218  3218 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:32.470  3218  3218 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:32.480  2102  2102 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-17 09:49:32.480  2102  2102 I dhcpcd  : wlan0: no IPv6 Routers available
,03-17 09:49:32.480  1016  1029 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3218 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-17 09:49:32.480  1016  1029 I ActivityManager: Killing 2397:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-17 09:49:32.490  1016  1097 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 09:49:32.490  1016  1016 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 09:49:32.530  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
,03-17 09:49:32.530  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.530  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.530  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 09:49:32.530  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.550  1016  1029 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3236 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 09:49:32.560  3236  3236 E Zygote  : MountEmulatedStorage(),
03-17 09:49:32.560  1016  1029 I ActivityManager: Killing 2304:com.sec.android.app.mt/1000 (adj 15): empty #31,
03-17 09:49:32.560  3236  3236 E Zygote  : v2,
03-17 09:49:32.560  3236  3236 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 09:49:32.560  3236  3236 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:32.560  3236  3236 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:32.570  3236  3236 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:32.570  3236  3236 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:32.570  1311  1311 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,03-17 09:49:32.570  1016  1503 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,03-17 09:49:32.580  1311  2596 V NearbySettings: MountReceiver.mPrefHandler - 7002
,03-17 09:49:32.590  3236  3236 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:32.590  3236  3236 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:32.590  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 09:49:32.610  1311  1311 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-17 09:49:32.610  1311  1311 I NearbySettings: MountReceiver.onReceive - Internal Path
,03-17 09:49:32.610  1463  1480 D TP/SmsProvider: query,matched:0, calling pid = 2333
,03-17 09:49:32.620  3218  3218 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:32.620  3218  3218 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:32.620  1016  1028 D SettingsProvider: name = personal_mode_enabled
03-17 09:49:32.620  1242  3044 V MediaScanner:  prescan time: 626ms (DB items: 141)
03-17 09:49:32.620  1242  3044 V MediaScanner:     scan time: 173ms (Caching mode: true), (makeEntry time: 122ms ~70%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 09:49:32.620  1242  3044 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 09:49:32.620  1242  3044 V MediaScanner:    total time: 799ms
03-17 09:49:32.620  1242  3044 V MediaScanner: checked files: 133  directories : 6  (I: 0, U: 0)
,03-17 09:49:32.620  1242  3044 D MediaScanner: checkDefaultSounds
03-17 09:49:32.620  1242  3044 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
,03-17 09:49:32.620  3236  3236 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 09:49:32.620  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 09:49:32.620  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 09:49:32.630  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:32.630  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:32.630  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:32.630  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:32.630  1016  1340 D SettingsProvider: name = next_alarm_formatted
03-17 09:49:32.630  1016  1340 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:32.630  1016  1340 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:32.630  1016  1340 D SettingsProvider: selectionArgs: false
03-17 09:49:32.630  1016  1340 D SettingsProvider: selectionArgs: 10085
03-17 09:49:32.630  1016  1340 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:32.630  1016  1340 D SettingsProvider: ret = -1
,03-17 09:49:32.640  1016  1340 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,03-17 09:49:32.660  1463  1480 D TP/SmsProvider: match 0:Elapsed time : 44.435 ms
,03-17 09:49:32.660   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 09:49:32.670  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 09:49:32.680  1016  1040 W libprocessgroup: failed to open /acct/uid_10131/pid_2397/cgroup.procs: No such file or directory
03-17 09:49:32.680  1016  1040 W libprocessgroup: failed to open /acct/uid_1000/pid_2304/cgroup.procs: No such file or directory
,03-17 09:49:32.680  1242  3044 D MediaScanner: OK. alarm_alert is already exist in setting DB.
,03-17 09:49:32.680  1242  3044 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
,03-17 09:49:32.680  3218  3218 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 09:49:32.680  1242  3044 D MediaScanner: OK. notification_sound is already exist in setting DB.
03-17 09:49:32.680  3236  3236 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 09:49:32.680  1242  3044 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
,03-17 09:49:32.690  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-17 09:49:32.690  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,03-17 09:49:32.690  1242  3044 D MediaScanner: OK. ringtone is already exist in setting DB.
,03-17 09:49:32.690  3236  3236 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,03-17 09:49:32.690  1463  1463 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 09:49:32.690  1463  1463 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-17 09:49:32.690  1463  1463 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 09:49:32.700  1463  1463 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 09:49:32.700  1463  1463 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 09:49:32.700  1463  1463 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 09:49:32.700  2671  2671 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2671) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 09:49:32.700  2671  2671 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2671) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-17 09:49:32.700  1242  3044 D MediaScannerService: !@done scanning volume internal
,03-17 09:49:32.700  1242  3044 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,03-17 09:49:32.700  2671  2671 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2671) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,03-17 09:49:32.710  1311  1311 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
,03-17 09:49:32.710  1311  1311 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
,03-17 09:49:32.720  1463  1702 D TP/SmsProvider: query,matched:51, calling pid = 2333
03-17 09:49:32.730  1242  3044 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 09:49:32.730  1463  1702 D TP/SmsProvider: match 51:Elapsed time : 5.965 ms
,03-17 09:49:32.740  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,03-17 09:49:32.750  1242  3044 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-17 09:49:32.760  3218  3218 D [0]UMC:UMCContentProvider: @onCreate
,03-17 09:49:32.760  2333  3152 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
,03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
,03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-17 09:49:32.770  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,03-17 09:49:32.780  1242  3044 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,03-17 09:49:32.780  1242  3044 D MediaProvider: savePlaylistTableInBulkDeleter finished,
03-17 09:49:32.780  1242  3044 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-17 09:49:32.780  1242  3044 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-17 09:49:32.780  1242  3044 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty,
,03-17 09:49:32.780  1311  1311 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-17 09:49:32.780  1311  1311 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX,
03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
,03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3,
,03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4,
03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-17 09:49:32.800  3236  3236 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-17 09:49:32.810  3218  3218 D [0]UMC:Core: onCreate(): 
03-17 09:49:32.810  3218  3218 D [0]UMC:Core: @isManagedProfileUser
03-17 09:49:32.810  3218  3218 D [0]UMC:Core: userId: 0
,03-17 09:49:32.810  3218  3218 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
03-17 09:49:32.810  3218  3218 D [0]UMC:Core: userInfo.isManagedProfile() : false
03-17 09:49:32.810  3236  3236 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-17 09:49:32.810  1016  1726 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,03-17 09:49:32.820  1016  1726 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.820  1016  1726 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.820  1016  1726 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.820  1016  1726 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.820   276   977 D EnterpriseController: uids 10120
03-17 09:49:32.820   276   977 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 09:49:32.820   276   977 D Netd    : getNetworkForDns: using netid 502 for uid 10120
,03-17 09:49:32.840  3262  3262 E Zygote  : MountEmulatedStorage(),
03-17 09:49:32.840  3262  3262 E Zygote  : v2
03-17 09:49:32.840  3262  3262 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 09:49:32.840  3262  3262 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:32.850  3262  3262 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 09:49:32.850  1016  1726 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3262 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 09:49:32.850  3262  3262 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 09:49:32.850  3262  3262 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:32.860  1572  1580 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 09:49:32.880  1016  1029 I ActivityManager: Killing 2437:com.wsomacp/u0a25 (adj 15): empty #31
,03-17 09:49:32.880  3262  3262 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:32.880  3262  3262 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:32.900  1242  3044 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-17 09:49:32.910   391   391 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,03-17 09:49:32.940  3100  3100 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 226.200ms
,03-17 09:49:32.950  1242  3044 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-17 09:49:32.960  1311  1311 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-17 09:49:32.960  1814  1814 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 09:49:32.960  2957  2957 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 09:49:32.970  3218  3218 D [0]UMC:DeviceInfo: USA==US==
,03-17 09:49:32.980  1572  3196 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
,03-17 09:49:32.990  1487  1487 D Launcher.Model: reloadBadges entered.
,03-17 09:49:32.990  1572  3196 D BadgeProvider: sendNotify, [notify] : null
03-17 09:49:32.990  1572  3196 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 09:49:32.990  1572  3196 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 09:49:32.990  1572  3196 D BadgeProvider: update, [UpdateCount] : 1
,03-17 09:49:33.000  2333  3152 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 09:49:33.020  2333  3278 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 09:49:33.020  1311  1311 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-17 09:49:33.020  1311  1311 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-17 09:49:33.030  3062  3136 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,03-17 09:49:33.030  3062  3136 I SecureStorage: [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,03-17 09:49:33.050  1311  1311 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,03-17 09:49:33.060  1016  1040 W libprocessgroup: failed to open /acct/uid_10025/pid_2437/cgroup.procs: No such file or directory
,03-17 09:49:33.060  2333  3152 D Mms/MessagingNotification: remove alarm
,03-17 09:49:33.070  1311  3281 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-17 09:49:33.080  1016  1231 D ActivityManager: startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,03-17 09:49:33.090  1242  3044 V MediaScanner: processDirectory :  /storage/emulated/0
,03-17 09:49:33.090  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.090  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.090  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.090  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.110  3282  3282 E Zygote  : MountEmulatedStorage()
03-17 09:49:33.110  3282  3282 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:33.110  3282  3282 E Zygote  : v2
03-17 09:49:33.110  3282  3282 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:33.110  1016  1231 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3282 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 09:49:33.110  3282  3282 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:33.110  1016  1503 D ActivityManager: getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,03-17 09:49:33.110  3282  3282 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:33.110  3282  3282 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:33.110  1016  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.110  1016  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.110  1016  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.110  1016  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.110  1242  3044 D MediaScanner: Skipping:
03-17 09:49:33.110  1242  3044 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
,03-17 09:49:33.120  1242  3044 D MediaScanner: Skipping:
03-17 09:49:33.120  1242  3044 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,03-17 09:49:33.140  3282  3282 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 09:49:33.140  3282  3282 D ActivityThread: Added TimaKeyStore provider,
,03-17 09:49:33.140  1016  1503 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3293 uid=10150 gids={50150, 9997} abi=armeabi-v7a
,03-17 09:49:33.150  3293  3293 E Zygote  : MountEmulatedStorage()
,03-17 09:49:33.150  3293  3293 E Zygote  : v2
03-17 09:49:33.150  3293  3293 I libpersona: KNOX_SDCARD checking this for 10150
03-17 09:49:33.150  3293  3293 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:33.150  3293  3293 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:33.150  3293  3293 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:33.150  3293  3293 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 09:49:33.160  1242  3044 V MediaScanner: processDirectory :  /storage/extSdCard
03-17 09:49:33.160  1242  3044 W MediaScanner: Error opening directory, reason : Permission denied.
03-17 09:49:33.160  1242  3044 W MediaScanner: 7klwibgf7fxlKdCbid7
,03-17 09:49:33.170  3293  3293 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:33.180  1242  3044 V MediaScanner:  prescan time: 190ms (DB items: 27)
03-17 09:49:33.180  1242  3044 V MediaScanner:     scan time: 74ms (Caching mode: true), (makeEntry time: 40ms ~54%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 09:49:33.180  1242  3044 V MediaScanner: postscan time: 16ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 09:49:33.180  1242  3044 V MediaScanner:    total time: 280ms
03-17 09:49:33.180  1242  3044 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
,03-17 09:49:33.180  3293  3293 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:33.190  2957  3197 D jxcore_app_log: JniHelper::setJavaVM(0xb7e7e450), pthread_self() = -1203949784
,03-17 09:49:33.190  3282  3282 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 09:49:33.200  2671  2671 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2671) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,03-17 09:49:33.200  2671  2671 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2671) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,03-17 09:49:33.200  2671  2671 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2671) ...
,03-17 09:49:33.200  2671  2671 D FactoryTestApp: [Support$Values.getString](2671) id=MODEL_COMMUNICATION_MODE, value=gsm
,03-17 09:49:33.200  2671  2671 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2671) mConnectionMode = gsm
,03-17 09:49:33.210  2671  2671 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2671) Create IPCWriterToSecPhoneService
,03-17 09:49:33.210  2671  2671 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2671)  
03-17 09:49:33.210  2957  3197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 09:49:33.210  2957  3197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 09:49:33.210  2957  3197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 09:49:33.210  2957  3197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 09:49:33.210  2957  3197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 09:49:33.210  2957  3197 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ff4693 added. We now have 1 listener(s)
,03-17 09:49:33.210  2671  2671 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-17 09:49:33.210  2693  2779 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-17 09:49:33.210  1016  1077 D ActivityManager: bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
03-17 09:49:33.210  1016  1077 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-17 09:49:33.210  1016  1077 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:33.220  1016  1077 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 09:49:33.220  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,03-17 09:49:33.220  2957  3197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,03-17 09:49:33.220  2957  3197 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,03-17 09:49:33.220  2957  3197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-17 09:49:33.220  2957  3197 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
03-17 09:49:33.220  2957  3197 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 09:49:33.220  2957  3197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 09:49:33.220  3262  3262 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 09:49:33.230  2957  3197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 09:49:33.230  2957  3197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 09:49:33.230  2957  3197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 09:49:33.230  2957  3197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
03-17 09:49:33.230  2957  3197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 09:49:33.230  2957  3197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 09:49:33.230  2957  3197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: MANUFACTURER_DATA
03-17 09:49:33.230  2957  3197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 09:49:33.230  2957  3197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 09:49:33.230  2957  3197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 09:49:33.230  2957  3197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 09:49:33.230  2957  3197 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@371c01ce added. We now have 1 listener(s)
,03-17 09:49:33.230  2957  3197 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 09:49:33.240  1242  3044 D MediaScannerService: !@done scanning volume external
,03-17 09:49:33.250  2693  2779 D BluetoothMediaBrowser: no now playing list
,03-17 09:49:33.250  2693  2779 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-17 09:49:33.260  2957  3197 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 09:49:33.260  2957  3197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 09:49:33.260  2957  3197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 09:49:33.260  2957  3197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 09:49:33.260  2957  3197 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 09:49:33.260  2957  3197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 09:49:33.270  2957  3197 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,03-17 09:49:33.270  2734  2750 W art     : Suspending all threads took: 5.547ms
,03-17 09:49:33.280  2957  3197 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 09:49:33.280  2957  3197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 09:49:33.280  2957  3197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 09:49:33.280  2957  3197 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 09:49:33.280  2957  3197 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 09:49:33.280  2957  3197 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 09:49:33.280  2957  3197 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 09:49:33.280  2957  3197 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 09:49:33.280  2957  3197 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-17 09:49:33.280  2957  3197 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 09:49:33.290  2957  2957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 09:49:33.290  2957  2957 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 09:49:33.340  2957  2957 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 09:49:33.400  3282  3282 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 09:49:33.430  1016  1717 I art     : Explicit concurrent mark sweep GC freed 17825(915KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 3.921ms total 285.907ms
,03-17 09:49:33.460  2671  2671 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2671) connected done
,03-17 09:49:33.460  2671  2671 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2671) Send Response Message to SecPhone
03-17 09:49:33.460  2671  2671 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2671) Response ��
,03-17 09:49:33.470  1463  1702 D TP/SmsProvider: query,matched:0, calling pid = 2333
,03-17 09:49:33.490  1016  1718 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,03-17 09:49:33.490  1814  1814 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 09:49:33.500   326  1073 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
,03-17 09:49:33.500  1016  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.500  1016  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 09:49:33.500  1463  1702 D TP/SmsProvider: match 0:Elapsed time : 38.031 ms
03-17 09:49:33.500  1016  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.500  1016  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.520  2671  2671 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2671) Send BOOTING COMPLETED done
,03-17 09:49:33.530  3320  3320 E Zygote  : MountEmulatedStorage()
,03-17 09:49:33.530  3320  3320 E Zygote  : v2
03-17 09:49:33.530  3320  3320 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:33.530  3320  3320 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:33.530  3320  3320 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:33.530  3218  3218 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,03-17 09:49:33.530  3320  3320 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 09:49:33.530  1016  1718 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3320 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 09:49:33.530  3320  3320 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:33.540  3218  3218 D [0]UMC:AdminManager: init - start
,03-17 09:49:33.570  3320  3320 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:33.570  3320  3320 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:33.600   326  1073 D AT_Distributor: SetAtdStatus(), 1_1_0
03-17 09:49:33.600   326  1073 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 09:49:33.610  1814  1814 I SamsungIME: KeybaordView init() : load resources
,03-17 09:49:33.610  3218  3218 D [0]UMC:AdminManager: loadAdmins
,03-17 09:49:33.610  2333  3152 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 1350.920677
,03-17 09:49:33.620  3320  3320 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 09:49:33.620  3282  3282 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 09:49:33.640  1016  1231 I ActivityManager: Killing 2519:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
,03-17 09:49:33.640  3218  3218 D [0]UMC:AdminManager: init - end
,03-17 09:49:33.650  3218  3218 D GSLBManager: migrateStoredUrlFromOldPref
,03-17 09:49:33.650  3282  3282 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-17 09:49:33.650  3282  3282 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-17 09:49:33.660  3218  3218 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,03-17 09:49:33.660   330   330 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 09:49:33.660  3218  3218 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 09:49:33.670  3218  3218 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 09:49:33.670  3218  3218 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 09:49:33.670  3218  3218 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 09:49:33.670  3218  3218 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 09:49:33.670  1016  1340 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,03-17 09:49:33.670  1016  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.670  1016  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.670  1016  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.670  1016  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.680  1016  1718 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 09:49:33.680  3218  3218 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
,03-17 09:49:33.680  3218  3218 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 09:49:33.690  1814  1814 I SamsungIME: getCurrentKeyboard
,03-17 09:49:33.690  1814  1814 I SamsungIME: getTextKeyboard
,03-17 09:49:33.690  3218  3218 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 09:49:33.700  3339  3339 E Zygote  : MountEmulatedStorage()
03-17 09:49:33.700  3339  3339 E Zygote  : v2
03-17 09:49:33.700  3339  3339 I libpersona: KNOX_SDCARD checking this for 10086
03-17 09:49:33.700  3339  3339 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:33.700  3339  3339 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:33.700  1016  1340 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3339 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,03-17 09:49:33.700  1016  1340 I ActivityManager: Killing 2536:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,03-17 09:49:33.700  3339  3339 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:33.710  3339  3339 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 09:49:33.710  1016  1029 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
,03-17 09:49:33.710  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 09:49:33.710  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:33.710  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:33.710  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 09:49:33.720  1814  1814 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 09:49:33.720  3339  3339 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:33.720  3339  3339 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:33.740  3218  3218 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,03-17 09:49:33.740  3218  3218 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-17 09:49:33.740  3218  3218 D [0]UMC:CoreReceiver:  check PreETag 
,03-17 09:49:33.770  3218  3218 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-17 09:49:33.770  3218  3218 V [0]UMC:ProfileStorage: Enter loadList
,03-17 09:49:33.770  3218  3218 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
03-17 09:49:33.770  3218  3218 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 09:49:33.770  3218  3218 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 09:49:33.770  3218  3218 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 09:49:33.770  3218  3218 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 09:49:33.770  3218  3218 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 09:49:33.770  1016  1028 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 09:49:33.770  3218  3218 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-17 09:49:33.770  3218  3218 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 09:49:33.780  3218  3218 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 09:49:33.800  3262  3262 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 09:49:33.810  3262  3262 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 09:49:33.810  1016  1231 I ActivityManager: Killing 2569:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-17 09:49:33.820  3218  3218 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-17 09:49:33.820  3218  3218 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
,03-17 09:49:33.820  3218  3218 I [0]UMC:Core: shutdown
,03-17 09:49:33.820  1016  1718 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 09:49:33.820  1016  1718 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:33.820  1016  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:33.820  1016  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 09:49:33.830  1016  1040 W libprocessgroup: failed to open /acct/uid_10088/pid_2519/cgroup.procs: No such file or directory
,03-17 09:49:33.840  3262  3262 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-17 09:49:33.840  3218  3218 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-17 09:49:33.840  3218  3218 I art     : System.exit called, status: 0
,03-17 09:49:33.840  3218  3218 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-17 09:49:33.860  3262  3262 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,03-17 09:49:33.860  3262  3262 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,03-17 09:49:33.860  3262  3262 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 09:49:33.870  1016  1718 E Tethering: No numeric data
,03-17 09:49:33.880  3339  3339 E UpdateRequestReceiver: ignoring update request
,03-17 09:49:33.880  1016  1340 E Tethering: No numeric data
,03-17 09:49:33.880  1016  1726 E Tethering: No numeric data
,03-17 09:49:33.890  3282  3282 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-17 09:49:33.890  1016  1521 E Tethering: No numeric data
,03-17 09:49:33.890  3282  3282 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-17 09:49:33.890  3339  3339 E UpdateRequestReceiver: ignoring update request
,03-17 09:49:33.890  1016  1040 W libprocessgroup: failed to open /acct/uid_10142/pid_2536/cgroup.procs: No such file or directory
03-17 09:49:33.890  1016  1040 W libprocessgroup: failed to open /acct/uid_10139/pid_2569/cgroup.procs: No such file or directory
,03-17 09:49:33.890  3282  3282 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-17 09:49:33.900  1016  1231 E Tethering: No numeric data
,03-17 09:49:33.900  1016  1029 E Tethering: No numeric data
,03-17 09:49:33.910  1016  1340 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3218)(adj 0) has died(196,1066)
,03-17 09:49:33.910  1016  1718 D ActivityManager: startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
,03-17 09:49:33.910  1016  1718 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 09:49:33.910  1016  1718 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:33.910  1016  1718 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 09:49:33.910  1016  1718 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 09:49:33.920  3282  3282 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 09:49:33.930  1333  1333 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 09:49:33.940  3339  3339 E UpdateRequestReceiver: ignoring update request
,03-17 09:49:33.940  3282  3282 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-17 09:49:33.940  1333  1333 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 09:49:33.950  3339  3339 E UpdateRequestReceiver: ignoring update request
,03-17 09:49:33.950  1187  1187 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-17 09:49:33.950  1187  1187 D OverheatReceiver: into the SAFE_MODE_ACTION
03-17 09:49:33.950  1187  1187 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-17 09:49:33.950  1333  1333 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 09:49:33.960  1187  1187 D OverheatReceiver: isSafeMode = false
,03-17 09:49:33.960  3282  3282 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-17 09:49:33.960  1333  1333 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 09:49:33.970  3339  3339 E UpdateRequestReceiver: ignoring update request
,03-17 09:49:33.970  1016  1029 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,03-17 09:49:33.980  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.980  1463  1463 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-17 09:49:33.980  1333  1333 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 09:49:33.980  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.980  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.990  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.990  1333  1333 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
03-17 09:49:33.990  1016  1503 D SettingsProvider: name = internet_call_settings_visibility
03-17 09:49:33.990  1016  1503 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:33.990  1016  1503 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:33.990  1016  1503 D SettingsProvider: selectionArgs: false
03-17 09:49:33.990  1016  1503 D SettingsProvider: selectionArgs: 1001
03-17 09:49:33.990  1016  1503 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:33.990  1016  1503 D SettingsProvider: ret = -1
03-17 09:49:33.990  1463  1463 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 09:49:33.990  1333  1333 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 09:49:33.990  1333  1333 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 09:49:33.990  1333  1333 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 09:49:33.990  1333  1333 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 09:49:33.990  1333  1333 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-17 09:49:33.990  1333  1333 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-17 09:49:33.990  1311  3281 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1],
03-17 09:49:33.990  1311  3281 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 09:49:33.990  3339  3339 E UpdateRequestReceiver: ignoring update request,
,03-17 09:49:34.010  1016  1029 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3374 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 09:49:34.010  3374  3374 E Zygote  : MountEmulatedStorage()
03-17 09:49:34.010  3374  3374 E Zygote  : v2
03-17 09:49:34.010  3374  3374 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:34.010  3374  3374 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:34.020  3374  3374 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 09:49:34.020  1439  1439 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false ,
,03-17 09:49:34.030  3374  3374 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 09:49:34.030  1016  1718 E Tethering: No numeric data
,03-17 09:49:34.030  3374  3374 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 09:49:34.030  1016  1328 D ActivityManager: startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
03-17 09:49:34.030  1016  1717 D SettingsProvider: name = aw_daemon_service_key_version_check
,03-17 09:49:34.030  1016  1717 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:34.030  1016  1717 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:34.030  1016  1717 D SettingsProvider: selectionArgs: false,
03-17 09:49:34.030  1016  1717 D SettingsProvider: selectionArgs: 10162
03-17 09:49:34.030  1016  1717 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:34.030  1016  1717 D SettingsProvider: ret = -1
,03-17 09:49:34.040  1016  1077 E Tethering: No numeric data
,03-17 09:49:34.040  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.040  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.050  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.050  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.060  1016  1521 E Tethering: No numeric data
,03-17 09:49:34.060  3374  3374 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:34.060  3374  3374 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:34.060  1016  1717 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-17 09:49:34.080  1016  1328 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3390 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 09:49:34.080  1016  1328 I ActivityManager: Killing 2476:com.example.hello/u0a174 (adj 15): empty #31
,03-17 09:49:34.080  3390  3390 E Zygote  : MountEmulatedStorage()
03-17 09:49:34.080  3390  3390 E Zygote  : v2
03-17 09:49:34.080  3390  3390 I libpersona: KNOX_SDCARD checking this for 10092
03-17 09:49:34.080  3390  3390 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:34.080  3390  3390 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:34.090  3390  3390 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:34.090  3282  3282 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 09:49:34.090  1333  1333 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 09:49:34.090  3390  3390 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 09:49:34.090  1016  1503 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
03-17 09:49:34.090  1016  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-17 09:49:34.090  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 09:49:34.100  1333  1333 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 09:49:34.100  1333  1333 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 09:49:34.100  1333  1333 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 09:49:34.100  1333  1333 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
03-17 09:49:34.100   317   317 I art     : Explicit concurrent mark sweep GC freed 8784(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 657us total 32.416ms
03-17 09:49:34.100  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:34.100  1016  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:34.100  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 09:49:34.100  1333  1333 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 09:49:34.120   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 17.017ms
,03-17 09:49:34.130  1016  1077 E Tethering: No numeric data
,03-17 09:49:34.130  1016  1028 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
03-17 09:49:34.130  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-17 09:49:34.130  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:34.130  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:34.130  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 09:49:34.130  3282  3282 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-17 09:49:34.130  3390  3390 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:34.130  3390  3390 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:34.140  1016  1521 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,03-17 09:49:34.140  1333  1333 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
03-17 09:49:34.140  1016  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.140  1333  1333 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 09:49:34.140  1016  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.140  1016  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.140  1016  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.140  1333  1333 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458204574146
,03-17 09:49:34.140  1333  1333 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458226140000
,03-17 09:49:34.140  1333  1333 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-17 09:49:34.140  1333  1333 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-17 09:49:34.140   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 693us total 21.520ms
,03-17 09:49:34.160  3282  3282 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
03-17 09:49:34.160  3282  3282 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
03-17 09:49:34.160  3282  3282 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-17 09:49:34.160  3282  3282 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
03-17 09:49:34.160  2957  3313 W jxcore-log: Initializing JXcore engine
03-17 09:49:34.160  2957  3313 W jxcore-log: JXcore engine is ready
03-17 09:49:34.160  3282  3282 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
03-17 09:49:34.160  3282  3282 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-17 09:49:34.180  3405  3405 E Zygote  : MountEmulatedStorage(),
03-17 09:49:34.180  3405  3405 E Zygote  : v2
03-17 09:49:34.180  3405  3405 I libpersona: KNOX_SDCARD checking this for 10057
03-17 09:49:34.180  3405  3405 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:34.180  3405  3405 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 09:49:34.190  1016  1521 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3405 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
03-17 09:49:34.190  3282  3282 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,03-17 09:49:34.190  3405  3405 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:34.190  1439  1439 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-17 09:49:34.200  3405  3405 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 09:49:34.200  3282  3335 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-17 09:49:34.200  3282  3282 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-17 09:49:34.210  1333  1333 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458226140000
,03-17 09:49:34.210  1016  1726 V VibratorService: hasVibrator - useVibetonz: true
,03-17 09:49:34.230  1929  1929 E audit   : type=1400 msg=audit(1458204574.220:205): avc:  denied  { ioctl } for  pid=3313 comm="Thread-369" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
03-17 09:49:34.230  1929  1929 E audit   :  SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:34.230  1929  1929 E audit   : type=1300 msg=audit(1458204574.220:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9b83b8f8 items=0 ppid=317 ppcomm=main pid=3313 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-369" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 09:49:34.230  1929  1929 E audit   : type=1320 msg=audit(1458204574.220:205): ,
,03-17 09:49:34.230  3282  3282 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-17 09:49:34.230  1311  3281 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 09:49:34.240  3282  3335 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 09:49:34.240  1016  1328 V VibratorService: hasVibrator - useVibetonz: true
,03-17 09:49:34.240  3405  3405 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:34.240  3405  3405 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:34.240  3282  3282 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-17 09:49:34.240  3282  3335 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 ,
03-17 09:49:34.240  3282  3282 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-17 09:49:34.250  3282  3282 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-17 09:49:34.250  1333  1333 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 42
,03-17 09:49:34.250  1333  1333 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458226140000
,03-17 09:49:34.250  2957  3313 W jxcore-log: Starting JXcore engine
,03-17 09:49:34.260  3282  3282 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-17 09:49:34.260  1016  1028 D ActivityManager: bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
,03-17 09:49:34.270  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 09:49:34.270  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:34.270  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:34.270  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 09:49:34.290  3282  3282 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 09:49:34.290  1016  1231 V VibratorService: hasVibrator - useVibetonz: true
,03-17 09:49:34.310  1016  1340 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-17 09:49:34.310  1016  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.310  1016  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.310  1016  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.310  1016  1340 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.320  3422  3422 E Zygote  : MountEmulatedStorage(),
03-17 09:49:34.330  3422  3422 E Zygote  : v2
,03-17 09:49:34.330  3422  3422 I libpersona: KNOX_SDCARD checking this for 10009
,03-17 09:49:34.330  3422  3422 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:34.330  1311  3281 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
03-17 09:49:34.330  3282  3282 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] ,
03-17 09:49:34.330  1016  1340 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3422 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 09:49:34.330  3422  3422 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:34.330  1333  1333 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,03-17 09:49:34.330  1333  1333 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 09:49:34.330  3422  3422 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:34.340  3422  3422 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 09:49:34.340  1016  1231 D ActivityManager: startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,03-17 09:49:34.340  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.340  3062  3062 E BluetoothHeadset: BTStateChangeCB is registed
,03-17 09:49:34.350  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.350  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.350  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.350  3062  3062 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-17 09:49:34.360  3435  3435 E Zygote  : MountEmulatedStorage()
03-17 09:49:34.360  3435  3435 E Zygote  : v2
03-17 09:49:34.360  3435  3435 I libpersona: KNOX_SDCARD checking this for 10166
03-17 09:49:34.360  3435  3435 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:34.370  3435  3435 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 09:49:34.370  1016  1231 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3435 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 09:49:34.370  3435  3435 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:34.370  1016  1521 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,03-17 09:49:34.370  1016  1521 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
03-17 09:49:34.370  3435  3435 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 09:49:34.370  1016  1521 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:34.370  1016  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:34.370  1016  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-17 09:49:34.370  3422  3422 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:34.370  3422  3422 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:34.390  3062  3062 E BluetoothHeadset: BluetoothHeadset service is binded
,03-17 09:49:34.390  3062  3062 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-17 09:49:34.390  1016  1077 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
03-17 09:49:34.390  1016  1077 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,03-17 09:49:34.390  1016  1077 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:34.390  1016  1077 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:34.390  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-17 09:49:34.410  3435  3435 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:34.410  3435  3435 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:34.410  2957  3313 W jxcore-log: Platform android
03-17 09:49:34.410  2957  3313 W jxcore-log: 
,03-17 09:49:34.420  2957  3313 W jxcore-log: Process ARCH arm
03-17 09:49:34.420  2957  3313 W jxcore-log: 
,03-17 09:49:34.440   281   682 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
,03-17 09:49:34.440   281   682 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 09:49:34.440   281   682 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 09:49:34.440   281   682 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 09:49:34.440   281   682 I str_params: key: 'call_forwarding' value: ''
,03-17 09:49:34.440  1989  1989 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 09:49:34.440  1989  1989 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-17 09:49:34.440  1989  1989 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-17 09:49:34.440  3282  3335 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-17 09:49:34.450  1989  1989 D ScoverManager: serviceVersion : 16908288
,03-17 09:49:34.450  1016  1726 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 09:49:34.450  1989  1989 D InCall  : InCallUtils - isCoverClosed false
,03-17 09:49:34.450  1439  1439 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-17 09:49:34.450  1016  1521 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 09:49:34.450  1989  1989 D InCall  : InCallUtils - isCoverClosed false
,03-17 09:49:34.450  1989  1989 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-17 09:49:34.450  1989  1989 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-17 09:49:34.460  1989  1989 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-17 09:49:34.470  1989  1989 I InCall  : CallSContextMotion - stopPutDownListening
,03-17 09:49:34.470  1989  1989 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 09:49:34.470  1187  1187 D PhoneStatusBarView: setCallBackground:0
,03-17 09:49:34.480  1016  1503 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 09:49:34.480  1989  1989 D InCall  : InCallUtils - isCoverClosed false
,03-17 09:49:34.520  3062  3062 D BluetoothA2dp: Proxy object connected
,03-17 09:49:34.530  1311  3281 D ScoverManager: serviceVersion : 16908288
,03-17 09:49:34.600  1016  1040 W libprocessgroup: failed to open /acct/uid_10174/pid_2476/cgroup.procs: No such file or directory
,03-17 09:49:34.630  1016  2786 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 09:49:34.670  1989  1989 D VideoCallManager: Instantiating VideoCallManager
,03-17 09:49:34.680  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 09:49:34.680  1989  1989 I GFX construct_block_size_descriptor_2d second part: took 2.131667ms for 0*0 texture 0
,03-17 09:49:34.680  1989  1989 I GFX generate_partition_tables: took 5.021771ms for 0*0 texture 0
,03-17 09:49:34.690  1989  1989 I GFX raster: took 11.102708ms for 176*144 texture 0
,03-17 09:49:34.690  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8249540 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8261750 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 09:49:34.700  3374  3374 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-17 09:49:34.700  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
03-17 09:49:34.700  3374  3374 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-17 09:49:34.700  2957  3313 I jxcore-log: JXcore Cordova bridge is ready!
03-17 09:49:34.700  2957  3313 I jxcore-log: 
,03-17 09:49:34.700  2957  3313 W jxcore-log: JXcore engine is started
,03-17 09:49:34.710  1989  1989 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 09:49:34.710  1989  1989 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 09:49:34.710  1989  1989 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 09:49:34.710  1989  1989 I Adreno-EGL: Local Branch: 
03-17 09:49:34.710  1989  1989 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 09:49:34.710  1989  1989 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 09:49:34.710  1989  1989 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 09:49:34.710  2957  3197 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 09:49:34.710  2957  2957 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 09:49:34.730  2957  3313 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 09:49:34.730  2957  3313 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 09:49:34.730  3374  3454 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 09:49:34.730  2957  2957 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-17 09:49:34.740  2957  2957 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 09:49:34.740  1016  1029 D FocusedStackFrame: Set to : 0
03-17 09:49:34.740  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 09:49:34.740  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 09:49:34.740  1016  1029 D InputDispatcher: Focused application set to: xxxx
03-17 09:49:34.740  1989  1989 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 09:49:34.740  1016  1029 D InputDispatcher: Focus left window: 2957
03-17 09:49:34.750  3374  3454 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
03-17 09:49:34.750   256   447 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (216 us)
03-17 09:49:34.750  1989  1989 I glCompressedTexImage2D: took 0.274688ms for 320*61440 texture 37809
,03-17 09:49:34.760  3374  3374 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-17 09:49:34.760  1989  1989 I draw setup: took 11.049688ms for 320*240 texture 37809
03-17 09:49:34.760  1989  1989 E GFX GPU raster: drawn
,03-17 09:49:34.760  3374  3374 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 09:49:34.760  1989  1989 I GFX GPU raster ASTC: took 41.460573ms for 320*240 texture 12
03-17 09:49:34.760  1989  1989 I GFX raster: took 41.546145ms for 320*240 texture 0
03-17 09:49:34.760  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8261750 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8263a90 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 09:49:34.770  1016  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 09:49:34.770  1016  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 09:49:34.780  1016  1328 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
03-17 09:49:34.780  1016  1328 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-17 09:49:34.780  2957  3197 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 40ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 09:49:34.780  1016  1328 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:34.780  1016  1328 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 09:49:34.780  1016  1328 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 09:49:34.780  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.780  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.780  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.780  1016  1328 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.780  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 09:49:34.790  1989  1989 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 09:49:34.790  1989  1989 I glCompressedTexImage2D: took 0.370052ms for 480*122880 texture 37813
03-17 09:49:34.790  1989  1989 I draw setup: took 0.771041ms for 480*640 texture 37813
03-17 09:49:34.790  1989  1989 E GFX GPU raster: drawn
,03-17 09:49:34.800  1989  1989 I GFX GPU raster ASTC: took 7.186040ms for 480*640 texture 12
03-17 09:49:34.800  1989  1989 I GFX raster: took 7.270207ms for 480*640 texture 0
03-17 09:49:34.800  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8263a90 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8491f20 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 09:49:34.810  3459  3459 E Zygote  : MountEmulatedStorage()
,03-17 09:49:34.810  1016  1328 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3459 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 09:49:34.810  3459  3459 E Zygote  : v2
03-17 09:49:34.810  3459  3459 I libpersona: KNOX_SDCARD checking this for 10092
03-17 09:49:34.810  3459  3459 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 09:49:34.810  3459  3459 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:34.810  3459  3459 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:34.810  1016  1717 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 09:49:34.810  3459  3459 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 09:49:34.810  1016  1717 W ActivityManager: mDVFSHelper.acquire()
,03-17 09:49:34.830  1016  1717 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-17 09:49:34.830  1016  1717 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 09:49:34.830  1016  1717 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-17 09:49:34.840  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-17 09:49:34.840  1016  1016 D SensorService: [SO] activate (ident=0xb8493fa0, enabled=0)
,03-17 09:49:34.840  1016  1016 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 09:49:34.850  1016  1016 D SensorManager: unregisterListener ::   
,03-17 09:49:34.850  1016  1016 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-17 09:49:34.850  1016  1016 D SensorService: [SO] changed settle time [0]
,03-17 09:49:34.860  1016  1016 D SensorService: [SO] setDelay [200000000]
,03-17 09:49:34.860  1016  1016 D SensorService: [SO] activate (ident=0xb8738c48, enabled=1)
03-17 09:49:34.860  1016  1016 D SensorService: [SO] AR_init
03-17 09:49:34.860  1016  1016 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 09:49:34.860  1487  1487 D Launcher: onRestart, Launcher: 941173783
,03-17 09:49:34.860  1016  1016 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-17 09:49:34.870  1487  1487 D Launcher: onStart, Launcher: 941173783
03-17 09:49:34.870  1487  1487 D Launcher.HomeView: onStart
,03-17 09:49:34.870  1487  1487 D Launcher: onResume, Launcher: 941173783
,03-17 09:49:34.870  3459  3459 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:34.870  1016  1231 D SettingsProvider: name = kids_home_mode
03-17 09:49:34.870  1016  1231 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:34.870  1016  1231 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:34.870  1016  1231 D SettingsProvider: selectionArgs: false
03-17 09:49:34.870  1016  1231 D SettingsProvider: selectionArgs: 10007
03-17 09:49:34.870  1016  1231 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:34.870  1016  1231 D SettingsProvider: ret = -1
03-17 09:49:34.870  3459  3459 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:34.870  1487  1487 D Launcher.HomeView: onResume
,03-17 09:49:34.880  1487  1487 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 09:49:34.880  1487  1487 D MenuAppsGridFragment: onResume
,03-17 09:49:34.880  1016  1328 D ActivityManager: handle home activity for 0
03-17 09:49:34.880  1016  1328 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 09:49:34.880  1016  1328 D KnoxTimeoutHandler: post home show event for user 0
03-17 09:49:34.880  1016  1328 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 09:49:34.880  1016  1328 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 09:49:34.880  1016  1328 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 09:49:34.880  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 09:49:34.880  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 09:49:34.880  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 09:49:34.880  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 09:49:34.890   256   256 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-17 09:49:34.890  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 09:49:34.890  1016  1029 D InputDispatcher: Focus entered window: 1487
,03-17 09:49:34.900  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-17 09:49:34.900  1989  1989 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 09:49:34.900  1016  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
,03-17 09:49:34.900  1016  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 09:49:34.900  1989  1989 I glCompressedTexImage2D: took 0.386563ms for 440*116864 texture 37809
03-17 09:49:34.900  1989  1989 I draw setup: took 0.810000ms for 440*330 texture 37809,
03-17 09:49:34.900  1989  1989 E GFX GPU raster: drawn
,03-17 09:49:34.910  1487  1487 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
03-17 09:49:34.910  1989  1989 I GFX GPU raster ASTC: took 4.610833ms for 440*330 texture 12
03-17 09:49:34.910  1989  1989 I GFX raster: took 4.674010ms for 440*330 texture 0
,03-17 09:49:34.910  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8491f20 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb84a6310 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 09:49:34.920  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 09:49:34.920  1487  1487 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 09:49:34.930  1016  1503 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 09:49:34.940  1187  1187 D PanelView: There is/are notification(s) 
,03-17 09:49:34.940  2957  2957 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 09:49:34.940  1016  3486 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 09:49:34.940  1814  1814 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 09:49:34.950  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-17 09:49:34.950  1989  1989 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 09:49:34.950  1989  1989 I glCompressedTexImage2D: took 0.572239ms for 480*163840 texture 37811
03-17 09:49:34.950  1989  1989 I draw setup: took 0.931302ms for 480*640 texture 37811
03-17 09:49:34.950  1989  1989 E GFX GPU raster: drawn
,03-17 09:49:34.960  1989  1989 I GFX GPU raster ASTC: took 5.950731ms for 480*640 texture 12
03-17 09:49:34.960  1989  1989 I GFX raster: took 6.040678ms for 480*640 texture 0
03-17 09:49:34.960  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8496120 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb84a5e48 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 09:49:34.980  1487  1487 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1bb5b46b time:40445
,03-17 09:49:34.980  1016  1049 D PersonaManager: isKioskContainerExistOnDevice
,03-17 09:49:34.990  3374  3454 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-17 09:49:35.020  1016  1049 I ActivityManager: Displayed Component not be shown by security: +196ms
,03-17 09:49:35.020  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 09:49:35.020  1989  1989 I GFX construct_block_size_descriptor_2d second part: took 2.310834ms for 0*0 texture 0
,03-17 09:49:35.030  1989  1989 I GFX generate_partition_tables: took 7.586198ms for 0*0 texture 0
,03-17 09:49:35.030  1989  1989 I GFX raster: took 11.896043ms for 176*144 texture 0
03-17 09:49:35.030  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb848f7e0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb848f900 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 09:49:35.050   289   289 E SMD     : DCD OFF
,03-17 09:49:35.060  1016  1038 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 09:49:35.060  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 09:49:35.060  1989  1989 I GFX construct_block_size_descriptor_2d second part: took 2.206094ms for 0*0 texture 0
,03-17 09:49:35.070  1989  1989 I GFX generate_partition_tables: took 6.294166ms for 0*0 texture 0
,03-17 09:49:35.070  1989  1989 I GFX raster: took 10.606511ms for 176*144 texture 0
03-17 09:49:35.070  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb848fb20 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb848fac0 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 09:49:35.070  3465  3465 D AndroidRuntime: 
03-17 09:49:35.070  3465  3465 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 09:49:35.070  1989  1989 D ScoverManager: registerListener
03-17 09:49:35.070  3465  3465 D AndroidRuntime: CheckJNI is OFF
03-17 09:49:35.070  3465  3465 D AndroidRuntime: readGMSProperty: start
03-17 09:49:35.070  3465  3465 D AndroidRuntime: readGMSProperty: already setted!!
03-17 09:49:35.070  3465  3465 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 09:49:35.070  3465  3465 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 09:49:35.070  3465  3465 D AndroidRuntime: readGMSProperty: end
03-17 09:49:35.070  3465  3465 D AndroidRuntime: addProductProperty: start
,03-17 09:49:35.100  1016  1340 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 09:49:35.100  1016  1726 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 09:49:35.100  1016  1726 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@145b6c45, pid : 1989, uid : 1001, type : 1
,03-17 09:49:35.100  1989  1989 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 09:49:35.140  3374  3374 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true],
03-17 09:49:35.140  1311  3281 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 09:49:35.140  1016  1029 I ActivityManager: Killing 2598:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,03-17 09:49:35.160  1311  3281 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-17 09:49:35.160  3374  3374 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false],
,03-17 09:49:35.170  3374  3374 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] ,
,03-17 09:49:35.170  3282  3335 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED,
,03-17 09:49:35.190  3390  3390 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 09:49:35.190  3374  3374 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 09:49:35.210  3282  3335 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 09:49:35.220  1016  1040 W libprocessgroup: failed to open /acct/uid_10068/pid_2598/cgroup.procs: No such file or directory
03-17 09:49:35.220  3435  3477 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 09:49:35.220  3435  3477 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 09:49:35.230  1016  1077 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 09:49:35.230  1016  1077 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:35.230  1016  1077 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 09:49:35.230  1016  1077 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 09:49:35.240  1016  2892 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 09:49:35.260  1016  1038 D SensorService: [SO] currT = 40720108942, prevT = 40240108421, diff = 480000521, [0.134 0.421 10.132]
03-17 09:49:35.260  1016  1038 D SensorService: [SO] 0.134 0.421 10.132
03-17 09:49:35.260  1016  1038 D SensorService: [SO] [100 -> 255]
,03-17 09:49:35.290  3465  3465 E AffinityControl: AffinityControl: registerfunction enter
,03-17 09:49:35.290  3374  3374 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-17 09:49:35.290  3390  3390 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-17 09:49:35.290  3435  3477 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 09:49:35.310  3465  3465 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-17 09:49:35.310  1016  1041 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 09:49:35.320  1311  1325 W art     : Suspending all threads took: 16.770ms
,03-17 09:49:35.320  1016  1041 W ActivityManager: mDVFSHelper.release()
03-17 09:49:35.320  3282  3335 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
03-17 09:49:35.320  1016  1041 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11,
03-17 09:49:35.320  3282  3335 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 09:49:35.330  1016  1340 D PackageManager: START PACKAGE DELETE: observer{54641900}
03-17 09:49:35.330  1016  1340 D PackageManager: pkg{<packageName>}
03-17 09:49:35.330  1016  1340 D PackageManager: user{0}
03-17 09:49:35.330  1016  1340 D PackageManager: caller{2000}
03-17 09:49:35.330  1016  1340 D PackageManager: flags{2}
03-17 09:49:35.330  1016  1340 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-17 09:49:35.330  1016  1340 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-17 09:49:35.330  1016  1340 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-17 09:49:35.330  1016  1340 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 09:49:35.330  1016  1340 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-17 09:49:35.330  1016  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-17 09:49:35.330  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-17 09:49:35.330  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-17 09:49:35.330  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
03-17 09:49:35.330  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-17 09:49:35.330  1016  1057 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,03-17 09:49:35.340  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg,
03-17 09:49:35.340  1016  1041 I ActivityManager: Killing 2957:com.test.thalitest/u0a155 (adj 1): stop com.test.thalitest cause uninstall pkg,
,03-17 09:49:35.390  3374  3454 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 09:49:35.400  3435  3477 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 09:49:35.400  3435  3477 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@556fa83: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 09:49:35.400  3435  3477 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 09:49:35.400  3390  3390 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-17 09:49:35.410  3374  3454 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 09:49:35.420  3390  3390 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-17 09:49:35.420  3390  3390 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-17 09:49:35.430   256  1851 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-17 09:49:35.430   256   445 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 09:49:35.450  3390  3390 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-17 09:49:35.470  3390  3390 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 09:49:35.490  3374  3454 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-17 09:49:35.490  3374  3454 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-17 09:49:35.490  3374  3454 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-17 09:49:35.530  3374  3454 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-17 09:49:35.540  3374  3454 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 09:49:35.550  3374  3454 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 09:49:35.550  3374  3455 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 09:49:35.550  3374  3454 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-17 09:49:35.560  3374  3455 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 09:49:35.560  3374  3454 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-17 09:49:35.570  3374  3455 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 09:49:35.570  3374  3454 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,03-17 09:49:35.570  3374  3455 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 09:49:35.570  3374  3454 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/17/09:49:35
,03-17 09:49:35.570  3374  3455 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 09:49:35.570  3374  3454 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-17 09:49:35.570  3374  3455 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 09:49:35.580  3374  3454 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-17 09:49:35.590  3374  3455 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 09:49:35.590  1814  3348 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 09:49:35.590  3374  3455 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-17 09:49:35.590  3374  3455 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 09:49:35.590  3374  3455 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 09:49:35.620  1016  1016 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 09:49:35.620  3374  3455 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 09:49:35.630  3374  3455 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-17 09:49:35.660  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,03-17 09:49:35.660  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.660  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.660  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.660  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:35.670  3514  3514 E Zygote  : MountEmulatedStorage(),
,03-17 09:49:35.670  3514  3514 E Zygote  : v2
03-17 09:49:35.670  3514  3514 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:35.670  3514  3514 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:35.680  3514  3514 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 09:49:35.680  3514  3514 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:35.680  3514  3514 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:35.680  1016  1029 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3514 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 09:49:35.680  1016  1029 I ActivityManager: Killing 2654:com.android.calendar/u0a135 (adj 15): empty #31
,03-17 09:49:35.680  1016  1029 I ActivityManager: Killing 2458:com.samsung.android.securitylogagent/1000 (adj 15): empty #32
,03-17 09:49:35.680  1016  1029 I ActivityManager: Killing 2614:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #33
,03-17 09:49:35.690  1016  1231 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,03-17 09:49:35.690  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.690  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.690  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.690  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:35.700  3514  3514 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:35.700  3514  3514 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:35.710  3529  3529 E Zygote  : MountEmulatedStorage()
03-17 09:49:35.710  3529  3529 I libpersona: KNOX_SDCARD checking this for 10015
03-17 09:49:35.710  3529  3529 E Zygote  : v2
03-17 09:49:35.710  3529  3529 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:35.710  3529  3529 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 09:49:35.710  3529  3529 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:35.710  3529  3529 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 09:49:35.710  1016  1231 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3529 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-17 09:49:35.720  1016  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{17da8a86 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:41183
,03-17 09:49:35.720  1016  1503 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 09:49:35.730  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:35.730  1016  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 09:49:35.730  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:35.740  1016  1717 D LocationManagerService: getProviders()=[passive]
,03-17 09:49:35.740  3529  3529 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:35.740  3529  3529 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:35.750  3390  3390 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 09:49:35.750  1016  1057 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,03-17 09:49:35.780  3374  3454 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-17 09:49:35.830  3514  3514 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
03-17 09:49:35.830  1016  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-17 09:49:35.840  3390  3390 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-17 09:49:35.860  3514  3514 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 09:49:35.860  3514  3514 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 09:49:35.860  3514  3514 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 09:49:35.890  1016  1040 W libprocessgroup: failed to open /acct/uid_10135/pid_2654/cgroup.procs: No such file or directory
03-17 09:49:35.890  1016  1040 W libprocessgroup: failed to open /acct/uid_1000/pid_2458/cgroup.procs: No such file or directory
03-17 09:49:35.890  1016  1040 W libprocessgroup: failed to open /acct/uid_10069/pid_2614/cgroup.procs: No such file or directory
,03-17 09:49:35.910  1016  1718 D ActivityManager: getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,03-17 09:49:35.910  1016  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.910  1016  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.910  1016  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.910  1016  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:35.920  3557  3557 E Zygote  : MountEmulatedStorage(),
03-17 09:49:35.920  3557  3557 E Zygote  : v2
03-17 09:49:35.920  3557  3557 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 09:49:35.920  3557  3557 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:35.920  3557  3557 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:35.930  1016  1718 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3557 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 09:49:35.930  1016  3510 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-17 09:49:35.930  1016  3510 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-17 09:49:35.930  1016  3510 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:35.930  1016  3510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 09:49:35.930  1016  3510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 09:49:35.940  3557  3557 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:35.940  3557  3557 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:35.950  3374  3454 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1,
03-17 09:49:35.950  3374  3455 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 09:49:35.980  1016  1103 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 09:49:36.000  3374  3455 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,03-17 09:49:36.000  3557  3557 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:36.000  3557  3557 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:36.010  1836  2111 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 09:49:36.010  1814  1814 E SamsungIME: mOCRHelper is null
,03-17 09:49:36.030  1463  1463 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 09:49:36.040  1016  1128 V NetworkStats: removeUidsLocked() for UIDs [10155]
,03-17 09:49:36.040  1016  1128 V NetworkStats: performPollLocked(flags=0x3)
03-17 09:49:36.040  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 09:49:36.040  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 09:49:36.040  1016  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 09:49:36.050  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,03-17 09:49:36.050  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-17 09:49:36.050  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-17 09:49:36.050  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,03-17 09:49:36.050  1016  1016 D OTPFW   : OtpDbHelper::getInstance New instance created
,03-17 09:49:36.050  1016  1016 D OTPFW   : DBIntegrity::getInstance - New instance created
,03-17 09:49:36.060  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,03-17 09:49:36.060  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,03-17 09:49:36.060  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-17 09:49:36.060  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-17 09:49:36.060  1016  1016 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
03-17 09:49:36.060  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-17 09:49:36.060  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-17 09:49:36.060  1016  1016 V EnterpriseBillingPolicy: uID is 10155
03-17 09:49:36.060  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 09:49:36.060  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 09:49:36.060  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 09:49:36.060  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 09:49:36.060  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 09:49:36.060  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 09:49:36.060  1016  1128 V NetworkStats: performPollLocked() took 22ms
,03-17 09:49:36.070  1016  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 09:49:36.070  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 09:49:36.080  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 09:49:36.090  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,03-17 09:49:36.090  1016  2786 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-17 09:49:36.090  1016  1016 V EnterpriseBillingPolicy: uID is 10155
03-17 09:49:36.090  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
,03-17 09:49:36.090  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 09:49:36.090  3374  3454 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 09:49:36.090  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,03-17 09:49:36.090  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 09:49:36.090  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 09:49:36.090  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 09:49:36.090  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 09:49:36.100  1451  1451 D RegisteredComponentCache: Collect Tech packages for Knox
,03-17 09:49:36.110  1451  1451 D PersonaManager: isKioskContainerExistOnDevice
,03-17 09:49:36.110  1016  1726 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 09:49:36.120  1016  1726 D SecContentProvider2: mCursor = null
,03-17 09:49:36.140  3557  3557 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 09:49:36.140  3557  3557 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 09:49:36.140  3557  3557 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 09:49:36.150  1016  1340 I ActivityManager: Killing 2811:com.android.email/u0a145 (adj 15): empty #31
,03-17 09:49:36.150  1016  1340 I ActivityManager: Killing 2710:com.android.keychain/1000 (adj 15): empty #32
,03-17 09:49:36.160  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-17 09:49:36.160  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.160  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.160  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.160  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:36.170  3577  3577 E Zygote  : MountEmulatedStorage(),
03-17 09:49:36.170  3577  3577 I libpersona: KNOX_SDCARD checking this for 10003
03-17 09:49:36.170  3577  3577 E Zygote  : v2
03-17 09:49:36.170  3577  3577 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:36.170  3577  3577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:36.170  1016  1016 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3577 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-17 09:49:36.170  3577  3577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:36.170  3577  3577 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 09:49:36.180  1016  1129 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 09:49:36.180  1016  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 09:49:36.180  1016  3509 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,03-17 09:49:36.180  1016  3509 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,03-17 09:49:36.180  1016  3509 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:36.180  1016  3509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 09:49:36.180  1016  3509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 09:49:36.200  3405  3586 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 09:49:36.210  1451  1451 D PersonaManager: isKioskContainerExistOnDevice
03-17 09:49:36.210  1451  1451 D RegisteredServicesCache: empty dynamic service
03-17 09:49:36.210  3577  3577 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:36.210  3577  3577 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:36.210  3405  3586 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 09:49:36.210  3405  3586 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_hotword_models]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 09:49:36.220  1016  1040 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
03-17 09:49:36.220  1016  1040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,03-17 09:49:36.220  3557  3568 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 09:49:36.290  1016  1231 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-17 09:49:36.300  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.300  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.300  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.300  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:36.320  1016  1231 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3602 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a,
,03-17 09:49:36.320  3602  3602 E Zygote  : MountEmulatedStorage()
,03-17 09:49:36.320  3602  3602 E Zygote  : v2
03-17 09:49:36.320  3602  3602 I libpersona: KNOX_SDCARD checking this for 10094
03-17 09:49:36.320  3602  3602 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:36.330  3602  3602 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 09:49:36.330  3602  3602 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 09:49:36.330  3602  3602 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:36.350  3514  3514 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 09:49:36.360  3514  3514 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 09:49:36.360  3514  3514 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
03-17 09:49:36.360  1016  1172 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
,03-17 09:49:36.360  1016  1172 D TaskPersister: removeObsoleteFile: deleting file=12_task_thumbnail.png
,03-17 09:49:36.360  3405  3593 I SearchServiceFactory: refreshing search history.
,03-17 09:49:36.370  1016  3510 D ActivityManager: startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,03-17 09:49:36.380  1016  3510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.380  3282  3335 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
03-17 09:49:36.380  1016  3510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.380  1016  3510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.380  1016  3510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:36.390  3577  3577 D UserAnalysis.PlaceProvider: PlaceProvider onCreate(),
,03-17 09:49:36.410  3618  3618 E Zygote  : MountEmulatedStorage(),
03-17 09:49:36.410  3618  3618 E Zygote  : v2
03-17 09:49:36.410  3618  3618 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:36.410  3618  3618 I libpersona: KNOX_SDCARD not a persona,
03-17 09:49:36.410  3602  3602 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:36.410  3602  3602 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:36.410  3618  3618 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 09:49:36.410  3618  3618 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 09:49:36.420  1016  3510 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3618 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 09:49:36.420  3618  3618 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:36.430  3390  3600 I System.out: Thread-454(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 09:49:36.440  3390  3600 I System.out: Thread-454(ApacheHTTPLog):isSBSettingEnabled false
03-17 09:49:36.440  3390  3600 I System.out: Thread-454(ApacheHTTPLog):isShipBuild true
03-17 09:49:36.440  3390  3600 I System.out: Thread-454(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 09:49:36.440  3390  3600 I System.out: Thread-454(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 09:49:36.440   276   977 D EnterpriseController: uids 10092
03-17 09:49:36.440   276   977 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 09:49:36.440   276   977 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-17 09:49:36.450  1016  1503 I ActivityManager: Killing 1572:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-17 09:49:36.460  3618  3618 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:36.460  3618  3618 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:36.460  1311  3281 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 09:49:36.460  2671  3319 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3319)  
,03-17 09:49:36.460  3577  3577 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 09:49:36.470  3577  3577 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 09:49:36.470  3577  3577 D UserAnalysis: Create SecureDbHelper
,03-17 09:49:36.520  3602  3602 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 09:49:36.530  3602  3602 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 09:49:36.530  3602  3602 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-17 09:49:36.560  1487  1487 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 09:49:36.560  1487  1487 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 09:49:36.560  1487  1487 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 09:49:36.610  3435  3513 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 09:49:36.610  3435  3513 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 09:49:36.620  1016  1057 I art     : Explicit concurrent mark sweep GC freed 49254(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 30MB/45MB, paused 20.881ms total 771.488ms
,03-17 09:49:36.630  1016  1340 I art     : WaitForGcToComplete blocked for 164.669ms for cause Explicit
,03-17 09:49:36.640  1016  1057 D PackageManager: delete codoeFile: 
,03-17 09:49:36.640  1016  1057 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
03-17 09:49:36.640  1016  1057 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,03-17 09:49:36.650  1016  1057 D PackageManager: result of delete: 1{54641900}
,03-17 09:49:36.650  3465  3465 D AndroidRuntime: Shutting down VM
,03-17 09:49:36.670  1016  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 09:49:36.670  1016  1057 D PackageManager: userId{-1}
03-17 09:49:36.670  1016  1057 D PackageManager: andCode{true}
,03-17 09:49:36.680  2693  2765 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 09:49:36.680  1016  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,03-17 09:49:36.700  3639  3639 I dex2oat : ----------------------------------------------------
03-17 09:49:36.700  3639  3639 I dex2oat : <SS>: S T A R T I N G . . .
03-17 09:49:36.700  3639  3639 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 09:49:36.700  3639  3639 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads516933313.jar --oat-fd=32 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads516933313.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 09:49:36.740  3639  3639 I dex2oat : dex2oat took 36.575ms (threads: 4)
,03-17 09:49:36.780  1016  1340 I art     : Explicit concurrent mark sweep GC freed 4503(229KB) AllocSpace objects, 1(1650KB) LOS objects, 33% free, 28MB/42MB, paused 2.661ms total 155.705ms
,03-17 09:49:36.780  1016  1028 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
03-17 09:49:36.780  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 09:49:36.790  3577  3577 D IntelligenceServiceApplication: onCreate()
,03-17 09:49:36.790  3577  3577 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 09:49:36.790  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:36.790  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 09:49:36.790  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 09:49:36.800  3602  3602 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 09:49:36.800  1016  1231 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,03-17 09:49:36.800  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:36.800  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:36.800  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.810  1016  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:36.810  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
03-17 09:49:36.810  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-17 09:49:36.810  1016  1040 W TextServicesManagerService: no available spell checker services found
,03-17 09:49:36.810  3577  3577 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 09:49:36.820  3649  3649 E Zygote  : MountEmulatedStorage()
03-17 09:49:36.820  3649  3649 E Zygote  : v2
,03-17 09:49:36.820  3649  3649 I libpersona: KNOX_SDCARD checking this for 10060
03-17 09:49:36.820  3649  3649 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:36.830  3602  3602 D elm:15183: ElmAgentService : onCreate()
,03-17 09:49:36.830  3602  3648 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 09:49:36.830  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:36.830  3649  3649 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:36.830  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 09:49:36.830  1016  1231 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3649 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 09:49:36.840  3649  3649 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 09:49:36.840  3649  3649 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:36.850  1016  1231 I ActivityManager: Killing 2510:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,03-17 09:49:36.860   317   317 I art     : Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 25.337ms
,03-17 09:49:36.860  3465  3465 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 09:49:36.880   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 683us total 22.821ms
,03-17 09:49:36.880  1016  3508 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0,
,03-17 09:49:36.890  3649  3649 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:36.890  3649  3649 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:36.890  3577  3577 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 09:49:36.900   317   317 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 18.465ms
,03-17 09:49:36.910  1426  1426 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 09:49:36.910  3602  3602 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,03-17 09:49:36.920  3602  3602 D elm:15183: BootCompletedState : startBootCompleted() call
,03-17 09:49:36.920  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:36.920  3602  3602 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 09:49:36.930  3602  3602 I elm:15183: Get License : 0
03-17 09:49:36.930  3602  3602 D elm:15183: ElmAgentService : onDestroy().
,03-17 09:49:36.930  3577  3577 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-17 09:49:36.930  3577  3577 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 09:49:36.930  1016  1077 I ActivityManager: Killing 2791:com.samsung.android.sm/1000 (adj 15): empty #31
,03-17 09:49:36.940  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:36.960  1426  1426 V EmergencyMode: [EmergencyBase] setBootTime
03-17 09:49:36.960  1426  1426 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 09:49:36.960  3618  3618 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 09:49:36.960  1016  1726 D ActivityManager: startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,03-17 09:49:36.960  1016  1726 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.960  1016  1726 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.960  1016  1726 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.960  1016  1726 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:36.970  3435  3435 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 09:49:36.980  3673  3673 E Zygote  : MountEmulatedStorage(),
03-17 09:49:36.980  3673  3673 E Zygote  : v2
,03-17 09:49:36.980  3673  3673 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 09:49:36.980  3673  3673 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:36.980  3673  3673 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:36.990  3673  3673 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:36.990  3673  3673 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:36.990  3618  3618 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 09:49:36.990  1016  1726 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3673 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 09:49:37.000  1016  3510 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 09:49:37.000  1016  3510 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:37.000  1016  3510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 09:49:37.000  1016  3510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.000  1016  3509 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 09:49:37.010  1016  3509 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:37.010  1016  3509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 09:49:37.010  1016  3509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.030  3673  3673 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:37.030  3673  3673 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:37.030  3435  3435 I System.out: YouTube MDX: MDX video stage moved to NEW
,03-17 09:49:37.030  3435  3435 I System.out: YouTube MDX: MDX video player state moved to UNSTARTED
,03-17 09:49:37.030  3435  3435 I System.out: YouTube MDX: MDX ad player state moved to UNSTARTED
,03-17 09:49:37.050  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 09:49:37.050  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:37.060  3405  3593 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 09:49:37.060  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:37.060  3557  3568 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 09:49:37.070  3618  3618 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 09:49:37.080  3618  3618 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 09:49:37.090  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:37.100  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 09:49:37.100  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 09:49:37.100  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 09:49:37.100  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:37.100  3405  3593 I LibraryLoader: Time to load native libraries: 14 ms (timestamps 2551-2565)
,03-17 09:49:37.100  3405  3593 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 09:49:37.110  3673  3673 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-17 09:49:37.120  3673  3673 I testFeature: Feature.Feature(context)
03-17 09:49:37.120  3673  3673 I testFeature: Feature.readInternalDefaultXml()
,03-17 09:49:37.120  3673  3673 I testFeature: ResetFeatureValue
03-17 09:49:37.120  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 09:49:37.120  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:37.120  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 09:49:37.120  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 09:49:37.130  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:37.130  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 09:49:37.130  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 09:49:37.130  3673  3673 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 09:49:37.130  3673  3673 I CameraApp: CameraApp.getAppFeature()...
,03-17 09:49:37.130  1016  3509 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,03-17 09:49:37.130  1016  3509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.130  1016  3509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.130  1016  3509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.130  1016  3509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.130  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 09:49:37.130  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 09:49:37.140  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:37.140  3405  3593 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,03-17 09:49:37.140  3405  3593 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor,
,03-17 09:49:37.150  3700  3700 E Zygote  : MountEmulatedStorage()
,03-17 09:49:37.150  3700  3700 E Zygote  : v2
03-17 09:49:37.150  3700  3700 I libpersona: KNOX_SDCARD checking this for 10100
,03-17 09:49:37.150  3700  3700 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:37.150  3700  3700 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 09:49:37.160  1016  3509 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3700 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 09:49:37.160  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest,
03-17 09:49:37.160  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-17 09:49:37.160  3700  3700 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:37.160  3700  3700 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:37.170  3649  3649 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-17 09:49:37.180  1311  3281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 09:49:37.190  1311  3281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 09:49:37.190  1311  3281 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 09:49:37.190  3700  3700 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:37.190  3700  3700 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:37.200  3618  3618 W FileUtils: Failed to chmod(/data/data/com.fmm.ds/databases/fmmds.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-17 09:49:37.210  3649  3649 W System.err: java.io.FileNotFoundException: /data/data/com.samsung.android.scloud.backup/files/FileSavedList/SPAM_processedKey: open failed: EROFS (Read-only file system)
03-17 09:49:37.210  1016  3508 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
03-17 09:49:37.210  3649  3649 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 09:49:37.210  3649  3649 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-17 09:49:37.210  3649  3649 W System.err: 	at java.io.FileWriter.<init>(FileWriter.java:58)
03-17 09:49:37.210  3649  3649 W System.err: 	at com.samsung.android.scloud.backup.util.FileSavedList.<init>(FileSavedList.java:61)
03-17 09:49:37.210  3649  3649 W System.err: 	at com.samsung.android.scloud.backup.util.FileSavedList.load(FileSavedList.java:27)
03-17 09:49:37.210  3649  3649 W System.err: 	at com.samsung.android.scloud.backup.core.BNRManager.clearPreRestoredData(BNRManager.java:89)
03-17 09:49:37.210  3649  3649 W System.err: 	at com.samsung.android.scloud.backup.model.ModelManager.initBNRManager(ModelManager.java:90)
03-17 09:49:37.210  3649  3649 W System.err: 	at com.samsung.android.scloud.backup.SCloudBackupReceiver.onReceive(SCloudBackupReceiver.java:86)
03-17 09:49:37.210  3649  3649 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 09:49:37.210  3649  3649 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 09:49:37.210  3649  3649 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 09:49:37.210  3649  3649 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.210  3649  3649 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.210  3649  3649 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.210  3649  3649 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.210  3649  3649 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.210  3649  3649 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.210  3649  3649 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.210  3649  3649 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-17 09:49:37.210  3618  3618 E SQLiteLog: (28) failed to open "/data/data/com.fmm.ds/databases/fmmds.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.210  3649  3649 W System.err: 	at libcore.io.Posix.open(Native Method)
03-17 09:49:37.210  3649  3649 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 09:49:37.210  3649  3649 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 09:49:37.210  3649  3649 W System.err: 	... 17 more
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: FileSavedList err
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: java.io.FileNotFoundException: /data/data/com.samsung.android.scloud.backup/files/FileSavedList/SPAM_processedKey: open failed: EROFS (Read-only file system)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at java.io.FileWriter.<init>(FileWriter.java:58)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at com.samsung.android.scloud.backup.util.FileSavedList.<init>(FileSavedList.java:61)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at com.samsung.android.scloud.backup.util.FileSavedList.load(FileSavedList.java:27)
03-17 ,09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at com.samsung.android.scloud.backup.core.BNRManager.clearPreRestoredData(BNRManager.java:89)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at com.samsung.android.scloud.backup.model.ModelManager.initBNRManager(ModelManager.java:90)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at com.samsung.android.scloud.backup.SCloudBackupReceiver.onReceive(SCloudBackupReceiver.java:86)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at libcore.io.Posix.open(Native Method)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 09:49:37.210  3649  3649 E BNR_ERR-FileSavedList_SPAM_processedKey: 	... 17 more
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: Failed to open database '/data/data/com.fmm.ds/databases/fmmds.db'.
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:4,9:37.210  3618  3618 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileNameExistsRow(XDBActivedProfileQuery.java:342)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileExistsRow(XDBActivedProfileQuery.java:214)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:77)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.210  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.220  1016  3508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: Couldn't open fmmds.db for writing (will try read-only):
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileNameExistsRow(XDBActivedProfileQuery.java:342)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileExistsRow(XDBActivedProfileQuery.java:214)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:77)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.210  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.220  1016  3508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.220  3618  3618 W SQLiteOpenHelper: Opened fmmds.db in read-only mode
03-17 09:49:37.220  1016  3508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.220  3618  3618 E SQLiteLog: (28) failed to open "/data/data/com.fmm.ds/databases/fmmds.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.220  1016  3508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: Failed to open database '/data/data/com.fmm.ds/databases/fmmds.db'.
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileIdExistsRow(XDBActivedProfileQuery.java:477)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileExistsRow(XDBActivedProfileQuery.java:218)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:77)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.220  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: Couldn't open fmmds.db for writing (will try read-only):
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileIdExistsRow(XDBActivedProfileQuery.java:477)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileExistsRow(XDBActivedProfileQuery.java:218)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:77)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.220  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.230  3618  3618 W SQLiteOpenHelper: Opened fmmds.db in read-only mode
03-17 09:49:37.230  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.230  3618  3618 E SQLiteLog: (28) failed to open "/data/data/com.fmm.ds/databases/fmmds.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: Failed to open database '/data/data/com.fmm.ds/databases/fmmds.db'.
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileFetchRow(XDBActivedProfileQuery.java:143)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:84)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.230  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: Couldn't open fmmds.db for writing (will try read-only):
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileFetchRow(XDBActivedProfileQuery.java:143)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:84)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.230  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.230  3618  3618 W SQLiteOpenHelper: Opened fmmds.db in read-only mode
03-17 09:49:37.240  3618  3618 E SQLiteLog: (28) failed to open "/data/data/com.fmm.ds/databases/fmmds.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.240  3719  3719 E Zygote  : MountEmulatedStorage()
03-17 09:49:37.240  3719  3719 I libpersona: KNOX_SDCARD checking this for 10062
03-17 09:49:37.240  3719  3719 E Zygote  : v2
03-17 09:49:37.240  3719  3719 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: Failed to open database '/data/data/com.fmm.ds/databases/fmmds.db'.
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileNameFetchRow(XDBActivedProfileQuery.java:303)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileFetchRow(XDBActivedProfileQuery.java:175)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:84)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.240  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: Couldn't open fmmds.db for writing (will try read-only):
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileNameFetchRow(XDBActivedProfileQuery.java:303)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileFetchRow(XDBActivedProfileQuery.java:175)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:84)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.240  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.240  1016  3508 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3719 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 09:49:37.240  3719  3719 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 09:49:37.240  1016  3508 I ActivityManager: Killing 2915:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-17 09:49:37.250  3719  3719 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:37.250  1016  1503 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 09:49:37.250  3618  3618 W SQLiteOpenHelper: Opened fmmds.db in read-only mode
03-17 09:49:37.250  3719  3719 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:37.250  1016  1503 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:37.250  1016  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 09:49:37.250  1016  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
03-17 09:49:37.250  3618  3618 E SQLiteLog: (28) failed to open "/data/data/com.fmm.ds/databases/fmmds.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: Failed to open database '/data/data/com.fmm.ds/databases/fmmds.db'.
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileIdFetchRow(XDBActivedProfileQuery.java:438)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileFetchRow(XDBActivedProfileQuery.java:176)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:84)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.250  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: Couldn't open fmmds.db for writing (will try read-only):
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileIdFetchRow(XDBActivedProfileQuery.java:438)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBActivedProfileQuery.xdbActivedProfileFetchRow(XDBActivedProfileQuery.java:176)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:84)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.250  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.250  3618  3618 W SQLiteOpenHelper: Opened fmmds.db in read-only mode
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.260  3618  3618 E SQLiteLog: (28) failed to open "/data/data/com.fmm.ds/databases/fmmds.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.260  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.260  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: Failed to open database '/data/data/com.fmm.ds/databases/fmmds.db'.
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDBNetworkProfileQuery.xdbNetworkProfileExistsRow(XDBNetworkProfileQuery.java:244)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:91)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.260  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: Couldn't open fmmds.db for writing (will try read-only):
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBNetworkProfileQuery.xdbNetworkProfileExistsRow(XDBNetworkProfileQuery.java:244)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:91)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.260  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.260  3618  3618 W SQLiteOpenHelper: Opened fmmds.db in read-only mode
03-17 09:49:37.260  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.260  3719  3719 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.270  3618  3618 E SQLiteLog: (28) failed to open "/data/data/com.fmm.ds/databases/fmmds.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: Failed to open database '/data/data/com.fmm.ds/databases/fmmds.db'.
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDBNetworkProfileQuery.xdbNetworkProfileFetchRow(XDBNetworkProfileQuery.java:162)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:98)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.270  3618  3618 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: Couldn't open fmmds.db for writing (will try read-only):
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBNetworkProfileQuery.xdbNetworkProfileFetchRow(XDBNetworkProfileQuery.java:162)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:98)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.270  3618  3618 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.270  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.270  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.270  3618  3618 W SQLiteOpenHelper: Opened fmmds.db in read-only mode
03-17 09:49:37.270  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.280  3700  3700 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
03-17 09:49:37.280  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.280  3618  3618 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.280  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.280  3719  3719 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:37.280  3700  3700 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
03-17 09:49:37.290  1016  1717 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
03-17 09:49:37.290  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.290  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.290  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.290  1016  1717 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.290  1016  1717 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.290  1016  1717 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.290  1016  1717 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.300  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.300  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.300  3618  3618 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-17 09:49:37.300  3618  3618 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
03-17 09:49:37.300  3618  3618 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-17 09:49:37.300  3618  3618 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
03-17 09:49:37.310  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.310  3618  3618 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.310  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.310  3618  3618 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
03-17 09:49:37.310  3740  3740 E Zygote  : MountEmulatedStorage()
03-17 09:49:37.310  3740  3740 I libpersona: KNOX_SDCARD checking this for 10101
03-17 09:49:37.310  3740  3740 E Zygote  : v2
03-17 09:49:37.310  3740  3740 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:37.310  3740  3740 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 09:49:37.310  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.320  1016  1717 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3740 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 09:49:37.320  1016  1717 I ActivityManager: Killing 2208:flipboard.app/u0a98 (adj 15): empty #31
03-17 09:49:37.320  3740  3740 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 09:49:37.320  3740  3740 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 09:49:37.320  1016  1040 W libprocessgroup: failed to open /acct/uid_1000/pid_2710/cgroup.procs: No such file or directory
03-17 09:49:37.330  1016  1040 W libprocessgroup: failed to open /acct/uid_10145/pid_2811/cgroup.procs: No such file or directory
03-17 09:49:37.330  1016  1040 W libprocessgroup: failed to open /acct/uid_10072/pid_1572/cgroup.procs: No such file or directory
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.330  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.330  1016  1040 W libprocessgroup: failed to open /acct/uid_10044/pid_2510/cgroup.procs: No such file or directory
03-17 09:49:37.330  1016  1040 W libprocessgroup: failed to open /acct/uid_1000/pid_2791/cgroup.procs: No such file or directory
,03-17 09:49:37.330  1016  1028 I ActivityManager: Killing 2998:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-17 09:49:37.330  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 09:49:37.340  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.340  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 09:49:37.340  3719  3719 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.scloud.sync/databases/smemofiletracker.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.340  3740  3740 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:37.340  3740  3740 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.340  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 09:49:37.340  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.340  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 09:49:37.350  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 09:49:37.350  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 09:49:37.350  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 09:49:37.350  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 09:49:37.350  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.350  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 09:49:37.350  3719  3719 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.scloud.sync/databases/smemofiletracker.db'.
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at com.sec.android.sCloudSync.Providers.SMemoFileTracker.onCreate(SMemoFileTracker.java:75)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 09:49:37.350  3719  3719 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/,write mode.
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.350  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.350  3422  3422 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 09:49:37.360  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 09:49:37.360  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.360  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 09:49:37.360  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.360  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 09:49:37.360  3422  3422 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 09:49:37.370  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.370  3422  3422 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 09:49:37.370  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 09:49:37.370  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 09:49:37.370  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.370  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 09:49:37.380  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 09:49:37.380  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 09:49:37.380  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 09:49:37.380  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.380  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 09:49:37.380  3282  3335 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 09:49:37.390  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30),
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
,03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source),
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 09:49:37.390  3719  3719 I SMemoFileTracker: Runtime Exception when creating DB not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.390  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.390  3719  3719 I ExternalOEMControlProvider: onCreate
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:49:37.390  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.390  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 09:49:37.400  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:49:37.400  2639  3260 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-17 09:49:37.400  2639  3260 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-17 09:49:37.400  1016  1718 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast

```
