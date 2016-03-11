#### Test 625481247756efd_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
I/qcom-bluetooth( 3119): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
--------- beginning of system
D/WifiP2pService( 1020): InactiveState{ what=143415 }
D/WifiP2pService( 1020): P2pEnabledState{ what=143415 }
D/WifiP2pService( 1020): DefaultState{ what=143415 }
D/Tethering( 1020): Boot complete.
V/EnterpriseBillingEngine( 1020): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1020): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1020): getCurrentActiveProfiles - start - 
D/WIFI_P2P( 1020): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/WIFI_P2P( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
I/qcom-bluetooth( 3121): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/ConnectivityService( 1020): Got NetworkFactory Messenger for WIFI_P2P
E/WifiStateMachine( 1020): Blacklist file delete
I/qcom-bluetooth( 3122): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
D/ConnectivityService( 1020): Got NetworkFactory Messenger for WIFI
I/qcom-bluetooth( 3123): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
V/EnterpriseBillingPolicyStorage( 1020): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1020): handleAllprofiles - end
I/qcom-bluetooth( 3124): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
D/UsbHostNotification( 1020): boot completed
D/UsbHostRestrictor( 1020): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1020): initSetUsbBlock STARTED
,D/WIFI    ( 1020): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/WIFI    ( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/UsbHostRestrictor( 1020): SIM was never inserted
D/UsbHostRestrictor( 1020): writableHostSysNode[false]
D/UsbHostRestrictor( 1020): Can NOT Write Disable Sys Node to [ON]
D/PersonaManagerService( 1020): ACTION_BOOT_COMPLETED
E/PersonaManagerServiceHandler( 1020):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
E/ConnectivityChangeReceiver( 2131): Ignoring connectivity change
D/UsbStorageNotification( 1020): boot completed
D/KnoxKeyguardUpdateMonitor( 1020): onBootComplete
I/KnoxKeyguardUpdateMonitor( 1020): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1020): onTrustChanged user:0, enable:false
D/StorageNotification( 1178): boot completed
D/KeyguardViewMediator( 1178): onTrustChanged( Showing = false , userId = 0 )
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
D/GpsLocationProvider( 1020): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
D/GpsLocationProvider_ex( 1020): BOOT_COMPLETED native_init 
D/ConnectivityManager( 2131): CallingUid : 10011, CallingPid : 2131
D/GpsLocationProvider( 1020): set_capabilities_callback: 55u
D/ConnectivityService( 1020): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1020): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1020): apparently satisfied.  currentScore=60
D/ConnectivityService( 1020): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
D/SensorService( 1020): [SO] currT = 38581043000, prevT = 38151359000, diff = 429684000, [-0.421 0.172 9.902]
D/SensorService( 1020): [SO] -0.421 0.172 9.902
D/SensorService( 1020): [SO] [100 -> 255]
D/ConnectivityManager.CallbackHandler( 2131): CM callback handler got msg 524290
E/LocSvc_api_v02( 1020): I/locClientOpen:2279]: Service instance id is -1
E/Geofence_Adapter( 1020): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1020): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1020): BOOT_COMPLETED native_cleanup 
D/StatusBarManagerService( 1020): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
D/PhoneStatusBar( 1178): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/qcom-bluetooth( 3140): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
E/Zygote  ( 3142): MountEmulatedStorage()
E/Zygote  ( 3142): v2
I/libpersona( 3142): KNOX_SDCARD checking this for 1000
I/libpersona( 3142): KNOX_SDCARD not a persona
I/qcom-bluetooth( 3141): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/ActivityManager( 1020): Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=3142 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3142): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/bt_vendor( 2972): bluetooth satus is on
D/bt_userial_mct( 2972): userial_open(port:0)
I/bt_vendor( 2972): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 2972): Done intiailizing UART
I/bt_vendor( 2972): Done intiailizing UART
I/bt_userial_mct( 2972): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 2972): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 2972): Entering userial_read_thread()
I/art     (  305): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 42.712ms
W/art     ( 2694): Attempt to remove local handle scope entry from IRT, ignoring
D/TimaKeyStoreProvider( 3142): TimaSignature is unavailable
D/ActivityThread( 3142): Added TimaKeyStore provider
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 16.686ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.791ms
I/        ( 2972): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2972): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2972): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2972): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2972): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2972): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2972): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2972): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2972): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2972): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2972): BTE_InitTraceLevels -- TRC_SAP
I/        ( 2972): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2972): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2972): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2972): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2972): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 2972): BTE_InitTraceLevels -- TRC_PROTOCOL
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
D/qmi_secgps_clnt( 1020): qmi_secgps_client_init()
W/ContextImpl( 3142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
I/splitIntent( 1020): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=126, mSplitNum[2]=164, mBgSplitQueueNum=3 divideNum= 37 r.nextReceiver= 50 receivers.size=201
I/splitIntent( 1020): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/qmi_secgps_clnt( 1020): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
D/qmi_secgps_clnt( 1020): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
D/qmi_secgps_clnt( 1020): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
E/Zygote  ( 3170): MountEmulatedStorage()
E/Zygote  ( 3170): v2
I/libpersona( 3170): KNOX_SDCARD checking this for 10097
I/libpersona( 3170): KNOX_SDCARD not a persona
I/SELinux ( 3170): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=3170 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3170): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3170): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10117
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3187): MountEmulatedStorage()
E/Zygote  ( 3187): v2
I/libpersona( 3187): KNOX_SDCARD checking this for 10081
I/libpersona( 3187): KNOX_SDCARD not a persona
D/TimaKeyStoreProvider( 3170): TimaSignature is unavailable
I/ActivityManager( 1020): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=3187 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3187): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/SELinux ( 3187): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3187): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 3170): Added TimaKeyStore provider
W/bt-l2cap( 2972): l2c_link_processs_ble_num_bufs 16
E/Zygote  ( 3200): MountEmulatedStorage()
E/Zygote  ( 3200): v2
I/libpersona( 3200): KNOX_SDCARD checking this for 1101
I/libpersona( 3200): KNOX_SDCARD not a persona
I/SELinux ( 3200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3200 uid=1101 gids={41101, 9997} abi=armeabi-v7a
E/bt-btm  ( 2972): BTM_SecRegister:p_cb_info->p_le_callback == 0xa446dead 
E/bt-btm  ( 2972): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa446dead 
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
E/SELinux ( 3200): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BluetoothAdapterProperties( 2972): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
E/bt-btif ( 2972): BTA got event 0x122b
E/bt-btif ( 2972):                : sec: 0x80, service name [] (up to 21 ch
D/BluetoothAdapterProperties( 2972): Address is:08:EC:A9:50:76:27
E/BluetoothServiceJni( 2972): populateRssiValuesNative
I/bluedroid( 2972): getModelRssiValues
E/BluetoothServiceJni( 2972): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 2972): modelRssiValuesCallback, low, mid, high = -70,-60,127
D/TimaKeyStoreProvider( 3187): TimaSignature is unavailable
D/ActivityThread( 3187): Added TimaKeyStore provider
I/GAV2    ( 2694): Thread[GAThread,5,main]: No campaign data found.
D/BluetoothAdapterProperties( 2972): Name is: Thali Test (Galaxy A3)
D/BluetoothAdapterProperties( 2972): Scan Mode:20
D/BluetoothAdapterProperties( 2972): Discoverable Timeout:120
D/SettingsProvider( 1020): name = bluetooth_name
D/BluetoothAdapterProperties( 2972): LE Address is:C8:D9:53:A0:EC:4E
E/bt-btif ( 2972): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2972): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 2972): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 2972): btif_sock_init: !vhci_init
D/IOP_DB_BT( 2972): db_open: file /etc/bluetooth/iop_bt.db
E/bt_mct  ( 2972): hci lib postload completed
I/ActivityManager( 1020): Killing 2471:com.sec.modem.settings/1000 (adj 15): empty #31
D/IOP_DB_BT( 2972): db_open: db_open : handle 3028377616l, read 13894 bytes onto local cache
D/IOP_DB_BT( 2972): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 2972): db_query: result 1
I/        ( 2972): iop_db_open: iop_db_open status 0
D/bte_conf( 2972): Device ID record 1 : primary
D/bte_conf( 2972):   vendorId            = 0075
D/bte_conf( 2972):   vendorIdSource      = 0001
D/bte_conf( 2972):   product             = 0100
D/bte_conf( 2972):   version             = 0200
D/bte_conf( 2972):   clientExecutableURL = 
D/bte_conf( 2972):   serviceDescription  = 
D/bte_conf( 2972):   documentationURL    = 
D/bte_conf( 2972): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 2972): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
E/LocSvc_utils_cfg( 1020): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
D/BluetoothAdapterState( 2972): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2972): ScanMode =  20
D/BluetoothAdapterProperties( 2972): State =  11
D/SecContentProvider( 1020): uri = 3 selection = isDiscoverableEnabled
D/TimaKeyStoreProvider( 3200): TimaSignature is unavailable
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
D/ActivityThread( 3200): Added TimaKeyStore provider
D/BluetoothAdapterProperties( 2972): Setting state to 12
I/BluetoothAdapterState( 2972): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties( 2972): Scan Mode:21
D/BluetoothAdapterProperties( 2972): Discoverable Timeout:120
D/SettingsProvider( 1020): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1002
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
I/qmi_secgps_clnt( 1020): SECGPS: Set AGPS Mode : 7
W/ResourcesManager( 3187): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3187): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3187): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/qmi_secgps_clnt( 1020): SECGPS: send a qmi message to secgps_server OK
W/ResourcesManager( 3187): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3187): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1020): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
W/ResourcesManager( 3200): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
D/BluetoothAdapterService( 2972): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2972): updateAdapterState state is 12
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1020): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
D/BluetoothA2dp( 1020): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 2972): Autoconnection is available 
D/BluetoothAdapterService( 2972): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 2972): starting service from this receiver
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothAdapterState( 2972): Entering On State from state = 11
D/BluetoothA2dp( 2972): onBluetoothStateChange: up=true
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
D/BluetoothAdapter( 2972): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2972): onBluetoothStateChange: Bluetooth is on
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/qmi_secgps_clnt( 1020): SECGPS: Set XTRA enable : 1
D/BluetoothAdapter( 1178): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1178): onBluetoothStateChange: Bluetooth is on
D/qmi_secgps_clnt( 1020): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1020): SECGPS: Set GNSS RF CONFIG : 1
D/qmi_secgps_clnt( 1020): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1020): SECGPS: Set CERT TYPE : 15
D/BluetoothAdapter( 1461): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1461): onBluetoothStateChange: Bluetooth is on
D/qmi_secgps_clnt( 1020): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1020): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
D/BluetoothAdapter( 1472): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1472): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1840): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1840): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1482): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1482): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1020): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1020): onBluetoothStateChange: Bluetooth is on
V/SmartcardService( 3200): main Received broadcast
V/SmartcardService( 3200): Starting smartcard service after boot completed
W/InputMethodManagerService( 1020): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1020): [BT Setting State] State =12
I/InputMethodManagerService( 1020): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/BluetoothTile( 1178):  onBluetoothStateChange:
D/BluetoothTile( 1178): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1178):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1178):  getBluetoothState : 12
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
I/SamsungIME( 1851): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
W/DriveInitializer( 2131): Awaiting to be initialized
W/DriveInitializer( 2131): Background init thread started
V/DownloadManager( 1227): onReceive intent + android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/BluetoothTile( 1178):  handleUpdatestate:false name:null
D/BluetoothTile( 1178):  handleUpdatestate:false name:null
D/BluetoothTile( 1178):  handleUpdatestate:false name:null
I/ActivityManager( 1020): Killing 2495:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
D/StatusBarManagerService( 1020): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/StatusBarManagerService( 1020): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1178): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
D/SecContentProvider2( 1020): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1020): mCursor = null
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1020): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
E/LocSvc_ApiV02( 1020): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
E/LocSvc_ApiV02( 1020): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3227): MountEmulatedStorage()
E/Zygote  ( 3227): v2
I/libpersona( 3227): KNOX_SDCARD checking this for 1000
I/libpersona( 3227): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=3227 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3227): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3227): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3227): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3227): TimaSignature is unavailable
D/ActivityThread( 3227): Added TimaKeyStore provider
D/SSRM:a  ( 1020): DeviceInfo:: 000000000000
D/SSRM:a  ( 1020): SettingsAirViewInfo:: 000000000
W/ContextImpl( 3227): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
I/BluetoothPbapService( 2972): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
D/BluetoothHeadset( 1461): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@14e58b79, true
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2471/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10127/pid_2495/cgroup.procs: No such file or directory
D/BluetoothHeadset( 1461): registerMessageListener
D/MediaScannerReceiver( 1227): action: android.intent.action.BOOT_COMPLETED
D/HeadsetService( 2972): registerMessageListener
D/HeadsetService( 2972): registerMessageListener
D/HeadsetStateMachine( 2972): Disconnected process message: 70
I/Telecom ( 1461): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1461): BluetoothPhoneService: updateHeadsetWithCallState
D/HeadsetStateMachine( 2972): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@4de26ed
I/Telecom ( 1461): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1461): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1461): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3245): MountEmulatedStorage()
E/Zygote  ( 3245): v2
I/libpersona( 3245): KNOX_SDCARD checking this for 10153
I/libpersona( 3245): KNOX_SDCARD not a persona
I/SELinux ( 3245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3245): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3245 uid=10153 gids={50153, 9997} abi=armeabi-v7a
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/HeadsetStateMachine( 2972): Disconnected process message: 9
D/HeadsetStateMachine( 2972): mNumActive: 0 mNumHeld: 0 mCallState: 6
E/ActivityThread( 3170): Failed to find provider info for flipboard.auth.internal.debug
I/BluetoothPbapService( 2972): Handler(): got msg=1
D/SecContentProvider( 1020): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/AndroidRuntime( 3132): 
D/AndroidRuntime( 3132): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/ActivityThread( 3170): Failed to find provider info for flipboard.auth.internal
D/AndroidRuntime( 3132): CheckJNI is OFF
D/AndroidRuntime( 3132): readGMSProperty: start
D/AndroidRuntime( 3132): readGMSProperty: already setted!!
D/AndroidRuntime( 3132): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3132): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3132): readGMSProperty: end
D/AndroidRuntime( 3132): addProductProperty: start
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/audio_hw_primary(  284): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  284): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  284): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  284): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  284): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  284): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  284): adev_set_parameters: exit
E/HeadsetStateMachine( 2972): terminateScoUsingVirtualVoiceCall:No present call to terminate
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2131): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3245): TimaSignature is unavailable
D/ActivityThread( 3245): Added TimaKeyStore provider
E/Zygote  ( 3260): MountEmulatedStorage()
I/ActivityManager( 1020): Start proc flipboard.app for content provider flipboard.app/flipboard.remoteservice.UserContentProvider: pid=3260 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 3260): v2
I/libpersona( 3260): KNOX_SDCARD checking this for 10096
I/SELinux ( 3260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3260): KNOX_SDCARD not a persona
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/SELinux ( 3260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3260): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/BluetoothPbapService( 2972): PBAP Service initSocket try: 0
D/BluetoothMapMasInstance( 2972): set MAP SDP message type : 1
D/TimaKeyStoreProvider( 3260): TimaSignature is unavailable
D/ActivityThread( 3260): Added TimaKeyStore provider
D/SettingsProvider( 1020): name = next_alarm_formatted
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10081
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
W/ResourcesManager( 3245): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/SettingsProvider( 1020): ret = -1
W/BluetoothAdapter( 2972): getBluetoothService() called with no BluetoothManagerCallback
W/BluetoothAdapter( 2972): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 2972): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 2972): bindListen(), new LocalSocket 
D/BluetoothSocket( 2972): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2972): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e64b970
D/BluetoothSocket( 2972): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 2972): bindListen(), new LocalSocket 
D/BluetoothSocket( 2972): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2972): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e0344e9
D/BluetoothSocket( 2972): channel: 19
D/BluetoothSocket( 2972): channel: 5
D/BluetoothPbapService( 2972): PBAP Socket is BluetoothServerSocket
D/MediaScannerService( 1227): !@start scanning volume internal: [/system/media, /oem/media]
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/MtpService( 1227): updating state; isCurrentUser=true, mMtpLocked=false
I/MultiDex( 3260): VM with version 2.1.0 has multidex support
D/TP/MmsProvider( 1482): Update uri=content://mms, match=0
I/MultiDex( 3260): install
I/MultiDex( 3260): VM has multidex support, MultiDex support library is disabled.
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/TP/MmsProvider( 1482): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1482): need read changed broadcast:false
W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10081
E/Zygote  ( 3288): MountEmulatedStorage()
E/Zygote  ( 3288): v2
I/libpersona( 3288): KNOX_SDCARD checking this for 1000
I/libpersona( 3288): KNOX_SDCARD not a persona
I/SELinux ( 3288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3288 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3288): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
I/ActivityManager( 1020): Killing 2510:com.sec.tcpdumpservice/1000 (adj 15): empty #31
I/DrmEventReceiver( 1020): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1020): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
I/DrmEventReceiver( 1020): DrmEventReceiver : beginStartingService
I/System.out( 1020): start Service
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
I/Mms:transaction( 2434): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2434): [start]    nonBlockingUpdateMessageIndicator() consume time = 7549.488383
I/Mms/ReservationManager( 2434): resetAfterConnected()
D/TimaKeyStoreProvider( 3288): TimaSignature is unavailable
D/ActivityThread( 3288): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1482): query,matched:7, calling pid = 2434
D/TP/MmsSmsProvider( 1482): match 7:Elapsed time : 7.523 ms
I/Mms/ReservationManager( 2434): getReservedSendMessageCount(): retMessageCount=0
D/WVMDrmPlugIn(  283): WVMDrmPlugin::onInitialize : 2989
D/WVMDrmPlugIn(  283): WVMDrmPlugin::onSetOnInfoListener : add 2989
D/Mms/MessagingNotification( 2434): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2434): isDefault true
D/TP/MmsProvider( 1482): Query uri=content://mms, match=0, calling pid = 2434
E/SQLiteLog( 1227): (283) recovered 274 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
D/TP/MmsSmsProvider( 1482): query,matched:200, calling pid = 2434
D/TP/MmsSmsProvider( 1482): match 200:Elapsed time : 1.367 ms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/art     ( 1020): Explicit concurrent mark sweep GC freed 237360(15MB) AllocSpace objects, 50(6MB) LOS objects, 33% free, 22MB/33MB, paused 3.798ms total 219.212ms
E/Zygote  ( 3315): MountEmulatedStorage()
E/Zygote  ( 3315): v2
I/libpersona( 3315): KNOX_SDCARD checking this for 10043
I/libpersona( 3315): KNOX_SDCARD not a persona
I/SELinux ( 3315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3315 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 3315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/Mms/SmsReceiverService( 2434): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/Mms/TelephonyPermission( 2434): isDefault true
D/Mms/SmsReceiverService( 2434): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2434): [start]    handleBootCompleted() consume time = 123.276093
D/TimaKeyStoreProvider( 3315): TimaSignature is unavailable
D/ActivityThread( 3315): Added TimaKeyStore provider
W/art     ( 3187): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 184.939ms
E/Zygote  ( 3331): MountEmulatedStorage()
I/libpersona( 3331): KNOX_SDCARD checking this for 10155
E/Zygote  ( 3331): v2
I/libpersona( 3331): KNOX_SDCARD not a persona
I/SELinux ( 3331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3331 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
I/SELinux ( 3331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Killing 2525:com.wsomacp/u0a23 (adj 15): empty #31
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 3260): Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
E/SELinux ( 3331): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DrmEventService( 1020): action event :android.intent.action.BOOT_COMPLETED
D/TimaKeyStoreProvider( 3331): TimaSignature is unavailable
D/TP/SmsProvider( 1482): query,matched:0, calling pid = 2434
D/TP/SmsProvider( 1482): match 0:Elapsed time : 1.965 ms
I/TimaServiceEventReceiver( 1020): TimaServiceEventReceiver : onReceive
D/ActivityThread( 3331): Added TimaKeyStore provider
I/ANDROID_DRM_FRWORKS_DrmManager(  283): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
D/MediaScanner( 1227): Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
W/libprocessgroup( 1020): failed to open /acct/uid_10023/pid_2525/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2510/cgroup.procs: No such file or directory
E/AffinityControl( 3132): AffinityControl: registerfunction enter
I/System.out( 3260): Reading bundled version for config.json
W/ResourcesManager( 3315): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3315): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3315): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3260): Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
I/art     ( 1482): Explicit concurrent mark sweep GC freed 35088(2MB) AllocSpace objects, 5(80KB) LOS objects, 45% free, 4MB/8MB, paused 923us total 70.329ms
E/CscReceiver( 1482): onReceive android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 3132): Calling main entry com.android.commands.am.Am
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 3331): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1482): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1482): deleteConversation threadId: 9223372036854775806
E/Zygote  ( 3370): MountEmulatedStorage()
E/Zygote  ( 3370): v2
I/libpersona( 3370): KNOX_SDCARD checking this for 10002
I/libpersona( 3370): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3370 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
I/SELinux ( 3370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CscUpdateService( 1482): onStart
E/CscUpdateService( 1482): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1482): set_CSC_version
E/CscParser( 1482): update(): xml file exist
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
I/ActivityManager( 1020): Killing 2543:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
D/TP/SmsProvider( 1482): query,matched:51, calling pid = 2434
D/TP/SmsProvider( 1482): match 51:Elapsed time : 0.795 ms
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TP/MmsSmsProvider( 1482): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1482): updateThread(), thread_id = 9223372036854775806
V/TP/MmsSmsDatabaseHelper( 1482): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1482): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1482): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1482): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1482): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1482): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1482): (284) automatic index on im_threads(normal_thread_id)
I/CscUtil ( 1482): isWifiOnly = false
I/System.out( 1482): HandDataNode = null
I/CscUpdateService( 1482): PATH_CSCNAME =CustomerDataSet.CSCName
D/TP/MmsSmsProvider( 1482): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1482): need read changed broadcast:false
I/CscUpdateService( 1482): This is normal boot : CSC not updated
D/TimaKeyStoreProvider( 3370): TimaSignature is unavailable
D/ActivityThread( 3370): Added TimaKeyStore provider
D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
E/CscParser( 1482): update(): xml file exist
W/ActivityManager( 1020): mDVFSHelper.acquire()
D/FocusedStackFrame( 1020): Set to : 0
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1519
D/AndroidRuntime( 3132): Shutting down VM
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : -2122120936
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/CscGPS  ( 1482): CSCGPS.updateParameters
D/CscGPS  ( 1482): supl host : null
D/CscGPS  ( 1482): SUPL Host is null or invalid
D/CscGPS  ( 1482): supl_ver : null
D/CscGPS  ( 1482): SUPL Ver is null or invalid
D/CscGPS  ( 1482): supl port : null
D/CscGPS  ( 1482): SUPL PORT is null or invalid
D/CscGPS  ( 1482): LPP : null
D/CscGPS  ( 1482): LPP is null or invalid
D/CscGPS  ( 1482): CSC don't have any AGPS value.
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, uhalitest
D/Launcher.HomeView( 1519): onPause
D/Mms/Conversation( 2434): deleteTempConversation(),deleted=0
V/MediaScanner( 1227): processDirectory :  /system/media
D/Launcher( 1519): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/Mms/MessagingNotification( 2434): isBlockingModeEnabled() = false, Zen mode = 0
W/DriveInitializer( 2131): Background init thread ended
I/CscUpdateService( 1482): same CSC Version
D/CscUtil ( 1482): Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
D/SmsProvider( 1482): Update uri=content://sms/outbox, match=8
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1482): need read changed broadcast:false
E/Zygote  ( 3396): MountEmulatedStorage()
E/Zygote  ( 3396): v2
I/libpersona( 3396): KNOX_SDCARD checking this for 10167
I/libpersona( 3396): KNOX_SDCARD not a persona
I/SELinux ( 3396): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3396): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3396): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3396 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/Mms/SmsReceiverService( 2434): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2434): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2434): [SIM-1]sendFirstQueuedMessage()
D/SettingsProvider( 1020): name = block_emergency_message
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10043
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
W/ActivityManager( 1020): getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
D/TP/SmsProvider( 1482): query,matched:26, calling pid = 2434
I/art     (  305): Explicit concurrent mark sweep GC freed 8678(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 25.208ms
D/TP/SmsProvider( 1482): match 26:Elapsed time : 15.002 ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 16.951ms
D/BadgeProvider( 1586): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
V/MediaScanner( 1227):  prescan time: 416ms (DB items: 138)
V/MediaScanner( 1227):     scan time: 112ms (Caching mode: true), (makeEntry time: 63ms ~56%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 528ms
V/MediaScanner( 1227): checked files: 130  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1227): checkDefaultSounds
D/MediaScanner( 1227): system alarm_alert  : Vwiurug_etwofi5wgg
I/System.out( 3260): Reading bundled version for services.json
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 631us total 18.023ms
D/TimaKeyStoreProvider( 3396): TimaSignature is unavailable
D/ActivityThread( 3396): Added TimaKeyStore provider
D/MediaScanner( 1227): OK. alarm_alert is already exist in setting DB.
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/[0]UMC:Core( 3331): onCreate(): 
D/MediaScanner( 1227): system notification_sound  : K_Oprkltf5wgg
D/MediaScanner( 1227): OK. notification_sound is already exist in setting DB.
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/MediaScanner( 1227): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1227): OK. ringtone is already exist in setting DB.
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/MediaScannerService( 1227): !@done scanning volume internal
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/BadgeProvider( 1586): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1586): sendNotify, [notify] : null
D/BadgeProvider( 1586): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1586): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1586): update, [UpdateCount] : 1
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/Mms/SmsReceiver( 2434): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2434): sDisableVibrateForCamera = false
W/art     ( 3132): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/ActivityThread( 1519): updateVisibility : ActivityRecord{74d306e token=android.os.BinderProxy@5ebd67f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 1519): onStop
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2543/cgroup.procs: No such file or directory
V/ActivityThread( 1519): updateVisibility : ActivityRecord{74d306e token=android.os.BinderProxy@5ebd67f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1519): onTrimMemory. Level: 20
D/Launcher.Model( 1519): reloadBadges entered.
D/Mms/TelephonyPermission( 2434): isDefault true
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,E/SMD     (  289): DCD OFF,
,D/MediaScannerService( 1227): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,D/Mms/MessagingNotification( 2434): setBadgeCount(), count=0
,I/WifiCredService( 1308): onCreate
,I/System.out( 3260): Reading bundled version for dynamicStrings.json
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,D/FactoryTestApp( 2927): [DummyFtClient$mBroadcastReceiver](2927) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2927): [DummyFtClient$mBroadcastReceiver](2927) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2927): [DummyFtClient$mBroadcastReceiver](2927) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/Mms/MessagingNotification( 2434): remove alarm
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/TP/MmsProvider( 1482): Query uri=content://mms, match=0, calling pid = 2434
,E/flip    ( 3260): [ERROR:4] Removing local copy of remote dynamicStrings.json: exception=java.io.IOException: invalid JSON, unexpected EOF in string
E/flip    ( 3260):     flipboard.json.JSONParserBase.b(JSONParserBase.java:549)
E/flip    ( 3260):     flipboard.json.JSONParserBase.a(JSONParserBase.java:338)
E/flip    ( 3260):     flipboard.json.JSONParser.a(JSONParser.java:284)
E/flip    ( 3260):     flipboard.json.JSONParserBase.R(JSONParserBase.java:618)
E/flip    ( 3260):     flipboard.json.JSONParserBase.Q(JSONParserBase.java:559)
E/flip    ( 3260):     flipboard.service.FlipboardManager$29.a(FlipboardManager.java:2502)
E/flip    ( 3260):     flipboard.service.FlipboardManager.a(FlipboardManager.java:1589)
E/flip    ( 3260):     flipboard.service.FlipboardManager.<init>(FlipboardManager.java:781)
E/flip    ( 3260):     flipboard.app.FlipboardApplication.onCreate(FlipboardApplication.java:212)
E/flip    ( 3260):     ...
,D/[0]UMC:DeviceInfo( 3331): USA==US==
,E/Zygote  ( 3416): MountEmulatedStorage(),
,E/Zygote  ( 3416): v2
I/libpersona( 3416): KNOX_SDCARD checking this for 1000
I/SELinux ( 3416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3416): KNOX_SDCARD not a persona
I/SELinux ( 3416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3416 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3416): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/System.out( 3260): Parsed section Cover Stories, private: false
,D/Mms/MessagingNotification( 2434): updateAllHistoryAsRead()
,D/WifiTimerReceiver( 1308): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1308): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1308): Action boot completed received
,D/TimaKeyStoreProvider( 3416): TimaSignature is unavailable
,D/ActivityThread( 3416): Added TimaKeyStore provider
,D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1020): [SO] activate (ident=0xb7ef7998, enabled=0)
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/WifiCredService( 1308): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/WifiStateMachine( 1020): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1020): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1020): invaild command id : 215
,D/SensorManager( 1020): unregisterListener ::   
I/Sensors ( 1020): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/USER_AGENT( 3331): UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
D/SensorService( 1020): [SO] changed settle time [1]
D/SensorService( 1020): [SO] setDelay [66000000]
D/SensorService( 1020): [SO] activate (ident=0xb7ef7998, enabled=1)
D/SensorService( 1020): [SO] AR_init
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/[0]UMC:AdminManager( 3331): init - start
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/SensorManager( 1020): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1227): savePlaylistTableInBulkDeleter finished
,D/[0]UMC:AdminManager( 3331): loadAdmins
,E/Zygote  ( 3437): MountEmulatedStorage()
E/Zygote  ( 3437): v2
I/libpersona( 3437): KNOX_SDCARD checking this for 1000
I/libpersona( 3437): KNOX_SDCARD not a persona
,I/SELinux ( 3437): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/MediaScanner( 1227): Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
I/SELinux ( 3437): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3437): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3437 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/[0]UMC:AdminManager( 3331): init - end
D/GSLBManager( 3331): migrateStoredUrlFromOldPref
,D/GSLBManager( 3331): migrateStoredUrlFromOldPref : Migration Not Needed
,D/[0]UMC:UMCAdmin( 3331): deactivateUMCAdminIfNotRequired : -1,
D/SensorService( 1020): [SO] Reset Rotation Old [100], Init [1]
E/[0]UMC:Utils( 3331): Admin not found in package com.samsung.knoxpb.mdm
,D/TimaKeyStoreProvider( 3437): TimaSignature is unavailable
D/ActivityThread( 3437): Added TimaKeyStore provider
,D/NearbySettings( 1308): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,V/NearbySettings( 1308): MountReceiver.mPrefHandler - 7002
D/SettingsProvider( 1020): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,V/MediaScanner( 1227): processDirectory :  /storage/emulated/0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/[0]UMC:Utils( 3331): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 3331): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 3331): isContainer : 0
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(75ebcf7
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/NearbySettings( 1308): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1308): MountReceiver.onReceive - Internal Path
D/MediaScanner( 1227): Skipping:
D/MediaScanner( 1227): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
V/MediaScanner( 1227): processDirectory :  /storage/extSdCard
W/MediaScanner( 1227): Error opening directory, reason : Permission denied.
W/MediaScanner( 1227): 7klwibgf7fxlKdCbid7
D/SensorService( 1020): [SO] currT = 40301079000, prevT = 39981068000, diff = 320011000, [-0.421 0.172 9.902]
D/SensorService( 1020): [SO] -0.421 0.172 9.902
D/SensorService( 1020): [SO] [100 -> 255]
D/TP/SmsProvider( 1482): query,matched:0, calling pid = 2434
D/EnterpriseDeviceManagerService( 1020): isManagedProfileUser(): userId = 0
V/MediaScanner( 1227):  prescan time: 79ms (DB items: 26)
D/TP/SmsProvider( 1482): match 0:Elapsed time : 4.761 ms
V/MediaScanner( 1227):     scan time: 48ms (Caching mode: true), (makeEntry time: 28ms ~58%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1227): postscan time: 11ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1227):    total time: 138ms
V/MediaScanner( 1227): checked files: 10  directories : 16  (I: 0, U: 0)
D/MediaScannerService( 1227): !@done scanning volume external
,W/ResourcesManager( 3437): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/ActivityManager( 1020): Killing 2460:com.sec.android.app.mt/1000 (adj 15): empty #31
,D/FactoryTestApp( 2927): [DummyFtClient$mBroadcastReceiver](2927) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,D/FactoryTestApp( 2927): [DummyFtClient$mBroadcastReceiver](2927) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,D/FactoryTestApp( 2927): [DummyFtClient$sendBootCompletedAndFinish](2927) ...
D/FactoryTestApp( 2927): [Support$Values.getString](2927) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2927): [ModuleCommon$isConnectionModeNone](2927) mConnectionMode = gsm
,D/FactoryTestApp( 2927): [IPCWriterToSecPhoneService$ResponseWriter](2927) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2927): [IPCWriterToSecPhoneService$connectToSecPhoneService](2927)  
,D/TP/MmsSmsProvider( 1482): query,matched:200, calling pid = 2434
,D/Mms/MessagingNotification( 2434): [end]    nonBlockingUpdateMessageIndicator() consume time = 780.922083
,D/TP/MmsSmsProvider( 1482): match 200:Elapsed time : 3.140 ms
,D/TP/SmsProvider( 1482): query,matched:0, calling pid = 2434
,D/TP/SmsProvider( 1482): match 0:Elapsed time : 3.221 ms
,D/SettingsProvider( 1020): name = personal_mode_enabled
,E/[0]UMC:UMCAdmin( 3331): No active admin owned by uid 10155
D/[0]UMC:UMCAdmin( 3331): isContainer : 0
,D/[0]UMC:UMCAdmin( 3331): deactivateUMCAdmin - UMC App Admin deactivated
,W/ContextImpl( 2927): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,D/TP/SmsProvider( 1482): query,matched:51, calling pid = 2434
,D/[0]UMC:CoreReceiver( 3331): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 3331):  check PreETag 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1482): match 51:Elapsed time : 10.890 ms
,E/SQLiteLog( 3416): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/8)
,E/Zygote  ( 3466): MountEmulatedStorage(),
,E/Zygote  ( 3466): v2
I/libpersona( 3466): KNOX_SDCARD checking this for 10082
I/SELinux ( 3466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3466): KNOX_SDCARD not a persona
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/8)
,D/[0]UMC:ByodSetupStarter( 3331): Container ID : 0
,I/SELinux ( 3466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3466): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/DSM     ( 3416): [Lines:107] Normal booted
D/DSM     ( 3416): [Lines:114] Boot completed
,I/ActivityManager( 1020): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3466 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
,I/FactoryTestApp( 2927): [IPCWriterToSecPhoneService$onServiceConnected](2927) connected done
D/FactoryTestApp( 2927): [IPCWriterToSecPhoneService$write](2927) Send Response Message to SecPhone
D/FactoryTestApp( 2927): [IPCWriterToSecPhoneService$write](2927) Response ��
,V/[0]UMC:Utils( 3331): checkAppScreen() : com.test.thalitest
I/[0]UMC:Core( 3331): shutdown
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2460/cgroup.procs: No such file or directory
,I/art     ( 3331): System.exit called, status: 0
I/AndroidRuntime( 3331): VM exiting with result code 0, cleanup skipped.
,I/WebViewFactory( 3396): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/TimaKeyStoreProvider( 3466): TimaSignature is unavailable
,D/ActivityThread( 3466): Added TimaKeyStore provider
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/AT_Distributor(  312): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
W/ResourcesManager( 1482): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1482): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1482): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1482): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1482): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1482): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/FactoryTestApp( 2927): [IPCWriterToSecPhoneService$handleMessage](2927) Send BOOTING COMPLETED done
D/Mms/MessagingNotification( 2434): isBlockingModeEnabled() = false, Zen mode = 0
,I/LibraryLoader( 3396): Loading: webviewchromium
,I/LibraryLoader( 3396): Time to load native libraries: 5 ms (timestamps 491-496)
I/LibraryLoader( 3396): Expected native library version number "",actual native library version number ""
,E/Zygote  ( 3484): MountEmulatedStorage()
,E/Zygote  ( 3484): v2
I/libpersona( 3484): KNOX_SDCARD checking this for 1000
I/libpersona( 3484): KNOX_SDCARD not a persona
,I/SELinux ( 3484): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3484): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 3484): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 2592:com.sec.pcw.device/1000 (adj 15): empty #31
,I/SmartcardBootCompleteReceiver( 1308): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1308): Received intent with action - android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,D/BadgeProvider( 1586): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/SmartcardBootCompleteReceiver( 1308): Broadcast sent with current lockscreen type
,D/TimaKeyStoreProvider( 3484): TimaSignature is unavailable
,D/ActivityThread( 3484): Added TimaKeyStore provider
,I/ActivityManager( 1020): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3331)(adj 0) has died(32,629)
,V/WebViewChromiumFactoryProvider( 3396): Binding Chromium to main looper Looper (main, tid 1) {3ed63261}
,I/LibraryLoader( 3396): Expected native library version number "",actual native library version number ""
,I/chromium( 3396): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/ResourcesManager( 3484): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/ActivityManager( 1020): Killing 2295:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
,D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/BrowserStartupController( 3396): Initializing chromium process, renderers=0,
D/AT_Distributor(  312): SetAtdStatus(), 1_1_0
D/AT_Distributor(  312): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
W/art     ( 3396): Attempt to remove local handle scope entry from IRT, ignoring
,D/daemonapp( 1798): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,D/comsamsunglog( 1798): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1798): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1798): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1798): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1798): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1798): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,D/SettingsProvider( 1020): name = aw_daemon_service_key_version_check
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1020): selectionArgs: false
,D/SettingsProvider( 1020): selectionArgs: 10157
,D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,W/chromium( 3396): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 3396): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 3396): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10157
,D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,W/ActivityThread( 3484): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1798): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/Adreno-EGL( 3396): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3396): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3396): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3396): Local Branch: 
I/Adreno-EGL( 3396): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3396): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3396):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2592/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10110/pid_2295/cgroup.procs: No such file or directory
,D/[SBeam] ( 1308): SBeamEnabler.initPreferenceForSbeam : 0
,E/daemonapp( 1798): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/BluetoothMediaBrowser( 2972):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1457708774023
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1457730360000
D/daemonapp( 1798): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,D/daemonapp( 1798): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457730360000
,D/BluetoothMediaBrowser( 2972): no now playing list
,D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1457730360000
,I/SettingSearch/SearchIntentReceiver( 1308): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1308): search setting db init!!
,D/BluetoothMediaBrowser( 2972):  getNowPlayingId now playing id : -1
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 3484): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/LcdtestApp( 3484): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
I/SettingSearch/SearchIntentReceiver( 1308): BOOT_COMPLETED call InitSerachDBThread thread start!
,I/DIAGMON_AGENT( 2884): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
I/DIAGMON_AGENT( 2884): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2884): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,I/DIAGMON_AGENT( 2884): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 20558(1041KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/33MB, paused 3.311ms total 146.499ms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3522): MountEmulatedStorage()
E/Zygote  ( 3522): v2
I/libpersona( 3522): KNOX_SDCARD checking this for 10146
I/libpersona( 3522): KNOX_SDCARD not a persona
,I/SELinux ( 3522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3522): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3522 uid=10146 gids={50146, 9997} abi=armeabi-v7a
,D/comdaemonstockapp( 1798): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1798): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,D/BadgeProvider( 1586): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/Launcher.Model( 1519): reloadBadges entered.
,D/TimaKeyStoreProvider( 3522): TimaSignature is unavailable
D/ActivityThread( 3522): Added TimaKeyStore provider
D/BadgeProvider( 1586): sendNotify, [notify] : null
,D/BadgeProvider( 1586): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1586): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1586): update, [UpdateCount] : 1
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3537): MountEmulatedStorage()
I/libpersona( 3537): KNOX_SDCARD checking this for 1000
,E/Zygote  ( 3537): v2
I/libpersona( 3537): KNOX_SDCARD not a persona
I/SELinux ( 3537): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3537): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3537): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3537 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/Mms/MessagingNotification( 2434): setBadgeCount(), count=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/Mms/MessagingNotification( 2434): remove alarm
,D/TimaKeyStoreProvider( 3537): TimaSignature is unavailable
,E/Zygote  ( 3554): MountEmulatedStorage(),
E/Zygote  ( 3554): v2
I/libpersona( 3554): KNOX_SDCARD checking this for 10161
D/ActivityThread( 3537): Added TimaKeyStore provider
I/libpersona( 3554): KNOX_SDCARD not a persona
,I/SELinux ( 3554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3554): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3554 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Mms/MessagingNotification( 2434): updateAllHistoryAsRead()
,W/chromium( 3396): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
E/UpdateRequestReceiver( 3466): ignoring update request
,W/ResourcesManager( 3537): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/UpdateRequestReceiver( 3466): ignoring update request
,D/TP/SmsProvider( 1482): query,matched:0, calling pid = 2434
,D/TP/SmsProvider( 1482): match 0:Elapsed time : 1.534 ms
,D/TimaKeyStoreProvider( 3554): TimaSignature is unavailable
,D/ActivityThread( 3554): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Mms/SmsReceiverService( 2434): [end]    handleBootCompleted() consume time = 554.052188
,E/UpdateRequestReceiver( 3466): ignoring update request
,I/DBG_POLICYDM( 2744): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,E/UpdateRequestReceiver( 3466): ignoring update request
,E/UpdateRequestReceiver( 3466): ignoring update request
,I/DBG_POLICYDM( 2744): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 2744): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 2744): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 2744): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 2744): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/UpdateRequestReceiver( 3466): ignoring update request
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3582): MountEmulatedStorage(),
E/Zygote  ( 3582): v2
I/libpersona( 3582): KNOX_SDCARD checking this for 10088,
I/libpersona( 3582): KNOX_SDCARD not a persona
,I/SELinux ( 3582): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3582 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 2714:com.sec.android.soagent/u0a31 (adj 15): empty #31
,I/SELinux ( 3582): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3582): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/chromium( 3396): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/TimaKeyStoreProvider( 3582): TimaSignature is unavailable
,E/Zygote  ( 3597): MountEmulatedStorage()
E/Zygote  ( 3597): v2
I/libpersona( 3597): KNOX_SDCARD checking this for 1000
I/libpersona( 3597): KNOX_SDCARD not a persona
,I/SELinux ( 3597): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3597): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/ActivityThread( 3582): Added TimaKeyStore provider
,E/SELinux ( 3597): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3597 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 2824:com.samsung.android.sconnect/u0a121 (adj 15): empty #31,
I/ActivityManager( 1020): Killing 2799:com.osp.app.signin/u0a36 (adj 15): empty #32
I/ActivityManager( 1020): Killing 1788:com.samsung.android.securitylogagent/1000 (adj 15): empty #33
,I/FOTA    ( 3537): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,W/art     ( 3396): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider( 3597): TimaSignature is unavailable
,D/ActivityThread( 3597): Added TimaKeyStore provider
,I/DBG_FMMDM( 3597): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,W/libprocessgroup( 1020): failed to open /acct/uid_10031/pid_2714/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10121/pid_2824/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_1788/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10036/pid_2799/cgroup.procs: No such file or directory
,W/AwContents( 3396): onDetachedFromWindow called when already detached. Ignoring
,I/DBG_FMMDM( 3597): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
I/DBG_FMMDM( 3597): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3597): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,D/PhoneWindow( 3396): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3396): *FMB* installDecor flags : -2139027200
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/SystemWebViewEngine( 3396): CordovaWebView is running on device made by: samsung
,I/DBG_DM  ( 3537): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,E/Zygote  ( 3618): MountEmulatedStorage()
,E/Zygote  ( 3618): v2
I/libpersona( 3618): KNOX_SDCARD checking this for 1000
I/libpersona( 3618): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3618 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3618): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3618): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3618): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3618): TimaSignature is unavailable
,D/ActivityThread( 3618): Added TimaKeyStore provider
,W/ResourcesManager( 3554): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3554): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3554): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/PCWCLIENTTRACE_LOG( 3618): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3618): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 3618): new DMDBOpenHelper instance
,D/PCWCLIENTTRACE_DMContentProvider( 3618): [URIMatcher] - result : 2
,I/DBG_FMMDM( 3597): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3597): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3597): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3636): MountEmulatedStorage()
E/Zygote  ( 3636): v2
,I/libpersona( 3636): KNOX_SDCARD checking this for 1000
I/libpersona( 3636): KNOX_SDCARD not a persona
,I/SELinux ( 3636): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3636): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1020): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3636 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3636): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 2611:com.google.android.music:main/u0a108 (adj 15): empty #31
,W/ActivityThread( 3554): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3554): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37521c1b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3554): Installed default security provider GmsCore_OpenSSL
,I/DBG_DM  ( 3537): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,W/art     ( 3396): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3396): Attempt to remove local handle scope entry from IRT, ignoring
,I/DBG_DM  ( 3537): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
I/art     (  305): Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 23.516ms
,D/TimaKeyStoreProvider( 3636): TimaSignature is unavailable
,D/ActivityThread( 3636): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 20.686ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.836ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3653): MountEmulatedStorage(),
E/Zygote  ( 3653): v2
I/libpersona( 3653): KNOX_SDCARD checking this for 10088
I/libpersona( 3653): KNOX_SDCARD not a persona
,I/SELinux ( 3653): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3653 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3653): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3653): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3653): TimaSignature is unavailable
,D/ActivityThread( 3653): Added TimaKeyStore provider
,I/DBG_DM  ( 3537): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 3537): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,I/DBG_DM  ( 3537): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 3537): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,D/OverheatReceiver( 1178): onReceive() getAction : android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3537): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,I/DBG_DM  ( 3537): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,I/DBG_DM  ( 3537): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 3537): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/DBG_DM  ( 3537): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,I/DBG_DM  ( 3537): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 3537): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,I/DBG_DM  ( 3537): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_FMMDS( 3636): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3636): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,W/libprocessgroup( 1020): failed to open /acct/uid_10108/pid_2611/cgroup.procs: No such file or directory
,I/ActivityManager( 1020): Killing 2849:com.sec.android.cloudagent/u0a1 (adj 15): empty #31
,D/OverheatReceiver( 1178): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1178): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1178): isSafeMode = false
,D/PowerManagerService( 1020): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1178 (0x0)
,D/BootupListener( 1482): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1020): name = internet_call_settings_visibility
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 1001
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,D/PhoneUtilsCommon( 1482): isSupportVoLTE is false.
,D/PCWCLIENTTRACE_DMContentProvider( 3618): [URIMatcher] - result : 2
,I/DBG_DM  ( 3537): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,W/ContextImpl( 3537): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,D/OpenGLRenderer( 3396): Render dirty regions requested: true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,E/DBG_FMMDS( 3636): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,D/PhoneWindow( 3396): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3396): *FMB* isFloatingMenuEnabled return false
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3582): Setting receiver enabled: false
,I/DBG_DM  ( 3537): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,I/DBG_FMMDS( 3636): [50.18.150420][Line:43][xdbDBInit] 
,W/libprocessgroup( 1020): failed to open /acct/uid_10001/pid_2849/cgroup.procs: No such file or directory
,I/Telecom ( 1461): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, NainActivit
,E/ActivityThread( 3582): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/DBG_DM  ( 3537): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/ContextImpl( 3554): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/InputDispatcher( 1020): Focus entered window: 3396,
,I/ActivityManager( 1020): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3679 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
E/Zygote  ( 3679): MountEmulatedStorage()
,E/Zygote  ( 3679): v2
I/libpersona( 3679): KNOX_SDCARD checking this for 10052
I/libpersona( 3679): KNOX_SDCARD not a persona
I/SELinux ( 3679): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3679): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 3396): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 3396): Initialized EGL, version 1.4
E/SELinux ( 3679): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/OpenGLRenderer( 3396): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 3396): Enabling debug mode 0
,I/dbxyzptlk.db240408.D.h( 3582): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,D/TimaKeyStoreProvider( 3679): TimaSignature is unavailable
D/ActivityThread( 3679): Added TimaKeyStore provider
,I/dbxyzptlk.db240408.D.h( 3582): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
I/Telecom ( 1461): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,I/dbxyzptlk.db240408.D.h( 3582): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,I/DBG_FMMDS( 3636): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,I/DBG_FMMDS( 3636): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3636): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3636): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3636): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
I/DBG_FMMDS( 3636): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
I/DBG_FMMDS( 3636): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,I/Timeline( 3396): Timeline: Activity_idle id: android.os.BinderProxy@2234f0a4 time:41793
,I/DBG_DM  ( 3537): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,I/ActivityManager( 1020): Displayed Component not be shown by security: +1s943ms
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{1dfb41bb u0 com.test.thalitest/.MainActivity t11} time:41818
W/ActivityManager( 1020): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/DBG_DM  ( 3537): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/dbxyzptlk.db240408.D.h( 3582): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 3537): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,V/audio_hw_primary(  284): adev_get_parameters: enter: keys - call_forwarding
,D/audio_hw_extn(  284): audio_extn_get_parameters: returns 
V/msm8974_platform(  284): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  284): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  284): key: 'call_forwarding' value: ''
V/InCall  ( 1964): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1964): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1964): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/ScoverManager( 1964): serviceVersion : 16908288
,D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
,D/breakpad( 3582): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,D/InCall  ( 1964): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1964): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
I/Telecom ( 1461): ProximitySensorManager: Proximity wake lock already released
I/InCall  ( 1964): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1964): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1964): InCallPresenter -  - dismissCoverDialog()...
,I/SamsungIME( 1851): getCurrentCandidateView
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/InCall  ( 1964): CallSContextMotion - stopPutDownListening
,D/InCall  ( 1964): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,I/com.dropbox.sync.android.a( 3582): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1964): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,D/PhoneStatusBarView( 1178): setCallBackground:0
,I/FOTA_Client( 2906): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 2906): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 2906): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 2906): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3714): MountEmulatedStorage()
E/Zygote  ( 3714): v2
I/libpersona( 3714): KNOX_SDCARD checking this for 10013
I/libpersona( 3714): KNOX_SDCARD not a persona
,I/SELinux ( 3714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1020): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3714 uid=10013 gids={50013, 9997} abi=armeabi-v7a
E/SELinux ( 3714): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 2865:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3714): TimaSignature is unavailable
,D/ActivityThread( 3714): Added TimaKeyStore provider
,D/VideoCallManager( 1964): Instantiating VideoCallManager
,E/        ( 1964): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (7/8)
,I/SurfaceFlinger(  258): id=11 Removed uhalitest (-2/8)
,I/GFX construct_block_size_descriptor_2d second part( 1964): took 2.278229ms for 0*0 texture 0
,W/libprocessgroup( 1020): failed to open /acct/uid_10009/pid_2865/cgroup.procs: No such file or directory
,I/GFX generate_partition_tables( 1964): took 5.163490ms for 0*0 texture 0
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GFX raster( 1964): took 11.648020ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1964): Bitmap=0xb7b08468 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7b0ba68 counterpartCT=4 counterpartW=176 counterparth=144
,E/        ( 1964): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1964): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1964): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1964): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1964): Local Branch: 
I/Adreno-EGL( 1964): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1964): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1964):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/SamsungIME( 1851): Dismiss ExpandCandiate,
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/GFX GPU raster( 1964): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1964): took 0.229635ms for 320*61440 texture 37809
,I/draw setup( 1964): took 11.656094ms for 320*240 texture 37809
E/GFX GPU raster( 1964): drawn
,I/GFX GPU raster ASTC( 1964): took 42.392344ms for 320*240 texture 12
I/GFX raster( 1964): took 42.471823ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1964): Bitmap=0xb7b0ba68 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb7b0bca8 counterpartCT=4 counterpartW=320 counterparth=240
,E/        ( 1964): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1964): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1964): took 0.320781ms for 480*122880 texture 37813
I/draw setup( 1964): took 0.667239ms for 480*640 texture 37813
E/GFX GPU raster( 1964): drawn
,I/GFX GPU raster ASTC( 1964): took 6.988126ms for 480*640 texture 12
I/GFX raster( 1964): took 7.082448ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1964): Bitmap=0xb7d4d6c0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7d4da38 counterpartCT=4 counterpartW=480 counterparth=640
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,V/OneTimeInitializerReceiver( 3714): OneTimeInitializerReceiver.onReceive
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,E/        ( 1964): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1964): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1964): took 0.484635ms for 440*116864 texture 37809
I/draw setup( 1964): took 0.881198ms for 440*330 texture 37809
E/GFX GPU raster( 1964): drawn
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/GFX GPU raster ASTC( 1964): took 5.150834ms for 440*330 texture 12
I/GFX raster( 1964): took 5.206667ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1964): Bitmap=0xb7d3dbe8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb7d62438 counterpartCT=4 counterpartW=440 counterparth=330
,V/OneTimeService( 3714): OneTimeService.onHandleIntent
,E/Zygote  ( 3744): MountEmulatedStorage(),
,I/SamsungIME( 1851): getDebugLevel  : 0x4f4c
E/Zygote  ( 3744): v2
I/libpersona( 3744): KNOX_SDCARD checking this for 10014
I/libpersona( 3744): KNOX_SDCARD not a persona,
I/SELinux ( 3744): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3744): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3744 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 3744): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/        ( 1964): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1964): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1964): took 0.545885ms for 480*163840 texture 37811
I/draw setup( 1964): took 0.935052ms for 480*640 texture 37811
E/GFX GPU raster( 1964): drawn
,I/GFX GPU raster ASTC( 1964): took 6.577083ms for 480*640 texture 12
I/GFX raster( 1964): took 6.667240ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1964): Bitmap=0xb7d388a0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7d4d688 counterpartCT=4 counterpartW=480 counterparth=640
,D/TimaKeyStoreProvider( 3744): TimaSignature is unavailable
,D/ActivityThread( 3744): Added TimaKeyStore provider
,E/        ( 1964): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1964): took 2.427916ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1964): took 7.574011ms for 0*0 texture 0
,I/GFX raster( 1964): took 12.039740ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1964): Bitmap=0xb7d4d688 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7d388d8 counterpartCT=4 counterpartW=176 counterparth=144
,E/YouTube MDX( 3554): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/        ( 1964): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1964): took 2.345469ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1964): took 6.396355ms for 0*0 texture 0
,I/GFX raster( 1964): took 10.980469ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1964): Bitmap=0xb7d4d548 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7d4dbe0 counterpartCT=4 counterpartW=176 counterparth=144
,D/ScoverManager( 1964): registerListener
,I/com.dropbox.sync.android.ad( 3582): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManagerWhiteLists( 1020): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1020): registerListenerCallback : binder = android.os.BinderProxy@1a97c13b, pid : 1964, uid : 1001, type : 1
,D/InCall  ( 1964): InCallPresenter -  - Finished InCallPresenter.setUp
,D/LocationManagerService( 1020): getProviders()=[passive]
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3775): MountEmulatedStorage()
E/Zygote  ( 3775): v2
I/libpersona( 3775): KNOX_SDCARD checking this for 10090
I/libpersona( 3775): KNOX_SDCARD not a persona
,I/SELinux ( 3775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3775 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/JsMessageQueue( 3396): Set native->JS mode to OnlineEventsBridgeMode
,E/SELinux ( 3775): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1020): Killing 2574:com.android.calendar/u0a131 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3775): TimaSignature is unavailable
,D/ActivityThread( 3775): Added TimaKeyStore provider
,I/ContactAccountLoggerTas( 3679): canRun() : Opted Out
,I/SamsungIME( 1851): getDebugLevel  : 0x4f4c
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/libprocessgroup( 1020): failed to open /acct/uid_10131/pid_2574/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 1724): Starting #7
I/Hs20UtilService( 1724): Message received 5003
,D/elm:15121( 3775): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/elm:15121( 3775): ELMEngine.ELMEngine( context ).
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/KLMS-2.5.123: ( 2623): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 11 16:06:15 GMT+01:00 2016
D/elm:15121( 3775): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/SamsungIME( 1851): KeybaordView init() : load resources
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/KLMS-2.5.123: ( 2623): KLMSAbstractReciever(): onReceive().END.
,D/elm:15121( 3775): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 3775): ElmAgentService : onCreate()
,D/elm:15121( 3775): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,E/Zygote  ( 3808): MountEmulatedStorage(),
E/Zygote  ( 3808): v2
I/libpersona( 3808): KNOX_SDCARD checking this for 10020
I/libpersona( 3808): KNOX_SDCARD not a persona
,I/SELinux ( 3808): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3808 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,I/SELinux ( 3808): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3808): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 2623): KLMSIntentService(): onCreate(),
,I/System.out( 3582): Thread-494(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
I/KLMS-2.5.123: ( 2623): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/System.out( 3582): Thread-494(ApacheHTTPLog):isSBSettingEnabled false,
I/System.out( 3582): Thread-494(ApacheHTTPLog):isShipBuild true
I/System.out( 3582): Thread-494(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3582): Thread-494(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/KLMS-2.5.123: ( 2623): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 2623): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 2623): KLMSIntentService(): BOOT_COMPLETED
,D/elm:15121( 3775): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15121( 3775): BootCompletedState : startBootCompleted() call
,D/TimaKeyStoreProvider( 3808): TimaSignature is unavailable
,D/ActivityThread( 3808): Added TimaKeyStore provider
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/elm:15121( 3775): MDMBridge.getAllLicenseInfoFromSDK()
,I/AudioService( 1020): getStreamVolume 3 index 0
,V/EmergencyMode( 1423): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,I/KLMS-2.5.123: ( 2623): KLMSIntentService(): onDestroy()
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10088
,I/SamsungIME( 1851): getCurrentKeyboard,
I/SamsungIME( 1851): getTextKeyboard
,I/elm:15121( 3775): Get License : 0
D/elm:15121( 3775): ElmAgentService : onDestroy().
,I/ActivityManager( 1020): Killing 2991:com.android.keychain/1000 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1851): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/art     ( 1635): Explicit concurrent mark sweep GC freed 3911(159KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 1.042ms total 153.599ms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/GAV2    ( 3679): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 3840): MountEmulatedStorage()
E/Zygote  ( 3840): v2
I/libpersona( 3840): KNOX_SDCARD checking this for 1000
I/libpersona( 3840): KNOX_SDCARD not a persona
,I/SELinux ( 3840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3840 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3840): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 3679): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1020): Killing 2771:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/ContactAccountLoggerTas( 3679): canRun() : Opted Out
,I/chromium( 3396): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!,
I/chromium( 3396): 
,V/EmergencyMode( 1423): [EmergencyBase] setBootTime
V/EmergencyMode( 1423): [EmergencyFactory] No Recovery State, kill my self.
,D/TimaKeyStoreProvider( 3840): TimaSignature is unavailable
,D/ActivityThread( 3840): Added TimaKeyStore provider
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3859): MountEmulatedStorage()
,E/Zygote  ( 3859): v2
I/libpersona( 3859): KNOX_SDCARD checking this for 1000
I/libpersona( 3859): KNOX_SDCARD not a persona
,I/SELinux ( 3859): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3859): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3859): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,I/ActivityManager( 1020): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3859 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2991/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3554): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_2771/cgroup.procs: No such file or directory
,W/ContextImpl( 3554): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3554): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,I/ActivityManager( 1020): Killing 1702:com.android.defcontainer/u0a3 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3859): TimaSignature is unavailable
,D/ActivityThread( 3859): Added TimaKeyStore provider
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1020): getStreamVolume 3 index 0
,I/MediaRouter( 3679): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/RlzPingService( 3744): Setting next ping for 1458313576400,
,E/SMD     (  289): DCD OFF
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/CameraApp( 3859): CameraApp.onCreate()... mFeature : null
I/testFeature( 3859): Feature.Feature(context)
I/testFeature( 3859): Feature.readInternalDefaultXml()
I/testFeature( 3859): ResetFeatureValue
,I/CameraFirmware_broadcast( 3859): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 3859): CameraApp.getAppFeature()...
,W/libprocessgroup( 1020): failed to open /acct/uid_10003/pid_1702/cgroup.procs: No such file or directory
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/FavoriteContactNamesSup( 3679): get() : Execute runnable (UI thread)
,I/ContactLabelSupplier( 3679): get() : Execute runnable (UI thread)
,I/ContactLabelSupplier( 3679): get() : OptedIn = false
,E/Zygote  ( 3895): MountEmulatedStorage()
I/libpersona( 3895): KNOX_SDCARD checking this for 10095
E/Zygote  ( 3895): v2
I/libpersona( 3895): KNOX_SDCARD not a persona
D/jxcore_app_log( 3396): JniHelper::setJavaVM(0xb7761448), pthread_self() = -1210266536
,I/SELinux ( 3895): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3895 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 2656:com.android.chrome/u0a77 (adj 15): empty #31
,I/SELinux ( 3895): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3895): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/MTPRx   ( 3840): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedState
D/SecContentProvider2( 1020): mCursor = null
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1020): mCursor = null
,V/MTPRx   ( 3840): sealedState: false
V/MTPRx   ( 3840): sealedUsbMassStorageState: false
,D/TimaKeyStoreProvider( 3895): TimaSignature is unavailable
I/ActivityManager( 1020): Killing 3038:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,D/ActivityThread( 3895): Added TimaKeyStore provider
,D/SettingsProvider( 1020): name = mtp_usb_connection_status
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3396): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3396):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3396):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3396):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3396):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3396): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ffe3fc3 added. We now have 1 listener(s)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396): setBluetoothMacAddress: 08:EC:A9:50:76:27
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 20312(1144KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 22MB/33MB, paused 10.819ms total 223.706ms
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3396): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,D/SettingsProvider( 1020): name = media_player_mode
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3396): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396):     - Bluetooth MAC address: 08:EC:A9:50:76:27
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@307b151f added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3396): addListener: New listener added - the number of listeners is now 1
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/PreloadFilterInstaller( 3895): uses FILTER_DB_VER_1
,E/Tethering( 1020): No numeric data
,E/Tethering( 1020): No numeric data
,E/Tethering( 1020): No numeric data
,D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,E/Tethering( 1020): No numeric data
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = mtp_running_status
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,I/ActivityManager( 1020): Killing 2641:com.android.email/u0a141 (adj 15): empty #31
,E/Tethering( 1020): No numeric data
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/SettingsProvider( 1020): name = media_mount_count
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/SQLiteLog( 3895): (284) automatic index on titles(filter_id)
,E/Tethering( 1020): No numeric data
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/MessageQueue( 3554): Handler (android.os.Handler) {1726f9a9} sending message to a Handler on a dead thread
W/MessageQueue( 3554): java.lang.IllegalStateException: Handler (android.os.Handler) {1726f9a9} sending message to a Handler on a dead thread
W/MessageQueue( 3554): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 3554): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 3554): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 3554): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 3554): 	at android.os.Handler.post(Handler.java:326)
W/MessageQueue( 3554): 	at ffw.a(SourceFile:327)
W/MessageQueue( 3554): 	at guw.a(SourceFile:120)
W/MessageQueue( 3554): 	at guf.c(SourceFile:26)
W/MessageQueue( 3554): 	at gui.run(SourceFile:297)
W/MessageQueue( 3554): 	at android.os.Handler.handleCallback(Handler.java:739)
W/MessageQueue( 3554): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/MessageQueue( 3554): 	at android.os.Looper.loop(Looper.java:145)
W/MessageQueue( 3554): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3396): setDiscoveryMode: Discovery mode BLE is supported
,D/SettingsProvider( 1020): name = mtp_sync_alive
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/ActivityManager( 1020): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3925 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,E/Zygote  ( 3925): MountEmulatedStorage()
E/Zygote  ( 3925): v2
I/libpersona( 3925): KNOX_SDCARD checking this for 10055
I/libpersona( 3925): KNOX_SDCARD not a persona
,I/SELinux ( 3925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 3925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SettingsProvider( 1020): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,I/ActivityManager( 1020): Killing 3142:com.mobeam.barcodeService/1000 (adj 15): empty #31
,W/ContextImpl( 1953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,D/AndroidHttpClient( 3554): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,D/AndroidHttpClient( 3554): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/chromium( 3396): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SettingsProvider( 1020): name = boot_time_connected
,I/System.out( 3554): Thread-537(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3554): Thread-537(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3554): Thread-537(ApacheHTTPLog):isShipBuild true
I/System.out( 3554): Thread-537(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3554): Thread-537(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10161
,D/SettingsProvider( 1020): name = mtp_open_session
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1953): Service started flags 0 startId 1
,D/TimaKeyStoreProvider( 3925): TimaSignature is unavailable
,D/ActivityThread( 3925): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,D/SecUISvc( 1953): Thread created.
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/FilterProviderReceiver( 3895): onReceive in FilterProviderReceiver
,I/FilterProviderReceiver( 3895): onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_PushUtil( 3618): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3618): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3618): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3618): [onReceive] - android.intent.action.BOOT_COMPLETED
,D/PCWCLIENTTRACE_SYSTEMReceiver( 3618): ACTION_BOOTUP - Version: 4.82,
D/PCWCLIENTTRACE_SYSTEMReceiver( 3618): ACTION_BOOTUP - Push type: [SPP, GCM]
,E/Zygote  ( 3946): MountEmulatedStorage(),
E/Zygote  ( 3946): v2
I/libpersona( 3946): KNOX_SDCARD checking this for 10098
I/libpersona( 3946): KNOX_SDCARD not a persona
,I/SELinux ( 3946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3946): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3946 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3946): TimaSignature is unavailable
D/ActivityThread( 3946): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 611us total 28.128ms
,W/libprocessgroup( 1020): failed to open /acct/uid_10077/pid_2656/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10039/pid_3038/cgroup.procs: No such file or directory
,I/FactoryTestApp( 2927): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3480)  
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3142/cgroup.procs: No such file or directory
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 17.870ms
,W/PCWCLIENTTRACE_AccountUtil( 3618): [hasSamungAccount] - No Samsung Account
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 854us total 17.383ms
,W/libprocessgroup( 1020): failed to open /acct/uid_10141/pid_2641/cgroup.procs: No such file or directory
,I/ActivityManager( 1020): Killing 3170:flipboard.boxer.app/u0a97 (adj 15): empty #31
,D/[SBeam] ( 1308): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1308): SBeamEnabler.isSBeamSupported : EXIST
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3618): [GetString-S]
,D/UserAnalysis.PlaceProvider( 3925): PlaceProvider onCreate()
,D/PackageIntentReceiver( 3946): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3946): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1020): failed to open /acct/uid_10097/pid_3170/cgroup.procs: No such file or directory
,I/ActivityManager( 1020): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3964 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 3964): MountEmulatedStorage()
E/Zygote  ( 3964): v2
I/libpersona( 3964): KNOX_SDCARD checking this for 10099
I/libpersona( 3964): KNOX_SDCARD not a persona
,I/SELinux ( 3964): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ReactiveServiceManager( 3618): Supported : 1
,D/QSEECOMAPI: ( 1020): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1020): App is not loaded in QSEE
,I/SELinux ( 3964): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3964): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/QSEECOMAPI: ( 1020): Loaded image: APP id = 10
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Tethering( 1020): No numeric data
,E/Tethering( 1020): No numeric data
,D/TimaKeyStoreProvider( 3964): TimaSignature is unavailable
,D/ActivityThread( 3964): Added TimaKeyStore provider
,E/Tethering( 1020): No numeric data
,D/UserAnalysis.SecureDbManager( 3925): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3925): SecurePlaceDbHelper() 
,D/UserAnalysis( 3925): Create SecureDbHelper
,D/QSEECOMAPI: ( 1020): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1020): QSEECom_shutdown_app, app_id = 10
,E/terrier ( 1020): handleString: Failed to handle string(-4)
E/terrier ( 1020): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,I/ActivityManager( 1020): Killing 3200:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,E/Tethering( 1020): No numeric data
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 3618): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3618): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 3618): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3618): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3618): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 3618): [ensureRegistration] - No Samsung account
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3979): MountEmulatedStorage()
E/Zygote  ( 3979): v2
I/libpersona( 3979): KNOX_SDCARD checking this for 10028
I/libpersona( 3979): KNOX_SDCARD not a persona
,I/SELinux ( 3979): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3979): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3979 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,E/SELinux ( 3979): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 3245:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,D/FileApkUtils( 2131): Optimizing (staging complete)
,D/IntelligenceServiceApplication( 3925): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3925): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3979): TimaSignature is unavailable
,E/Zygote  ( 3994): MountEmulatedStorage(),
E/Zygote  ( 3994): v2,
I/libpersona( 3994): KNOX_SDCARD checking this for 10056,
I/ActivityManager( 1020): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3994 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/libpersona( 3994): KNOX_SDCARD not a persona
,I/SELinux ( 3994): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/IntelligenceServiceApplication( 3925): no applications having user consent for prediction,
I/SELinux ( 3994): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3994): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 3979): Added TimaKeyStore provider
,D/FileApkUtils( 2131): Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 3994): TimaSignature is unavailable
,D/ActivityThread( 3994): Added TimaKeyStore provider
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,W/libprocessgroup( 1020): failed to open /acct/uid_10153/pid_3245/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1101/pid_3200/cgroup.procs: No such file or directory
,I/System.out( 3554): Thread-537 calls detatch()
,I/art     ( 2131): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,D/ChimeraCfgMgr( 1840): Reading stored module config
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,V/PlaceDetection v1.0.19 ( 3925): [PlaceDetection::stopService] Service stopped.
,D/DexOptUtils( 2131): Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
,W/NotificationAccessSettings( 1308): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,W/ResourcesManager( 1308): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/System.out( 3582): pool-10-thread-1 calls detatch()
,D/WearableService( 1840): callingUid 10011, callindPid: 1840
,I/ActivityManager( 1020): Killing 3260:flipboard.app/u0a96 (adj 15): empty #31
,V/PlaceDetection v1.0.19 ( 3925): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/GmsWearableNodeHelper( 1840): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/UserAnalysis.MyPlaceDbPreference( 3925): Constructor Preference
,I/System.out( 3979): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 3979): Inside WakeupProvider
,D/ScoverManager( 1308): serviceVersion : 16908288
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/sCloudBackupApp( 3994): sCloudBackupApp Version Info : 4.04.7.KK_APP
,W/InstanceID/Rpc( 2131): Found 10011
,I/VlingoApplication( 3979): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1020): failed to open /acct/uid_10096/pid_3260/cgroup.procs: No such file or directory
,E/Zygote  ( 4024): MountEmulatedStorage()
E/Zygote  ( 4024): v2
I/libpersona( 4024): KNOX_SDCARD checking this for 10058
I/libpersona( 4024): KNOX_SDCARD not a persona
,I/SELinux ( 4024): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4024 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3288:com.sec.usbsettings/1000 (adj 15): empty #31
,I/SELinux ( 4024): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4024): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 3396): Background sticky concurrent mark sweep GC freed 6904(922KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 15MB/15MB, paused 6.927ms total 25.834ms
,D/SensorService( 1020): [SO] -0.421 0.172 9.922
,D/TimaKeyStoreProvider( 4024): TimaSignature is unavailable
,D/ActivityThread( 4024): Added TimaKeyStore provider
,I/VlingoAndroidCore( 3979): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3288/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1020): Killing 2434:com.android.mms/u0a41 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3964): getAccountsCursor
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ExternalOEMControlProvider( 4024): onCreate
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/GAV2    ( 3964): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 4051): MountEmulatedStorage()
,E/Zygote  ( 4051): v2
I/libpersona( 4051): KNOX_SDCARD checking this for 1000
I/libpersona( 4051): KNOX_SDCARD not a persona,
,I/SELinux ( 4051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4051): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=4051 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1020): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10058
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,D/SettingsProvider( 1020): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10058
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,D/TimaKeyStoreProvider( 4051): TimaSignature is unavailable
,D/ActivityThread( 4051): Added TimaKeyStore provider
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,D/CountryDetector( 1020): No listener is left
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,W/ResourcesManager( 4051): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/LockPatternUtils( 1308): isSmartCardAuthenticationAvailable: false
,D/VlingoApplication( 3979): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3979): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1020): failed to open /acct/uid_10041/pid_2434/cgroup.procs: No such file or directory
,D/DialogFlow( 3979): initQueue()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2131): Reading stored module config
,D/Settings_Utils( 1308): isSupportVNFestival SM-A300FU XEO
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 1308): Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,W/ResourceType( 1308): Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75),
,W/jxcore-log( 3396): Initializing JXcore engine
W/jxcore-log( 3396): JXcore engine is ready
,E/Zygote  ( 4076): MountEmulatedStorage(),
I/libpersona( 4076): KNOX_SDCARD checking this for 10030
E/Zygote  ( 4076): v2
I/libpersona( 4076): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4076 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 4076): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/SELinux ( 4076): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4076): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/Gmail   ( 3964): Observing account changes for notifications
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4076): TimaSignature is unavailable
,D/ActivityThread( 4076): Added TimaKeyStore provider
,D/BootCompletedReceiver( 2131): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2131): Got an BootCompleted event.
,I/ServiceMode( 4051): received = ACTION_BOOT_COMPLETED
,I/ServiceMode( 4051): setReferenceIsDumpState : 0
,D/BootCompletedReceiver( 2131): Will NOT schedule AdAttestation signal task because it's disabled.
,E/Gmail   ( 3964): Error finding the version of the Email provider.....
E/Gmail   ( 3964): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3964): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3964): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3964): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3964): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3964): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 3964): We do not support migrating this version of the Email provider.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/audit   ( 1922): type=1400 msg=audit(1457708778.090:205): avc:  denied  { ioctl } for  pid=3924 comm="Thread-468" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
,E/audit   ( 1922):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1922): type=1300 msg=audit(1457708778.090:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=4 a3=923d68f8 items=0 ppid=305 ppcomm=main pid=3924 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-468" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1922): type=1320 msg=audit(1457708778.090:205): 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 3396): Starting JXcore engine
,E/Zygote  ( 4093): MountEmulatedStorage(),
I/ActivityManager( 1020): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=4093 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 4093): v2
I/libpersona( 4093): KNOX_SDCARD checking this for 1000
,I/libpersona( 4093): KNOX_SDCARD not a persona
,I/SELinux ( 4093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4093): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 3315:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/Gmail   ( 3964): getAccountsCursor
,D/GCM     ( 2131): COMPAT: Multi user not supported
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4093): TimaSignature is unavailable
,D/ActivityThread( 4093): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/jxcore-log( 3396): Platform android
W/jxcore-log( 3396): 
,W/jxcore-log( 3396): Process ARCH arm
W/jxcore-log( 3396): 
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,W/ActivityManager( 1020): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/GCM     ( 1840): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/btif_config_util( 2972): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/ActivityThread( 3964): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@1caa6635 that was originally bound here
E/ActivityThread( 3964): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@1caa6635 that was originally bound here
E/ActivityThread( 3964): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3964): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3964): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3964): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3964): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3964): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3964): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3964): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3964): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3964): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3964): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3964): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3964): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3964): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1020): Unbind failed: could not find connection for android.os.BinderProxy@3769f867
,W/libprocessgroup( 1020): failed to open /acct/uid_10043/pid_3315/cgroup.procs: No such file or directory
,D/NPS_WSSNPS( 4093): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4093): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,D/NPS_WSSNPS( 4093): [] Service onCreate!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4116): MountEmulatedStorage(),
E/Zygote  ( 4116): v2
I/libpersona( 4116): KNOX_SDCARD checking this for 1000,
I/libpersona( 4116): KNOX_SDCARD not a persona
,I/SELinux ( 4116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1020): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=4116 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4116): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,D/TimaKeyStoreProvider( 4116): TimaSignature is unavailable,
D/ActivityThread( 4116): Added TimaKeyStore provider
,E/SQLiteLog( 3964): (283) recovered 31 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ResourcesManager( 4076): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,I/GoogleHttpClient( 1635): GMS http client unavailable, use old client
,W/ResourcesManager( 4076): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4076): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/NPS_WSSNPS( 4093): [50.150321] NpsServiceTask Start
,I/CheckinService( 2131): Disabling old GoogleServicesFramework version
,W/ResourcesManager( 4076): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4076): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4076): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4076): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4076): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 21707(1100KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.817ms total 179.178ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4137 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
,E/File    ( 3964): fail readDirectory() errno=2,
,E/Zygote  ( 4137): MountEmulatedStorage(),
E/Zygote  ( 4137): v2
I/libpersona( 4137): KNOX_SDCARD checking this for 10102,
I/libpersona( 4137): KNOX_SDCARD not a persona
,I/SELinux ( 4137): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4137): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4137): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4137): TimaSignature is unavailable
,D/ActivityThread( 4137): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 2131): onCreate
,I/Gmail   ( 3964): notifyAccountChanged
,D/NPS_WSSNPS( 4093): [50.150321] smlDBHelper
,I/Gmail   ( 3964): getAccountsCursor
,W/ResourcesManager( 4137): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NPS_WSSNPS( 4093): [50.150321] AsyncBulkFlagCheck
,I/CheckinService( 2131): Checking schedule, now: 1457708778775 next: 1457732977569
,I/CheckinService( 2131): active receiver: disabled
,D/SettingsProvider( 1020): name = access_control_enabled
,D/FactoryTestApp( 2927): [DummyFtClient$onDestroy](2927) Destroy DummyFtClient service
,D/FactoryTestApp( 2927): [Support$Values.getString](2927) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2927): [ModuleCommon$isConnectionModeNone](2927) mConnectionMode = gsm
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/FactoryTestApp( 2927): [ModuleCommon$isRunningFtClient](2927) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2927): [DummyFtClient$onDestroy](2927) kill process
I/Process ( 2927): Sending signal. PID: 2927 SIG: 9
,I/Gmail   ( 3964): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/NPS_WSSNPS( 4093): [50.150321] IsRemain_AsyncBulkCheck
,I/NPS_WSSNPS( 4093): [50.150321] IsRemain_Asyncing nothing
W/ContextImpl( 4093): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
E/Zygote  ( 4159): MountEmulatedStorage()
E/Zygote  ( 4159): v2
I/libpersona( 4159): KNOX_SDCARD checking this for 10065
I/libpersona( 4159): KNOX_SDCARD not a persona
,I/SELinux ( 4159): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4159): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4159): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/jxcore-log( 3396): JXcore Cordova bridge is ready!
I/jxcore-log( 3396): 
,W/jxcore-log( 3396): JXcore engine is started
,I/ActivityManager( 1020): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4159 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3187:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,I/org.thaliproject.p2p.ThaliPermissions( 3396): execute: REQUEST_ACCESS_COARSE_LOCATION
,V/VibratorService( 1020): hasVibrator - useVibetonz: true
,D/TimaKeyStoreProvider( 4159): TimaSignature is unavailable
,D/ActivityThread( 4159): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 1586:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 4093): [50.150321] Service onDestroy
,I/GCoreUlr( 2131): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/jxcore  ( 3396): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3396): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
D/SystemUpdateService( 2131): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ActivityManager( 1020): Process com.sec.factory (pid 2927)(adj 0) has died(22,607)
,I/NPS_WSSNPS( 4093): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 4093): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 4093): [50.150321] smlBREmailDelete
,I/NPS_WSSNPS( 4093): [50.150321] smlBRNetworkDelete
,I/chromium( 3396): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/NPS_WSSNPS( 4093): [50.150321] smlBRCallLogDelete
,I/NPS_WSSNPS( 4093): [50.150321] smlBRMiniDiaryDelete
,I/NPS_WSSNPS( 4093): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 4093): [50.150321] smlBRSMemoDelete
,I/NPS_WSSNPS( 4093): [50.150321] cpuBooster release : false
,I/Gmail   ( 3964): calculateUnknownSyncRationalesAndPurgeInBackground: queueing,
,D/FocusedStackFrame( 1020): Set to : 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1020): Focused application set to: xxxx
,V/AuthZen ( 2131): Handling intent: android.intent.action.BOOT_COMPLETED
,I/Gmail   ( 3964): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/InputDispatcher( 1020): Focus left window: 3396
,I/Gmail   ( 3964): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (205 us)
,W/PluginManager( 3396): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 76ms. Plugin should use CordovaInterface.getThreadPool().
,D/AuthZenEventHandler( 2131): Handling event: android.intent.action.BOOT_COMPLETED
,D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1020): mDVFSHelper.acquire()
,D/NPS_WSSNPS( 4093): [50.150321] dsServerSocket close
,V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 1020): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1020): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/FileShare-Server( 4159): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1020): [SO] activate (ident=0xb7ef7998, enabled=0)
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1020): unregisterListener ::   
,D/Launcher( 1519): onRestart, Launcher: 1054924818
I/ActivityManager( 1020): Killing 3437:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,I/Sensors ( 1020): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1020): [SO] changed settle time [0]
D/SensorService( 1020): [SO] setDelay [200000000]
D/SensorService( 1020): [SO] activate (ident=0xb7ef7998, enabled=1)
D/SensorService( 1020): [SO] AR_init
I/Sensors ( 1020): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/Launcher( 1519): onStart, Launcher: 1054924818
D/Launcher.HomeView( 1519): onStart
D/Launcher( 1519): onResume, Launcher: 1054924818
,D/SensorManager( 1020): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/SettingsProvider( 1020): name = kids_home_mode
D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10006
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,D/Launcher.HomeView( 1519): onResume
,I/ActivityManager( 1020): Waited long enough for: ServiceRecord{2bad084a u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,D/Launcher( 1519): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1519): onResume
,D/ActivityManager( 1020): handle home activity for 0
I/WallpaperManagerService( 1020): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1020): post home show event for user 0
D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/WallpaperManagerService( 1020):  force update = false; persona id = 0; current user =0; current persona = 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1020): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,I/SurfaceFlinger(  258): id=13 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SystemUpdateService( 2131): cancelUpdate (empty URL)
,I/SystemUpdateService( 2131): active receiver: disabled
,D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1020): Focus entered window: 1519
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 1519): log_dcs ThreadedRenderer::initialize entered! 
,D/Launcher( 1519): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1851): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/IInputConnectionWrapper( 3396): showStatusIcon on inactive InputConnection
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4305, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/SensorService( 1020): [SO] Reset Rotation Old [100], Init [1]
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Timeline( 1519): Timeline: Activity_idle id: android.os.BinderProxy@5ebd67f time:45897
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/PowerUI ( 1178): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1178): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/EmergencyMode( 1423): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1423): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
D/PersonaManager( 1020): isKioskContainerExistOnDevice
,V/HeadsetService( 2972): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2972): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,W/libprocessgroup( 1020): failed to open /acct/uid_10068/pid_1586/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10081/pid_3187/cgroup.procs: No such file or directory
,I/ActivityManager( 1020): Displayed Component not be shown by security: +340ms
,I/GCoreUlr( 1840): DispatchingService.onCreate()
,W/BaseAppContext( 2131): Using Auth Proxy for data requests.
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3437/cgroup.procs: No such file or directory
,I/Gmail   ( 3964): getAccountsCursor
,W/art     ( 3979): Suspending all threads took: 13.892ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 2694:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,E/SMD     (  289): DCD OFF
,D/SensorService( 1020): [SO] currT = 46071060000, prevT = 45631106000, diff = 439954000, [-0.421 0.172 9.883]
D/SensorService( 1020): [SO] -0.421 0.172 9.883
D/SensorService( 1020): [SO] [100 -> 255]
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1020): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Zygote  ( 4209): MountEmulatedStorage()
,E/Zygote  ( 4209): v2
I/libpersona( 4209): KNOX_SDCARD checking this for 1000
I/libpersona( 4209): KNOX_SDCARD not a persona
,W/libprocessgroup( 1020): failed to open /acct/uid_10117/pid_2694/cgroup.procs: No such file or directory
I/SELinux ( 4209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4209): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=4209 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1020): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1020): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/art     (  305): Explicit concurrent mark sweep GC freed 8707(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 671us total 25.071ms
,D/TimaKeyStoreProvider( 4209): TimaSignature is unavailable
,D/ActivityThread( 4209): Added TimaKeyStore provider
,E/BaseAppContext( 2131): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 21.667ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 22.268ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/Babel   ( 4137): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4137): MmsConfig.loadMmsSettings
I/Babel   ( 4137): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 4137): MmsConfig.loadFromDatabase
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Process ( 4076): Sending signal. PID: 4076 SIG: 9
,I/LockPatternUtils( 1308): isSmartCardAuthenticationAvailable: false
,E/Babel   ( 4137): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4137): MmsConfig.loadFromResources
,E/Babel   ( 4137): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4137): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,I/GCoreUlr( 1840): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/Icing   ( 2131): Storage manager: low false usage 2.11MB avail 9.95GB capacity 11.63GB
,I/System.out( 3979): INFO:Resource not found:/Common.properties Using default values
,W/ContextImpl( 4209): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3618): unregister AuthInfo UpdateReceiver v2.0
,I/ActivityManager( 1020): Process com.sec.android.app.sns3 (pid 4076)(adj 0) has died(45,609)
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4238): MountEmulatedStorage(),
E/Zygote  ( 4238): v2
,I/libpersona( 4238): KNOX_SDCARD checking this for 10031
I/libpersona( 4238): KNOX_SDCARD not a persona,
I/ActivityManager( 1020): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4238 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
W/VideoCapabilities( 4137): Unrecognized profile 2130706433 for video/avc
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 4238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
W/AudioCapabilities( 4137): Unsupported mime audio/evrc
,W/AudioCapabilities( 4137): Unsupported mime audio/qcelp,
,I/SELinux ( 4238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4238): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/AudioCapabilities( 4137): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 4137): Unsupported mime audio/mpeg-L2
,E/Zygote  ( 4254): MountEmulatedStorage()
E/Zygote  ( 4254): v2
I/libpersona( 4254): KNOX_SDCARD checking this for 1000
I/libpersona( 4254): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider( 4238): TimaSignature is unavailable,
D/ActivityThread( 4238): Added TimaKeyStore provider,
W/art     ( 2131): Suspending all threads took: 64.337ms
W/AudioCapabilities( 4137): Unsupported mime audio/x-ms-wma
,I/SELinux ( 4254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4254 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
W/Settings( 4137): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/SELinux ( 4254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{97d83a7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:46398
,E/SELinux ( 4254): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 3416:com.sec.dsm.system/1000 (adj 15): empty #31
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (7/8)
,I/SurfaceFlinger(  258): id=12 Removed NainActivit (-2/8)
,W/AudioCapabilities( 4137): Unsupported mime audio/x-ima
,W/AudioCapabilities( 4137): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4137): Unsupported mime audio/evrc
,D/TimaKeyStoreProvider( 4254): TimaSignature is unavailable
,D/ActivityThread( 4254): Added TimaKeyStore provider
,D/CustomFrequencyManagerService( 1020): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3416/cgroup.procs: No such file or directory
,W/ResourcesManager( 4254): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ScreenOrientationListener( 3396): Removing an inexistent observer!
,I/AuthZen ( 2131): Fetching signing key...
,W/ContextImpl( 4254): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,W/VideoCapabilities( 4137): Unsupported mime video/wvc1
,W/art     ( 3979): Suspending all threads took: 75.079ms
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4274): MountEmulatedStorage()
E/Zygote  ( 4274): v2
I/libpersona( 4274): KNOX_SDCARD checking this for 1000
I/libpersona( 4274): KNOX_SDCARD not a persona
I/SELinux ( 4274): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4274): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4274 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 4274): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/VideoCapabilities( 4137): Unsupported mime video/x-ms-wmv
,I/AuthZen ( 2131): Signing key fetched successfully!
,I/F_PHONE ( 4254): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 4254): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/TimaKeyStoreProvider( 4274): TimaSignature is unavailable
,D/ActivityThread( 4274): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,W/BaseAppContext( 2131): Using Auth Proxy for data requests.
,W/Auth    ( 1840): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4274): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/VideoCapabilities( 4137): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 4137): Unsupported mime video/wvc1
,D/BluetoothBDAdrressReceiver( 4274): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/VideoCapabilities( 4137): Unsupported mime video/x-ms-wmv
W/ContextImpl( 4274): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,D/F_PHONE ( 4254): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 4254): default registerAction()
I/F_PHONE ( 4254): [[com.sec.bcservice]] sendPendingMessage()
,I/GCoreUlr( 1840): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/ResourcesManager( 1482): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/DBG_POLICYDM( 2744): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,D/BluetoothBDTestService( 1482): onCreate()
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/BluetoothBDTestService( 1482): onStart(), extra_type: BOOT_COMPLETED
,E/BluetoothBDTestService( 1482): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1482): already exist!( /efs/bluetooth/bt_addr ), file length: 17,
,W/VideoCapabilities( 4137): Unsupported mime video/x-ms-wmv7,
E/Zygote  ( 4296): MountEmulatedStorage()
,E/Zygote  ( 4296): v2
I/libpersona( 4296): KNOX_SDCARD checking this for 1000
I/libpersona( 4296): KNOX_SDCARD not a persona
,I/SELinux ( 4296): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4296): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/VideoCapabilities( 4137): Unsupported mime video/x-ms-wmv8
,E/SELinux ( 4296): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4296 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/VideoCapabilities( 4137): Unsupported mime video/mp43
,I/DBG_POLICYDM( 2744): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,V/Babel   ( 4137): babel boot account: SMS
,V/Babel   ( 4137): babel boot account: thalitester@gmail.com
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 4137): Unsupported mime video/sorenson,
,D/TimaKeyStoreProvider( 4296): TimaSignature is unavailable,
D/ActivityThread( 4296): Added TimaKeyStore provider
,E/Zygote  ( 4313): MountEmulatedStorage()
E/Zygote  ( 4313): v2
I/libpersona( 4313): KNOX_SDCARD checking this for 10032
I/libpersona( 4313): KNOX_SDCARD not a persona
,W/VideoCapabilities( 4137): Unsupported mime video/mp4v-esdp
,I/SELinux ( 4313): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4313 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4313): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4313): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/VideoCapabilities( 4137): Unsupported profile 4 for video/mp4v-es
,D/TimaKeyStoreProvider( 4313): TimaSignature is unavailable
D/ActivityThread( 4313): Added TimaKeyStore provider
,E/Zygote  ( 4329): MountEmulatedStorage(),
I/libpersona( 4329): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4329): v2,
I/libpersona( 4329): KNOX_SDCARD not a persona
I/SELinux ( 4329): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/SQLiteConnectionPool( 2131): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/SELinux ( 4329): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4329 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 4329): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 3484:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
I/ActivityManager( 1020): Killing 2884:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,I/GCoreUlr( 1840): Unbound from all location providers,
I/GCoreUlr( 1840): Place inference reporting - stopped
,W/ContextImpl( 1308): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,V/AlarmManager( 1020): waitForAlarm result :4
,W/ResourcesManager( 4296): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4329): TimaSignature is unavailable
,D/ActivityThread( 4329): Added TimaKeyStore provider
,I/SettingSearch/SearchIntentReceiver( 1308): InitSerachDBThread thread end!
,D/a       ( 2131): Opening database auth.proximity.permit_store...
,V/AlarmManager( 1020): waitForAlarm result :4
,I/GCoreUlr( 1840): DispatchingService.onDestroy()
,I/GCoreUlr( 1840): Stopping handler for UlrDispSvcFast
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4209): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 4209): Resource data:2131165186
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/GCoreUlr( 1840): Unbound from all location providers
I/GCoreUlr( 1840): Place inference reporting - stopped
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ResourcesManager( 4209): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4209): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4209): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4209): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,D/SystemUpdateService( 2131): onDestroy
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,I/KnoxUsageLogPro( 4296): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3484/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_2884/cgroup.procs: No such file or directory
,I/KnoxUsageLogPro( 4296): savePreference: key = previous_sys_time value = 1457708780332
,I/KnoxUsageLogPro( 4296): premStatus:2
,I/KnoxUsageLogPro( 4296): isEulaShown : false
,I/KnoxUsageLogPro( 4296): KnoxUsageReceiver onReceive : not Processible, just return
,I/ActivityManager( 1020): Killing 3522:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 3466:com.google.android.configupdater/u0a82 (adj 15): empty #31
,I/AMMetaDataParserService( 4209): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthZenTransactionCache( 2131): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2131): Clearing transaction cache
,D/PersistentNotificationBroadcastReceiver( 1840): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 4209): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,W/art     ( 3979): Suspending all threads took: 6.101ms
,E/Zygote  ( 4350): MountEmulatedStorage()
E/Zygote  ( 4350): v2
I/libpersona( 4350): KNOX_SDCARD checking this for 1000
I/libpersona( 4350): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4350 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/libprocessgroup( 1020): failed to open /acct/uid_10082/pid_3466/cgroup.procs: No such file or directory
I/ActivityManager( 1020): Killing 3582:com.dropbox.android/u0a88 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_10146/pid_3522/cgroup.procs: No such file or directory
,I/SELinux ( 4350): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/art     ( 1635): Explicit concurrent mark sweep GC freed 4398(189KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 4MB/6MB, paused 1.111ms total 28.830ms
,I/AMMetaDataParserService( 4209): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
I/KnoxUsageLogPro( 4296): savePreference: key = previous_elapsed_time value = 46955
,I/SELinux ( 4350): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4350): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 4313): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4313): [PushClientApplication] Push log off : This is Ship build version
,W/GCoreFlp( 1840): No location to return for getLastLocation()
,W/FusedLocationProvider( 1840): location=null
,W/GCoreFlp( 1840): No location to return for getLastLocation()
,W/FusedLocationProvider( 1840): location=null
,I/AMMetaDataParserService( 4209): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,W/SQLiteConnectionPool( 1635): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/TimaKeyStoreProvider( 4350): TimaSignature is unavailable
,D/ActivityThread( 4350): Added TimaKeyStore provider
,E/SPPClientService( 4313): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 4209): Resource data:L,oop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 4209): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
D/SPPClientService( 4313): PushLog.txt file is not deleted.
D/SPPClientService( 4313): PushLog.txt file is not deleted.
D/SPPClientService( 4313): ============PushLog. stop!
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4369): MountEmulatedStorage(),
E/Zygote  ( 4369): v2
I/libpersona( 4369): KNOX_SDCARD checking this for 10036
I/libpersona( 4369): KNOX_SDCARD not a persona
,I/SELinux ( 4369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4369): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4369 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 3597:com.fmm.dm/1000 (adj 15): empty #31
,E/KnoxSetupWizardClient( 4350): isShipMode : 1
I/KnoxSetupWizardClient( 4350): onReceive : android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 4369): TimaSignature is unavailable
,D/ActivityThread( 4369): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131034113
,W/ResourcesManager( 4209): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4209): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 4209): took 5.913959ms for 0*0 texture 0
,I/GFX generate_partition_tables( 4209): took 18.031774ms for 0*0 texture 0
,I/GFX raster( 4209): took 25.634900ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b382b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7b383f0 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1020): failed to open /acct/uid_10088/pid_3582/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3597/cgroup.procs: No such file or directory
,D/ShortcutReceiver( 4350):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 4209): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.868802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b382b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7afb788 counterpartCT=4 counterpartW=96 counterparth=96
,W/System.err( 4350): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4350): 	at android.os.Parcel.readException(Parcel.java:1544)
,W/System.err( 4350): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4350): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 4350): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 4350): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4350): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/KnoxShortcutUtil( 4350): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4350):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 4350):  shortcut migration not required 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4388): MountEmulatedStorage(),
,E/Zygote  ( 4388): v2
I/libpersona( 4388): KNOX_SDCARD checking this for 1000
I/libpersona( 4388): KNOX_SDCARD not a persona,
I/ActivityManager( 1020): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4388): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/SA      ( 4369): [SSP] onCreated
,I/AMMetaDataParserService( 4209): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/TimaKeyStoreProvider( 4388): TimaSignature is unavailable
,D/ActivityThread( 4388): Added TimaKeyStore provider
,I/SA      ( 4369): [TPM] There is no property file
,I/SA      ( 4369): [SCU] isHaveSA() - false
,I/SA      ( 4369): [TPM] getModelProperty : null
I/SA      ( 4369): [TPM] getCSCProperty : null
,I/SA      ( 4369): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4369): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4369): [DM] TFT FEATURE: false
,D/StatusChecker( 4388): onReceive : android.intent.action.BOOT_COMPLETED
,I/SA      ( 4369): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/SA      ( 4369): [DM] init START
,I/SA      ( 4369): [DM] This device is not a Vodafone
,I/StatusChecker( 4388): onReceive : net.mt.init : DONE
,W/ResourceType( 4369): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4369): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4369): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4369): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
W/ResourceType( 4369): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 4369): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4369): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4369): No package identifier when getting value for resource number 0x00000000,
W/ResourceType( 4369): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 4369): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4369): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4369): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,W/ResourceType( 4369): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4369): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4369): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4369): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4369): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4369): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,W/ResourceType( 4369): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4369): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 4369): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4369): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4369): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4369): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4369): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 4369): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,E/Zygote  ( 4408): MountEmulatedStorage()
,I/SA      ( 4369): [SCU] isHaveSA() - false
I/SA      ( 4369): support phone number id : false
I/SA      ( 4369): [DM] Supports Ref Jpn : true
I/SA      ( 4369): [DM] init END
E/Zygote  ( 4408): v2
I/libpersona( 4408): KNOX_SDCARD checking this for 10113
I/libpersona( 4408): KNOX_SDCARD not a persona
,I/SELinux ( 4408): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4408 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3636:com.fmm.ds/1000 (adj 15): empty #31
,I/SELinux ( 4408): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4408): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      ( 4369): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 4369): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4369): [OR] onReceive END
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4408): TimaSignature is unavailable
,I/SA      ( 4369): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
D/ActivityThread( 4408): Added TimaKeyStore provider
I/SA      ( 4369): [ODM] queryOpenData(key= GEO_IP )
,E/Zygote  ( 4423): MountEmulatedStorage()
E/Zygote  ( 4423): v2
I/libpersona( 4423): KNOX_SDCARD checking this for 10037
I/libpersona( 4423): KNOX_SDCARD not a persona
,I/SELinux ( 4423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4423): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/SA      ( 4369): getMccForGalaxyJpn step2 GEO_IP MCC : 260
E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SA      ( 4369): [LBE] REF_JPN : true
I/SA      ( 4369): [BDC] create
,I/GFX construct_block_size_descriptor_2d second part( 4209): took 2.646146ms for 0*0 texture 0,
,I/ActivityManager( 1020): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4423 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GFX generate_partition_tables( 4209): took 7.504480ms for 0*0 texture 0
,I/GFX raster( 4209): took 11.156720ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7afd468 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b1f2c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4209): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/ActivityManager( 1020): Killing 3653:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
D/TimaKeyStoreProvider( 4423): TimaSignature is unavailable
I/art     (  305): Explicit concurrent mark sweep GC freed 8743(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 24.572ms
,D/ActivityThread( 4423): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 742us total 22.891ms
,I/PageBuddyNotiSvc( 4408): Intent received : action=android.intent.action.BOOT_COMPLETED
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4369): [DBMV2] getEmailID
,I/SA      ( 4369): [DBMV2] getDataV02ForItems
,I/SA      ( 4369): [SSP] query invoked
,I/SA      ( 4369): [SCU] get signed id from samsung account2.0 DB.
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 654us total 19.188ms
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.716042ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7afb788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b38000 counterpartCT=4 counterpartW=96 counterparth=96
,I/SA      ( 4369): [SCU] get signed id from samsung account1.0 DB.
,I/AMMetaDataParserService( 4209): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/Zygote  ( 4442): MountEmulatedStorage()
,E/Zygote  ( 4442): v2
I/libpersona( 4442): KNOX_SDCARD checking this for 10026
I/libpersona( 4442): KNOX_SDCARD not a persona
W/ResourcesManager( 4423): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/SELinux ( 4442): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4442): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4442 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4442): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 4408): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
I/SA      ( 4369): [BDC] destroy
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/PageBuddyNotiSvc( 4408): onCreate mCpBitFlag=0
,I/ActivityManager( 1020): Killing 2906:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.847083ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b1f2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b1e7e8 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 4209): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/TimaKeyStoreProvider( 4442): TimaSignature is unavailable
,D/ActivityThread( 4442): Added TimaKeyStore provider
,E/Zygote  ( 4457): MountEmulatedStorage()
,E/Zygote  ( 4457): v2,
I/libpersona( 4457): KNOX_SDCARD checking this for 10121
I/libpersona( 4457): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4457 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 4457): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4457): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4457): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3636/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10088/pid_3653/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10008/pid_2906/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4457): TimaSignature is unavailable
,D/ActivityThread( 4457): Added TimaKeyStore provider
,W/ResourcesManager( 4457): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4457): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4457): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 4457): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1020): name = scon_is_running
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10121
,D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1020): ret = -1
,W/BackupManagerService( 1020): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 4457): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 4457): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/QuickConnect( 4457): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,E/Zygote  ( 4472): MountEmulatedStorage()
E/Zygote  ( 4472): v2
I/libpersona( 4472): KNOX_SDCARD checking this for 10127
I/libpersona( 4472): KNOX_SDCARD not a persona
,I/SELinux ( 4472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4472): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4472 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3714:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CalendarProvider2( 4423): CalendarProvider2.onCreate() called
,D/TimaKeyStoreProvider( 4472): TimaSignature is unavailable
D/ActivityThread( 4472): Added TimaKeyStore provider
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.793698ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b38000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b1e7e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.674791ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b1e7e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b00900 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4209): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/ActivityManager( 1020): Waited long enough for: ServiceRecord{336d35d9 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.604530ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b00900 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b16748 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4209): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131034113
,I/AMMetaDataParserService( 4209): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 1.012292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b382b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7b033d8 counterpartCT=4 counterpartW=96 counterparth=96
,I/Icing   ( 2131): updateResources: need to parse f{com.google.android.gms}
,I/AMMetaDataParserService( 4209): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/libprocessgroup( 1020): failed to open /acct/uid_10013/pid_3714/cgroup.procs: No such file or directory
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.819635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b382b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7859a08 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,I/AMMetaDataParserService( 4209): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 41431(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 24MB/37MB, paused 6.022ms total 171.579ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.615833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7afd468 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb77c0708 counterpartCT=4 counterpartW=96 counterparth=96
,I/GAV2    ( 3679): Thread[GAThread,5,main]: No campaign data found.
,I/AMMetaDataParserService( 4209): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/ResourcesManager( 4472): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4472): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4472): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4472): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SBrowserFeatureFlag( 4472): initialized in static block : loadCscFeatureValue() succeed! 
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 1.110989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7afb788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b39028 counterpartCT=4 counterpartW=96 counterparth=96
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,I/AMMetaDataParserService( 4209): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/ManifestProvider( 4472): onCreate()
,E/NetworkSettingsReceiver( 4472): onReceive: android.intent.action.BOOT_COMPLETED
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 1.064010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b1f2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b3cc88 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4209): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/SSRM:n  ( 1020): SIOP:: AP = 430
,W/System.err( 4472): java.lang.NoSuchMethodException: isEnabled []
,W/System.err( 4472): 	at java.lang.Class.getMethod(Class.java:665)
,W/System.err( 4472): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
,W/System.err( 4472): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
,W/System.err( 4472): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
,D/Finsky  ( 4442): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/System.err( 4472): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
,W/System.err( 4472): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4472): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4472): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4472): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4472): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4472): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4472): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4472): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4472): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4472): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4472): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 4472): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@3ee0e012
,D/SBrowserFeatureFlag( 4472): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4472): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4505): MountEmulatedStorage()
E/Zygote  ( 4505): v2
I/libpersona( 4505): KNOX_SDCARD checking this for 10131
I/libpersona( 4505): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4505 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/SELinux ( 4505): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 4505): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4505): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaKeyStoreProvider( 4505): TimaSignature is unavailable
,D/ActivityThread( 4505): Added TimaKeyStore provider
,W/ResourcesManager( 4505): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4505): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4505): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1020): Killing 3775:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SettingsProvider( 1020): name = audio_safe_volume_state
,E/Watchdog( 1020): !@Sync 1
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.872604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b38000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb77c0708 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.676511ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b1e7e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b388c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4209): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,W/libprocessgroup( 1020): failed to open /acct/uid_10090/pid_3775/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4539): MountEmulatedStorage(),
E/Zygote  ( 4539): v2
,I/libpersona( 4539): KNOX_SDCARD checking this for 10135,
,I/libpersona( 4539): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4539 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/SELinux ( 4539): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4539): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4539): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4539): TimaSignature is unavailable
,D/ActivityThread( 4539): Added TimaKeyStore provider
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.562240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b00900 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b38268 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4209): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/ResourcesManager( 4539): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4539): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4539): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4539): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4539): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4209): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 4209): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 4209): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131034112
,I/AMMetaDataParserService( 4209): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.610937ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7afb788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b38268 counterpartCT=4 counterpartW=96 counterparth=96,
,I/AMMetaDataParserService( 4209): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,D/Finsky  ( 4442): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.626301ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7afb788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b38268 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/Settings( 4442): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4442): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/AMMetaDataParserService( 4209): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,E/Zygote  ( 4559): MountEmulatedStorage()
,E/Zygote  ( 4559): v2
I/libpersona( 4559): KNOX_SDCARD checking this for 10141
I/libpersona( 4559): KNOX_SDCARD not a persona
,I/SELinux ( 4559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4559 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux ( 4559): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Killing 3808:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4559): TimaSignature is unavailable
E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.713854ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b38268 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7b17268 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityThread( 4559): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4209): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,W/ResourcesManager( 4559): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4559): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4559): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4559): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.638698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b38000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb77c0708 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,D/Volley  ( 4442): [676] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4442): [683] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1020): Killing 3744:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 3840:com.samsung.android.MtpApplication/1000 (adj 15): empty #32
,W/libprocessgroup( 1020): failed to open /acct/uid_10020/pid_3808/cgroup.procs: No such file or directory
,D/Ads     ( 4442): Skipping gmscore version check
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4442): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4442): [1] Libraries$2.run: Finished loading 1 libraries.
,W/libprocessgroup( 1020): failed to open /acct/uid_10014/pid_3744/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3840/cgroup.procs: No such file or directory
,D/Finsky  ( 4442): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 4442): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/SMD     (  289): DCD OFF
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activit,ycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131034113
I/AMMetaDataParserService( 4209): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 4209): took 1.352917ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb77c0708 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7b1f2c0 counterpartCT=4 counterpartW=96 counterparth=96
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
I/AMMetaDataParserService( 4209): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 4209): took 0.980781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb77c0708 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7b1e7e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4209): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533,
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,V/AlarmManager( 1020): waitForAlarm result :8
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.602135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7afb788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7afd468 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4209): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/Icing   ( 2131): Internal init done: storage state 0
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.621145ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b1d928 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b1f2c0 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 4209): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530,
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
E/Zygote  ( 4589): MountEmulatedStorage()
E/Zygote  ( 4589): v2
I/libpersona( 4589): KNOX_SDCARD checking this for 10068
I/libpersona( 4589): KNOX_SDCARD not a persona
E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SELinux ( 4589): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/GFX raster( 4209): took 0.869219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7868958 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b1e7e8 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4589): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4589 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,E/SELinux ( 4589): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
I/Icing   ( 2131): Post-init done
I/AMMetaDataParserService( 4209): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,D/TimaKeyStoreProvider( 4589): TimaSignature is unavailable
,D/ActivityThread( 4589): Added TimaKeyStore provider
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 4209): took 0.685730ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b38000 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7afd468 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 4209): took 0.678125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b1f2c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b1e7e8 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4611): MountEmulatedStorage()
I/libpersona( 4611): KNOX_SDCARD checking this for 10142
E/Zygote  ( 4611): v2
I/libpersona( 4611): KNOX_SDCARD not a persona
,I/SELinux ( 4611): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4611 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 4611): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4611): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 3964): Thread[GAThread,5,main]: No campaign data found.
,I/AMMetaDataParserService( 4209): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
I/ActivityManager( 1020): Killing 3895:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
I/ActivityManager( 1020): Killing 3859:com.sec.factory.camera/1000 (adj 15): empty #32
,D/BadgeProvider( 4589): onCreate
D/BadgeProvider( 4589): DatabaseHelper
,D/BadgeProvider( 4589): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 4611): TimaSignature is unavailable
,D/ActivityThread( 4611): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BadgeProvider( 4589): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1519): reloadBadges entered.
D/BadgeProvider( 4589): sendNotify, [notify] : null
D/BadgeProvider( 4589): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4589): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4589): update, [UpdateCount] : 1
,W/ResourcesManager( 4611): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3859/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10095/pid_3895/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1020): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,I/Process ( 4559): Sending signal. PID: 4559 SIG: 9
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4209): took 0.675834ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7afd468 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b1e7e8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4209): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
W/ContextImpl( 4209): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,I/CalendarProvider2( 4423): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1020): Killing 3618:com.sec.pcw.device/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209,): Resource data:2131165203
W/ResourcesManager( 4209): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 4209): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
D/RCPManagerService( 1020): exchangeData() failure , invalid userId
I/GFX construct_block_size_descriptor_2d second part( 4209): took 3.470105ms for 0*0 texture 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4630): MountEmulatedStorage()
E/Zygote  ( 4630): v2
I/libpersona( 4630): KNOX_SDCARD checking this for 1000
I/libpersona( 4630): KNOX_SDCARD not a persona
,I/GFX generate_partition_tables( 4209): took 17.660784ms for 0*0 texture 0
I/GFX raster( 4209): took 21.709587ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7b0c830 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb7b3b160 counterpartCT=4 counterpartW=80 counterparth=80
,I/SELinux ( 4630): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1020): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4630 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/AMMetaDataParserService( 4209): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,I/SELinux ( 4630): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4630): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
E/lowmemorykiller(  255): Error writing /proc/4559/oom_score_adj; errno=22
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 4209): took 2.853542ms for 0*0 texture 0
,I/GFX generate_partition_tables( 4209): took 5.746302ms for 0*0 texture 0
,I/GFX raster( 4209): took 9.647865ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7ad7770 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7b3b160 counterpartCT=4 counterpartW=80 counterparth=80
,E/lowmemorykiller(  255): Error writing /proc/4559/oom_score_adj; errno=22
,E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
,I/ActivityManager( 1020): Killing 3925:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,I/AMMetaDataParserService( 4209): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,E/JavaBinder( 4611): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 1020): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,I/Process ( 4611): Sending signal. PID: 4611 SIG: 9
,D/TimaKeyStoreProvider( 4630): TimaSignature is unavailable
D/ActivityThread( 4630): Added TimaKeyStore provider
,I/ActivityManager( 1020): Process com.android.email (pid 4559)(adj 9) has died(37,621)
,E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4209): took 0.754270ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7ad7770 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb77c1008 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 4209): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_3618/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10055/pid_3925/cgroup.procs: No such file or directory
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4647 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 4647): MountEmulatedStorage()
E/Zygote  ( 4647): v2
I/libpersona( 4647): KNOX_SDCARD checking this for 1000
I/libpersona( 4647): KNOX_SDCARD not a persona
I/SELinux ( 4647): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Process com.android.exchange (pid 4611)(adj 9) has died(38,622)
,I/SELinux ( 4647): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4647): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4209): took 0.777448ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7ad7770 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7b18348 counterpartCT=4 counterpartW=80 counterparth=80
,D/TimaKeyStoreProvider( 4647): TimaSignature is unavailable
,D/ActivityThread( 4647): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4209): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4209): took 0.621302ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7ae2128 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7b3e3e0 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 4209): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/SecurityLogAgent( 4647): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 4647): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 4647): StateMachine : Current State = 1
,D/SecurityLogAgent( 4647): BootReceiver : completed task. Failed to return wakelock . 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4663): MountEmulatedStorage(),
E/Zygote  ( 4663): v2
,I/libpersona( 4663): KNOX_SDCARD checking this for 10148
I/SELinux ( 4663): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4663): KNOX_SDCARD not a persona
,E/        ( 4209): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 4209): took 0.668125ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4209): Bitmap=0xb7ae2128 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7b1d350 counterpartCT=4 counterpartW=80 counterparth=80
,I/SELinux ( 4663): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4663): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4663 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
I/AMMetaDataParserService( 4209): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/TimaKeyStoreProvider( 4663): TimaSignature is unavailable,
D/ActivityThread( 4663): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
W/ContextImpl( 4209): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/art     (  305): Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 645us total 33.104ms
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131099648
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 754us total 17.331ms
,W/ResourcesManager( 4209): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4209): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 16.727ms
,I/AMMetaDataParserService( 4209): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/SQLiteLog( 4663): (284) automatic index on shooting_modes(title_id)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 4209): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 4209): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/Zygote  ( 4680): MountEmulatedStorage()
,E/Zygote  ( 4680): v2
I/libpersona( 4680): KNOX_SDCARD checking this for 1000
I/SELinux ( 4680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4680): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4680 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4680): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 4209): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TimaKeyStoreProvider( 4680): TimaSignature is unavailable
,D/ActivityThread( 4680): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 3946:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/AMMetaDataParserService( 4209): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131099648
,I/AMMetaDataParserService( 4209): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,I/AMMetaDataParserService( 4209): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/splitIntent( 1020): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1020): Killing 3994:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,I/splitIntent( 1020): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,I/splitIntent( 1020): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,I/AMMetaDataParserService( 4209): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1746): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/AMMetaDataParserService( 4209): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1746): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 4024): Time Difference not stored. TIME_DIFFERENCE
,D/daemonapp( 1798): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 1798): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1798): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1798): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1798): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1798): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/AMMetaDataParserService( 4209): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1798): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1798): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1798): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename,
,I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/daemonapp( 1798): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,E/Zygote  ( 4698): MountEmulatedStorage()
E/Zygote  ( 4698): v2
,I/SELinux ( 4698): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4698): KNOX_SDCARD checking this for 10008
I/libpersona( 4698): KNOX_SDCARD not a persona
,I/SELinux ( 4698): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4698): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 4209): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
I/ActivityManager( 1020): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=4698 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131099648
I/AMMetaDataParserService( 4209): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,D/TimaKeyStoreProvider( 4698): TimaSignature is unavailable
,D/ActivityThread( 4698): Added TimaKeyStore provider
I/AMMetaDataParserService( 4209): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
E/Zygote  ( 4712): MountEmulatedStorage()
E/Zygote  ( 4712): v2
I/libpersona( 4712): KNOX_SDCARD checking this for 10081
I/libpersona( 4712): KNOX_SDCARD not a persona
,I/SELinux ( 4712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4712 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4712): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/comdaemonstockapp( 1798): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 1798): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
I/AMMetaDataParserService( 4209): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/TimaKeyStoreProvider( 4712): TimaSignature is unavailable
,D/ActivityThread( 4712): Added TimaKeyStore provider
,D/SecurityLogAgent( 4647): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4647): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4647): StateMachine : Current State = 1
,I/AMMetaDataParserService( 4209): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 4209): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/Zygote  ( 4729): MountEmulatedStorage(),
E/Zygote  ( 4729): v2
I/libpersona( 4729): KNOX_SDCARD checking this for 10153,
I/libpersona( 4729): KNOX_SDCARD not a persona
,I/SELinux ( 4729): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
I/ActivityManager( 1020): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4729 uid=10153 gids={50153, 9997} abi=armeabi-v7a
I/SELinux ( 4729): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4729): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 4712): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4712): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4712): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4209): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/TimaKeyStoreProvider( 4729): TimaSignature is unavailable
,D/ActivityThread( 4729): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131099648
,I/AMMetaDataParserService( 4209): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,I/AMMetaDataParserService( 4209): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,V/AlarmManager( 1020): waitForAlarm result :4
,W/ResourcesManager( 4729): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4744): MountEmulatedStorage()
E/Zygote  ( 4744): v2
I/libpersona( 4744): KNOX_SDCARD checking this for 10117
I/libpersona( 4744): KNOX_SDCARD not a persona
,I/SELinux ( 4744): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4744): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4744): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService: pid=4744 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4756): MountEmulatedStorage()
I/libpersona( 4756): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4756): v2
I/libpersona( 4756): KNOX_SDCARD not a persona
I/SELinux ( 4756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/TimaKeyStoreProvider( 4744): TimaSignature is unavailable
,D/ActivityThread( 4744): Added TimaKeyStore provider
I/ActivityManager( 1020): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4756 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/AMMetaDataParserService( 4209): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
E/SELinux ( 4756): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4756): TimaSignature is unavailable
,D/ActivityThread( 4756): Added TimaKeyStore provider
,W/ResourcesManager( 4744): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4209): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 4209): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/FOTA_Client( 4698): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 4698): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,W/libprocessgroup( 1020): failed to open /acct/uid_10098/pid_3946/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10056/pid_3994/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/ActivityManager( 1020): Killing 4051:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 2623): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Fri Mar 11 16:06:23 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 2623): KLMSAbstractReciever(): onReceive().END.
,I/SA      ( 4369): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/SettingsProvider( 1020): name = next_alarm_formatted
,D/SettingsProvider( 1020): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1020): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1020): selectionArgs: false
D/SettingsProvider( 1020): selectionArgs: 10081
D/SecContentProvider( 1020): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1020): ret = -1
,I/KLMS-2.5.123: ( 2623): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 2623): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 2623): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 2623): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.5.123: ( 2623): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.123: ( 2623): StateImplV2(): dateTimeChanged().START : Fri Mar 11 16:06:23 GMT+01:00 2016
,D/TimeService( 4756): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457708783886
,D/        ( 4756): TimeServiceNative: User Time to be set is 1457708783886
D/QC-time-services( 4756): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4756): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4756): Lib:time_genoff_operation: pargs->ts_val = 1457708783886
,D/QC-time-services(  318): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  318): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457708783886
D/QC-time-services(  318): Daemon:genoff_opr: Base = 2, val = 1457708783886, operation = 0
,D/QC-time-services(  318): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/6/70 18:43:5
D/QC-time-services(  318): Daemon:Value read from RTC seconds = 21494585000
D/QC-time-services(  318): Daemon:new time 1457708783886 
D/QC-time-services(  318): Daemon: delta 1436214198886 genoff 1436214198886 
D/QC-time-services(  318): Daemon:genoff_persistent_update: Writing genoff = 1436214198886 to memory
D/QC-time-services(  318): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  318): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services( 4756): Lib:time_genoff_operation: Send to server  passed!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 2623): StateImplV2(): dateTimeChanged().END
,E/Zygote  ( 4781): MountEmulatedStorage()
E/Zygote  ( 4781): v2
I/libpersona( 4781): KNOX_SDCARD checking this for 10041
I/libpersona( 4781): KNOX_SDCARD not a persona
,I/SELinux ( 4781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/QC-time-services(  318): Updating the TOD offset,
D/QC-time-services(  318): Daemon:genoff_persistent_update: Writing genoff = 1436214198886 to memory
D/QC-time-services(  318): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  318): Daemon:time_persistent_memory_opr:Genoff write operation 
,I/SELinux ( 4781): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4781): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4781 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 3979:com.vlingo.midas/u0a28 (adj 15): empty #31
,E/QC-time-services(  318): Daemon:Update to modem bit set
D/QC-time-services(  318): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  318): Daemon: Base = 2, Value being sent to MODEM = 1120249398886
,E/QC-time-services(  318): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  318): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services( 4756): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/KLMS-2.5.123: ( 2623): KLMSIntentService(): onDestroy()
,I/ActivityManager( 1020): Killing 3964:com.google.android.gm/u0a99 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4781): TimaSignature is unavailable
,D/ActivityThread( 4781): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4209): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ResourcesManager( 4781): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4781): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4781): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4781): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4781): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131099648
,I/AMMetaDataParserService( 4209): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,I/AMMetaDataParserService( 4209): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/art     ( 4712): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 195.633ms
,I/AMMetaDataParserService( 4209): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/Mms/MmsApp( 4781): [start]    onCreate() consume time = 0.0
,I/AMMetaDataParserService( 4209): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_4051/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10028/pid_3979/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10099/pid_3964/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 4209): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4807): MountEmulatedStorage()
E/Zygote  ( 4807): v2
I/libpersona( 4807): KNOX_SDCARD checking this for 10090
I/libpersona( 4807): KNOX_SDCARD not a persona
,I/SELinux ( 4807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4807): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4807 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4807): TimaSignature is unavailable
,D/ActivityThread( 4807): Added TimaKeyStore provider
,I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 4209): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131099648
,D/elm:15121( 4807): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 4807): ELMEngine.ELMEngine( context ).
,I/AMMetaDataParserService( 4209): getResourceName:com.android.mms:xml/assistant_messaging
D/elm:15121( 4807): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 4807): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,D/elm:15121( 4807): ElmAgentService : onCreate()
,D/elm:15121( 4807): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,I/AMMetaDataParserService( 4209): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/Zygote  ( 4826): MountEmulatedStorage(),
,E/Zygote  ( 4826): v2
I/libpersona( 4826): KNOX_SDCARD checking this for 10130
I/SELinux ( 4826): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4826): KNOX_SDCARD not a persona
I/SELinux ( 4826): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4826 uid=10130 gids={50130, 9997} abi=armeabi-v7a
E/SELinux ( 4826): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/art     ( 4781): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 151.466ms
,I/AMMetaDataParserService( 4209): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/TimaKeyStoreProvider( 4826): TimaSignature is unavailable
,D/ActivityThread( 4826): Added TimaKeyStore provider
,D/elm:15121( 4807): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15121( 4807): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:15121( 4807): ModuleBase.ModifySetAlarm()
D/elm:15121( 4807): MDMBridge.getInstance()
D/elm:15121( 4807): MDMBridge.getAllLicenseInfoFromSDK()
,I/AMMetaDataParserService( 4209): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/elm:15121( 4807): ElmAgentService : onDestroy().
,I/ActivityManager( 1020): Killing 4093:com.wssnps/1000 (adj 15): empty #31
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,I/AMMetaDataParserService( 4209): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ResourcesManager( 4826): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4826): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 28984(1605KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 24MB/36MB, paused 3.363ms total 170.044ms
,I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 4209): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
W/ContextImpl( 4209): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 4209): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/ActivityManager( 1020): Killing 4116:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131165197
W/ResourcesManager( 4209): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/art     ( 4781): Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 149.946ms
W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_4093/cgroup.procs: No such file or directory
I/ActivityManager( 1020): Killing 4137:com.google.android.talk/u0a102 (adj 15): empty #31
,I/AMMetaDataParserService( 4209): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
D/Mms/ArtClassLoader( 4781): init before art
D/Mms/TelephonyPermission( 4781): start operation mode monitor
W/ResourcesManager( 4781): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,D/Mms/TelephonyPermission( 4781): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4781): isDefault true
,D/Mms/MmsApp( 4781): onCreate() com.android.mms
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 4209): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 4209): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4209): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/Mms/MmsApp( 4781): [start]    initCountryIso consume time = 418.221822
,D/CountryDetector( 1020): The first listener is added
,D/Mms/MmsApp( 4781): [end]    initCountryIso consume time = 7.857292
D/Mms/MmsConfig( 4781): [start]    MmsConfig.init() consume time = 0.104219
,I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131165197
,I/AMMetaDataParserService( 4209): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,I/AMMetaDataParserService( 4209): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 4209): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_4116/cgroup.procs: No such file or directory
W/libprocessgroup( 1020): failed to open /acct/uid_10102/pid_4137/cgroup.procs: No such file or directory
,D/Mms/MmsConfig( 4781): before partial update
,D/Mms/MmsConfig( 4781): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4781): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4781): isAuth is false
,D/Mms/MmsConfig( 4781): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1482): query,matched:2117, calling pid = 4781
,D/TP/MmsSmsProvider( 1482): match 2117:Elapsed time : 1.957 ms
,I/AMMetaDataParserService( 4209): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/EasySignUpManager_1.0.1( 4781): isAuth is false
D/EasySignUpManager_1.0.1( 4781): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4781): mps_code.dat does not exist
E/CscParser( 4781): customer_path =/system/csc/customer.xml
E/CscParser( 4781): fileName + /system/csc/customer.xml
,I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.cooliris.media.Gallery
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131165197
,I/AMMetaDataParserService( 4209): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,E/CscParser( 4781): mps_code.dat does not exist
,E/CscParser( 4781): customer_path =/system/csc/customer.xml
E/CscParser( 4781): fileName + /system/csc/customer.xml
,D/CscParser( 4781): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4781):  enable multiwindow = false
,I/AMMetaDataParserService( 4209): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,D/Mms/ArtClassLoader( 4781): init [DONE] art
,E/Mms/MessageUtils( 4781): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 4781): updateCountryIso : update country iso info 
,I/AMMetaDataParserService( 4209): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,D/Mms/MmsConfig( 4781): [end]    init() consume time = 172.417448
,D/Mms/Contact( 4781): [start]    init() consume time = 0.619271
,D/TP/MmsSmsProvider( 1482): query,matched:13, calling pid = 4781
,D/TP/MmsSmsProvider( 1482): match 13:Elapsed time : 2.524 ms
,D/Mms/Contact( 4781): [end]    init consume time = 10.863437
,I/AMMetaDataParserService( 4209): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/Mms/MethodReflector( 4781): getSubId is called
,D/Mms/TelephonyUtils( 4781): getLongSubId from simSlot 0, return Value = -1
,D/Mms/DraftCache( 4781): [start]    rebuildCache consume time = 7.499688
,D/Mms/MethodReflector( 4781): getTelephonyProperty is called
D/Mms/DownloadManager( 4781): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4781): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4781): auto download without roaming -> true
D/Mms/DownloadManager( 4781): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 4781): getSubId is called
,D/Mms/MethodReflector( 4781): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4781): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4781): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 4781): getTelephonyProperty is called
D/Mms/DownloadManager( 4781): roaming -> false (slotId = 1)
,D/Mms/DownloadManager( 4781): [NotificationTransaction] getAutoDownloadState simSlot : 1
,D/Mms/DownloadManager( 4781): auto download without roaming -> true
D/Mms/DownloadManager( 4781): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
,D/Mms/DownloadManager( 4781): auto download during roaming secondary -> false
,D/TP/MmsSmsProvider( 1482): query,matched:12, calling pid = 4781
D/Mms/DownloadManager( 4781): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 1482): match 12:Elapsed time : 1.650 ms
I/AMMetaDataParserService( 4209): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/Mms/DraftCache( 4781): [end]    rebuildCache consume time = 10.882343
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 4209): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131099648
,W/ResourcesManager( 4209): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ComposerPerformance( 4781): 1457708784728 ms / [DONE] Composer constructor
I/AMMetaDataParserService( 4209): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/Mms/Conversation( 4781): [start]    init() consume time = 15.046198
,E/CII     ( 4781): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 4781): ReservationManager()
,I/Mms/ReservationManager( 4781): resetAfterConnected()
,D/TP/MmsSmsProvider( 1482): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1482): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1482): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1482): sUpgradeVersion = 0, db.getVersion() = 81
,I/AMMetaDataParserService( 4209): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,E/SQLiteLog( 1482): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1482): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1482): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1482): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1482): (284) automatic index on im_threads(normal_thread_id)
,E/SQLiteLog( 1482): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1482): query,matched:7, calling pid = 4781
,D/TP/MmsSmsProvider( 1482): match 7:Elapsed time : 4.952 ms
,D/TP/MmsSmsProvider( 1482): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1482): need read changed broadcast:false
,D/Mms/Conversation( 4781): [end]    init consume time = 28.268281
,D/Mms/MessagingNotification( 4781): [start]    init() consume time = 1.211511,
,I/Mms/ReservationManager( 4781): getReservedSendMessageCount(): retMessageCount=0
,D/Mms/MessagingNotification( 4781): [end]    init consume time = 4.766562
,D/Mms/MmsApp( 4781): [end]    onCreate() consume time = 9.840313
,D/TP/MmsSmsProvider( 1482): query,matched:0, calling pid = 4781
V/TP/MmsSmsProvider( 1482): getSimpleConversations entered.
I/AMMetaDataParserService( 4209): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/TP/MmsSmsProvider( 1482): match 0:Elapsed time : 1.914 ms
,D/Mms/DownloadManager( 4781): Service state changed: Bundle[mParcelledData.dataSize=744]
I/splitIntent( 1020): Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
D/Mms/DownloadManager( 4781): roaming ------> false, mSimSlot = 0
D/Mms/SpamFilter( 4781): [start]    SpamFilter fill() begin consume time = 20.608073
W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/ActivityManager( 1020): Killing 4159:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/Mms/Synchronizer( 4781): [start]    doSync consume time = 1.523333
,D/Mms/MethodReflector( 4781): getSubId is called
D/Mms/TelephonyUtils( 4781): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4781): getTelephonyProperty is called
D/Mms/DownloadManager( 4781): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4781): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4781): auto download without roaming -> true
D/Mms/DownloadManager( 4781): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/DownloadManager( 4781): mAutoDownload ------> true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1482): query,matched:400, calling pid = 4781
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 4209): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/splitIntent( 1020): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1020): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1020): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1482): update, matched:300, calling pid = 4781
D/Mms/SpamFilter( 4781): [end]    SpamFilter fill() finished consume time = 43.239583
,V/TP/MmsSmsProvider( 1482): syncDBData start
,V/TP/MmsSmsProvider( 1482): syncDBData sms end
,V/TP/MmsSmsProvider( 1482): syncDBData mms end
,V/TP/MmsSmsProvider( 1482): syncDBData end
,D/Mms/Synchronizer( 4781): [end]    doSync consume time = 7.056302
,D/Mms/MessagingNotification( 4781): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1482): query,matched:26, calling pid = 4781
,D/TP/SmsProvider( 1482): match 26:Elapsed time : 1.566 ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,D/TP/MmsSmsProvider( 1482): query,matched:6, calling pid = 4781
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/MmsSmsProvider( 1482): match 6:Elapsed time : 4.623 ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4861): MountEmulatedStorage()
I/libpersona( 4861): KNOX_SDCARD checking this for 10023
E/Zygote  ( 4861): v2
I/libpersona( 4861): KNOX_SDCARD not a persona
I/SELinux ( 4861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4861 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,I/SELinux ( 4861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:assistant
I/AMMetaDataParserService( 4209): Resource data:2131165220
E/SELinux ( 4861): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 4209): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4209): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 4209): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 4209): getResourceTypeNamexml
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/libprocessgroup( 1020): failed to open /acct/uid_10065/pid_4159/cgroup.procs: No such file or directory
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 4209): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1840): callingUid 10011, callindPid: 1840
,I/AMMetaDataParserService( 4209): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1840): [236] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/TimaKeyStoreProvider( 4861): TimaSignature is unavailable
,D/ActivityThread( 4861): Added TimaKeyStore provider
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1020): Killing 4238:com.sec.android.soagent/u0a31 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2131): Restart initialization of location
,I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParse,rService( 4209): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ContextImpl( 4209): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/ActivityManager( 1020): Killing 4209:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
W/ActivityManager( 1020): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEAD,ER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 4209): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4209): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 4209): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 4861): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp( 4781): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,W/libprocessgroup( 1020): failed to open /acct/uid_10031/pid_4238/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_4209/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1482): query,matched:0, calling pid = 2131
,I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,D/TP/SmsProvider( 1482): match 0:Elapsed time : 1.432 ms
I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false,
,I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,D/TP/MmsProvider( 1482): Query uri=content://mms, match=0, calling pid = 2131
,I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4861): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/TP/SmsProvider( 1482): query,matched:0, calling pid = 2131,
D/TP/SmsProvider( 1482): match 0:Elapsed time : 0.912 ms
,D/TP/MmsProvider( 1482): Query uri=content://mms, match=0, calling pid = 2131
,W/IcingInternalCorpora( 2131): getNumBytesRead when not calculated.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1840): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,D/a       ( 1840): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,E/SMD     (  289): DCD OFF
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/art     ( 1840): Explicit concurrent mark sweep GC freed 26502(2012KB) AllocSpace objects, 37(592KB) LOS objects, 40% free, 9MB/16MB, paused 1.248ms total 90.115ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/GCoreFlp( 1840): No location to return for getLastLocation()
,W/FusedLocationProvider( 1840): location=null
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/SIP     ( 1482): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,E/File    ( 1482): fail readDirectory() errno=2
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1020): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1020): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1020): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1840): [251] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2131): Restart initialization of location
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1840): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1840): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/GCoreFlp( 1840): No location to return for getLastLocation()
,W/FusedLocationProvider( 1840): location=null
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4904): MountEmulatedStorage(),
E/Zygote  ( 4904): v2
I/libpersona( 4904): KNOX_SDCARD checking this for 1000
,I/libpersona( 4904): KNOX_SDCARD not a persona
,I/SELinux ( 4904): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4904 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 4904): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4904): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  305): Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 20.539ms
,D/TimaKeyStoreProvider( 4904): TimaSignature is unavailable
,D/ActivityThread( 4904): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.816ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 18.205ms
,E/MTPRx   ( 4904): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedState
D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1020): mCursor = null
,V/MTPRx   ( 4904): sealedState: false
V/MTPRx   ( 4904): sealedUsbMassStorageState: false
E/MTPRx   ( 4904): check value of boot_completed is1
E/MTPRx   ( 4904): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4904): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4904): Status for mount/Unmount :removed
E/MTPRx   ( 4904): SDcard is not available
,W/MTPRx   ( 4904): value of connected istrue
W/MTPRx   ( 4904): value of configured istrue
W/MTPRx   ( 4904): value of mtpEnabled istrue
W/MTPRx   ( 4904): value of ptpEnabled isfalse
,E/MTPRx   ( 4904): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4904): mFirstTime: false
,D/Mms/Contact( 4781): sContactsObserver.onChange(),selfUpdate=false
,D/        ( 4904): MTP: reading debug level property
,E/MTPJNIInterface( 4904): Getting CryptionKey from JAVA
E/MTPRx   ( 4904): currentUserId is 0
,D/Mms/ContactsCache( 4781): [start]    invalidate() consume time = 1104.843698
,D/Mms/Contact( 4781): performUpdate:widgetCount=0
,D/Mms/ContactsCache( 4781): [end]    invalidate() consume time = 0.871615
,I/ValidateNoPeople( 1020): mEvictionCount: 0
,E/MTPRx   ( 4904): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4904): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 4904): is_Privatemode is NOT 1
,D/SettingsProvider( 1020): name = boot_time_connected
,E/MTPRx   ( 4904): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 4904): noti = 17
,D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,D/SecContentProvider( 1020): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4904): sending MTP_ICON_ENABLED to stack
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1020): name = mtp_running_status
,D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,E/MTPRx   ( 4904): else part ... so first time!!!
,E/MTPPlaObsrvr( 4904): inside setContext()
E/MTPPlaObsrvr( 4904):  inside createplafiles
,I/SecKeyguardClockSingleView( 1178): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 4904): playlist count is0
,E/MTPPlaObsrvr( 4904):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4904):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 4904): Inside registerContentObserver
,E/MtpAdbObserver( 4904): inside setContext()
E/MtpAdbObserver( 4904): Inside registerContentObserver
W/Settings( 4904): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1020): name = mtp_running_status
,D/SettingsProvider( 1020): name = mtp_usb_conditions_met
,E/MtpService( 4904): onCreate.
,V/MtpMediaDBManager( 4904): inside deleteAllDB
,E/MtpService( 4904): < MTP > Registering BroadCast receiver :::::
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 4904): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,D/MtpService( 1227): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 4904): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 4904): onStartCommand.
,W/MTPRx   ( 4904): calling native method
,E/MTPJNIInterface( 4904): < MTP > Registering BroadCast receiver :::::
E/MtpService( 4904): handleMessage. msg= { when=-2ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/ContextImpl( 3227): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,E/MTPJNIInterface( 4904): < MTP > Registering BroadCast receiver :::::::
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4925): MountEmulatedStorage()
,E/Zygote  ( 4925): v2
I/ActivityManager( 1020): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4925 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/libpersona( 4925): KNOX_SDCARD checking this for 1000
I/libpersona( 4925): KNOX_SDCARD not a persona
,I/SELinux ( 4925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,V/MtpMediaDBManager( 4904): inside Thread updateDB
,E/MTPJNIInterface( 4904): noti = 10
W/MTPRx   ( 4904): calling native method,
E/MTPRx   ( 4904): Checking the driver time out
E/MTPJNIInterface( 4904): noti = 2
,D/        ( 4904): deleting sockets before message queue initialization
D/        ( 4904): event handler thread is created, so set the flag
,I/SELinux ( 4925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/MTPRx   ( 4904): called native method
E/MTPJNIInterface( 4904): setting Media scanner status0
E/MTPJNIInterface( 4904): After setting Media scanner status0
E/MtpService( 4904): onStartCommand.
I/DBG_DM  ( 3537): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,E/MtpService( 4904): handleMessage. msg= { when=-2ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,I/DBG_DM  ( 3537): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,W/MTPRx   ( 4904): notification from stack 1
E/DBG_DM  ( 3537): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,E/        ( 4904): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4904): Getting media scanner status0
,E/MTPJNIInterface( 4904): DeviceName is Thali Test (Galaxy A3)
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,D/TimaKeyStoreProvider( 4925): TimaSignature is unavailable
,D/ActivityThread( 4925): Added TimaKeyStore provider
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 23625(1393KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 2.543ms total 132.429ms
,I/art     ( 1020): WaitForGcToComplete blocked for 132.081ms for cause Explicit
,E/MtpMediaDBManager( 4904): count : 26
,W/MtpMediaDBManager( 4904): sending db update complete noti to stack
E/MTPJNIInterface( 4904): noti = 29
,E/SQLiteLog( 4904): (5) database is locked
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,E/SQLiteLog( 4904): (5) database is locked
,I/DBG_DM  ( 3537): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3537): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,I/DBG_DM  ( 3537): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
E/MTPJNIInterface( 4904): Status for mount/Unmount :removed
E/MTPJNIInterface( 4904): SDcard is not available
,I/DBG_DM  ( 3537): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3537): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 8
,I/DBG_DM  ( 3537): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,E/        ( 4904): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,I/DBG_DM  ( 3537): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,E/MTPJNIInterface( 4904): Status for mount/Unmount :removed
E/MTPJNIInterface( 4904): SDcard is not available
E/SQLiteLog( 4904): (21) API call with NULL database connection pointer
E/SQLiteLog( 4904): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4904): (21) API call with NULL database connection pointer
E/SQLiteLog( 4904): (21) misuse at line 100726 of [9491ba7d73]
,E/SQLiteLog( 4904): (21) API call with NULL database connection pointer
E/SQLiteLog( 4904): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4904): (21) API call with NULL database connection pointer
E/SQLiteLog( 4904): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4904): notification from stack 2
,D/        ( 4904): [mtp_init_device] Library open with 32 bits.
D/        ( 4904): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4904): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 4904): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4904):  [sua_support_present:1287] returning false 
D/        ( 4904): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,D/TMNetworkReceiver( 4925): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
,D/TMNetworkReceiver( 4925): TMNetworkReceiver.onReceive() Enter
,I/DBG_DM  ( 3537): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 0

```
