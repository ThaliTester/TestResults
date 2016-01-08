#### Test 50242285ae22b3b_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
D/ConnectivityManager.CallbackHandler( 2042): CM callback handler got msg 524290
--------- beginning of system
D/ConnectivityService( 1021): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1021): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
D/ConnectivityService( 1021): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1021): apparently satisfied.  currentScore=60
D/WIFI_P2P( 1021): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/WIFI_P2P( 1021): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
W/ActivityManager( 1021): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/WifiP2pService( 1021): InactiveState{ what=143415 }
D/WifiP2pService( 1021): P2pEnabledState{ what=143415 }
D/WifiP2pService( 1021): DefaultState{ what=143415 }
D/ConnectivityService( 1021): Got NetworkFactory Messenger for WIFI_P2P
D/Tethering( 1021): Boot complete.
E/WifiStateMachine( 1021): Blacklist file delete
V/EnterpriseBillingEngine( 1021): ACTION_BOOT_COMPLETED
V/EnterpriseBillingEngine( 1021): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage( 1021): getCurrentActiveProfiles - start - 
D/ConnectivityService( 1021): Got NetworkFactory Messenger for WIFI
V/EnterpriseBillingPolicyStorage( 1021): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine( 1021): handleAllprofiles - end
D/SSRM:a  ( 1021): DeviceInfo:: 000000000000
D/SSRM:a  ( 1021): SettingsAirViewInfo:: 000000000
E/USB_UICC(  298): Timeout! No signal received. Retry num = 25
E/SMD     (  290): DCD OFF
D/UsbHostNotification( 1021): boot completed
D/UsbHostRestrictor( 1021): mBootCompletedReceiver onReceive
D/UsbHostRestrictor( 1021): initSetUsbBlock STARTED
,D/SensorService( 1021): [SO] -0.402 0.057 9.883
W/ActivityManager( 1021): userId = 0, bbcId = -10000
D/UsbHostRestrictor( 1021): SIM was never inserted
D/UsbHostRestrictor( 1021): writableHostSysNode[false]
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/UsbHostRestrictor( 1021): Can NOT Write Disable Sys Node to [ON]
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
D/PersonaManagerService( 1021): ACTION_BOOT_COMPLETED
E/PersonaManagerServiceHandler( 1021):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
D/WIFI    ( 1021): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/WIFI    ( 1021): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/KnoxKeyguardUpdateMonitor( 1021): onBootComplete
I/KnoxKeyguardUpdateMonitor( 1021): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1021): onTrustChanged user:0, enable:false
D/UsbStorageNotification( 1021): boot completed
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/KeyguardViewMediator( 1179): onTrustChanged( Showing = false , userId = 0 )
D/StorageNotification( 1179): boot completed
D/GpsLocationProvider( 1021): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
D/GpsLocationProvider_ex( 1021): BOOT_COMPLETED native_init 
D/GpsLocationProvider( 1021): set_capabilities_callback: 55u
I/qcom-bluetooth( 2835): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
I/qcom-bluetooth( 2839): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
I/bt_vendor( 2619): bluetooth satus is on
D/bt_userial_mct( 2619): userial_open(port:0)
I/bt_vendor( 2619): bt-vendor : BT_VND_OP_USERIAL_OPEN
I/bt_vendor( 2619): Done intiailizing UART
I/bt_vendor( 2619): Done intiailizing UART
I/bt_userial_mct( 2619): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 2619): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 2619): Entering userial_read_thread()
I/        ( 2619): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2619): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2619): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2619): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2619): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2619): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2619): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2619): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2619): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2619): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2619): BTE_InitTraceLevels -- TRC_SAP
I/        ( 2619): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2619): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2619): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2619): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2619): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 2619): BTE_InitTraceLevels -- TRC_PROTOCOL
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
E/LocSvc_api_v02( 1021): I/locClientOpen:2279]: Service instance id is -1
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/Geofence_Adapter( 1021): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter( 1021): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1021): BOOT_COMPLETED native_cleanup 
D/StatusBarManagerService( 1021): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
D/PhoneStatusBar( 1179): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2847): MountEmulatedStorage()
E/Zygote  ( 2847): v2
I/libpersona( 2847): KNOX_SDCARD checking this for 1000
I/libpersona( 2847): KNOX_SDCARD not a persona
I/SELinux ( 2847): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=2847 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 2847): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2847): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/bt-l2cap( 2619): l2c_link_processs_ble_num_bufs 16
E/bt-btm  ( 2619): BTM_SecRegister:p_cb_info->p_le_callback == 0xa44e5ead 
E/bt-btm  ( 2619): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa44e5ead 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 2847): TimaSignature is unavailable
D/ActivityThread( 2847): Added TimaKeyStore provider
D/BluetoothAdapterProperties( 2619): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
E/bt-btif ( 2619): L2CAP - L2CA_Registe
E/bt-btif ( 2619): BTM_SEC_REG[8]: id 29, is_orig 0, psm 0x0003] (up to 21 
D/BluetoothAdapterProperties( 2619): Address is:08:EC:A9:50:76:27
E/BluetoothServiceJni( 2619): populateRssiValuesNative
I/bluedroid( 2619): getModelRssiValues
E/BluetoothServiceJni( 2619): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 2619): modelRssiValuesCallback, low, mid, high = -70,-60,127
D/BluetoothAdapterProperties( 2619): Name is: Thali Test (Galaxy A3)
D/SettingsProvider( 1021): name = bluetooth_name
D/BluetoothAdapterProperties( 2619): Scan Mode:20
D/BluetoothAdapterProperties( 2619): Discoverable Timeout:120
D/BluetoothAdapterProperties( 2619): LE Address is:C8:D9:53:A0:EC:4E
E/bt-btif ( 2619): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2619): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 2619): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 2619): btif_sock_init: !vhci_init
E/LocSvc_ApiV02( 1021): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
D/IOP_DB_BT( 2619): db_open: file /etc/bluetooth/iop_bt.db
E/bt_mct  ( 2619): hci lib postload completed
E/LocSvc_ApiV02( 1021): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
D/qmi_secgps_clnt( 1021): qmi_secgps_client_init()
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/IOP_DB_BT( 2619): db_open: db_open : handle 3027984400l, read 13894 bytes onto local cache
D/IOP_DB_BT( 2619): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 2619): db_query: result 1
I/        ( 2619): iop_db_open: iop_db_open status 0
D/bte_conf( 2619): Device ID record 1 : primary
D/bte_conf( 2619):   vendorId            = 0075
D/bte_conf( 2619):   vendorIdSource      = 0001
D/bte_conf( 2619):   product             = 0100
D/bte_conf( 2619):   version             = 0200
D/bte_conf( 2619):   clientExecutableURL = 
D/bte_conf( 2619):   serviceDescription  = 
D/bte_conf( 2619):   documentationURL    = 
D/bte_conf( 2619): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 2619): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 2619): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2619): ScanMode =  20
D/BluetoothAdapterProperties( 2619): State =  11
D/SecContentProvider( 1021): uri = 3 selection = isDiscoverableEnabled
D/BluetoothAdapterProperties( 2619): Setting state to 12
I/BluetoothAdapterState( 2619): Bluetooth adapter state changed: 11-> 12
D/qmi_secgps_clnt( 1021): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
D/qmi_secgps_clnt( 1021): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
D/qmi_secgps_clnt( 1021): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
D/BluetoothAdapterProperties( 2619): Scan Mode:21
D/SettingsProvider( 1021): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1002
D/BluetoothAdapterProperties( 2619): Discoverable Timeout:120
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/BluetoothAdapterService( 2619): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2619): updateAdapterState state is 12
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapterService( 2619): Autoconnection is available 
D/BluetoothAdapterService( 2619): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 2619): starting service from this receiver
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
I/BluetoothAdapterState( 2619): Entering On State from state = 11
D/BluetoothAdapter( 1460): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1460): onBluetoothStateChange: Bluetooth is on
I/BluetoothPbapService( 2619): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
D/BluetoothAdapter( 1451): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1451): onBluetoothStateChange: Bluetooth is on
I/art     ( 1633): Explicit concurrent mark sweep GC freed 6994(347KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 781us total 47.844ms
D/BluetoothAdapter( 1021): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1021): onBluetoothStateChange: Bluetooth is on
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
D/BluetoothAdapter( 2619): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2619): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 2186): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2186): onBluetoothStateChange: Bluetooth is on
D/BluetoothA2dp( 1021): onBluetoothStateChange: up=true
D/BluetoothA2dp( 2619): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1475): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1475): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1179): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1179): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1811): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1811): onBluetoothStateChange: Bluetooth is on
W/DriveInitializer( 2042): Awaiting to be initialized
W/InputMethodManagerService( 1021): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1021): [BT Setting State] State =12
I/InputMethodManagerService( 1021): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
W/ContextImpl( 2847): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
D/BluetoothTile( 1179):  onBluetoothStateChange:
I/SamsungIME( 1836): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothTile( 1179):  handleUpdatestate:false name:null
D/BluetoothHeadset( 1451): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2b133668, true
D/BluetoothHeadset( 1451): registerMessageListener
I/BluetoothPbapService( 2619): Handler(): got msg=1
W/DriveInitializer( 2042): Background init thread started
D/BluetoothTile( 1179): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1179):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1179):  getBluetoothState : 12
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
D/SecContentProvider( 1021): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/BluetoothTile( 1179):  handleUpdatestate:false name:null
I/splitIntent( 1021): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=126, mSplitNum[2]=164, mBgSplitQueueNum=3 divideNum= 37 r.nextReceiver= 50 receivers.size=201
I/splitIntent( 1021): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/BluetoothTile( 1179):  handleUpdatestate:false name:null
E/LocSvc_utils_cfg( 1021): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
V/BluetoothPbapService( 2619): PBAP Service initSocket try: 0
E/LocSvc_ApiV02( 1021): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
D/StatusBarManagerService( 1021): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/StatusBarManagerService( 1021): setIconVisibility slot=bluetooth visible=true
D/BluetoothMapMasInstance( 2619): set MAP SDP message type : 1
D/PhoneStatusBar( 1179): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
E/LocSvc_ApiV02( 1021): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
I/libpersona( 2874): KNOX_SDCARD checking this for 10097
E/Zygote  ( 2874): MountEmulatedStorage()
I/libpersona( 2874): KNOX_SDCARD not a persona
E/Zygote  ( 2874): v2
I/SELinux ( 2874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/LocSvc_ApiV02( 1021): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
I/SELinux ( 2874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/qmi_secgps_clnt( 1021): SECGPS: Set AGPS Mode : 7
D/qmi_secgps_clnt( 1021): SECGPS: send a qmi message to secgps_server OK
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
E/SELinux ( 2874): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2042): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
I/ActivityManager( 1021): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2874 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/LocSvc_ApiV02( 1021): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1021): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
E/LocSvc_ApiV02( 1021): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1021): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
W/BluetoothAdapter( 2619): getBluetoothService() called with no BluetoothManagerCallback
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/LocSvc_ApiV02( 1021): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/qmi_secgps_clnt( 1021): SECGPS: Set XTRA enable : 1
D/qmi_secgps_clnt( 1021): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1021): SECGPS: Set GNSS RF CONFIG : 1
D/qmi_secgps_clnt( 1021): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1021): SECGPS: Set CERT TYPE : 15
D/qmi_secgps_clnt( 1021): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1021): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
E/Zygote  ( 2888): MountEmulatedStorage()
I/libpersona( 2888): KNOX_SDCARD checking this for 10081
E/Zygote  ( 2888): v2
I/libpersona( 2888): KNOX_SDCARD not a persona
I/SELinux ( 2888): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2888 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 2888): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/SELinux ( 2888): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 2874): TimaSignature is unavailable
D/ActivityThread( 2874): Added TimaKeyStore provider
D/AndroidRuntime( 2833): 
D/AndroidRuntime( 2833): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2833): CheckJNI is OFF
D/AndroidRuntime( 2833): readGMSProperty: start
D/AndroidRuntime( 2833): readGMSProperty: already setted!!
D/AndroidRuntime( 2833): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 2833): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 2833): readGMSProperty: end
D/AndroidRuntime( 2833): addProductProperty: start
E/Zygote  ( 2905): MountEmulatedStorage()
E/Zygote  ( 2905): v2
I/libpersona( 2905): KNOX_SDCARD checking this for 1101
I/libpersona( 2905): KNOX_SDCARD not a persona
I/SELinux ( 2905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2905 uid=1101 gids={41101, 9997} abi=armeabi-v7a
D/BluetoothSocket( 2619): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
I/SELinux ( 2905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/BluetoothSocket( 2619): bindListen(), new LocalSocket 
D/BluetoothSocket( 2619): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2619): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d5c330a
D/BluetoothSocket( 2619): channel: 5
W/BluetoothAdapter( 2619): getBluetoothService() called with no BluetoothManagerCallback
E/SELinux ( 2905): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/HeadsetService( 2619): registerMessageListener
D/HeadsetService( 2619): registerMessageListener
D/HeadsetStateMachine( 2619): Disconnected process message: 70
D/HeadsetStateMachine( 2619): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3b8af77b
I/Telecom ( 1451): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1451): BluetoothPhoneService: updateHeadsetWithCallState
I/Telecom ( 1451): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1451): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1451): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
E/LocSvc_ApiV02( 1021): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1021): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
E/LocSvc_ApiV02( 1021): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
D/HeadsetStateMachine( 2619): Disconnected process message: 9
D/HeadsetStateMachine( 2619): mNumActive: 0 mNumHeld: 0 mCallState: 6
I/art     (  309): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 26.715ms
E/LocSvc_ApiV02( 1021): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
E/LocSvc_ApiV02( 1021): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
D/BluetoothSocket( 2619): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothSocket( 2619): bindListen(), new LocalSocket 
D/BluetoothSocket( 2619): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2619): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15b50998
D/BluetoothSocket( 2619): channel: 19
D/BluetoothPbapService( 2619): PBAP Socket is BluetoothServerSocket
D/TimaKeyStoreProvider( 2888): TimaSignature is unavailable
D/ActivityThread( 2888): Added TimaKeyStore provider
D/audio_hw_primary(  285): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  285): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
E/HeadsetStateMachine( 2619): terminateScoUsingVirtualVoiceCall:No present call to terminate
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.960ms
I/ActivityManager( 1021): Killing 1398:com.sec.android.provider.emergencymode/u0a92 (adj 15): empty #31
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 18.292ms
W/ResourcesManager( 2888): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 2888): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 2888): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 2888): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 2888): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 2905): TimaSignature is unavailable
D/ActivityThread( 2905): Added TimaKeyStore provider
W/ResourcesManager( 2905): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
W/libprocessgroup( 1021): failed to open /acct/uid_10092/pid_1398/cgroup.procs: No such file or directory
V/SmartcardService( 2905): main Received broadcast
V/SmartcardService( 2905): Starting smartcard service after boot completed
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
I/ActivityManager( 1021): Killing 1560:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
V/DownloadManager( 1223): onReceive intent + android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2( 1021): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1021): mCursor = null
E/Zygote  ( 2938): MountEmulatedStorage()
E/Zygote  ( 2938): v2
I/libpersona( 2938): KNOX_SDCARD checking this for 1000
I/libpersona( 2938): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2938 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 2938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2938): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2938): TimaSignature is unavailable
D/ActivityThread( 2938): Added TimaKeyStore provider
D/MediaScannerReceiver( 1223): action: android.intent.action.BOOT_COMPLETED
W/libprocessgroup( 1021): failed to open /acct/uid_10052/pid_1560/cgroup.procs: No such file or directory
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
W/ContextImpl( 2938): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2959): MountEmulatedStorage()
I/libpersona( 2959): KNOX_SDCARD checking this for 10153
E/Zygote  ( 2959): v2
I/libpersona( 2959): KNOX_SDCARD not a persona
I/SELinux ( 2959): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2959 uid=10153 gids={50153, 9997} abi=armeabi-v7a
I/SELinux ( 2959): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2959): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 2959): TimaSignature is unavailable
D/ActivityThread( 2959): Added TimaKeyStore provider
D/SettingsProvider( 1021): name = next_alarm_formatted
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10081
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
W/ResourcesManager( 2959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/dhcpcd  ( 1757): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 1757): wlan0: no IPv6 Routers available
W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=10081
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/DriveInitializer( 2042): Background init thread ended
D/MediaScannerService( 1223): !@start scanning volume internal: [/system/media, /oem/media]
E/Zygote  ( 2976): MountEmulatedStorage()
E/Zygote  ( 2976): v2
I/libpersona( 2976): KNOX_SDCARD checking this for 1000
I/libpersona( 2976): KNOX_SDCARD not a persona
I/SELinux ( 2976): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 2976): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 2976): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2976 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 1917:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
E/USB_UICC(  298): Timeout! No signal received. Retry num = 26
D/TimaKeyStoreProvider( 2976): TimaSignature is unavailable
D/ActivityThread( 2976): Added TimaKeyStore provider
D/MtpService( 1223): updating state; isCurrentUser=true, mMtpLocked=false
D/TP/MmsProvider( 1475): Update uri=content://mms, match=0
D/TP/MmsProvider( 1475): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1475): need read changed broadcast:false
I/Mms:transaction( 2355): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2355): [start]    nonBlockingUpdateMessageIndicator() consume time = 4057.59979
I/Mms/ReservationManager( 2355): resetAfterConnected()
D/TP/MmsSmsProvider( 1475): query,matched:7, calling pid = 2355
D/TP/MmsSmsProvider( 1475): match 7:Elapsed time : 2.024 ms
D/Mms/MessagingNotification( 2355): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2355): isDefault true
E/ActivityThread( 2874): Failed to find provider info for flipboard.auth.internal.debug
E/ActivityThread( 2874): Failed to find provider info for flipboard.auth.internal
W/art     ( 2888): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 144.809ms
E/AffinityControl( 2833): AffinityControl: registerfunction enter
I/Mms/ReservationManager( 2355): getReservedSendMessageCount(): retMessageCount=0
D/TP/MmsProvider( 1475): Query uri=content://mms, match=0, calling pid = 2355
I/art     ( 1021): Explicit concurrent mark sweep GC freed 60082(3MB) AllocSpace objects, 27(1428KB) LOS objects, 33% free, 22MB/33MB, paused 19.110ms total 220.288ms
I/DrmEventReceiver( 1021): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1021): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
I/DrmEventReceiver( 1021): DrmEventReceiver : beginStartingService
I/System.out( 1021): start Service
W/libprocessgroup( 1021): failed to open /acct/uid_10134/pid_1917/cgroup.procs: No such file or directory
D/TP/MmsSmsProvider( 1475): query,matched:200, calling pid = 2355
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/TP/MmsSmsProvider( 1475): match 200:Elapsed time : 1.666 ms
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 2998): MountEmulatedStorage()
I/libpersona( 2998): KNOX_SDCARD checking this for 10043
E/Zygote  ( 2998): v2
I/libpersona( 2998): KNOX_SDCARD not a persona
I/SELinux ( 2998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=2998 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 2998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 ,
E/SELinux ( 2998): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 2833): Calling main entry com.android.commands.am.Am
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3011): MountEmulatedStorage()
E/Zygote  ( 3011): v2
I/libpersona( 3011): KNOX_SDCARD checking this for 10155
I/libpersona( 3011): KNOX_SDCARD not a persona
I/SELinux ( 3011): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3011 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
D/TimaKeyStoreProvider( 2998): TimaSignature is unavailable
D/ActivityThread( 2998): Added TimaKeyStore provider
I/SELinux ( 3011): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3011): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Killing 2156:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
D/Mms/SmsReceiverService( 2355): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/WVMDrmPlugIn(  284): WVMDrmPlugin::onInitialize : 2123
D/WVMDrmPlugIn(  284): WVMDrmPlugin::onSetOnInfoListener : add 2123
D/Mms/TelephonyPermission( 2355): isDefault true
D/Mms/SmsReceiverService( 2355): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2355): [start]    handleBootCompleted() consume time = 157.139584
D/TP/SmsProvider( 1475): query,matched:0, calling pid = 2355
D/TP/SmsProvider( 1475): match 0:Elapsed time : 1.006 ms
E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ResourcesManager( 2998): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 2998): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 3011): TimaSignature is unavailable
W/ResourcesManager( 2998): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
D/ActivityThread( 3011): Added TimaKeyStore provider
D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1021): mDVFSHelper.acquire()
I/SurfaceFlinger(  259): id=8 createSurf (16x16),-1 flag=20004, EimLayer(Di
I/SurfaceFlinger(  259): id=9 createSurf (16x16),-1 flag=20004, EimLayer(An
D/FocusedStackFrame( 1021): Set to : 0
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 1500
D/AndroidRuntime( 2833): Shutting down VM
I/DrmEventService( 1021): action event :android.intent.action.BOOT_COMPLETED
D/PhoneWindow( 1021): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1021): *FMB* installDecor flags : 25362712
D/Launcher.HomeView( 1500): onPause
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Launcher( 1500): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=10 createSurf (1x1),1 flag=404, iello
I/TimaServiceEventReceiver( 1021): TimaServiceEventReceiver : onReceive
D/SettingsProvider( 1021): name = block_emergency_message
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10043
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
W/ActivityManager( 1021): getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
I/ANDROID_DRM_FRWORKS_DrmManager(  284): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
W/ResourcesManager( 3011): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1475): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1475): deleteConversation threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1475): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1475): updateThread(), thread_id = 9223372036854775806
V/TP/MmsSmsDatabaseHelper( 1475): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
I/libpersona( 3041): KNOX_SDCARD checking this for 10334
E/Zygote  ( 3041): MountEmulatedStorage()
I/libpersona( 3041): KNOX_SDCARD not a persona
E/Zygote  ( 3041): v2
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
I/SELinux ( 3041): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3041): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3041): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1021): failed to open /acct/uid_10064/pid_2156/cgroup.procs: No such file or directory
I/ActivityManager( 1021): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3041 uid=10334 gids={50334, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/TP/MmsSmsProvider( 1475): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1475): need read changed broadcast:false
D/TimaKeyStoreProvider( 3041): TimaSignature is unavailable
I/ActivityManager( 1021): Killing 2171:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
I/art     ( 1475): Explicit concurrent mark sweep GC freed 34220(2MB) AllocSpace objects, 5(80KB) LOS objects, 45% free, 4MB/8MB, paused 1.097ms total 140.938ms
D/ActivityThread( 3041): Added TimaKeyStore provider
D/TP/SmsProvider( 1475): query,matched:51, calling pid = 2355
D/TP/SmsProvider( 1475): match 51:Elapsed time : 1.144 ms
D/Mms/Conversation( 2355): deleteTempConversation(),deleted=0
E/CscReceiver( 1475): onReceive android.intent.action.BOOT_COMPLETED
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SQLiteLog( 1223): (283) recovered 656 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
V/ActivityThread( 1500): updateVisibility : ActivityRecord{14a0c0d6 token=android.os.BinderProxy@3cb388e1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1021): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1500): onStop
V/ActivityThread( 1500): updateVisibility : ActivityRecord{14a0c0d6 token=android.os.BinderProxy@3cb388e1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/CscUpdateService( 1475): onStart
E/CscUpdateService( 1475): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1475): set_CSC_version
E/CscParser( 1475): update(): xml file exist
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1021): isKioskContainerExistOnDevice
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/[0]UMC:Core( 3011): onCreate(): 
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/SmsProvider( 1475): Update uri=content://sms/outbox, match=8
D/TP/MmsSmsProvider( 1475): need read changed broadcast:false
D/Launcher( 1500): onTrimMemory. Level: 20
E/Zygote  ( 3059): MountEmulatedStorage()
E/Zygote  ( 3059): v2
I/libpersona( 3059): KNOX_SDCARD checking this for 10002
I/libpersona( 3059): KNOX_SDCARD not a persona
I/SELinux ( 3059): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3059 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
I/SELinux ( 3059): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3059): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/SmsReceiverService( 2355): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2355): handle boot completed, sendFirstQueuedMessage()
D/Mms/MessagingNotification( 2355): isBlockingModeEnabled() = false, Zen mode = 0
D/[0]UMC:DeviceInfo( 3011): USA==US==
W/libprocessgroup( 1021): failed to open /acct/uid_10065/pid_2171/cgroup.procs: No such file or directory
W/art     ( 2833): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/CscUtil ( 1475): isWifiOnly = false
D/Mms/SmsReceiverService( 2355): [SIM-1]sendFirstQueuedMessage()
I/System.out( 1475): HandDataNode = null
I/CscUpdateService( 1475): PATH_CSCNAME =CustomerDataSet.CSCName
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
I/WifiCredService( 1312): onCreate
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 3059): TimaSignature is unavailable
D/ActivityThread( 3059): Added TimaKeyStore provider
D/BadgeProvider( 1583): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/CscUpdateService( 1475): This is normal boot : CSC not updated
D/MediaScanner( 1223): Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
E/CscParser( 1475): update(): xml file exist
D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1021): [SO] activate (ident=0xb7ee2728, enabled=0)
I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/CscGPS  ( 1475): CSCGPS.updateParameters
D/CscGPS  ( 1475): supl host : null
D/CscGPS  ( 1475): SUPL Host is null or invalid
D/CscGPS  ( 1475): supl_ver : null
D/CscGPS  ( 1475): SUPL Ver is null or invalid
D/CscGPS  ( 1475): supl port : null
D/CscGPS  ( 1475): SUPL PORT is null or invalid
D/CscGPS  ( 1475): LPP : null
D/CscGPS  ( 1475): LPP is null or invalid
D/CscGPS  ( 1475): CSC don't have any AGPS value.
D/TP/SmsProvider( 1475): query,matched:26, calling pid = 2355
D/SensorManager( 1021): unregisterListener ::   
D/TP/SmsProvider( 1475): match 26:Elapsed time : 1.351 ms
I/Sensors ( 1021): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1021): [SO] changed settle time [1]
D/SensorService( 1021): [SO] setDelay [66000000]
D/SensorService( 1021): [SO] activate (ident=0xb7ee2728, enabled=1)
D/SensorService( 1021): [SO] AR_init
I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
D/SensorManager( 1021): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/Mms/SmsReceiver( 2355): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2355): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2355): isDefault true
D/TP/MmsProvider( 1475): Query uri=content://mms, match=0, calling pid = 2355
I/CscUpdateService( 1475): same CSC Version
D/CscUtil ( 1475): Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
D/USER_AGENT( 3011): UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
D/[0]UMC:AdminManager( 3011): init - start
D/TP/MmsSmsProvider( 1475): query,matched:200, calling pid = 2355
D/[0]UMC:AdminManager( 3011): loadAdmins
D/TP/MmsSmsProvider( 1475): match 200:Elapsed time : 1.098 ms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/BadgeProvider( 1583): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1583): sendNotify, [notify] : null
D/BadgeProvider( 1583): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1583): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1583): update, [UpdateCount] : 1
D/Launcher.Model( 1500): reloadBadges entered.
D/SensorService( 1021): [SO] Reset Rotation Old [100], Init [1]
E/Zygote  ( 3078): MountEmulatedStorage()
E/Zygote  ( 3078): v2
I/libpersona( 3078): KNOX_SDCARD checking this for 1000
I/libpersona( 3078): KNOX_SDCARD not a persona
D/[0]UMC:AdminManager( 3011): init - end
I/SELinux ( 3078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/GSLBManager( 3011): migrateStoredUrlFromOldPref
I/SELinux ( 3078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3078 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3078): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/MessagingNotification( 2355): setBadgeCount(), count=0
D/WifiTimerReceiver( 1312): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1312): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1312): Action boot completed received
D/Mms/MessagingNotification( 2355): remove alarm
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/GSLBManager( 3011): migrateStoredUrlFromOldPref : Migration Not Needed
D/[0]UMC:UMCAdmin( 3011): deactivateUMCAdminIfNotRequired : -1
D/WifiCredService( 1312): Action received :android.net.wifi.WIFI_STATE_CHANGED
E/Zygote  ( 3096): MountEmulatedStorage()
I/libpersona( 3096): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3096): v2
I/libpersona( 3096): KNOX_SDCARD not a persona
I/SELinux ( 3096): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3096): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3096 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3096): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/WifiStateMachine( 1021): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1021): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1021): invaild command id : 215
E/[0]UMC:Utils( 3011): Admin not found in package com.samsung.knoxpb.mdm
E/[0]UMC:Utils( 3011): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 3011): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 3011): isContainer : 0
I/WebViewFactory( 3041): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/TimaKeyStoreProvider( 3078): TimaSignature is unavailable
D/ActivityThread( 3078): Added TimaKeyStore provider
V/MediaScanner( 1223): processDirectory :  /system/media
D/SensorService( 1021): [SO] -0.383 0.057 9.883
D/SensorService( 1021): [SO] [100 -> 255]
D/TP/SmsProvider( 1475): query,matched:0, calling pid = 2355
D/EnterpriseDeviceManagerService( 1021): isManagedProfileUser(): userId = 0
D/TP/SmsProvider( 1475): match 0:Elapsed time : 3.232 ms
D/Mms/MessagingNotification( 2355): updateAllHistoryAsRead()
I/ActivityManager( 1021): Killing 2186:com.vlingo.midas/u0a28 (adj 15): empty #31
E/[0]UMC:UMCAdmin( 3011): No active admin owned by uid 10155
D/[0]UMC:UMCAdmin( 3011): isContainer : 0
D/TP/SmsProvider( 1475): query,matched:0, calling pid = 2355
D/TP/SmsProvider( 1475): match 0:Elapsed time : 0.842 ms
I/LibraryLoader( 3041): Loading: webviewchromium
I/LibraryLoader( 3041): Time to load native libraries: 9 ms (timestamps 2875-2884)
I/LibraryLoader( 3041): Expected native library version number "",actual native library version number ""
D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1021): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
D/[0]UMC:UMCAdmin( 3011): deactivateUMCAdmin - UMC App Admin deactivated
D/TimaKeyStoreProvider( 3096): TimaSignature is unavailable
D/ActivityThread( 3096): Added TimaKeyStore provider
D/[0]UMC:CoreReceiver( 3011): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 3011):  check PreETag 
D/Mms/MessagingNotification( 2355): [end]    nonBlockingUpdateMessageIndicator() consume time = 530.560156
V/MediaScanner( 1223):  prescan time: 544ms (DB items: 138)
V/MediaScanner( 1223):     scan time: 63ms (Caching mode: true), (makeEntry time: 22ms ~34%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1223): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1223):    total time: 607ms
V/MediaScanner( 1223): checked files: 130  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1223): checkDefaultSounds
D/MediaScanner( 1223): system alarm_alert  : Vwiurug_etwofi5wgg
D/TP/SmsProvider( 1475): query,matched:51, calling pid = 2355
D/TP/SmsProvider( 1475): match 51:Elapsed time : 3.592 ms
W/ResourcesManager( 3096): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/Mms/MessagingNotification( 2355): isBlockingModeEnabled() = false, Zen mode = 0
W/libprocessgroup( 1021): failed to open /acct/uid_10028/pid_2186/cgroup.procs: No such file or directory
D/[0]UMC:ByodSetupStarter( 3011): Container ID : 0
D/BadgeProvider( 1583): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
V/[0]UMC:Utils( 3011): checkAppScreen() : com.example.hello
I/[0]UMC:Core( 3011): shutdown
I/art     ( 3011): System.exit called, status: 0
I/AndroidRuntime( 3011): VM exiting with result code 0, cleanup skipped.
E/SQLiteLog( 3078): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
D/Launcher.Model( 1500): reloadBadges entered.
D/MediaScanner( 1223): OK. alarm_alert is already exist in setting DB.
D/BadgeProvider( 1583): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1583): sendNotify, [notify] : null
D/MediaScanner( 1223): system notification_sound  : K_Oprkltf5wgg
D/BadgeProvider( 1583): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1583): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1583): update, [UpdateCount] : 1
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
I/NearbySettings( 1312): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1312): MountReceiver.onReceive - Internal Path
V/WebViewChromiumFactoryProvider( 3041): Binding Chromium to main looper Looper (main, tid 1) {2315faa2}
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/LibraryLoader( 3041): Expected native library version number "",actual native library version number ""
I/chromium( 3041): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/MediaScanner( 1223): OK. notification_sound is already exist in setting DB.
D/DSM     ( 3078): [Lines:107] Normal booted
D/DSM     ( 3078): [Lines:114] Boot completed
D/MediaScanner( 1223): system ringtone  : Wmfi_lpf_pwirywu5wgg
D/MediaScanner( 1223): OK. ringtone is already exist in setting DB.
E/Zygote  ( 3118): MountEmulatedStorage()
I/libpersona( 3118): KNOX_SDCARD checking this for 10082
E/Zygote  ( 3118): v2
I/libpersona( 3118): KNOX_SDCARD not a persona
I/SELinux ( 3118): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3118): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3118): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3118 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
I/BrowserStartupController( 3041): Initializing chromium process, renderers=0
W/art     ( 3041): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager( 1021): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3011)(adj 0) has died(46,683)
D/Mms/MessagingNotification( 2355): setBadgeCount(), count=0
D/Mms/MessagingNotification( 2355): remove alarm
D/SettingsProvider( 1021): name = personal_mode_enabled
D/TimaKeyStoreProvider( 3118): TimaSignature is unavailable
D/ActivityThread( 3118): Added TimaKeyStore provider
D/FactoryTestApp( 2596): [DummyFtClient$mBroadcastReceiver](2596) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2596): [DummyFtClient$mBroadcastReceiver](2596) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2596): [DummyFtClient$mBroadcastReceiver](2596) ACTION_MEDIA_SCANNER_FINISHED = Ignored
D/daemonapp( 1770): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1770): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/chromium( 3041): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 3041): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 3041): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/SurfaceFlinger(  259): id=7 Removed Mauncher (5/8)
I/SurfaceFlinger(  259): id=7 Removed Mauncher (-2/8)
D/MediaScannerService( 1223): !@done scanning volume internal
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3146): MountEmulatedStorage()
E/Zygote  ( 3146): v2
I/libpersona( 3146): KNOX_SDCARD checking this for 1000
I/libpersona( 3146): KNOX_SDCARD not a persona
I/SELinux ( 3146): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3146 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3146): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Killing 2212:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
E/SELinux ( 3146): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MediaScannerService( 1223): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/Mms/MessagingNotification( 2355): updateAllHistoryAsRead()
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
I/Adreno-EGL( 3041): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3041): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3041): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3041): Local Branch: 
I/Adreno-EGL( 3041): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3041): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3041):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/ResourcesManager( 1475): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1475): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1475): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1475): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1475): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/art     (  309): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 628us total 28.326ms
W/ResourcesManager( 1475): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/daemonapp( 1770): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1770): [MSC_Daemon]>>> ====================================================================================================================
I/ActivityManager( 1021): Killing 2269:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
D/comsamsunglog( 1770): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1770): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1770): [MSC_Daemon]>>> ====================================================================================================================
D/TP/SmsProvider( 1475): query,matched:0, calling pid = 2355
D/daemonapp( 1770): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1770): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
D/TP/SmsProvider( 1475): match 0:Elapsed time : 3.153 ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 17.573ms
D/SettingsProvider( 1021): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10157
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=10157
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 18.259ms
D/TimaKeyStoreProvider( 3146): TimaSignature is unavailable
D/ActivityThread( 3146): Added TimaKeyStore provider
I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
D/daemonapp( 1770): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/Mms/SmsReceiverService( 2355): [end]    handleBootCompleted() consume time = 241.252031
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started
D/daemonapp( 1770): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1770): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1770): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/SmartcardBootCompleteReceiver( 1312): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1312): Received intent with action - android.intent.action.BOOT_COMPLETED
E/daemonapp( 1770): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
I/ActivityManager( 1021): Killing 1526:com.android.printspooler/u0a132 (adj 15): empty #31
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1770): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1452261053528
W/ContextImpl( 1312): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
I/SmartcardBootCompleteReceiver( 1312): Broadcast sent with current lockscreen type
D/daemonapp( 1770): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1452282600000
W/ResourcesManager( 3146): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/daemonapp( 1770): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1770): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
E/USB_UICC(  298): Timeout! No signal received. Retry num = 27
D/daemonapp( 1770): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1452282600000
I/ServiceManager(  326): Waiting for service AtCmdFwd...
W/libprocessgroup( 1021): failed to open /acct/uid_10045/pid_2212/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10110/pid_2269/cgroup.procs: No such file or directory
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
W/libprocessgroup( 1021): failed to open /acct/uid_10132/pid_1526/cgroup.procs: No such file or directory
E/UpdateRequestReceiver( 3118): ignoring update request
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 82
D/daemonapp( 1770): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1452282600000
E/UpdateRequestReceiver( 3118): ignoring update request
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter finished
W/ActivityThread( 3146): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
D/MediaProvider( 1223): savePlaylistTableInBulkDeleter finished
D/[SBeam] ( 1312): SBeamEnabler.initPreferenceForSbeam : 0
E/UpdateRequestReceiver( 3118): ignoring update request
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
I/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
I/SettingSearch/SearchIntentReceiver( 1312): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1312): search setting db init!!
E/UpdateRequestReceiver( 3118): ignoring update request
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
D/MediaScanner( 1223): Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
E/UpdateRequestReceiver( 3118): ignoring update request
W/ContextImpl( 1312): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
D/comdaemonstockapp( 1770): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1770): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
E/UpdateRequestReceiver( 3118): ignoring update request
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
W/chromium( 3041): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
W/chromium( 3041): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
D/LcdtestApp( 3146): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
I/LcdtestApp( 3146): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
W/art     ( 3041): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3041): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 3041): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3041): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 3041): CordovaWebView is running on device made by: samsung
I/art     ( 1021): Explicit concurrent mark sweep GC freed 19231(943KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 2.167ms total 137.143ms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3184): MountEmulatedStorage()
I/libpersona( 3184): KNOX_SDCARD checking this for 10161
E/Zygote  ( 3184): v2
I/libpersona( 3184): KNOX_SDCARD not a persona
I/SELinux ( 3184): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3184 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3184): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3184): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
V/MediaScanner( 1223): processDirectory :  /storage/emulated/0
D/MediaScanner( 1223): Skipping:
D/MediaScanner( 1223): 7klwibgf7fvntblfd7(75ebcf7
D/TimaKeyStoreProvider( 3184): TimaSignature is unavailable
I/libpersona( 3199): KNOX_SDCARD checking this for 10088
D/ActivityThread( 3184): Added TimaKeyStore provider
I/libpersona( 3199): KNOX_SDCARD not a persona
E/Zygote  ( 3199): MountEmulatedStorage()
E/Zygote  ( 3199): v2
I/SELinux ( 3199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/MediaScanner( 1223): Skipping:
I/ActivityManager( 1021): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3199 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/MediaScanner( 1223): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
V/MediaScanner( 1223): processDirectory :  /storage/extSdCard
I/ActivityManager( 1021): Killing 1613:com.google.android.partnersetup/u0a14 (adj 15): empty #31
W/MediaScanner( 1223): Error opening directory, reason : Permission denied.
W/MediaScanner( 1223): 7klwibgf7fxlKdCbid7
I/SELinux ( 3199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3199): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/MediaScanner( 1223):  prescan time: 200ms (DB items: 26)
V/MediaScanner( 1223):     scan time: 20ms (Caching mode: true), (makeEntry time: 9ms ~45%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1223): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1223):    total time: 222ms
V/MediaScanner( 1223): checked files: 10  directories : 16  (I: 0, U: 0)
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3214): MountEmulatedStorage()
E/Zygote  ( 3214): v2
I/libpersona( 3214): KNOX_SDCARD checking this for 1000
I/libpersona( 3214): KNOX_SDCARD not a persona
I/SELinux ( 3214): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3214 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3214): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/TimaKeyStoreProvider( 3199): TimaSignature is unavailable
I/ActivityManager( 1021): Killing 2334:com.sec.modem.settings/1000 (adj 15): empty #31
D/ActivityThread( 3199): Added TimaKeyStore provider
E/SELinux ( 3214): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/art     ( 3041): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3041): Attempt to remove local handle scope entry from IRT, ignoring
I/SettingSearch/SearchIntentReceiver( 1312): BOOT_COMPLETED call InitSerachDBThread thread start!
D/MediaScannerService( 1223): !@done scanning volume external
D/FactoryTestApp( 2596): [DummyFtClient$mBroadcastReceiver](2596) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2596): [DummyFtClient$mBroadcastReceiver](2596) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 2596): [DummyFtClient$sendBootCompletedAndFinish](2596) ...
D/FactoryTestApp( 2596): [Support$Values.getString](2596) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2596): [ModuleCommon$isConnectionModeNone](2596) mConnectionMode = gsm
D/FactoryTestApp( 2596): [IPCWriterToSecPhoneService$ResponseWriter](2596) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 2596): [IPCWriterToSecPhoneService$connectToSecPhoneService](2596)  
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3214): TimaSignature is unavailable
W/ContextImpl( 2596): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
D/ActivityThread( 3214): Added TimaKeyStore provider
E/Zygote  ( 3232): MountEmulatedStorage()
I/libpersona( 3232): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3232): v2
I/libpersona( 3232): KNOX_SDCARD not a persona
I/SELinux ( 3232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3232): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
I/ActivityManager( 1021): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3232 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,W/libprocessgroup( 1021): failed to open /acct/uid_10014/pid_1613/cgroup.procs: No such file or directory
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/BluetoothMediaBrowser( 2619):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,E/Zygote  ( 3244): MountEmulatedStorage(),
E/Zygote  ( 3244): v2
I/libpersona( 3244): KNOX_SDCARD checking this for 10146
I/libpersona( 3244): KNOX_SDCARD not a persona
,I/ActivityManager( 1021): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3244 uid=10146 gids={50146, 9997} abi=armeabi-v7a
,I/SELinux ( 3244): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/TimaKeyStoreProvider( 3232): TimaSignature is unavailable
,D/ActivityThread( 3232): Added TimaKeyStore provider
,I/SELinux ( 3244): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3244): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_2334/cgroup.procs: No such file or directory
,D/BluetoothMediaBrowser( 2619): no now playing list
,D/BluetoothMediaBrowser( 2619):  getNowPlayingId now playing id : -1
,W/ResourcesManager( 3232): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 3244): TimaSignature is unavailable
,D/ActivityThread( 3244): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 3214): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/FactoryTestApp( 2596): [IPCWriterToSecPhoneService$onServiceConnected](2596) connected done,
D/FactoryTestApp( 2596): [IPCWriterToSecPhoneService$write](2596) Send Response Message to SecPhone
D/FactoryTestApp( 2596): [IPCWriterToSecPhoneService$write](2596) Response ��
,I/FOTA    ( 3232): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,D/AT_Distributor(  315): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,D/FactoryTestApp( 2596): [IPCWriterToSecPhoneService$handleMessage](2596) Send BOOTING COMPLETED done
,D/OpenGLRenderer( 3041): Render dirty regions requested: true
,D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
,D/PhoneWindow( 3041): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null,
D/PhoneWindow( 3041): *FMB* isFloatingMenuEnabled return false
,D/AT_Distributor(  315): SetAtdStatus(), 1_1_0
D/AT_Distributor(  315): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3184): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3184): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 3276): MountEmulatedStorage()
E/Zygote  ( 3276): v2
I/libpersona( 3276): KNOX_SDCARD checking this for 10088
I/libpersona( 3276): KNOX_SDCARD not a persona
,I/SELinux ( 3276): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3276): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3276): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3276 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3276): TimaSignature is unavailable
D/ActivityThread( 3276): Added TimaKeyStore provider
,V/JNIHelp ( 3184): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, NainActivit
,W/ActivityThread( 3184): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3184): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@251275d6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3184): Installed default security provider GmsCore_OpenSSL
,I/DBG_DM  ( 3232): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,I/DBG_DM  ( 3232): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 3232): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,D/InputDispatcher( 1021): Focus entered window: 3041
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3041): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 3041): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3041): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 3041): Enabling debug mode 0
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 28
,E/SMD     (  290): DCD OFF,
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3199): Setting receiver enabled: false
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220,
,E/ActivityThread( 3199): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 3232): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/dbxyzptlk.db240408.D.h( 3199): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/OverheatReceiver( 1179): onReceive() getAction : android.intent.action.BOOT_COMPLETED
,D/OverheatReceiver( 1179): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1179): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1179): isSafeMode = false
,I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
,I/Timeline( 3041): Timeline: Activity_idle id: android.os.BinderProxy@26565052 time:34268
,D/BootupListener( 1475): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1021): name = internet_call_settings_visibility,
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 1001
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
D/PhoneUtilsCommon( 1475): isSupportVoLTE is false.
I/ActivityManager( 1021): Displayed Component not be shown by security: +1s805ms
D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@7
,D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@11,
D/CustomFrequencyManagerService( 1021): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 1
,I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{2d706d26 u0 com.example.hello/.MainActivity t2} time:34280
W/ActivityManager( 1021): mDVFSHelper.release()
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,I/Telecom ( 1451): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,I/dbxyzptlk.db240408.D.h( 3199): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,I/DBG_DM  ( 3232): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3232): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,I/DBG_DM  ( 3232): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
I/DBG_DM  ( 3232): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
I/DBG_DM  ( 3232): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3232): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,E/Zygote  ( 3306): MountEmulatedStorage(),
E/Zygote  ( 3306): v2
I/libpersona( 3306): KNOX_SDCARD checking this for 10052,
I/dbxyzptlk.db240408.D.h( 3199): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
I/libpersona( 3306): KNOX_SDCARD not a persona
,I/SELinux ( 3306): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1021): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3306 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/DIAGMON_AGENT( 3214): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,I/SELinux ( 3306): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/Telecom ( 1451): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,E/SELinux ( 3306): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3232): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,I/SamsungIME( 1836): getCurrentCandidateView
,I/DBG_DM  ( 3232): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,I/DBG_DM  ( 3232): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DIAGMON_AGENT( 3214): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,W/ContextImpl( 3232): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,I/DBG_DM  ( 3232): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
D/TimaKeyStoreProvider( 3306): TimaSignature is unavailable
I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(155/onStartCommand)] 
D/ActivityThread( 3306): Added TimaKeyStore provider
,I/DBG_DM  ( 3232): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3184): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/chromium( 3041): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/dbxyzptlk.db240408.D.h( 3199): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,I/DIAGMON_AGENT( 3214): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,I/DIAGMON_AGENT( 3214): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 3214): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 3214): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/AndroidProtocolHandler( 3041): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,I/SurfaceFlinger(  259): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  259): id=10 Removed iello (-2/8)
,D/breakpad( 3199): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,V/audio_hw_primary(  285): adev_get_parameters: enter: keys - call_forwarding
,D/audio_hw_extn(  285): audio_extn_get_parameters: returns 
V/msm8974_platform(  285): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  285): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  285): key: 'call_forwarding' value: ''
,V/InCall  ( 1862): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1862): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1862): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,I/com.dropbox.sync.android.a( 3199): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,E/Zygote  ( 3331): MountEmulatedStorage()
E/Zygote  ( 3331): v2
I/libpersona( 3331): KNOX_SDCARD checking this for 1000
I/libpersona( 3331): KNOX_SDCARD not a persona
,I/SELinux ( 3331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/ScoverManager( 1862): serviceVersion : 16908288
,D/CoverManagerWhiteLists( 1021): isAllowedToUse : SIGNATURE_MATCH
,I/SELinux ( 3331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3331 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 3331): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/InCall  ( 1862): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@11
,D/CoverManagerWhiteLists( 1021): isAllowedToUse : SIGNATURE_MATCH,
I/Telecom ( 1451): ProximitySensorManager: Proximity wake lock already released
D/InCall  ( 1862): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,I/InCall  ( 1862): InCallPresenter -  - InCallState = NO_CALLS
I/InCall  ( 1862): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1862): InCallPresenter -  - dismissCoverDialog()...
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/DBG_DM  ( 3232): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,E/Tethering( 1021): No numeric data
I/InCall  ( 1862): CallSContextMotion - stopPutDownListening
,D/TimaKeyStoreProvider( 3331): TimaSignature is unavailable
,E/Tethering( 1021): No numeric data
D/ActivityThread( 3331): Added TimaKeyStore provider
,E/Tethering( 1021): No numeric data
,E/Tethering( 1021): No numeric data
,D/JsMessageQueue( 3041): Set native->JS mode to OnlineEventsBridgeMode
,E/Tethering( 1021): No numeric data
,E/Tethering( 1021): No numeric data
,D/InCall  ( 1862): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,D/PhoneStatusBarView( 1179): setCallBackground:0
,D/CoverManagerWhiteLists( 1021): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1862): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 3232): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/SamsungIME( 1836): Dismiss ExpandCandiate
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/VideoCallManager( 1862): Instantiating VideoCallManager
,D/[SBeam] ( 1312): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1312): SBeamEnabler.isSBeamSupported : EXIST
,I/chromium( 3041): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 3041): 
,E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1862): took 2.205156ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1862): took 5.234010ms for 0*0 texture 0
,I/GFX raster( 1862): took 11.300418ms for 176*144 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb7b0f1c0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7b0f148 counterpartCT=4 counterpartW=176 counterparth=144
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3356): MountEmulatedStorage(),
E/Zygote  ( 3356): v2
I/libpersona( 3356): KNOX_SDCARD checking this for 10014
I/libpersona( 3356): KNOX_SDCARD not a persona
,I/SELinux ( 3356): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3356): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3356): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3356 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3356): TimaSignature is unavailable,
D/ActivityThread( 3356): Added TimaKeyStore provider
,I/ActivityManager( 1021): Waited long enough for: ServiceRecord{e3617bf u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,E/Tethering( 1021): No numeric data
,E/Tethering( 1021): No numeric data
,E/Tethering( 1021): No numeric data
,D/jxcore_app_log( 3041): JniHelper::setJavaVM(0xb7764448), pthread_self() = -1210209832
,D/JX-Cordova( 3041): jxcore cordova android initializing
,E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,I/Adreno-EGL( 1862): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1862): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1862): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1862): Local Branch: 
I/Adreno-EGL( 1862): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1862): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1862):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/LocationManagerService( 1021): getProviders()=[passive]
,I/GFX GPU raster( 1862): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1862): took 0.400156ms for 320*61440 texture 37809
,I/com.dropbox.sync.android.ad( 3199): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,I/draw setup( 1862): took 10.845469ms for 320*240 texture 37809
E/GFX GPU raster( 1862): drawn
,I/GFX GPU raster ASTC( 1862): took 39.893175ms for 320*240 texture 12
I/GFX raster( 1862): took 39.970467ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb7b0f148 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb7b0f8c0 counterpartCT=4 counterpartW=320 counterparth=240
,E/Tethering( 1021): No numeric data
,I/SamsungIME( 1836): getDebugLevel  : 0x4f4c
,W/jxcore-log( 3041): Initializing JXcore engine
W/jxcore-log( 3041): JXcore engine is ready
,E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1862): eglCreateImageKHR: EGL_SUCCESS,
I/glCompressedTexImage2D( 1862): took 0.356511ms for 480*122880 texture 37813
I/draw setup( 1862): took 1.002031ms for 480*640 texture 37813
,E/GFX GPU raster( 1862): drawn,
,I/GFX GPU raster ASTC( 1862): took 7.890676ms for 480*640 texture 12
I/GFX raster( 1862): took 7.985833ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb7d512c0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7d51638 counterpartCT=4 counterpartW=480 counterparth=640
,E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1862): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1862): took 0.338802ms for 440*116864 texture 37809
I/draw setup( 1862): took 1.190729ms for 440*330 texture 37809
E/GFX GPU raster( 1862): drawn
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/GFX GPU raster ASTC( 1862): took 4.791979ms for 440*330 texture 12
I/GFX raster( 1862): took 4.871147ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb7d417e8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb7d66038 counterpartCT=4 counterpartW=440 counterparth=330
,E/Zygote  ( 3383): MountEmulatedStorage()
,E/Zygote  ( 3383): v2
I/libpersona( 3383): KNOX_SDCARD checking this for 10008
I/libpersona( 3383): KNOX_SDCARD not a persona
,I/SELinux ( 3383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3383 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 3383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3383): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/audit   ( 1834): type=1400 msg=audit(1452261055.321:205): avc:  denied  { ioctl } for  pid=3372 comm="Thread-383" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1834):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1834): type=1300 msg=audit(1452261055.321:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9e1a98e8 items=0 ppid=309 ppcomm=main pid=3372 auid=4294967295 uid=10334 gid=10334 euid=10334 suid=10334 fsuid=10334 egid=10334 sgid=10334 fsgid=10334 ses=4294967295 tty=(none) comm="Thread-383" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1834): type=1320 msg=audit(1452261055.321:205): 
,W/jxcore-log( 3041): Starting JXcore engine
,V/VibratorService( 1021): hasVibrator - useVibetonz: true
,D/TimaKeyStoreProvider( 3383): TimaSignature is unavailable
E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
D/ActivityThread( 3383): Added TimaKeyStore provider
,I/GFX GPU raster( 1862): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1862): took 5.260782ms for 480*163840 texture 37811
W/NotificationAccessSettings( 1312): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,I/draw setup( 1862): took 5.759948ms for 480*640 texture 37811
E/GFX GPU raster( 1862): drawn
,V/VibratorService( 1021): hasVibrator - useVibetonz: true
,I/GFX GPU raster ASTC( 1862): took 11.395676ms for 480*640 texture 12
I/GFX raster( 1862): took 11.482395ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb7d3c458 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7d66078 counterpartCT=4 counterpartW=480 counterparth=640
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,V/VibratorService( 1021): hasVibrator - useVibetonz: true
,W/ResourcesManager( 1312): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Zygote  ( 3400): MountEmulatedStorage()
I/libpersona( 3400): KNOX_SDCARD checking this for 10090
E/Zygote  ( 3400): v2
I/libpersona( 3400): KNOX_SDCARD not a persona
,I/SELinux ( 3400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3400): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3400 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144,
,I/GFX construct_block_size_descriptor_2d second part( 1862): took 2.121510ms for 0*0 texture 0,
F/libc    ( 3041): Fatal signal 11 (SIGSEGV), code 1, fault addr 0x0 in tid 3372 (Thread-383)
,I/GFX generate_partition_tables( 1862): took 7.629219ms for 0*0 texture 0
I/GFX raster( 1862): took 12.022552ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb7d3c510 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7d66088 counterpartCT=4 counterpartW=176 counterparth=144
,I/art     (  309): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 29.889ms
,I/SamsungIME( 1836): getDebugLevel  : 0x4f4c
,D/TimaKeyStoreProvider( 3400): TimaSignature is unavailable
D/ActivityThread( 3400): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 625us total 16.973ms
,I/ContactAccountLoggerTas( 3306): canRun() : Opted Out
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/DBG_POLICYDM( 3331): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,I/DBG_POLICYDM( 3331): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 16.919ms,
,I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 3331): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 3331): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 3331): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 3331): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 3331): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
D/elm:15121( 3400): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 3400): ELMEngine.ELMEngine( context ).
I/DBG_POLICYDM( 3331): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
D/elm:15121( 3400): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 3400): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 3400): ElmAgentService : onCreate()
I/DEBUG   (  281): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
I/DEBUG   (  281): Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
I/DEBUG   (  281): Revision: '1'
I/DEBUG   (  281): ABI: 'arm'
D/elm:15121( 3400): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/DEBUG   (  281): pid: 3041, tid: 3372, name: Thread-383  >>> com.example.hello <<<
I/DEBUG   (  281): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
D/elm:15121( 3400): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15121( 3400): BootCompletedState : startBootCompleted() call
D/elm:15121( 3400): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:15121( 3400): Get License : 0
D/elm:15121( 3400): ElmAgentService : onDestroy().
,I/ActivityManager( 1021): Killing 2374:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,V/EmergencyMode( 1420): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,I/DEBUG   (  281):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
I/DEBUG   (  281):     r4 9e1a7e78  r5 9e1a7e38  r6 b7dca130  r7 9e1a7e38
I/DEBUG   (  281):     r8 00000000  r9 9e1a7e74  sl 9e1a93d0  fp 9e1a7e1c
I/DEBUG   (  281):     ip 9ec7dba0  sp 9e1a7e00  lr 9e984308  pc b6ee9468  cpsr 600d0030
I/DEBUG   (  281): 
I/DEBUG   (  281): backtrace:
I/DEBUG   (  281):     #00 pc 00010468  /system/lib/libc.so (strlen+83)
I/DEBUG   (  281):     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
E/USB_UICC(  298): Timeout! No signal received. Retry num = 29
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_2374/cgroup.procs: No such file or directory
,I/SamsungIME( 1836): KeybaordView init() : load resources
,E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1862): took 2.167866ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1862): took 6.242501ms for 0*0 texture 0
,I/GFX raster( 1862): took 10.784532ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb7d51418 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7d51810 counterpartCT=4 counterpartW=176 counterparth=144
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/ScoverManager( 1862): registerListener
,D/ScoverManager( 1312): serviceVersion : 16908288
,D/CoverManagerWhiteLists( 1021): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManagerWhiteLists( 1021): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1021): registerListenerCallback : binder = android.os.BinderProxy@3be2eec4, pid : 1862, uid : 1001, type : 1
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,I/ActivityManager( 1021): Killing 2387:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,I/Velvet.VelvetFactory( 3306): refreshing search history.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/InCall  ( 1862): InCallPresenter -  - Finished InCallPresenter.setUp
,I/SamsungIME( 1836): getCurrentKeyboard
,I/SamsungIME( 1836): getTextKeyboard
,V/EmergencyMode( 1420): [EmergencyBase] setBootTime
,V/EmergencyMode( 1420): [EmergencyFactory] No Recovery State, kill my self.
,D/SamsungIME( 1836): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/System.out( 3199): Thread-409(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
,I/ActivityManager( 1021): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3439 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 3439): MountEmulatedStorage()
E/Zygote  ( 3439): v2
I/libpersona( 3439): KNOX_SDCARD checking this for 1000
I/libpersona( 3439): KNOX_SDCARD not a persona
,I/System.out( 3199): Thread-409(ApacheHTTPLog):isSBSettingEnabled false,
D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/System.out( 3199): Thread-409(ApacheHTTPLog):isShipBuild true,
I/System.out( 3199): Thread-409(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3199): Thread-409(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux ( 3439): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3439): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3439): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1021): failed to open /acct/uid_10127/pid_2387/cgroup.procs: No such file or directory
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10088
,I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1021): getStreamVolume 3 index 70
,I/MediaRouter( 3306): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
I/DBG_POLICYDM( 3331): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 3331): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT,
,I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 3331): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/TimaKeyStoreProvider( 3439): TimaSignature is unavailable
,I/DBG_POLICYDM( 3331): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/ActivityThread( 3439): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3331): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 3331): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 3331): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3459): MountEmulatedStorage()
,E/Zygote  ( 3459): v2
I/libpersona( 3459): KNOX_SDCARD checking this for 1000
I/libpersona( 3459): KNOX_SDCARD not a persona
I/SELinux ( 3459): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3459): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3459 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 2528:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/SELinux ( 3459): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Killing 2450:com.wsomacp/u0a23 (adj 15): empty #32,
I/ActivityManager( 1021): Killing 2406:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #33
,D/TimaKeyStoreProvider( 3459): TimaSignature is unavailable
E/YouTube MDX( 3184): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/ActivityThread( 3459): Added TimaKeyStore provider
,I/LockPatternUtils( 1312): isSmartCardAuthenticationAvailable: false
,D/Settings_Utils( 1312): isSupportVNFestival SM-A300FU XEO
,I/DBG_POLICYDM( 3331): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,I/CameraApp( 3439): CameraApp.onCreate()... mFeature : null
I/testFeature( 3439): Feature.Feature(context)
,I/testFeature( 3439): Feature.readInternalDefaultXml()
I/testFeature( 3439): ResetFeatureValue
,I/CameraFirmware_broadcast( 3439): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3439): CameraApp.getAppFeature()...
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3331): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/libpersona( 3481): KNOX_SDCARD checking this for 10095
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/libpersona( 3481): KNOX_SDCARD not a persona
E/Zygote  ( 3481): MountEmulatedStorage()
I/ActivityManager( 1021): Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3481 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
E/Zygote  ( 3481): v2
I/ActivityManager( 1021): Killing 2546:com.sec.android.app.camera/u0a135 (adj 15): empty #31
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/SELinux ( 3481): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_POLICYDM( 3331): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/SELinux ( 3481): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/DBG_POLICYDM( 3331): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 3331): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 3331): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
I/DBG_POLICYDM( 3331): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/SELinux ( 3481): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 3331): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 3331): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 3331): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 3331): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_FMMDM( 3459): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_POLICYDM( 3331): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
W/GAV2    ( 3306): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/DBG_POLICYDM( 3331): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/01/11/09:09:33
,I/DBG_POLICYDM( 3331): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 3331): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
W/libprocessgroup( 1021): failed to open /acct/uid_10139/pid_2528/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_2406/cgroup.procs: No such file or directory
W/ResourceType( 1312): Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,I/DBG_POLICYDM( 3331): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 3331): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/01/08/14:50:55
W/ResourceType( 1312): Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,I/DBG_POLICYDM( 3331): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/DBG_POLICYDM( 3331): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,D/TimaKeyStoreProvider( 3481): TimaSignature is unavailable,
D/ActivityThread( 3481): Added TimaKeyStore provider
W/GAV2    ( 3306): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ContactAccountLoggerTas( 3306): canRun() : Opted Out
,I/DBG_FMMDM( 3459): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3459): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3459): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/libprocessgroup( 1021): failed to open /acct/uid_10023/pid_2450/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10135/pid_2546/cgroup.procs: No such file or directory
I/AudioService( 1021): getStreamVolume 3 index 70
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3331): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,E/Zygote  ( 3497): MountEmulatedStorage()
E/Zygote  ( 3497): v2
,I/libpersona( 3497): KNOX_SDCARD checking this for 1000
I/libpersona( 3497): KNOX_SDCARD not a persona
,I/ActivityManager( 1021): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3497 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/PreloadFilterInstaller( 3481): uses FILTER_DB_VER_1
,I/SELinux ( 3497): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3497): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3497): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/SQLiteLog( 3481): (284) automatic index on titles(filter_id)
,D/TimaKeyStoreProvider( 3497): TimaSignature is unavailable
,D/ActivityThread( 3497): Added TimaKeyStore provider
,I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,I/FilterProviderReceiver( 3481): onReceive in FilterProviderReceiver
I/FilterProviderReceiver( 3481): onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/FavoriteContactNamesSup( 3306): get() : Execute runnable (UI thread)
I/ContactLabelSupplier( 3306): get() : Execute runnable (UI thread)
,E/Zygote  ( 3516): MountEmulatedStorage()
I/libpersona( 3516): KNOX_SDCARD checking this for 10098
E/Zygote  ( 3516): v2
I/libpersona( 3516): KNOX_SDCARD not a persona
,I/SELinux ( 3516): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3516 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 2326:com.sec.android.app.mt/1000 (adj 15): empty #31
I/SELinux ( 3516): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3516): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3516): TimaSignature is unavailable
,D/ActivityThread( 3516): Added TimaKeyStore provider
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4270, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
,D/PowerUI ( 1179): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1179): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/DBG_POLICYDM( 3331): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2619): Disconnected process message: 10
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
,W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3184): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache,
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3184): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,I/DBG_POLICYDM( 3331): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,W/ContextImpl( 3184): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_2326/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_LOG( 3497): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3497): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3497): new DMDBOpenHelper instance
,I/DBG_POLICYDM( 3331): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 3331): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 19344(1094KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 22MB/33MB, paused 2.589ms total 157.734ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/PCWCLIENTTRACE_DMContentProvider( 3497): [URIMatcher] - result : 2
,I/GAV2    ( 2708): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/DBG_POLICYDM( 3331): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,I/DBG_FMMDM( 3459): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3459): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3459): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,I/ContactLabelSupplier( 3306): get() : OptedIn = false
,I/WebViewFactory( 3306): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/PackageIntentReceiver( 3516): ACTION_BOOT_COMPLETED
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1021): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3553 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 3553): MountEmulatedStorage()
E/Zygote  ( 3553): v2
I/libpersona( 3553): KNOX_SDCARD checking this for 1000
I/libpersona( 3553): KNOX_SDCARD not a persona
,I/SELinux ( 3553): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Killing 1785:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/PackageIntentReceiver( 3516): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/SELinux ( 3553): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3553): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 3331): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 3331): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,V/VibratorService( 1021): hasVibrator - useVibetonz: true,
,D/TimaKeyStoreProvider( 3553): TimaSignature is unavailable
D/ActivityThread( 3553): Added TimaKeyStore provider
,E/Zygote  ( 3568): MountEmulatedStorage()
E/Zygote  ( 3568): v2
I/libpersona( 3568): KNOX_SDCARD checking this for 10099
I/libpersona( 3568): KNOX_SDCARD not a persona
,I/SELinux ( 3568): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 3568): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3568): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1021): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3568 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 2575:com.android.calendar/u0a131 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3568): TimaSignature is unavailable
D/ActivityThread( 3568): Added TimaKeyStore provider
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 30
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/ActivityManager( 1021): Killing 2638:com.android.keychain/1000 (adj 15): empty #31
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/LockPatternUtils( 1312): isSmartCardAuthenticationAvailable: false
,I/DBG_FMMDS( 3553): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_1785/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10131/pid_2575/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_2638/cgroup.procs: No such file or directory
,E/USB_UICC(  298): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  298): usb_uicc_init_qmi failed ! 
I/USB_UICC(  298): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  298): usb_uicc_cleanup, Issuing QMI deinit ... 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/ActivityManager( 1021): Killing 2675:com.android.chrome/u0a77 (adj 15): empty #31
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3596): MountEmulatedStorage()
E/Zygote  ( 3596): v2
I/libpersona( 3596): KNOX_SDCARD checking this for 10055
I/libpersona( 3596): KNOX_SDCARD not a persona
,I/SELinux ( 3596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3596 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 3596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3596): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/LibraryLoader( 3306): Loading: webviewchromium
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
I/LibraryLoader( 3306): Time to load native libraries: 4 ms (timestamps 6365-6369)
I/LibraryLoader( 3306): Expected native library version number "",actual native library version number ""
,I/DBG_FMMDS( 3553): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,I/ActivityManager( 1021): Killing 2749:com.android.email/u0a141 (adj 15): empty #31
,I/ActivityManager( 1021): Killing 2500:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3596): TimaSignature is unavailable
D/ActivityThread( 3596): Added TimaKeyStore provider
,W/art     ( 3306): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/MessageQueue( 3184): Handler (android.os.Handler) {a44ca40} sending message to a Handler on a dead thread
W/MessageQueue( 3184): java.lang.IllegalStateException: Handler (android.os.Handler) {a44ca40} sending message to a Handler on a dead thread
W/MessageQueue( 3184): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 3184): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 3184): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 3184): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 3184): 	at android.os.Handler.post(Handler.java:326)
W/MessageQueue( 3184): 	at ffw.a(SourceFile:327)
W/MessageQueue( 3184): 	at guw.a(SourceFile:120)
W/MessageQueue( 3184): 	at guf.c(SourceFile:26)
W/MessageQueue( 3184): 	at gui.run(SourceFile:297)
W/MessageQueue( 3184): 	at android.os.Handler.handleCallback(Handler.java:739)
W/MessageQueue( 3184): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/MessageQueue( 3184): 	at android.os.Looper.loop(Looper.java:145)
W/MessageQueue( 3184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/libprocessgroup( 1021): failed to open /acct/uid_10141/pid_2749/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10077/pid_2675/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10039/pid_2500/cgroup.procs: No such file or directory
,D/PCWCLIENTTRACE_DMContentProvider( 3497): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3553): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/DBG_FMMDS( 3553): [50.18.150420][Line:43][xdbDBInit] 
,D/UserAnalysis.PlaceProvider( 3596): PlaceProvider onCreate()
,W/ContextImpl( 1853): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/SecUISvc( 1853): Service started flags 0 startId 1
,D/SecUISvc( 1853): Thread created.
,I/System.out( 3199): pool-10-thread-1 calls detatch()
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/UserAnalysis.SecureDbManager( 3596): Key for secure DB is newly created
D/UserAnalysis.SecurePlaceDbHelper( 3596): SecurePlaceDbHelper() 
D/UserAnalysis( 3596): Create SecureDbHelper
,I/DBG_FMMDS( 3553): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,I/DBG_FMMDS( 3553): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,I/DBG_FMMDS( 3553): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,D/IntelligenceServiceApplication( 3596): onCreate()
I/DBG_FMMDS( 3553): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
D/UserAnalysis.UserAnalysisBroadcastReceiver( 3596): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,I/DBG_FMMDS( 3553): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/DBG_FMMDS( 3553): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3553): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3633): MountEmulatedStorage()
,E/Zygote  ( 3633): v2
I/libpersona( 3633): KNOX_SDCARD checking this for 10056
I/libpersona( 3633): KNOX_SDCARD not a persona
,I/SELinux ( 3633): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3633): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/IntelligenceServiceApplication( 3596): no applications having user consent for prediction
I/ActivityManager( 1021): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3633 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 3633): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidHttpClient( 3184): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
D/AndroidHttpClient( 3184): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 3184): Thread-448(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 3184): Thread-448(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3184): Thread-448(ApacheHTTPLog):isShipBuild true
I/System.out( 3184): Thread-448(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 3184): Thread-448(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
,W/ContextImpl( 1312): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
W/ContextImpl( 1312): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/SettingSearch/SearchIntentReceiver( 1312): InitSerachDBThread thread end!
I/FactoryTestApp( 2596): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3267)  
,W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/PlaceDetection v1.0.19 ( 3596): [PlaceDetection::stopService] Service stopped.
,I/FOTA_Client( 3383): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...,
,D/TimaKeyStoreProvider( 3633): TimaSignature is unavailable
,D/ActivityThread( 3633): Added TimaKeyStore provider
,I/FOTA_Client( 3383): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 3383): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 3383): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3654): MountEmulatedStorage(),
E/Zygote  ( 3654): v2
I/libpersona( 3654): KNOX_SDCARD checking this for 10013,
,I/SELinux ( 3654): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3654): KNOX_SDCARD not a persona
,I/SELinux ( 3654): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3654): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3654 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 1583:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,I/DEBUG   (  281): 
I/DEBUG   (  281): Tombstone written to: /data/tombstones/tombstone_03
E/        (  281): !@dumpstate -k -t -z -d -o /data/log/dumpstate_app_native -m 3041
,E/SharedPreferencesImpl( 1021): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver( 1021): Copying /data/tombstones/tombstone_03 to DropBox (SYSTEM_TOMBSTONE)
,D/TimaKeyStoreProvider( 3654): TimaSignature is unavailable
,D/ActivityThread( 3654): Added TimaKeyStore provider
,I/dumpstate( 3669): begin
,V/PlaceDetection v1.0.19 ( 3596): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
D/UserAnalysis.MyPlaceDbPreference( 3596): Constructor Preference
,D/PackageManager( 1021): [MSG] MCS_UNBIND
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.example.hello
W/ActivityManager( 1021):   Force finishing activity com.example.hello/.MainActivity
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/FocusedStackFrame( 1021): Set to : 0
D/InputDispatcher( 1021): Focused application set to: xxxx
,D/InputDispatcher( 1021): Focus left window: 3041,
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (737 us)
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10052,
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1021): failed to open /acct/uid_10068/pid_1583/cgroup.procs: No such file or directory,
,D/PhoneWindow( 1021): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 1021): *FMB* installDecor flags : 8519682
,V/OneTimeInitializerReceiver( 3654): OneTimeInitializerReceiver.onReceive
,I/qtaguid ( 3306): Tagging socket 39 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
,D/InputDispatcher( 1021): Focus entered window: 1021
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
W/ActivityManager( 1021): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/System.out( 3184): Thread-448 calls detatch(),
I/ActivityManager( 1021): Killing 2847:com.mobeam.barcodeService/1000 (adj 15): empty #31
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,I/ActivityManager( 1021): Killing 2874:flipboard.boxer.app/u0a97 (adj 15): empty #31,
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
V/OneTimeService( 3654): OneTimeService.onHandleIntent
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector( 1021): Build: samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
D/CrashAnrDetector( 1021): Hardware: MSM8916
D/CrashAnrDetector( 1021): Revision: 1
D/CrashAnrDetector( 1021): Bootloader: A300FUXXU1BOEC
D/CrashAnrDetector( 1021): Radio: unknown
D/CrashAnrDetector( 1021): Kernel: Linux version 3.10.49-4866174 (dpi@SWDD6204) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Fri May 29 20:06:40 KST 2015
D/CrashAnrDetector( 1021): 
D/CrashAnrDetector( 1021): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector( 1021): Build fingerprint: 'samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys'
D/CrashAnrDetector( 1021): Revision: '1'
D/CrashAnrDetector( 1021): ABI: 'arm'
D/CrashAnrDetector( 1021): pid: 3041, tid: 3372, name: Thread-383  >>> com.example.hello <<<
D/CrashAnrDetector( 1021): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
D/CrashAnrDetector( 1021):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
D/CrashAnrDetector( 1021):     r4 9e1a7e78  r5 9e1a7e38  r6 b7dca130  r7 9e1a7e38
D/CrashAnrDetector( 1021):     r8 00000000  r9 9e1a7e74  sl 9e1a93d0  fp 9e1a7e1c
D/CrashAnrDetector( 1021):     ip 9ec7dba0  sp 9e1a7e00  lr 9e984308  pc b6ee9468  cpsr 600d0030
D/CrashAnrDetector( 1021):     d0  00000035020000d5  d1  513802003a373ef1
D/CrashAnrDetector( 1021):     d2  0000b80c0300009d  d3  88000000560a1060
D/CrashAnrDetector( 1021):     d4  07490c0000003d01  d5  0000008849000000
D/CrashAnrDetector( 1021):     d6  0a0e000000b80c0c  d7  01003a0f0000003d
D/CrashAnrDetector( 1021):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector( 1021):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector( 1021):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector( 1021):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector( 1021):     d16 0000000000000000  d17 ffffffffffffffff
D/CrashAnrDetector( 1021):     d18 0001000100010001  d19 0001000100010001
D/CrashAnrDetector( 1021):     d20 0000000000000001  d21 0000000000000000
D/CrashAnrDetector( 1021):     d22 0000000000000000  d23 0000000000000000
D/CrashAnrDetector( 1021):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector( 1021):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector( 1021):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector( 1021):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector( 1021):     scr 20000012
D/CrashAnrDetector( 1021): 
D/CrashAnrDetector( 1021): backtrace:
D/CrashAnrDetector( 1021):     #00 pc 00010468  /system/lib/libc.so (strlen+83)
D/CrashAnrDetector( 1021):     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
D/CrashAnrDetector( 1021): 
D/CrashAnrDetector( 1021): stack:
D/CrashAnrDetector( 1021):          9e1a7d80  00000000  
D/CrashAnrDetector( 1021):          9e1a7d84  00000000  
D/CrashAnrDetector( 1021):          9e1a7d88  9de2b820  [anon:js-gc-heap]
D/CrashAnrDetector( 1021):          9e1a7d8c  f5cf96b7  
D/CrashAnrDetector( 1021):          9e1a7d90  9e1a7dbc  [stack:3372]
D/CrashAnrDetector( 1021):        ,  9e1a7d94  9e1a7e64  [stack:3372]
D/CrashAnrDetector( 1021):          9e1a7d98  b7dca130  [heap]
D/CrashAnrDetector( 1021):          9e1a7d9c  00000003  
D/CrashAnrDetector( 1021):          9e1a7da0  9e1a7ddc  [stack:3372]
D/CrashAnrDetector( 1021):          9e1a7da4  b7ebd960  [heap]
D/CrashAnrDetector( 1021):          9e1a7da8  9de53b00  [anon:js-gc-heap]
D/CrashAnrDetector( 1021):          9e1a7dac  9df11b30  [anon:js-gc-heap]
D/CrashAnrDetector( 1021):          9e1a7db0  00000000  
D/CrashAnrDetector( 1021):          9e1a7db4  ffffff82  
D/CrashAnrDetector( 1021):          9e1a7db8  00000000  
D/CrashAnrDetector( 1021):          9e1a7dbc  ffffff82  
D/CrashAnrDetector( 1021):          9e1a7dc0  9de2b040  [anon:js-gc-heap]
D/CrashAnrDetector( 1021):          9e1a7dc4  b7eba960  [heap]
D/CrashAnrDetector( 1021):          9e1a7dc8  b7f16b48  [heap]
D/CrashAnrDetector( 1021):          9e1a7dcc  00000001  
D/CrashAnrDetector( 1021):          9e1a7dd0  9de49160  [anon:js-gc-heap]
D/CrashAnrDetector( 1021):          9e1a7dd4  b7dca130  [heap]
D/CrashAnrDetector( 1021):          9e1a7dd8  9de4f1c0  [anon:js-gc-heap]
D/CrashAnrDetector( 1021):          9e1a7ddc  00000000  
D/CrashAnrDetector( 1021):          9e1a7de0  00000000  
D/CrashAnrDetector( 1021):          9e1a7de4  00000000  
D/CrashAnrDetector( 1021):          9e1a7de8  00000003  
D/CrashAnrDetector( 1021):          9e1a7dec  000000aa  
D/CrashAnrDetector( 1021):          9e1a7df0  0000006b  
D/CrashAnrDetector( 1021):          9e1a7df4  0001416e  
D/CrashAnrDetector( 1021):          9e1a7df8  00000000  
D/CrashAnrDetector( 1021):          9e1a7dfc  9e1a7e30  [stack:3372]
D/CrashAnrDetector( 1021):     #00  9e1a7e00  9e1a7e78  [stack:3372]
D/CrashAnrDetector( 1021):          ........  ........
D/CrashAnrDetector( 1021):     #01  9e1a7e00  9e1a7e78  [stack:3372]
D/CrashAnrDetector( 1021):          9e1a7e04  00000000  
D/CrashAnrDetector( 1021):          9e1a7e08  9e1a7e78  [stack:3372]
D/CrashAnrDetector( 1021):          9e1a7e0c  9e1a7e5c  [stack:3372]
D/CrashAnrDetector( 1021):          9e1a7e10  9e1a7e48  [stack:3372]
D/CrashAnrDetector( 1021):          9e1a7e14  00000000  
D/CrashAnrDetector( 1021):          9e1a7e18  9e1a8e94  [stack:3372]
D/CrashAnrDetector( 1021):          9e1a7e1c  9e95b3f0  /data/app/com.example.hello-1/lib/arm/libjxcore.so
D/CrashAnrDetector( 1021):          9e1a7e20  9e1a7e50  [stack:3372]
D/CrashAnrDetector( 1021):          9e1a7e24  00000000  
D/CrashAnrDetector( 1021):          9e1a7e28  9e1a7e44  [stack:3372]
D/CrashAnrDetector( 1021):          9e1a7e2c  9e78d184  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
D/CrashAnrDetector( 1021):          9e1a7e30  00000000  
D/CrashAnrDetector( 1021):          9e1a7e34  00000000  
D/CrashAnrDetector( 1021):          9e1a7e38  b6f2fde4  
D/CrashAnrDetector( 1021):          9e1a7e3c  00000000  
D/CrashAnrDetector( 1021):          9e1a7e40  9e1a81cc  [stack:3372]
D/CrashAnrDetector( 1021):          9e1a7e44  9e869b34  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js::Invoke(JSContext*, JS::CallArgs, js::MaybeConstruct)+340)
D/CrashAnrDetector( 1021):          9e1a7e48  b7dca130  [heap]
D/CrashAnrDetector( 1021):          9e1a7e4c  b7dca130  [heap]
D/CrashAnrDetector( 1021):          9e1a7e50  b7f16b48  [heap]
D/CrashAnrDetector( 1021):          9e1a7e54  00000001  
D/CrashAnrDetector( 1021):          9e1a7e58  9
D/CrashAnrDetector( 1021): processName:com.example.hello
D/CrashAnrDetector( 1021): broadcastEvent : com.example.hello SYSTEM_TOMBSTONE
I/sCloudBackupApp( 3633): sCloudBackupApp Version Info : 4.04.7.KK_APP
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
E/SMD     (  290): DCD OFF
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/Gmail   ( 3568): Observing account changes for notifications
I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/Zygote  ( 3687): MountEmulatedStorage()
E/Zygote  ( 3687): v2
I/libpersona( 3687): KNOX_SDCARD checking this for 10058
I/libpersona( 3687): KNOX_SDCARD not a persona
I/SELinux ( 3687): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3687): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3687): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
I/ActivityManager( 1021): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3687 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/qtaguid ( 3306): Untagging socket 43
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
I/qtaguid ( 3306): Untagging socket 43
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
I/qtaguid ( 3306): Untagging socket 43
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
I/qtaguid ( 3306): Untagging socket 43
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
I/qtaguid ( 3306): Untagging socket 43
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled return false
I/Gmail   ( 3568): getAccountsCursor
,I/qtaguid ( 3306): Untagging socket 43
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
I/qtaguid ( 3306): Untagging socket 43
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
,I/qtaguid ( 3306): Untagging socket 43
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
I/qtaguid ( 3306): Untagging socket 43
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
I/qtaguid ( 3306): Untagging socket 43
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
I/qtaguid ( 3306): Untagging socket 43
,I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
I/qtaguid ( 3306): Untagging socket 43
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
,I/qtaguid ( 3306): Untagging socket 43
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
I/art     (  309): Explicit concurrent mark sweep GC freed 8688(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 27.206ms
,W/libprocessgroup( 1021): failed to open /acct/uid_10097/pid_2874/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_2847/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  259): id=12 createSurf (73x73),1 flag=4, iello
,D/TimaKeyStoreProvider( 3687): TimaSignature is unavailable
D/ActivityThread( 3687): Added TimaKeyStore provider
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1021): [SO] activate (ident=0xb7ee2728, enabled=0)
I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/art     (  309): Explicit concurrent mark sweep GC freed 3(96B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 21.889ms
,D/SensorManager( 1021): unregisterListener ::   ,
I/Sensors ( 1021): AccelerometerSensor(0) setDelay : 200000000(ns)
D/SRIB_DCS( 1021): log_dcs ThreadedRenderer::initialize entered! 
I/Adreno-EGL( 1021): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1021): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1021): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1021): Local Branch: 
I/Adreno-EGL( 1021): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1021): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1021):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/OpenGLRenderer( 1021): Initialized EGL, version 1.4
,D/SensorService( 1021): [SO] changed settle time [0]
D/SensorService( 1021): [SO] setDelay [200000000]
D/SensorService( 1021): [SO] activate (ident=0xb7ee2728, enabled=1)
,D/SensorService( 1021): [SO] AR_init
I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/art     (  309): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 26.822ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
D/SensorManager( 1021): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/OpenGLRenderer( 1021): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 1021): Enabling debug mode 0
,W/GAV2    ( 3568): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/qtaguid ( 3306): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3306, getuid(): 10052
I/Hs20UtilService( 1737): Starting #4
,I/Hs20UtilService( 1737): Message received 5003
V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ContactAccountLoggerTas( 3306): canRun() : Opted Out,
,E/Zygote  ( 3715): MountEmulatedStorage()
,I/libpersona( 3715): KNOX_SDCARD checking this for 10018
E/Zygote  ( 3715): v2
I/libpersona( 3715): KNOX_SDCARD not a persona
I/SELinux ( 3715): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3715 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3715): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3715): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/android.os.Debug( 1021): !@Dumpstate > dumpstate -k -t -z -d -o /data/log/dumpstate_app_error
,I/dumpstate( 3724): begin
,I/dumpstate( 3724): dumpstate is still running
,D/WearableService( 1811): callingUid 10011, callindPid: 1811
,D/TimaKeyStoreProvider( 3715): TimaSignature is unavailable
,D/ActivityThread( 3715): Added TimaKeyStore provider
,E/GmsWearableNodeHelper( 1811): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/KLMS-2.5.123: ( 3715): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 14:50:57 GMT+01:00 2016
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3715): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3715): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3715): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3715): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3715): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/SensorService( 1021): [SO] Reset Rotation Old [100], Init [1]
D/btif_config_util( 2619): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/Zygote  ( 3736): MountEmulatedStorage()
E/Zygote  ( 3736): v2
I/libpersona( 3736): KNOX_SDCARD checking this for 10020
I/libpersona( 3736): KNOX_SDCARD not a persona
,I/KLMS-2.5.123: ( 3715): KLMSIntentService(): BOOT_COMPLETED
I/ActivityManager( 1021): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3736 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,I/SELinux ( 3736): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/SELinux ( 3736): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/SELinux ( 3736): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ExternalOEMControlProvider( 3687): onCreate
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/TimaKeyStoreProvider( 3736): TimaSignature is unavailable
,D/SettingsProvider( 1021): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10058
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
D/ActivityThread( 3736): Added TimaKeyStore provider
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Gmail   ( 3568): Error finding the version of the Email provider.....
E/Gmail   ( 3568): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3568): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3568): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3568): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3568): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3568): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3568): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3568): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 3568): We do not support migrating this version of the Email provider.
,E/Zygote  ( 3755): MountEmulatedStorage()
,E/Zygote  ( 3755): v2
I/libpersona( 3755): KNOX_SDCARD checking this for 1000
I/libpersona( 3755): KNOX_SDCARD not a persona
,I/SELinux ( 3755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1021): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3755 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 2905:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
I/SELinux ( 3755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3755): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,D/SettingsProvider( 1021): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10058
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,I/Gmail   ( 3568): getAccountsCursor
,D/TimaKeyStoreProvider( 3755): TimaSignature is unavailable
,D/ActivityThread( 3755): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3715): KLMSIntentService(): onDestroy()
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/RlzPingService( 3356): Setting next ping for 1452865858033
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3755): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,E/Zygote  ( 3777): MountEmulatedStorage(),
E/Zygote  ( 3777): v2
I/libpersona( 3777): KNOX_SDCARD checking this for 10102,
I/libpersona( 3777): KNOX_SDCARD not a persona
,I/SELinux ( 3777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 3777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3777): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1021): failed to open /acct/uid_1101/pid_2905/cgroup.procs: No such file or directory
,I/ActivityManager( 1021): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3777 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/SensorService( 1021): [SO] currT = 37711089000, prevT = 37261072000, diff = 450017000, [-0.402 0.057 9.902]
,D/SensorService( 1021): [SO] -0.402 0.057 9.902
D/SensorService( 1021): [SO] [100 -> 255]
,W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1021): Activity pause timeout for ActivityRecord{2d706d26 u0 com.example.hello/.MainActivity t2 f}
,D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1021): mDVFSHelper.acquire()
,I/ServiceMode( 3755): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3755): setReferenceIsDumpState : 0
,D/TimaKeyStoreProvider( 3777): TimaSignature is unavailable
D/ActivityThread( 3777): Added TimaKeyStore provider
,I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1021): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,D/Launcher( 1500): onRestart, Launcher: 132632101
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/Launcher( 1500): onStart, Launcher: 132632101
,E/ActivityThread( 3568): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@855ff67 that was originally bound here
E/ActivityThread( 3568): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@855ff67 that was originally bound here
E/ActivityThread( 3568): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3568): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3568): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3568): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3568): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3568): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3568): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3568): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3568): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3568): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3568): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3568): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3568): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3568): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3568): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3568): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Launcher.HomeView( 1500): onStart
,D/Launcher( 1500): onResume, Launcher: 132632101
,V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleHttpClient( 1633): GMS http client unavailable, use old client
,D/SettingsProvider( 1021): name = kids_home_mode
,V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10006
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,D/Launcher.HomeView( 1500): onResume
,E/SQLiteLog( 3568): (283) recovered 111 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/Launcher( 1500): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 3777): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/Zygote  ( 3796): MountEmulatedStorage()
E/Zygote  ( 3796): v2
I/libpersona( 3796): KNOX_SDCARD checking this for 1000
I/libpersona( 3796): KNOX_SDCARD not a persona
,I/SELinux ( 3796): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3796): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1021): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3796 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 2959:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,E/SELinux ( 3796): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3806): MountEmulatedStorage(),
I/libpersona( 3806): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3806): v2
I/libpersona( 3806): KNOX_SDCARD not a persona
I/SELinux ( 3806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3806): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3806 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 2976:com.sec.usbsettings/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3796): TimaSignature is unavailable
,D/ActivityThread( 3796): Added TimaKeyStore provider
W/ActivityManager( 1021): Unbind failed: could not find connection for android.os.BinderProxy@22a811c5
,D/MenuAppsGridFragment( 1500): onResume
,D/ActivityManager( 1021): handle home activity for 0
I/WallpaperManagerService( 1021): switchPersonaWallpaper is called for personaId-0
,D/WallpaperManagerService( 1021):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1021): post home show event for user 0
D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/TimaKeyStoreProvider( 3806): TimaSignature is unavailable
,D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
D/ActivityThread( 3806): Added TimaKeyStore provider
,I/SurfaceFlinger(  259): id=13 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/SRIB_DCS( 1500): log_dcs ThreadedRenderer::initialize entered! 
,W/libprocessgroup( 1021): failed to open /acct/uid_10153/pid_2959/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_2976/cgroup.procs: No such file or directory
,I/Timeline( 1500): Timeline: Activity_idle id: android.os.BinderProxy@3cb388e1 time:37970
,D/PersonaManager( 1021): isKioskContainerExistOnDevice
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1021): Displayed Component not be shown by security: +262ms
,D/NPS_WSSNPS( 3806): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3806): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3806): [] Service onCreate!!
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 23567(1442KB) AllocSpace objects, 16(1418KB) LOS objects, 33% free, 24MB/36MB, paused 3.035ms total 205.700ms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/File    ( 3568): fail readDirectory() errno=2
,E/MTPRx   ( 3796): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,E/Zygote  ( 3829): MountEmulatedStorage()
E/Zygote  ( 3829): v2
I/libpersona( 3829): KNOX_SDCARD checking this for 1000
I/libpersona( 3829): KNOX_SDCARD not a persona
,I/SELinux ( 3829): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3829): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3829 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/Gmail   ( 3568): notifyAccountChanged
,E/SELinux ( 3829): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1021): uri = 14 selection = getSealedState
D/SecContentProvider2( 1021): mCursor = null
I/Gmail   ( 3568): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/SecContentProvider2( 1021): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 1021): mCursor = null
V/MTPRx   ( 3796): sealedState: false
V/MTPRx   ( 3796): sealedUsbMassStorageState: false
,D/NPS_WSSNPS( 3806): [50.150321] smlDBHelper
,I/ActivityManager( 1021): Killing 2228:flipboard.app/u0a96 (adj 15): empty #31
,D/TimaKeyStoreProvider( 3829): TimaSignature is unavailable
,D/ActivityThread( 3829): Added TimaKeyStore provider
,D/SettingsProvider( 1021): name = mtp_usb_connection_status
,D/NPS_WSSNPS( 3806): [50.150321] NpsServiceTask Start
,I/Gmail   ( 3568): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/SettingsProvider( 1021): name = media_player_mode
,D/SettingsProvider( 1021): name = mtp_usb_conditions_met
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/SettingsProvider( 1021): name = mtp_running_status
,D/SettingsProvider( 1021): name = media_mount_count
,I/NPS_WSSNPS( 3806): [50.150321] AsyncBulkFlagCheck
,I/art     ( 1633): Explicit concurrent mark sweep GC freed 3617(158KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 892us total 80.859ms
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/SettingsProvider( 1021): name = mtp_sync_alive
,I/NPS_WSSNPS( 3806): [50.150321] IsRemain_AsyncBulkCheck
,W/SQLiteConnectionPool( 1633): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,I/NPS_WSSNPS( 3806): [50.150321] IsRemain_Asyncing nothing
W/ContextImpl( 3806): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3806): [50.150321] Service onDestroy
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/NPS_WSSNPS( 3806): [50.150321] smlBRConfigurationDelete
,D/SettingsProvider( 1021): name = sdcard_launch
,I/NPS_WSSNPS( 3806): [50.150321] smlBRMessageDelete
,I/NPS_WSSNPS( 3806): [50.150321] smlBREmailDelete
,I/NPS_WSSNPS( 3806): [50.150321] smlBRNetworkDelete
,I/NPS_WSSNPS( 3806): [50.150321] smlBRCallLogDelete
,I/NPS_WSSNPS( 3806): [50.150321] smlBRMiniDiaryDelete
,D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1021): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/SettingsProvider( 1021): name = boot_time_connected
,I/NPS_WSSNPS( 3806): [50.150321] smlBRPenMemoMDelete
,I/NPS_WSSNPS( 3806): [50.150321] smlBRSMemoDelete
,I/NPS_WSSNPS( 3806): [50.150321] cpuBooster release : false
,I/Gmail   ( 3568): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/NPS_WSSNPS( 3806): [50.150321] dsServerSocket close
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
I/ActivityManager( 1021): Killing 2355:com.android.mms/u0a41 (adj 15): empty #31
,I/Gmail   ( 3568): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/SettingsProvider( 1021): name = mtp_open_session
,I/ActivityManager( 1021): Killing 2998:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,D/SettingsProvider( 1021): name = access_control_enabled
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3857): MountEmulatedStorage(),
E/Zygote  ( 3857): v2
I/libpersona( 3857): KNOX_SDCARD checking this for 10065
,I/libpersona( 3857): KNOX_SDCARD not a persona
,I/SELinux ( 3857): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1021): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3857 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 3857): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1021): Killing 2888:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,D/CountryDetector( 1021): No listener is left,
E/SELinux ( 3857): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/PCWCLIENTTRACE_PushUtil( 3497): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3497): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3497): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3497): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3497): ACTION_BOOTUP - Version: 4.82
D/TimaKeyStoreProvider( 3857): TimaSignature is unavailable
D/ActivityThread( 3857): Added TimaKeyStore provider
D/PCWCLIENTTRACE_SYSTEMReceiver( 3497): ACTION_BOOTUP - Push type: [SPP, GCM]
,W/PCWCLIENTTRACE_AccountUtil( 3497): [hasSamungAccount] - No Samsung Account
,I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{18e5b31b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:38442
,I/ActivityManager( 1021): Killing 3096:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
I/Babel   ( 3777): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3777): MmsConfig.loadMmsSettings
I/Babel   ( 3777): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml,
I/Babel   ( 3777): MmsConfig.loadFromDatabase
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3497): [GetString-S]
,W/libprocessgroup( 1021): failed to open /acct/uid_10096/pid_2228/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10041/pid_2355/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10043/pid_2998/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10081/pid_2888/cgroup.procs: No such file or directory
,I/ReactiveServiceManager( 3497): Supported : 1
,V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3568): getAccountsCursor
,D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@11
,E/Babel   ( 3777): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3777): MmsConfig.loadFromResources,
,I/Gmail   ( 3568): getAccountsCursor
D/FileShare-Server( 3857): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3096/cgroup.procs: No such file or directory
,D/FileApkUtils( 2042): Spent 152ms computing apk sha1.,
,D/FileApkUtils( 2042): Module already staged or being staged:chimera-modules/MapsModule.apk,
,I/art     ( 2042): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-cf053f76526e84be2388d3f24ecde21377d895e5@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-cf053f76526e84be2388d3f24ecde21377d895e5/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/FactoryTestApp( 2596): [DummyFtClient$onDestroy](2596) Destroy DummyFtClient service
D/FactoryTestApp( 2596): [Support$Values.getString](2596) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2596): [ModuleCommon$isConnectionModeNone](2596) mConnectionMode = gsm
I/FactoryTestApp( 2596): [ModuleCommon$isRunningFtClient](2596) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2596): [DummyFtClient$onDestroy](2596) kill process
I/Process ( 2596): Sending signal. PID: 2596 SIG: 9
,D/QSEECOMAPI: ( 1021): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1021): App is not loaded in QSEE
,W/VideoCapabilities( 3777): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 3777): Unsupported mime audio/evrc
W/AudioCapabilities( 3777): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3777): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3777): Unsupported mime audio/mpeg-L2
I/ActivityManager( 1021): Process com.sec.factory (pid 2596)(adj 0) has died(54,630)
,W/AudioCapabilities( 3777): Unsupported mime audio/x-ms-wma,
,W/AudioCapabilities( 3777): Unsupported mime audio/x-ima,
,W/AudioCapabilities( 3777): Unsupported mime audio/qcelp
D/DexOptUtils( 2042): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-cf053f76526e84be2388d3f24ecde21377d895e5/MapsModule.apk is already optimized. Bailing.,
,W/AudioCapabilities( 3777): Unsupported mime audio/evrc
D/FileApkUtils( 2042): Keeping up-to-date module: module-cf053f76526e84be2388d3f24ecde21377d895e5
,D/QSEECOMAPI: ( 1021): Loaded image: APP id = 9,
,D/ChimeraCfgMgr( 2042): Reading stored module config
,W/VideoCapabilities( 3777): Unsupported mime video/wvc1
,D/QSEECOMAPI: ( 1021): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1021): QSEECom_shutdown_app, app_id = 9
E/terrier ( 1021): handleString: Failed to handle string(-4)
E/terrier ( 1021): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 3497): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3497): [GetString-E],
W/VideoCapabilities( 3777): Unsupported mime video/x-ms-wmv
I/PCWCLIENTTRACE_PushUtil( 3497): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3497): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3497): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 3497): [ensureRegistration] - No Samsung account,
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 3777): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 3777): Unsupported mime video/wvc1
W/VideoCapabilities( 3777): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 3777): Unsupported mime video/x-ms-wmv7
,E/Zygote  ( 3878): MountEmulatedStorage()
E/Zygote  ( 3878): v2
I/libpersona( 3878): KNOX_SDCARD checking this for 10028
I/libpersona( 3878): KNOX_SDCARD not a persona
,I/SELinux ( 3878): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3878): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3878): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/VideoCapabilities( 3777): Unsupported mime video/x-ms-wmv8
I/ActivityManager( 1021): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3878 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 3078:com.sec.dsm.system/1000 (adj 15): empty #31
E/Babel   ( 3777): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3777): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
W/VideoCapabilities( 3777): Unsupported mime video/mp43
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/GmsModuleFndr( 2042): Beginning GMS chimera module scan
,D/TimaKeyStoreProvider( 3878): TimaSignature is unavailable
,D/ActivityThread( 3878): Added TimaKeyStore provider
,W/VideoCapabilities( 3777): Unsupported mime video/sorenson
,W/VideoCapabilities( 3777): Unsupported mime video/mp4v-esdp,
,W/Settings( 3777): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/VideoCapabilities( 3777): Unsupported profile 4 for video/mp4v-es,
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3078/cgroup.procs: No such file or directory,
,I/System.out( 3878): Inside onCreate() of WakeupTriggerProvide
I/System.out( 3878): Inside WakeupProvider
,D/GmsModuleFndr( 2042): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping,
D/ChimeraCfgMgr( 2042): Beginning module configuration check
,D/ChimeraCfgMgr( 2042): Module APKs unchanged, check complete,
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3331): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO,
,I/VlingoApplication( 3878): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 3331): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 3331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/DBG_POLICYDM( 3331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/DBG_POLICYDM( 3331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/DBG_POLICYDM( 3331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
I/DBG_POLICYDM( 3331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 3331): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml,
,V/Babel   ( 3777): babel boot account: SMS
V/Babel   ( 3777): babel boot account: thalitester@gmail.com
,I/Icing   ( 2042): Storage manager: low false usage 2.08MB avail 9.99GB capacity 11.63GB
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
,I/VlingoAndroidCore( 3878): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,E/Zygote  ( 3906): MountEmulatedStorage(),
E/Zygote  ( 3906): v2
,I/libpersona( 3906): KNOX_SDCARD checking this for 1000
,I/libpersona( 3906): KNOX_SDCARD not a persona
,I/SELinux ( 3906): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3906 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 2708:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,I/SELinux ( 3906): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3906): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/AlarmManager( 1021): waitForAlarm result :4,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/TimaKeyStoreProvider( 3906): TimaSignature is unavailable
,D/ActivityThread( 3906): Added TimaKeyStore provider
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/libprocessgroup( 1021): failed to open /acct/uid_10117/pid_2708/cgroup.procs: No such file or directory,
,I/ActivityManager( 1021): Killing 3146:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31,
W/InstanceID/Rpc( 2042): Found 10011
,I/ActivityManager( 1021): Killing 3118:com.google.android.configupdater/u0a82 (adj 15): empty #31,
W/ContextImpl( 1021): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3929): MountEmulatedStorage(),
E/Zygote  ( 3929): v2
I/libpersona( 3929): KNOX_SDCARD checking this for 1000
I/libpersona( 3929): KNOX_SDCARD not a persona
,I/SELinux ( 3929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3929 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 3929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3929): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 3929): TimaSignature is unavailable
,W/libprocessgroup( 1021): failed to open /acct/uid_10082/pid_3118/cgroup.procs: No such file or directory
I/art     (  309): Explicit concurrent mark sweep GC freed 8734(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 29.628ms
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3146/cgroup.procs: No such file or directory
D/ActivityThread( 3929): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 16.772ms,
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.582ms,
,W/ContextImpl( 3929): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 ,
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
D/PowerManagerService( 1021): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1179 (0x0),
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3946): MountEmulatedStorage()
,E/Zygote  ( 3946): v2,
I/libpersona( 3946): KNOX_SDCARD checking this for 1000
I/libpersona( 3946): KNOX_SDCARD not a persona
,I/SELinux ( 3946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3946): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3946 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3946): TimaSignature is unavailable
,D/ActivityThread( 3946): Added TimaKeyStore provider
,E/Zygote  ( 3965): MountEmulatedStorage()
,E/Zygote  ( 3965): v2
,I/libpersona( 3965): KNOX_SDCARD checking this for 1000
I/libpersona( 3965): KNOX_SDCARD not a persona
,I/SELinux ( 3965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3965 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 3199:com.dropbox.android/u0a88 (adj 15): empty #31
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 3965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3965): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 3946): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 3965): TimaSignature is unavailable
,D/ActivityThread( 3965): Added TimaKeyStore provider
,W/libprocessgroup( 1021): failed to open /acct/uid_10088/pid_3199/cgroup.procs: No such file or directory
,W/ContextImpl( 3946): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3980): MountEmulatedStorage(),
E/Zygote  ( 3980): v2
I/libpersona( 3980): KNOX_SDCARD checking this for 1000
I/libpersona( 3980): KNOX_SDCARD not a persona,
,I/SELinux ( 3980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3980 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/VlingoApplication( 3878): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 3878): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,E/KnoxSetupWizardClient( 3965): isShipMode : 1
,I/KnoxSetupWizardClient( 3965): onReceive : android.intent.action.BOOT_COMPLETED
,I/F_PHONE ( 3946): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 3946): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/TimaKeyStoreProvider( 3980): TimaSignature is unavailable
D/ActivityThread( 3980): Added TimaKeyStore provider
,D/F_PHONE ( 3946): [[com.sec.bcservice]] onServiceConnected()
V/AlarmManager( 1021): waitForAlarm result :8
I/F_PHONE ( 3946): default registerAction()
I/F_PHONE ( 3946): [[com.sec.bcservice]] sendPendingMessage()
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1179): handleTimeUpdate
,W/ResourcesManager( 3980): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/SecKeyguardClockView( 1179): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,D/SecKeyguardClockView( 1179): HomeTimezone(): 1
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1179): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1179): *** don't update sliding image ***
,D/DialogFlow( 3878): initQueue()
,D/ShortcutReceiver( 3965):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4007): MountEmulatedStorage()
,E/Zygote  ( 4007): v2
I/libpersona( 4007): KNOX_SDCARD checking this for 10029
I/libpersona( 4007): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4007 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 4007): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4007): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4007): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/DateView( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3929): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3929): Resource data:2131165186
,D/BluetoothBDAdrressReceiver( 3980): onReceive(), action: android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
D/SViewCoverWidget( 1179): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,W/ContextImpl( 3980): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,W/ResourcesManager( 3929): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 4007): TimaSignature is unavailable
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/ActivityThread( 4007): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3929): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,D/SecKeyguardStatusUtils( 1179): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,W/ResourcesManager( 1475): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.,
D/BluetoothBDTestService( 1475): onCreate()
,E/BluetoothBDTestService( 1475): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1475): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 1475): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/AMMetaDataParserService( 3929): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
D/KnoxShortcutUtil( 3965): getIsShortcutMigrationFor_2_3_0_Done true
D/ShortcutReceiver( 3965):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 3965):  shortcut migration not required 
W/System.err( 3965): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,E/Zygote  ( 4022): MountEmulatedStorage()
E/Zygote  ( 4022): v2
I/libpersona( 4022): KNOX_SDCARD checking this for 1000
I/libpersona( 4022): KNOX_SDCARD not a persona
,W/System.err( 3965): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 3965): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 3965): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 3965): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 3965): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 3965): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
I/SELinux ( 4022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4022): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4022 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4022): TimaSignature is unavailable
D/ActivityThread( 4022): Added TimaKeyStore provider
,E/Zygote  ( 4037): MountEmulatedStorage()
,E/Zygote  ( 4037): v2
I/libpersona( 4037): KNOX_SDCARD checking this for 1000
I/libpersona( 4037): KNOX_SDCARD not a persona
,I/SELinux ( 4037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1021): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4037 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 3214:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,E/SELinux ( 4037): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/accuweather( 1718): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK,
D/accuweather( 1718): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/accuweather( 1718): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1718): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/TimaKeyStoreProvider( 4037): TimaSignature is unavailable
D/accuweather( 1718): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1718): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
D/ActivityThread( 4037): Added TimaKeyStore provider
D/accuweather( 1718): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
D/accuweather( 1718): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,E/accuweather( 1718): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 14 51
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3214/cgroup.procs: No such file or directory
D/GCM     ( 2042): COMPAT: Multi user not supported
W/ResourcesManager( 4022): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/OpenGLRenderer( 1500): SFEffectCache::get: create texture(0xa202c724): name, size, mSize = 34, 77280, 205512
I/CheckinService( 2042): Checkin interval check for package: unspecified last checkin: 1451923470852 min interval config: 0 actual interval: 337589460,
,D/GCM     ( 1811): COMPAT: Multi user not supported,
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 2042): Disabling old GoogleServicesFramework version
,D/StatusChecker( 4037): onReceive : android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 4037): onReceive : net.mt.init : DONE
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4057): MountEmulatedStorage()
,I/libpersona( 4057): KNOX_SDCARD checking this for 10113
E/Zygote  ( 4057): v2,
,I/libpersona( 4057): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4057 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 3244:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,I/SELinux ( 4057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 4057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4057): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4057): TimaSignature is unavailable,
D/ActivityThread( 4057): Added TimaKeyStore provider
,I/GCoreUlr( 2042): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,W/art     ( 3878): Suspending all threads took: 6.214ms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
,I/PageBuddyNotiSvc( 4057): Intent received : action=android.intent.action.BOOT_COMPLETED
,I/KnoxUsageLogPro( 4022): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/KnoxUsageLogPro( 4022): savePreference: key = previous_sys_time value = 1452261060473
,I/KnoxUsageLogPro( 4022): premStatus:2
I/KnoxUsageLogPro( 4022): isEulaShown : false
I/KnoxUsageLogPro( 4022): KnoxUsageReceiver onReceive : not Processible, just return
,I/ActivityManager( 1021): Killing 3276:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,W/ContextImpl( 4057): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/PageBuddyNotiSvc( 4057): onCreate mCpBitFlag=0
,E/Zygote  ( 4080): MountEmulatedStorage()
,E/Zygote  ( 4080): v2
I/libpersona( 4080): KNOX_SDCARD checking this for 10121
,I/libpersona( 4080): KNOX_SDCARD not a persona
,I/SELinux ( 4080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 4080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4080 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 4080): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  290): DCD OFF
,D/TimaKeyStoreProvider( 4080): TimaSignature is unavailable,
D/ActivityThread( 4080): Added TimaKeyStore provider
,D/ChimeraCfgMgr( 2042): Loading module com.google.android.gms.gass from APK com.google.android.gms,
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 ,
D/BootCompletedReceiver( 2042): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.,
D/BootCompletedReceiver( 2042): Got an BootCompleted event.
,W/ResourcesManager( 4080): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
,W/ResourcesManager( 4080): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4080): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.,
I/CheckinService( 2042): Checking schedule, now: 1452261060628 next: 1452490397821
I/CheckinService( 2042): active receiver: disabled
,D/BootCompletedReceiver( 2042): Will NOT schedule AdAttestation signal task because it's disabled.
D/SystemUpdateService( 2042): onCreate
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4101): MountEmulatedStorage()
I/libpersona( 4101): KNOX_SDCARD checking this for 10030
E/Zygote  ( 4101): v2
I/libpersona( 4101): KNOX_SDCARD not a persona
I/SELinux ( 4101): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4101 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 3331:com.policydm/1000 (adj 15): empty #31
,I/SELinux ( 4101): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4101): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1021): failed to open /acct/uid_10146/pid_3244/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10088/pid_3276/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3929): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
D/TimaKeyStoreProvider( 4101): TimaSignature is unavailable
D/ActivityThread( 4101): Added TimaKeyStore provider
I/AMMetaDataParserService( 3929): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager,
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8,
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
W/ContextImpl( 3929): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity,
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,I/KnoxUsageLogPro( 4022): savePreference: key = previous_elapsed_time value = 40107,
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3331/cgroup.procs: No such file or directory
,D/SystemUpdateService( 2042): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,D/SSRM:n  ( 1021): SIOP:: AP = 410
,D/QuickConnect( 4080): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED,
D/SettingsProvider( 1021): name = scon_is_running
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false,
D/SettingsProvider( 1021): selectionArgs: 10121
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,I/SystemUpdateService( 2042): cancelUpdate (empty URL)
I/SystemUpdateService( 2042): active receiver: disabled
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131034113
,W/ResourcesManager( 3929): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,V/AuthZen ( 2042): Handling intent: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3929): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,W/art     ( 1811): Verification of void com.google.android.gms.gcm.cb.f() took 112.608ms
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/art     ( 1021): Suspending all threads took: 21.731ms
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/TimaService( 1021): TIMA: timaDumpLog
I/GFX construct_block_size_descriptor_2d second part( 3929): took 2.496406ms for 0*0 texture 0
I/TLC_TIMA_PKM_initialize( 1021): initializing...
I/TLC_TIMA_PKM_initialize( 1021): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1021): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1021): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1021): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1021): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1021): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1021): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1021): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1021): App is not loaded in QSEE
,W/BackupManagerService( 1021): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
D/QuickConnect( 4080): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 4080): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 29633(1672KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 25MB/37MB, paused 34.310ms total 199.588ms
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/QSEECOMAPI: ( 1021): Loaded image: APP id = 10
,I/TZ: qc_tlc_communication( 1021): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1021): Trustlet response is completed
I/GFX generate_partition_tables( 3929): took 6.264635ms for 0*0 texture 0
I/GFX raster( 3929): took 10.063125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b035b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7b1ffb8 counterpartCT=4 counterpartW=96 counterparth=96
,I/GAV2    ( 3306): Thread[GAThread,5,main]: No campaign data found.,
I/QuickConnect( 4080): PeriphStartReceiver.onReceive - no need to start
,W/art     ( 2042): Suspending all threads took: 61.604ms
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3929): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
W/art     ( 3878): Suspending all threads took: 22.566ms
,I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/Zygote  ( 4121): MountEmulatedStorage()
E/Zygote  ( 4121): v2
I/libpersona( 4121): KNOX_SDCARD checking this for 10127
I/libpersona( 4121): KNOX_SDCARD not a persona
I/GFX raster( 3929): took 0.844010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b035b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7b20a90 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4121): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4121 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a,
I/ActivityManager( 1021): Killing 3400:com.sec.esdk.elm/u0a90 (adj 15): empty #31
W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthZenEventHandler( 2042): Handling event: android.intent.action.BOOT_COMPLETED
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3497): unregister AuthInfo UpdateReceiver v2.0
,D/TimaKeyStoreProvider( 4121): TimaSignature is unavailable
D/ActivityThread( 4121): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3929): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/ResourcesManager( 4121): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4121): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4121): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4121): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 2042): Using Auth Proxy for data requests.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1021): failed to open /acct/uid_10090/pid_3400/cgroup.procs: No such file or directory
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3929): took 2.688854ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3929): took 7.522396ms for 0*0 texture 0
I/GFX raster( 3929): took 11.210678ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b1ffb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b20a90 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3929): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/SystemUpdateService( 2042): onDestroy,
W/ResourcesManager( 4101): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4101): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4101): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 4101): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4101): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4101): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4101): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
I/art     ( 1633): Explicit concurrent mark sweep GC freed 3423(134KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 732us total 25.159ms
W/ResourcesManager( 4101): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/BaseAppContext( 2042): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.,
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3929): took 0.642500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b20a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7aef088 counterpartCT=4 counterpartW=96 counterparth=96
,I/System.out( 3878): INFO:Resource not found:/Common.properties Using default values
I/AMMetaDataParserService( 3929): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3929): took 0.817500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b15560 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7aef088 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3929): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/AuthZen ( 2042): Fetching signing key...
,D/GCM     ( 1811): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED,
,I/AuthZen ( 2042): Signing key fetched successfully!
,W/BaseAppContext( 2042): Using Auth Proxy for data requests.
,I/GCoreUlr( 1811): DispatchingService.onCreate()
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,D/SBrowserFeatureFlag( 4121): initialized in static block : loadCscFeatureValue() succeed! 
,D/ManifestProvider( 4121): onCreate()
,D/a       ( 2042): Opening database auth.proximity.permit_store...
,E/NetworkSettingsReceiver( 4121): onReceive: android.intent.action.BOOT_COMPLETED,
,D/AuthZenTransactionCache( 2042): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2042): Clearing transaction cache
,I/GCM     ( 1811): GCM config loaded
,W/ResourcesManager( 4007): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/System.err( 4121): java.lang.NoSuchMethodException: isEnabled [],
,W/System.err( 4121): ,	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 4121): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4121): 	,at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 4121): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4121): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4121): ,	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4121): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4121): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4121): 	,at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4121): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559),
W/System.err( 4121): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4121): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4121): ,	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4121): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4121): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4121): ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4121): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 4121): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@7e7ce25
,D/SBrowserFeatureFlag( 4121): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4121): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4007): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
W/ResourcesManager( 4007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4007): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 4163): MountEmulatedStorage(),
E/Zygote  ( 4163): v2
I/libpersona( 4163): KNOX_SDCARD checking this for 10131
I/libpersona( 4163): KNOX_SDCARD not a persona
,I/SELinux ( 4163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4163): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4163 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
I/ActivityManager( 1021): Killing 3439:com.sec.factory.camera/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4163): TimaSignature is unavailable
,D/ActivityThread( 4163): Added TimaKeyStore provider
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.693489ms for 96*96 texture 0
I/art     (  309): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 33.539ms
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7aef088 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b07f58 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 3878): Suspending all threads took: 12.434ms,
V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 25.071ms,
,W/ResourcesManager( 4163): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4163): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4163): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.725884ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b14ce0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b14fa8 counterpartCT=4 counterpartW=96 counterparth=96
,I/Icing   ( 2042): updateResources: need to parse f{com.google.android.gms}
,I/GCoreUlr( 1811): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 28.475ms
,I/AMMetaDataParserService( 3929): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/ActivityManager( 1021): Killing 3459:com.fmm.dm/1000 (adj 15): empty #31
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3439/cgroup.procs: No such file or directory
,D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3459/cgroup.procs: No such file or directory
,W/art     ( 3878): Suspending all threads took: 18.762ms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1021): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4192 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/Zygote  ( 4192): MountEmulatedStorage(),
E/Zygote  ( 4192): v2
I/libpersona( 4192): KNOX_SDCARD checking this for 10037
I/libpersona( 4192): KNOX_SDCARD not a persona
,I/SELinux ( 4192): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/GCoreFlp( 1811): No location to return for getLastLocation()
,W/FusedLocationProvider( 1811): location=null
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 4192): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4192): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 4202): MountEmulatedStorage()
E/Zygote  ( 4202): v2
,I/libpersona( 4202): KNOX_SDCARD checking this for 10135
I/libpersona( 4202): KNOX_SDCARD not a persona
,I/SELinux ( 4202): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4202 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,W/GCoreFlp( 1811): No location to return for getLastLocation()
,W/FusedLocationProvider( 1811): location=null
,I/SELinux ( 4202): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4202): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4192): TimaSignature is unavailable
D/ActivityThread( 4192): Added TimaKeyStore provider
D/TimaKeyStoreProvider( 4202): TimaSignature is unavailable
,D/ActivityThread( 4202): Added TimaKeyStore provider
,W/ResourcesManager( 4192): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/AlarmManager( 1021): waitForAlarm result :8
,W/ResourcesManager( 4202): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4202): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4202): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4202): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 4202): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1021): Killing 3481:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1021): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4226 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,E/Zygote  ( 4226): MountEmulatedStorage()
,E/Zygote  ( 4226): v2
,I/libpersona( 4226): KNOX_SDCARD checking this for 10141
I/libpersona( 4226): KNOX_SDCARD not a persona
,I/SELinux ( 4226): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4226): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4226): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CalendarProvider2( 4192): CalendarProvider2.onCreate() called,
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.521823ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b04b90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b04ce8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4226): TimaSignature is unavailable
D/ActivityThread( 4226): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3929): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131034113
,I/AMMetaDataParserService( 3929): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3929): took 0.901302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b035b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7b39920 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3929): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/ResourcesManager( 4226): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4226): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4226): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4226): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1021): failed to open /acct/uid_10095/pid_3481/cgroup.procs: No such file or directory
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 3568): Thread[GAThread,5,main]: No campaign data found.
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,E/Zygote  ( 4262): MountEmulatedStorage(),
E/Zygote  ( 4262): v2
I/libpersona( 4262): KNOX_SDCARD checking this for 10068
I/libpersona( 4262): KNOX_SDCARD not a persona
,I/SELinux ( 4262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4262 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
I/SELinux ( 4262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4262): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.847240ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b035b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7afe468 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3929): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/TimaKeyStoreProvider( 4262): TimaSignature is unavailable
,D/ActivityThread( 4262): Added TimaKeyStore provider
,I/GCoreUlr( 1811): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/Auth    ( 1811): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 4262): onCreate
D/BadgeProvider( 4262): DatabaseHelper
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.606458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b1ffb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b39920 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4293): MountEmulatedStorage()
I/libpersona( 4293): KNOX_SDCARD checking this for 10142
E/Zygote  ( 4293): v2
I/libpersona( 4293): KNOX_SDCARD not a persona
I/SELinux ( 4293): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4293 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 4293): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SELinux ( 4293): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Waited long enough for: ServiceRecord{473dffc u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/AMMetaDataParserService( 3929): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/ActivityManager( 1021): Killing 3516:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,D/BadgeProvider( 4262): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 4293): TimaSignature is unavailable
,D/ActivityThread( 4293): Added TimaKeyStore provider
,D/BadgeProvider( 4262): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1500): reloadBadges entered.
,D/BadgeProvider( 4262): sendNotify, [notify] : null
D/BadgeProvider( 4262): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4262): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4262): update, [UpdateCount] : 1
,I/ActivityManager( 1021): Killing 3553:com.fmm.ds/1000 (adj 15): empty #31
,W/ResourcesManager( 4293): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.642031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b20a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b07f58 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3929): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/ActivityManager( 1021): Killing 3596:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.890938ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b15560 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b04ce8 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1021): failed to kill pid 3553: No such process
,I/AMMetaDataParserService( 3929): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/art     ( 1811): Explicit concurrent mark sweep GC freed 26209(1964KB) AllocSpace objects, 38(608KB) LOS objects, 39% free, 9MB/15MB, paused 1.278ms total 160.177ms
,D/PersistentNotificationBroadcastReceiver( 1811): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/libprocessgroup( 1021): failed to open /acct/uid_10098/pid_3516/cgroup.procs: No such file or directory
,W/ActivityManager( 1021): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/GCoreUlr( 1811): Unbound from all location providers
I/GCoreUlr( 1811): Place inference reporting - stopped
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,I/Process ( 4101): Sending signal. PID: 4101 SIG: 9
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3553/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10055/pid_3596/cgroup.procs: No such file or directory
,I/Process ( 4226): Sending signal. PID: 4226 SIG: 9
I/GCoreUlr( 1811): DispatchingService.onDestroy()
I/GCoreUlr( 1811): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1811): Unbound from all location providers
,I/GCoreUlr( 1811): Place inference reporting - stopped
,I/ActivityManager( 1021): Process com.sec.android.app.sns3 (pid 4101)(adj 0) has died(35,633)
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1021): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4319 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,E/Zygote  ( 4319): MountEmulatedStorage()
E/Zygote  ( 4319): v2
I/libpersona( 4319): KNOX_SDCARD checking this for 10031
I/libpersona( 4319): KNOX_SDCARD not a persona
,I/SELinux ( 4319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4319): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.784114ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7aef088 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b07f58 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4335): MountEmulatedStorage()
I/libpersona( 4335): KNOX_SDCARD checking this for 10026
E/Zygote  ( 4335): v2
I/libpersona( 4335): KNOX_SDCARD not a persona
I/SELinux ( 4335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/TimaKeyStoreProvider( 4319): TimaSignature is unavailable
,D/ActivityThread( 4319): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
I/ActivityManager( 1021): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4335 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1021): Process com.android.email (pid 4226)(adj 9) has died(43,633)
E/SELinux ( 4335): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,I/GFX raster( 3929): took 0.953958ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b14ce0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b0fd40 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4335): TimaSignature is unavailable
D/ActivityThread( 4335): Added TimaKeyStore provider
,E/Zygote  ( 4352): MountEmulatedStorage()
,E/Zygote  ( 4352): v2
I/libpersona( 4352): KNOX_SDCARD checking this for 1000
I/libpersona( 4352): KNOX_SDCARD not a persona
,I/SELinux ( 4352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/AMMetaDataParserService( 3929): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
I/ActivityManager( 1021): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4352 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4352): TimaSignature is unavailable
,D/ActivityThread( 4352): Added TimaKeyStore provider
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4369): MountEmulatedStorage()
E/Zygote  ( 4369): v2
I/libpersona( 4369): KNOX_SDCARD checking this for 10141
I/libpersona( 4369): KNOX_SDCARD not a persona
,I/SELinux ( 4369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4369 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,I/SELinux ( 4369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4369): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4369): TimaSignature is unavailable
,D/ActivityThread( 4369): Added TimaKeyStore provider
,I/ActivityManager( 1021): Killing 3383:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,W/ResourcesManager( 4369): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4369): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4369): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4369): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1021): failed to open /acct/uid_10008/pid_3383/cgroup.procs: No such file or directory
,I/ActivityManager( 1021): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4388 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 4388): MountEmulatedStorage()
I/libpersona( 4388): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4388): v2
I/libpersona( 4388): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Killing 3633:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,I/SELinux ( 4388): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4388): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4388): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3929): took 0.529844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b04b90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b04ce8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4388): TimaSignature is unavailable
D/ActivityThread( 4388): Added TimaKeyStore provider
,W/art     ( 2042): Suspending all threads took: 9.414ms
,I/AMMetaDataParserService( 3929): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3929): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3929): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131034112
I/AMMetaDataParserService( 3929): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.610520ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b20a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b14d18 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3929): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,V/AlarmManager( 1021): waitForAlarm result :4
,W/libprocessgroup( 1021): failed to open /acct/uid_10056/pid_3633/cgroup.procs: No such file or directory
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.610051ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b20a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b14d18 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4406): MountEmulatedStorage(),
I/libpersona( 4406): KNOX_SDCARD checking this for 10117
E/Zygote  ( 4406): v2
,I/libpersona( 4406): KNOX_SDCARD not a persona,
I/SELinux ( 4406): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4406): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4406): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3929): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,I/ActivityManager( 1021): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService: pid=4406 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 30.439ms,
,D/TimaKeyStoreProvider( 4406): TimaSignature is unavailable,
D/ActivityThread( 4406): Added TimaKeyStore provider
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 28421(1567KB) AllocSpace objects, 8(624KB) LOS objects, 33% free, 24MB/37MB, paused 2.655ms total 167.535ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.862ms
,E/SMD     (  290): DCD OFF
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 18.239ms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4406): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3929): took 0.674271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b14d18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb78ab278 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1021): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4427 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 4427): MountEmulatedStorage(),
E/Zygote  ( 4427): v2
I/libpersona( 4427): KNOX_SDCARD checking this for 1000
I/libpersona( 4427): KNOX_SDCARD not a persona
I/SELinux ( 4427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/AMMetaDataParserService( 3929): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
E/SELinux ( 4427): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3929): took 0.730833ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7aef088 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7aeeea8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,D/TimaKeyStoreProvider( 4427): TimaSignature is unavailable
D/ActivityThread( 4427): Added TimaKeyStore provider
,D/SecurityLogAgent( 4388): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4388): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4388): StateMachine : Current State = 1
D/SecurityLogAgent( 4388): BootReceiver : completed task. Failed to return wakelock . 
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/CalendarProvider2( 4192): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/Zygote  ( 4447): MountEmulatedStorage()
E/Zygote  ( 4447): v2
I/libpersona( 4447): KNOX_SDCARD checking this for 10148
I/libpersona( 4447): KNOX_SDCARD not a persona
,I/SELinux ( 4447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4447 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/ActivityManager( 1021): Killing 2479:com.android.defcontainer/u0a3 (adj 15): empty #31
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
,I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131034113
I/AMMetaDataParserService( 3929): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/SELinux ( 4447): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GFX raster( 3929): took 0.889948ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7aeeea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7b18960 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3929): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1021): Killing 3654:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4447): TimaSignature is unavailable
D/ActivityThread( 4447): Added TimaKeyStore provider
,D/BadgeProvider( 4262): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.810104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7aeeea8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7b14ce0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3929): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,W/ActivityManager( 1021): getTasks: caller 10142 does not hold GET_TASKS; limiting output,
,D/Launcher.Model( 1500): reloadBadges entered.
,D/BadgeProvider( 4262): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4262): sendNotify, [notify] : null
D/BadgeProvider( 4262): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4262): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4262): update, [UpdateCount] : 1
,I/Process ( 4293): Sending signal. PID: 4293 SIG: 9
,I/DBG_POLICYDM( 4427): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,W/libprocessgroup( 1021): failed to open /acct/uid_10013/pid_3654/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10003/pid_2479/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4427): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,W/ProcessCpuTracker( 1021): Skipping unknown process pid 4465
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] ,
I/ActivityManager( 1021): Process com.android.exchange (pid 4293)(adj 13) has died(21,625)
I/DBG_POLICYDM( 4427): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4427): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.625625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b20a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b035b8 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 4447): (284) automatic index on shooting_modes(title_id)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
I/AMMetaDataParserService( 3929): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,D/Finsky  ( 4335): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0],
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.607708ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7880bb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b18960 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
E/Zygote  ( 4492): MountEmulatedStorage()
E/Zygote  ( 4492): v2
I/libpersona( 4492): KNOX_SDCARD checking this for 1000,
,I/SELinux ( 4492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4492): KNOX_SDCARD not a persona
I/SELinux ( 4492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/DBG_POLICYDM( 4427): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,E/SELinux ( 4492): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3929): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ActivityManager( 1021): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4492 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true],
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false],
I/DBG_POLICYDM( 4427): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.822396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b14ce0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b035b8 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4492): TimaSignature is unavailable
D/ActivityThread( 4492): Added TimaKeyStore provider
I/AMMetaDataParserService( 3929): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/DBG_POLICYDM( 4427): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 4427): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 4427): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.869114ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7aef088 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b18960 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,I/ActivityManager( 1021): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4513 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 4513): MountEmulatedStorage()
I/libpersona( 4513): KNOX_SDCARD checking this for 10032
E/Zygote  ( 4513): v2
I/libpersona( 4513): KNOX_SDCARD not a persona
,I/SELinux ( 4513): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4513): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4513): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/ActivityManager( 1021): Killing 3687:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,I/GFX raster( 3929): took 0.859011ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b035b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b18960 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1021): Killing 3356:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/AMMetaDataParserService( 3929): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/DBG_POLICYDM( 4427): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 4427): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4427): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 4427): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,D/TimaKeyStoreProvider( 4513): TimaSignature is unavailable
D/ActivityThread( 4513): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4427): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
I/Icing   ( 2042): Internal init done: storage state 0
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3929): took 0.537761ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b18960 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7b2cd00 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3929): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
W/ActivityManager( 1021): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
W/ContextImpl( 3929): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,W/libprocessgroup( 1021): failed to open /acct/uid_10058/pid_3687/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10014/pid_3356/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929,): Resource data:2131165203
,W/ResourcesManager( 3929): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3929): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3929): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX construct_block_size_descriptor_2d second part( 3929): took 3.551252ms for 0*0 texture 0
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4427): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 4427): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 4427): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 4427): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4427): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/01/11/09:09:33
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4427): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 4427): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4427): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/GFX generate_partition_tables( 3929): took 17.095625ms for 0*0 texture 0
I/GFX raster( 3929): took 21.248023ms for 80*80 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7b1b4c8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb7b1c188 counterpartCT=4 counterpartW=80 counterparth=80
I/DBG_POLICYDM( 4427): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4427): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] ,
I/DBG_POLICYDM( 4427): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/01/08/14:51:04
,I/DBG_POLICYDM( 4427): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4427): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 4427): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/AMMetaDataParserService( 3929): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,I/Icing   ( 2042): Post-init done
,I/DBG_POLICYDM( 4427): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX construct_block_size_descriptor_2d second part( 3929): took 2.405677ms for 0*0 texture 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX generate_partition_tables( 3929): took 5.284166ms for 0*0 texture 0
I/GFX raster( 3929): took 8.748645ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7e8c538 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7e8c5e0 counterpartCT=4 counterpartW=80 counterparth=80
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,I/AMMetaDataParserService( 3929): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,E/SPPClientService( 4513): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 4513): [PushClientApplication] Push log off : This is Ship build version
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SPPClientService( 4513): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/SPPClientService( 4513): PushLog.txt file is not deleted.
,D/SPPClientService( 4513): PushLog.txt file is not deleted.
D/SPPClientService( 4513): ============PushLog. stop!
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/DBG_POLICYDM( 4427): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,I/GFX raster( 3929): took 0.691094ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7e8c538 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7e8e7e8 counterpartCT=4 counterpartW=80 counterparth=80
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3929): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575,
,I/DBG_POLICYDM( 4427): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,E/Zygote  ( 4550): MountEmulatedStorage(),
I/libpersona( 4550): KNOX_SDCARD checking this for 10036
E/Zygote  ( 4550): v2
I/libpersona( 4550): KNOX_SDCARD not a persona
,I/SELinux ( 4550): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4550): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4550): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1021): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4550 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 3736:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,D/Finsky  ( 4335): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4427): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/TimaKeyStoreProvider( 4550): TimaSignature is unavailable
,D/ActivityThread( 4550): Added TimaKeyStore provider
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3929): took 0.774636ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb7e8c538 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7b1e428 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3929): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,W/Settings( 4335): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4335): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX raster( 3929): took 0.746302ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb80361a8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8036250 counterpartCT=4 counterpartW=80 counterparth=80
,W/libprocessgroup( 1021): failed to open /acct/uid_10020/pid_3736/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3929): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/Volley  ( 4335): [658] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4335): [651] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1021): Killing 3568:com.google.android.gm/u0a99 (adj 15): empty #31
,I/ActivityManager( 1021): Killing 3755:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #32
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,D/Ads     ( 4335): Skipping gmscore version check
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3755/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10099/pid_3568/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,D/Finsky  ( 4335): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4335): [1] Libraries$2.run: Finished loading 1 libraries.
,I/SA      ( 4550): [SSP] onCreated
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 4335): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/SA      ( 4550): [TPM] There is no property file
,I/SA      ( 4550): [SCU] isHaveSA() - false
,I/SA      ( 4550): [TPM] getModelProperty : null
,I/SA      ( 4550): [TPM] getCSCProperty : null
,I/SA      ( 4550): [DM] FLOATING AMOLED FEATURE: true
,I/SA      ( 4550): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4550): [DM] TFT FEATURE: false
,D/Finsky  ( 4335): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/SA      ( 4550): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
D/PowerManagerService( 1021): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 1021): getFinalBrightness : Summary is 15 -> 15
D/DisplayPowerController( 1021): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SA      ( 4550): [DM] init START
,D/PowerManagerService( 1021): [s] DisplayPowerCallbacks : onStateChanged()
,I/SA      ( 4550): [DM] This device is not a Vodafone
,W/ResourceType( 4550): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4550): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4550): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4550): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4550): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4550): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4550): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4550): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4550): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,D/lights  ( 1021): lcd : 236 +
W/ResourceType( 4550): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
E/        ( 3929): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,W/ResourceType( 4550): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4550): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
I/GFX raster( 3929): took 0.837135ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3929): Bitmap=0xb80361a8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7b1b4c8 counterpartCT=4 counterpartW=80 counterparth=80
W/ResourceType( 4550): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4550): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4550): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4550): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4550): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4550): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,W/ResourceType( 4550): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4550): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4550): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4550): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4550): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4550): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4550): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4550): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4550): [SCU] isHaveSA() - false
I/SA      ( 4550): support phone number id : false
I/SA      ( 4550): [DM] Supports Ref Jpn : true
,I/SA      ( 4550): [DM] init END
,D/lights  ( 1021): lcd : 236 -
D/lights  ( 1021): lcd : 136 +
,I/SA      ( 4550): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 4550): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
I/AMMetaDataParserService( 3929): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4550): [OR] onReceive END
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
W/ContextImpl( 3929): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
D/lights  ( 1021): lcd : 136 -
D/lights  ( 1021): lcd : 102 +
,D/lights  ( 1021): lcd : 102 -
D/lights  ( 1021): lcd : 69 +
,I/SA      ( 4550): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4550): [ODM] queryOpenData(key= GEO_IP )
,I/SA      ( 4550): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4550): [LBE] REF_JPN : true
I/SA      ( 4550): [BDC] create
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131099648
,D/lights  ( 1021): lcd : 69 -
,D/lights  ( 1021): lcd : 36 +
,W/ResourcesManager( 3929): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 3929): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3929): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SA      ( 4550): [DBMV2] getEmailID
,W/ResourcesManager( 3929): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/SA      ( 4550): [DBMV2] getDataV02ForItems
,I/SA      ( 4550): [SSP] query invoked
,I/AMMetaDataParserService( 3929): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,I/SA      ( 4550): [SCU] get signed id from samsung account2.0 DB.
,D/lights  ( 1021): lcd : 36 -
D/DisplayPowerController( 1021): getFinalBrightness : Summary is 15 -> 15
D/lights  ( 1021): lcd : 15 +
D/DisplayPowerController( 1021): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/AMMetaDataParserService( 3929): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/SA      ( 4550): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4550): [BDC] destroy
,I/ActivityManager( 1021): Killing 3777:com.google.android.talk/u0a102 (adj 15): empty #31
,I/AMMetaDataParserService( 3929): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/lights  ( 1021): lcd : 15 -
,D/DisplayPowerController( 1021): getFinalBrightness : Summary is 15 -> 15
,D/DisplayPowerController( 1021): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/splitIntent( 1021): Queue : background intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart  false.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3929): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3929): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3929): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
,I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131099648
I/AMMetaDataParserService( 3929): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,I/AMMetaDataParserService( 3929): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
I/splitIntent( 1021): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1021): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1021): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1811): callingUid 10011, callindPid: 1811
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2042): Restart initialization of location
,E/MDM     ( 1811): [229] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131099648
,I/AMMetaDataParserService( 3929): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,I/AMMetaDataParserService( 3929): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,I/AMMetaDataParserService( 3929): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/art     ( 1633): Explicit concurrent mark sweep GC freed 3246(130KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 738us total 42.924ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 3929): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1475): query,matched:0, calling pid = 2042
,D/TP/SmsProvider( 1475): match 0:Elapsed time : 1.310 ms
,I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 3929): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/art     ( 2042): Suspending all threads took: 41.153ms
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131099648
,I/AMMetaDataParserService( 3929): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,I/AMMetaDataParserService( 3929): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/libprocessgroup( 1021): failed to open /acct/uid_10102/pid_3777/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3929): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/AMMetaDataParserService( 3929): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/AMMetaDataParserService( 3929): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 24746(1320KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.498ms total 150.413ms
,D/TP/MmsProvider( 1475): Query uri=content://mms, match=0, calling pid = 2042
,I/AMMetaDataParserService( 3929): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/TP/SmsProvider( 1475): query,matched:0, calling pid = 2042
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131099648
,D/TP/SmsProvider( 1475): match 0:Elapsed time : 3.063 ms
,I/AMMetaDataParserService( 3929): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,I/AMMetaDataParserService( 3929): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/TP/MmsProvider( 1475): Query uri=content://mms, match=0, calling pid = 2042
,W/IcingInternalCorpora( 2042): getNumBytesRead when not calculated.
,I/AMMetaDataParserService( 3929): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/AuthorizationBluetoothService( 1811): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/AMMetaDataParserService( 3929): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/a       ( 1811): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131099648
,I/AMMetaDataParserService( 3929): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,I/AMMetaDataParserService( 3929): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 3929): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AMMetaDataParserService( 3929): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/GCoreFlp( 1811): No location to return for getLastLocation()
W/FusedLocationProvider( 1811): location=null
,I/AMMetaDataParserService( 3929): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
W/ContextImpl( 3929): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$Servi,ceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList,
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity,
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131165197
,W/ResourcesManager( 3929): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3929): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3929): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,I/AMMetaDataParserService( 3929): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3929): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/SIP     ( 1475): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls,
W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,E/File    ( 1475): fail readDirectory() errno=2
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131165197
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3929): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3929): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3929): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1021): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1021): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1021): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,E/MDM     ( 1811): [244] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
,I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131165197
,I/AMMetaDataParserService( 3929): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,D/LocationInitializer( 2042): Restart initialization of location
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625,
D/AuthorizationBluetoothService( 1811): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
I/AMMetaDataParserService( 3929): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1811): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3929): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1811): No location to return for getLastLocation()
,W/FusedLocationProvider( 1811): location=null
,I/AMMetaDataParserService( 3929): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3929): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1737): Starting #5
,I/Hs20UtilService( 1737): Message received 5007
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131099648
,W/ResourcesManager( 3929): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3929): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,I/AMMetaDataParserService( 3929): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1737): Starting #6
,I/Hs20UtilService( 1737): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1737): Starting #7
,I/Hs20UtilService( 1737): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1021): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/AMMetaDataParserService( 3929): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravityXOffset,
,D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1021): mCursor = null
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3929): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/SecContentProvider2( 1021): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1021): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 3497): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3497): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3497): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 3497): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1021): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29,
I/splitIntent( 1021): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4621): MountEmulatedStorage()
I/libpersona( 4621): KNOX_SDCARD checking this for 10108
E/Zygote  ( 4621): v2
I/libpersona( 4621): KNOX_SDCARD not a persona
,I/SELinux ( 4621): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4621 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4621): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4621): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/accuweather( 1718): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=4, Uoast
,I/KLMS-2.5.123: ( 3715): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 14:51:05 GMT+01:00 2016
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,I/KLMS-2.5.123: ( 3715): KLMSAbstractReciever(): onReceive().END.,
D/PowerManagerService( 1021): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1021
D/DisplayPowerController( 1021): getFinalBrightness : Summary is 255 -> 255
D/DisplayPowerController( 1021): animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1021): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 1021): lcd : 42 +
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 4621): TimaSignature is unavailable
,D/ActivityThread( 4621): Added TimaKeyStore provider
,D/SRIB_DCS( 1179): log_dcs ThreadedRenderer::initialize entered! 
,D/lights  ( 1021): lcd : 42 -
D/lights  ( 1021): lcd : 76 +
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:assistant
I/AMMetaDataParserService( 3929): Resource data:2131165220
,D/StatusBar.NetworkController( 1179): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1179): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1179): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ResourcesManager( 3929): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/KLMS-2.5.123: ( 3715): KLMSIntentService(): onCreate()
W/ResourcesManager( 3929): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3929): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3929): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3929): getResourceTypeNamexml
,D/SecurityLogAgent( 4388): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4388): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4388): StateMachine : Current State = 1
,D/accuweather( 1718): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1718): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1718): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/SecurityLogAgent( 4388): StateMachine : Changed Current State = 1
,D/accuweather( 1718): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/lights  ( 1021): lcd : 76 -
,D/lights  ( 1021): lcd : 109 +
,I/KLMS-2.5.123: ( 3715): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/DBG_POLICYDM( 4427): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3715): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/lights  ( 1021): lcd : 109 -
,D/lights  ( 1021): lcd : 142 +
,I/AMMetaDataParserService( 3929): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,E/SPPClientService( 4513): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
I/KLMS-2.5.123: ( 3715): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3715): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/lights  ( 1021): lcd : 142 -
D/lights  ( 1021): lcd : 176 +
,I/DBG_POLICYDM( 4427): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4427): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 4427): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 4550): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,D/lights  ( 1021): lcd : 176 -
,D/lights  ( 1021): lcd : 209 +
,I/KLMS-2.5.123: ( 3715): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/SA      ( 4550): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/KLMS-2.5.123: ( 3715): StateImplV2(): networkChangeListener().START
,I/SA      ( 4550): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/KLMS-2.5.123: ( 3715): NetworkChangeOperations(): uploadRequestLog().START 
,D/lights  ( 1021): lcd : 209 -
D/lights  ( 1021): lcd : 242 +
,D/lights  ( 1021): lcd : 242 -
,D/lights  ( 1021): lcd : 255 +
D/DisplayPowerController( 1021): getFinalBrightness : Summary is 255 -> 255
D/DisplayPowerController( 1021): animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,D/lights  ( 1021): lcd : 255 -
,D/DisplayPowerController( 1021): getFinalBrightness : Summary is 255 -> 255
I/DBG_POLICYDM( 4427): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,D/DisplayPowerController( 1021): animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/KLMS-2.5.123: ( 3715): NetworkChangeOperations(): uploadRequestLog().END 
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/KLMS-2.5.123: ( 3715): StateImplV2(): networkChangeListener().END
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts,
I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/KLMS-2.5.123: ( 3715): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 4427): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/DBG_POLICYDM( 4427): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/accuweather( 1718): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1718): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/AMMetaDataParserService( 3929): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4427): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,E/Zygote  ( 4642): MountEmulatedStorage(),
E/Zygote  ( 4642): v2
I/libpersona( 4642): KNOX_SDCARD checking this for 10077
I/libpersona( 4642): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4642 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4642): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1179): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1179): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/SA      ( 4550): [SLFUCHKMGR] constructor called
,D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1179): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1179): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1179): level :100 plugged : 2
,V/HeadsetService( 2619): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2619): Disconnected process message: 10
,I/SA      ( 4550): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4550): [OR] == isSIMCardReady false ==
,D/TimaKeyStoreProvider( 4642): TimaSignature is unavailable
D/ActivityThread( 4642): Added TimaKeyStore provider
,I/iu.SyncManager( 2042): SYNC; picasa accounts
,W/ContextImpl( 2938): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/DBG_DM  ( 3232): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3232): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,D/NetworkLogImpl( 2042): Loaded NetworkSpeedPredictor
,I/iu.Environment( 2042): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/Process ( 2938): Sending signal. PID: 2938 SIG: 9
I/SA      ( 4550): [SCU] == networkStateCheck == true
,I/SA      ( 4550): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4550): isChinaCountryCode : false
I/SA      ( 4550): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 4550): [OR] == networkStateCheck true ==
E/DBG_DM  ( 3232): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,I/SA      ( 4550): [OR] GetMyCountryZoneTask
,I/SA      ( 4550): [OR] onReceive END
,V/DownloadManager( 1223): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1021): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1021): mCursor = null
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/iu.UploadsManager( 2042): num queued entries: 0
,I/iu.UploadsManager( 2042): num updated entries: 0
,I/iu.SyncManager( 2042): NEXT; no task
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/MusicStore( 4621): Database version: 104
,E/Zygote  ( 4668): MountEmulatedStorage()
I/libpersona( 4668): KNOX_SDCARD checking this for 10009
E/Zygote  ( 4668): v2
I/libpersona( 4668): KNOX_SDCARD not a persona
I/SELinux ( 4668): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4668): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1021): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4668 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 4668): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Process com.sec.android.app.sysscope (pid 2938)(adj 0) has died(20,626)
,I/SA      ( 4550): [SRS] prepareGetMyCountryZone
,D/TimaKeyStoreProvider( 4668): TimaSignature is unavailable
,D/ActivityThread( 4668): Added TimaKeyStore provider
,I/SA      ( 4550): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4550): [SSP] query invoked
,E/SMD     (  290): DCD OFF
,I/SA      ( 4550): [TPMU] GetMccFromDB : null
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/SA      ( 4550): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4550): [TPM] isNoProxy(default) : true
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4686): MountEmulatedStorage()
I/libpersona( 4686): KNOX_SDCARD checking this for 10110
,E/Zygote  ( 4686): v2
I/libpersona( 4686): KNOX_SDCARD not a persona
,I/SELinux ( 4686): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4686): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4686 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 3796:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
E/SELinux ( 4686): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/File    ( 4550): fail readDirectory() errno=2
,D/TimaKeyStoreProvider( 4686): TimaSignature is unavailable
D/ActivityThread( 4686): Added TimaKeyStore provider
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3796/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 4668): notifyNetworkActivated
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SubSettings
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.LabelName
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
,I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog,
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
,I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
,I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
,I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE,
I/AMMetaDataParserService( 3929): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE,
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
W/ContextImpl( 3929): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/ActivityManager( 1021): Killing 3806:com.wssnps/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
,I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMe,taDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserSe,rvice( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3929): Resour,ce data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
W/ActivityManager( 1021): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AM,MetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMe,taDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3806/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:co,m.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3929): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3929): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3929): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
W/ContextImpl( 4668): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ResourcesManager( 4621): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4621): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4621): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 4621): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4621): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3518a02d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4621): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 4621): GMSCore installation verified
,I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,I/DBG_DM  ( 3232): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected,
I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
I/DBG_DM  ( 3232): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4686): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4686): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/DBG_DM  ( 3232): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 3232): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ConfigStore( 4621): Config Database version: 1
,I/DBG_DM  ( 3232): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3232): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/DBG_DM  ( 3232): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START,
I/DBG_DM  ( 3232): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,I/DBG_DM  ( 3232): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:362673799
,W/ContextImpl( 4686): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/DBG_DM  ( 3232): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,D/hcjo    ( 4668): AutoUpdateManager:IDLE:execute
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4686): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
D/InitializeManagerStateMachine( 4668): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4668): exit::IDLE
D/InitializeManagerStateMachine( 4668): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4668): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4668): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4668): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4668): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4668): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4668): entry::SUCCESS
D/hcjo    ( 4668): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 4668): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,D/hcjo    ( 4668): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 4668): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,W/ContextImpl( 4621): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 705624899
,I/DBG_DM  ( 3232): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,D/InitializeManagerStateMachine( 4668): exit::SUCCESS
D/InitializeManagerStateMachine( 4668): entry::IDLE
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,E/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
I/DBG_DM  ( 3232): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,E/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@3d0773b0
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(755/lllllIIlIIIlIlIIIllI)] UI_id:223
,W/ContextImpl( 3232): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 com.wssyncmldm.llIIllllIIlllIIIIlll.handleMessage:1090 
,W/ContextImpl( 3232): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4621): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4621): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/Timeline( 3232): Timeline: Activity_launch_request id:com.wssyncmldm time:46992
,E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,W/ResourcesManager( 1021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1021): mDVFSHelper.acquire()
,D/FocusedStackFrame( 1021): Set to : 0
,D/Launcher.HomeView( 1500): onPause
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1021): Focused application set to: xxxx
,D/Launcher( 1500): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1021): [SO] activate (ident=0xb7ee2728, enabled=0)
I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/SensorManager( 1021): unregisterListener ::   
,I/Sensors ( 1021): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1021): [SO] changed settle time [1]
,D/SensorService( 1021): [SO] setDelay [66000000]
D/SensorService( 1021): [SO] activate (ident=0xb7ee2728, enabled=1)
D/SensorService( 1021): [SO] AR_init
,I/Sensors ( 1021): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1021): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.XUIDialogActivity(2153/onResume)] 
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.XUIDialogActivity(2195/lllIlIlIIIllIIlIllIl)] id 223
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1021): getStreamVolume 3 index 70
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/MediaRouter( 4621): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 8
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/NetworkMonitor( 4621): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/Timeline( 3232): Timeline: Activity_launch_request id:com.wssyncmldm time:47140
D/SensorService( 1021): [SO] Reset Rotation Old [100], Init [1]
E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
,I/WebViewFactory( 4686): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,E/Zygote  ( 4731): MountEmulatedStorage()
E/Zygote  ( 4731): v2
I/libpersona( 4731): KNOX_SDCARD checking this for 10001
I/libpersona( 4731): KNOX_SDCARD not a persona
,I/SELinux ( 4731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4731 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 4731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4731): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@7
D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1021): mDVFSHelper.acquire()
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/InputDispatcher( 1021): Focused application set to: xxxx
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.IIllIIIlIllIIIllIIlI(252/llllIIIllIlIIIIllllI)] 
,D/TimaKeyStoreProvider( 4731): TimaSignature is unavailable
D/ActivityManager( 1021): post active user change for 0 fullscreen false record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
,D/ActivityThread( 4731): Added TimaKeyStore provider
,I/KnoxTimeoutHandler( 1021): Target Activity is not fullscreen. We will not show this activity0
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.XUIDialogActivity(2145/onPause)] 
,V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1021): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1021): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,I/LibraryLoader( 4686): Loading: webviewchromium
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/LibraryLoader( 4686): Time to load native libraries: 5 ms (timestamps 7192-7197)
I/LibraryLoader( 4686): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4686): Binding Chromium to main looper Looper (main, tid 1) {32e334f}
I/LibraryLoader( 4686): Expected native library version number "",actual native library version number ""
I/chromium( 4686): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/SensorService( 1021): [SO] currT = 47211384000, prevT = 46911066000, diff = 300318000, [-0.421 0.057 9.922]
D/SensorService( 1021): [SO] -0.421 0.057 9.922
,D/SensorService( 1021): [SO] [100 -> 255]
I/DBG_POLICYDM( 4427): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/NetworkMonitor( 4621): type=WIFI subType= reason=null isConnected=true
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/ActivityManager( 1021): Killing 3829:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
I/DBG_POLICYDM( 4427): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 8
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/BrowserStartupController( 4686): Initializing chromium process, renderers=0
,W/art     ( 4686): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 4686): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/chromium( 4686): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
I/DBG_DM  ( 3232): [com.wssyncmldm.ui.XUIInstallConfirmActivity(75/onCreate)] Postpone Count : 8
I/chromium( 4686): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,I/Adreno-EGL( 4686): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
I/Adreno-EGL( 4686): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4686): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4686): Local Branch: 
I/Adreno-EGL( 4686): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4686): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4686):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 4686): Requires BLUETOOTH permission
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3829/cgroup.procs: No such file or directory
,I/NSApplication( 4686): Starting up...
,I/ActivityManager( 1021): Killing 3041:com.example.hello/u0a334 (adj 15): empty #31
I/ActivityManager( 1021): Killing 3857:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #32
,D/PhoneWindow( 3232): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3232): *FMB* installDecor flags : -2139029248
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4770): MountEmulatedStorage()
I/libpersona( 4770): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4770): v2
I/libpersona( 4770): KNOX_SDCARD not a persona
,I/SELinux ( 4770): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4770 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
I/ActivityManager( 1021): Killing 3906:com.samsung.helphub/1000 (adj 15): empty #31
,I/SELinux ( 4770): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4770): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WindowState( 1021): WIN DEATH: Window{2d9ea32b u0 com.example.hello/com.example.hello.MainActivity}
,I/SurfaceFlinger(  259): id=11 Removed NainActivit (6/10),
I/SurfaceFlinger(  259): id=11 Removed NainActivit (-2/10)
,I/SurfaceFlinger(  259): id=11 Removed NainActivit (-2/10)
,I/art     (  309): Explicit concurrent mark sweep GC freed 8690(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 628us total 26.600ms
,D/TimaKeyStoreProvider( 4770): TimaSignature is unavailable
D/ActivityThread( 4770): Added TimaKeyStore provider
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 17.524ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.503ms
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,D/QuickConnect( 4080): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect( 4080): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 4080): PeriphStartReceiver.onReceive - no need to start
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,E/Watchdog( 1021): !@Sync 1
,D/SettingsProvider( 1021): name = audio_safe_volume_state
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/libprocessgroup( 1021): failed to open /acct/uid_10334/pid_3041/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10065/pid_3857/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3906/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 4770): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1021): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 8
,W/ResourcesManager( 1179): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 8
,I/ActivityManager( 1021): Waited long enough for: ServiceRecord{3a0a6b61 u0 com.android.settings/.wifi.WifiCredService}
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,D/KnoxNotification( 1179): ----- inflateViews : modified publicViewLocal -----
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 8
,D/KnoxNotification( 1179): ----- inflateViews : modified KnoxViewLocal -----
D/PersonaManager( 1179): PersonaID is invalid or persona doesn't exists. : 0
D/PersonaManager( 1179): isKioskContainerExistOnDevice
D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1179): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1179): Icon Only
I/StatusBar( 1179): Icon Only
D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
I/DBG_DM  ( 3232): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 8
,I/DIAGMON_AGENT( 4770): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0,
,I/DIAGMON_AGENT( 4770): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 4770): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 4770): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
I/DIAGMON_AGENT( 4770): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 4770): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
I/DBG_DM  ( 3232): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 8
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,I/DBG_DM  ( 3232): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,I/ActivityManager( 1021): Waited long enough for: ServiceRecord{112d7686 u0 com.samsung.android.providers.context/.ContextService}
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1179): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 8
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1179): Icon Only
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
,D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,D/PersonaManager( 1179): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1179): Icon Only
,I/StatusBar( 1179): Icon Only
,D/PanelView( 1179): There is/are notification(s) 
D/PanelView( 1179): kidsfalse mQsExpansionEnabled:true
,I/DBG_DM  ( 3232): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3232): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3232): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 3232): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/OpenGLRenderer( 3232): Render dirty regions requested: true
,I/SA      ( 4550): [RC New] Execute method=[GET] start
,D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/PhoneWindow( 3232): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3232): *FMB* isFloatingMenuEnabled return false
,I/DBG_POLICYDM( 4427): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO,
,I/DBG_POLICYDM( 4427): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4792): MountEmulatedStorage()
,I/libpersona( 4792): KNOX_SDCARD checking this for 10008
E/Zygote  ( 4792): v2
I/libpersona( 4792): KNOX_SDCARD not a persona
I/SELinux ( 4792): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/PanelView( 1179): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
I/ActivityManager( 1021): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4792 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4792): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4792): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4792): TimaSignature is unavailable
,D/ActivityThread( 4792): Added TimaKeyStore provider
,I/SA      ( 4550): [RC New] Security=[true]
,I/SurfaceFlinger(  259): id=15 createSurf (1x1),1 flag=404, YUIInstallC
,I/System.out( 4550): Thread-695(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 4550): Thread-695(ApacheHTTPLog):isSBSettingEnabled false
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/System.out( 4550): Thread-695(ApacheHTTPLog):isShipBuild true
I/System.out( 4550): Thread-695(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4550): Thread-695(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10036
,D/SRIB_DCS( 3232): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 3232): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3232): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3232): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3232): Local Branch: 
I/Adreno-EGL( 3232): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3232): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3232):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/OpenGLRenderer( 3232): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3232): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3232): Enabling debug mode 0
,I/ActivityManager( 1021): Killing 3929:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/FOTA_Client( 4792): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 4792): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 4792): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 4792): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/splitIntent( 1021): Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,D/PersonaManager( 1021): isKioskContainerExistOnDevice
,I/ActivityManager( 1021): Killing 3980:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,I/splitIntent( 1021): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 1021): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/Timeline( 3232): Timeline: Activity_idle id: android.os.BinderProxy@3a7533f8 time:48033
,E/Zygote  ( 4812): MountEmulatedStorage()
,E/Zygote  ( 4812): v2
I/libpersona( 4812): KNOX_SDCARD checking this for 10058
I/libpersona( 4812): KNOX_SDCARD not a persona
,I/SELinux ( 4812): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4812 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4812): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4812): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1770): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR,
D/daemonapp( 1770): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 4812): TimaSignature is unavailable
D/ActivityThread( 4812): Added TimaKeyStore provider
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/FOTA_Client( 4792): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...,
,D/daemonapp( 1770): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true,
I/ActivityManager( 1021): Displayed Component not be shown by security: +940ms (total +1s107ms)
D/comsamsunglog( 1770): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1770): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1770): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1770): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1770): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/daemonapp( 1770): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/daemonapp( 1770): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1770): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1770): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1770): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/FOTA_Client( 4792): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings,
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
E/daemonapp( 1770): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/KLMS-2.5.123: ( 3715): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Fri Jan 08 14:51:08 GMT+01:00 2016
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/comdaemonstockapp( 1770): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 1770): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/KLMS-2.5.123: ( 3715): KLMSAbstractReciever(): onReceive().END.
,I/SA      ( 4550): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3980/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3929/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3715): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3715): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/ExternalOEMControlProvider( 4812): onCreate
,I/KLMS-2.5.123: ( 3715): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/SecurityLogAgent( 4388): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4388): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4388): StateMachine : Current State = 1
I/KLMS-2.5.123: ( 3715): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
I/KLMS-2.5.123: ( 3715): KLMSIntentService(): TIME_CHANGED
I/KLMS-2.5.123: ( 3715): StateImplV2(): dateTimeChanged().START : Fri Jan 08 14:51:08 GMT+01:00 2016
,I/KLMS-2.5.123: ( 3715): StateImplV2(): dateTimeChanged().END
I/KLMS-2.5.123: ( 3715): KLMSIntentService(): onDestroy()
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 30896(1913KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 2.132ms total 144.857ms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/dumpstate( 3669): waiting for zip started,
I/libpersona( 4834): KNOX_SDCARD checking this for 10153
E/Zygote  ( 4834): MountEmulatedStorage()
I/libpersona( 4834): KNOX_SDCARD not a persona
,E/Zygote  ( 4834): v2
I/SELinux ( 4834): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 4834): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4834): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1021): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4834 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,I/ Time Manager ( 4812): Time Difference not stored. TIME_DIFFERENCE
,I/dumpstate( 3669): waiting for zip end
,I/dumpstate( 3669): done
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1718): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/accuweather( 1718): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/TimaKeyStoreProvider( 4834): TimaSignature is unavailable
,D/ActivityThread( 4834): Added TimaKeyStore provider
,E/Zygote  ( 4849): MountEmulatedStorage(),
E/Zygote  ( 4849): v2
I/libpersona( 4849): KNOX_SDCARD checking this for 10041
I/libpersona( 4849): KNOX_SDCARD not a persona
,I/SELinux ( 4849): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4849 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
,I/SELinux ( 4849): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4849): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/        (  281): ptrace detach from 3372 failed: No such process
,E/        (  281): debuggerd committing suicide to free the zombie!
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/        ( 4860): debuggerd: May 29 2015 20:19:21
D/TimaKeyStoreProvider( 4849): TimaSignature is unavailable
,D/ActivityThread( 4849): Added TimaKeyStore provider
,E/Zygote  ( 4864): MountEmulatedStorage()
,W/ResourcesManager( 4834): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  ( 4864): v2
I/libpersona( 4864): KNOX_SDCARD checking this for 10081
I/libpersona( 4864): KNOX_SDCARD not a persona
,I/SELinux ( 4864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4864 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4864): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1021): mDVFSHelper.release()
I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{2781ab1b u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t3} time:48474
,I/SurfaceFlinger(  259): id=13 Removed Mauncher (4/10)
,I/SurfaceFlinger(  259): id=13 Removed Mauncher (-2/10)
,D/TimaKeyStoreProvider( 4864): TimaSignature is unavailable
,D/ActivityThread( 4864): Added TimaKeyStore provider
,W/ResourcesManager( 4849): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4849): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4849): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4849): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 4849): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/CustomFrequencyManagerService( 1021): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/Launcher.HomeView( 1500): onStop
,V/ActivityThread( 1500): updateVisibility : ActivityRecord{14a0c0d6 token=android.os.BinderProxy@3cb388e1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1500): onTrimMemory. Level: 20
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4881): MountEmulatedStorage(),
E/Zygote  ( 4881): v2
I/libpersona( 4881): KNOX_SDCARD checking this for 1000
I/libpersona( 4881): KNOX_SDCARD not a persona
,I/SELinux ( 4881): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SA      ( 4550): [RC New] [v2liruge] api execute + 634
I/ActivityManager( 1021): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4881 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SA      ( 4550): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 4550): AsyncTask #1 calls detatch()
,I/SELinux ( 4881): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4881): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CheckinService( 2042): Checkin interval check for package: unspecified last checkin: 1451923470852 min interval config: 0 actual interval: 337598052
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4881): TimaSignature is unavailable
,D/ActivityThread( 4881): Added TimaKeyStore provider
W/ResourcesManager( 4864): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 4864): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4864): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4864): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4864): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/ActivityManager( 1021): Killing 3965:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,I/SA      ( 4550): [ODM] saveOpenData( GEO_IP, PL )
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_3965/cgroup.procs: No such file or directory
,D/Mms/MmsApp( 4849): [start]    onCreate() consume time = 0.0
,I/SA      ( 4550): [OCP] update openData : PL
,I/GAV2    ( 4406): Thread[GAThread,5,main]: No campaign data found.
,I/SA      ( 4550): [TPMU] getNetworkMcc : 
,I/SA      ( 4550): [SCU] saveMccToPreferece Start
,I/SA      ( 4550): [SCU] RegionMCC : 260
I/SA      ( 4550): [SSP] query invoked
,D/TimeService( 4881): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452261069059
D/        ( 4881): TimeServiceNative: User Time to be set is 1452261069059
,D/QC-time-services( 4881): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4881): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 4881): Lib:time_genoff_operation: pargs->ts_val = 1452261069059
,I/SA      ( 4550): [TPMU] GetMccFromDB : null
I/SA      ( 4550): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4550): [SCU] saveMccToPreferece End
I/SA      ( 4550): [RC New] executeRequest [v2liruge] end. 855
I/SA      ( 4550): [RC New] Execute end
,I/SA      ( 4550): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 4550): [OR] GetMyCountryZoneTask Success
,D/QC-time-services(  328): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 4881): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  328): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452261069059
D/QC-time-services(  328): Daemon:genoff_opr: Base = 2, val = 1452261069059, operation = 0
D/QC-time-services(  328): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/5/70 17:28:22,
D/QC-time-services(  328): Daemon:Value read from RTC seconds = 16046902000
D/QC-time-services(  328): Daemon:new time 1452261069059 ,
D/QC-time-services(  328): Daemon: delta 1436214167059 genoff 1436214167059 
D/QC-time-services(  328): Daemon:genoff_persistent_update: Writing genoff = 1436214167059 to memory
D/QC-time-services(  328): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  328): Daemon:time_persistent_memory_opr:Genoff write operation ,
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/QC-time-services(  328): Updating the TOD offset
D/QC-time-services(  328): Daemon:genoff_persistent_update: Writing genoff = 1436214167059 to memory
D/QC-time-services(  328): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  328): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  328): Daemon:Update to modem bit set
D/QC-time-services(  328): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  328): Daemon: Base = 2, Value being sent to MODEM = 1120249367059
,E/QC-time-services( 4881): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  328): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  328): Daemon: Time-services: Waiting to acceptconnection
,I/ActivityManager( 1021): Killing 3878:com.vlingo.midas/u0a28 (adj 15): empty #31
,W/art     ( 4849): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 120.818ms
,I/ActivityManager( 1021): Killing 4037:com.sec.android.app.mt/1000 (adj 15): empty #31
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/SettingsProvider( 1021): name = next_alarm_formatted
D/SettingsProvider( 1021): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1021): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1021): selectionArgs: false
D/SettingsProvider( 1021): selectionArgs: 10081
D/SecContentProvider( 1021): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1021): ret = -1
,D/CustomFrequencyManagerService( 1021): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1021  tag : ACTIVITY_RESUME_BOOSTER@11
,I/ActivityManager( 1021): Killing 4022:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/Mms/ArtClassLoader( 4849): init before art
,D/Mms/TelephonyPermission( 4849): start operation mode monitor
,W/ResourcesManager( 4849): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 4849): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission( 4849): isDefault true
,D/Mms/MmsApp( 4849): onCreate() com.android.mms
,W/libprocessgroup( 1021): failed to open /acct/uid_10028/pid_3878/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4037/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4022/cgroup.procs: No such file or directory
,D/Mms/MmsApp( 4849): [start]    initCountryIso consume time = 265.509739
,D/CountryDetector( 1021): The first listener is added
,D/Mms/MmsApp( 4849): [end]    initCountryIso consume time = 10.14474
,D/Mms/MmsConfig( 4849): [start]    MmsConfig.init() consume time = 0.703541
,W/art     ( 4864): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 113.670ms
,D/Mms/MmsConfig( 4849): before partial update
,D/Mms/MmsConfig( 4849): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4849): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4849): isAuth is false
,D/Mms/MmsConfig( 4849): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1475): query,matched:2117, calling pid = 4849
,D/TP/MmsSmsProvider( 1475): match 2117:Elapsed time : 1.658 ms
,D/EasySignUpManager_1.0.1( 4849): isAuth is false
,D/EasySignUpManager_1.0.1( 4849): getServiceStatus : serviceId (1) is OFF
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/CscParser( 4849): mps_code.dat does not exist
E/CscParser( 4849): customer_path =/system/csc/customer.xml
,E/CscParser( 4849): fileName + /system/csc/customer.xml
,E/CscParser( 4849): mps_code.dat does not exist
E/CscParser( 4849): customer_path =/system/csc/customer.xml
E/CscParser( 4849): fileName + /system/csc/customer.xml
,E/Zygote  ( 4905): MountEmulatedStorage()
,E/Zygote  ( 4905): v2
I/libpersona( 4905): KNOX_SDCARD checking this for 10090
I/libpersona( 4905): KNOX_SDCARD not a persona
,I/SELinux ( 4905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1021): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4905 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 4121:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
I/SELinux ( 4905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/CscParser( 4849): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 4849):  enable multiwindow = false
,E/SELinux ( 4905): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Mms/MessageUtils( 4849): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 4849): updateCountryIso : update country iso info 
,D/Mms/MmsConfig( 4849): [end]    init() consume time = 96.067188
,D/Mms/Contact( 4849): [start]    init() consume time = 2.390677
,D/TimaKeyStoreProvider( 4905): TimaSignature is unavailable
,D/ActivityThread( 4905): Added TimaKeyStore provider
,D/Mms/Contact( 4849): [end]    init consume time = 22.47
,D/TP/MmsSmsProvider( 1475): query,matched:13, calling pid = 4849
,D/TP/MmsSmsProvider( 1475): match 13:Elapsed time : 1.747 ms
,D/elm:15121( 4905): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 4905): ELMEngine.ELMEngine( context ).
,D/elm:15121( 4905): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 4905): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/elm:15121( 4905): ElmAgentService : onCreate()
D/Mms/DraftCache( 4849): [start]    rebuildCache consume time = 19.165104,
D/elm:15121( 4905): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/TP/MmsSmsProvider( 1475): query,matched:12, calling pid = 4849
,D/Mms/MethodReflector( 4849): getSubId is called
D/Mms/TelephonyUtils( 4849): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1475): match 12:Elapsed time : 4.167 ms
,D/elm:15121( 4905): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15121( 4905): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:15121( 4905): ModuleBase.ModifySetAlarm()
D/Mms/MethodReflector( 4849): getTelephonyProperty is called
D/elm:15121( 4905): MDMBridge.getInstance()
D/elm:15121( 4905): MDMBridge.getAllLicenseInfoFromSDK()
,D/Mms/DownloadManager( 4849): roaming -> false (slotId = 0)
,D/Mms/DownloadManager( 4849): [NotificationTransaction] getAutoDownloadState simSlot : 0,
D/Mms/DownloadManager( 4849): auto download without roaming -> true
,D/Mms/DownloadManager( 4849): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/MethodReflector( 4849): getSubId is called
,D/Mms/MethodReflector( 4849): getDefaultSmsSubId is called
,E/Mms/TelephonyUtils( 4849): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4849): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 4849): getTelephonyProperty is called
D/Mms/DownloadManager( 4849): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4849): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4849): auto download without roaming -> true
D/Mms/DownloadManager( 4849): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4849): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4849): mAutoDownload ------> true
,E/Zygote  ( 4927): MountEmulatedStorage()
I/libpersona( 4927): KNOX_SDCARD checking this for 10130
E/Zygote  ( 4927): v2
I/libpersona( 4927): KNOX_SDCARD not a persona
I/SELinux ( 4927): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4927 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,I/SELinux ( 4927): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4927): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/PowerManagerService( 1021): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1021) eventTime = 49094
,D/PowerManagerService( 1021): [s] UserActivityState : 2 -> 1
D/PowerManagerService( 1021): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1021 (0x0),
,D/PowerManagerService( 1021): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1021, ws=WorkSource{10049}) (elapsedTime=3474)
,D/elm:15121( 4905): ElmAgentService : onDestroy().
,D/TimaKeyStoreProvider( 4927): TimaSignature is unavailable
,D/ActivityThread( 4927): Added TimaKeyStore provider
,I/ActivityManager( 1021): Killing 4202:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,D/Mms/DraftCache( 4849): [end]    rebuildCache consume time = 84.133906
,D/ComposerPerformance( 4849): 1452261069523 ms / [DONE] Composer constructor
,D/Mms/Conversation( 4849): [start]    init() consume time = 16.982865
,E/CII     ( 4849): CommonIMSInterface: VoLTE CSC feature disabled.
,W/libprocessgroup( 1021): failed to open /acct/uid_10127/pid_4121/cgroup.procs: No such file or directory
,I/Mms/ReservationManager( 4849): ReservationManager()
,I/Mms/ReservationManager( 4849): resetAfterConnected()
,D/SensorService( 1021): [SO] -0.402 0.057 9.902
,D/TP/MmsSmsProvider( 1475): deleteConversation threadId: 9223372036854775807
,D/Mms/ArtClassLoader( 4849): init [DONE] art
,D/TP/MmsSmsProvider( 1475): query,matched:7, calling pid = 4849
,D/TP/MmsSmsProvider( 1475): match 7:Elapsed time : 2.791 ms
D/TP/MmsSmsProvider( 1475): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1475): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1475): sUpgradeVersion = 0, db.getVersion() = 81
,I/Mms/ReservationManager( 4849): getReservedSendMessageCount(): retMessageCount=0
,E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1475): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 1475): delete threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1475): need read changed broadcast:false
,D/Mms/Conversation( 4849): [end]    init consume time = 31.889687
,W/libprocessgroup( 1021): failed to open /acct/uid_10135/pid_4202/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD OFF
W/ResourcesManager( 4927): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4927): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/Mms/MessagingNotification( 4849): [start]    init() consume time = 17.14948
,D/Mms/MessagingNotification( 4849): [end]    init consume time = 2.881562
,D/Mms/SpamFilter( 4849): [start]    SpamFilter fill() begin consume time = 5.178386
,D/TP/MmsSmsProvider( 1475): query,matched:0, calling pid = 4849
,V/TP/MmsSmsProvider( 1475): getSimpleConversations entered.
D/Mms/Synchronizer( 4849): [start]    doSync consume time = 2.387395
,D/TP/MmsSmsProvider( 1475): match 0:Elapsed time : 2.156 ms
,D/TP/MmsSmsProvider( 1475): query,matched:400, calling pid = 4849
,D/Mms/MmsApp( 4849): [end]    onCreate() consume time = 2.936094
,D/TP/MmsSmsProvider( 1475): update, matched:300, calling pid = 4849
V/TP/MmsSmsProvider( 1475): syncDBData start
,V/TP/MmsSmsProvider( 1475): syncDBData sms end
,V/TP/MmsSmsProvider( 1475): syncDBData mms end
I/ActivityManager( 1021): Killing 4352:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,V/TP/MmsSmsProvider( 1475): syncDBData end
,D/Mms/DownloadManager( 4849): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 4849): roaming ------> false, mSimSlot = 0
,D/Mms/Synchronizer( 4849): [end]    doSync consume time = 7.52375
,D/Mms/MethodReflector( 4849): getSubId is called
D/Mms/TelephonyUtils( 4849): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4849): getTelephonyProperty is called
D/Mms/DownloadManager( 4849): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4849): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4849): auto download without roaming -> true
D/Mms/DownloadManager( 4849): [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
D/Mms/SpamFilter( 4849): [end]    SpamFilter fill() finished consume time = 8.804063
,D/Mms/DownloadManager( 4849): mAutoDownload ------> true
,D/Mms/MessagingNotification( 4849): checkBadgeCount unreadCount=0 badgeCount=0
,I/splitIntent( 1021): Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1021): Killing 4262:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,D/TP/SmsProvider( 1475): query,matched:26, calling pid = 4849
,D/TP/SmsProvider( 1475): match 26:Elapsed time : 1.344 ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/TP/MmsSmsProvider( 1475): query,matched:6, calling pid = 4849
,D/TP/MmsSmsProvider( 1475): match 6:Elapsed time : 1.299 ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4946): MountEmulatedStorage()
E/Zygote  ( 4946): v2
I/libpersona( 4946): KNOX_SDCARD checking this for 10023
I/libpersona( 4946): KNOX_SDCARD not a persona
,I/SELinux ( 4946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4946 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,I/SELinux ( 4946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4946): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_4352/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10068/pid_4262/cgroup.procs: No such file or directory
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/TimaKeyStoreProvider( 4946): TimaSignature is unavailable
,D/ActivityThread( 4946): Added TimaKeyStore provider
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1021): Killing 4447:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,V/UserPresentBroadcastReceiver( 1811): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/OMACP   ( 4946): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,E/Zygote  ( 4962): MountEmulatedStorage()
,E/Zygote  ( 4962): v2
I/libpersona( 4962): KNOX_SDCARD checking this for 1000
I/libpersona( 4962): KNOX_SDCARD not a persona
,I/SELinux ( 4962): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4962): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1021): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4962 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 4962): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1021): failed to open /acct/uid_10148/pid_4447/cgroup.procs: No such file or directory
,D/Mms/Omacp( 4849): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/TimaKeyStoreProvider( 4962): TimaSignature is unavailable
,D/ActivityThread( 4962): Added TimaKeyStore provider
,V/AlarmManager( 1021): waitForAlarm result :4
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   ( 4946): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,I/ValidateNoPeople( 1021): mEvictionCount: 0
,D/Mms/Contact( 4849): sContactsObserver.onChange(),selfUpdate=false
D/Mms/Contact( 4849): performUpdate:widgetCount=0
,D/Mms/ContactsCache( 4849): [start]    invalidate() consume time = 285.744531
,D/Mms/ContactsCache( 4849): [end]    invalidate() consume time = 0.400104
,E/MTPRx   ( 4962): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1021): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1021): mCursor = null
,V/MTPRx   ( 4962): sealedState: false
,V/MTPRx   ( 4962): sealedUsbMassStorageState: false
E/MTPRx   ( 4962): check value of boot_completed is1
E/MTPRx   ( 4962): check booting is completed_sys.boot_completed
,E/MTPRx   ( 4962): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 4962): Status for mount/Unmount :removed
,E/MTPRx   ( 4962): SDcard is not available
,W/MTPRx   ( 4962): value of connected istrue
,W/MTPRx   ( 4962): value of configured istrue
,W/MTPRx   ( 4962): value of mtpEnabled istrue
W/MTPRx   ( 4962): value of ptpEnabled isfalse
,E/MTPRx   ( 4962): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 4962): mFirstTime: false
,D/        ( 4962): MTP: reading debug level property
,E/MTPJNIInterface( 4962): Getting CryptionKey from JAVA
E/MTPRx   ( 4962): currentUserId is 0
,E/MTPRx   ( 4962): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 4962): cannot open file : /sys/class/android_usb/android0/bcdUSB
,E/MTPRx   ( 4962): is_Privatemode is NOT 1
,D/SettingsProvider( 1021): name = boot_time_connected
,E/MTPRx   ( 4962): Sending NORMAL_BOOT to stack
,E/MTPJNIInterface( 4962): noti = 17
,D/SettingsProvider( 1021): name = mtp_usb_conditions_met
,D/SecContentProvider( 1021): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 4962): sending MTP_ICON_ENABLED to stack
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1021): name = mtp_running_status
,D/SettingsProvider( 1021): name = mtp_usb_conditions_met
,E/MTPRx   ( 4962): else part ... so first time!!!
E/MTPPlaObsrvr( 4962): inside setContext()
E/MTPPlaObsrvr( 4962):  inside createplafiles
,E/MTPPlaObsrvr( 4962): playlist count is0
,E/MTPPlaObsrvr( 4962):  inside try branch createplafiles
,E/MTPPlaObsrvr( 4962):  inside deleteing plas createplafiles
,I/SecKeyguardClockSingleView( 1179): Ignore. Because it is same clock text
,E/MTPPlaObsrvr( 4962): Inside registerContentObserver
,E/MtpAdbObserver( 4962): inside setContext()
,E/MtpAdbObserver( 4962): Inside registerContentObserver
W/Settings( 4962): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1021): name = mtp_running_status
,D/SettingsProvider( 1021): name = mtp_usb_conditions_met
,E/MtpService( 4962): onCreate.
,E/MtpService( 4962): < MTP > Registering BroadCast receiver :::::
,V/MtpMediaDBManager( 4962): inside deleteAllDB
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/MtpService( 4962): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,D/MtpService( 1223): updating state; isCurrentUser=true, mMtpLocked=false,
,E/MtpService( 4962): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,W/MTPRx   ( 4962): calling native method
E/MTPJNIInterface( 4962): < MTP > Registering BroadCast receiver :::::
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4982): MountEmulatedStorage(),
I/libpersona( 4982): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4982): v2
I/libpersona( 4982): KNOX_SDCARD not a persona
I/SELinux ( 4982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,V/MtpMediaDBManager( 4962): inside Thread updateDB
,I/SELinux ( 4982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4982 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 4982): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  259): id=14 Removed Uoast (9/9)
I/SurfaceFlinger(  259): id=14 Removed Uoast (-2/9)
,E/MTPJNIInterface( 4962): < MTP > Registering BroadCast receiver :::::::
,E/MtpMediaDBManager( 4962): count : 26
,E/MTPJNIInterface( 4962): noti = 10
,E/MtpService( 4962): onStartCommand.
,E/MtpService( 4962): onStartCommand.
W/MTPRx   ( 4962): calling native method
E/MTPRx   ( 4962): Checking the driver time out
E/MTPJNIInterface( 4962): noti = 2
D/        ( 4962): deleting sockets before message queue initialization
,D/        ( 4962): event handler thread is created, so set the flag
E/MtpService( 4962): handleMessage. msg= { when=-3ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPRx   ( 4962): called native method
E/MTPJNIInterface( 4962): setting Media scanner status0
E/MTPJNIInterface( 4962): After setting Media scanner status0
W/MTPRx   ( 4962): notification from stack 1
E/MtpService( 4962): handleMessage. msg= { when=-8ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/        ( 4962): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 4962): Getting media scanner status0
,I/art     (  309): Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 622us total 20.369ms
,E/MTPJNIInterface( 4962): DeviceName is Thali Test (Galaxy A3)
,D/TimaKeyStoreProvider( 4982): TimaSignature is unavailable
,W/MtpMediaDBManager( 4962): sending db update complete noti to stack
E/MTPJNIInterface( 4962): noti = 29
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 16.689ms
,D/ActivityThread( 4982): Added TimaKeyStore provider
,E/MTPJNIInterface( 4962): Status for mount/Unmount :removed
E/MTPJNIInterface( 4962): SDcard is not available
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 16.670ms
,E/        ( 4962): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/TMNetworkReceiver( 4982): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
,D/TMNetworkReceiver( 4982): TMNetworkReceiver.onReceive() Enter
,D/TMNetworkReceiver( 4982): MirrorLink feauture level: using UEvent
,I/ActivityManager( 1021): Killing 4492:com.sec.modem.settings/1000 (adj 15): empty #31
,E/MTPJNIInterface( 4962): Status for mount/Unmount :removed
,E/MTPJNIInterface( 4962): SDcard is not available
E/SQLiteLog( 4962): (21) API call with NULL database connection pointer
E/SQLiteLog( 4962): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 4962): (21) API call with NULL database connection pointer,
E/SQLiteLog( 4962): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4962): (21) API call with NULL database connection pointer
E/SQLiteLog( 4962): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 4962): (21) API call with NULL database connection pointer
E/SQLiteLog( 4962): (21) misuse at line 106108 of [9491ba7d73]
,W/MTPRx   ( 4962): notification from stack 2
D/        ( 4962): [mtp_init_device] Library open with 32 bits.
D/        ( 4962): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 4962): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
,D/        ( 4962): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 4962):  [sua_support_present:1287] returning false 
D/        ( 4962): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,D/BluetoothNotiBroadcastReceiver( 1312): onReceive
,V/BluetoothStatusReceiver( 1179): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1179): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11

```
