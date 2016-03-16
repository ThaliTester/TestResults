#### Test 63008475d624ed8_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-16 12:20:28.623   315   315 I ServiceManager: Waiting for service AtCmdFwd...
03-16 12:20:28.633  1187  1187 D PhoneStatusBar: updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_HCI
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_L2CAP
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_RFCOMM
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_AVDT
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_AVRC
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_A2D
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_BNEP
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_BTM
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_GAP
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_PAN
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_SAP
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_SDP
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_GATT
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_SMP
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_BTAPP
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_BTIF
03-16 12:20:28.633  2613  2785 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
--------- beginning of system
03-16 12:20:28.633  1020  1819 D StatusBarManagerService: setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
03-16 12:20:28.643  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.643  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.643  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.643  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.653  2846  2846 E Zygote  : MountEmulatedStorage()
03-16 12:20:28.653  2846  2846 E Zygote  : v2
03-16 12:20:28.653  2846  2846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:28.653  2846  2846 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:28.653  2846  2846 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:28.653  2846  2846 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:28.653  2846  2846 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:28.653  1020  1507 I ActivityManager: Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=2846 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:28.663  2108  2816 W DriveInitializer: Background init thread ended
03-16 12:20:28.693  1020  2845 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
03-16 12:20:28.703  1020  2845 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
03-16 12:20:28.703  2846  2846 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:28.703  2846  2846 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:28.703  1020  2838 D qmi_secgps_clnt: qmi_secgps_client_init()
03-16 12:20:28.713  1020  2838 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
03-16 12:20:28.723  1020  2838 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
03-16 12:20:28.723  1020  2838 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
03-16 12:20:28.723  2613  2785 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
03-16 12:20:28.723  2613  2785 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa440fead 
03-16 12:20:28.723  2613  2785 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa440fead 
,03-16 12:20:28.753  2613  2698 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
03-16 12:20:28.753  2613  2698 E bt-btif :                : sec
03-16 12:20:28.753  2613  2698 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
03-16 12:20:28.753  2613  2698 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
03-16 12:20:28.753  2613  2698 E BluetoothServiceJni: populateRssiValuesNative
03-16 12:20:28.753  2613  2698 I bluedroid: getModelRssiValues
03-16 12:20:28.753  2613  2698 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-16 12:20:28.753  2613  2698 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
03-16 12:20:28.753  2613  2698 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
03-16 12:20:28.763  1020  1020 D SettingsProvider: name = bluetooth_name
03-16 12:20:28.763  2613  2698 D BluetoothAdapterProperties: Scan Mode:20
03-16 12:20:28.763  2613  2698 D BluetoothAdapterProperties: Discoverable Timeout:120
03-16 12:20:28.763  2613  2698 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
03-16 12:20:28.763  2613  2698 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
03-16 12:20:28.763  2613  2698 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
03-16 12:20:28.763  2613  2698 E bt-btif : btif_sock_init: !radio_req && !rfc_init
03-16 12:20:28.763  2613  2698 E bt-btif : btif_sock_init: !vhci_init
03-16 12:20:28.763  2613  2698 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
03-16 12:20:28.763  2613  2698 D IOP_DB_BT: db_open: db_open : handle 3028090896l, read 13894 bytes onto local cache
03-16 12:20:28.763  2613  2698 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
03-16 12:20:28.763  2613  2698 D IOP_DB_BT: db_query: result 1
03-16 12:20:28.763  2613  2698 I         : iop_db_open: iop_db_open status 0
03-16 12:20:28.763  2613  2698 D bte_conf: Device ID record 1 : primary
03-16 12:20:28.763  2613  2698 D bte_conf:   vendorId            = 0075
03-16 12:20:28.763  2613  2698 D bte_conf:   vendorIdSource      = 0001
03-16 12:20:28.763  2613  2698 D bte_conf:   product             = 0100
03-16 12:20:28.763  2613  2698 D bte_conf:   version             = 0200
03-16 12:20:28.763  2613  2698 D bte_conf:   clientExecutableURL = 
03-16 12:20:28.763  2613  2698 D bte_conf:   serviceDescription  = 
03-16 12:20:28.763  2613  2698 D bte_conf:   documentationURL    = 
03-16 12:20:28.763  2613  2698 D bte_conf: bte_load_did_conf no section named DID2.
03-16 12:20:28.763  2613  2698 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
03-16 12:20:28.773  2613  2840 E bt_mct  : hci lib postload completed
03-16 12:20:28.773  2613  2694 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-16 12:20:28.773  2613  2694 D BluetoothAdapterProperties: ScanMode =  20
03-16 12:20:28.773  2613  2694 D BluetoothAdapterProperties: State =  11
03-16 12:20:28.773  1020  1080 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
03-16 12:20:28.773  2846  2846 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
03-16 12:20:28.773  2613  2694 D BluetoothAdapterProperties: Setting state to 12
03-16 12:20:28.773  2613  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
03-16 12:20:28.773  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:28.773  1020  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:28.773  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
03-16 12:20:28.783  1020  1032 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=126, mSplitNum[2]=164, mBgSplitQueueNum=3 divideNum= 37 r.nextReceiver= 50 receivers.size=201
03-16 12:20:28.783  1020  1032 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
03-16 12:20:28.783  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.783  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.783  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.783  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.793  2877  2877 E Zygote  : MountEmulatedStorage()
03-16 12:20:28.793  2877  2877 E Zygote  : v2
03-16 12:20:28.793  2877  2877 I libpersona: KNOX_SDCARD checking this for 10097
03-16 12:20:28.793  2877  2877 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:28.793  2877  2877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:28.803  2877  2877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:28.803  2877  2877 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 12:20:28.803  1020  1032 I ActivityManager: Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2877 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 12:20:28.803  2613  2698 D BluetoothAdapterProperties: Scan Mode:21
03-16 12:20:28.803  2613  2698 D BluetoothAdapterProperties: Discoverable Timeout:120
03-16 12:20:28.803  1020  1762 D SettingsProvider: name = bluetooth_a2dp_sink_mode
03-16 12:20:28.803  1020  1762 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 12:20:28.803  1020  1762 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 12:20:28.803  1020  1762 D SettingsProvider: selectionArgs: false
03-16 12:20:28.803  1020  1762 D SettingsProvider: selectionArgs: 1002
03-16 12:20:28.803  1020  1762 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 12:20:28.803  1020  1762 D SettingsProvider: ret = -1
03-16 12:20:28.813  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.813  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.813  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.813  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.813  1020  1762 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-16 12:20:28.823  2613  2694 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-16 12:20:28.823  2613  2694 D BluetoothAdapterService: updateAdapterState state is 12
03-16 12:20:28.823  2877  2877 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:28.823  2877  2877 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:28.823  2892  2892 E Zygote  : MountEmulatedStorage()
03-16 12:20:28.823  2892  2892 E Zygote  : v2
03-16 12:20:28.823  2892  2892 I libpersona: KNOX_SDCARD checking this for 10081
03-16 12:20:28.823  2892  2892 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:28.833  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 12:20:28.833  1020  1045 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2892 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 12:20:28.833  2892  2892 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:28.833  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.833  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.833  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.833  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:28.833  2892  2892 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:28.833  2892  2892 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:28.843  2904  2904 E Zygote  : MountEmulatedStorage()
03-16 12:20:28.843  2904  2904 I libpersona: KNOX_SDCARD checking this for 1101
03-16 12:20:28.843  2904  2904 E Zygote  : v2
03-16 12:20:28.843  2904  2904 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:28.853  2904  2904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:28.853  1020  1045 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2904 uid=1101 gids={41101, 9997} abi=armeabi-v7a
03-16 12:20:28.853  2904  2904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:28.853  1020  1130 I ActivityManager: Killing 1587:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31
03-16 12:20:28.863  2904  2904 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:28.873  1020  1033 I ActivityManager: Killing 1951:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
03-16 12:20:28.873  2892  2892 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:28.873  2892  2892 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:28.873  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:28.873  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:28.873  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-16 12:20:28.883  1020  2838 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
03-16 12:20:28.883  2613  2694 D BluetoothAdapterService: Autoconnection is available 
03-16 12:20:28.883  2613  2694 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
03-16 12:20:28.883  2613  2694 D BluetoothAdapterService: starting service from this receiver
03-16 12:20:28.883  2613  2621 D BluetoothAdapter: onBluetoothStateChange: up=true
03-16 12:20:28.883  2613  2621 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-16 12:20:28.883  1820  1829 D BluetoothAdapter: onBluetoothStateChange: up=true
03-16 12:20:28.883  1020  2845 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-16 12:20:28.883  1820  1829 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-16 12:20:28.883   306   306 I art     : Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 629us total 35.194ms
03-16 12:20:28.903  2613  2621 D BluetoothA2dp: onBluetoothStateChange: up=true
03-16 12:20:28.903  1020  2845 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-16 12:20:28.903  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:28.903  1020  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:28.903  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 12:20:28.903  1459  1467 D BluetoothAdapter: onBluetoothStateChange: up=true
03-16 12:20:28.903  1459  1467 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-16 12:20:28.913  1020  2845 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
03-16 12:20:28.913  1020  2838 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
03-16 12:20:28.913  2613  2613 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
03-16 12:20:28.913  2613  2613 I BluetoothPbapService: Handler(): got msg=1
03-16 12:20:28.913  1020  1506 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
03-16 12:20:28.913   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 25.437ms
03-16 12:20:28.913  1020  1542 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:28.913  1020  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:28.913  1020  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-16 12:20:28.913  1020  1050 D BluetoothAdapter: onBluetoothStateChange: up=true
03-16 12:20:28.913  1020  1050 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-16 12:20:28.913  1020  1050 D BluetoothA2dp: onBluetoothStateChange: up=true
03-16 12:20:28.913  2613  2694 I BluetoothAdapterState: Entering On State from state = 11
03-16 12:20:28.923  1187  2693 D BluetoothAdapter: onBluetoothStateChange: up=true
03-16 12:20:28.923  1187  2693 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-16 12:20:28.923  1020  2838 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-16 12:20:28.923  1020  2845 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-16 12:20:28.923  2212  2220 D BluetoothAdapter: onBluetoothStateChange: up=true
03-16 12:20:28.923  2904  2904 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:28.923  2904  2904 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:28.923  2212  2220 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-16 12:20:28.923  1468  1501 D BluetoothAdapter: onBluetoothStateChange: up=true
03-16 12:20:28.923  1468  1501 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-16 12:20:28.933  1020  2838 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
03-16 12:20:28.933  1478  1502 D BluetoothAdapter: onBluetoothStateChange: up=true
03-16 12:20:28.933   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 18.083ms
03-16 12:20:28.933  1020  2845 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-16 12:20:28.933  1020  2838 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
03-16 12:20:28.933  1478  1502 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-16 12:20:28.933  1020  2845 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-16 12:20:28.933  1020  2838 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
03-16 12:20:28.933  1020  2838 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-16 12:20:28.933  1020  2838 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-16 12:20:28.933  1020  2838 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-16 12:20:28.933  1020  2838 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
03-16 12:20:28.933  1020  2838 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-16 12:20:28.933  1020  2838 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
03-16 12:20:28.943  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-16 12:20:28.943  1020  1020 I InputMethodManagerService: [BT Setting State] State =12
03-16 12:20:28.943  1020  1020 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
03-16 12:20:28.943  2892  2892 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 12:20:28.943  2892  2892 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 12:20:28.943  2892  2892 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 12:20:28.943  2892  2892 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:28.943  2892  2892 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-16 12:20:28.943  1187  1187 D BluetoothTile:  onBluetoothStateChange:
03-16 12:20:28.953  1187  1187 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-16 12:20:28.953  1187  1187 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-16 12:20:28.953  1187  1187 D BluetoothTile:  getBluetoothState : 12
03-16 12:20:28.953  2613  2930 V BluetoothPbapService: PBAP Service initSocket try: 0
03-16 12:20:28.953  1020  1507 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-16 12:20:28.953  1020  1543 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
03-16 12:20:28.963  1187  1187 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-16 12:20:28.963  1187  1626 D BluetoothTile:  handleUpdatestate:false name:null
03-16 12:20:28.963  1880  1880 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
03-16 12:20:28.963  1020  2845 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-16 12:20:28.963  1020  2838 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
03-16 12:20:28.963  1187  1626 D BluetoothTile:  handleUpdatestate:false name:null
03-16 12:20:28.963  1020  2845 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
03-16 12:20:28.973  2613  2930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-16 12:20:28.973  1187  1626 D BluetoothTile:  handleUpdatestate:false name:null
03-16 12:20:28.973  1020  2845 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-16 12:20:28.973  1020  2838 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
03-16 12:20:28.973  2613  2930 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
03-16 12:20:28.973  2613  2930 D BluetoothSocket: bindListen(), new LocalSocket 
03-16 12:20:28.973  2613  2930 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-16 12:20:28.973  2613  2930 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@26840a15
03-16 12:20:28.973  2613  2930 D BluetoothSocket: channel: 19
03-16 12:20:28.973  2613  2930 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
03-16 12:20:28.983  2904  2904 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
03-16 12:20:28.993  2613  2931 D BluetoothMapMasInstance: set MAP SDP message type : 1
03-16 12:20:29.003  2904  2904 V SmartcardService: main Received broadcast
03-16 12:20:29.003  2904  2904 V SmartcardService: Starting smartcard service after boot completed
03-16 12:20:29.003  2613  2931 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-16 12:20:29.003  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.003  1020  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:29.003  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
03-16 12:20:29.003  1459  1459 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@5b71f46, true
03-16 12:20:29.003  2613  2931 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
03-16 12:20:29.003  2613  2931 D BluetoothSocket: bindListen(), new LocalSocket 
03-16 12:20:29.003  2613  2931 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-16 12:20:29.003  2613  2931 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28a83291
03-16 12:20:29.013  2613  2931 D BluetoothSocket: channel: 5
03-16 12:20:29.013  1459  1459 D BluetoothHeadset: registerMessageListener
03-16 12:20:29.013  1255  1255 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-16 12:20:29.013  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.013  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:29.013  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 12:20:29.023  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.023  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:29.023  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 12:20:29.023  2613  2623 D HeadsetService: registerMessageListener
03-16 12:20:29.023  2613  2623 D HeadsetService: registerMessageListener
03-16 12:20:29.023  2613  2728 D HeadsetStateMachine: Disconnected process message: 70
03-16 12:20:29.023  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.023  2613  2728 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3c2be5f6
03-16 12:20:29.023  1020  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:29.023  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-16 12:20:29.033  1459  1459 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
03-16 12:20:29.033  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
03-16 12:20:29.033  1459  1459 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-16 12:20:29.033  1459  1459 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
03-16 12:20:29.033  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.033  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
03-16 12:20:29.033  1020  1819 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:29.033  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-16 12:20:29.043  2613  2728 D HeadsetStateMachine: Disconnected process message: 9
03-16 12:20:29.043  2613  2728 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
03-16 12:20:29.053  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.053  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.053  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.053  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.053  1020  1500 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-16 12:20:29.053  1020  1500 D SecContentProvider2: mCursor = null
03-16 12:20:29.063  2935  2935 E Zygote  : MountEmulatedStorage()
03-16 12:20:29.063  2935  2935 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:29.063  2935  2935 E Zygote  : v2
03-16 12:20:29.063  2935  2935 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:29.063  2935  2935 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:29.063  2935  2935 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:29.073  2935  2935 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:29.073  1020  1130 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2935 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:29.083   283   697 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
03-16 12:20:29.083   283   697 V voice   : voice_set_parameters: enter: A2dpSuspended=false
03-16 12:20:29.083   283   697 V voice   : voice_set_parameters: exit with code(-2)
03-16 12:20:29.083   283   697 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
03-16 12:20:29.083   283   697 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-16 12:20:29.083   283   697 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-16 12:20:29.083   283   697 V audio_hw_primary: adev_set_parameters: exit
03-16 12:20:29.083  2613  2728 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
03-16 12:20:29.083  1020  1819 I ActivityManager: Killing 1790:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
03-16 12:20:29.093  1020  1044 W libprocessgroup: failed to open /acct/uid_10134/pid_1951/cgroup.procs: No such file or directory
03-16 12:20:29.093  1020  1044 W libprocessgroup: failed to open /acct/uid_10052/pid_1587/cgroup.procs: No such file or directory
03-16 12:20:29.103  2935  2935 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:29.103  2935  2935 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:29.113  1848  1848 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-16 12:20:29.113  1848  1848 I dhcpcd  : wlan0: no IPv6 Routers available
03-16 12:20:29.153  2935  2935 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
03-16 12:20:29.153  1255  1255 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-16 12:20:29.153  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.153  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:29.153  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
03-16 12:20:29.153  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_1790/cgroup.procs: No such file or directory
03-16 12:20:29.153  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.153  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.153  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.153  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.173  2953  2953 E Zygote  : MountEmulatedStorage()
03-16 12:20:29.173  2953  2953 E Zygote  : v2
03-16 12:20:29.173  2953  2953 I libpersona: KNOX_SDCARD checking this for 10153
03-16 12:20:29.173  2953  2953 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:29.173  2953  2953 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:29.173  1020  1500 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2953 uid=10153 gids={50153, 9997} abi=armeabi-v7a
03-16 12:20:29.183  2953  2953 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:29.183  2953  2953 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:29.193  2953  2953 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:29.203  2953  2953 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:29.223  1020  1543 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.223  1020  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:29.223  1020  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-16 12:20:29.233  2953  2953 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:29.233  2877  2877 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
03-16 12:20:29.233  2877  2877 E ActivityThread: Failed to find provider info for flipboard.auth.internal
03-16 12:20:29.243  1020  1543 I ActivityManager: Killing 2181:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
03-16 12:20:29.243  1020  1020 I DrmEventReceiver: DrmEventReceiver : onReceive
03-16 12:20:29.243  1020  1020 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
03-16 12:20:29.253  1020  1020 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-16 12:20:29.253  1020  1020 I System.out: start Service
03-16 12:20:29.263  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.263  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.263  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.263  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.273  2972  2972 E Zygote  : MountEmulatedStorage()
03-16 12:20:29.273  2972  2972 E Zygote  : v2
03-16 12:20:29.273  2972  2972 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:29.273  2972  2972 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:29.273  2972  2972 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:29.273  1020  1080 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2972 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:29.273  1020  1080 I ActivityManager: Killing 2197:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
03-16 12:20:29.273  2972  2972 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:29.283  2972  2972 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:29.303  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-16 12:20:29.303  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 12:20:29.303  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 12:20:29.303  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:29.313  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:29.313  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:29.313  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:29.313  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.313  1020  1080 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:29.313  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-16 12:20:29.313  2972  2972 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:29.313  2972  2972 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:29.313  1020  1542 D SettingsProvider: name = next_alarm_formatted
03-16 12:20:29.313  1020  1542 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 12:20:29.313  1020  1542 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 12:20:29.313  1020  1542 D SettingsProvider: selectionArgs: false
03-16 12:20:29.313  1020  1542 D SettingsProvider: selectionArgs: 10081
03-16 12:20:29.313  1020  1542 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 12:20:29.313  1020  1542 D SettingsProvider: ret = -1
03-16 12:20:29.323  1020  1542 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10081
03-16 12:20:29.323  1020  1543 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.323  1020  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:29.323  1020  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-16 12:20:29.333  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 12:20:29.343  2701  2802 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 12:20:29.353   282   519 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 931
03-16 12:20:29.353   282   519 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 931
03-16 12:20:29.353  1020  1044 W libprocessgroup: failed to open /acct/uid_10064/pid_2181/cgroup.procs: No such file or directory
03-16 12:20:29.353  1020  1044 W libprocessgroup: failed to open /acct/uid_10065/pid_2197/cgroup.procs: No such file or directory
03-16 12:20:29.373  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.373  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.373  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.373  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.383  2993  2993 E Zygote  : MountEmulatedStorage()
03-16 12:20:29.383  2993  2993 E Zygote  : v2
03-16 12:20:29.383  2993  2993 I libpersona: KNOX_SDCARD checking this for 10155
03-16 12:20:29.383  2993  2993 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:29.383  2993  2993 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:29.393  1020  1532 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2993 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-16 12:20:29.393  1020  1532 I ActivityManager: Killing 2212:com.vlingo.midas/u0a28 (adj 15): empty #31
03-16 12:20:29.393  2993  2993 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:29.393  2993  2993 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:29.393  1020  1020 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
03-16 12:20:29.393  1020  2992 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
03-16 12:20:29.403   282   282 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-16 12:20:29.413  1478  1478 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-16 12:20:29.413  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.413  1020  1080 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:29.413  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-16 12:20:29.423  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.423  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.423  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.423  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.433  1478  1478 D CscUpdateService: onStart
03-16 12:20:29.433  1478  1478 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-16 12:20:29.433  1478  1478 I CscUpdateService: set_CSC_version
03-16 12:20:29.433  1478  1478 E CscParser: update(): xml file exist
03-16 12:20:29.433  3011  3011 E Zygote  : MountEmulatedStorage()
03-16 12:20:29.443  1255  2988 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-16 12:20:29.443  3011  3011 E Zygote  : v2
03-16 12:20:29.443  3011  3011 I libpersona: KNOX_SDCARD checking this for 10002
03-16 12:20:29.443  3011  3011 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:29.443  3011  3011 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:29.453  3011  3011 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:29.453  1020  1033 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3011 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
03-16 12:20:29.453  3011  3011 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:29.473  2876  2876 D AndroidRuntime: 
03-16 12:20:29.473  2876  2876 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 12:20:29.473  1478  1478 I CscUtil : isWifiOnly = false
03-16 12:20:29.473  2876  2876 D AndroidRuntime: CheckJNI is OFF
03-16 12:20:29.473  2876  2876 D AndroidRuntime: readGMSProperty: start
03-16 12:20:29.473  2876  2876 D AndroidRuntime: readGMSProperty: already setted!!
03-16 12:20:29.473  2876  2876 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 12:20:29.473  2876  2876 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 12:20:29.473  2876  2876 D AndroidRuntime: readGMSProperty: end
03-16 12:20:29.473  2876  2876 D AndroidRuntime: addProductProperty: start
03-16 12:20:29.473  1478  1478 I System.out: HandDataNode = null
03-16 12:20:29.473  1478  1478 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
03-16 12:20:29.483  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.483  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:29.483  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-16 12:20:29.483  1478  1478 I CscUpdateService: This is normal boot : CSC not updated
03-16 12:20:29.483  2993  2993 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:29.483  2993  2993 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:29.493  3011  3011 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:29.493  3011  3011 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:29.503  1255  1255 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-16 12:20:29.503  1478  3028 E CscParser: update(): xml file exist
,03-16 12:20:29.513  1478  3028 D CscGPS  : CSCGPS.updateParameters
03-16 12:20:29.513  1478  3028 D CscGPS  : supl host : null
03-16 12:20:29.513  1478  3028 D CscGPS  : SUPL Host is null or invalid
03-16 12:20:29.513  1478  3028 D CscGPS  : supl_ver : null
03-16 12:20:29.513  1478  3028 D CscGPS  : SUPL Ver is null or invalid
03-16 12:20:29.513  1478  3028 D CscGPS  : supl port : null
03-16 12:20:29.513  1478  3028 D CscGPS  : SUPL PORT is null or invalid
03-16 12:20:29.513  1478  3028 D CscGPS  : LPP : null
03-16 12:20:29.513  1478  3028 D CscGPS  : LPP is null or invalid
03-16 12:20:29.513  1478  3028 D CscGPS  : CSC don't have any AGPS value.
03-16 12:20:29.513  1478  1478 I CscUpdateService: same CSC Version
03-16 12:20:29.513  1478  1478 D CscUtil : Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-16 12:20:29.523  1478  2459 D TP/MmsProvider: Update uri=content://mms, match=0
03-16 12:20:29.523  1478  2459 D TP/MmsProvider: update , handleReadChangedBroadcast
03-16 12:20:29.523  1478  2459 D TP/MmsSmsProvider: need read changed broadcast:false
03-16 12:20:29.523  2383  2383 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-16 12:20:29.523  2383  2383 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 4295.173384
03-16 12:20:29.523  2383  2383 I Mms/ReservationManager: resetAfterConnected()
03-16 12:20:29.533  1478  1851 D TP/MmsSmsProvider: query,matched:7, calling pid = 2383
03-16 12:20:29.533  2383  3033 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-16 12:20:29.533  2383  3033 D Mms/TelephonyPermission: isDefault true
03-16 12:20:29.533  2892  2892 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 177.756ms
03-16 12:20:29.533  1478  1488 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2383
03-16 12:20:29.533  1478  1851 D TP/MmsSmsProvider: match 7:Elapsed time : 2.632 ms
03-16 12:20:29.543  2383  2383 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
03-16 12:20:29.543  2993  2993 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-16 12:20:29.543  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.543  1020  1819 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:29.543  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-16 12:20:29.553  1478  1851 D TP/MmsSmsProvider: query,matched:200, calling pid = 2383
03-16 12:20:29.553  1478  1851 D TP/MmsSmsProvider: match 200:Elapsed time : 1.334 ms
03-16 12:20:29.553  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.553  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.553  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.553  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.573  3034  3034 E Zygote  : MountEmulatedStorage()
03-16 12:20:29.573  3034  3034 E Zygote  : v2
03-16 12:20:29.573  3034  3034 I libpersona: KNOX_SDCARD checking this for 10043
03-16 12:20:29.573  3034  3034 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:29.573  3034  3034 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:29.573  3034  3034 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:29.573  1020  1542 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3034 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-16 12:20:29.573  3034  3034 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:29.583  1478  1502 D TP/SmsProvider: query,matched:0, calling pid = 2383
03-16 12:20:29.593  1478  1502 D TP/SmsProvider: match 0:Elapsed time : 2.657 ms
03-16 12:20:29.593  3034  3034 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:29.593  3034  3034 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:29.593  2383  2383 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-16 12:20:29.593  2383  3043 D Mms/TelephonyPermission: isDefault true
03-16 12:20:29.593  2383  3043 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-16 12:20:29.593  2383  3043 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 70.777552
03-16 12:20:29.613  2993  2993 D [0]UMC:Core: onCreate(): 
03-16 12:20:29.613  3034  3034 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-16 12:20:29.613  3034  3034 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:29.613  3034  3034 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-16 12:20:29.613  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.623  1020  1130 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:29.623  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-16 12:20:29.623   297   297 E USB_UICC: Timeout! No signal received. Retry num = 29
03-16 12:20:29.623  1020  1505 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.623  1020  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:29.623  1020  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-16 12:20:29.623  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.623  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.623  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.623  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.633   315   315 I ServiceManager: Waiting for service AtCmdFwd...
03-16 12:20:29.633  1020  1044 W libprocessgroup: failed to open /acct/uid_10028/pid_2212/cgroup.procs: No such file or directory
03-16 12:20:29.643  3050  3050 E Zygote  : MountEmulatedStorage()
03-16 12:20:29.643  3050  3050 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:29.643  3050  3050 E Zygote  : v2
03-16 12:20:29.643  3050  3050 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:29.643  3050  3050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:29.643  1020  1500 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3050 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:29.643  3050  3050 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:29.643  3050  3050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:29.663  1020  1505 D SettingsProvider: name = block_emergency_message
03-16 12:20:29.663  1020  1505 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 12:20:29.663  1020  1505 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 12:20:29.663  1020  1505 D SettingsProvider: selectionArgs: false
03-16 12:20:29.663  1020  1505 D SettingsProvider: selectionArgs: 10043
03-16 12:20:29.663  1020  1505 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 12:20:29.663  1020  1505 D SettingsProvider: ret = -1
03-16 12:20:29.663  1020  1543 W ActivityManager: getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
03-16 12:20:29.673  3050  3050 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:29.673  3050  3050 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:29.723   278   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 12:20:29.723   278   995 D Netd    : getNetworkForDns: using netid 502 for uid 10117
03-16 12:20:29.723  2993  2993 D [0]UMC:DeviceInfo: USA==US==
03-16 12:20:29.743  1478  1851 I art     : Explicit concurrent mark sweep GC freed 39982(2MB) AllocSpace objects, 11(176KB) LOS objects, 45% free, 4MB/8MB, paused 1.044ms total 132.491ms
03-16 12:20:29.743  1478  1851 D TP/SmsProvider: query,matched:51, calling pid = 2383
03-16 12:20:29.743  1478  1851 D TP/SmsProvider: match 51:Elapsed time : 1.221 ms
03-16 12:20:29.753  2383  3033 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-16 12:20:29.763  1609  1625 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-16 12:20:29.763  1020  1762 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:29.763  1020  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:29.773  1020  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
03-16 12:20:29.773  1346  1346 I WifiCredService: onCreate
03-16 12:20:29.783  1609  1625 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-16 12:20:29.783  1508  1508 D Launcher.Model: reloadBadges entered.
03-16 12:20:29.783  1346  1346 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-16 12:20:29.783  1609  1625 D BadgeProvider: sendNotify, [notify] : null
03-16 12:20:29.783  1609  1625 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-16 12:20:29.783  1346  1346 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-16 12:20:29.783  1346  1346 D MY_TAG  : Action boot completed received
03-16 12:20:29.783  1609  1625 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 12:20:29.783  1609  1625 D BadgeProvider: update, [UpdateCount] : 1
03-16 12:20:29.793  2383  3033 D Mms/MessagingNotification: setBadgeCount(), count=0
03-16 12:20:29.793  2383  3033 D Mms/MessagingNotification: remove alarm
03-16 12:20:29.803  1346  1346 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-16 12:20:29.803  1255  2988 E SQLiteLog: (283) recovered 345 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
03-16 12:20:29.803  1020  1135 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-16 12:20:29.803  1020  1135 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-16 12:20:29.803  1020  1135 E WifiNative-wlan0: invaild command id : 215
03-16 12:20:29.813  2383  3078 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-16 12:20:29.813  1478  1502 D TP/SmsProvider: query,matched:0, calling pid = 2383
03-16 12:20:29.813  1478  1502 D TP/SmsProvider: match 0:Elapsed time : 1.333 ms
03-16 12:20:29.823  1346  1346 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-16 12:20:29.823  1020  1032 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-16 12:20:29.823  2993  2993 D USER_AGENT: UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
03-16 12:20:29.833  2383  3033 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 236.049948
03-16 12:20:29.843  1346  2179 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-16 12:20:29.863  2993  2993 D [0]UMC:AdminManager: init - start
03-16 12:20:29.873  1020  1080 I art     : Explicit concurrent mark sweep GC freed 149913(8MB) AllocSpace objects, 22(2MB) LOS objects, 33% free, 22MB/33MB, paused 3.733ms total 256.287ms
03-16 12:20:29.873  3050  3050 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-16 12:20:29.883  1346  1346 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-16 12:20:29.883  1346  1346 I NearbySettings: MountReceiver.onReceive - Internal Path
03-16 12:20:29.883  2993  2993 D [0]UMC:AdminManager: loadAdmins
03-16 12:20:29.883  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 12:20:29.883  1478  1502 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-16 12:20:29.883  1478  1502 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
03-16 12:20:29.893  1478  1502 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-16 12:20:29.893  1478  1502 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
03-16 12:20:29.893  1478  1502 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
03-16 12:20:29.893  1478  1502 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 12:20:29.893  1478  1502 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 12:20:29.893  1478  1502 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 12:20:29.893  1478  1502 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 12:20:29.893  1478  1502 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 12:20:29.903  1478  1502 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 12:20:29.903  1020  1130 D SettingsProvider: name = personal_mode_enabled
03-16 12:20:29.913  1478  1502 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-16 12:20:29.913  1478  1502 D TP/MmsSmsProvider: need read changed broadcast:false
03-16 12:20:29.923  2383  3043 D Mms/Conversation: deleteTempConversation(),deleted=0
03-16 12:20:29.923  3050  3050 D DSM     : [Lines:107] Normal booted
03-16 12:20:29.923  3050  3050 D DSM     : [Lines:114] Boot completed
03-16 12:20:29.933  1255  2988 D MediaScanner: Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-16 12:20:29.933  1478  1488 D SmsProvider: Update uri=content://sms/outbox, match=8
03-16 12:20:29.933  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.933  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.933  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.933  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:29.933  1478  1488 D TP/MmsSmsProvider: need read changed broadcast:false
03-16 12:20:29.943  3083  3083 E Zygote  : MountEmulatedStorage()
03-16 12:20:29.943  3083  3083 E Zygote  : v2
03-16 12:20:29.953  3083  3083 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:29.953  3083  3083 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:29.953  3083  3083 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:29.953  2993  2993 D [0]UMC:AdminManager: init - end
03-16 12:20:29.953  2993  2993 D GSLBManager: migrateStoredUrlFromOldPref
03-16 12:20:29.953  3083  3083 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:29.963  1020  1032 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3083 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:29.963  1478  1478 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-16 12:20:29.963  1478  1478 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 12:20:29.963  1478  1478 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 12:20:29.963  3083  3083 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:29.963  1478  1478 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 12:20:29.963  1478  1478 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:29.963  1478  1478 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-16 12:20:29.963  2383  3043 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-16 12:20:29.963  2383  3043 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-16 12:20:29.963  2383  3043 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
03-16 12:20:29.963  2993  2993 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
03-16 12:20:29.963  2993  2993 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-16 12:20:29.963  2993  2993 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
03-16 12:20:29.973  2993  2993 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-16 12:20:29.973  2993  2993 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-16 12:20:29.973  2993  2993 D [0]UMC:UMCAdmin: isContainer : 0
03-16 12:20:29.973  1478  2459 D TP/SmsProvider: query,matched:26, calling pid = 2383
03-16 12:20:29.973  1478  2459 D TP/SmsProvider: match 26:Elapsed time : 4.104 ms
03-16 12:20:29.983  3083  3083 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:29.983  3083  3083 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:29.983  1255  2988 V MediaScanner: processDirectory :  /system/media
03-16 12:20:29.993  2383  3043 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-16 12:20:29.993  2383  3043 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-16 12:20:29.993  2383  3043 D Mms/TelephonyPermission: isDefault true
03-16 12:20:29.993  1346  1346 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-16 12:20:29.993  1346  1346 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-16 12:20:29.993  3083  3083 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-16 12:20:30.003  1346  1346 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
03-16 12:20:30.003  1478  1851 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2383
03-16 12:20:30.003  1346  1346 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
03-16 12:20:30.003  1020  1506 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
03-16 12:20:30.003  2993  2993 E [0]UMC:UMCAdmin: No active admin owned by uid 10155
03-16 12:20:30.003  2993  2993 D [0]UMC:UMCAdmin: isContainer : 0
03-16 12:20:30.013  2993  2993 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-16 12:20:30.013  2993  2993 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-16 12:20:30.013  2993  2993 D [0]UMC:CoreReceiver:  check PreETag 
03-16 12:20:30.023  1478  2459 D TP/MmsSmsProvider: query,matched:200, calling pid = 2383
03-16 12:20:30.033  1478  2459 D TP/MmsSmsProvider: match 200:Elapsed time : 6.853 ms
03-16 12:20:30.043  3083  3083 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-16 12:20:30.043  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
03-16 12:20:30.053  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
03-16 12:20:30.053  2993  2993 D [0]UMC:ByodSetupStarter: Container ID : 0
03-16 12:20:30.053  3083  3083 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
03-16 12:20:30.053  1255  2988 V MediaScanner:  prescan time: 451ms (DB items: 138)
03-16 12:20:30.053  1255  2988 V MediaScanner:     scan time: 80ms (Caching mode: true), (makeEntry time: 20ms ~25%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-16 12:20:30.053  1255  2988 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-16 12:20:30.053  1255  2988 V MediaScanner:    total time: 531ms
03-16 12:20:30.053  1255  2988 V MediaScanner: checked files: 130  directories : 6  (I: 0, U: 0)
03-16 12:20:30.053  2993  2993 V [0]UMC:Utils: checkAppScreen() : com.sec.android.app.launcher
03-16 12:20:30.053  2993  2993 I [0]UMC:Core: shutdown
03-16 12:20:30.053  1255  2988 D MediaScanner: checkDefaultSounds
03-16 12:20:30.063  2993  2993 I art     : System.exit called, status: 0
03-16 12:20:30.063  2993  2993 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
03-16 12:20:30.063  1255  2988 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
03-16 12:20:30.063  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-16 12:20:30.063  1478  1851 D TP/SmsProvider: query,matched:0, calling pid = 2383
03-16 12:20:30.073  1478  1851 D TP/SmsProvider: match 0:Elapsed time : 2.802 ms
03-16 12:20:30.073  1255  2988 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-16 12:20:30.083  1255  2988 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
03-16 12:20:30.083  2876  2876 E AffinityControl: AffinityControl: registerfunction enter
03-16 12:20:30.083  1255  2988 D MediaScanner: OK. notification_sound is already exist in setting DB.
03-16 12:20:30.083  1255  2988 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
03-16 12:20:30.083  1478  2459 D TP/SmsProvider: query,matched:51, calling pid = 2383
03-16 12:20:30.083  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-16 12:20:30.083  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-16 12:20:30.083  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-16 12:20:30.083  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-16 12:20:30.083  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-16 12:20:30.083  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-16 12:20:30.083  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-16 12:20:30.083  1478  2459 D TP/SmsProvider: match 51:Elapsed time : 1.804 ms
03-16 12:20:30.083  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-16 12:20:30.083  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-16 12:20:30.083  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-16 12:20:30.093  1255  2988 D MediaScanner: OK. ringtone is already exist in setting DB.
03-16 12:20:30.093  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-16 12:20:30.093  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-16 12:20:30.093  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
03-16 12:20:30.093  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-16 12:20:30.093  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-16 12:20:30.093  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-16 12:20:30.093  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-16 12:20:30.093  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-16 12:20:30.093  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-16 12:20:30.103  1255  2988 D MediaScannerService: !@done scanning volume internal
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-16 12:20:30.103  1255  2988 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-16 12:20:30.103  2584  2584 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2584) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-16 12:20:30.103  2584  2584 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2584) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-16 12:20:30.103  2584  2584 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2584) ACTION_MEDIA_SCANNER_FINISHED = Ignored
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-16 12:20:30.103  3083  3083 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-16 12:20:30.103  1346  1346 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
03-16 12:20:30.113  2383  3043 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-16 12:20:30.113  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.113  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.113  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.113  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.113  2876  2876 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 12:20:30.123  1020  1080 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3107 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:30.133  1020  1080 I ActivityManager: Killing 1524:com.android.printspooler/u0a132 (adj 15): empty #31
03-16 12:20:30.133  3107  3107 E Zygote  : MountEmulatedStorage()
03-16 12:20:30.133  3107  3107 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:30.133  3107  3107 E Zygote  : v2
03-16 12:20:30.133  3107  3107 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:30.133  3107  3107 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:30.133  3083  3083 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-16 12:20:30.133  3107  3107 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:30.133  3107  3107 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:30.133  1020  1762 E PersonaManagerService: inState():  stateMachine is null !!
03-16 12:20:30.133  1020  1762 I PersonaManagerService: PersonaId don't exist
03-16 12:20:30.133  1020  1762 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-16 12:20:30.143  1346  1346 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-16 12:20:30.143  1346  1346 I SettingSearch/SearchIntentReceiver: search setting db init!!
03-16 12:20:30.143  1020  1762 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 12:20:30.143  1609  1619 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-16 12:20:30.153  1346  1346 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-16 12:20:30.153  1255  2988 D MediaProvider: savePlaylistTableInBulkDeleter started
03-16 12:20:30.153  1255  2988 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
03-16 12:20:30.153  1255  2988 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
03-16 12:20:30.163  3107  3107 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:30.163  3107  3107 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:30.163  1255  2988 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-16 12:20:30.163  1255  2988 D MediaProvider: savePlaylistTableInBulkDeleter started
03-16 12:20:30.163  1255  2988 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-16 12:20:30.163  1255  2988 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
03-16 12:20:30.163  1255  2988 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-16 12:20:30.163  1020  1762 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-16 12:20:30.163  1020  1762 W ActivityManager: mDVFSHelper.acquire()
03-16 12:20:30.173  1255  2988 D MediaScanner: Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-16 12:20:30.173  1020  1762 D FocusedStackFrame: Set to : 0
03-16 12:20:30.173  1020  1762 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 12:20:30.173  1020  1505 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 12:20:30.173  1020  1762 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 12:20:30.173  1020  1505 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4305, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:20:30.173  1020  1762 D InputDispatcher: Focused application set to: xxxx
03-16 12:20:30.173  1020  1505 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:20:30.173  1020  1762 D InputDispatcher: Focus left window: 1508
03-16 12:20:30.173  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 12:20:30.173  2876  2876 D AndroidRuntime: Shutting down VM
03-16 12:20:30.173  1020  1051 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 12:20:30.173  1020  1051 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-16 12:20:30.183  1508  1508 D Launcher.HomeView: onPause
03-16 12:20:30.183  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.183  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.183  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.183  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.183  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-16 12:20:30.193  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 12:20:30.193  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 12:20:30.193  1020  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 12:20:30.193  1020  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 12:20:30.193   257   257 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-16 12:20:30.193  1255  2988 V MediaScanner: processDirectory :  /storage/emulated/0
03-16 12:20:30.193  3123  3123 E Zygote  : MountEmulatedStorage()
03-16 12:20:30.203  3123  3123 E Zygote  : v2
03-16 12:20:30.203  1255  2988 D MediaScanner: Skipping:
03-16 12:20:30.203  1255  2988 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
03-16 12:20:30.203  3123  3123 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:30.203  3123  3123 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:30.203  3123  3123 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:30.203  1020  1080 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3123 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:30.203  3123  3123 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:30.213  3123  3123 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:30.213  1255  2988 D MediaScanner: Skipping:
03-16 12:20:30.213  1255  2988 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-16 12:20:30.213  1255  2988 V MediaScanner: processDirectory :  /storage/extSdCard
03-16 12:20:30.213  1255  2988 W MediaScanner: Error opening directory, reason : Permission denied.
03-16 12:20:30.213  1255  2988 W MediaScanner: 7klwibgf7fxlKdCbid7
03-16 12:20:30.213  1020  1033 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2993)(adj 0) has died(30,676)
03-16 12:20:30.213  1255  2988 V MediaScanner:  prescan time: 30ms (DB items: 26)
03-16 12:20:30.213  1255  2988 V MediaScanner:     scan time: 18ms (Caching mode: true), (makeEntry time: 13ms ~72%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-16 12:20:30.213  1255  2988 V MediaScanner: postscan time: 4ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-16 12:20:30.213  1255  2988 V MediaScanner:    total time: 52ms
03-16 12:20:30.213  1255  2988 V MediaScanner: checked files: 10  directories : 16  (I: 0, U: 0)
03-16 12:20:30.223  1020  1044 W libprocessgroup: failed to open /acct/uid_10132/pid_1524/cgroup.procs: No such file or directory
03-16 12:20:30.223  1020  1020 I MotionRecognitionService: Plugged
03-16 12:20:30.223  3107  3107 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 12:20:30.223  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-16 12:20:30.233  1346  3136 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
03-16 12:20:30.233  1187  1187 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:20:30.233  1187  1187 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 12:20:30.233  1187  1187 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-16 12:20:30.233  1187  1187 D PowerUI : Cable  true --> true mBootCompleted : true
03-16 12:20:30.233  1187  1187 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-16 12:20:30.233  1444  1444 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 12:20:30.233  1444  1444 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-16 12:20:30.243  3123  3123 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:30.243  3123  3123 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:30.253  2613  2613 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 12:20:30.253  2613  2728 D HeadsetStateMachine: Disconnected process message: 10
03-16 12:20:30.263  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.263  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.263  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.263  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.263  1609  1625 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-16 12:20:30.263  1609  1625 D BadgeProvider: sendNotify, [notify] : null
03-16 12:20:30.263  1609  1625 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-16 12:20:30.263  1609  1625 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 12:20:30.263  1609  1625 D BadgeProvider: update, [UpdateCount] : 1
03-16 12:20:30.263  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-16 12:20:30.263  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-16 12:20:30.273  1686  1686 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-16 12:20:30.273  3139  3139 E Zygote  : MountEmulatedStorage()
03-16 12:20:30.273  3139  3139 I libpersona: KNOX_SDCARD checking this for 10167
03-16 12:20:30.273  3139  3139 E Zygote  : v2
03-16 12:20:30.273  3139  3139 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:30.273  1686  1686 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-16 12:20:30.273  1020  1033 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3139 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 12:20:30.273  3139  3139 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:30.273  1686  1686 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-16 12:20:30.273  3139  3139 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:30.283  3139  3139 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 12:20:30.283  1686  1686 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
03-16 12:20:30.283  1686  1686 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-16 12:20:30.283  1686  1686 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-16 12:20:30.283  1686  1686 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-16 12:20:30.283  1686  1686 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-16 12:20:30.283  1686  1686 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-16 12:20:30.283  1686  1686 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
03-16 12:20:30.283  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.283  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.283  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.283  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.293  1508  1508 D Launcher.Model: reloadBadges entered.
03-16 12:20:30.293   306   306 I art     : Explicit concurrent mark sweep GC freed 8749(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 631us total 21.601ms
03-16 12:20:30.313   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 17.127ms
03-16 12:20:30.313  3139  3139 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:30.313  3139  3139 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:30.323  1508  1508 V ActivityThread: updateVisibility : ActivityRecord{1507cf7 token=android.os.BinderProxy@29a0c0bd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-16 12:20:30.333   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 567us total 16.342ms
03-16 12:20:30.343  3154  3154 E Zygote  : MountEmulatedStorage()
03-16 12:20:30.343  3154  3154 E Zygote  : v2
03-16 12:20:30.343  3154  3154 I libpersona: KNOX_SDCARD checking this for 10146
03-16 12:20:30.343  3154  3154 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:30.343  3154  3154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:30.343  3154  3154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:30.343  3154  3154 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-16 12:20:30.343  1020  1532 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3154 uid=10146 gids={50146, 9997} abi=armeabi-v7a
03-16 12:20:30.353  2383  3043 D Mms/MessagingNotification: setBadgeCount(), count=0
03-16 12:20:30.353  1255  2988 D MediaScannerService: !@done scanning volume external
03-16 12:20:30.353  1020  1543 D SecContentProvider2: uri = 14 selection = getSealedState
03-16 12:20:30.353  1020  1543 D SecContentProvider2: mCursor = null
03-16 12:20:30.353  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:30.353  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:30.353  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-16 12:20:30.353  1020  1762 D SettingsProvider: name = aw_daemon_service_key_version_check
03-16 12:20:30.353  1020  1762 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 12:20:30.353  1020  1762 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 12:20:30.353  1020  1762 D SettingsProvider: selectionArgs: false
03-16 12:20:30.353  1020  1762 D SettingsProvider: selectionArgs: 10157
03-16 12:20:30.353  1020  1762 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 12:20:30.353  1020  1762 D SettingsProvider: ret = -1
03-16 12:20:30.363  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.363  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.363  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.363  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.363  2383  3043 D Mms/MessagingNotification: remove alarm
03-16 12:20:30.373  1020  1762 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10157
03-16 12:20:30.373  1020  1507 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
03-16 12:20:30.373  1020  1507 V ApplicationPolicy: isApplicationStateBlocked userId -1 pkgname com.android.systemui
03-16 12:20:30.373  1686  1686 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-16 12:20:30.373  1020  1020 I ValidateNoPeople: skipping global notification
03-16 12:20:30.373  1020  1020 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
03-16 12:20:30.373  1020  1506 D PowerManagerService: [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1187
03-16 12:20:30.383  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:20:30.383  3173  3173 E Zygote  : MountEmulatedStorage()
03-16 12:20:30.383  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:20:30.383  3173  3173 E Zygote  : v2
03-16 12:20:30.383  3173  3173 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:30.383  3173  3173 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:30.383  3173  3173 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:30.383  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:20:30.383  1187  1187 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:20:30.383  1187  1187 D SViewCoverView: level :100 plugged : 2
03-16 12:20:30.383  3173  3173 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:30.383  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
03-16 12:20:30.383  3173  3173 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:30.393  2876  2876 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-16 12:20:30.393  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 12:20:30.393  1020  1130 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3173 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:30.403  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-16 12:20:30.403  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-16 12:20:30.403  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
03-16 12:20:30.403  2584  2584 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2584) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-16 12:20:30.403  1020  1080 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 12:20:30.403  1020  1080 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-16 12:20:30.403  1020  1080 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 12:20:30.403  1686  1686 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-16 12:20:30.403  3154  3154 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:30.403  3154  3154 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:30.403  1187  1187 D BatteryMeterView: onDraw batteryColor : -1
03-16 12:20:30.403  1508  1508 D Launcher.HomeView: onStop
03-16 12:20:30.413  1508  1508 V ActivityThread: updateVisibility : ActivityRecord{1507cf7 token=android.os.BinderProxy@29a0c0bd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-16 12:20:30.413  1686  1686 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
03-16 12:20:30.413  1686  1686 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-16 12:20:30.413  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458127230415
,03-16 12:20:30.413  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458148800000
03-16 12:20:30.413  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-16 12:20:30.413  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
03-16 12:20:30.413  2584  2584 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2584) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-16 12:20:30.413  2584  2584 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2584) ...
03-16 12:20:30.413  2584  2584 D FactoryTestApp: [Support$Values.getString](2584) id=MODEL_COMMUNICATION_MODE, value=gsm
03-16 12:20:30.413  2584  2584 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2584) mConnectionMode = gsm
03-16 12:20:30.413  2584  2584 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2584) Create IPCWriterToSecPhoneService
03-16 12:20:30.413  2584  2584 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2584)  
,03-16 12:20:30.413  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-16 12:20:30.423  1020  1080 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:20:30.423  2584  2584 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-16 12:20:30.433  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:30.433  1020  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:30.433  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,03-16 12:20:30.443  3173  3173 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:30.443  3173  3173 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:30.443  1686  1686 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458148800000
,03-16 12:20:30.443  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:30.443  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:30.443  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-16 12:20:30.453  1686  1686 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,03-16 12:20:30.453  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458148800000
,03-16 12:20:30.463  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:30.463  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.463  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.463  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.463  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:30.463  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-16 12:20:30.473  3189  3189 E Zygote  : MountEmulatedStorage()
03-16 12:20:30.473  3189  3189 I libpersona: KNOX_SDCARD checking this for 10082
03-16 12:20:30.473  3189  3189 E Zygote  : v2
03-16 12:20:30.473  3189  3189 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:30.483  3189  3189 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:30.483  1020  1130 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3189 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
,03-16 12:20:30.483  3189  3189 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:30.483  3189  3189 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 12:20:30.483  2383  3161 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-16 12:20:30.503  1508  1508 D Launcher: onTrimMemory. Level: 20
,03-16 12:20:30.523  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-16 12:20:30.523  1020  1020 D SensorService: [SO] activate (ident=0xb8c0f240, enabled=0)
03-16 12:20:30.523  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-16 12:20:30.523  2584  2584 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2584) connected done
03-16 12:20:30.523  2584  2584 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2584) Send Response Message to SecPhone
,03-16 12:20:30.523  2584  2584 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2584) Response ��
,03-16 12:20:30.523  3189  3189 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:30.533  3189  3189 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:30.533  1020  1020 D SensorManager: unregisterListener ::   
,03-16 12:20:30.533  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-16 12:20:30.543  1020  1020 D SensorService: [SO] changed settle time [1],
03-16 12:20:30.543  1020  1020 D SensorService: [SO] setDelay [66000000]
03-16 12:20:30.543  1020  1020 D SensorService: [SO] activate (ident=0xb8da7cc0, enabled=1)
03-16 12:20:30.543  1020  1020 D SensorService: [SO] AR_init
03-16 12:20:30.543  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-16 12:20:30.543  1187  1187 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-16 12:20:30.553  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-16 12:20:30.553  3173  3173 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 12:20:30.563  1020  1506 I ActivityManager: Killing 2238:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
,03-16 12:20:30.563  3123  3123 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-16 12:20:30.573  1187  1187 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-16 12:20:30.573  1478  1488 D TP/SmsProvider: query,matched:0, calling pid = 2383
,03-16 12:20:30.583  1686  1686 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-16 12:20:30.583  1187  1187 D PersonaManager: PersonaID is invalid or persona doesn't exists. : -1
03-16 12:20:30.583  1686  1686 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-16 12:20:30.583  1478  1488 D TP/SmsProvider: match 0:Elapsed time : 8.538 ms
,03-16 12:20:30.593  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:20:30.593  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:20:30.593  1187  1187 I PhoneStatusBar: Icon Only
03-16 12:20:30.593  1187  1187 I StatusBar: Icon Only
03-16 12:20:30.593  1187  1187 D PanelView: There is/are notification(s) 
03-16 12:20:30.593  1187  1187 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 12:20:30.603   311  1076 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
03-16 12:20:30.603  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:20:30.603  1187  1187 I PhoneStatusBar: Icon Only
03-16 12:20:30.603  1187  1187 I StatusBar: Icon Only
03-16 12:20:30.603  1187  1187 D PanelView: There is/are notification(s) 
03-16 12:20:30.603  1187  1187 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 12:20:30.603  2584  2584 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2584) Send BOOTING COMPLETED done
,03-16 12:20:30.613  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:30.613  1020  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:30.613  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:30.613  2383  3043 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 781.366562
,03-16 12:20:30.623  1020  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-16 12:20:30.623   297   297 E USB_UICC: Timeout! No signal received. Retry num = 30
,03-16 12:20:30.623  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.623  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.623  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:30.623  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:30.633   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:20:30.643  2613  2729 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-16 12:20:30.653  3209  3209 E Zygote  : MountEmulatedStorage(),
,03-16 12:20:30.653  3209  3209 E Zygote  : v2
03-16 12:20:30.653  3209  3209 I libpersona: KNOX_SDCARD checking this for 10161
03-16 12:20:30.653  3209  3209 I libpersona: KNOX_SDCARD not a persona,
,03-16 12:20:30.653  3209  3209 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-16 12:20:30.653  1020  1506 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3209 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:20:30.663  3209  3209 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:30.663  3209  3209 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 12:20:30.663  3139  3139 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
03-16 12:20:30.683  1187  1187 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-16 12:20:30.693  1020  1042 D SensorService: [SO] -0.460 0.192 9.883
03-16 12:20:30.693  1020  1042 D SensorService: [SO] [100 -> 255]
,03-16 12:20:30.703  3209  3209 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:30.703  3209  3209 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:30.703   311  1076 D AT_Distributor: SetAtdStatus(), 1_1_0
03-16 12:20:30.703   311  1076 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-16 12:20:30.703  1020  1044 W libprocessgroup: failed to open /acct/uid_10045/pid_2238/cgroup.procs: No such file or directory
,03-16 12:20:30.713   297   297 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-16 12:20:30.713   297   297 E USB_UICC: usb_uicc_init_qmi failed ! 
03-16 12:20:30.713   297   297 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
,03-16 12:20:30.713   297   297 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-16 12:20:30.723  3139  3139 I LibraryLoader: Loading: webviewchromium
,03-16 12:20:30.723  2613  2729 D BluetoothMediaBrowser: no now playing list
03-16 12:20:30.723  2613  2729 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-16 12:20:30.733  3139  3139 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 6332-6340)
03-16 12:20:30.733  3139  3139 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 12:20:30.733  1020  1505 I ActivityManager: Killing 2297:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
,03-16 12:20:30.773  3123  3123 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,03-16 12:20:30.773  3173  3173 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] ,
03-16 12:20:30.773  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{1e5b863a u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-16 12:20:30.783  3139  3139 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2b48d12f}
,03-16 12:20:30.793  3139  3139 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 12:20:30.793  3139  3139 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 12:20:30.803  3123  3123 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-16 12:20:30.813  1020  1044 W libprocessgroup: failed to open /acct/uid_10110/pid_2297/cgroup.procs: No such file or directory
,03-16 12:20:30.823  3139  3139 I BrowserStartupController: Initializing chromium process, renderers=0
,03-16 12:20:30.823  3139  3139 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 12:20:30.853  3139  3139 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-16 12:20:30.853  3139  3139 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
,03-16 12:20:30.853  3139  3139 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
,03-16 12:20:30.863   257  1100 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-16 12:20:30.863   257   445 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-16 12:20:30.883  3189  3189 E UpdateRequestReceiver: ignoring update request
,03-16 12:20:30.883  3139  3139 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 12:20:30.883  3139  3139 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 12:20:30.883  3139  3139 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 12:20:30.883  3139  3139 I Adreno-EGL: Local Branch: 
03-16 12:20:30.883  3139  3139 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 12:20:30.883  3139  3139 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 12:20:30.883  3139  3139 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 12:20:30.893  3123  3123 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-16 12:20:30.893  3123  3123 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-16 12:20:30.893  3123  3123 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-16 12:20:30.893  3123  3123 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-16 12:20:30.893  3189  3189 E UpdateRequestReceiver: ignoring update request
,03-16 12:20:30.933  3189  3189 E UpdateRequestReceiver: ignoring update request
,03-16 12:20:30.963  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:30.963  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:30.963  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 12:20:30.963  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:30.973  3254  3254 E Zygote  : MountEmulatedStorage(),
03-16 12:20:30.973  3254  3254 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:30.973  3254  3254 E Zygote  : v2
03-16 12:20:30.973  3254  3254 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:30.973  3254  3254 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-16 12:20:30.973  1020  1130 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3254 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:30.983  3254  3254 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 12:20:30.983  3254  3254 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 12:20:31.003  3189  3189 E UpdateRequestReceiver: ignoring update request
,03-16 12:20:31.013  3254  3254 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:31.013  3254  3254 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:31.013  3189  3189 E UpdateRequestReceiver: ignoring update request
,03-16 12:20:31.033  3189  3189 E UpdateRequestReceiver: ignoring update request
,03-16 12:20:31.043  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.043  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.043  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.043  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:31.053  3278  3278 E Zygote  : MountEmulatedStorage()
,03-16 12:20:31.053  3278  3278 E Zygote  : v2
03-16 12:20:31.053  3278  3278 I libpersona: KNOX_SDCARD checking this for 10088
03-16 12:20:31.053  3278  3278 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:31.063  1020  1080 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3278 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:20:31.063  1020  1080 I ActivityManager: Killing 1712:com.google.android.partnersetup/u0a14 (adj 15): empty #31,
,03-16 12:20:31.073  3209  3273 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 12:20:31.073  3209  3273 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 12:20:31.103  3278  3278 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:31.113  3278  3278 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:31.113  3278  3278 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-16 12:20:31.113  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-16 12:20:31.123  3209  3273 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 12:20:31.123  3139  3242 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
03-16 12:20:31.133  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-16 12:20:31.133  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-16 12:20:31.133  3139  3139 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-16 12:20:31.143  3278  3278 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:31.143  3278  3278 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:31.183  1020  1044 W libprocessgroup: failed to open /acct/uid_10014/pid_1712/cgroup.procs: No such file or directory
,03-16 12:20:31.203  3209  3273 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-16 12:20:31.203  3209  3273 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@156062d0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 12:20:31.203  3209  3273 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 12:20:31.313  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-16 12:20:31.313  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 12:20:31.313  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 12:20:31.313  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:31.313  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:31.313  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 12:20:31.323  1020  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:31.323  1020  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.323  1020  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.323  1020  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:31.343  3301  3301 E Zygote  : MountEmulatedStorage()
03-16 12:20:31.343  3301  3301 E Zygote  : v2
03-16 12:20:31.343  3301  3301 I libpersona: KNOX_SDCARD checking this for 10008
03-16 12:20:31.343  3301  3301 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:31.343  3301  3301 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:31.343  3301  3301 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:31.343  3301  3301 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 12:20:31.353  1020  1543 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3301 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:20:31.363  3301  3301 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:31.363  3301  3301 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:31.363  3254  3254 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-16 12:20:31.363  3254  3254 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-16 12:20:31.373  3254  3310 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-16 12:20:31.373  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-16 12:20:31.373  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-16 12:20:31.383  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-16 12:20:31.383  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-16 12:20:31.383  3254  3310 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-16 12:20:31.383  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-16 12:20:31.393  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,03-16 12:20:31.393  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-16 12:20:31.393  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-16 12:20:31.403  3254  3310 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-16 12:20:31.443  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:31.443  1020  1080 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,03-16 12:20:31.443  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-16 12:20:31.443  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 12:20:31.443  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.443  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.443  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:31.463  3254  3254 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-16 12:20:31.463  3321  3321 E Zygote  : MountEmulatedStorage(),
03-16 12:20:31.463  3321  3321 E Zygote  : v2
03-16 12:20:31.463  3321  3321 I libpersona: KNOX_SDCARD checking this for 10088
03-16 12:20:31.463  3321  3321 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:31.463  3254  3254 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
03-16 12:20:31.463  3321  3321 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:31.463  1020  1080 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3321 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-16 12:20:31.463  3321  3321 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:31.473  3254  3254 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-16 12:20:31.473  3321  3321 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-16 12:20:31.473  3139  3139 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 12:20:31.483  3139  3139 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 12:20:31.493  3139  3139 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 12:20:31.493  3139  3139 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-16 12:20:31.493  3321  3321 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:31.493  3321  3321 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:31.503  3139  3139 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-16 12:20:31.513  3139  3139 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 12:20:31.513  3139  3139 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 12:20:31.533  3173  3173 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-16 12:20:31.543  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-16 12:20:31.543  3173  3173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-16 12:20:31.543  1020  1505 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:31.543  1020  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:31.543  1020  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-16 12:20:31.553  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-16 12:20:31.553  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-16 12:20:31.553  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-16 12:20:31.563   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-16 12:20:31.563   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 12:20:31.563  3209  3209 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-16 12:20:31.573  1187  1187 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-16 12:20:31.573  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-16 12:20:31.573  3173  3173 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-16 12:20:31.573  1187  1187 D OverheatReceiver: into the SAFE_MODE_ACTION
,03-16 12:20:31.573  1187  1187 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-16 12:20:31.573  1187  1187 D OverheatReceiver: isSafeMode = false
,03-16 12:20:31.583  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-16 12:20:31.583  1478  1478 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-16 12:20:31.583  1020  3165 D SettingsProvider: name = internet_call_settings_visibility
03-16 12:20:31.583  1020  3165 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 12:20:31.583  1020  3165 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 12:20:31.583  1020  3165 D SettingsProvider: selectionArgs: false
03-16 12:20:31.583  1020  3165 D SettingsProvider: selectionArgs: 1001
03-16 12:20:31.583  1020  3165 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 12:20:31.583  1020  3165 D SettingsProvider: ret = -1
03-16 12:20:31.583  3173  3173 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-16 12:20:31.583  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-16 12:20:31.583  1478  1478 D PhoneUtilsCommon: isSupportVoLTE is false.
03-16 12:20:31.583  3173  3173 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
03-16 12:20:31.593  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
03-16 12:20:31.593   288   288 E SMD     : DCD OFF
03-16 12:20:31.593  3173  3173 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
03-16 12:20:31.593  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-16 12:20:31.593  3173  3284 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-16 12:20:31.603  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-16 12:20:31.613  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-16 12:20:31.613  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-16 12:20:31.613  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-16 12:20:31.613  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-16 12:20:31.613  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-16 12:20:31.623  3254  3265 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 12:20:31.623  3139  3348 D OpenGLRenderer: Render dirty regions requested: true
,03-16 12:20:31.623  3254  3265 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 12:20:31.623  1020  1505 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 12:20:31.623  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 12:20:31.623  1020  1505 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 12:20:31.623  1020  1505 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 12:20:31.623  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 12:20:31.633  3173  3173 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-16 12:20:31.633   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 12:20:31.633  3254  3265 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-16 12:20:31.633  3254  3270 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 12:20:31.643  3254  3270 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 12:20:31.643  3139  3139 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 12:20:31.643  3139  3139 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-16 12:20:31.643  3254  3270 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-16 12:20:31.643  3173  3284 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-16 12:20:31.643  3173  3284 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-16 12:20:31.663  1020  1505 I ActivityManager: Killing 2366:com.sec.modem.settings/1000 (adj 15): empty #31
,03-16 12:20:31.743  2701  2714 W art     : Suspending all threads took: 148.762ms
,03-16 12:20:31.773  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2366/cgroup.procs: No such file or directory
,03-16 12:20:31.783  3254  3310 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT,
,03-16 12:20:31.783  3254  3310 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected,
,03-16 12:20:31.793  2701  2802 E AclDataUtils: Circle ID not found for type: 9
,03-16 12:20:31.793  3278  3278 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-16 12:20:31.793  1459  1459 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-16 12:20:31.823  3254  3310 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-16 12:20:31.823  3254  3310 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-16 12:20:31.823  3254  3310 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-16 12:20:31.853  3254  3310 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-16 12:20:31.863  3254  3310 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-16 12:20:31.873  1020  1543 I art     : Explicit concurrent mark sweep GC freed 20565(1066KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.440ms total 232.282ms
,03-16 12:20:31.883  1020  1543 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:31.883  1020  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:31.883  1020  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-16 12:20:31.883  3254  3310 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-16 12:20:31.883  1020  1505 E Tethering: No numeric data
,03-16 12:20:31.883  3254  3310 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-16 12:20:31.883  3254  3312 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-16 12:20:31.883  3254  3310 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-16 12:20:31.883  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-16 12:20:31.883  1020  1762 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:31.883  1020  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:31.883  1020  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-16 12:20:31.893  3254  3312 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 12:20:31.893  3278  3278 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-16 12:20:31.893  3254  3310 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
,03-16 12:20:31.903  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:31.903  1020  1080 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:31.903  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-16 12:20:31.903  1020  1762 E Tethering: No numeric data
,03-16 12:20:31.903  1020  1130 E Tethering: No numeric data
,03-16 12:20:31.903  3254  3310 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/16/12:20:31
03-16 12:20:31.903   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-16 12:20:31.903  3254  3310 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-16 12:20:31.903  1020  1506 E Tethering: No numeric data
,03-16 12:20:31.913  3254  3310 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-16 12:20:31.913  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.913  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.913  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.913  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:31.913  3254  3312 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-16 12:20:31.913  3254  3312 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-16 12:20:31.913  3254  3312 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-16 12:20:31.913  3254  3312 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
03-16 12:20:31.913  3254  3312 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
03-16 12:20:31.913  3254  3312 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-16 12:20:31.923  3254  3312 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-16 12:20:31.923  3254  3312 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-16 12:20:31.923  3366  3366 E Zygote  : MountEmulatedStorage()
03-16 12:20:31.923  3366  3366 E Zygote  : v2
03-16 12:20:31.923  3366  3366 I libpersona: KNOX_SDCARD checking this for 10052
03-16 12:20:31.923  3366  3366 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:31.923  3366  3366 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 12:20:31.923  1020  1080 D InputDispatcher: Focus entered window: 3139
,03-16 12:20:31.933  1020  1507 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3366 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-16 12:20:31.933  1459  1459 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
03-16 12:20:31.933  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 12:20:31.933  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 12:20:31.933  3366  3366 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:31.933  3139  3139 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
,03-16 12:20:31.933  3139  3348 I OpenGLRenderer: Initialized EGL, version 1.4
03-16 12:20:31.933  3366  3366 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 12:20:31.933  1020  1543 E Tethering: No numeric data
,03-16 12:20:31.943  3139  3348 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-16 12:20:31.943  3139  3348 D OpenGLRenderer: Enabling debug mode 0
,03-16 12:20:31.943  1020  1506 E Tethering: No numeric data
,03-16 12:20:31.943  3278  3278 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-16 12:20:31.943  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.943  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.943  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:31.943  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:31.963  3379  3379 E Zygote  : MountEmulatedStorage(),
03-16 12:20:31.963  3278  3278 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
03-16 12:20:31.963  3379  3379 E Zygote  : v2
03-16 12:20:31.963  3379  3379 I libpersona: KNOX_SDCARD checking this for 1000,
03-16 12:20:31.963  3379  3379 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:31.963  3379  3379 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:31.963  3379  3379 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 12:20:31.963  3379  3379 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:31.963  1020  1500 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3379 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:31.973  1020  1500 I ActivityManager: Killing 2432:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-16 12:20:31.973  1020  1500 I ActivityManager: Killing 2410:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #32
,03-16 12:20:31.973  1020  1500 I ActivityManager: Killing 2400:com.sec.tcpdumpservice/1000 (adj 15): empty #33
,03-16 12:20:31.983  3278  3278 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-16 12:20:31.983  3366  3366 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:31.983  3366  3366 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:31.993  3379  3379 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:31.993  3379  3379 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:32.023  3254  3312 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-16 12:20:32.053  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2400/cgroup.procs: No such file or directory
,03-16 12:20:32.053  1020  1044 W libprocessgroup: failed to open /acct/uid_10127/pid_2410/cgroup.procs: No such file or directory
,03-16 12:20:32.053  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2432/cgroup.procs: No such file or directory
,03-16 12:20:32.083  3379  3379 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-16 12:20:32.093  3278  3278 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-16 12:20:32.103  1020  1507 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 12:20:32.103  3254  3310 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-16 12:20:32.113  1020  3400 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:20:32.113  1187  1187 I StatusBar: Icon Only
03-16 12:20:32.113  1187  1187 D PanelView: There is/are notification(s) 
,03-16 12:20:32.123  3173  3284 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-16 12:20:32.133  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:32.133  1020  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:32.133  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
03-16 12:20:32.133  3254  3312 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
03-16 12:20:32.133  3139  3139 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e82b5ca time:37744
,03-16 12:20:32.143  3379  3379 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-16 12:20:32.143  3379  3379 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-16 12:20:32.143  3278  3278 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-16 12:20:32.143  3379  3379 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-16 12:20:32.153  1020  3165 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:32.153  1020  3165 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:32.153  1020  3165 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:32.153  1020  3165 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:32.173  3408  3408 E Zygote  : MountEmulatedStorage()
03-16 12:20:32.173  3408  3408 E Zygote  : v2
03-16 12:20:32.173  3408  3408 I libpersona: KNOX_SDCARD checking this for 10014
03-16 12:20:32.173  3408  3408 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:32.173  3408  3408 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:32.173  3408  3408 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 12:20:32.173  3408  3408 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 12:20:32.173  1020  3165 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3408 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
03-16 12:20:32.173  1020  1051 I ActivityManager: Displayed Component not be shown by security: +1s919ms
03-16 12:20:32.173  1020  1051 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,03-16 12:20:32.173  1020  1051 W ActivityManager: mDVFSHelper.release()
03-16 12:20:32.173  1020  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3ea3f166 u0 com.test.thalitest/.MainActivity t11} time:37789
,03-16 12:20:32.183  1020  1045 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-16 12:20:32.183  1346  3136 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-16 12:20:32.203   283   697 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-16 12:20:32.203   283   697 D audio_hw_extn: audio_extn_get_parameters: returns 
03-16 12:20:32.203   283   697 V msm8974_platform: platform_get_parameters: exit: returns - 
03-16 12:20:32.203   283   697 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-16 12:20:32.203   283   697 I str_params: key: 'call_forwarding' value: ''
,03-16 12:20:32.203  1935  1935 V InCall  : ProximitySensor -  - screenonImmediately: false
03-16 12:20:32.203  1935  1935 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-16 12:20:32.203  1935  1935 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-16 12:20:32.213  1935  1935 D ScoverManager: serviceVersion : 16908288
,03-16 12:20:32.213  1020  1506 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-16 12:20:32.213  1935  1935 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-16 12:20:32.213  1020  1532 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-16 12:20:32.213   306   306 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 655us total 41.025ms
03-16 12:20:32.213  1459  1459 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-16 12:20:32.213  1935  1935 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-16 12:20:32.213  1935  1935 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-16 12:20:32.223  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:32.223  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:32.223  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:32.223  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:32.223  1935  1935 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-16 12:20:32.223  1935  1935 D InCall  : InCallPresenter -  - dismissCoverDialog()...
03-16 12:20:32.223  3408  3408 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:32.223  3408  3408 D ActivityThread: Added TimaKeyStore provider,
03-16 12:20:32.233  1346  3136 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-16 12:20:32.233   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 17.503ms
,03-16 12:20:32.233  1935  1935 I InCall  : CallSContextMotion - stopPutDownListening
,03-16 12:20:32.233  1935  1935 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-16 12:20:32.253   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 17.370ms
,03-16 12:20:32.253  1020  1543 D LocationManagerService: getProviders()=[passive]
,03-16 12:20:32.263  1880  1880 I SamsungIME: getCurrentCandidateView
,03-16 12:20:32.263  1187  1187 D PhoneStatusBarView: setCallBackground:0
,03-16 12:20:32.263  1020  1506 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-16 12:20:32.273  1935  1935 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-16 12:20:32.273  3427  3427 E Zygote  : MountEmulatedStorage()
03-16 12:20:32.273  3427  3427 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:32.273  3427  3427 E Zygote  : v2
03-16 12:20:32.273  3427  3427 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:32.273  3427  3427 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:32.273  3427  3427 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 12:20:32.283  3254  3310 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1,
03-16 12:20:32.283  3427  3427 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:32.293  1020  1507 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3427 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:32.313  3254  3310 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-16 12:20:32.323  3173  3284 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-16 12:20:32.343  3366  3436 I ContactAccountLoggerTas: canRun() : Opted Out
,03-16 12:20:32.343  1020  1505 E Tethering: No numeric data
,03-16 12:20:32.343  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:32.343  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:32.353  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-16 12:20:32.353  1935  1935 D VideoCallManager: Instantiating VideoCallManager
,03-16 12:20:32.353  3427  3427 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:32.353  1020  1543 E Tethering: No numeric data
03-16 12:20:32.353  3427  3427 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:32.363  3278  3278 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-16 12:20:32.373  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-16 12:20:32.373  1020  1130 E Tethering: No numeric data
,03-16 12:20:32.373  1935  1935 I GFX construct_block_size_descriptor_2d second part: took 2.359948ms for 0*0 texture 0
,03-16 12:20:32.373  3173  3284 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-16 12:20:32.383  1935  1935 I GFX generate_partition_tables: took 5.367501ms for 0*0 texture 0
,03-16 12:20:32.393  1935  1935 I GFX raster: took 11.901772ms for 176*144 texture 0,
03-16 12:20:32.393  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8851f88 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8851858 counterpartCT=4 counterpartW=176 counterparth=144
,03-16 12:20:32.393  3173  3284 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-16 12:20:32.393  1020  1543 E Tethering: No numeric data
,03-16 12:20:32.393  3173  3284 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-16 12:20:32.403  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:32.403  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:32.403  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-16 12:20:32.423  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-16 12:20:32.423  1935  1935 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 12:20:32.423  1935  1935 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 12:20:32.423  1935  1935 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 12:20:32.423  1935  1935 I Adreno-EGL: Local Branch: 
03-16 12:20:32.423  1935  1935 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 12:20:32.423  1935  1935 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 12:20:32.423  1935  1935 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 12:20:32.433  1880  1880 D SamsungIME: Dismiss ExpandCandiate
,03-16 12:20:32.433   257   445 I SurfaceFlinger: id=10 Removed uhalitest (7/8),
,03-16 12:20:32.433   257   449 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-16 12:20:32.443  1935  1935 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-16 12:20:32.463  1935  1935 I glCompressedTexImage2D: took 0.619114ms for 320*61440 texture 37809
,03-16 12:20:32.473  1935  1935 I draw setup: took 11.021355ms for 320*240 texture 37809
03-16 12:20:32.473  1935  1935 E GFX GPU raster: drawn
,03-16 12:20:32.473  1020  1542 V VibratorService: hasVibrator - useVibetonz: true
,03-16 12:20:32.473  1935  1935 I GFX GPU raster ASTC: took 40.969533ms for 320*240 texture 12
03-16 12:20:32.473  1935  1935 I GFX raster: took 41.054742ms for 320*240 texture 0
03-16 12:20:32.473  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8851f08 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8851a70 counterpartCT=4 counterpartW=320 counterparth=240
,03-16 12:20:32.483  1020  1020 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,03-16 12:20:32.483  3254  3312 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-16 12:20:32.483  3139  3139 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 12:20:32.483  3366  3436 I Velvet.VelvetFactory: refreshing search history.
,03-16 12:20:32.493  1880  1880 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 12:20:32.493  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-16 12:20:32.493  1935  1935 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-16 12:20:32.503  1935  1935 I glCompressedTexImage2D: took 0.338177ms for 480*122880 texture 37813
03-16 12:20:32.503  1935  1935 I draw setup: took 0.833958ms for 480*640 texture 37813
03-16 12:20:32.503  1935  1935 E GFX GPU raster: drawn
03-16 12:20:32.503  1935  1935 I GFX GPU raster ASTC: took 6.942605ms for 480*640 texture 12
03-16 12:20:32.503  1935  1935 I GFX raster: took 7.024741ms for 480*640 texture 0
03-16 12:20:32.503  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8851a70 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8a934c8 counterpartCT=4 counterpartW=480 counterparth=640
,03-16 12:20:32.533  1346  3136 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-16 12:20:32.533  1020  1505 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:32.533  1020  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:32.533  1020  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 12:20:32.543  1020  1762 V VibratorService: hasVibrator - useVibetonz: true
,03-16 12:20:32.553  3278  3278 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,03-16 12:20:32.553  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-16 12:20:32.553  1935  1935 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-16 12:20:32.553  1935  1935 I glCompressedTexImage2D: took 0.352969ms for 440*116864 texture 37809
03-16 12:20:32.553  1935  1935 I draw setup: took 0.678698ms for 440*330 texture 37809
03-16 12:20:32.553  1935  1935 E GFX GPU raster: drawn
,03-16 12:20:32.553  1935  1935 I GFX GPU raster ASTC: took 4.371459ms for 440*330 texture 12
03-16 12:20:32.553  1935  1935 I GFX raster: took 4.461876ms for 440*330 texture 0
03-16 12:20:32.553  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a934a8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8a93878 counterpartCT=4 counterpartW=440 counterparth=330
,03-16 12:20:32.563  1020  1080 V VibratorService: hasVibrator - useVibetonz: true
,03-16 12:20:32.563  3139  3416 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-16 12:20:32.563  3139  3416 I chromium: 
,03-16 12:20:32.583  1346  3136 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 12:20:32.623  1020  2733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-16 12:20:32.623  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-16 12:20:32.623  1935  1935 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-16 12:20:32.633  1935  1935 I glCompressedTexImage2D: took 0.497240ms for 480*163840 texture 37811
03-16 12:20:32.633  1935  1935 I draw setup: took 0.814323ms for 480*640 texture 37811
03-16 12:20:32.633  1935  1935 E GFX GPU raster: drawn
,03-16 12:20:32.633   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-16 12:20:32.633  1935  1935 I GFX GPU raster ASTC: took 6.189636ms for 480*640 texture 12
03-16 12:20:32.633  1935  1935 I GFX raster: took 6.300416ms for 480*640 texture 0
03-16 12:20:32.633  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a932e8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb8aa6310 counterpartCT=4 counterpartW=480 counterparth=640
03-16 12:20:32.633  3254  3312 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-16 12:20:32.663  3254  3312 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-16 12:20:32.673  3427  3427 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-16 12:20:32.673  3427  3427 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-16 12:20:32.673  3139  3464 D jxcore_app_log: JniHelper::setJavaVM(0xb84a5448), pthread_self() = -1195414448
,03-16 12:20:32.683  3427  3427 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
03-16 12:20:32.693  1880  1880 I SamsungIME: getDebugLevel  : 0x4f4c
03-16 12:20:32.693  3209  3209 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
03-16 12:20:32.693  3139  3464 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 12:20:32.693  3139  3464 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 12:20:32.693  3139  3464 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 12:20:32.693  3139  3464 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 12:20:32.693  3139  3464 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 12:20:32.693  3139  3464 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5023f21 added. We now have 1 listener(s)
03-16 12:20:32.703  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-16 12:20:32.703  1935  1935 I GFX construct_block_size_descriptor_2d second part: took 2.460677ms for 0*0 texture 0
03-16 12:20:32.703  3139  3464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
03-16 12:20:32.703  3139  3464 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-16 12:20:32.713  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:32.713  1020  3165 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:32.713  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
03-16 12:20:32.713  3139  3464 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-16 12:20:32.713  3139  3464 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 12:20:32.713  1935  1935 I GFX generate_partition_tables: took 7.723437ms for 0*0 texture 0
03-16 12:20:32.713  3139  3464 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
03-16 12:20:32.713  1935  1935 I GFX raster: took 12.186979ms for 176*144 texture 0
03-16 12:20:32.713  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a93268 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8aa6310 counterpartCT=4 counterpartW=176 counterparth=144
03-16 12:20:32.723  3427  3441 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-16 12:20:32.723  1935  1935 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-16 12:20:32.723  1935  1935 I GFX construct_block_size_descriptor_2d second part: took 2.654427ms for 0*0 texture 0
,03-16 12:20:32.733  3139  3464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 12:20:32.733  3139  3464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 12:20:32.733  3139  3464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 12:20:32.733  3139  3464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-16 12:20:32.733  3139  3464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 12:20:32.733  3139  3464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 12:20:32.733  3139  3464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 12:20:32.733  3139  3464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 12:20:32.733  3139  3464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 12:20:32.733  3139  3464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 12:20:32.733  3139  3464 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b140634 added. We now have 1 listener(s)
03-16 12:20:32.733  1935  1935 I GFX generate_partition_tables: took 6.446615ms for 0*0 texture 0
03-16 12:20:32.733  3139  3464 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 12:20:32.733  1935  1935 I GFX raster: took 11.212500ms for 176*144 texture 0
03-16 12:20:32.733  1935  1935 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8aa6310 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8a93a30 counterpartCT=4 counterpartW=176 counterparth=144
,03-16 12:20:32.733  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:32.743  1880  1880 I SamsungIME: KeybaordView init() : load resources
03-16 12:20:32.743  1935  1935 D ScoverManager: registerListener
03-16 12:20:32.743  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:32.743  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:32.743  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:32.743  1020  1507 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-16 12:20:32.753  3139  3464 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-16 12:20:32.753  3139  3464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-16 12:20:32.753  3139  3464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-16 12:20:32.753  3139  3464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-16 12:20:32.753  3139  3464 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-16 12:20:32.753  3471  3471 E Zygote  : MountEmulatedStorage()
,03-16 12:20:32.753  3471  3471 E Zygote  : v2
03-16 12:20:32.753  3471  3471 I libpersona: KNOX_SDCARD checking this for 10090
03-16 12:20:32.753  3471  3471 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:32.763  1020  1080 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-16 12:20:32.763  1020  1080 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@3cdcdf10, pid : 1935, uid : 1001, type : 1
,03-16 12:20:32.763  2701  2768 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 12:20:32.763  3471  3471 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:32.763  3471  3471 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:32.763  1020  1532 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3471 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,03-16 12:20:32.773  3139  3464 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,03-16 12:20:32.773  3471  3471 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:32.773  3139  3464 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,03-16 12:20:32.783  3379  3379 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-16 12:20:32.793  3379  3379 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
03-16 12:20:32.793  3379  3379 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
03-16 12:20:32.793  3139  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 12:20:32.793  3139  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 12:20:32.793  3139  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-16 12:20:32.793  3139  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 12:20:32.793  3139  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 12:20:32.793  3139  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 12:20:32.793  3139  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 12:20:32.793  3139  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-16 12:20:32.793  3139  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 12:20:32.793  3139  3464 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 12:20:32.793  3139  3139 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 12:20:32.803  1020  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 12:20:32.803  1020  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:32.803  3139  3139 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-16 12:20:32.803  1020  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:32.803  1020  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:32.803  1346  3136 D ScoverManager: serviceVersion : 16908288
,03-16 12:20:32.813  3471  3471 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:32.813  3471  3471 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:32.823  3493  3493 E Zygote  : MountEmulatedStorage()
03-16 12:20:32.823  3493  3493 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:32.823  3493  3493 E Zygote  : v2
03-16 12:20:32.823  3493  3493 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:32.823  3493  3493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:32.823  1020  1543 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3493 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:32.823  1020  1543 I ActivityManager: Killing 2524:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
03-16 12:20:32.823  1020  1543 I ActivityManager: Killing 2462:com.wsomacp/u0a23 (adj 15): empty #32
,03-16 12:20:32.833  3493  3493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:32.833  3139  3139 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-16 12:20:32.833  3493  3493 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:32.843  1935  1935 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-16 12:20:32.873  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:32.873  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:32.873  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 12:20:32.873  3493  3493 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:32.873  3493  3493 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:32.893  1880  1880 I SamsungIME: getCurrentKeyboard,
03-16 12:20:32.893  1880  1880 I SamsungIME: getTextKeyboard
,03-16 12:20:32.913  1020  1033 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 12:20:32.913  3471  3471 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-16 12:20:32.913  3471  3471 D elm:15121: ELMEngine.ELMEngine( context ).
,03-16 12:20:32.913  3471  3471 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-16 12:20:32.923  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:32.923  1020  1819 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 12:20:32.923  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-16 12:20:32.923  3471  3471 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-16 12:20:32.933  1020  1543 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 12:20:32.933  1020  1080 I AudioService: getStreamVolume 3 index 0
,03-16 12:20:32.943  3471  3471 D elm:15121: ElmAgentService : onCreate()
,03-16 12:20:32.943  3471  3512 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-16 12:20:32.943  3471  3471 D elm:15121: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-16 12:20:32.943  3471  3471 D elm:15121: BootCompletedState : startBootCompleted() call
,03-16 12:20:32.943  1444  1444 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-16 12:20:32.963  3471  3471 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-16 12:20:32.973  3278  3469 I System.out: Thread-429(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-16 12:20:32.973  3471  3471 I elm:15121: Get License : 0
,03-16 12:20:32.973  3471  3471 D elm:15121: ElmAgentService : onDestroy().
,03-16 12:20:32.973  3366  3440 W GAV2    : Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 12:20:32.973  1020  3165 I ActivityManager: Killing 2545:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,03-16 12:20:32.973  1020  1044 W libprocessgroup: failed to open /acct/uid_10139/pid_2524/cgroup.procs: No such file or directory
,03-16 12:20:32.983  3493  3493 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-16 12:20:32.983  1880  1880 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-16 12:20:32.993  3278  3469 I System.out: Thread-429(ApacheHTTPLog):isSBSettingEnabled false
03-16 12:20:32.993  3278  3469 I System.out: Thread-429(ApacheHTTPLog):isShipBuild true
03-16 12:20:32.993  3278  3469 I System.out: Thread-429(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-16 12:20:32.993  3278  3469 I System.out: Thread-429(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-16 12:20:32.993  3493  3493 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-16 12:20:33.003   278   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 12:20:33.003   278   995 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-16 12:20:33.013  3366  3440 W GAV2    : Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,03-16 12:20:33.013   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-16 12:20:33.013   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 12:20:33.013  3209  3209 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-16 12:20:33.023  1020  1044 W libprocessgroup: failed to open /acct/uid_10023/pid_2462/cgroup.procs: No such file or directory
03-16 12:20:33.023   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-16 12:20:33.023   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 12:20:33.033  1020  1044 W libprocessgroup: failed to open /acct/uid_10135/pid_2545/cgroup.procs: No such file or directory
,03-16 12:20:33.033  1020  1506 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 12:20:33.033  3427  3441 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-16 12:20:33.033  3209  3209 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-16 12:20:33.043  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:33.043  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:33.043  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-16 12:20:33.043  1444  1444 V EmergencyMode: [EmergencyBase] setBootTime
,03-16 12:20:33.043  1444  1444 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-16 12:20:33.043   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-16 12:20:33.043   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 12:20:33.043  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.043  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.043  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.043  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.053  3209  3209 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-16 12:20:33.053  1020  1542 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 12:20:33.063  3523  3523 E Zygote  : MountEmulatedStorage()
03-16 12:20:33.063  3523  3523 E Zygote  : v2
03-16 12:20:33.063  3523  3523 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:33.063  3523  3523 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:33.063  3523  3523 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:33.063  3523  3523 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:33.063  1020  1819 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3523 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:33.063  3523  3523 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:33.073  1020  1507 I AudioService: getStreamVolume 3 index 0
,03-16 12:20:33.073  3366  3366 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-16 12:20:33.073  1020  1762 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:33.073  1020  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:33.073  1020  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-16 12:20:33.073  3493  3493 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-16 12:20:33.083  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:33.083  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:33.083  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 12:20:33.083  3366  3450 I ContactAccountLoggerTas: canRun() : Opted Out
,03-16 12:20:33.093  3366  3366 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
03-16 12:20:33.093  3366  3366 I ContactLabelSupplier: get() : Execute runnable (UI thread)
,03-16 12:20:33.103  3493  3493 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-16 12:20:33.113  3523  3523 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:33.123  3523  3523 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:33.143  3366  3440 I ContactLabelSupplier: get() : OptedIn = false
,03-16 12:20:33.203  1020  1080 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 12:20:33.203  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.203  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.203  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.203  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.213  3555  3555 E Zygote  : MountEmulatedStorage()
03-16 12:20:33.213  3555  3555 E Zygote  : v2
03-16 12:20:33.213  3555  3555 I libpersona: KNOX_SDCARD checking this for 10055
03-16 12:20:33.213  3555  3555 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:33.223  3555  3555 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:33.223  3555  3555 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:33.223  1020  1532 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3555 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,03-16 12:20:33.223  3555  3555 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:33.253  3523  3523 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-16 12:20:33.253  3523  3523 I testFeature: Feature.Feature(context)
03-16 12:20:33.253  3523  3523 I testFeature: Feature.readInternalDefaultXml()
03-16 12:20:33.253  3523  3523 I testFeature: ResetFeatureValue
,03-16 12:20:33.253  3523  3523 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-16 12:20:33.253  3523  3523 I CameraApp: CameraApp.getAppFeature()...
,03-16 12:20:33.263  1020  1507 I ActivityManager: Killing 2353:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-16 12:20:33.273  3555  3555 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:33.273  3555  3555 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:33.313  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 12:20:33.313  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 12:20:33.313  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:33.313  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:33.313  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:33.313  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 12:20:33.333  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.333  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.333  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.333  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.363  3493  3493 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-16 12:20:33.373  3574  3574 E Zygote  : MountEmulatedStorage()
03-16 12:20:33.373  3574  3574 E Zygote  : v2
03-16 12:20:33.373  3574  3574 I libpersona: KNOX_SDCARD checking this for 10095
03-16 12:20:33.373  3574  3574 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:33.373  3574  3574 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:33.373  1020  1032 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3574 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,03-16 12:20:33.383  3574  3574 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:33.383  3574  3574 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 12:20:33.393  1020  1032 I ActivityManager: Killing 2566:com.android.calendar/u0a131 (adj 15): empty #31
,03-16 12:20:33.403  3493  3493 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-16 12:20:33.403  3493  3493 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-16 12:20:33.403  3493  3493 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-16 12:20:33.413  3493  3493 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-16 12:20:33.413  3493  3493 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
03-16 12:20:33.413  3493  3493 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-16 12:20:33.423  3555  3555 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-16 12:20:33.433  3574  3574 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:33.433  3574  3574 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:33.453  1020  1080 I ActivityManager: Killing 2630:com.android.keychain/1000 (adj 15): empty #31
,03-16 12:20:33.453  1346  3136 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-16 12:20:33.463  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:33.463  1020  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:33.463  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 12:20:33.463  1020  2820 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:20:33.473  3574  3574 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,03-16 12:20:33.483  1346  3136 D Settings_Utils: isSupportVNFestival SM-A300FU XEO
,03-16 12:20:33.483  3574  3574 E SQLiteLog: (284) automatic index on titles(filter_id)
,03-16 12:20:33.493  3555  3555 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-16 12:20:33.493  3555  3555 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-16 12:20:33.493  3555  3555 D UserAnalysis: Create SecureDbHelper
,03-16 12:20:33.493  1020  1032 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 12:20:33.493  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-16 12:20:33.503  3301  3301 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-16 12:20:33.513  3555  3555 D IntelligenceServiceApplication: onCreate()
,03-16 12:20:33.513  3555  3555 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-16 12:20:33.513  1020  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.513  1020  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.513  1020  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.513  1020  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.533  3597  3597 E Zygote  : MountEmulatedStorage(),
03-16 12:20:33.533  3597  3597 E Zygote  : v2
03-16 12:20:33.533  3597  3597 I libpersona: KNOX_SDCARD checking this for 10056
03-16 12:20:33.533  3597  3597 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:33.533  3366  3436 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201),
,03-16 12:20:33.533  3597  3597 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:33.533  3597  3597 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:33.533  3301  3301 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated,
03-16 12:20:33.533  1020  1762 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3597 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-16 12:20:33.533  2584  3207 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3207)  
,03-16 12:20:33.543  1346  3136 W ResourceType: Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,03-16 12:20:33.543  3597  3597 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:33.543  1020  1762 I ActivityManager: Killing 2671:com.android.chrome/u0a77 (adj 15): empty #31
,03-16 12:20:33.553  1020  3165 I ActivityManager: Killing 2499:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,03-16 12:20:33.553  1020  1542 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:33.553  1020  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:33.553  1020  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 12:20:33.553  3574  3574 I FilterProviderReceiver: onReceive in FilterProviderReceiver
,03-16 12:20:33.553  3574  3574 I FilterProviderReceiver: onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,03-16 12:20:33.563  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.563  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.563  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.563  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.563  3301  3301 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-16 12:20:33.563  1346  3136 W ResourceType: Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75),
03-16 12:20:33.573  3555  3555 D IntelligenceServiceApplication: no applications having user consent for prediction
03-16 12:20:33.573  3615  3615 I libpersona: KNOX_SDCARD checking this for 10098
03-16 12:20:33.573  3615  3615 E Zygote  : MountEmulatedStorage()
03-16 12:20:33.573  3615  3615 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:33.573  3615  3615 E Zygote  : v2
03-16 12:20:33.573  3615  3615 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:33.573  3615  3615 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:33.583  1020  1033 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3615 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-16 12:20:33.583  3597  3597 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:33.583  1020  1033 I ActivityManager: Killing 1220:com.android.defcontainer/u0a3 (adj 15): empty #31
03-16 12:20:33.583  3597  3597 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:33.583  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:33.583  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:33.583  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 12:20:33.583  3615  3615 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:33.593  1020  1033 I ActivityManager: Killing 2746:com.android.email/u0a141 (adj 15): empty #31
,03-16 12:20:33.613  1020  1762 I ActivityManager: Killing 2846:com.mobeam.barcodeService/1000 (adj 15): empty #31
,03-16 12:20:33.613  3615  3615 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:33.613  3615  3615 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:33.623  3366  3436 I LibraryLoader: Loading: webviewchromium
,03-16 12:20:33.633  3301  3301 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-16 12:20:33.643  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.643  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.643  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.643  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.653  3631  3631 E Zygote  : MountEmulatedStorage(),
03-16 12:20:33.653  3366  3436 I LibraryLoader: Time to load native libraries: 42 ms (timestamps 9225-9267)
03-16 12:20:33.653  3366  3436 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 12:20:33.653  3631  3631 E Zygote  : v2
,03-16 12:20:33.653  3631  3631 I libpersona: KNOX_SDCARD checking this for 10013
03-16 12:20:33.653  3631  3631 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:33.653  3631  3631 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:33.663  1020  1819 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3631 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,03-16 12:20:33.663  1020  1819 I ActivityManager: Killing 2877:flipboard.boxer.app/u0a97 (adj 15): empty #31
,03-16 12:20:33.663  3631  3631 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:33.663  3555  3555 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-16 12:20:33.673  3631  3631 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 12:20:33.693  3555  3555 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-16 12:20:33.693  3555  3555 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-16 12:20:33.703  3366  3436 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 12:20:33.713  3631  3631 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:33.713  3631  3631 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:33.723  3615  3615 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-16 12:20:33.733  3615  3615 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-16 12:20:33.743  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:33.743  1020  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:33.743  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 12:20:33.743  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.743  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.743  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:33.743  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:33.763  3654  3654 E Zygote  : MountEmulatedStorage()
03-16 12:20:33.763  3654  3654 E Zygote  : v2
03-16 12:20:33.763  3654  3654 I libpersona: KNOX_SDCARD checking this for 10099
03-16 12:20:33.763  3654  3654 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:33.763  3654  3654 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:33.763  3654  3654 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:33.763  3654  3654 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 12:20:33.773  1020  1033 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3654 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:20:33.773  1020  1033 I ActivityManager: Killing 2904:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-16 12:20:33.773  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:33.773  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:33.773  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 12:20:33.773  3139  3488 W jxcore-log: Initializing JXcore engine
03-16 12:20:33.773  3139  3488 W jxcore-log: JXcore engine is ready
,03-16 12:20:33.793  3209  3599 W MessageQueue: Handler (android.os.Handler) {3647e2ea} sending message to a Handler on a dead thread
03-16 12:20:33.793  3209  3599 W MessageQueue: java.lang.IllegalStateException: Handler (android.os.Handler) {3647e2ea} sending message to a Handler on a dead thread
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at ffw.a(SourceFile:327)
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at guw.a(SourceFile:120)
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at guf.c(SourceFile:26)
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at gui.run(SourceFile:297)
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at android.os.Looper.loop(Looper.java:145)
03-16 12:20:33.793  3209  3599 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 12:20:33.793  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2353/cgroup.procs: No such file or directory
03-16 12:20:33.793  1020  1044 W libprocessgroup: failed to open /acct/uid_10131/pid_2566/cgroup.procs: No such file or directory
,03-16 12:20:33.803  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2630/cgroup.procs: No such file or directory
,03-16 12:20:33.813  1020  1044 W libprocessgroup: failed to open /acct/uid_10077/pid_2671/cgroup.procs: No such file or directory
,03-16 12:20:33.813  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2846/cgroup.procs: No such file or directory
03-16 12:20:33.813  1020  1044 W libprocessgroup: failed to open /acct/uid_10003/pid_1220/cgroup.procs: No such file or directory
,03-16 12:20:33.813  3654  3654 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:33.813  3654  3654 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:33.813  3209  3608 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
03-16 12:20:33.813  3209  3608 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-16 12:20:33.823  3209  3608 I System.out: Thread-465(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-16 12:20:33.823  3209  3608 I System.out: Thread-465(ApacheHTTPLog):isSBSettingEnabled false
,03-16 12:20:33.823  3209  3608 I System.out: Thread-465(ApacheHTTPLog):isShipBuild true
03-16 12:20:33.823  3209  3608 I System.out: Thread-465(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-16 12:20:33.823  3209  3608 I System.out: Thread-465(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-16 12:20:33.823   278   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 12:20:33.823   278   995 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,03-16 12:20:33.843  1020  1044 W libprocessgroup: failed to open /acct/uid_10141/pid_2746/cgroup.procs: No such file or directory
,03-16 12:20:33.843  1020  1044 W libprocessgroup: failed to open /acct/uid_10039/pid_2499/cgroup.procs: No such file or directory
,03-16 12:20:33.843  1020  1044 W libprocessgroup: failed to open /acct/uid_10097/pid_2877/cgroup.procs: No such file or directory
03-16 12:20:33.843  1020  1044 W libprocessgroup: failed to open /acct/uid_1101/pid_2904/cgroup.procs: No such file or directory
,03-16 12:20:33.853  3631  3631 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-16 12:20:33.853  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:33.853  1020  3165 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:33.853  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-16 12:20:33.883  1890  1890 E audit   : type=1400 msg=audit(1458127233.883:205): avc:  denied  { ioctl } for  pid=3488 comm="Thread-413" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-16 12:20:33.893  1890  1890 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:33.893  1890  1890 E audit   : type=1300 msg=audit(1458127233.883:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=4 a3=9238f8f8 items=0 ppid=306 ppcomm=main pid=3488 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-413" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-16 12:20:33.893  1890  1890 E audit   : type=1320 msg=audit(1458127233.883:205): 
,03-16 12:20:33.893  1912  1912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-16 12:20:33.893  3631  3671 V OneTimeService: OneTimeService.onHandleIntent
,03-16 12:20:33.903  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:33.903  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:33.903  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-16 12:20:33.903  3139  3488 W jxcore-log: Starting JXcore engine
,03-16 12:20:33.903  1912  3674 D SecUISvc: Thread created.
,03-16 12:20:33.903  1912  1912 D SecUISvc: Service started flags 0 startId 1
,03-16 12:20:33.953  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:33.963  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:33.963  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 12:20:33.973  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:33.983  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:33.983  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 12:20:33.983  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:33.983  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:33.983  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 12:20:33.983  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:33.983  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:33.983  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 12:20:33.993  1020  1762 V VibratorService: hasVibrator - useVibetonz: true
,03-16 12:20:34.013  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:34.023  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:34.023  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:34.033  3139  3488 W jxcore-log: Platform android
03-16 12:20:34.033  3139  3488 W jxcore-log: 
03-16 12:20:34.033  3139  3488 W jxcore-log: Process ARCH arm
03-16 12:20:34.033  3139  3488 W jxcore-log: 
,03-16 12:20:34.043  3597  3597 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.7.KK_APP
,03-16 12:20:34.053  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:34.053  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.053  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.053  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:34.083  3684  3684 E Zygote  : MountEmulatedStorage()
03-16 12:20:34.083  3684  3684 I libpersona: KNOX_SDCARD checking this for 10058
03-16 12:20:34.083  3684  3684 E Zygote  : v2
03-16 12:20:34.083  3684  3684 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:34.083  3684  3684 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:34.083  3684  3684 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:34.083  1020  1819 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3684 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:20:34.083  3684  3684 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:34.103  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:34.103  1020  3165 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:34.103  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 12:20:34.113   306   306 I art     : Explicit concurrent mark sweep GC freed 8687(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 639us total 22.659ms
,03-16 12:20:34.123  3684  3684 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:34.133  3684  3684 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:34.133   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 21.406ms
,03-16 12:20:34.143  2108  3680 D FileApkUtils: Optimizing (staging complete)
,03-16 12:20:34.143  2108  3680 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
,03-16 12:20:34.153  1020  1762 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:34.153  1020  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 12:20:34.153  1020  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-16 12:20:34.153  1745  1745 I Hs20UtilService: Starting #4
,03-16 12:20:34.153  1745  1786 I Hs20UtilService: Message received 5003
,03-16 12:20:34.153   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 24.256ms
,03-16 12:20:34.163  2108  3680 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-16 12:20:34.163  1020  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.163  1020  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.163  1020  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.163  1020  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:34.173  2108  3680 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
,03-16 12:20:34.183  3701  3701 E Zygote  : MountEmulatedStorage()
,03-16 12:20:34.183  3701  3701 E Zygote  : v2
03-16 12:20:34.183  3701  3701 I libpersona: KNOX_SDCARD checking this for 10018
03-16 12:20:34.183  3701  3701 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:34.183  3701  3701 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:34.183  3701  3701 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 12:20:34.183  1020  1543 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3701 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
03-16 12:20:34.183  3701  3701 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:34.223  3701  3701 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:34.223  3701  3701 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:34.303  3701  3701 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 16 12:20:34 GMT+01:00 2016
,03-16 12:20:34.303  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:34.303  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:34.303  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-16 12:20:34.313  3139  3488 I jxcore-log: JXcore Cordova bridge is ready!
03-16 12:20:34.313  3139  3488 I jxcore-log: 
,03-16 12:20:34.313  3139  3488 W jxcore-log: JXcore engine is started
,03-16 12:20:34.313  3701  3701 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-16 12:20:34.313  3139  3464 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 12:20:34.313  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:34.323  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.323  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.323  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:34.323  3701  3701 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-16 12:20:34.323  3701  3701 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-16 12:20:34.333  3717  3717 E Zygote  : MountEmulatedStorage()
03-16 12:20:34.333  3717  3717 I libpersona: KNOX_SDCARD checking this for 10020
03-16 12:20:34.333  3717  3717 E Zygote  : v2
03-16 12:20:34.333  3717  3717 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:34.333  3139  3488 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 12:20:34.333  3139  3488 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 12:20:34.333  3701  3701 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-16 12:20:34.333  1020  1033 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3717 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,03-16 12:20:34.343  3701  3716 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-16 12:20:34.353  3717  3717 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:34.353  3717  3717 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 12:20:34.353  3139  3139 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-16 12:20:34.353  3717  3717 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:34.353  1020  1507 D FocusedStackFrame: Set to : 0
03-16 12:20:34.353  1020  1507 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 12:20:34.353  1020  1507 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 12:20:34.353  1020  1507 D InputDispatcher: Focused application set to: xxxx
,03-16 12:20:34.353  1020  1507 D InputDispatcher: Focus left window: 3139
,03-16 12:20:34.363  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-16 12:20:34.363  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 12:20:34.373  3684  3684 I ExternalOEMControlProvider: onCreate
,03-16 12:20:34.373   257   449 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (2132 us)
,03-16 12:20:34.373   278   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 12:20:34.373   278   995 D Netd    : getNetworkForDns: using netid 502 for uid 10052
,03-16 12:20:34.383  3717  3717 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:34.383  3717  3717 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:34.393  1346  3136 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-16 12:20:34.403  3139  3464 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 44ms. Plugin should use CordovaInterface.getThreadPool().
,03-16 12:20:34.403  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:34.403  1020  3165 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:34.403  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:34.403  1020  1532 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-16 12:20:34.403  1020  1532 W ActivityManager: mDVFSHelper.acquire()
,03-16 12:20:34.403  1020  1532 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 12:20:34.413  1020  1532 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-16 12:20:34.413  1020  1532 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-16 12:20:34.413  3701  3716 I KLMS-2.5.123: : KLMSIntentService(): BOOT_COMPLETED
,03-16 12:20:34.423  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:34.423  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:34.423  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 12:20:34.453  1508  1508 D Launcher: onRestart, Launcher: 790319435
,03-16 12:20:34.453  3366  3436 I qtaguid : Tagging socket 39 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
,03-16 12:20:34.453  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 12:20:34.453  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.453  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.453  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-16 12:20:34.473  3741  3741 E Zygote  : MountEmulatedStorage()
03-16 12:20:34.473  3741  3741 E Zygote  : v2
03-16 12:20:34.473  3741  3741 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:34.473  3741  3741 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:34.473  3741  3741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:34.473  1020  1819 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3741 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:34.473  3741  3741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:34.473  3741  3741 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:34.483  1508  1508 D Launcher: onStart, Launcher: 790319435
,03-16 12:20:34.483  1508  1508 D Launcher.HomeView: onStart
,03-16 12:20:34.483  1508  1508 D Launcher: onResume, Launcher: 790319435
,03-16 12:20:34.483  1020  1130 D SettingsProvider: name = kids_home_mode
03-16 12:20:34.483  1020  1130 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 12:20:34.483  1020  1130 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 12:20:34.483  1020  1130 D SettingsProvider: selectionArgs: false
03-16 12:20:34.483  1020  1130 D SettingsProvider: selectionArgs: 10006
03-16 12:20:34.483  1020  1130 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 12:20:34.483  1020  1130 D SettingsProvider: ret = -1
,03-16 12:20:34.483  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-16 12:20:34.483  1020  1020 D SensorService: [SO] activate (ident=0xb8da7cc0, enabled=0)
03-16 12:20:34.483  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-16 12:20:34.493  1508  1508 D Launcher.HomeView: onResume
,03-16 12:20:34.503  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-16 12:20:34.533  1020  1506 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-16 12:20:34.533  1020  1506 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 12:20:34.533  1020  1506 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 12:20:34.533  1020  1506 D SettingsProvider: selectionArgs: false
03-16 12:20:34.533  1020  1506 D SettingsProvider: selectionArgs: 10058
03-16 12:20:34.533  1020  1506 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 12:20:34.533  1020  1506 D SettingsProvider: ret = -1
,03-16 12:20:34.533  1020  1020 D SensorManager: unregisterListener ::   
,03-16 12:20:34.533  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-16 12:20:34.533  1020  1020 D SensorService: [SO] changed settle time [0]
03-16 12:20:34.533  1020  1020 D SensorService: [SO] setDelay [200000000]
03-16 12:20:34.533  1020  1020 D SensorService: [SO] activate (ident=0xb8dec3b8, enabled=1)
03-16 12:20:34.533  1020  1020 D SensorService: [SO] AR_init
03-16 12:20:34.533  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-16 12:20:34.533  3741  3741 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:34.533  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.533  3701  3701 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-16 12:20:34.533  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.533  3741  3741 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:34.533  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.533  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.533  1020  1506 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
03-16 12:20:34.543  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-16 12:20:34.543  1020  1505 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-16 12:20:34.543  1020  1505 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 12:20:34.543  1020  1505 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 12:20:34.543  1020  1505 D SettingsProvider: selectionArgs: false
03-16 12:20:34.543  1020  1505 D SettingsProvider: selectionArgs: 10058
03-16 12:20:34.543  1020  1505 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 12:20:34.543  1020  1505 D SettingsProvider: ret = -1
,03-16 12:20:34.553  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-16 12:20:34.553  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
03-16 12:20:34.553  3760  3760 E Zygote  : MountEmulatedStorage()
03-16 12:20:34.553  3760  3760 E Zygote  : v2
,03-16 12:20:34.563  3760  3760 I libpersona: KNOX_SDCARD checking this for 1000
,03-16 12:20:34.563  1020  1542 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3760 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:34.563  3760  3760 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:34.563  3760  3760 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:34.563  3760  3760 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:34.563  1020  1080 I art     : Explicit concurrent mark sweep GC freed 25028(1378KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 24MB/36MB, paused 38.031ms total 207.390ms
03-16 12:20:34.563  1020  1542 I ActivityManager: Killing 2953:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
03-16 12:20:34.563  3760  3760 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 12:20:34.573  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:34.573  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:34.573  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:34.583  1020  1505 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-16 12:20:34.593  1508  1508 D MenuAppsGridFragment: onResume
,03-16 12:20:34.593  1020  1033 D ActivityManager: handle home activity for 0
03-16 12:20:34.593  1020  1033 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-16 12:20:34.593  1020  1033 D KnoxTimeoutHandler: post home show event for user 0
03-16 12:20:34.593  1020  1033 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 12:20:34.593  1020  1020 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-16 12:20:34.593  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 12:20:34.593  1020  1033 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 12:20:34.593  1020  1033 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 12:20:34.593  1020  1020 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-16 12:20:34.593  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 12:20:34.593   288   288 E SMD     : DCD OFF
,03-16 12:20:34.593   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=4, Mauncher
,03-16 12:20:34.603  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-16 12:20:34.603  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 12:20:34.603  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 12:20:34.603  1020  1762 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:34.603  1020  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:34.603  1020  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:34.613  1020  3165 D InputDispatcher: Focus entered window: 1508
,03-16 12:20:34.623  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-16 12:20:34.623  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 12:20:34.623  1508  1508 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-16 12:20:34.633  3760  3760 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:34.633  3760  3760 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:34.643  3278  3469 I System.out: pool-10-thread-1 calls detatch()
,03-16 12:20:34.643  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-16 12:20:34.653  1020  1506 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 12:20:34.653  1187  1187 I StatusBar: Icon Only
,03-16 12:20:34.653  1187  1187 D PanelView: There is/are notification(s) 
,03-16 12:20:34.653  3139  3139 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-16 12:20:34.663  1020  3778 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:20:34.663  3408  3408 I RlzPingService: Setting next ping for 1458732034666
,03-16 12:20:34.663  1880  1880 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-16 12:20:34.663  3741  3741 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-16 12:20:34.693  1020  1819 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 12:20:34.703  1020  1044 W libprocessgroup: failed to open /acct/uid_10153/pid_2953/cgroup.procs: No such file or directory
,03-16 12:20:34.713  1508  1508 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29a0c0bd time:40321
,03-16 12:20:34.713  1020  1051 D PersonaManager: isKioskContainerExistOnDevice
,03-16 12:20:34.733  3760  3760 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-16 12:20:34.733  1820  1820 D ChimeraCfgMgr: Reading stored module config
,03-16 12:20:34.733  1020  1033 D SecContentProvider2: uri = 14 selection = getSealedState
03-16 12:20:34.733  1020  1033 D SecContentProvider2: mCursor = null
,03-16 12:20:34.743  1020  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-16 12:20:34.743  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
03-16 12:20:34.743  3741  3741 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-16 12:20:34.743  3741  3741 I ServiceMode: setReferenceIsDumpState : 0
03-16 12:20:34.743  3366  3436 I qtaguid : Untagging socket 43
,03-16 12:20:34.743  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
,03-16 12:20:34.743  3366  3436 I qtaguid : Untagging socket 43
03-16 12:20:34.743  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
,03-16 12:20:34.743  3366  3436 I qtaguid : Untagging socket 43
,03-16 12:20:34.743  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
03-16 12:20:34.743  3366  3436 I qtaguid : Untagging socket 43
03-16 12:20:34.743  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
03-16 12:20:34.743  3366  3436 I qtaguid : Untagging socket 43
,03-16 12:20:34.743  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
,03-16 12:20:34.743  3366  3436 I qtaguid : Untagging socket 43
03-16 12:20:34.743  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
,03-16 12:20:34.743  3366  3436 I qtaguid : Untagging socket 43
03-16 12:20:34.743  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
,03-16 12:20:34.743  3366  3436 I qtaguid : Untagging socket 43
,03-16 12:20:34.743  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
03-16 12:20:34.743  3366  3436 I qtaguid : Untagging socket 43
03-16 12:20:34.743  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
,03-16 12:20:34.743  3366  3436 I qtaguid : Untagging socket 43
,03-16 12:20:34.753  3654  3782 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-16 12:20:34.753  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
,03-16 12:20:34.753  3366  3436 I qtaguid : Untagging socket 43
,03-16 12:20:34.753  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
03-16 12:20:34.753  3366  3436 I qtaguid : Untagging socket 43
,03-16 12:20:34.753  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
03-16 12:20:34.753  3366  3436 I qtaguid : Untagging socket 43
,03-16 12:20:34.753  1020  1532 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-16 12:20:34.753  1020  1532 D SecContentProvider2: mCursor = null
,03-16 12:20:34.763  3760  3760 V MTPRx   : sealedState: false
03-16 12:20:34.763  3760  3760 V MTPRx   : sealedUsbMassStorageState: false
,03-16 12:20:34.763  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.763  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.763  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.763  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:34.773  3785  3785 E Zygote  : MountEmulatedStorage()
03-16 12:20:34.773  3785  3785 E Zygote  : v2
03-16 12:20:34.773  3785  3785 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:34.773  3785  3785 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:34.773  3785  3785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:34.773  2613  2695 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-16 12:20:34.783  3785  3785 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:34.783  3785  3785 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-16 12:20:34.783  1020  1506 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3785 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-16 12:20:34.783  1020  1506 I ActivityManager: Killing 2255:flipboard.app/u0a96 (adj 15): empty #31
03-16 12:20:34.783  1020  1051 I ActivityManager: Displayed Component not be shown by security: +381ms
,03-16 12:20:34.793  1020  1033 D SettingsProvider: name = mtp_usb_connection_status
03-16 12:20:34.793  1020  1819 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 12:20:34.813  3785  3785 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:34.813  3785  3785 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:34.833  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:34.833  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:34.843  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-16 12:20:34.863  3654  3806 I Gmail   : getAccountsCursor
,03-16 12:20:34.883  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 12:20:34.883  1020  1080 D SettingsProvider: name = media_player_mode
,03-16 12:20:34.903  1020  1044 W libprocessgroup: failed to open /acct/uid_10096/pid_2255/cgroup.procs: No such file or directory
,03-16 12:20:34.903  1020  1032 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 12:20:34.903  1020  1045 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,03-16 12:20:34.903  1020  1045 W ActivityManager: mDVFSHelper.release()
,03-16 12:20:34.903  1020  1045 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-16 12:20:34.913  2108  2108 W InstanceID/Rpc: Found 10011
,03-16 12:20:34.913  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 12:20:34.933  3654  3654 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 12:20:34.943  1020  1819 D SettingsProvider: name = mtp_running_status
,03-16 12:20:34.943  1820  1820 D WearableService: callingUid 10011, callindPid: 1820
,03-16 12:20:34.943  1020  1042 D SensorService: [SO] currT = 40551131000, prevT = 40091084000, diff = 460047000, [-0.460 0.192 9.902]
03-16 12:20:34.943  1020  1042 D SensorService: [SO] -0.460 0.192 9.902
03-16 12:20:34.943  1020  1042 D SensorService: [SO] [100 -> 255]
,03-16 12:20:34.943  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 12:20:34.953  1020  1130 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 12:20:34.963  1020  3165 D SettingsProvider: name = media_mount_count
,03-16 12:20:34.963  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 12:20:34.963  1020  1507 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-16 12:20:34.963  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:34.963  1020  1033 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-16 12:20:34.973  3785  3785 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-16 12:20:34.973  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:34.973  3785  3785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-16 12:20:34.973  1020  1505 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:34.973  1020  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:34.973  1020  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-16 12:20:34.973  3366  3436 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3366, getuid(): 10052
,03-16 12:20:34.973  1020  1500 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 12:20:34.973  3785  3785 D NPS_WSSNPS: [] Service onCreate!!
,03-16 12:20:34.983  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.983  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.983  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:34.983  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:34.983  3366  3450 I ContactAccountLoggerTas: canRun() : Opted Out
,03-16 12:20:34.993  3814  3814 E Zygote  : MountEmulatedStorage()
03-16 12:20:34.993  3814  3814 E Zygote  : v2
03-16 12:20:34.993  3814  3814 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:34.993  3814  3814 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:34.993  3814  3814 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:34.993  1020  1033 D SettingsProvider: name = mtp_sync_alive
,03-16 12:20:35.003  3814  3814 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:35.003  3814  3814 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:35.003  1020  1819 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3814 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:35.003  1020  1130 D SettingsProvider: name = sdcard_launch
,03-16 12:20:35.013  1020  1506 D SettingsProvider: name = boot_time_connected
,03-16 12:20:35.023  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:35.023  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 12:20:35.033  3785  3785 D NPS_WSSNPS: [50.150321] smlDBHelper
,03-16 12:20:35.033  1020  1819 D SettingsProvider: name = mtp_open_session
,03-16 12:20:35.033  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.033  1020  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.033  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-16 12:20:35.033  1820  1820 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 12:20:35.033  3785  3822 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-16 12:20:35.033  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 12:20:35.043  3814  3814 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:35.043  3814  3814 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:35.043  3654  3811 I Gmail   : Observing account changes for notifications
,03-16 12:20:35.043  1020  1506 I ActivityManager: Killing 2972:com.sec.usbsettings/1000 (adj 15): empty #31
,03-16 12:20:35.053  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 12:20:35.053  3785  3785 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-16 12:20:35.063  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:35.063  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.063  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.063  3427  3427 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-16 12:20:35.063  3427  3427 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 12:20:35.063  3427  3427 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 12:20:35.063  3427  3427 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-16 12:20:35.063  3427  3427 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-16 12:20:35.063  3427  3427 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-16 12:20:35.063  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 12:20:35.063  1020  1762 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:35.063  1020  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.063  1020  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-16 12:20:35.073  1020  1130 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 12:20:35.073  1346  3136 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-16 12:20:35.073  1346  3136 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-16 12:20:35.083  3785  3833 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
03-16 12:20:35.083  1346  3136 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-16 12:20:35.083  3785  3833 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
,03-16 12:20:35.083  3785  3833 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-16 12:20:35.083  1020  1762 I ActivityManager: Killing 2383:com.android.mms/u0a41 (adj 15): empty #31
,03-16 12:20:35.083  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:35.083  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:35.083  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-16 12:20:35.093  3785  3785 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-16 12:20:35.093  3427  3427 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-16 12:20:35.113  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.113  1020  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.113  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.123  3785  3785 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-16 12:20:35.123  1020  1819 D SettingsProvider: name = access_control_enabled
,03-16 12:20:35.123  3785  3785 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-16 12:20:35.123  3785  3785 I NPS_WSSNPS: [50.150321] smlBREmailDelete
,03-16 12:20:35.123  3785  3785 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
03-16 12:20:35.123  3785  3785 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
03-16 12:20:35.123  3785  3785 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
,03-16 12:20:35.123  3785  3785 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
03-16 12:20:35.123  3785  3785 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
,03-16 12:20:35.133  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:35.133  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:35.133  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:35.133  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:35.133  3785  3785 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-16 12:20:35.133  3654  3837 E Gmail   : Error finding the version of the Email provider.....
03-16 12:20:35.133  3654  3837 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-16 12:20:35.133  3654  3837 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-16 12:20:35.133  3654  3837 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
03-16 12:20:35.133  3654  3837 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-16 12:20:35.133  3654  3837 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 12:20:35.133  3654  3837 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 12:20:35.133  3654  3837 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-16 12:20:35.133  3654  3837 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 12:20:35.133  3654  3837 W EmailMigration: We do not support migrating this version of the Email provider.
,03-16 12:20:35.143  3839  3839 E Zygote  : MountEmulatedStorage()
03-16 12:20:35.143  3839  3839 E Zygote  : v2
03-16 12:20:35.143  3839  3839 I libpersona: KNOX_SDCARD checking this for 10065
03-16 12:20:35.143  3839  3839 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:35.143  3839  3839 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:35.143  1020  1032 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3839 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:20:35.143  3427  3427 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-16 12:20:35.153  3839  3839 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:35.153  3839  3839 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:35.153  3427  3427 I ReactiveServiceManager: Supported : 1
,03-16 12:20:35.153  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.153  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.153  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-16 12:20:35.163  3654  3783 I Gmail   : getAccountsCursor
03-16 12:20:35.163  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.163  1020  3165 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.163  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.163  1020  1543 D CountryDetector: No listener is left
,03-16 12:20:35.163  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2972/cgroup.procs: No such file or directory
,03-16 12:20:35.173  1020  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{39253b69 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:40780
,03-16 12:20:35.173  1020  1542 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-16 12:20:35.173  1020  1542 D QSEECOMAPI: : App is not loaded in QSEE
,03-16 12:20:35.173   257  1100 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-16 12:20:35.173  3785  3785 D NPS_WSSNPS: [50.150321] dsServerSocket close,
,03-16 12:20:35.183  1020  1044 W libprocessgroup: failed to open /acct/uid_10041/pid_2383/cgroup.procs: No such file or directory
,03-16 12:20:35.183  3839  3839 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:35.183  3839  3839 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:35.193  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.193  1020  3165 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.193  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.193  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.193  1020  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.193  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-16 12:20:35.193  1020  1542 D QSEECOMAPI: : Loaded image: APP id = 9
,03-16 12:20:35.203  1020  1020 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,03-16 12:20:35.213  1020  1542 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-16 12:20:35.213  1020  1542 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
03-16 12:20:35.213  1020  1045 I ActivityManager: Killing 3034:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,03-16 12:20:35.213  1020  1542 E terrier : handleString: Failed to handle string(-4)
03-16 12:20:35.213  1020  1542 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-16 12:20:35.213  3427  3427 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-16 12:20:35.213  3427  3427 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-16 12:20:35.213  3427  3427 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 12:20:35.213  3427  3427 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 12:20:35.213  1020  1032 I ActivityManager: Killing 2892:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
03-16 12:20:35.213  3427  3427 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 12:20:35.213  3427  3427 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-16 12:20:35.223  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.223  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.223  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.223  1020  1080 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 12:20:35.233  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:35.233  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:35.233  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:35.233  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:35.253  3858  3858 E Zygote  : MountEmulatedStorage()
,03-16 12:20:35.253  3858  3858 E Zygote  : v2
,03-16 12:20:35.253  3858  3858 I libpersona: KNOX_SDCARD checking this for 10028
03-16 12:20:35.253  3858  3858 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:35.253  3858  3858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:35.253  1020  1032 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3858 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-16 12:20:35.253  1020  1032 I ActivityManager: Killing 3050:com.sec.dsm.system/1000 (adj 15): empty #31
,03-16 12:20:35.253  1020  1542 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.253  1020  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.253  1020  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-16 12:20:35.263  3858  3858 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:35.263  3858  3858 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 12:20:35.263  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:35.263  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:35.263  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:35.263  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:35.283  1725  3864 I GoogleHttpClient: GMS http client unavailable, use old client
03-16 12:20:35.283  3870  3870 E Zygote  : MountEmulatedStorage()
03-16 12:20:35.283  3870  3870 E Zygote  : v2
03-16 12:20:35.283  3870  3870 I libpersona: KNOX_SDCARD checking this for 10102
03-16 12:20:35.283  3870  3870 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:35.283  3870  3870 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:35.283  1020  1033 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3870 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-16 12:20:35.293  3870  3870 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:35.293  1020  1819 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 12:20:35.293  3139  3139 W ScreenOrientationListener: Removing an inexistent observer!
03-16 12:20:35.293  3870  3870 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 12:20:35.293  3654  3654 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@15e2b159 that was originally bound here
03-16 12:20:35.293  3654  3654 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@15e2b159 that was originally bound here
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at com.android.emailcommon.service.H.a(SourceFile:181)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at com.android.emailcommon.service.H.mb(SourceFile:224)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at com.android.email.service.n.j(SourceFile:160)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:171)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at com.android.email.provider.b.F(SourceFile:115)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 12:20:35.293  3654  3654 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 12:20:35.293  1020  1500 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@17af2b33
,03-16 12:20:35.303  3839  3839 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-16 12:20:35.313  3858  3858 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:35.313  3858  3858 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:35.323  3870  3870 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:35.323  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:35.323  3870  3870 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:35.333  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:35.333  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.333  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 12:20:35.333  3139  3139 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1fb5e9d2 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 12:20:35.333  3139  3139 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1fb5e9d2 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 12:20:35.333  3139  3139 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 12:20:35.343  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:35.343  3139  3139 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@31a2ac5d that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 12:20:35.343  3139  3139 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@31a2ac5d that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at com.android.org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:28)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 12:20:35.343  3139  3139 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 12:20:35.353  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:35.353  3254  3310 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 12:20:35.373  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:35.373  1020  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.373  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.383  3870  3870 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 12:20:35.433  1020  1044 W libprocessgroup: failed to open /acct/uid_10043/pid_3034/cgroup.procs: No such file or directory
03-16 12:20:35.433  1020  1044 W libprocessgroup: failed to open /acct/uid_10081/pid_2892/cgroup.procs: No such file or directory
03-16 12:20:35.433  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3050/cgroup.procs: No such file or directory
,03-16 12:20:35.443  1020  1542 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:35.443  1020  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.443  1020  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.453  2584  2584 D FactoryTestApp: [DummyFtClient$onDestroy](2584) Destroy DummyFtClient service
,03-16 12:20:35.453  2584  2584 D FactoryTestApp: [Support$Values.getString](2584) id=MODEL_COMMUNICATION_MODE, value=gsm
03-16 12:20:35.453  2584  2584 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2584) mConnectionMode = gsm
03-16 12:20:35.453  2584  2584 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2584) RUNNING_FTCLIENT : false
,03-16 12:20:35.453  2584  2584 D FactoryTestApp: [DummyFtClient$onDestroy](2584) kill process
03-16 12:20:35.453  2584  2584 I Process : Sending signal. PID: 2584 SIG: 9
,03-16 12:20:35.463  3254  3310 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-16 12:20:35.473  3254  3310 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-16 12:20:35.473  2108  3835 D GCM     : COMPAT: Multi user not supported
,03-16 12:20:35.473  1020  1762 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:35.473  3254  3310 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
03-16 12:20:35.473  1020  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.473  1020  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.473  3254  3310 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-16 12:20:35.473  3654  3848 E SQLiteLog: (283) recovered 59 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 12:20:35.473  3254  3310 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-16 12:20:35.473  3254  3310 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-16 12:20:35.483  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.483  1020  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.483  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 12:20:35.483  3254  3310 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-16 12:20:35.483  1820  1820 D GCM     : COMPAT: Multi user not supported
,03-16 12:20:35.483  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.483  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.483  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.493  1020  1500 I ActivityManager: Process com.sec.factory (pid 2584)(adj 0) has died(39,635)
,03-16 12:20:35.513  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-16 12:20:35.573  3209  3608 I System.out: Thread-465 calls detatch()
,03-16 12:20:35.603  3858  3858 I System.out: Inside onCreate() of WakeupTriggerProvide
,03-16 12:20:35.603  3858  3858 I System.out: Inside WakeupProvider
,03-16 12:20:35.633  2108  3894 I CheckinService: Disabling old GoogleServicesFramework version
,03-16 12:20:35.693  1020  1762 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:35.693  1020  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.693  1020  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.703  1020  1505 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.703  1020  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.703  1020  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.713  3858  3858 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,03-16 12:20:35.713  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.713  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.713  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.723  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.723  1020  3165 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.723  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.723  2108  2108 D SystemUpdateService: onCreate
,03-16 12:20:35.733  2108  3835 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-16 12:20:35.743  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:35.743  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:35.743  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.743  1020  1543 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:35.743  1020  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:35.743  1020  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:35.773  2108  2108 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-16 12:20:35.793  2108  3897 I CheckinService: Checking schedule, now: 1458127235801 next: 1458299986961
03-16 12:20:35.793  2108  3897 I CheckinService: active receiver: disabled
,03-16 12:20:35.793  3654  3848 E File    : fail readDirectory() errno=2
,03-16 12:20:35.803  3654  3890 I Gmail   : notifyAccountChanged
,03-16 12:20:35.813  3858  3858 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,03-16 12:20:35.813  3654  3799 I Gmail   : getAccountsCursor
,03-16 12:20:35.813  3654  3890 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 12:20:35.823  1020  1507 I ActivityManager: Killing 3083:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-16 12:20:35.833  1020  1532 I ActivityManager: Killing 3107:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-16 12:20:35.833  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:35.833  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:35.843  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,03-16 12:20:35.853  3654  3890 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 12:20:35.853  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-16 12:20:35.853  1020  1020 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-16 12:20:35.853  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:35.853  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:35.853  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:35.853  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:35.863  2108  3901 I SystemUpdateService: cancelUpdate (empty URL)
,03-16 12:20:35.863  2108  3901 I SystemUpdateService: active receiver: disabled
,03-16 12:20:35.873  3909  3909 E Zygote  : MountEmulatedStorage()
03-16 12:20:35.873  3909  3909 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:35.873  3909  3909 E Zygote  : v2
03-16 12:20:35.873  3909  3909 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:35.873  3909  3909 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 12:20:35.873  3654  3890 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 12:20:35.873  3654  3890 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-16 12:20:35.873  3909  3909 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 12:20:35.873  3909  3909 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-16 12:20:35.883  1020  1020 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3909 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-16 12:20:35.893  3909  3909 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:35.903  3909  3909 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:35.903  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3083/cgroup.procs: No such file or directory
03-16 12:20:35.903  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3107/cgroup.procs: No such file or directory
,03-16 12:20:36.003  1020  1819 I art     : Explicit concurrent mark sweep GC freed 22522(1134KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 19.898ms total 170.647ms
,03-16 12:20:36.023  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:36.023  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:36.023  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:36.053  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:36.053  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:36.053  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:36.073  3909  3909 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-16 12:20:36.073  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:36.073  1020  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:36.073  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-16 12:20:36.083  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.083  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.083  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.083  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:36.093  1725  1740 I art     : Explicit concurrent mark sweep GC freed 3611(154KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 802us total 87.890ms
03-16 12:20:36.093  3940  3940 E Zygote  : MountEmulatedStorage()
03-16 12:20:36.093  3940  3940 E Zygote  : v2
03-16 12:20:36.093  3940  3940 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:36.093  3940  3940 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:36.093  3940  3940 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:36.103  1725  1742 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-16 12:20:36.103  3940  3940 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:36.103  2108  3935 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-16 12:20:36.103  1020  1500 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3940 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:36.113  3940  3940 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:36.123  3870  3939 I Babel   : MmsConfig: mnc/mcc: 0/0
03-16 12:20:36.123  3870  3939 I Babel   : MmsConfig.loadMmsSettings
,03-16 12:20:36.123  3870  3939 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-16 12:20:36.123  3870  3939 I Babel   : MmsConfig.loadFromDatabase
,03-16 12:20:36.123   306   306 I art     : Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 611us total 22.385ms
,03-16 12:20:36.133  2108  2108 D ChimeraCfgMgr: Reading stored module config
,03-16 12:20:36.133  3940  3940 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:36.133  3940  3940 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:36.143   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 16.727ms
,03-16 12:20:36.163   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 17.032ms,
,03-16 12:20:36.193  2108  3908 I Icing   : Storage manager: low false usage 2.11MB avail 9.95GB capacity 11.63GB
,03-16 12:20:36.233  3940  3940 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-16 12:20:36.283  2108  3935 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-16 12:20:36.293  3870  3889 W art     : Suspending all threads took: 6.207ms
,03-16 12:20:36.323  3870  3937 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 12:20:36.323  3870  3937 W AudioCapabilities: Unsupported mime audio/evrc
,03-16 12:20:36.333  3870  3937 W AudioCapabilities: Unsupported mime audio/qcelp
,03-16 12:20:36.333  3870  3937 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-16 12:20:36.333  3870  3937 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-16 12:20:36.333  3870  3937 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-16 12:20:36.343  3870  3937 W AudioCapabilities: Unsupported mime audio/x-ima
,03-16 12:20:36.343  3870  3939 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,03-16 12:20:36.343  3870  3939 I Babel   : MmsConfig.loadFromResources
,03-16 12:20:36.343  3870  3939 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,03-16 12:20:36.343  3870  3939 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-16 12:20:36.343  3870  3937 W AudioCapabilities: Unsupported mime audio/qcelp
,03-16 12:20:36.343  3870  3937 W AudioCapabilities: Unsupported mime audio/evrc
,03-16 12:20:36.363  3870  3937 W VideoCapabilities: Unsupported mime video/wvc1
,03-16 12:20:36.363  3870  3937 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-16 12:20:36.383  3870  3937 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-16 12:20:36.393  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:36.393  1020  3165 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:36.393  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:36.393  3858  3858 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-16 12:20:36.403  3858  3858 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-16 12:20:36.403  3870  3937 W VideoCapabilities: Unsupported mime video/wvc1
,03-16 12:20:36.403  2108  2126 W art     : Suspending all threads took: 17.316ms
,03-16 12:20:36.403  3870  3937 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-16 12:20:36.423  3940  3940 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-16 12:20:36.423  3870  3937 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-16 12:20:36.423  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:36.423  1020  3165 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 12:20:36.423  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-16 12:20:36.423  3870  3937 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-16 12:20:36.433  3870  3937 W VideoCapabilities: Unsupported mime video/mp43
,03-16 12:20:36.433  3858  3858 D DialogFlow: initQueue()
,03-16 12:20:36.443  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:36.443  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:36.443  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:36.443  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-16 12:20:36.453  2108  2108 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-16 12:20:36.453  2108  2108 D BootCompletedReceiver: Got an BootCompleted event.
,03-16 12:20:36.463  3962  3962 E Zygote  : MountEmulatedStorage()
03-16 12:20:36.463  3962  3962 E Zygote  : v2
03-16 12:20:36.463  3962  3962 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:36.463  3962  3962 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:36.463  3962  3962 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:36.463  1020  1505 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3962 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:36.463  3962  3962 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 12:20:36.463  3962  3962 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:36.463  3940  3940 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-16 12:20:36.463  3940  3940 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-16 12:20:36.483  3870  3937 W VideoCapabilities: Unsupported mime video/sorenson
,03-16 12:20:36.483  3962  3962 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:36.483  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:36.483  1020  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:36.483  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-16 12:20:36.483  3962  3962 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:36.513  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:36.513  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.513  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.513  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:36.513  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-16 12:20:36.523  3870  3937 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-16 12:20:36.533  3980  3980 E Zygote  : MountEmulatedStorage()
03-16 12:20:36.533  3980  3980 E Zygote  : v2
03-16 12:20:36.533  3980  3980 I libpersona: KNOX_SDCARD checking this for 10029
03-16 12:20:36.533  3980  3980 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:36.533  3980  3980 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:36.533  3980  3980 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:36.533  3980  3980 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:36.553  1020  1045 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3980 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,03-16 12:20:36.563  2108  2108 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-16 12:20:36.573  3870  3870 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-16 12:20:36.573  3962  3962 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 12:20:36.583  3940  3940 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
,03-16 12:20:36.583  3940  3940 I F_PHONE : default registerAction()
03-16 12:20:36.583  3940  3940 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-16 12:20:36.583  3980  3980 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:36.583  3980  3980 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:36.623  2108  3935 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 12:20:36.633  3962  3962 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-16 12:20:36.633  3962  3962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-16 12:20:36.643  1020  1500 W ActivityManager: userId = 0, bbcId = -10000,
03-16 12:20:36.643  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:36.643  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-16 12:20:36.663  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:36.663  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:36.663  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:36.683  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.683  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.683  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.683  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:36.683  1478  1478 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 12:20:36.683  1478  1478 D BluetoothBDTestService: onCreate()
,03-16 12:20:36.683  1478  1478 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-16 12:20:36.683  1478  1478 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-16 12:20:36.693  1478  1478 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17,
,03-16 12:20:36.693  3996  3996 E Zygote  : MountEmulatedStorage(),
03-16 12:20:36.693  3996  3996 E Zygote  : v2
03-16 12:20:36.693  3996  3996 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:36.693  3996  3996 I libpersona: KNOX_SDCARD not a persona,
,03-16 12:20:36.703  3996  3996 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-16 12:20:36.703  1020  1505 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3996 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:36.703  1020  1505 I ActivityManager: Killing 3123:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-16 12:20:36.703  3996  3996 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:36.703  3996  3996 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:36.723  3870  3937 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-16 12:20:36.733  3996  3996 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:36.743  3996  3996 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:36.753  3654  3782 I Gmail   : getAccountsCursor
,03-16 12:20:36.773  2108  3935 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-16 12:20:36.783  3996  3996 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 12:20:36.783  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-16 12:20:36.783  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:36.783  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 12:20:36.783  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-16 12:20:36.783  3909  3942 I AMMetaDataParserService: Resource data:2131165186
,03-16 12:20:36.783  2108  2108 D SystemUpdateService: onDestroy
,03-16 12:20:36.793  3909  3942 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-16 12:20:36.793  3909  3942 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 12:20:36.793  3909  3942 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 12:20:36.793  3909  3942 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 12:20:36.833  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3123/cgroup.procs: No such file or directory
,03-16 12:20:36.833  3909  3942 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-16 12:20:36.833  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:36.833  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.833  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.833  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.833  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:36.843  3909  3942 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509,
03-16 12:20:36.843  4021  4021 I libpersona: KNOX_SDCARD checking this for 10030
03-16 12:20:36.843  3870  3870 V Babel   : babel boot account: SMS
03-16 12:20:36.843  4021  4021 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:36.843  4021  4021 E Zygote  : MountEmulatedStorage(),
03-16 12:20:36.843  4021  4021 E Zygote  : v2
03-16 12:20:36.843  3870  3870 V Babel   : babel boot account: thalitester@gmail.com
03-16 12:20:36.843  4021  4021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:36.853  1020  1505 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4021 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-16 12:20:36.853  4021  4021 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:36.853  4021  4021 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,03-16 12:20:36.853  1020  1505 I ActivityManager: Killing 1609:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,03-16 12:20:36.863  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.863  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.863  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:36.863  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:36.883  1020  1505 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4039 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:36.883  4039  4039 E Zygote  : MountEmulatedStorage()
,03-16 12:20:36.883  1020  1505 I ActivityManager: Killing 3154:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
03-16 12:20:36.883  4039  4039 E Zygote  : v2
03-16 12:20:36.883  4039  4039 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:36.883  4039  4039 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:36.883  4039  4039 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:36.883  4021  4021 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:36.883  4021  4021 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:36.883  4039  4039 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:36.883  4039  4039 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:36.903  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:36.903  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:36.903  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:36.903  4039  4039 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:36.903  1020  1532 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 12:20:36.903  4039  4039 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:36.913  3996  3996 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-16 12:20:36.923  1020  1099 V AlarmManager: waitForAlarm result :4
,03-16 12:20:36.923  3909  3942 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-16 12:20:36.933  3996  3996 I KnoxUsageLogPro: premStatus:2
,03-16 12:20:36.933  3996  3996 I KnoxUsageLogPro: isEulaShown : false
03-16 12:20:36.933  3996  3996 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-16 12:20:36.933  3996  4055 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458127236936
,03-16 12:20:36.933  1020  1500 I ActivityManager: Killing 3254:com.policydm/1000 (adj 15): empty #31
,03-16 12:20:36.953  3909  3942 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,03-16 12:20:36.973  1020  1044 W libprocessgroup: failed to open /acct/uid_10068/pid_1609/cgroup.procs: No such file or directory
,03-16 12:20:36.983  2108  3935 I AuthZen : Fetching signing key...
,03-16 12:20:36.983  1020  1099 V AlarmManager: waitForAlarm result :4
,03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-16 12:20:37.013  1020  1044 W libprocessgroup: failed to open /acct/uid_10146/pid_3154/cgroup.procs: No such file or directory
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-16 12:20:37.013  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3254/cgroup.procs: No such file or directory
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.and,roid.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-16 12:20:37.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,03-16 12:20:37.033  1725  1740 I art     : Explicit concurrent mark sweep GC freed 2852(114KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 704us total 27.833ms
,03-16 12:20:37.043  2108  3898 I EventLogService: Aggregate from 1458125246176 (log), 1458125246176 (data)
,03-16 12:20:37.083  3996  4055 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 42542
,03-16 12:20:37.083  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:37.083  1020  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:37.083  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-16 12:20:37.113  3909  3942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-16 12:20:37.123  1820  4061 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-16 12:20:37.133  2108  3935 I AuthZen : Signing key fetched successfully!
,03-16 12:20:37.133   278   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 12:20:37.133   278   995 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-16 12:20:37.133  2108  3935 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 12:20:37.163  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:37.163  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:37.163  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.163  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:37.163  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,03-16 12:20:37.163  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:37.163  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:37.163  3909  3942 I AMMetaDataParserService: Resource data:2131034113
,03-16 12:20:37.173  2108  3935 D a       : Opening database auth.proximity.permit_store...
,03-16 12:20:37.173  3909  3942 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 12:20:37.173  3909  3942 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 12:20:37.173  4065  4065 E Zygote  : MountEmulatedStorage()
03-16 12:20:37.173  3909  3942 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 12:20:37.173  4065  4065 E Zygote  : v2
03-16 12:20:37.173  4065  4065 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:37.173  4065  4065 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:37.173  4065  4065 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:37.173  3909  3942 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-16 12:20:37.183  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
03-16 12:20:37.183  2108  3935 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
03-16 12:20:37.183  4021  4021 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 12:20:37.183  2108  3935 D AuthZenTransactionCache: Clearing transaction cache
03-16 12:20:37.183  4021  4021 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:37.183  4021  4021 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 12:20:37.183  4065  4065 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 12:20:37.183  1020  1819 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4065 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:37.193  4065  4065 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:37.193  1020  1819 I ActivityManager: Killing 3189:com.google.android.configupdater/u0a82 (adj 15): empty #31
,03-16 12:20:37.203  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:37.213  3909  3942 I GFX construct_block_size_descriptor_2d second part: took 2.545312ms for 0*0 texture 0
,03-16 12:20:37.223  4065  4065 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:37.223  4065  4065 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:37.223  3909  3942 I GFX generate_partition_tables: took 6.268179ms for 0*0 texture 0
03-16 12:20:37.223  4021  4021 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 12:20:37.223  4021  4021 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 12:20:37.233  3909  3942 I GFX raster: took 10.129324ms for 96*96 texture 0
03-16 12:20:37.223  4021  4021 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:37.233  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8846c88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88635d8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:37.233  3909  3942 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 12:20:37.243  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:37.243  3909  3942 I GFX raster: took 0.805312ms for 96*96 texture 0
03-16 12:20:37.243  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8846c88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88158a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:37.253  1820  1820 I GCoreUlr: DispatchingService.onCreate()
,03-16 12:20:37.253  4021  4021 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-16 12:20:37.253  4021  4021 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 12:20:37.263  3909  3942 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 12:20:37.273  1020  1044 W libprocessgroup: failed to open /acct/uid_10082/pid_3189/cgroup.procs: No such file or directory
,03-16 12:20:37.313  4065  4065 E KnoxSetupWizardClient: isShipMode : 1
03-16 12:20:37.313  4065  4065 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-16 12:20:37.373  1820  4060 I GCM     : GCM config loaded
,03-16 12:20:37.373  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:37.383  3909  3942 I GFX construct_block_size_descriptor_2d second part: took 2.655365ms for 0*0 texture 0
,03-16 12:20:37.383  3909  3942 I GFX generate_partition_tables: took 7.386354ms for 0*0 texture 0
,03-16 12:20:37.383  3909  3942 I GFX raster: took 10.973229ms for 96*96 texture 0
03-16 12:20:37.383  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88640b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8863dc8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:37.393  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:37.393  4065  4065 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-16 12:20:37.393  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:37.393  3909  3942 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 12:20:37.403  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:37.413  3427  3438 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-16 12:20:37.443  4065  4065 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-16 12:20:37.443  4065  4065 D ShortcutReceiver:  KnoxContainerVersion 2.3.0
03-16 12:20:37.443  4065  4065 D ShortcutReceiver:  shortcut migration not required 
,03-16 12:20:37.443  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.443  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.443  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.443  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:37.453  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:37.453  3909  3942 I GFX raster: took 0.610156ms for 96*96 texture 0
03-16 12:20:37.453  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88635d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88158a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:37.463  4091  4091 E Zygote  : MountEmulatedStorage()
03-16 12:20:37.463  4091  4091 E Zygote  : v2
03-16 12:20:37.463  4091  4091 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:37.463  4091  4091 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:37.463  4091  4091 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:37.463  1020  1032 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4091 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:37.463  1020  1032 I ActivityManager: Killing 3278:com.dropbox.android/u0a88 (adj 15): empty #31
,03-16 12:20:37.463  4091  4091 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:37.463  4065  4080 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-16 12:20:37.463  4091  4091 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:37.473  4065  4080 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
,03-16 12:20:37.483  4065  4080 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-16 12:20:37.483  4065  4080 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-16 12:20:37.483  4065  4080 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-16 12:20:37.483  4065  4080 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-16 12:20:37.483  4065  4080 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-16 12:20:37.483  3909  3942 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 12:20:37.493  1020  3165 I ActivityManager: Killing 3321:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,03-16 12:20:37.493  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:37.493  1820  4085 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-16 12:20:37.493  1020  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:37.493  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:37.503  4091  4091 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:37.503  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 12:20:37.503  4091  4091 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:37.503  3909  3942 I GFX raster: took 0.849739ms for 96*96 texture 0
03-16 12:20:37.503  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8863dc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88158a0 counterpartCT=4 counterpartW=96 counterparth=96,
,03-16 12:20:37.513  3909  3942 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 12:20:37.513  3858  3936 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-16 12:20:37.533  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-16 12:20:37.543  1820  1820 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,03-16 12:20:37.543  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:37.543  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:37.553  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:37.583  4091  4091 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-16 12:20:37.593   288   288 E SMD     : DCD OFF
,03-16 12:20:37.603  4091  4091 I StatusChecker: onReceive : net.mt.init : DONE
,03-16 12:20:37.603  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:37.603  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:37.603  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.603  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:37.613  1020  2733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-16 12:20:37.623  4121  4121 E Zygote  : MountEmulatedStorage(),
03-16 12:20:37.623  4121  4121 I libpersona: KNOX_SDCARD checking this for 10113
03-16 12:20:37.623  4121  4121 E Zygote  : v2
03-16 12:20:37.623  4121  4121 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:37.623  4121  4121 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:37.623  1020  1080 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4121 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,03-16 12:20:37.623  4121  4121 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 12:20:37.623  4121  4121 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:37.623  1020  1080 I ActivityManager: Killing 3379:com.fmm.dm/1000 (adj 15): empty #31
,03-16 12:20:37.643  1020  1044 W libprocessgroup: failed to open /acct/uid_10088/pid_3278/cgroup.procs: No such file or directory
,03-16 12:20:37.653  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:37.653  3909  3942 I GFX raster: took 0.788958ms for 96*96 texture 0
,03-16 12:20:37.653  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88158a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8838268 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:37.663  4121  4121 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:37.663  4121  4121 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:37.663  1820  2139 I art     : Explicit concurrent mark sweep GC freed 26199(1976KB) AllocSpace objects, 40(640KB) LOS objects, 39% free, 9MB/15MB, paused 2.541ms total 154.535ms
,03-16 12:20:37.663  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 12:20:37.673  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:37.693  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:37.693  3909  3942 I GFX raster: took 0.928958ms for 96*96 texture 0
03-16 12:20:37.693  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb884ca60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8845700 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:37.703  4021  4021 I Process : Sending signal. PID: 4021 SIG: 9
,03-16 12:20:37.713  1020  1044 W libprocessgroup: failed to open /acct/uid_10088/pid_3321/cgroup.procs: No such file or directory
03-16 12:20:37.713  3909  3942 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
03-16 12:20:37.713  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3379/cgroup.procs: No such file or directory
,03-16 12:20:37.723  1820  1820 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-16 12:20:37.743  1820  2137 W GCoreFlp: No location to return for getLastLocation()
,03-16 12:20:37.743  1820  1829 W FusedLocationProvider: location=null
,03-16 12:20:37.753  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:37.753  1020  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:37.753  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:37.773  1820  2137 W GCoreFlp: No location to return for getLastLocation()
03-16 12:20:37.773  1820  1830 W FusedLocationProvider: location=null
,03-16 12:20:37.773  4121  4121 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-16 12:20:37.773  1020  1507 I ActivityManager: Process com.sec.android.app.sns3 (pid 4021)(adj 0) has died(34,639)
,03-16 12:20:37.773  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:37.773  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.773  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.773  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:37.783  1020  2733 D SSRM:n  : SIOP:: AP = 420
,03-16 12:20:37.793  4142  4142 E Zygote  : MountEmulatedStorage(),
03-16 12:20:37.793  4142  4142 E Zygote  : v2
03-16 12:20:37.793  4142  4142 I libpersona: KNOX_SDCARD checking this for 10031
,03-16 12:20:37.793  4142  4142 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:37.793  4142  4142 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:37.793  4142  4142 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:37.793  1020  1045 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4142 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,03-16 12:20:37.793  4142  4142 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:37.793  1020  1542 W ActivityManager: userId = 0, bbcId = -10000,
03-16 12:20:37.793  1020  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:37.793  1020  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:37.803  4121  4121 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-16 12:20:37.803  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:37.803  1020  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:37.803  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-16 12:20:37.813  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.813  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.813  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.813  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:37.823  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 12:20:37.823  3909  3942 I GFX raster: took 0.518489ms for 96*96 texture 0
03-16 12:20:37.823  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8838268 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8845700 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:37.823  4142  4142 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:37.823  4121  4121 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-16 12:20:37.823  4142  4142 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:37.833  4157  4157 E Zygote  : MountEmulatedStorage()
03-16 12:20:37.833  4157  4157 E Zygote  : v2
03-16 12:20:37.833  4157  4157 I libpersona: KNOX_SDCARD checking this for 10026
03-16 12:20:37.833  4157  4157 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:37.833  4157  4157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:37.833  1020  1505 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4157 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:20:37.833  4157  4157 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 12:20:37.843  3909  3942 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 12:20:37.843  4157  4157 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 12:20:37.843  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:37.843  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:37.843  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-16 12:20:37.853  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.853  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.853  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:37.853  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:37.853  3366  3499 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 12:20:37.863  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
,03-16 12:20:37.863  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 12:20:37.863  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
,03-16 12:20:37.863  3909  3942 I AMMetaDataParserService: Resource data:2131034113
,03-16 12:20:37.873  4173  4173 E Zygote  : MountEmulatedStorage()
03-16 12:20:37.873  4173  4173 E Zygote  : v2
03-16 12:20:37.873  4173  4173 I libpersona: KNOX_SDCARD checking this for 10121
03-16 12:20:37.873  4173  4173 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:37.873  1020  1505 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4173 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,03-16 12:20:37.873  4173  4173 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:37.873  3909  3942 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-16 12:20:37.873  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:37.873  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 12:20:37.883  4157  4157 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:37.883  4173  4173 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:37.883  4173  4173 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:37.883  3909  3942 I GFX raster: took 1.027605ms for 96*96 texture 0
03-16 12:20:37.883  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8846c88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8845700 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:37.883  4157  4157 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:37.893   306   306 I art     : Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 657us total 23.271ms
,03-16 12:20:37.903  3909  3942 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 12:20:37.903  4173  4173 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:37.913  4173  4173 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:37.913  1820  4085 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-16 12:20:37.913   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 17.083ms
,03-16 12:20:37.933  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 12:20:37.933  3909  3942 I GFX raster: took 1.429271ms for 96*96 texture 0
03-16 12:20:37.933  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8846c88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8845700 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:37.933   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.659ms total 18.346ms
,03-16 12:20:37.933  3858  3884 W art     : Suspending all threads took: 18.299ms
,03-16 12:20:37.943  3909  3942 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 12:20:37.953  4173  4173 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 12:20:37.953  4173  4173 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 12:20:37.953  4173  4173 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 12:20:37.953  2108  3908 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-16 12:20:37.963  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{3ec947f2 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,03-16 12:20:37.963  1820  4085 I GCoreUlr: Unbound from all location providers
03-16 12:20:37.963  1820  4085 I GCoreUlr: Place inference reporting - stopped
,03-16 12:20:37.973  1820  1820 I GCoreUlr: DispatchingService.onDestroy()
,03-16 12:20:37.973  1820  1820 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-16 12:20:37.983  1820  1820 I GCoreUlr: Unbound from all location providers
03-16 12:20:37.983  1820  1820 I GCoreUlr: Place inference reporting - stopped
,03-16 12:20:38.053  3980  4007 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 12:20:38.123  4173  4173 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-16 12:20:38.153  1020  1506 D SettingsProvider: name = scon_is_running
,03-16 12:20:38.153  1020  1506 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 12:20:38.153  1020  1506 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 12:20:38.153  1020  1506 D SettingsProvider: selectionArgs: false
03-16 12:20:38.153  1020  1506 D SettingsProvider: selectionArgs: 10121
03-16 12:20:38.153  1020  1506 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 12:20:38.153  1020  1506 D SettingsProvider: ret = -1
,03-16 12:20:38.153  1020  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:38.153  1020  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:38.153  1020  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:38.153  1020  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:38.163  4194  4194 E Zygote  : MountEmulatedStorage()
,03-16 12:20:38.163  4194  4194 E Zygote  : v2
03-16 12:20:38.163  4194  4194 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:38.163  4194  4194 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:38.163  4194  4194 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:38.173  4194  4194 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 12:20:38.173  1020  1762 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4194 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:38.173  4194  4194 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:38.183  1020  1506 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-16 12:20:38.183  4173  4173 D QuickConnect: Utils.setQCRunningSetting - set : 0
03-16 12:20:38.183  4173  4173 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-16 12:20:38.183  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:38.193  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 12:20:38.193  3909  3942 I GFX raster: took 0.780207ms for 96*96 texture 0
03-16 12:20:38.193  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88640b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84acce0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:38.203  4173  4173 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-16 12:20:38.203  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:38.203  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:38.203  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:38.203  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:38.203  3909  3942 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 12:20:38.213  4194  4194 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:38.213  4194  4194 D ActivityThread: Added TimaKeyStore provider,
,03-16 12:20:38.213  4211  4211 E Zygote  : MountEmulatedStorage()
,03-16 12:20:38.213  4211  4211 E Zygote  : v2
03-16 12:20:38.213  4211  4211 I libpersona: KNOX_SDCARD checking this for 10127
03-16 12:20:38.213  4211  4211 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:38.223  1020  1033 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4211 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-16 12:20:38.223  4211  4211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:38.223  1020  1033 I ActivityManager: Killing 3493:com.fmm.ds/1000 (adj 15): empty #31
,03-16 12:20:38.223  4211  4211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 12:20:38.223  4211  4211 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:38.243  4211  4211 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:38.243  4211  4211 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:38.253  3980  4007 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 12:20:38.253  3980  4007 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 12:20:38.253  3980  4007 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 12:20:38.263  4211  4211 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-16 12:20:38.263  4211  4211 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:38.263  4211  4211 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 12:20:38.263  4211  4211 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 12:20:38.293  4194  4194 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-16 12:20:38.303  4194  4194 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-16 12:20:38.303  4194  4227 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-16 12:20:38.313  4194  4227 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-16 12:20:38.323  4194  4194 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-16 12:20:38.353  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3493/cgroup.procs: No such file or directory
,03-16 12:20:38.353  4194  4194 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-16 12:20:38.353  4194  4194 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-16 12:20:38.363  4194  4227 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init,
03-16 12:20:38.363  4194  4194 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-16 12:20:38.363  4194  4194 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-16 12:20:38.363  4194  4194 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,03-16 12:20:38.373  4194  4194 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-16 12:20:38.373  4194  4194 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-16 12:20:38.373  4194  4194 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-16 12:20:38.373  4194  4194 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-16 12:20:38.383  4194  4194 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-16 12:20:38.383  4194  4194 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,03-16 12:20:38.393  4194  4194 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-16 12:20:38.393  4157  4157 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 12:20:38.393  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:38.393  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:38.393  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:38.393  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:38.413  4234  4234 E Zygote  : MountEmulatedStorage()
,03-16 12:20:38.413  4234  4234 E Zygote  : v2
03-16 12:20:38.413  4234  4234 I libpersona: KNOX_SDCARD checking this for 10032
03-16 12:20:38.413  4234  4234 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:38.413  1020  1542 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4234 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-16 12:20:38.423  4234  4234 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 12:20:38.423  1020  1542 I ActivityManager: Killing 3471:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,03-16 12:20:38.423  4234  4234 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:38.423  4234  4234 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-16 12:20:38.453  4234  4234 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:38.453  4234  4234 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:38.453  4194  4227 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-16 12:20:38.463  4194  4227 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 12:20:38.463  1020  2820 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:20:38.463  4194  4227 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-16 12:20:38.463  4194  4227 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-16 12:20:38.463  4194  4227 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-16 12:20:38.473  4194  4227 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-16 12:20:38.493  4211  4211 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-16 12:20:38.523  4194  4227 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-16 12:20:38.533  4211  4211 D ManifestProvider: onCreate()
,03-16 12:20:38.533  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-16 12:20:38.553  1020  1044 W libprocessgroup: failed to open /acct/uid_10090/pid_3471/cgroup.procs: No such file or directory
,03-16 12:20:38.553  4211  4211 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-16 12:20:38.573  4194  4227 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-16 12:20:38.573  4194  4227 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
03-16 12:20:38.573  4194  4228 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-16 12:20:38.573  4194  4227 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-16 12:20:38.573  4194  4228 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 12:20:38.583  4194  4227 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
,03-16 12:20:38.593  4194  4227 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/16/12:20:38
,03-16 12:20:38.603  4194  4227 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-16 12:20:38.603  4194  4227 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-16 12:20:38.613  4211  4211 W System.err: java.lang.NoSuchMethodException: isEnabled []
03-16 12:20:38.613  4194  4228 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-16 12:20:38.613  4194  4228 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-16 12:20:38.613  4211  4211 W System.err: 	at java.lang.Class.getMethod(Class.java:665)
03-16 12:20:38.613  4211  4211 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
03-16 12:20:38.613  4211  4211 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
03-16 12:20:38.613  4211  4211 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
03-16 12:20:38.613  4211  4211 W System.err: 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
03-16 12:20:38.613  4211  4211 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
03-16 12:20:38.613  4211  4211 W System.err: 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
03-16 12:20:38.613  4211  4211 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-16 12:20:38.613  4211  4211 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-16 12:20:38.613  4211  4211 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-16 12:20:38.613  4211  4211 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 12:20:38.613  4211  4211 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-16 12:20:38.613  4211  4211 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 12:20:38.613  4211  4211 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 12:20:38.613  4211  4211 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 12:20:38.613  4211  4211 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 12:20:38.613  4211  4211 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-16 12:20:38.613  4194  4228 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-16 12:20:38.623  4211  4211 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@2f1b514b
03-16 12:20:38.623  4194  4228 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-16 12:20:38.623  4211  4211 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
,03-16 12:20:38.623  4211  4211 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-16 12:20:38.623  4194  4228 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-16 12:20:38.623  4194  4228 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-16 12:20:38.633  4194  4228 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-16 12:20:38.633  4194  4228 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-16 12:20:38.633  4194  4227 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-16 12:20:38.643  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:38.643  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:38.643  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:38.643  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:38.643  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:38.643  3909  3942 I GFX raster: took 0.668125ms for 96*96 texture 0
,03-16 12:20:38.643  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88635d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8845700 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:38.653  1020  1080 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4259 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-16 12:20:38.653  1020  1080 I ActivityManager: Killing 2701:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,03-16 12:20:38.653  4259  4259 E Zygote  : MountEmulatedStorage()
03-16 12:20:38.653  4259  4259 E Zygote  : v2
03-16 12:20:38.653  4259  4259 I libpersona: KNOX_SDCARD checking this for 10131
03-16 12:20:38.653  4259  4259 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:38.663  4259  4259 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:38.663  4259  4259 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:38.663  4259  4259 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:38.663  3909  3942 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 12:20:38.683  4194  4228 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-16 12:20:38.683  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:38.683  3909  3942 I GFX raster: took 0.999271ms for 96*96 texture 0
03-16 12:20:38.683  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8863dc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84acce0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:38.693  4259  4259 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:38.693  4259  4259 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:38.693  3909  3942 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 12:20:38.713  4234  4274 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
03-16 12:20:38.713  4234  4274 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-16 12:20:38.713  4234  4234 E SPPClientService: [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,03-16 12:20:38.723  4259  4259 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 12:20:38.723  4194  4228 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-16 12:20:38.723  4259  4259 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 12:20:38.723  4259  4259 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 12:20:38.743  1020  1507 I art     : Explicit concurrent mark sweep GC freed 37362(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/36MB, paused 3.563ms total 178.906ms
,03-16 12:20:38.773  4234  4274 D SPPClientService: PushLog.txt file is not deleted.
,03-16 12:20:38.773  4234  4274 D SPPClientService: PushLog.txt file is not deleted.
03-16 12:20:38.773  4234  4274 D SPPClientService: ============PushLog. stop!
,03-16 12:20:38.783  4194  4227 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-16 12:20:38.783  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:38.783  3909  3942 I GFX raster: took 0.669741ms for 96*96 texture 0
03-16 12:20:38.783  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88158a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8845700 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:38.793  4194  4227 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-16 12:20:38.793  1020  1044 W libprocessgroup: failed to open /acct/uid_10117/pid_2701/cgroup.procs: No such file or directory
,03-16 12:20:38.793  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 12:20:38.803  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:38.803  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:38.803  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:38.803  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:38.813  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:38.813  3909  3942 I GFX raster: took 0.696458ms for 96*96 texture 0
,03-16 12:20:38.813  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb884ca60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb84acce0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:38.813  1020  1819 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4284 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 12:20:38.823  4284  4284 E Zygote  : MountEmulatedStorage(),
03-16 12:20:38.823  4284  4284 E Zygote  : v2
03-16 12:20:38.823  4284  4284 I libpersona: KNOX_SDCARD checking this for 10036
03-16 12:20:38.823  4284  4284 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:38.823  4284  4284 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:38.823  1020  1819 I ActivityManager: Killing 3523:com.sec.factory.camera/1000 (adj 15): empty #31
,03-16 12:20:38.823  4284  4284 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:38.823  4284  4284 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-16 12:20:38.833  3909  3942 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 12:20:38.843  4284  4284 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:38.843  4284  4284 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:38.853  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3523/cgroup.procs: No such file or directory
,03-16 12:20:38.933  4284  4284 I SA      : [SSP] onCreated
,03-16 12:20:38.953  4194  4228 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-16 12:20:38.973  4284  4284 I SA      : [TPM] There is no property file
,03-16 12:20:38.973  4284  4284 I SA      : [SCU] isHaveSA() - false
,03-16 12:20:38.973  4284  4284 I SA      : [TPM] getModelProperty : null
,03-16 12:20:38.973  4284  4284 I SA      : [TPM] getCSCProperty : null
,03-16 12:20:38.973  4194  4228 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-16 12:20:38.973  4157  4157 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 12:20:38.973  4284  4284 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-16 12:20:38.973  4284  4284 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-16 12:20:38.973  4284  4284 I SA      : [DM] TFT FEATURE: false
,03-16 12:20:38.983  4284  4284 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
03-16 12:20:38.983  4284  4284 I SA      : [DM] init START
,03-16 12:20:38.983  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 12:20:38.983  4194  4228 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-16 12:20:38.983  3909  3942 I GFX raster: took 0.670833ms for 96*96 texture 0
03-16 12:20:38.983  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8838268 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8845700 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:38.993  4284  4284 I SA      : [DM] This device is not a Vodafone
,03-16 12:20:39.003  3909  3942 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 12:20:39.003  4284  4284 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,03-16 12:20:39.003  4284  4284 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
03-16 12:20:39.003  4284  4284 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,03-16 12:20:39.003  4284  4284 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
03-16 12:20:39.003  4284  4284 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,03-16 12:20:39.003  4284  4284 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
03-16 12:20:39.003  4284  4284 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,03-16 12:20:39.003  4284  4284 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 12:20:39.013  3909 , 3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: Resource data:2131034112
03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-16 12:20:39.013  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
03-16 12:20:39.013  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 12:20:39.013  3909  3942 I GFX raster: took 0.591562ms for 96*96 texture 0
03-16 12:20:39.013  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88635d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8845700 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,03-16 12:20:39.013  4157  4157 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
03-16 12:20:39.013  4157  4157 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,03-16 12:20:39.013  4284  4284 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,03-16 12:20:39.023  3909  3942 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-16 12:20:39.023  4284  4284 I SA      : [SCU] isHaveSA() - false
03-16 12:20:39.023  4284  4284 I SA      : support phone number id : false
03-16 12:20:39.023  4284  4284 I SA      : [DM] Supports Ref Jpn : true
,03-16 12:20:39.023  4284  4284 I SA      : [DM] init END
,03-16 12:20:39.023  4284  4284 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
03-16 12:20:39.023  4284  4284 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-16 12:20:39.023  1020  1543 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:39.023  1020  1543 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-16 12:20:39.023  1020  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-16 12:20:39.033  4284  4284 I SA      : [OR] onReceive END
,03-16 12:20:39.033  1020  3165 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.033  1020  3165 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.033  1020  3165 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.033  1020  3165 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.043  4284  4284 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-16 12:20:39.043  4284  4284 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-16 12:20:39.053  4309  4309 E Zygote  : MountEmulatedStorage()
03-16 12:20:39.053  4309  4309 I libpersona: KNOX_SDCARD checking this for 10037
03-16 12:20:39.053  4309  4309 E Zygote  : v2
03-16 12:20:39.053  4309  4309 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:39.053  4309  4309 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:39.053  4309  4309 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:39.053  4284  4284 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-16 12:20:39.053  4284  4284 I SA      : [LBE] REF_JPN : true
03-16 12:20:39.053  1020  3165 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4309 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 12:20:39.053  4284  4284 I SA      : [BDC] create
03-16 12:20:39.053  4309  4309 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 12:20:39.053  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:39.053  1020  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:39.053  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 12:20:39.063  1686  1707 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 12:20:39.073  4309  4309 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:39.073  4309  4309 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:39.083  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:39.083  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:39.083  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 12:20:39.093  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.093  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.093  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.093  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.093  4284  4284 I SA      : [DBMV2] getEmailID
,03-16 12:20:39.093  4284  4284 I SA      : [DBMV2] getDataV02ForItems
,03-16 12:20:39.093  4284  4284 I SA      : [SSP] query invoked
,03-16 12:20:39.103  4284  4284 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-16 12:20:39.103  4309  4309 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 12:20:39.103  4326  4326 E Zygote  : MountEmulatedStorage()
,03-16 12:20:39.113  4326  4326 E Zygote  : v2
03-16 12:20:39.113  4326  4326 I libpersona: KNOX_SDCARD checking this for 10135
03-16 12:20:39.113  4326  4326 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:39.113  1020  1080 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4326 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-16 12:20:39.123  4326  4326 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:39.123  4326  4326 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:39.123  4326  4326 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:39.123  4284  4284 I SA      : [SCU] get signed id from samsung account1.0 DB.
03-16 12:20:39.123  4157  4279 D Volley  : [618] DiskBasedCache.clear: Cache cleared.
,03-16 12:20:39.133  4284  4284 I SA      : [BDC] destroy
03-16 12:20:39.133  4157  4241 D Volley  : [611] DiskBasedCache.clear: Cache cleared.
,03-16 12:20:39.133  1020  1506 I ActivityManager: Killing 3574:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,03-16 12:20:39.133  1020  1506 I ActivityManager: Killing 3555:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #32
,03-16 12:20:39.133  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:39.133  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:39.133  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-16 12:20:39.143  4157  4333 D Ads     : Skipping gmscore version check
,03-16 12:20:39.143  4326  4326 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:39.153  4157  4157 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-16 12:20:39.153  4326  4326 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:39.153  4157  4157 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 12:20:39.153  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:39.153  3909  3942 I GFX raster: took 0.606302ms for 96*96 texture 0
03-16 12:20:39.153  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88635d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8845700 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:39.163  1020  1099 V AlarmManager: waitForAlarm result :8
,03-16 12:20:39.173  4326  4326 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-16 12:20:39.173  4326  4326 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 12:20:39.173  4326  4326 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 12:20:39.173  4326  4326 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-16 12:20:39.173  4326  4326 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 12:20:39.173  3909  3942 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-16 12:20:39.193  1020  1543 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:39.193  1020  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:39.193  1020  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-16 12:20:39.213  4157  4157 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-16 12:20:39.213  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:39.213  1020  3165 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:39.213  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-16 12:20:39.213  4309  4309 I CalendarProvider2: CalendarProvider2.onCreate() called,
,03-16 12:20:39.263  4157  4157 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 12:20:39.263  1020  1044 W libprocessgroup: failed to open /acct/uid_10055/pid_3555/cgroup.procs: No such file or directory
03-16 12:20:39.263  1020  1044 W libprocessgroup: failed to open /acct/uid_10095/pid_3574/cgroup.procs: No such file or directory
,03-16 12:20:39.273  1020  1506 I ActivityManager: Killing 3301:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,03-16 12:20:39.303  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.303  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.303  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.303  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.313  1020  1500 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4350 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-16 12:20:39.323  4350  4350 E Zygote  : MountEmulatedStorage()
,03-16 12:20:39.323  4350  4350 E Zygote  : v2
03-16 12:20:39.323  4350  4350 I libpersona: KNOX_SDCARD checking this for 10141
,03-16 12:20:39.323  4350  4350 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:39.323  4350  4350 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:39.323  4350  4350 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:39.323  4350  4350 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:39.333  1020  1542 I ActivityManager: Killing 3597:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,03-16 12:20:39.333  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-16 12:20:39.343  3909  3942 I GFX raster: took 0.877397ms for 96*96 texture 0
03-16 12:20:39.343  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8848468 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8845700 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:39.353  4350  4350 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:39.353  4350  4350 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:39.363  3909  3942 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-16 12:20:39.363  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:39.373  3909  3942 I GFX raster: took 1.127552ms for 96*96 texture 0
03-16 12:20:39.373  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88158a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8853658 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:39.373  4350  4350 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 12:20:39.373  4350  4350 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 12:20:39.373  4350  4350 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:39.373  4350  4350 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-16 12:20:39.373  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-16 12:20:39.383  1020  1044 W libprocessgroup: failed to open /acct/uid_10008/pid_3301/cgroup.procs: No such file or directory
,03-16 12:20:39.383  1020  1044 W libprocessgroup: failed to open /acct/uid_10056/pid_3597/cgroup.procs: No such file or directory
,03-16 12:20:39.433  1020  1130 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:39.443  1020  1500 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:39.453  1020  1532 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:39.453  1020  1762 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
,03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
,03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
,03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
,03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
,03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
,03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
,03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
,03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
,03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
,03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-16 12:20:39.463  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
,03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
,03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: Resource data:2131034113
,03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
,03-16 12:20:39.473  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:39.473  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:39.473  3909  3942 I GFX raster: took 0.793802ms for 96*96 texture 0
03-16 12:20:39.473  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8863dc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88640b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:39.483  3909  3942 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 12:20:39.493  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:39.493  3909  3942 I GFX raster: took 0.824063ms for 96*96 texture 0
03-16 12:20:39.493  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8863dc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8846c88 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:39.503  3909  3942 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 12:20:39.513  1020  1500 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:39.513  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.513  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.513  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.513  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.513  1020  1762 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:39.523  4374  4374 E Zygote  : MountEmulatedStorage(),
03-16 12:20:39.523  4374  4374 E Zygote  : v2
03-16 12:20:39.523  4374  4374 I libpersona: KNOX_SDCARD checking this for 10068,
03-16 12:20:39.523  4374  4374 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:39.533  4374  4374 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:39.533  1020  1819 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4374 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,03-16 12:20:39.533  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:39.533  1020  3165 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 12:20:39.533  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-16 12:20:39.533  4374  4374 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:39.533  4374  4374 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-16 12:20:39.533  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-16 12:20:39.543  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.543  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.543  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.543  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.553  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:39.553  3909  3942 I GFX raster: took 0.656093ms for 96*96 texture 0
03-16 12:20:39.553  4390  4390 I libpersona: KNOX_SDCARD checking this for 10142
03-16 12:20:39.553  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb85a0ad0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb884c728 counterpartCT=4 counterpartW=96 counterparth=96
03-16 12:20:39.553  4390  4390 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:39.553  4390  4390 E Zygote  : MountEmulatedStorage()
03-16 12:20:39.553  4390  4390 E Zygote  : v2
03-16 12:20:39.553  4390  4390 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:39.563  1020  1506 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4390 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-16 12:20:39.563  4390  4390 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:39.563  4390  4390 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:39.563  1020  1500 I ActivityManager: Killing 3615:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,03-16 12:20:39.573  3909  3942 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
03-16 12:20:39.573  4374  4374 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:39.573  4374  4374 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:39.593  4390  4390 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:39.593  4390  4390 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:39.603  2108  3908 I Icing   : Internal init done: storage state 0
,03-16 12:20:39.603  1020  1505 I ActivityManager: Killing 3631:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,03-16 12:20:39.613  4390  4390 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 12:20:39.623  2108  3908 I Icing   : Post-init done
,03-16 12:20:39.643  1020  1044 W libprocessgroup: failed to open /acct/uid_10098/pid_3615/cgroup.procs: No such file or directory
,03-16 12:20:39.643  1020  1044 W libprocessgroup: failed to open /acct/uid_10013/pid_3631/cgroup.procs: No such file or directory
,03-16 12:20:39.673  4374  4374 D BadgeProvider: onCreate
03-16 12:20:39.673  4374  4374 D BadgeProvider: DatabaseHelper
03-16 12:20:39.673  1020  1500 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-16 12:20:39.683  1020  1542 W ActivityManager: getTasks: caller 10141 does not hold GET_TASKS; limiting output
,03-16 12:20:39.693  4374  4389 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-16 12:20:39.713  1020  1819 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:39.713  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:39.713  1020  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:39.713  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-16 12:20:39.723  4374  4389 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-16 12:20:39.723  4374  4389 D BadgeProvider: sendNotify, [notify] : null
03-16 12:20:39.723  4374  4389 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-16 12:20:39.723  4374  4389 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 12:20:39.723  4374  4389 D BadgeProvider: update, [UpdateCount] : 1
,03-16 12:20:39.723  1508  1508 D Launcher.Model: reloadBadges entered.
,03-16 12:20:39.723  4350  4385 I Process : Sending signal. PID: 4350 SIG: 9
,03-16 12:20:39.723  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.723  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.723  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.723  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.733  4411  4411 E Zygote  : MountEmulatedStorage()
,03-16 12:20:39.733  4411  4411 E Zygote  : v2
03-16 12:20:39.733  4411  4411 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:39.733  4411  4411 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:39.743  4411  4411 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 12:20:39.743  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:39.743  3909  3942 I GFX raster: took 0.624375ms for 96*96 texture 0,
,03-16 12:20:39.743  1020  1500 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4411 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:39.743  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88640b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8846c88 counterpartCT=4 counterpartW=96 counterparth=96
03-16 12:20:39.743  4411  4411 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:39.743  4411  4411 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:39.753  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:39.753  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:39.753  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:39.763  3909  3942 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 12:20:39.773   306   306 I art     : Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 768us total 27.697ms
,03-16 12:20:39.773  4411  4411 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:39.773  4411  4411 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:39.783  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 12:20:39.783  3909  3942 I GFX raster: took 0.836979ms for 96*96 texture 0
03-16 12:20:39.783  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb884c728 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8846c88 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:39.793   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 685us total 19.691ms
,03-16 12:20:39.793  3909  3942 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 12:20:39.803  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:39.803  1020  3165 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:39.803  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:39.813   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 18.771ms
,03-16 12:20:39.813  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 12:20:39.813  3909  3942 I GFX raster: took 0.635677ms for 96*96 texture 0
03-16 12:20:39.813  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88158a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8846c88 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:39.823  1020  1505 I ActivityManager: Process com.android.email (pid 4350)(adj 9) has died(29,629)
,03-16 12:20:39.823  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 12:20:39.833  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-16 12:20:39.833  3909  3942 I GFX raster: took 0.679271ms for 96*96 texture 0
03-16 12:20:39.833  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8846c88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8848d10 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:39.843  3909  3942 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 12:20:39.853  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:39.853  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:39.853  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:39.873  4309  4309 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-16 12:20:39.873  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.873  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.873  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.873  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.883  1020  1542 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4431 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:39.883  1020  1542 I ActivityManager: Killing 3684:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,03-16 12:20:39.883  4431  4431 E Zygote  : MountEmulatedStorage()
03-16 12:20:39.883  4431  4431 E Zygote  : v2
03-16 12:20:39.883  4431  4431 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:39.883  4431  4431 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:39.883  4431  4431 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:39.893  1020  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.893  1020  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.893  1020  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:39.893  1020  1762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:39.893  4431  4431 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:39.893  4431  4431 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:39.913  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 12:20:39.913  4445  4445 E Zygote  : MountEmulatedStorage()
03-16 12:20:39.913  4445  4445 E Zygote  : v2
03-16 12:20:39.913  4445  4445 I libpersona: KNOX_SDCARD checking this for 10141
03-16 12:20:39.913  4445  4445 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:39.913  4445  4445 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:39.913  3909  3942 I GFX raster: took 0.773334ms for 96*96 texture 0
,03-16 12:20:39.913  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8848d10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8863d28 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 12:20:39.913  4445  4445 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:39.913  4445  4445 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:39.923  4431  4431 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:39.923  4431  4431 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:39.923  1020  1762 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4445 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-16 12:20:39.923  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:39.923  1020  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:39.923  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-16 12:20:39.933  3654  3807 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 12:20:39.943  3909  3942 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 12:20:39.943  4445  4445 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-16 12:20:39.953  3909  3942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 12:20:39.953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-16 12:20:39.,953  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
03-16 12:20:39.953  4445  4445 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:39.963  1020  1532 I ActivityManager: Killing 3717:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.Ac,countSecurity
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:39.963  3909  3942 I AMMetaDataParserService: Resource data:2131165203
,03-16 12:20:39.963  3909  3942 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 12:20:39.973  3909  3942 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 12:20:39.973  3909  3942 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:39.973  3909  3942 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 12:20:39.973  3909  3942 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-16 12:20:39.973  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:39.973  4445  4445 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 12:20:39.973  4445  4445 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 12:20:39.973  4445  4445 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:39.973  4445  4445 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 12:20:39.983  1020  1505 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:39.983  1020  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:39.983  1020  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-16 12:20:40.003  4431  4431 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-16 12:20:40.003  4431  4431 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-16 12:20:40.003  4431  4431 D SecurityLogAgent: StateMachine : Current State = 1
03-16 12:20:40.003  4431  4431 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-16 12:20:40.003  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:40.003  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:40.003  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:40.003  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:40.023  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 12:20:40.023  4468  4468 I libpersona: KNOX_SDCARD checking this for 10148
03-16 12:20:40.023  4468  4468 E Zygote  : MountEmulatedStorage()
03-16 12:20:40.023  4468  4468 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:40.023  4468  4468 E Zygote  : v2
03-16 12:20:40.023  4468  4468 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:40.023  3909  3942 I GFX construct_block_size_descriptor_2d second part: took 4.238750ms for 0*0 texture 0
03-16 12:20:40.023  4468  4468 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:40.023  4468  4468 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:40.033  1020  1032 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4468 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,03-16 12:20:40.033  1020  1032 I ActivityManager: Killing 3408:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,03-16 12:20:40.043  1020  1044 W libprocessgroup: failed to open /acct/uid_10058/pid_3684/cgroup.procs: No such file or directory
,03-16 12:20:40.043  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.043  1020  3165 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.043  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-16 12:20:40.063  3909  3942 I GFX generate_partition_tables: took 17.986563ms for 0*0 texture 0
,03-16 12:20:40.063  3909  3942 I GFX raster: took 22.781979ms for 80*80 texture 0
03-16 12:20:40.063  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8861e80 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb8861350 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 12:20:40.063  4468  4468 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:40.073  4468  4468 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:40.073  3909  3942 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-16 12:20:40.073  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 12:20:40.083  3909  3942 I GFX construct_block_size_descriptor_2d second part: took 2.563437ms for 0*0 texture 0
,03-16 12:20:40.083  3909  3942 I GFX generate_partition_tables: took 5.173907ms for 0*0 texture 0
,03-16 12:20:40.083  3909  3942 I GFX raster: took 8.777968ms for 80*80 texture 0
03-16 12:20:40.083  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8bd7b00 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8bd7cf0 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 12:20:40.093  1020  1500 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:40.093  3909  3942 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-16 12:20:40.103  1020  1044 W libprocessgroup: failed to open /acct/uid_10020/pid_3717/cgroup.procs: No such file or directory
,03-16 12:20:40.103  1020  1044 W libprocessgroup: failed to open /acct/uid_10014/pid_3408/cgroup.procs: No such file or directory
,03-16 12:20:40.113  1020  1033 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:40.113  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 12:20:40.113  3909  3942 I GFX raster: took 0.732135ms for 80*80 texture 0
03-16 12:20:40.113  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8bd7b00 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8bd7cf0 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 12:20:40.123  1020  1542 I ActivityManager: Killing 3741:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-16 12:20:40.133  3909  3942 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-16 12:20:40.133  4468  4468 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-16 12:20:40.143  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.143  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.143  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider,
,03-16 12:20:40.143  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:40.143  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:40.143  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:40.143  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:40.163  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 12:20:40.163  3909  3942 I GFX raster: took 0.719740ms for 80*80 texture 0
,03-16 12:20:40.163  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8bd7b00 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8bd7cf0 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 12:20:40.173  1020  1762 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:40.173  3909  3942 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-16 12:20:40.183  4491  4491 E Zygote  : MountEmulatedStorage(),
03-16 12:20:40.183  4491  4491 E Zygote  : v2
03-16 12:20:40.183  4491  4491 I libpersona: KNOX_SDCARD checking this for 1000,
03-16 12:20:40.183  4491  4491 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:40.183  4491  4491 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:40.183  4491  4491 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:40.183  1020  1032 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4491 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:40.183  4491  4491 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:40.193  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3741/cgroup.procs: No such file or directory
,03-16 12:20:40.193  1020  1080 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:40.193  1020  1080 I ActivityManager: Killing 3760:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-16 12:20:40.203  1020  3165 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 12:20:40.203  1020  3165 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 12:20:40.203  1020  3165 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 12:20:40.203  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 12:20:40.203  1020  1020 I MotionRecognitionService: Plugged
03-16 12:20:40.203  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 12:20:40.203  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 12:20:40.203  1187  1187 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 12:20:40.203  1187  1187 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 12:20:40.213  3909  3942 I GFX raster: took 0.716875ms for 80*80 texture 0
,03-16 12:20:40.213  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8bd7cf0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8d7ac28 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 12:20:40.213  1444  1444 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 12:20:40.213  1444  1444 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 12:20:40.223  3909  3942 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
03-16 12:20:40.223  4491  4491 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:40.223  4491  4491 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:40.233  2613  2613 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 12:20:40.233  2613  2728 D HeadsetStateMachine: Disconnected process message: 10
,03-16 12:20:40.243  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 12:20:40.243  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:20:40.253  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 12:20:40.253  1187  1187 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 12:20:40.253  1187  1187 D SViewCoverView: level :100 plugged : 2
,03-16 12:20:40.263  3909  3942 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 12:20:40.263  3909  3942 I GFX raster: took 0.665261ms for 80*80 texture 0
,03-16 12:20:40.263  3909  3942 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8bd7cf0 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8d7d320 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 12:20:40.273  3909  3942 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-16 12:20:40.283  1020  1099 V AlarmManager: waitForAlarm result :4
,03-16 12:20:40.283  1020  1099 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:40.293  1020  1099 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:40.293  1020  1099 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:40.293  1020  1099 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-16 12:20:40.293  3909  3942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-16 12:20:40.293  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-16 12:20:40.303  1020  1060 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-16 12:20:40.313  4511  4511 E Zygote  : MountEmulatedStorage()
03-16 12:20:40.313  4511  4511 E Zygote  : v2
,03-16 12:20:40.313  4511  4511 I libpersona: KNOX_SDCARD checking this for 10117,
03-16 12:20:40.313  1020  1099 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService: pid=4511 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-16 12:20:40.313  4511  4511 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:40.323  4511  4511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:40.323  1020  1819 W ActivityManager: getTasks: caller 10142 does not hold GET_TASKS; limiting output
,03-16 12:20:40.323  1020  1505 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:40.323  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 12:20:40.323  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700",
03-16 12:20:40.323  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:40.323  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
03-16 12:20:40.323  1020  1506 D RCPManagerService: exchangeData() failure , invalid userId
03-16 12:20:40.323  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
03-16 12:20:40.323  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:40.333  4374  4389 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
03-16 12:20:40.333  4511  4511 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:40.333  4511  4511 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 12:20:40.333  1020  1542 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
03-16 12:20:40.333  1020  1542 I ActivityManager: Killing 3785:com.wssnps/1000 (adj 15): empty #31
,03-16 12:20:40.343  4431  4431 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,03-16 12:20:40.343  4431  4431 D SecurityLogAgent:  SeDenialReceiver : File path = /data/misc/audit/audit.old
03-16 12:20:40.343  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3760/cgroup.procs: No such file or directory
,03-16 12:20:40.353  4390  4427 I Process : Sending signal. PID: 4390 SIG: 9
,03-16 12:20:40.353  4431  4431 D SecurityLogAgent:  SeDenialReceiver : Start file Zipping Service 
,03-16 12:20:40.353  4431  4431 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
,03-16 12:20:40.353  4374  4389 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-16 12:20:40.353  4374  4389 D BadgeProvider: sendNotify, [notify] : null
03-16 12:20:40.353  4374  4389 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-16 12:20:40.353  4374  4389 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 12:20:40.353  4374  4389 D BadgeProvider: update, [UpdateCount] : 1
,03-16 12:20:40.353  1508  1508 D Launcher.Model: reloadBadges entered.
,03-16 12:20:40.353  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.353  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 12:20:40.353  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.securitylogagent, destAppInfo.processName = com.samsung.android.securitylogagent
,03-16 12:20:40.363  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-16 12:20:40.363  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-16 12:20:40.363  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-16 12:20:40.363  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-16 12:20:40.363  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-16 12:20:40.363  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:40.363  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-16 12:20:40.363  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 12:20:40.363  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:40.363  3909  3942 I AMMetaDataParserService: Resource data:2131099648
,03-16 12:20:40.373  3909  3942 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-16 12:20:40.373  3909  3942 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 12:20:40.373  3909  3942 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:40.373  3909  3942 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 12:20:40.373  3909  3942 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-16 12:20:40.373  3909  3942 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 12:20:40.373  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:40.383  3909  3942 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 12:20:40.393  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.393  1020  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.393  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.393  4431  4524 D SecurityLogAgent: FileZippingService : onHandleIntent 
03-16 12:20:40.393  4431  4524 D SecurityLogAgent: FileZippingService : file path =  /data/misc/audit/audit.old
,03-16 12:20:40.403  4431  4524 D SecurityLogAgent: FileZippingService : onPremise disabled. Zipping..  
,03-16 12:20:40.403  4431  4524 D SecurityLogAgent: DenialLogFileZipCreator : createZip
,03-16 12:20:40.403  4431  4524 D SecurityLogAgent: DenialLogFileZipCreator : Not empty 
,03-16 12:20:40.403  4511  4511 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:40.403  4511  4511 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:40.403  4431  4524 D SecurityLogAgent: DenialLogFileZipCreator File existence : true audit.old file size 1333
,03-16 12:20:40.413  1020  1020 W ActivityManager: userId = 0, bbcId = -10000,
03-16 12:20:40.413  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.413  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.413  3909  3942 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 12:20:40.423  4431  4524 D SecurityLogAgent: DenialLogFileZipCreator : denied strings found . Starts zipping . 
03-16 12:20:40.423  4431  4524 D SecurityLogAgent: ProcessFileZipCreator : File name = denialLog
,03-16 12:20:40.423  4431  4524 D SecurityLogAgent: ProcessFileZipCreator : Created temp file 
,03-16 12:20:40.433  4431  4524 D SecurityLogAgent: ProcessFileZipCreator br.readline() has read  12 lines. 
03-16 12:20:40.433  4431  4524 D SecurityLogAgent: ProcessFileZipCreator denialxxx.txt file file existence : true size after copying : 0
,03-16 12:20:40.433  4431  4524 D SecurityLogAgent: ProcessFileZipCreator : Source = /data/data/com.samsung.android.securitylogagent/files/denialLogData/denialLog-1558283057.txt
03-16 12:20:40.433  4431  4524 D SecurityLogAgent: ProcessFileZipCreator : Destination = /data/data/com.samsung.android.securitylogagent/files/denialLogData/denialLog-1558283057.txt.zip
03-16 12:20:40.433  4431  4524 D SecurityLogAgent: ProcessFileZipCreator : File compressed.
03-16 12:20:40.433  4431  4524 D SecurityLogAgent: ProcessFileZipCreatordenialLog-1558283057.txt has been deleted after compression. 
03-16 12:20:40.433  4431  4524 D SecurityLogAgent: FileCipher : getKey Called 
,03-16 12:20:40.433  4511  4511 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 12:20:40.443   254   254 E lowmemorykiller: Error writing /proc/4390/oom_score_adj; errno=22
,03-16 12:20:40.463  1020  3165 I ActivityManager: Process com.android.exchange (pid 4390)(adj 15) has died(28,620)
,03-16 12:20:40.523  3909  3942 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 12:20:40.523  4431  4524 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,03-16 12:20:40.543  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-16 12:20:40.543  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.543  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.543  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-16 12:20:40.553  1745  1745 I Hs20UtilService: Starting #5
,03-16 12:20:40.553  1745  1786 I Hs20UtilService: Message received 5007
,03-16 12:20:40.553  1346  1346 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-16 12:20:40.553  1346  1346 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-16 12:20:40.563  1020  1542 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.563  1020  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.563  1020  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.563  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.563  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.563  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.573  3909  3942 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 12:20:40.573  1020  1762 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.573  1020  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 12:20:40.583  1020  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-16 12:20:40.583  1745  1745 I Hs20UtilService: Starting #6
,03-16 12:20:40.583  1745  1786 I Hs20UtilService: Message received 5007
,03-16 12:20:40.583  1346  1346 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-16 12:20:40.583  1346  1346 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-16 12:20:40.583  1346  1346 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-16 12:20:40.583  1346  1346 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-16 12:20:40.593  1346  1346 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-16 12:20:40.593  1346  1346 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-16 12:20:40.593   288   288 E SMD     : DCD OFF,
,03-16 12:20:40.603  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.603  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 12:20:40.603  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-16 12:20:40.603  1745  1745 I Hs20UtilService: Starting #7
,03-16 12:20:40.603  1745  1786 I Hs20UtilService: Message received 5007
03-16 12:20:40.613  1346  1346 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
03-16 12:20:40.613  1346  1346 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-16 12:20:40.643  4431  4524 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,03-16 12:20:40.653   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1000, gid 1000, pid 4431
03-16 12:20:40.653   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,03-16 12:20:40.653  4431  4524 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
03-16 12:20:40.653  4431  4524 D SecurityLogAgent: FileCipher : Secure Storage Supported 
,03-16 12:20:40.653  1020  1032 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,03-16 12:20:40.653  4431  4524 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,03-16 12:20:40.663  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 12:20:40.663   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1000, gid 1000, pid 4431
03-16 12:20:40.663   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,03-16 12:20:40.663  1020  1500 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
03-16 12:20:40.663  1020  1500 D SecContentProvider2: mCursor = null
,03-16 12:20:40.673  1020  1543 D SecContentProvider2: uri = 15 selection = getToastGravity
03-16 12:20:40.673  1020  1543 D SecContentProvider2: mCursor = null
,03-16 12:20:40.673  1020  1080 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,03-16 12:20:40.673  1020  1080 D SecContentProvider2: mCursor = null
,03-16 12:20:40.673  1020  1542 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
03-16 12:20:40.673  1020  1542 D SecContentProvider2: mCursor = null
,03-16 12:20:40.673  1020  1762 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-16 12:20:40.673  1020  1762 D SecContentProvider2: mCursor = null
,03-16 12:20:40.683  1020  1762 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-16 12:20:40.683  1020  1532 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
03-16 12:20:40.683  1020  1532 D SecContentProvider2: mCursor = null
,03-16 12:20:40.723  3909  3942 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 12:20:40.723  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.723  1020  1080 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.723  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.733  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.733  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.733  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.733  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.733  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.733  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.743  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.743  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.743  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.743  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.743  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.743  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.753  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,03-16 12:20:40.753  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
,03-16 12:20:40.753  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 12:20:40.753  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant,
,03-16 12:20:40.753  3909  3942 I AMMetaDataParserService: Resource data:2131099648
03-16 12:20:40.753  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3785/cgroup.procs: No such file or directory
03-16 12:20:40.753   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,03-16 12:20:40.763  3909  3942 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-16 12:20:40.763  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.763  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 12:20:40.763  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.763  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:40.773  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.773  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.773  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.773  3909  3942 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
03-16 12:20:40.773  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.773  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.773  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.773  1020  3165 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020
,03-16 12:20:40.783  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.783  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.783  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.783  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.783  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.783  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.783  1187  1187 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-16 12:20:40.783  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.783  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.783  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.793  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.793  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.793  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.793  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.793  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.793  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.803  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.803  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.803  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.803  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.803  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:40.803  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:40.803  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.803  1020  1020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:40.803  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:40.813  1020  1080 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-16 12:20:40.813  1020  1080 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-16 12:20:40.813  1020  1080 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-16 12:20:40.813  1020  1080 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-16 12:20:40.813  3909  3942 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 12:20:40.813  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.813  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:40.813  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:40.843  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.843  1020  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:40.843  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-16 12:20:40.863  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.863  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:40.863  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:40.903  1020  1505 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.903  1020  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:40.903  1020  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:40.923  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.923  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:40.923  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:40.943  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:40.943  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:40.943  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:40.943  1820  1820 D WearableService: callingUid 10011, callindPid: 1820
,03-16 12:20:40.953  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.953  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:40.953  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:40.963  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.963  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:40.963  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:40.963  1020  1543 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:40.973  1020  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:40.973  1020  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:40.973  2108  4535 D LocationInitializer: Restart initialization of location
,03-16 12:20:40.983  4309  4309 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-16 12:20:41.003  1820  4534 E MDM     : [237] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 12:20:41.013  3909  3942 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 12:20:41.023  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:41.023  1020  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:41.023  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-16 12:20:41.023  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:41.033  1020  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.033  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.033  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:41.033  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.033  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.053  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:41.053  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.053  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.053  4309  4309 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-16 12:20:41.103  3909  3942 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 12:20:41.173  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 12:20:41.183  3909  3942 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 12:20:41.203  1020  3165 I art     : Explicit concurrent mark sweep GC freed 29623(1715KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 4.928ms total 208.453ms
,03-16 12:20:41.233  1020  1053 D PowerManagerService: [s] UserActivityState : 1 -> 2
,03-16 12:20:41.243  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-16 12:20:41.243  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-16 12:20:41.243  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-16 12:20:41.243  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-16 12:20:41.243  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:41.243  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:41.243  3909  3942 I AMMetaDataParserService: Resource data:2131099648
,03-16 12:20:41.253  3909  3942 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 12:20:41.253  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:41.253  3909  3942 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 12:20:41.263  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:41.263  1020  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.263  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.293  3909  3942 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 12:20:41.303  3909  3942 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 12:20:41.313  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:41.313  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.313  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.323  1478  1488 D TP/SmsProvider: query,matched:0, calling pid = 2108
,03-16 12:20:41.323  1478  1488 D TP/SmsProvider: match 0:Elapsed time : 4.997 ms
,03-16 12:20:41.333  3909  3942 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 12:20:41.333  1020  1762 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:41.333  1020  1762 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.333  1020  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.343  1478  2459 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2108
,03-16 12:20:41.353  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520,
,03-16 12:20:41.363  1478  1488 D TP/SmsProvider: query,matched:0, calling pid = 2108
,03-16 12:20:41.373  1478  1488 D TP/SmsProvider: match 0:Elapsed time : 2.181 ms
,03-16 12:20:41.393  3909  3942 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 12:20:41.393  1478  2459 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2108
,03-16 12:20:41.423  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-16 12:20:41.423  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:41.423  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:41.423  3909  3942 I AMMetaDataParserService: Resource data:2131099648
,03-16 12:20:41.433  3909  3942 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 12:20:41.433  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:41.443  3909  3942 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 12:20:41.463  3909  3942 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 12:20:41.493  3909  3942 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 12:20:41.493   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,03-16 12:20:41.493  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:41.493  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.493  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.503  3909  3942 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522,
,03-16 12:20:41.513  1820  1820 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-16 12:20:41.523  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 12:20:41.533  1820  1820 D a       : Opening database auth.proximity.permit_store...,
,03-16 12:20:41.533  1020  1033 W ActivityManager: userId = 0, bbcId = -10000,
03-16 12:20:41.533  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.533  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.543  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,03-16 12:20:41.543  4431  4524 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,03-16 12:20:41.543  4431  4524 I SecureStorage: [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
03-16 12:20:41.543  4431  4524 D SecurityLogAgent: FileCipher : Got the key bytes 
03-16 12:20:41.543  4431  4524 D SecurityLogAgent: FileCipher : Saving Key to SecureStorage.  
,03-16 12:20:41.553  4431  4524 I SecureStorage: [INFO]: SPID(0x00000002)Processing data
,03-16 12:20:41.553   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1000, gid 1000, pid 4431
03-16 12:20:41.553   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000104
,03-16 12:20:41.563  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:41.563  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.563  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.563  3909  3942 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 12:20:41.563  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-16 12:20:41.563  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:41.563  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
,03-16 12:20:41.573  3909  3942 I AMMetaDataParserService: Resource data:2131099648
,03-16 12:20:41.573  3909  3942 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 12:20:41.573  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:41.573  3909  3942 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 12:20:41.613  2108  4555 W IcingInternalCorpora: getNumBytesRead when not calculated.
,03-16 12:20:41.613  3909  3942 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 12:20:41.623  3909  3942 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 12:20:41.643  3909  3942 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 12:20:41.653  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:41.653  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.653  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.663  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:41.663  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.663  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.673  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 12:20:41.673  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:41.673  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.673  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.683  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:41.683  3909  3942 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 12:20:41.693  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:41.693  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.693  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.703  1020  1506 W ActivityManager: userId = 0, bbcId = -10000,
03-16 12:20:41.703  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:41.703  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:41.713  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList,
03-16 12:20:41.713  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:41.713  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:41.713  3909  3942 I AMMetaDataParserService: Resource data:2131099648
,03-16 12:20:41.713  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:41.713  1020  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:41.713  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:41.713  3909  3942 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 12:20:41.713  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:41.723  1820  2137 W GCoreFlp: No location to return for getLastLocation()
,03-16 12:20:41.723  3909  3942 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 12:20:41.723  1820  4561 W FusedLocationProvider: location=null
,03-16 12:20:41.723  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:41.723  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:41.723  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:41.733  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:41.733  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:41.733  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-16 12:20:41.743  3909  3942 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 12:20:41.753  3909  3942 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 12:20:41.783  3909  3942 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 12:20:41.793  3427  3427 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 12:20:41.793  3427  3427 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 12:20:41.793  3427  3427 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 12:20:41.793  3427  3427 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-16 12:20:41.793  1020  1080 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,03-16 12:20:41.793  1020  1080 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,03-16 12:20:41.793  1478  4572 D SIP     : [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,03-16 12:20:41.803  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 12:20:41.803  1646  1646 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-16 12:20:41.813  1478  4572 E File    : fail readDirectory() errno=2
,03-16 12:20:41.813  3701  3701 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 16 12:20:41 GMT+01:00 2016
,03-16 12:20:41.813  4194  4227 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 12:20:41.813  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:41.813  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:41.813  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:41.813  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:41.833  3909  3942 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
03-16 12:20:41.833  1020  1080 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4575 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:20:41.833  4575  4575 E Zygote  : MountEmulatedStorage()
03-16 12:20:41.833  4575  4575 I libpersona: KNOX_SDCARD checking this for 10108
03-16 12:20:41.833  4575  4575 E Zygote  : v2
03-16 12:20:41.833  4575  4575 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:41.833  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:41.833  1020  1819 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:41.833  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-16 12:20:41.833  4575  4575 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:41.843  4575  4575 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:41.843  4575  4575 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 12:20:41.843  3701  3701 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
,03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings,
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings,
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings,
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings,
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
,03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog,
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-16 12:20:41.853  3909  3942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
,03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-16 12:20:41.843  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-16 12:20:41.853  1686  1707 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 9
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
,03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-16 12:2,0:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-16 12:20:41.853  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
03-16 12:20:41.853  1020  1532 D RCPManagerService: exchangeData() failure , invalid userId
03-16 12:20:41.863  1646  1646 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
03-16 12:20:41.863  1646  1646 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,03-16 12:20:41.863  1646  1646 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-16 12:20:41.863  1646  1646 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-16 12:20:41.873  1020  1542 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 12:20:41.873  3701  3701 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-16 12:20:41.883  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-16 12:20:41.883  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:41.883  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:41.883  3909  3942 I AMMetaDataParserService: Resource data:2131165197
,03-16 12:20:41.883  3701  3701 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-16 12:20:41.883  3909  3942 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 12:20:41.883  3909  3942 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 12:20:41.883  4194  4227 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
03-16 12:20:41.883  3701  3701 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-16 12:20:41.883  4194  4227 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-16 12:20:41.893  3909  3942 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-16 12:20:41.893  3909  3942 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:41.893  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
03-16 12:20:41.893  3909  3942 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 12:20:41.893  3909  3942 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 12:20:41.893  3909  3942 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 12:20:41.893  3909  3942 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 12:20:41.903  4431  4431 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-16 12:20:41.903  4431  4431 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-16 12:20:41.903  4431  4431 D SecurityLogAgent: StateMachine : Current State = 1
03-16 12:20:41.903  4194  4227 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
03-16 12:20:41.903  4431  4431 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-16 12:20:41.903  4194  4227 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-16 12:20:41.903  4575  4575 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:41.903  4194  4227 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-16 12:20:41.903  4575  4575 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:41.903  1646  1646 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-16 12:20:41.903  1646  1646 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-16 12:20:41.903  4194  4227 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-16 12:20:41.903  4194  4227 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-16 12:20:41.913  3701  4583 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-16 12:20:41.913  4194  4194 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,03-16 12:20:41.923  3701  4583 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-16 12:20:41.933  3701  4583 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
03-16 12:20:41.933  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:41.933  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:41.933  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:41.933  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:41.943  4194  4591 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-16 12:20:41.943  4194  4591 I DBG_POLICYDM: [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,03-16 12:20:41.943  3701  4583 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,03-16 12:20:41.953  3701  4583 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
03-16 12:20:41.953  1020  1507 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4594 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 12:20:41.953  3909  3942 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-16 12:20:41.953  4194  4591 E DBG_POLICYDM: [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,03-16 12:20:41.963  4594  4594 E Zygote  : MountEmulatedStorage()
,03-16 12:20:41.963  4594  4594 E Zygote  : v2
03-16 12:20:41.963  4594  4594 I libpersona: KNOX_SDCARD checking this for 10077
03-16 12:20:41.963  4594  4594 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:41.963  4594  4594 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:41.963  4594  4594 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:41.963  4594  4594 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-16 12:20:41.973  3701  4583 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
03-16 12:20:41.973  3909  3942 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-16 12:20:41.983  3701  4583 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,03-16 12:20:41.993  3701  3701 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-16 12:20:41.993  4594  4594 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:41.993  4594  4594 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:41.993  4234  4234 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,03-16 12:20:42.003  4194  4591 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 12:20:42.013  4284  4284 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,03-16 12:20:42.013  4284  4284 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-16 12:20:42.013  4284  4284 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-16 12:20:42.053  4194  4591 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
03-16 12:20:42.053  4194  4591 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-16 12:20:42.063  4194  4591 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-16 12:20:42.063  4194  4591 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-16 12:20:42.063  4194  4591 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-16 12:20:42.063  4194  4591 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-16 12:20:42.063  4194  4591 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-16 12:20:42.063  4194  4591 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-16 12:20:42.073  4194  4591 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-16 12:20:42.073  4194  4591 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,03-16 12:20:42.093  4194  4591 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 12:20:42.093  4194  4591 I DBG_POLICYDM: [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
03-16 12:20:42.103  1020  1819 W ActivityManager: userId = 0, bbcId = -10000,
03-16 12:20:42.103  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:42.103  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-16 12:20:42.323  4284  4284 I SA      : [SLFUCHKMGR] constructor called,
,03-16 12:20:42.333  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
03-16 12:20:42.333  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 12:20:42.333  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:42.333  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:42.333  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 12:20:42.333  4284  4284 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-16 12:20:42.333  4284  4284 I SA      : [OR] == isSIMCardReady false ==
03-16 12:20:42.333  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 12:20:42.413  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:42.413  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:42.413  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:42.413  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:42.433  4614  4614 E Zygote  : MountEmulatedStorage()
03-16 12:20:42.433  4614  4614 E Zygote  : v2
03-16 12:20:42.433  4614  4614 I libpersona: KNOX_SDCARD checking this for 10110
03-16 12:20:42.433  4614  4614 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:42.433  1020  1505 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4614 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 12:20:42.433  4614  4614 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:42.433  4614  4614 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 12:20:42.433  4614  4614 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 12:20:42.453  4614  4614 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:42.453  4614  4614 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:42.453  2108  4628 I iu.SyncManager: SYNC; picasa accounts
,03-16 12:20:42.483   370   370 W SecureStorage: [WARN]: SPID(0x00000003)Trying update data block to DB
,03-16 12:20:42.483  4284  4284 I SA      : [SCU] == networkStateCheck == true,
03-16 12:20:42.483  4284  4284 I SA      : [DM] getCountryCodeFromCSC : PL
03-16 12:20:42.483  4284  4284 I SA      : isChinaCountryCode : false
03-16 12:20:42.483  4284  4284 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-16 12:20:42.483  4284  4284 I SA      : [OR] == networkStateCheck true ==
,03-16 12:20:42.493  2108  2108 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-16 12:20:42.493  2108  2108 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*,
,03-16 12:20:42.493  4284  4284 I SA      : [OR] GetMyCountryZoneTask
03-16 12:20:42.493  4284  4284 I SA      : [OR] onReceive END
,03-16 12:20:42.503  4284  4633 I SA      : [SRS] prepareGetMyCountryZone
,03-16 12:20:42.523  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:42.523  1020  3165 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:42.523  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:42.523  4284  4633 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-16 12:20:42.523  4284  4633 I SA      : [SSP] query invoked
,03-16 12:20:42.533  4284  4633 I SA      : [TPMU] GetMccFromDB : null
,03-16 12:20:42.533  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:42.533  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:42.533  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:42.533  1020  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:42.543  4635  4635 E Zygote  : MountEmulatedStorage()
03-16 12:20:42.543  4635  4635 E Zygote  : v2
,03-16 12:20:42.543  4635  4635 I libpersona: KNOX_SDCARD checking this for 10009
03-16 12:20:42.543  4635  4635 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:42.543  4635  4635 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:42.543  1020  1532 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4635 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-16 12:20:42.553  4635  4635 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 12:20:42.553  4635  4635 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-16 12:20:42.553  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-16 12:20:42.563  4284  4633 I SA      : [SCU] getMccFromPreferece mcc = 260,
03-16 12:20:42.563  4284  4633 I SA      : [TPM] isNoProxy(default) : true
,03-16 12:20:42.563  2108  4628 I iu.UploadsManager: num queued entries: 0
,03-16 12:20:42.563  2108  4628 I iu.UploadsManager: num updated entries: 0
,03-16 12:20:42.563  2108  4628 I iu.SyncManager: NEXT; no task
03-16 12:20:42.563  4575  4575 I MusicStore: Database version: 104
,03-16 12:20:42.573  4635  4635 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:42.573  4635  4635 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:42.613  4284  4633 E File    : fail readDirectory() errno=2,
,03-16 12:20:42.653  1255  1255 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-16 12:20:42.653  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:42.653  1020  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:42.653  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-16 12:20:42.663  1020  1032 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,03-16 12:20:42.663  1020  1032 D SecContentProvider2: mCursor = null
,03-16 12:20:42.783   370   370 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,03-16 12:20:42.793  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:42.793  1020  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:42.793  3909  3942 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-16 12:20:42.793  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 12:20:42.813  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-16 12:20:42.833  4431  4524 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,03-16 12:20:42.833  4431  4524 I SecureStorage: [INFO]: SPID(0x00000003)Skip using SecureStorageExceptionJNI
03-16 12:20:42.833  4431  4524 D SecurityLogAgent: FileCipher : Key loaded. 
,03-16 12:20:42.833  4431  4524 D SecurityLogAgent: ProcessFileZipCreator : source file  :  file existence : true size after compression : 164
03-16 12:20:42.833  4431  4524 D SecurityLogAgent: FileCipher : File ciphering 
03-16 12:20:42.833  4431  4524 D SecurityLogAgent: FileCipher : Source file name = denialLog-1558283057.txt.zip source file size 164
,03-16 12:20:42.843  4431  4524 D SecurityLogAgent: FileCipher : Destination file name = denialLog-150492053.zip dest file Size 176
03-16 12:20:42.843  4431  4524 D SecurityLogAgent: FileCipher : File ciphered successful 
03-16 12:20:42.843  4431  4524 D SecurityLogAgent: ProcessFileZipCreator : source after encryption :  file existence : true file size:176
03-16 12:20:42.843  4431  4524 D SecurityLogAgent: ProcessFileZipCreator : File ciphered 
03-16 12:20:42.843  4431  4524 D SecurityLogAgent: ProcessFileZipCreatordenialLog-1558283057.txt.zip has been deleted after encryption. 
03-16 12:20:42.843  4431  4524 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-16 12:20:42.843  4431  4524 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-16 12:20:42.843  4431  4524 D SecurityLogAgent: StateMachine : Current State = 1
,03-16 12:20:42.843  4431  4524 D SecurityLogAgent: FileZippingService : completed task. Returning wakelock . 
,03-16 12:20:42.843  1020  1819 I ActivityManager: Killing 3814:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,03-16 12:20:42.883  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-16 12:20:42.883  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:42.883  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 12:20:42.883  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:42.883  3909  3942 I AMMetaDataParserService: Resource data:2131165197
,03-16 12:20:42.883  3909  3942 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-16 12:20:42.883  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:42.903  3909  3942 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-16 12:20:42.913  3909  3942 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-16 12:20:42.923  4635  4635 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-16 12:20:42.963  3909  3942 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-16 12:20:42.963  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3814/cgroup.procs: No such file or directory
,03-16 12:20:42.983  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-16 12:20:42.993  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery,
03-16 12:20:42.993  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-16 12:20:42.993  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:42.993  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:42.993  3909  3942 I AMMetaDataParserService: Resource data:2131165197
03-16 12:20:42.993  3909  3942 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-16 12:20:42.993  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
03-16 12:20:43.003  4575  4575 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-16 12:20:43.003  4575  4575 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 12:20:43.003  3909  3942 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-16 12:20:43.023  3909  3942 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-16 12:20:43.033  4575  4575 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 12:20:43.033  4635  4635 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-16 12:20:43.043  1020  1033 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-16 12:20:43.043   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-16 12:20:43.043   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 12:20:43.043  4614  4660 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-16 12:20:43.053   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-16 12:20:43.053   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 12:20:43.053  4614  4660 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-16 12:20:43.063   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-16 12:20:43.063   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 12:20:43.063  4614  4662 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-16 12:20:43.063   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-16 12:20:43.063   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
03-16 12:20:43.063  4614  4662 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-16 12:20:43.083  3909  3942 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-16 12:20:43.093  4575  4575 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-16 12:20:43.093  4575  4575 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e839293: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 12:20:43.093  4575  4575 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-16 12:20:43.093  4575  4575 D AndroidMusic: GMSCore installation verified
,03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-16 12:20:43.123  3909  3942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-16 12:20:43.123  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-16 12:20:43.133  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:43.133  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:43.133  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 12:20:43.143  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-16 12:20:43.143  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 12:20:43.143  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-16 12:20:43.143  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-16 12:20:43.143  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-16 12:20:43.143  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:43.143  3909  3942 I AMMetaDataParserService: Resource data:2131099648
,03-16 12:20:43.143  3909  3942 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-16 12:20:43.143  3909  3942 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 12:20:43.143  3909  3942 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 12:20:43.143  3909  3942 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-16 12:20:43.143  3909  3942 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 12:20:43.143  3909  3942 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-16 12:20:43.143  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:43.153  4575  4575 I ConfigStore: Config Database version: 1
,03-16 12:20:43.183  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:43.183  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:43.183  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-16 12:20:43.213  3909  3942 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-16 12:20:43.213  1020  1345 E Watchdog: !@Sync 1
,03-16 12:20:43.253  1020  1142 D SettingsProvider: name = audio_safe_volume_state
,03-16 12:20:43.263  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:43.263  1020  1032 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-16 12:20:43.263  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-16 12:20:43.273  4635  4635 D hcjo    : AutoUpdateManager:IDLE:execute
,03-16 12:20:43.283  4635  4635 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-16 12:20:43.283  4635  4635 D InitializeManagerStateMachine: exit::IDLE
03-16 12:20:43.283  4635  4635 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-16 12:20:43.283  4635  4635 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
,03-16 12:20:43.283  4635  4635 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-16 12:20:43.283  4635  4635 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-16 12:20:43.283  4635  4635 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-16 12:20:43.283  4635  4635 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-16 12:20:43.283  4635  4635 D InitializeManagerStateMachine: entry::SUCCESS
03-16 12:20:43.283  4635  4635 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-16 12:20:43.283  3909  3942 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-16 12:20:43.293  4635  4635 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,03-16 12:20:43.293   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-16 12:20:43.293   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 12:20:43.293  4575  4575 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-16 12:20:43.303  4635  4635 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
03-16 12:20:43.303  4635  4635 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,03-16 12:20:43.303  4635  4635 D InitializeManagerStateMachine: exit::SUCCESS
03-16 12:20:43.303  4635  4635 D InitializeManagerStateMachine: entry::IDLE
,03-16 12:20:43.313  4614  4614 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-16 12:20:43.313  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-16 12:20:43.313  3909  3942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 12:20:43.313  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-16 12:20:43.313  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-16 12:20:43.313  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,03-16 12:20:43.333  4614  4614 I LibraryLoader: Loading: webviewchromium
,03-16 12:20:43.333  4614  4614 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8943-8947)
03-16 12:20:43.333  4614  4614 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 12:20:43.333  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 12:20:43.343  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 12:20:43.343  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 12:20:43.343  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 12:20:43.343  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 12:20:43.343  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 12:20:43.343   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-16 12:20:43.343   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 12:20:43.343  4575  4575 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-16 12:20:43.353   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-16 12:20:43.353   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 12:20:43.353  4575  4575 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-16 12:20:43.363  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:43.363  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:43.363  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 12:20:43.373  4614  4614 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {163ca285}
,03-16 12:20:43.373  4614  4614 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 12:20:43.373  4614  4614 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 12:20:43.393  1020  1130 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 12:20:43.403  1020  1500 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 12:20:43.403  1020  3165 I AudioService: getStreamVolume 3 index 0
,03-16 12:20:43.403  4575  4575 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-16 12:20:43.413  4614  4614 I BrowserStartupController: Initializing chromium process, renderers=0
,03-16 12:20:43.413  4614  4614 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 12:20:43.413  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-16 12:20:43.413  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.413  3909  3942 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 12:20:43.413  3909  3942 I AMMetaDataParserService: Resource data:2131165220
,03-16 12:20:43.423  3909  3942 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-16 12:20:43.423  3909  3942 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 12:20:43.423  3909  3942 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 12:20:43.423  3909  3942 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 12:20:43.423  3909  3942 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:43.423  3909  3942 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 12:20:43.423  3909  3942 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-16 12:20:43.423  3909  3942 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 12:20:43.433  4575  4575 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 12:20:43.433  3909  3942 I AMMetaDataParserService: Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,03-16 12:20:43.433  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:43.433  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:43.433  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:43.433  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:43.453  4614  4614 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-16 12:20:43.453  4614  4614 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,03-16 12:20:43.453  4614  4614 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
03-16 12:20:43.453  4688  4688 E Zygote  : MountEmulatedStorage()
03-16 12:20:43.453  4688  4688 E Zygote  : v2
,03-16 12:20:43.453  4688  4688 I libpersona: KNOX_SDCARD checking this for 10001
03-16 12:20:43.453  4688  4688 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:43.453  3909  3942 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
03-16 12:20:43.453  4688  4688 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:43.463  1020  1020 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4688 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:20:43.463  4688  4688 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:43.463  1020  2820 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:20:43.463  4688  4688 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.,settings.wifi.WifiSecSetupActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
,03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
,03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings,
,03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  1020  1507 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Reso,urce data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PAR,ENT_FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.473  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.513  1020  1506 I ActivityManager: Killing 3654:com.google.android.gm/u0a99 (adj 15): empty #31
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.523  1020  1500 I ActivityManager: Killing 3839:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:L,oop for running activitycom.android.settings.notification.RedactionInterstitial
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909,  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.483  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-16 12:20:43.493  4688  4688 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  4688  4688 D ActivityThread: Added TimaKeyStore provider
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.set,tings.Settings$CloudSettingActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.493  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-16 12:20:43.503  4575  4575 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resourc,e data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-16 12:20:43.503  3909  3942 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-16 12:20:43.523  4614  4614 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 12:20:43.523  4614  4614 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 12:20:43.523  4614  4614 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 12:20:43.523  4614  4614 I Adreno-EGL: Local Branch: 
03-16 12:20:43.523  4614  4614 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 12:20:43.523  4614  4614 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 12:20:43.523  4614  4614 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-16 12:20:43.523  4614  4687 W AudioManagerAndroid: Requires BLUETOOTH permission
03-16 12:20:43.553  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
03-16 12:20:43.603   288   288 E SMD     : DCD OFF
,03-16 12:20:43.613  4614  4614 I NSApplication: Starting up...
,03-16 12:20:43.623  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:43.623  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:43.623  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:43.623  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:43.633  4718  4718 E Zygote  : MountEmulatedStorage(),
03-16 12:20:43.643  4718  4718 E Zygote  : v2
,03-16 12:20:43.643  4718  4718 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:43.643  4718  4718 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:43.643  4718  4718 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:43.643  4718  4718 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:43.643  4718  4718 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-16 12:20:43.643  1020  1542 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4718 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 12:20:43.643  1020  1542 I ActivityManager: Killing 3139:com.test.thalitest/u0a167 (adj 15): empty #31,
03-16 12:20:43.643  1020  1044 W libprocessgroup: failed to open /acct/uid_10065/pid_3839/cgroup.procs: No such file or directory
,03-16 12:20:43.653  1020  1044 W libprocessgroup: failed to open /acct/uid_10099/pid_3654/cgroup.procs: No such file or directory
,03-16 12:20:43.663   306   306 I art     : Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 743us total 24.905ms
,03-16 12:20:43.683  1020  1505 I ActivityManager: Killing 3909:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-16 12:20:43.683  1020  1505 I ActivityManager: Killing 3870:com.google.android.talk/u0a102 (adj 15): empty #32
,03-16 12:20:43.683   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 20.051ms
,03-16 12:20:43.693  1020  1507 I art     : Explicit concurrent mark sweep GC freed 20498(1230KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 2.633ms total 146.371ms
,03-16 12:20:43.703   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 17.783ms
,03-16 12:20:43.713  4718  4718 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:43.713  4718  4718 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:43.743  4173  4173 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-16 12:20:43.743  4173  4173 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
03-16 12:20:43.743  4173  4173 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-16 12:20:43.783  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3909/cgroup.procs: No such file or directory
03-16 12:20:43.783  1020  1044 W libprocessgroup: failed to open /acct/uid_10167/pid_3139/cgroup.procs: No such file or directory
03-16 12:20:43.783  1020  1044 W libprocessgroup: failed to open /acct/uid_10102/pid_3870/cgroup.procs: No such file or directory
,03-16 12:20:43.813  4718  4718 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-16 12:20:43.963  4718  4718 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-16 12:20:43.973  4718  4718 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-16 12:20:43.973  4718  4718 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-16 12:20:43.973  4718  4718 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-16 12:20:43.973  4718  4718 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-16 12:20:43.973  4718  4718 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-16 12:20:44.043  4194  4202 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 12:20:44.053  4194  4202 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 12:20:44.053  4194  4202 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-16 12:20:44.053  4194  4204 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 12:20:44.053  4194  4204 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 12:20:44.053  4194  4204 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true,
,03-16 12:20:44.063  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.063  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.063  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.063  1020  1819 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.073  4736  4736 E Zygote  : MountEmulatedStorage()
,03-16 12:20:44.073  4736  4736 E Zygote  : v2
03-16 12:20:44.073  4736  4736 I libpersona: KNOX_SDCARD checking this for 10008
,03-16 12:20:44.073  4736  4736 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:44.083  4736  4736 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:44.083  1020  1819 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4736 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:20:44.083  4736  4736 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 12:20:44.083  4736  4736 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 12:20:44.113  4736  4736 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:44.113  4736  4736 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:44.203  1020  1507 I ActivityManager: Killing 3962:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-16 12:20:44.213  4736  4736 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-16 12:20:44.223  1020  1543 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1020) eventTime = 49837
03-16 12:20:44.223  1020  1543 D PowerManagerService: [s] UserActivityState : 2 -> 1
03-16 12:20:44.223  1020  1543 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020 (0x0)
03-16 12:20:44.223  4736  4736 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-16 12:20:44.233  1020  1543 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1020, ws=WorkSource{10049}) (elapsedTime=3452)
03-16 12:20:44.233  4284  4633 I SA      : [RC New] Execute method=[GET] start
,03-16 12:20:44.233  4736  4736 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-16 12:20:44.233  4736  4736 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-16 12:20:44.233  1020  1032 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,03-16 12:20:44.233  1020  1032 I ActivityManager: Killing 3858:com.vlingo.midas/u0a28 (adj 15): empty #31
,03-16 12:20:44.243  1020  1020 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,03-16 12:20:44.243  1020  1020 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-16 12:20:44.243  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.243  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.243  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.243  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.253  4753  4753 E Zygote  : MountEmulatedStorage()
,03-16 12:20:44.253  4753  4753 E Zygote  : v2
03-16 12:20:44.253  4753  4753 I libpersona: KNOX_SDCARD checking this for 10058
03-16 12:20:44.253  4753  4753 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:44.253  4753  4753 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:44.263  4753  4753 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:44.263  4753  4753 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-16 12:20:44.263  1020  1045 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4753 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 12:20:44.263  2935  4348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-16 12:20:44.273  4284  4633 I SA      : [RC New] Security=[true]
,03-16 12:20:44.273  4284  4633 I System.out: Thread-640(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
03-16 12:20:44.273  4284  4633 I System.out: Thread-640(ApacheHTTPLog):isSBSettingEnabled false
03-16 12:20:44.273  4284  4633 I System.out: Thread-640(ApacheHTTPLog):isShipBuild true
03-16 12:20:44.273  4284  4633 I System.out: Thread-640(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-16 12:20:44.273  4284  4633 I System.out: Thread-640(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-16 12:20:44.273   278   995 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
03-16 12:20:44.273   278   995 D Netd    : getNetworkForDns: using netid 502 for uid 10036
,03-16 12:20:44.283  4736  4736 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-16 12:20:44.283  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:44.283  1020  1819 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:44.283  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 12:20:44.283  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-16 12:20:44.283  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-16 12:20:44.283  1686  1686 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 12:20:44.293  1686  1686 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-16 12:20:44.293  3173  3173 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,03-16 12:20:44.293  3173  3173 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,03-16 12:20:44.303  3173  3173 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,03-16 12:20:44.303  1686  1686 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-16 12:20:44.303  2935  2935 I Process : Sending signal. PID: 2935 SIG: 9
,03-16 12:20:44.303  4753  4753 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:44.303  4753  4753 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:44.303  4736  4736 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-16 12:20:44.313  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:44.313  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-16 12:20:44.313  1686  1686 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
03-16 12:20:44.313  1020  3165 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:44.313  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 12:20:44.313  1686  1686 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-16 12:20:44.313  1686  1686 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-16 12:20:44.313  1686  1686 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-16 12:20:44.313  1686  1686 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-16 12:20:44.313  1686  1686 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-16 12:20:44.313  1686  1686 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-16 12:20:44.313  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-16 12:20:44.323  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-16 12:20:44.323  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-16 12:20:44.323  1686  1686 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-16 12:20:44.323  1686  1686 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-16 12:20:44.323  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3962/cgroup.procs: No such file or directory
03-16 12:20:44.323  1020  1044 W libprocessgroup: failed to open /acct/uid_10028/pid_3858/cgroup.procs: No such file or directory
,03-16 12:20:44.333  1686  1686 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-16 12:20:44.333  3701  3701 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Wed Mar 16 12:20:44 GMT+01:00 2016
,03-16 12:20:44.333  1020  1505 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:44.333  1020  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:44.333  1020  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-16 12:20:44.333  4431  4431 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-16 12:20:44.333  4431  4431 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,03-16 12:20:44.343  4431  4431 D SecurityLogAgent: StateMachine : Current State = 1
,03-16 12:20:44.343  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 12:20:44.343  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 12:20:44.343  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 12:20:44.343  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:44.343  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 12:20:44.343  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 12:20:44.353  3701  3701 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-16 12:20:44.353  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.353  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.353  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.353  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.353  1686  1686 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,03-16 12:20:44.353  1686  1686 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-16 12:20:44.363  3701  3701 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
03-16 12:20:44.363  3701  3701 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-16 12:20:44.363  3701  3701 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-16 12:20:44.373  3701  4772 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-16 12:20:44.373  3701  4772 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,03-16 12:20:44.373  4774  4774 E Zygote  : MountEmulatedStorage()
03-16 12:20:44.373  4774  4774 E Zygote  : v2
03-16 12:20:44.373  4774  4774 I libpersona: KNOX_SDCARD checking this for 10153
03-16 12:20:44.373  4774  4774 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:44.383  4774  4774 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:44.383  4774  4774 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:44.383  4753  4753 I ExternalOEMControlProvider: onCreate
03-16 12:20:44.383  1020  1500 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4774 uid=10153 gids={50153, 9997} abi=armeabi-v7a
03-16 12:20:44.383  4774  4774 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:44.383  3701  4772 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Wed Mar 16 12:20:44 GMT+01:00 2016
,03-16 12:20:44.383  1020  1505 I ActivityManager: Process com.sec.android.app.sysscope (pid 2935)(adj 0) has died(93,590),
,03-16 12:20:44.393  3701  4772 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,03-16 12:20:44.393  4284  4284 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,03-16 12:20:44.403  3701  3701 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-16 12:20:44.403  1646  1646 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-16 12:20:44.413  1646  1646 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-16 12:20:44.413  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:44.413  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:44.413  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:44.413  4774  4774 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:44.413  4774  4774 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:44.423  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.423  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.423  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.423  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.423  4753  4783 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-16 12:20:44.433  4790  4790 E Zygote  : MountEmulatedStorage()
03-16 12:20:44.433  4790  4790 E Zygote  : v2
03-16 12:20:44.433  4790  4790 I libpersona: KNOX_SDCARD checking this for 10081
03-16 12:20:44.433  4790  4790 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:44.433  4790  4790 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:44.433  4790  4790 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:44.443  4790  4790 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:44.443  1020  1500 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4790 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 12:20:44.463  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.463  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.463  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.463  1020  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.473  4790  4790 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:44.473  4790  4790 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:44.473  4774  4774 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:44.473  4805  4805 E Zygote  : MountEmulatedStorage()
03-16 12:20:44.473  4805  4805 E Zygote  : v2
03-16 12:20:44.473  4805  4805 I libpersona: KNOX_SDCARD checking this for 10041
03-16 12:20:44.473  4805  4805 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:44.473  4805  4805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:44.483  4805  4805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:44.483  1020  1500 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4805 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
03-16 12:20:44.483  4805  4805 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 12:20:44.503  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.503  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.503  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.503  1020  1507 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.513  4790  4790 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-16 12:20:44.513  4790  4790 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 12:20:44.513  4790  4790 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 12:20:44.513  4790  4790 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:44.513  4790  4790 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.,
,03-16 12:20:44.513  4820  4820 E Zygote  : MountEmulatedStorage(),
03-16 12:20:44.513  4820  4820 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:44.513  4820  4820 E Zygote  : v2
03-16 12:20:44.513  4820  4820 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:44.513  4820  4820 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:44.523  4820  4820 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 12:20:44.523  4820  4820 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:44.523  1020  1507 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4820 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:44.533  4805  4805 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:44.533  4805  4805 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:44.533  1020  1507 I ActivityManager: Killing 3996:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-16 12:20:44.543  1020  3165 I ActivityManager: Killing 4039:com.samsung.helphub/1000 (adj 15): empty #31
,03-16 12:20:44.553  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:44.553  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:44.553  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:44.553  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,03-16 12:20:44.563  3173  3284 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-16 12:20:44.563  4805  4805 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-16 12:20:44.563  4805  4805 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 12:20:44.563  4805  4805 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:44.563  4805  4805 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-16 12:20:44.563  4805  4805 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 12:20:44.563  4820  4820 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:44.563  4820  4820 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:44.563  3173  3284 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-16 12:20:44.623  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{14a002e1 u0 com.samsung.android.providers.context/.ContextService}
,03-16 12:20:44.653  3173  3284 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,03-16 12:20:44.653  4820  4820 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458127244658
03-16 12:20:44.653  4820  4820 D         : TimeServiceNative: User Time to be set is 1458127244658
03-16 12:20:44.653  4820  4820 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-16 12:20:44.653  4820  4820 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-16 12:20:44.653  4820  4820 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458127244658
,03-16 12:20:44.653  4820  4820 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-16 12:20:44.653   317   562 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-16 12:20:44.653   317  4836 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458127244658
,03-16 12:20:44.653   317  4836 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458127244658, operation = 0
,03-16 12:20:44.653   317  4836 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/11/70 14:57:23
,03-16 12:20:44.653   317  4836 D QC-time-services: Daemon:Value read from RTC seconds = 21913043000
03-16 12:20:44.653   317  4836 D QC-time-services: Daemon:new time 1458127244658 
03-16 12:20:44.653   317  4836 D QC-time-services: Daemon: delta 1436214201658 genoff 1436214201658 
03-16 12:20:44.653   317  4836 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214201658 to memory
03-16 12:20:44.653   317  4836 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-16 12:20:44.653   317  4836 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-16 12:20:44.663  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3996/cgroup.procs: No such file or directory
,03-16 12:20:44.673  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4039/cgroup.procs: No such file or directory
,03-16 12:20:44.683  3173  3284 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-16 12:20:44.693  1020  1506 D SettingsProvider: name = next_alarm_formatted
,03-16 12:20:44.693  1020  1506 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-16 12:20:44.693  1020  1506 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 12:20:44.693  1020  1506 D SettingsProvider: selectionArgs: false
,03-16 12:20:44.693  1020  1506 D SettingsProvider: selectionArgs: 10081
03-16 12:20:44.693  1020  1506 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-16 12:20:44.693  1020  1506 D SettingsProvider: ret = -1
,03-16 12:20:44.703  4805  4805 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,03-16 12:20:44.713  3173  3284 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-16 12:20:44.723  3173  3284 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,03-16 12:20:44.723   317  4836 D QC-time-services: Updating the TOD offset
03-16 12:20:44.723   317  4836 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214201658 to memory
03-16 12:20:44.723   317  4836 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-16 12:20:44.723   317  4836 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-16 12:20:44.723  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,03-16 12:20:44.723   317  4836 E QC-time-services: Daemon:Update to modem bit set
03-16 12:20:44.723   317  4836 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-16 12:20:44.723   317  4836 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120249401658
,03-16 12:20:44.723  4820  4820 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-16 12:20:44.733   317   559 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-16 12:20:44.733   317   562 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-16 12:20:44.733  3173  3284 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,03-16 12:20:44.743  3173  3284 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,03-16 12:20:44.743  3173  3285 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,03-16 12:20:44.753  3173  3284 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,03-16 12:20:44.753  3173  3285 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,03-16 12:20:44.763  3173  3284 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-16 12:20:44.763  3173  3284 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,03-16 12:20:44.763   257  1100 I SurfaceFlinger: id=13 Removed Uoast (8/8)
,03-16 12:20:44.763   257   445 I SurfaceFlinger: id=13 Removed Uoast (-2/8)
,03-16 12:20:44.773  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{f168e89 u0 com.android.settings/.wifi.WifiCredService}
,03-16 12:20:44.773  1020  1033 I ActivityManager: Killing 4065:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-16 12:20:44.783  3173  3285 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:362673799
,03-16 12:20:44.793  3173  3285 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,03-16 12:20:44.803  3173  3285 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,03-16 12:20:44.813  3173  3285 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,03-16 12:20:44.823  3173  3285 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,03-16 12:20:44.833  4805  4805 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 114.342ms
,03-16 12:20:44.833  3173  3285 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 705624899
03-16 12:20:44.833  4790  4790 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 118.040ms
,03-16 12:20:44.833  3173  3173 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,03-16 12:20:44.843  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4065/cgroup.procs: No such file or directory
,03-16 12:20:44.843  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-16 12:20:44.843  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,03-16 12:20:44.863  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,03-16 12:20:44.863  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,03-16 12:20:44.863  3173  3285 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,03-16 12:20:44.863  3173  3173 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,03-16 12:20:44.863  3173  3173 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@3b75bdce
,03-16 12:20:44.873  3173  3285 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-16 12:20:44.873  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(755/lllllIIlIIIlIlIIIllI)] UI_id:223
,03-16 12:20:44.883  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.883  3173  3173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 com.wssyncmldm.llIIllllIIlllIIIIlll.handleMessage:1090 
03-16 12:20:44.883  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.883  3173  3173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 
,03-16 12:20:44.883  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:44.883  1020  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:44.883  3173  3173 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:50493,
,03-16 12:20:44.883  1020  1542 E PersonaManagerService: inState():  stateMachine is null !!
03-16 12:20:44.883  1020  1542 I PersonaManagerService: PersonaId don't exist
03-16 12:20:44.883  1020  1542 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-16 12:20:44.893  4837  4837 E Zygote  : MountEmulatedStorage()
03-16 12:20:44.893  4837  4837 I libpersona: KNOX_SDCARD checking this for 10090
03-16 12:20:44.893  4837  4837 E Zygote  : v2
,03-16 12:20:44.893  4837  4837 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:44.893  4837  4837 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:44.893  1020  1080 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4837 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,03-16 12:20:44.903  4837  4837 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:44.903  4837  4837 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 12:20:44.903  1020  1080 I ActivityManager: Killing 4091:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-16 12:20:44.903  1020  1542 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-16 12:20:44.903  1020  1542 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:44.903  1020  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:44.903  1020  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-16 12:20:44.903  1020  1542 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 12:20:44.913  1020  1542 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-16 12:20:44.913  1020  1542 W ActivityManager: mDVFSHelper.acquire()
,03-16 12:20:44.913  1020  1542 D FocusedStackFrame: Set to : 0,
,03-16 12:20:44.923  1508  1508 D Launcher.HomeView: onPause
,03-16 12:20:44.923  1020  1542 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 12:20:44.923  1020  1542 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-16 12:20:44.923  1020  1542 D InputDispatcher: Focused application set to: xxxx
03-16 12:20:44.923  1020  1542 D InputDispatcher: Focus left window: 1508
03-16 12:20:44.923  1508  1508 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-16 12:20:44.923  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 12:20:44.923  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 12:20:44.923  4805  4853 D Mms/ArtClassLoader: init before art
,03-16 12:20:44.923  4837  4837 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:44.923  4805  4805 D Mms/TelephonyPermission: start operation mode monitor
03-16 12:20:44.923  4837  4837 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:44.933  1020  1099 V AlarmManager: waitForAlarm result :4
,03-16 12:20:44.943  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-16 12:20:44.943  1020  1020 D SensorService: [SO] activate (ident=0xb8dec3b8, enabled=0)
03-16 12:20:44.943  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-16 12:20:44.963  4805  4805 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 12:20:44.963  1020  1020 D SensorManager: unregisterListener ::   
,03-16 12:20:44.963  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-16 12:20:44.973  1020  1020 D SensorService: [SO] changed settle time [1]
03-16 12:20:44.973  1020  1020 D SensorService: [SO] setDelay [66000000]
03-16 12:20:44.973  1020  1020 D SensorService: [SO] activate (ident=0xb8e3d390, enabled=1)
03-16 12:20:44.973  1020  1020 D SensorService: [SO] AR_init
03-16 12:20:44.973  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-16 12:20:44.973  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-16 12:20:44.983  4805  4805 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-16 12:20:44.983  4805  4805 D Mms/TelephonyPermission: isDefault true
,03-16 12:20:44.993  4805  4805 D Mms/MmsApp: onCreate() com.android.mms
,03-16 12:20:44.993  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4091/cgroup.procs: No such file or directory
,03-16 12:20:44.993  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2153/onResume)] 
,03-16 12:20:44.993  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2195/lllIlIlIIIllIIlIllIl)] id 223
,03-16 12:20:45.003  1020  1542 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.003  1020  1542 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,03-16 12:20:45.003  1020  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-16 12:20:45.013  4837  4837 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver },
03-16 12:20:45.013  4837  4837 D elm:15121: ELMEngine.ELMEngine( context ).
,03-16 12:20:45.023  4837  4837 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-16 12:20:45.023  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.023  1020  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.023  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-16 12:20:45.023  4837  4837 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-16 12:20:45.023  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:45.023  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:45.023  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:45.023  1020  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:45.033  4837  4837 D elm:15121: ElmAgentService : onCreate()
,03-16 12:20:45.033  4837  4856 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,03-16 12:20:45.033  4837  4856 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
03-16 12:20:45.033  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-16 12:20:45.033  4837  4837 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
03-16 12:20:45.033  4837  4837 D elm:15121: ModuleBase.ModifySetAlarm()
03-16 12:20:45.033  4837  4837 D elm:15121: MDMBridge.getInstance()
03-16 12:20:45.033  4837  4837 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-16 12:20:45.043  1020  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-16 12:20:45.043  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-16 12:20:45.043  4860  4860 E Zygote  : MountEmulatedStorage()
,03-16 12:20:45.043  4860  4860 E Zygote  : v2
03-16 12:20:45.043  4860  4860 I libpersona: KNOX_SDCARD checking this for 10130
03-16 12:20:45.043  4860  4860 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:45.053  4860  4860 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:45.053  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-16 12:20:45.053  4860  4860 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 12:20:45.053  1020  1505 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4860 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,03-16 12:20:45.053  4860  4860 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-16 12:20:45.053  4837  4837 D elm:15121: ElmAgentService : onDestroy().
03-16 12:20:45.053  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-16 12:20:45.063  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
03-16 12:20:45.063  4805  4805 D Mms/MmsApp: [start]    initCountryIso consume time = 357.200989
,03-16 12:20:45.063  3173  3173 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:50672
03-16 12:20:45.063  1020  1507 I ActivityManager: Killing 4211:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
03-16 12:20:45.063  1020  1762 E PersonaManagerService: inState():  stateMachine is null !!
03-16 12:20:45.063  1020  1033 D CountryDetector: The first listener is added
03-16 12:20:45.063  1020  1762 I PersonaManagerService: PersonaId don't exist
03-16 12:20:45.063  1020  1762 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-16 12:20:45.073  1020  1762 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.073  1020  1762 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.073  1020  1762 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-16 12:20:45.073  4805  4805 D Mms/MmsApp: [end]    initCountryIso consume time = 13.603958
03-16 12:20:45.073  4805  4805 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.238959
03-16 12:20:45.073  1020  1762 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,03-16 12:20:45.073  1020  1762 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-16 12:20:45.073  1020  1762 W ActivityManager: mDVFSHelper.acquire()
,03-16 12:20:45.093  1020  1762 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-16 12:20:45.093  1020  1762 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-16 12:20:45.093  1020  1762 D InputDispatcher: Focused application set to: xxxx
,03-16 12:20:45.093  4860  4860 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:45.093  4860  4860 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:45.093  4805  4805 D Mms/MmsConfig: before partial update
,03-16 12:20:45.103  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.IIllIIIlIllIIIllIIlI(252/llllIIIllIlIIIIllllI)] 
,03-16 12:20:45.103  1020  1542 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
03-16 12:20:45.103  1020  1542 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 12:20:45.103  1020  1542 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 12:20:45.103  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 12:20:45.103  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,03-16 12:20:45.103  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2145/onPause)] 
,03-16 12:20:45.113  1020  1500 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 12:20:45.113  1020  1500 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-16 12:20:45.113  1020  1500 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 12:20:45.113  1020  1020 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,03-16 12:20:45.113  1020  1042 D SensorService: [SO] -0.479 0.192 9.883
03-16 12:20:45.113  1020  1042 D SensorService: [SO] [100 -> 255]
03-16 12:20:45.113  4805  4805 D Mms/MmsConfig: Load Resize quality : 80
03-16 12:20:45.113  4805  4805 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-16 12:20:45.123  4805  4805 D EasySignUpManager_1.0.1: isAuth is false
,03-16 12:20:45.123  4805  4805 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-16 12:20:45.123  4860  4860 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 12:20:45.123  4860  4860 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-16 12:20:45.133  1478  1502 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4805
,03-16 12:20:45.133  1478  1502 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.387 ms
,03-16 12:20:45.143  4805  4805 D EasySignUpManager_1.0.1: isAuth is false
03-16 12:20:45.143  4805  4805 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-16 12:20:45.143  4805  4805 E CscParser: mps_code.dat does not exist
,03-16 12:20:45.143  4805  4805 E CscParser: customer_path =/system/csc/customer.xml
03-16 12:20:45.143  4805  4805 E CscParser: fileName + /system/csc/customer.xml
,03-16 12:20:45.143  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-16 12:20:45.153  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-16 12:20:45.153  4805  4805 E CscParser: mps_code.dat does not exist
03-16 12:20:45.153  4805  4805 E CscParser: customer_path =/system/csc/customer.xml
03-16 12:20:45.153  4805  4805 E CscParser: fileName + /system/csc/customer.xml
,03-16 12:20:45.163  4805  4805 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-16 12:20:45.163  4805  4805 D Mms/MmsConfig:  enable multiwindow = false
,03-16 12:20:45.173  4805  4805 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-16 12:20:45.173  4805  4805 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-16 12:20:45.183  1020  1532 I ActivityManager: Killing 4326:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,03-16 12:20:45.183  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-16 12:20:45.183  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(75/onCreate)] Postpone Count : 24
,03-16 12:20:45.193  4805  4805 D Mms/MmsConfig: [end]    init() consume time = 114.989062
,03-16 12:20:45.193  4284  4633 I SA      : [RC New] [v2liruge] api execute + 923
03-16 12:20:45.193  4284  4633 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,03-16 12:20:45.193  4284  4633 I System.out: AsyncTask #1 calls detatch()
,03-16 12:20:45.193  4805  4805 D Mms/Contact: [start]    init() consume time = 5.233594
,03-16 12:20:45.193  1020  1044 W libprocessgroup: failed to open /acct/uid_10127/pid_4211/cgroup.procs: No such file or directory
,03-16 12:20:45.203  4284  4633 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,03-16 12:20:45.213  1478  1502 D TP/MmsSmsProvider: query,matched:13, calling pid = 4805
,03-16 12:20:45.213  1478  1502 D TP/MmsSmsProvider: match 13:Elapsed time : 1.444 ms
,03-16 12:20:45.213  4284  4633 I SA      : [OCP] update openData : PL
,03-16 12:20:45.223  4805  4805 D Mms/Contact: [end]    init consume time = 25.067031
,03-16 12:20:45.223  4284  4633 I SA      : [TPMU] getNetworkMcc : 
,03-16 12:20:45.223  4284  4633 I SA      : [SCU] saveMccToPreferece Start
,03-16 12:20:45.223  4284  4633 I SA      : [SCU] RegionMCC : 260
03-16 12:20:45.223  4284  4633 I SA      : [SSP] query invoked
,03-16 12:20:45.223  4284  4633 I SA      : [TPMU] GetMccFromDB : null
03-16 12:20:45.223  4284  4633 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-16 12:20:45.223  4284  4633 I SA      : [SCU] saveMccToPreferece End
,03-16 12:20:45.223  4284  4633 I SA      : [RC New] executeRequest [v2liruge] end. 998
03-16 12:20:45.223  4284  4633 I SA      : [RC New] Execute end
,03-16 12:20:45.223  4284  4284 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-16 12:20:45.223  4284  4284 I SA      : [OR] GetMyCountryZoneTask Success
03-16 12:20:45.233  4805  4880 D Mms/DraftCache: [start]    rebuildCache consume time = 9.737292
,03-16 12:20:45.233  1478  2459 D TP/MmsSmsProvider: query,matched:12, calling pid = 4805
,03-16 12:20:45.233  4805  4805 D Mms/MethodReflector: getSubId is called
03-16 12:20:45.233  4805  4805 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-16 12:20:45.233  4805  4805 D Mms/MethodReflector: getTelephonyProperty is called
03-16 12:20:45.233  1478  2459 D TP/MmsSmsProvider: match 12:Elapsed time : 2.999 ms
,03-16 12:20:45.233  4805  4805 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-16 12:20:45.233  4805  4805 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-16 12:20:45.233  4805  4805 D Mms/DownloadManager: auto download without roaming -> true
03-16 12:20:45.233  4805  4805 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
03-16 12:20:45.233  4805  4805 D Mms/MethodReflector: getSubId is called
,03-16 12:20:45.233  4805  4805 D Mms/MethodReflector: getDefaultSmsSubId is called
03-16 12:20:45.233  3173  3173 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 12:20:45.233  3173  3173 D PhoneWindow: *FMB* installDecor flags : -2139029248
03-16 12:20:45.233  4805  4805 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-16 12:20:45.233  4805  4805 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
03-16 12:20:45.233  4805  4805 D Mms/MethodReflector: getTelephonyProperty is called
03-16 12:20:45.233  4805  4805 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-16 12:20:45.233  4805  4805 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-16 12:20:45.233  4805  4805 D Mms/DownloadManager: auto download without roaming -> true
03-16 12:20:45.233  4805  4805 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-16 12:20:45.233  4805  4805 D Mms/DownloadManager: auto download during roaming secondary -> false
03-16 12:20:45.233  4805  4805 D Mms/DownloadManager: mAutoDownload ------> true
,03-16 12:20:45.243  4805  4880 D Mms/DraftCache: [end]    rebuildCache consume time = 19.51875
,03-16 12:20:45.253  4805  4805 D ComposerPerformance: 1458127245260 ms / [DONE] Composer constructor
,03-16 12:20:45.253  4805  4805 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-16 12:20:45.253  4805  4805 I Mms/ReservationManager: ReservationManager()
03-16 12:20:45.253  4805  4805 I Mms/ReservationManager: resetAfterConnected()
,03-16 12:20:45.263  1478  1488 D TP/MmsSmsProvider: query,matched:7, calling pid = 4805
,03-16 12:20:45.263  1478  1488 D TP/MmsSmsProvider: match 7:Elapsed time : 3.519 ms
,03-16 12:20:45.263  4805  4881 D Mms/Conversation: [start]    init() consume time = 15.883958
,03-16 12:20:45.263  1478  2459 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-16 12:20:45.263  4805  4805 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-16 12:20:45.273  1478  2459 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-16 12:20:45.273  1478  2459 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-16 12:20:45.273  1478  2459 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-16 12:20:45.273  1478  2459 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 12:20:45.273  1478  2459 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 12:20:45.273  1478  2459 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 12:20:45.273  1478  2459 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-16 12:20:45.273  1478  2459 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 12:20:45.273  1478  2459 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-16 12:20:45.273  4805  4805 D Mms/MmsApp: [end]    onCreate() consume time = 13.606302
,03-16 12:20:45.283  4805  4853 D Mms/ArtClassLoader: init [DONE] art
,03-16 12:20:45.283  1478  2459 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-16 12:20:45.283  1478  2459 D TP/MmsSmsProvider: need read changed broadcast:false
03-16 12:20:45.283  4805  4805 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,03-16 12:20:45.283  4805  4805 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,03-16 12:20:45.283  1020  1080 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.,
,03-16 12:20:45.283  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.283  1020  1080 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.283  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.283  4805  4805 D Mms/MethodReflector: getSubId is called
,03-16 12:20:45.283  4805  4805 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-16 12:20:45.293  4805  4881 D Mms/Conversation: [end]    init consume time = 10.852604
03-16 12:20:45.293  4805  4881 D Mms/MessagingNotification: [start]    init() consume time = 0.088178
,03-16 12:20:45.293  1020  1080 I ActivityManager: Killing 4157:com.android.vending/u0a26 (adj 15): empty #31
,03-16 12:20:45.293  4805  4805 D Mms/MethodReflector: getTelephonyProperty is called
03-16 12:20:45.293  4805  4805 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-16 12:20:45.293  4805  4805 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-16 12:20:45.293  4805  4805 D Mms/DownloadManager: auto download without roaming -> true
03-16 12:20:45.293  4805  4805 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,03-16 12:20:45.293  4805  4805 D Mms/DownloadManager: mAutoDownload ------> true
,03-16 12:20:45.293  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.293  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.293  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.303  1020  1044 W libprocessgroup: failed to open /acct/uid_10135/pid_4326/cgroup.procs: No such file or directory
,03-16 12:20:45.303  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.303  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 12:20:45.303  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.313  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.313  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.313  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.313  4805  4881 D Mms/MessagingNotification: [end]    init consume time = 26.392604
,03-16 12:20:45.313  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.313  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.313  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.313  4805  4882 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 2.405364
,03-16 12:20:45.323  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.323  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.323  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.323  4805  4883 D Mms/Synchronizer: [start]    doSync consume time = 3.646719
,03-16 12:20:45.323  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-16 12:20:45.323  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-16 12:20:45.323  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.323  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.323  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.323  1478  1502 D TP/MmsSmsProvider: query,matched:0, calling pid = 4805
03-16 12:20:45.323  1478  1502 V TP/MmsSmsProvider: getSimpleConversations entered.
,03-16 12:20:45.323  1478  1502 D TP/MmsSmsProvider: match 0:Elapsed time : 1.082 ms
,03-16 12:20:45.333  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.333  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.333  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.333  1478  2459 D TP/MmsSmsProvider: query,matched:400, calling pid = 4805
,03-16 12:20:45.333  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.333  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.333  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.333  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-16 12:20:45.333  1020  1044 W libprocessgroup: failed to open /acct/uid_10026/pid_4157/cgroup.procs: No such file or directory
,03-16 12:20:45.333  1478  1851 D TP/MmsSmsProvider: update, matched:300, calling pid = 4805
03-16 12:20:45.333  1478  1851 V TP/MmsSmsProvider: syncDBData start
,03-16 12:20:45.343  1478  1851 V TP/MmsSmsProvider: syncDBData sms end
,03-16 12:20:45.343  1478  1851 V TP/MmsSmsProvider: syncDBData mms end
,03-16 12:20:45.343  1478  1851 V TP/MmsSmsProvider: syncDBData end
,03-16 12:20:45.343  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.343  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.343  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.353  4805  4882 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 28.124375
,03-16 12:20:45.353  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.353  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.353  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.353  4805  4883 D Mms/Synchronizer: [end]    doSync consume time = 4.051667
,03-16 12:20:45.353  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.353  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.353  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.363  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.363  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.363  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.363  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-16 12:20:45.363  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.363  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.363  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.363  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.363  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.363  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 12:20:45.373  4805  4881 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-16 12:20:45.373  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.373  1020  1020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.373  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.373  1478  2459 D TP/SmsProvider: query,matched:26, calling pid = 4805
,03-16 12:20:45.373  1020  1532 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-16 12:20:45.373  1020  1532 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-16 12:20:45.373  1020  1532 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-16 12:20:45.373  1020  1532 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-16 12:20:45.383  1478  2459 D TP/SmsProvider: match 26:Elapsed time : 2.161 ms
,03-16 12:20:45.383  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.383  1020  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.383  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.393  1020  1033 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-16 12:20:45.393  1020  1033 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-16 12:20:45.393  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.393  1020  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:45.393  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.393  1020  1020 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-16 12:20:45.393  1478  1851 D TP/MmsSmsProvider: query,matched:6, calling pid = 4805
,03-16 12:20:45.403  1478  1851 D TP/MmsSmsProvider: match 6:Elapsed time : 1.757 ms
,03-16 12:20:45.403  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
03-16 12:20:45.403  1020  1020 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-16 12:20:45.403  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.403  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.403  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.403  1187  1204 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 12:20:45.403  1820  4884 E MDM     : [252] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 12:20:45.413  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-16 12:20:45.413  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.413  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.413  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.413  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-16 12:20:45.413  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-16 12:20:45.423  1020  1543 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.423  1020  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.423  1020  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.423  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.423  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.423  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.433  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.433  1020  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.433  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.433  2108  4885 D LocationInitializer: Restart initialization of location
,03-16 12:20:45.433  1020  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.433  1020  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.433  1020  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.443  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-16 12:20:45.443  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.443  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.443  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.443  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-16 12:20:45.453  1020  1080 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.453  1020  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.453  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-16 12:20:45.453  1020  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.453  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-16 12:20:45.463  1820  1820 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-16 12:20:45.463  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-16 12:20:45.473  1187  1187 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-16 12:20:45.473  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.473  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 12:20:45.473  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
03-16 12:20:45.473  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-16 12:20:45.473  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.473  1020  1819 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.473  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.483  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.483  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.483  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 12:20:45.483  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-16 12:20:45.483  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-16 12:20:45.483  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,03-16 12:20:45.493  1820  1820 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 12:20:45.493  1187  1187 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-16 12:20:45.493  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.493  1020  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.493  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.493  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-16 12:20:45.493  1187  1187 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
,03-16 12:20:45.493  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
03-16 12:20:45.493  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
,03-16 12:20:45.493  1187  1187 I PhoneStatusBar: Icon Only
,03-16 12:20:45.493  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.493  1020  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.503  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.503  1187  1187 I StatusBar: Icon Only
,03-16 12:20:45.503  1187  1187 D PanelView: There is/are notification(s) 
03-16 12:20:45.503  1187  1187 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 12:20:45.503  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
,03-16 12:20:45.503  1187  1187 I PhoneStatusBar: Icon Only
03-16 12:20:45.503  1187  1187 I StatusBar: Icon Only
03-16 12:20:45.503  1187  1187 D PanelView: There is/are notification(s) 
03-16 12:20:45.503  1187  1187 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 12:20:45.503  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-16 12:20:45.503  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:45.503  1820  2137 W GCoreFlp: No location to return for getLastLocation()
,03-16 12:20:45.503  1820  4886 W FusedLocationProvider: location=null,
03-16 12:20:45.513  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:45.513  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:45.513  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:45.513  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-16 12:20:45.523  4889  4889 I libpersona: KNOX_SDCARD checking this for 10023
03-16 12:20:45.513  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 24
03-16 12:20:45.523  4889  4889 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:45.523  4889  4889 E Zygote  : MountEmulatedStorage()
03-16 12:20:45.523  4889  4889 E Zygote  : v2
03-16 12:20:45.523  4889  4889 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 12:20:45.523  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-16 12:20:45.523  4889  4889 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:45.523  4889  4889 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:45.533  1020  1542 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4889 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,03-16 12:20:45.533  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-16 12:20:45.543  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.543  1020  1130 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.543  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-16 12:20:45.553  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-16 12:20:45.553  4889  4889 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 12:20:45.553  4889  4889 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:45.553  1020  1819 I ActivityManager: Killing 4411:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-16 12:20:45.563  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-16 12:20:45.573  1187  1187 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-16 12:20:45.573  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.573  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 12:20:45.573  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-16 12:20:45.573  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.573  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:45.573  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 12:20:45.583  1020  1033 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,03-16 12:20:45.583  1020  1033 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-16 12:20:45.593  1020  1020 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-16 12:20:45.593  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 24
,03-16 12:20:45.603  1187  1187 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-16 12:20:45.603  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-16 12:20:45.603  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
,03-16 12:20:45.603  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
,03-16 12:20:45.603  1187  1187 I PhoneStatusBar: Icon Only
,03-16 12:20:45.603  1187  1187 I StatusBar: Icon Only
,03-16 12:20:45.603  1187  1187 D PanelView: There is/are notification(s) 
03-16 12:20:45.603  1187  1187 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 12:20:45.603  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
,03-16 12:20:45.603  1187  1187 I PhoneStatusBar: Icon Only
,03-16 12:20:45.613  1187  1187 I StatusBar: Icon Only
,03-16 12:20:45.613  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-16 12:20:45.613  1187  1187 D PanelView: There is/are notification(s) 
,03-16 12:20:45.613  1187  1187 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 12:20:45.613  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-16 12:20:45.613  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,03-16 12:20:45.613  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4411/cgroup.procs: No such file or directory
,03-16 12:20:45.613  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,03-16 12:20:45.643  3173  4905 D OpenGLRenderer: Render dirty regions requested: true
,03-16 12:20:45.653  1020  1506 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-16 12:20:45.653  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 12:20:45.653  1020  1506 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 12:20:45.653  1020  1506 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 12:20:45.653  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-16 12:20:45.653  3173  3173 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 12:20:45.653  3173  3173 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-16 12:20:45.663  4889  4889 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-16 12:20:45.673  1187  1187 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-16 12:20:45.693  4805  4881 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-16 12:20:45.703  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-16 12:20:45.703  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,03-16 12:20:45.713  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-16 12:20:45.713  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-16 12:20:45.713  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-16 12:20:45.713  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-16 12:20:45.713  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:45.713  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:45.713  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,03-16 12:20:45.713  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:45.713  1020  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:45.713  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,03-16 12:20:45.713  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-16 12:20:45.713  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-16 12:20:45.723   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, YUIInstallC,
03-16 12:20:45.723  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
03-16 12:20:45.723  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
03-16 12:20:45.723  4889  4889 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-16 12:20:45.723  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
03-16 12:20:45.723  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
03-16 12:20:45.733  4907  4907 E Zygote  : MountEmulatedStorage()
03-16 12:20:45.733  4907  4907 E Zygote  : v2,
,03-16 12:20:45.733  4907  4907 I libpersona: KNOX_SDCARD checking this for 1000
,03-16 12:20:45.733  4907  4907 I libpersona: KNOX_SDCARD not a persona
03-16 12:20:45.733  4907  4907 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:45.733  1020  1542 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4907 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:45.733  4907  4907 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:45.733  4907  4907 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 12:20:45.743  1020  1543 D InputDispatcher: Focus entered window: 3173
,03-16 12:20:45.743  3173  3173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-16 12:20:45.753  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 12:20:45.753  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 12:20:45.753  3173  4905 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 12:20:45.753  3173  4905 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 12:20:45.753  3173  4905 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 12:20:45.753  3173  4905 I Adreno-EGL: Local Branch: 
03-16 12:20:45.753  3173  4905 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 12:20:45.753  3173  4905 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 12:20:45.753  3173  4905 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 12:20:45.763  3173  4905 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 12:20:45.783  4907  4907 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:45.783  3173  4905 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-16 12:20:45.783  3173  4905 D OpenGLRenderer: Enabling debug mode 0
,03-16 12:20:45.783  4907  4907 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:45.783  1725  1847 I art     : Explicit concurrent mark sweep GC freed 2853(113KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 749us total 31.089ms
,03-16 12:20:45.803  4805  4805 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-16 12:20:45.803  4805  4805 D Mms/Contact: performUpdate:widgetCount=0
,03-16 12:20:45.803  4805  4924 D Mms/ContactsCache: [start]    invalidate() consume time = 452.734843
,03-16 12:20:45.803  4805  4924 D Mms/ContactsCache: [end]    invalidate() consume time = 1.650261
,03-16 12:20:45.833  1020  1020 I ValidateNoPeople: mEvictionCount: 0
,03-16 12:20:45.833  4907  4907 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-16 12:20:45.833  1020  1506 D SecContentProvider2: uri = 14 selection = getSealedState
03-16 12:20:45.833  1020  1506 D SecContentProvider2: mCursor = null
,03-16 12:20:45.833  1020  1130 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-16 12:20:45.833  1020  1130 D SecContentProvider2: mCursor = null
,03-16 12:20:45.833  4907  4907 V MTPRx   : sealedState: false
03-16 12:20:45.833  4907  4907 V MTPRx   : sealedUsbMassStorageState: false
03-16 12:20:45.833  4907  4907 E MTPRx   : check value of boot_completed is1
03-16 12:20:45.833  4907  4907 E MTPRx   : check booting is completed_sys.boot_completed
,03-16 12:20:45.843  4907  4907 E MTPRx   : Sd-Card path/storage/extSdCard
,03-16 12:20:45.843  4907  4907 E MTPRx   : Status for mount/Unmount :removed
03-16 12:20:45.843  4907  4907 E MTPRx   : SDcard is not available
,03-16 12:20:45.843  4907  4907 W MTPRx   : value of connected istrue
03-16 12:20:45.843  4907  4907 W MTPRx   : value of configured istrue
03-16 12:20:45.843  4907  4907 W MTPRx   : value of mtpEnabled istrue
03-16 12:20:45.843  4907  4907 W MTPRx   : value of ptpEnabled isfalse
,03-16 12:20:45.843  4907  4907 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-16 12:20:45.853  4907  4907 E MTPRx   : mFirstTime: false
,03-16 12:20:45.863  4907  4907 D         : MTP: reading debug level property
,03-16 12:20:45.863  4907  4907 E MTPJNIInterface: Getting CryptionKey from JAVA
03-16 12:20:45.863  4907  4907 E MTPRx   : currentUserId is 0
,03-16 12:20:45.863  1020  1130 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 12:20:45.863  1020  1051 D PersonaManager: isKioskContainerExistOnDevice
,03-16 12:20:45.863  4907  4907 E MTPRx   : Start observing USB_STATE_MATCH 
,03-16 12:20:45.873  4907  4907 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
03-16 12:20:45.873  4907  4907 E MTPRx   : is_Privatemode is NOT 1
,03-16 12:20:45.873  1020  1051 I ActivityManager: Displayed Component not be shown by security: +763ms (total +947ms)
,03-16 12:20:45.873  1020  4926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 12:20:45.873  1020  1542 D SettingsProvider: name = boot_time_connected
,03-16 12:20:45.873  1187  1187 I StatusBar: Icon Only
,03-16 12:20:45.883  1187  1187 D PanelView: There is/are notification(s) 
,03-16 12:20:45.883  4907  4907 E MTPRx   : Sending NORMAL_BOOT to stack
03-16 12:20:45.883  4907  4907 E MTPJNIInterface: noti = 17
,03-16 12:20:45.893  1020  1080 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 12:20:45.903  3173  3173 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8759756 time:51513
,03-16 12:20:45.903  1880  1880 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-16 12:20:45.903  1020  1506 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-16 12:20:45.903  4907  4907 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-16 12:20:45.903  1020  1542 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.903  1020  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.903  1020  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-16 12:20:45.913  1020  1130 D SettingsProvider: name = mtp_running_status
,03-16 12:20:45.913  1020  3165 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 12:20:45.923  4907  4907 E MTPRx   : else part ... so first time!!!
,03-16 12:20:45.923  4907  4907 E MTPPlaObsrvr: inside setContext()
03-16 12:20:45.923  4907  4907 E MTPPlaObsrvr:  inside createplafiles
,03-16 12:20:45.933  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 12:20:45.933  4907  4907 E MTPPlaObsrvr: playlist count is0
,03-16 12:20:45.933  4907  4907 E MTPPlaObsrvr:  inside try branch createplafiles
,03-16 12:20:45.933  4907  4907 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-16 12:20:45.933  4907  4907 E MTPPlaObsrvr: Inside registerContentObserver
,03-16 12:20:45.943  4907  4907 E MtpAdbObserver: inside setContext()
,03-16 12:20:45.943  4907  4907 E MtpAdbObserver: Inside registerContentObserver
03-16 12:20:45.943  4907  4907 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-16 12:20:45.943  1020  1819 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:45.943  1020  1819 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.943  1020  1819 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-16 12:20:45.943  1020  1505 D SettingsProvider: name = mtp_running_status
,03-16 12:20:45.943  1020  1542 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 12:20:45.943  4907  4907 E MtpService: onCreate.
,03-16 12:20:45.943  4907  4930 V MtpMediaDBManager: inside deleteAllDB
,03-16 12:20:45.953  1020  3165 W ActivityManager: userId = 0, bbcId = -10000
03-16 12:20:45.953  1020  3165 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:45.953  1020  3165 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-16 12:20:45.953  4907  4907 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-16 12:20:45.953  1255  1255 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-16 12:20:45.953  4907  4907 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-16 12:20:45.953  4907  4907 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-16 12:20:45.963  4907  4907 E MtpService: onStartCommand.
,03-16 12:20:45.963  4907  4907 W MTPRx   : calling native method
03-16 12:20:45.963  4907  4907 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-16 12:20:45.963  4907  4931 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-16 12:20:45.963  1020  3165 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:45.963  1020  3165 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:45.963  1020  3165 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 12:20:45.963  1020  3165 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 12:20:45.983  4932  4932 E Zygote  : MountEmulatedStorage()
,03-16 12:20:45.983  4932  4932 E Zygote  : v2
03-16 12:20:45.983  4932  4932 I libpersona: KNOX_SDCARD checking this for 1000
03-16 12:20:45.983  4932  4932 I libpersona: KNOX_SDCARD not a persona
,03-16 12:20:45.983  4932  4932 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 12:20:45.993  1020  3165 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4932 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 12:20:45.993  4932  4932 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 12:20:45.993  4932  4932 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 12:20:45.993  4907  4907 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-16 12:20:46.003  4907  4907 E MTPJNIInterface: noti = 10
,03-16 12:20:46.003  4907  4930 V MtpMediaDBManager: inside Thread updateDB
03-16 12:20:46.003  4907  4907 E MtpService: onStartCommand.
,03-16 12:20:46.003  4907  4907 W MTPRx   : calling native method
03-16 12:20:46.003  4907  4907 E MTPRx   : Checking the driver time out
03-16 12:20:46.003  4907  4907 E MTPJNIInterface: noti = 2
03-16 12:20:46.003  4907  4907 D         : deleting sockets before message queue initialization
,03-16 12:20:46.003  4907  4907 D         : event handler thread is created, so set the flag
03-16 12:20:46.003  4907  4907 E MTPRx   : called native method
03-16 12:20:46.003   306   306 I art     : Explicit concurrent mark sweep GC freed 8672(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 630us total 21.855ms
03-16 12:20:46.003  4907  4907 E MTPJNIInterface: setting Media scanner status0
03-16 12:20:46.003  4907  4907 E MTPJNIInterface: After setting Media scanner status0
,03-16 12:20:46.003  4907  4907 W MTPRx   : notification from stack 1
03-16 12:20:46.003  4907  4931 E MtpService: handleMessage. msg= { when=-5ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-16 12:20:46.003  4907  4944 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-16 12:20:46.003  4907  4944 E MTPJNIInterface: Getting media scanner status0
,03-16 12:20:46.013  4907  4944 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A3)
,03-16 12:20:46.023  4932  4932 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 12:20:46.023  4932  4932 D ActivityThread: Added TimaKeyStore provider
,03-16 12:20:46.023   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.906ms
,03-16 12:20:46.043   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.443ms
,03-16 12:20:46.053  1020  1060 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,03-16 12:20:46.153  1020  1819 I art     : Explicit concurrent mark sweep GC freed 19911(1079KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 2.465ms total 139.827ms
,03-16 12:20:46.163  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:46.163  1020  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:46.163  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-16 12:20:46.163  4511  4539 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 12:20:46.183  1187  1187 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.PACKAGE_CHANGED
,03-16 12:20:46.183  1020  1104 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 12:20:46.193  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 12:20:46.193  4907  4930 E MtpMediaDBManager: count : 26
,03-16 12:20:46.203  4121  4121 I PageBuddyNotiSvc: mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,03-16 12:20:46.213  1468  1468 D RegisteredServicesCache: empty dynamic service
,03-16 12:20:46.213  1020  1020 W IntentResolver: resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,03-16 12:20:46.213  1478  1478 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 12:20:46.223  4907  4930 W MtpMediaDBManager: sending db update complete noti to stack
,03-16 12:20:46.223  4907  4930 E MTPJNIInterface: noti = 29
,03-16 12:20:46.233  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 12:20:46.243  4907  4944 E SQLiteLog: (5) database is locked
,03-16 12:20:46.243  4907  4944 E SQLiteLog: (5) database is locked
,03-16 12:20:46.263  4907  4944 E MTPJNIInterface: Status for mount/Unmount :removed
03-16 12:20:46.263  4907  4944 E MTPJNIInterface: SDcard is not available
,03-16 12:20:46.273  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 12:20:46.283  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 12:20:46.283  1020  1532 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:46.283  1020  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 12:20:46.283  1020  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-16 12:20:46.293  1020  1051 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,03-16 12:20:46.293  1020  1051 W ActivityManager: mDVFSHelper.release()
03-16 12:20:46.293  1020  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{394eb5f u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t12} time:51905
,03-16 12:20:46.293   257  1100 I SurfaceFlinger: id=12 Removed Mauncher (5/8)
,03-16 12:20:46.293   257   449 I SurfaceFlinger: id=12 Removed Mauncher (-2/8)
,03-16 12:20:46.303  1020  1542 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-16 12:20:46.303  1020  1542 D SecContentProvider2: mCursor = null
,03-16 12:20:46.313  1020  1045 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11,
,03-16 12:20:46.313  1508  1508 D Launcher.HomeView: onStop
,03-16 12:20:46.313  4907  4944 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-16 12:20:46.323  1508  1508 V ActivityThread: updateVisibility : ActivityRecord{1507cf7 token=android.os.BinderProxy@29a0c0bd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,03-16 12:20:46.323  1508  1508 D Launcher: onTrimMemory. Level: 20
,03-16 12:20:46.333  4907  4944 E MTPJNIInterface: Status for mount/Unmount :removed
03-16 12:20:46.333  4907  4944 E MTPJNIInterface: SDcard is not available
,03-16 12:20:46.333  4907  4944 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 12:20:46.333  1020  1080 I ActivityManager: Killing 4468:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
03-16 12:20:46.333  4907  4944 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-16 12:20:46.333  4907  4944 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 12:20:46.333  4907  4944 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-16 12:20:46.333  4907  4944 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 12:20:46.333  4907  4944 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-16 12:20:46.333  4907  4944 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 12:20:46.333  4907  4944 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-16 12:20:46.333  4907  4907 W MTPRx   : notification from stack 2
,03-16 12:20:46.333  4907  4954 D         : [mtp_init_device] Library open with 32 bits.
,03-16 12:20:46.333  4907  4954 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,03-16 12:20:46.343  4907  4954 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-16 12:20:46.343  4907  4954 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-16 12:20:46.343  4907  4954 E         :  [sua_support_present:1287] returning false 
03-16 12:20:46.343  4907  4954 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,03-16 12:20:46.343  4932  4932 D TMNetworkReceiver: TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
03-16 12:20:46.343  4932  4932 D TMNetworkReceiver: TMNetworkReceiver.onReceive() Enter
,03-16 12:20:46.343  4932  4932 D TMNetworkReceiver: MirrorLink feauture level: using UEvent
,03-16 12:20:46.343  1020  1543 W ActivityManager: userId = 0, bbcId = -10000
,03-16 12:20:46.343  1020  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 12:20:46.343  1020  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,03-16 12:20:46.343  1020  1543 I ActivityManager: Killing 4491:com.sec.modem.settings/1000 (adj 15): empty #31

```
