#### Test 63186632d456b18_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-17 09:49:29.664   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 562us total 16.434ms
03-17 09:49:29.674  2946  2946 E Zygote  : MountEmulatedStorage()
03-17 09:49:29.674  2946  2946 E Zygote  : v2
03-17 09:49:29.674  2946  2946 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
--------- beginning of system
03-17 09:49:29.674  2946  2946 I libpersona: KNOX_SDCARD checking this for 1101
03-17 09:49:29.674  2946  2946 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:29.674  1022  1048 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=2946 uid=1101 gids={41101, 9997} abi=armeabi-v7a
03-17 09:49:29.684  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:29.684  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:29.684  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
03-17 09:49:29.684  2946  2946 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:29.684  2946  2946 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:29.694  2653  2765 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
03-17 09:49:29.704  1022  1022 D SettingsProvider: name = bluetooth_name
03-17 09:49:29.704  1022  1510 I ActivityManager: Killing 2092:com.sec.android.widgetapp.samsungapps/u0a134 (adj 15): empty #31
03-17 09:49:29.714  2653  2765 D BluetoothAdapterProperties: Scan Mode:20
03-17 09:49:29.714  2653  2765 D BluetoothAdapterProperties: Discoverable Timeout:120
03-17 09:49:29.714  2653  2765 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
03-17 09:49:29.714  2653  2765 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
03-17 09:49:29.714  2653  2765 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
03-17 09:49:29.714  2653  2765 E bt-btif : btif_sock_init: !radio_req && !rfc_init
03-17 09:49:29.714  2653  2765 E bt-btif : btif_sock_init: !vhci_init
03-17 09:49:29.714  2653  2765 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
03-17 09:49:29.714  2653  2895 E bt_mct  : hci lib postload completed
03-17 09:49:29.714  2946  2946 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:29.714  2946  2946 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:29.714  1022  1504 I ActivityManager: Killing 1859:com.android.vending/u0a26 (adj 15): empty #31
03-17 09:49:29.724  1022  2880 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
03-17 09:49:29.724  2653  2765 D IOP_DB_BT: db_open: db_open : handle 3027611664l, read 13894 bytes onto local cache
03-17 09:49:29.724  2653  2765 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
03-17 09:49:29.724  2653  2765 D IOP_DB_BT: db_query: result 1
03-17 09:49:29.724  2653  2765 I         : iop_db_open: iop_db_open status 0
03-17 09:49:29.724  2653  2765 D bte_conf: Device ID record 1 : primary
03-17 09:49:29.724  2653  2765 D bte_conf:   vendorId            = 0075
03-17 09:49:29.724  2653  2765 D bte_conf:   vendorIdSource      = 0001
03-17 09:49:29.724  2653  2765 D bte_conf:   product             = 0100
03-17 09:49:29.724  2653  2765 D bte_conf:   version             = 0200
03-17 09:49:29.724  2653  2765 D bte_conf:   clientExecutableURL = 
03-17 09:49:29.724  2653  2765 D bte_conf:   serviceDescription  = 
03-17 09:49:29.724  2653  2765 D bte_conf:   documentationURL    = 
03-17 09:49:29.724  2653  2765 D bte_conf: bte_load_did_conf no section named DID2.
03-17 09:49:29.724  1022  2888 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 09:49:29.724  2653  2765 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
03-17 09:49:29.734  1022  2888 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 09:49:29.734  2653  2762 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-17 09:49:29.734  2653  2762 D BluetoothAdapterProperties: ScanMode =  20
03-17 09:49:29.734  2653  2762 D BluetoothAdapterProperties: State =  11
03-17 09:49:29.734  1022  1509 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
03-17 09:49:29.734  2653  2762 D BluetoothAdapterProperties: Setting state to 12
03-17 09:49:29.734  2924  2924 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 09:49:29.734  2924  2924 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 09:49:29.734  2924  2924 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 09:49:29.734  2924  2924 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 09:49:29.734  2924  2924 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-17 09:49:29.744  1022  2888 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
03-17 09:49:29.744  1022  2880 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
03-17 09:49:29.744  2653  2762 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
03-17 09:49:29.744  1022  2880 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 09:49:29.744  1022  2888 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 09:49:29.744  1022  2880 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
03-17 09:49:29.744  1022  1500 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:29.744  1022  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:29.744  1022  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 09:49:29.754  1022  2888 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 09:49:29.754  1022  2880 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
03-17 09:49:29.754  2653  2765 D BluetoothAdapterProperties: Scan Mode:21
03-17 09:49:29.754  2653  2765 D BluetoothAdapterProperties: Discoverable Timeout:120
03-17 09:49:29.754  1022  1382 D SettingsProvider: name = bluetooth_a2dp_sink_mode
03-17 09:49:29.754  1022  1600 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:29.754  1022  1382 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:29.754  1022  1382 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:29.754  1022  1382 D SettingsProvider: selectionArgs: false
03-17 09:49:29.754  1022  1382 D SettingsProvider: selectionArgs: 1002
03-17 09:49:29.754  1022  1600 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:29.754  1022  1600 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 09:49:29.754  1022  1382 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:29.754  1022  1382 D SettingsProvider: ret = -1
03-17 09:49:29.754  2946  2946 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
03-17 09:49:29.764  2946  2946 V SmartcardService: main Received broadcast
03-17 09:49:29.764  2946  2946 V SmartcardService: Starting smartcard service after boot completed
03-17 09:49:29.764  1022  1504 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:29.764  1022  2888 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 09:49:29.764  1022  2880 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
03-17 09:49:29.764  1022  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:29.764  1022  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
03-17 09:49:29.764  1022  2880 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 09:49:29.764  1022  2880 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-17 09:49:29.774  1022  2880 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 09:49:29.774  1022  2880 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
03-17 09:49:29.774  1022  2880 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 09:49:29.774  1022  2880 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
03-17 09:49:29.774  1022  2835 I ActivityManager: Killing 2220:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
03-17 09:49:29.784  1022  1500 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:29.784  1022  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:29.784  1022  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-17 09:49:29.784  1022  1382 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-17 09:49:29.794  1243  1243 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-17 09:49:29.794  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:29.794  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:29.794  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:29.794  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:29.794  2653  2762 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-17 09:49:29.794  2653  2762 D BluetoothAdapterService: updateAdapterState state is 12
03-17 09:49:29.794  1022  1047 W libprocessgroup: failed to open /acct/uid_10134/pid_2092/cgroup.procs: No such file or directory
03-17 09:49:29.804  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 09:49:29.814  2973  2973 E Zygote  : MountEmulatedStorage()
03-17 09:49:29.814  2973  2973 E Zygote  : v2
03-17 09:49:29.814  2973  2973 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:29.814  2973  2973 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:29.814  2973  2973 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:29.814  1022  1035 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=2973 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:29.814  2973  2973 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:29.814  1022  1271 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:29.814  1022  1271 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:29.814  1022  1271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 09:49:29.814  2973  2973 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:29.824  1022  2888 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 09:49:29.824  2653  2762 D BluetoothAdapterService: Autoconnection is available 
03-17 09:49:29.824  2653  2762 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
03-17 09:49:29.824  2653  2762 D BluetoothAdapterService: starting service from this receiver
03-17 09:49:29.824  1022  2880 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
03-17 09:49:29.824  1175  1850 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:29.834  1175  1850 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:29.834  1022  2888 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
03-17 09:49:29.834  1022  2888 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-17 09:49:29.834  1022  2880 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
03-17 09:49:29.834  2250  2259 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:29.834  2250  2259 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:29.834  1022  1142 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:29.834  1022  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:29.834  1022  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 09:49:29.834  2653  2664 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:29.834  2653  2664 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:29.834  1022  1052 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:29.834  1022  1052 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:29.834  1472  1501 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:29.834  1472  1501 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:29.834  1483  1503 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:29.834  1483  1503 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:29.844  1022  1500 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:29.844  1022  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:29.844  1022  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 09:49:29.844  2653  2666 D BluetoothA2dp: onBluetoothStateChange: up=true
03-17 09:49:29.854  1916  2187 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:29.854  1916  2187 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:29.854  2653  2762 I BluetoothAdapterState: Entering On State from state = 11
03-17 09:49:29.854  1459  2769 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 09:49:29.854  1022  1047 W libprocessgroup: failed to open /acct/uid_10026/pid_1859/cgroup.procs: No such file or directory
03-17 09:49:29.854  1459  2769 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 09:49:29.854  1022  1047 W libprocessgroup: failed to open /acct/uid_10064/pid_2220/cgroup.procs: No such file or directory
03-17 09:49:29.854  2973  2973 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:29.854  1022  1052 D BluetoothA2dp: onBluetoothStateChange: up=true
03-17 09:49:29.854  2973  2973 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:29.864  1022  1034 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 09:49:29.864  1022  1034 D SecContentProvider2: mCursor = null
03-17 09:49:29.864  1022  1022 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-17 09:49:29.864  1022  1022 I InputMethodManagerService: [BT Setting State] State =12
03-17 09:49:29.864  1022  1022 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
03-17 09:49:29.874  1175  1175 D BluetoothTile:  onBluetoothStateChange:
03-17 09:49:29.874  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-17 09:49:29.874  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-17 09:49:29.874  1175  1175 D BluetoothTile:  getBluetoothState : 12
03-17 09:49:29.884  1243  1243 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 09:49:29.884  1175  1627 D BluetoothTile:  handleUpdatestate:false name:null
03-17 09:49:29.884  1832  1832 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
03-17 09:49:29.894  1022  1142 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-17 09:49:29.894  1022  1569 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
03-17 09:49:29.894  1175  1627 D BluetoothTile:  handleUpdatestate:false name:null
03-17 09:49:29.894  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-17 09:49:29.894  1175  1627 D BluetoothTile:  handleUpdatestate:false name:null
03-17 09:49:29.904  2653  2653 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
03-17 09:49:29.944  1459  1459 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@244d9433, true
03-17 09:49:29.944  1459  1459 D BluetoothHeadset: registerMessageListener
03-17 09:49:29.944  2653  2666 D HeadsetService: registerMessageListener
03-17 09:49:29.944  2653  2666 D HeadsetService: registerMessageListener
03-17 09:49:29.944  2653  2770 D HeadsetStateMachine: Disconnected process message: 70
03-17 09:49:29.944  2653  2770 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3c3d56ab
03-17 09:49:29.954  1459  1459 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
03-17 09:49:29.954  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
03-17 09:49:29.954  1459  1459 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-17 09:49:29.954  2973  2973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
03-17 09:49:29.964  2653  2653 I BluetoothPbapService: Handler(): got msg=1
03-17 09:49:29.964  1459  1459 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
03-17 09:49:29.964  1459  1459 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
03-17 09:49:29.964  1022  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:29.964  1022  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:29.964  1022  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
03-17 09:49:29.964  1022  1509 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
03-17 09:49:29.964  2653  2770 D HeadsetStateMachine: Disconnected process message: 9
03-17 09:49:29.974  2653  2770 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
03-17 09:49:29.974  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:29.974  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:29.974  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:29.974  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:29.984  2994  2994 E Zygote  : MountEmulatedStorage()
03-17 09:49:29.984  2994  2994 E Zygote  : v2
03-17 09:49:29.984  2994  2994 I libpersona: KNOX_SDCARD checking this for 10153
03-17 09:49:29.984  2994  2994 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:29.984  1022  1034 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=2994 uid=10153 gids={50153, 9997} abi=armeabi-v7a
03-17 09:49:29.984  2994  2994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:29.994  2994  2994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:29.994  2994  2994 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:29.994  2653  3000 V BluetoothPbapService: PBAP Service initSocket try: 0
03-17 09:49:30.004  2653  3001 D BluetoothMapMasInstance: set MAP SDP message type : 1
03-17 09:49:30.004   285   677 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
03-17 09:49:30.004   285   677 V voice   : voice_set_parameters: enter: A2dpSuspended=false
03-17 09:49:30.004   285   677 V voice   : voice_set_parameters: exit with code(-2)
03-17 09:49:30.004   285   677 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
03-17 09:49:30.004   285   677 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-17 09:49:30.004   285   677 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-17 09:49:30.004   285   677 V audio_hw_primary: adev_set_parameters: exit
03-17 09:49:30.004  2653  2770 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
03-17 09:49:30.004  1022  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.004  1022  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:30.004  1022  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 09:49:30.014  1022  1142 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.014  1022  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:30.014  1022  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 09:49:30.024  2653  3001 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-17 09:49:30.024  2653  3000 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-17 09:49:30.024  2653  3001 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
03-17 09:49:30.024  2653  3001 D BluetoothSocket: bindListen(), new LocalSocket 
03-17 09:49:30.024  2653  3001 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-17 09:49:30.024  2653  3001 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@9608552
03-17 09:49:30.024  2653  3001 D BluetoothSocket: channel: 5
03-17 09:49:30.024  2653  3000 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
03-17 09:49:30.024  2653  3000 D BluetoothSocket: bindListen(), new LocalSocket 
03-17 09:49:30.024  2653  3000 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-17 09:49:30.024  2653  3000 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1623f023
03-17 09:49:30.024  2653  3000 D BluetoothSocket: channel: 19
03-17 09:49:30.024  2653  3000 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
03-17 09:49:30.024  2994  2994 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:30.024  2911  2911 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
03-17 09:49:30.024  2994  2994 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:30.024  2911  2911 E ActivityThread: Failed to find provider info for flipboard.auth.internal
03-17 09:49:30.034  1022  2835 I ActivityManager: Killing 2235:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
03-17 09:49:30.044  1022  1022 I DrmEventReceiver: DrmEventReceiver : onReceive
03-17 09:49:30.044  1022  1022 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
03-17 09:49:30.044  1022  1022 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-17 09:49:30.044  1022  1022 I System.out: start Service
03-17 09:49:30.044  2994  2994 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 09:49:30.064  1022  1382 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.064  1022  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:30.064  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-17 09:49:30.064  1022  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-17 09:49:30.064  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.064  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.064  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.064  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.084  3016  3016 E Zygote  : MountEmulatedStorage()
03-17 09:49:30.084  3016  3016 E Zygote  : v2
03-17 09:49:30.084  1022  1034 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3016 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:30.084  3016  3016 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:30.084  3016  3016 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:30.084  1022  1034 I ActivityManager: Killing 2250:com.vlingo.midas/u0a28 (adj 15): empty #31
03-17 09:49:30.084  3016  3016 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:30.084  3016  3016 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:30.084  3016  3016 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:30.094  1022  1509 D SettingsProvider: name = next_alarm_formatted
03-17 09:49:30.094  1022  1509 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:30.094  1022  1509 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:30.094  1022  1509 D SettingsProvider: selectionArgs: false
03-17 09:49:30.094  1022  1509 D SettingsProvider: selectionArgs: 10081
03-17 09:49:30.094  1022  1509 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:30.094  1022  1509 D SettingsProvider: ret = -1
03-17 09:49:30.104  1022  1509 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10081
03-17 09:49:30.124  1243  3010 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-17 09:49:30.124   284   512 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 629
03-17 09:49:30.124   284   512 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 629
03-17 09:49:30.124  1022  1271 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.124  1022  1271 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:30.124  1022  1271 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 09:49:30.124  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 09:49:30.134  3016  3016 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:30.134  3016  3016 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:30.134  1243  1243 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-17 09:49:30.154  1022  3034 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
03-17 09:49:30.154  1022  1022 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
03-17 09:49:30.154  1483  1498 D TP/MmsProvider: Update uri=content://mms, match=0
03-17 09:49:30.154  1483  1498 D TP/MmsProvider: update , handleReadChangedBroadcast
03-17 09:49:30.154  1483  1498 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 09:49:30.164  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 09:49:30.164  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 09:49:30.164  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:30.164  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:30.164  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:30.164  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:30.164  2420  2420 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-17 09:49:30.164  2420  2420 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 4572.013123
03-17 09:49:30.164  2420  2420 I Mms/ReservationManager: resetAfterConnected()
03-17 09:49:30.174  2420  3035 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 09:49:30.174  2420  3035 D Mms/TelephonyPermission: isDefault true
03-17 09:49:30.174   284   284 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-17 09:49:30.174  1483  1785 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2420
03-17 09:49:30.174  1022  1047 W libprocessgroup: failed to open /acct/uid_10065/pid_2235/cgroup.procs: No such file or directory
03-17 09:49:30.184  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.184  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.184  1022  1047 W libprocessgroup: failed to open /acct/uid_10028/pid_2250/cgroup.procs: No such file or directory
03-17 09:49:30.184  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.184  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.184  1483  1807 D TP/MmsSmsProvider: query,matched:7, calling pid = 2420
03-17 09:49:30.194  1483  1807 D TP/MmsSmsProvider: match 7:Elapsed time : 2.666 ms
03-17 09:49:30.194  3036  3036 E Zygote  : MountEmulatedStorage()
03-17 09:49:30.194  3036  3036 E Zygote  : v2
03-17 09:49:30.194  3036  3036 I libpersona: KNOX_SDCARD checking this for 10155
03-17 09:49:30.194  3036  3036 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:30.204  3036  3036 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:30.204  1022  1569 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3036 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-17 09:49:30.204  3036  3036 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:30.204  3036  3036 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:30.214  1483  1483 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-17 09:49:30.214  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.214  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:30.214  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-17 09:49:30.224  1022  1271 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.224  1022  1271 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.224  1022  1271 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.224  1022  1271 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.224  1483  1785 D TP/MmsSmsProvider: query,matched:200, calling pid = 2420
03-17 09:49:30.234  1483  1785 D TP/MmsSmsProvider: match 200:Elapsed time : 1.017 ms
03-17 09:49:30.234  1483  1483 D CscUpdateService: onStart
03-17 09:49:30.234  1483  1483 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-17 09:49:30.234  1483  1483 I CscUpdateService: set_CSC_version
03-17 09:49:30.234  1483  1483 E CscParser: update(): xml file exist
03-17 09:49:30.244  3051  3051 E Zygote  : MountEmulatedStorage()
03-17 09:49:30.244  3051  3051 E Zygote  : v2
03-17 09:49:30.244  3051  3051 I libpersona: KNOX_SDCARD checking this for 10002
03-17 09:49:30.244  3051  3051 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:30.244  3051  3051 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:30.244  1022  1271 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3051 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
03-17 09:49:30.244  3051  3051 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:30.244  3051  3051 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:30.244  3036  3036 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:30.254  3036  3036 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:30.254  2924  2924 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 140.525ms
03-17 09:49:30.254  2420  2420 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
03-17 09:49:30.264  1243  3010 E SQLiteLog: (283) recovered 364 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
03-17 09:49:30.264  1022  1382 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.264  1022  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:30.264  1022  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-17 09:49:30.274  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.274  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.274  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.274  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.274   299   299 E USB_UICC: Timeout! No signal received. Retry num = 29
03-17 09:49:30.284  1483  1483 I CscUtil : isWifiOnly = false
03-17 09:49:30.284  1483  1483 I System.out: HandDataNode = null
03-17 09:49:30.284  1483  1483 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
03-17 09:49:30.284  3036  3036 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 09:49:30.284  1483  1483 I CscUpdateService: This is normal boot : CSC not updated
03-17 09:49:30.294  3065  3065 E Zygote  : MountEmulatedStorage()
03-17 09:49:30.294  3065  3065 E Zygote  : v2
03-17 09:49:30.294  3065  3065 I libpersona: KNOX_SDCARD checking this for 10043
03-17 09:49:30.294  3065  3065 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:30.294  3065  3065 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:30.294  1483  3067 E CscParser: update(): xml file exist
03-17 09:49:30.294  3065  3065 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:30.294  3065  3065 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:30.294  1022  1034 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3065 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 09:49:30.304  3051  3051 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:30.304  3051  3051 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:30.304  1483  3067 D CscGPS  : CSCGPS.updateParameters
03-17 09:49:30.304  1483  3067 D CscGPS  : supl host : null
03-17 09:49:30.304  1483  3067 D CscGPS  : SUPL Host is null or invalid
03-17 09:49:30.304  1483  3067 D CscGPS  : supl_ver : null
03-17 09:49:30.304  1483  3067 D CscGPS  : SUPL Ver is null or invalid
03-17 09:49:30.304  1483  3067 D CscGPS  : supl port : null
03-17 09:49:30.304  1483  3067 D CscGPS  : SUPL PORT is null or invalid
03-17 09:49:30.304  1483  3067 D CscGPS  : LPP : null
03-17 09:49:30.304  1483  3067 D CscGPS  : LPP is null or invalid
03-17 09:49:30.304  1483  3067 D CscGPS  : CSC don't have any AGPS value.
03-17 09:49:30.314  1483  1483 I CscUpdateService: same CSC Version
03-17 09:49:30.314  1483  1483 D CscUtil : Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 09:49:30.324  1483  1498 D TP/SmsProvider: query,matched:0, calling pid = 2420
03-17 09:49:30.324   318   318 I ServiceManager: Waiting for service AtCmdFwd...
03-17 09:49:30.324  2420  2420 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-17 09:49:30.324  1483  1498 D TP/SmsProvider: match 0:Elapsed time : 3.281 ms
03-17 09:49:30.324  2420  3076 D Mms/TelephonyPermission: isDefault true
03-17 09:49:30.324  2420  3076 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-17 09:49:30.324  2420  3076 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 159.530573
03-17 09:49:30.334  3065  3065 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:30.334  3065  3065 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:30.344  1483  1503 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-17 09:49:30.344  1483  1503 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
03-17 09:49:30.344  1483  1503 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 09:49:30.344  1483  1503 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
03-17 09:49:30.344  1483  1503 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
03-17 09:49:30.344  1483  1503 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 09:49:30.344  1483  1503 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 09:49:30.344  1483  1503 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 09:49:30.344  1483  1503 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 09:49:30.344  1483  1503 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 09:49:30.344  1483  1503 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 09:49:30.354  3065  3065 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 09:49:30.354  3065  3065 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 09:49:30.354  3065  3065 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 09:49:30.354  1483  1503 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-17 09:49:30.354  1483  1503 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 09:49:30.354  2420  3076 D Mms/Conversation: deleteTempConversation(),deleted=0
03-17 09:49:30.374  1483  1807 D SmsProvider: Update uri=content://sms/outbox, match=8
03-17 09:49:30.374  1483  1807 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 09:49:30.374  2420  3076 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-17 09:49:30.384  2420  3076 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-17 09:49:30.384  2420  3076 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
03-17 09:49:30.384  1483  1785 D TP/SmsProvider: query,matched:26, calling pid = 2420
03-17 09:49:30.384  1483  1785 D TP/SmsProvider: match 26:Elapsed time : 1.407 ms
03-17 09:49:30.394  2420  3076 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 09:49:30.394  2420  3076 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 09:49:30.394  2420  3076 D Mms/TelephonyPermission: isDefault true
03-17 09:49:30.394  1483  1503 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2420
03-17 09:49:30.404  1483  1498 I art     : Explicit concurrent mark sweep GC freed 40628(2MB) AllocSpace objects, 11(176KB) LOS objects, 45% free, 4MB/8MB, paused 959us total 82.359ms
03-17 09:49:30.414  1483  1785 D TP/MmsSmsProvider: query,matched:200, calling pid = 2420
03-17 09:49:30.414  1483  1807 D TP/SmsProvider: query,matched:51, calling pid = 2420
03-17 09:49:30.424  1483  1785 D TP/MmsSmsProvider: match 200:Elapsed time : 0.591 ms
03-17 09:49:30.424  1483  1807 D TP/SmsProvider: match 51:Elapsed time : 4.205 ms
03-17 09:49:30.424  2420  3035 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 09:49:30.434  3036  3036 D [0]UMC:Core: onCreate(): 
03-17 09:49:30.434  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.434  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:30.434  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 09:49:30.454  1022  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.454  1022  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:30.454  1022  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 09:49:30.464  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.464  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.464  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.464  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.464  3036  3036 D [0]UMC:DeviceInfo: USA==US==
03-17 09:49:30.464  1608  1617 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 09:49:30.474  1243  3010 D MediaScanner: Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 09:49:30.474  3087  3087 E Zygote  : MountEmulatedStorage()
03-17 09:49:30.474  3087  3087 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:30.474  3087  3087 E Zygote  : v2
03-17 09:49:30.474  3087  3087 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:30.484  3087  3087 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:30.484  3087  3087 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:30.484  3087  3087 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:30.484  1022  2835 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3087 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:30.484  1022  1510 D SettingsProvider: name = block_emergency_message
03-17 09:49:30.484  1022  1510 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:30.484  1022  1510 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:30.484  1022  1510 D SettingsProvider: selectionArgs: false
03-17 09:49:30.484  1022  1510 D SettingsProvider: selectionArgs: 10043
03-17 09:49:30.484  1022  1510 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:30.484  1022  1510 D SettingsProvider: ret = -1
03-17 09:49:30.494  1022  1271 W ActivityManager: getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
03-17 09:49:30.514  3087  3087 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:30.514  3087  3087 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:30.524  1511  1511 D Launcher.Model: reloadBadges entered.,
03-17 09:49:30.524  1608  1618 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 09:49:30.524  1608  1618 D BadgeProvider: sendNotify, [notify] : null
03-17 09:49:30.524  1608  1618 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 09:49:30.524  1608  1618 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 09:49:30.524  1608  1618 D BadgeProvider: update, [UpdateCount] : 1
03-17 09:49:30.534  2420  3035 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 09:49:30.544  3036  3036 D USER_AGENT: UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
03-17 09:49:30.554  3036  3036 D [0]UMC:AdminManager: init - start
03-17 09:49:30.564  2980  2980 D AndroidRuntime: 
03-17 09:49:30.564  2980  2980 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 09:49:30.564  1022  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.564  1022  1569 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:30.564  1022  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
03-17 09:49:30.564  2980  2980 D AndroidRuntime: CheckJNI is OFF
03-17 09:49:30.564  2980  2980 D AndroidRuntime: readGMSProperty: start
03-17 09:49:30.564  2980  2980 D AndroidRuntime: readGMSProperty: already setted!!
03-17 09:49:30.564  2980  2980 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 09:49:30.564  2980  2980 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 09:49:30.564  2980  2980 D AndroidRuntime: readGMSProperty: end
03-17 09:49:30.564  2980  2980 D AndroidRuntime: addProductProperty: start
03-17 09:49:30.574  1347  1347 I WifiCredService: onCreate
03-17 09:49:30.584  2420  3102 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 09:49:30.584  2420  3035 D Mms/MessagingNotification: remove alarm
03-17 09:49:30.594  3036  3036 D [0]UMC:AdminManager: loadAdmins
03-17 09:49:30.594  1347  1347 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 09:49:30.594  1347  1347 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 09:49:30.594  1347  1347 D MY_TAG  : Action boot completed received
03-17 09:49:30.604  1347  1347 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-17 09:49:30.614  1022  1134 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 09:49:30.614  1022  1134 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 09:49:30.614  1022  1134 E WifiNative-wlan0: invaild command id : 215
03-17 09:49:30.614  1243  3010 V MediaScanner: processDirectory :  /system/media
03-17 09:49:30.624  1347  1347 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-17 09:49:30.624  1022  1569 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-17 09:49:30.624  3036  3036 D [0]UMC:AdminManager: init - end
03-17 09:49:30.624  3036  3036 D GSLBManager: migrateStoredUrlFromOldPref
03-17 09:49:30.634  1347  1347 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-17 09:49:30.634  1347  1347 I NearbySettings: MountReceiver.onReceive - Internal Path
03-17 09:49:30.634  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 09:49:30.644  1347  2218 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-17 09:49:30.644  1022  1142 I art     : Explicit concurrent mark sweep GC freed 142179(7MB) AllocSpace objects, 4(1814KB) LOS objects, 33% free, 22MB/33MB, paused 2.974ms total 210.114ms
03-17 09:49:30.644  1243  3010 V MediaScanner:  prescan time: 437ms (DB items: 138)
03-17 09:49:30.644  1243  3010 V MediaScanner:     scan time: 38ms (Caching mode: true), (makeEntry time: 16ms ~42%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 09:49:30.644  1243  3010 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 09:49:30.644  1243  3010 V MediaScanner:    total time: 475ms
03-17 09:49:30.644  1243  3010 V MediaScanner: checked files: 130  directories : 6  (I: 0, U: 0)
03-17 09:49:30.654  1243  3010 D MediaScanner: checkDefaultSounds
03-17 09:49:30.654  1243  3010 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
03-17 09:49:30.654  3036  3036 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
03-17 09:49:30.654  3036  3036 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-17 09:49:30.654  3036  3036 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
03-17 09:49:30.654  1483  1498 D TP/SmsProvider: query,matched:0, calling pid = 2420
03-17 09:49:30.664  1243  3010 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-17 09:49:30.664  1483  1498 D TP/SmsProvider: match 0:Elapsed time : 4.398 ms
03-17 09:49:30.664  1243  3010 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
03-17 09:49:30.664  3036  3036 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 09:49:30.664  3036  3036 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 09:49:30.664  3036  3036 D [0]UMC:UMCAdmin: isContainer : 0
03-17 09:49:30.664  1483  1785 D TP/SmsProvider: query,matched:0, calling pid = 2420
03-17 09:49:30.664  1243  3010 D MediaScanner: OK. notification_sound is already exist in setting DB.
03-17 09:49:30.664  1243  3010 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
03-17 09:49:30.664  1483  1785 D TP/SmsProvider: match 0:Elapsed time : 5.311 ms
03-17 09:49:30.674  2420  3035 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 343.715052
03-17 09:49:30.674  1022  1035 D SettingsProvider: name = personal_mode_enabled
03-17 09:49:30.674  1243  3010 D MediaScanner: OK. ringtone is already exist in setting DB.
03-17 09:49:30.684  1243  3010 D MediaScannerService: !@done scanning volume internal
03-17 09:49:30.684  1243  3010 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
03-17 09:49:30.684  1022  1600 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
03-17 09:49:30.684  2633  2633 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2633) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 09:49:30.684  2633  2633 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2633) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-17 09:49:30.684  2633  2633 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2633) ACTION_MEDIA_SCANNER_FINISHED = Ignored
03-17 09:49:30.694  1483  1503 D TP/SmsProvider: query,matched:51, calling pid = 2420
03-17 09:49:30.694  1483  1503 D TP/SmsProvider: match 51:Elapsed time : 1.888 ms
03-17 09:49:30.704  3036  3036 E [0]UMC:UMCAdmin: No active admin owned by uid 10155
03-17 09:49:30.704  3036  3036 D [0]UMC:UMCAdmin: isContainer : 0
03-17 09:49:30.704  1022  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.704  1022  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:30.704  1022  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-17 09:49:30.704  3036  3036 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-17 09:49:30.704  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 09:49:30.704  1243  3010 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 09:49:30.714  3036  3036 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-17 09:49:30.714  3036  3036 D [0]UMC:CoreReceiver:  check PreETag 
03-17 09:49:30.714  1243  3010 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
03-17 09:49:30.724  2420  3076 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 09:49:30.734  1608  1618 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 09:49:30.734  1483  1483 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 09:49:30.734  1483  1483 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 09:49:30.734  1483  1483 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 09:49:30.734  1483  1483 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 09:49:30.734  1483  1483 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 09:49:30.734  1483  1483 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 09:49:30.734  1243  3010 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
03-17 09:49:30.754  1243  3010 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 09:49:30.754  1243  3010 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 09:49:30.754  1243  3010 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-17 09:49:30.754  1243  3010 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
03-17 09:49:30.754  1243  3010 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 09:49:30.764  1243  3010 D MediaScanner: Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 09:49:30.764  1511  1511 D Launcher.Model: reloadBadges entered.
03-17 09:49:30.764  1347  1347 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 09:49:30.764  1347  1347 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-17 09:49:30.774  1608  1624 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 09:49:30.774  1608  1624 D BadgeProvider: sendNotify, [notify] : null
03-17 09:49:30.774  1608  1624 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 09:49:30.774  1608  1624 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 09:49:30.774  1608  1624 D BadgeProvider: update, [UpdateCount] : 1
03-17 09:49:30.774  2420  3076 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 09:49:30.774  3036  3036 D [0]UMC:ByodSetupStarter: Container ID : 0
03-17 09:49:30.774  3087  3087 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-17 09:49:30.774  3036  3036 V [0]UMC:Utils: checkAppScreen() : com.sec.android.app.launcher
03-17 09:49:30.774  3036  3036 I [0]UMC:Core: shutdown
03-17 09:49:30.774  3036  3036 I art     : System.exit called, status: 0
03-17 09:49:30.774  3036  3036 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
03-17 09:49:30.774  1347  1347 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
03-17 09:49:30.784  1347  1347 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
03-17 09:49:30.784  2420  3120 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 09:49:30.794  2420  3076 D Mms/MessagingNotification: remove alarm
03-17 09:49:30.794  1243  3010 V MediaScanner: processDirectory :  /storage/emulated/0
03-17 09:49:30.804  1243  3010 D MediaScanner: Skipping:
03-17 09:49:30.804  1243  3010 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
03-17 09:49:30.804  3087  3087 D DSM     : [Lines:107] Normal booted
03-17 09:49:30.804  3087  3087 D DSM     : [Lines:114] Boot completed
03-17 09:49:30.814  1483  1503 D TP/SmsProvider: query,matched:0, calling pid = 2420
03-17 09:49:30.814  1483  1503 D TP/SmsProvider: match 0:Elapsed time : 1.166 ms
03-17 09:49:30.814  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.814  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.814  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.814  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.814  1243  3010 D MediaScanner: Skipping:
03-17 09:49:30.814  1243  3010 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-17 09:49:30.814  1243  3010 V MediaScanner: processDirectory :  /storage/extSdCard
03-17 09:49:30.814  1243  3010 W MediaScanner: Error opening directory, reason : Permission denied.
03-17 09:49:30.814  1243  3010 W MediaScanner: 7klwibgf7fxlKdCbid7
03-17 09:49:30.824  1243  3010 V MediaScanner:  prescan time: 35ms (DB items: 26)
03-17 09:49:30.824  1243  3010 V MediaScanner:     scan time: 26ms (Caching mode: true), (makeEntry time: 16ms ~61%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 09:49:30.824  1243  3010 V MediaScanner: postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 09:49:30.824  1243  3010 V MediaScanner:    total time: 64ms
03-17 09:49:30.824  1243  3010 V MediaScanner: checked files: 10  directories : 16  (I: 0, U: 0)
03-17 09:49:30.834  3123  3123 E Zygote  : MountEmulatedStorage()
03-17 09:49:30.834  3123  3123 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:30.834  3123  3123 E Zygote  : v2
03-17 09:49:30.834  3123  3123 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:30.834  1022  1500 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3123 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:30.834  1022  1500 I ActivityManager: Killing 2275:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
03-17 09:49:30.834  3123  3123 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:30.834  3123  3123 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:30.834  3123  3123 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:30.844  1243  3010 D MediaScannerService: !@done scanning volume external
03-17 09:49:30.844  2633  2633 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2633) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 09:49:30.844  2633  2633 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2633) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-17 09:49:30.844  2633  2633 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2633) ...
03-17 09:49:30.844  2633  2633 D FactoryTestApp: [Support$Values.getString](2633) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 09:49:30.844  2633  2633 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2633) mConnectionMode = gsm
03-17 09:49:30.844  2633  2633 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2633) Create IPCWriterToSecPhoneService
03-17 09:49:30.844  2633  2633 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2633)  
03-17 09:49:30.854  1022  1569 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3036)(adj 0) has died(40,667)
03-17 09:49:30.864  2420  3076 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 190.682552
03-17 09:49:30.864  1022  1382 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 09:49:30.864  1022  1382 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 09:49:30.864  1022  1382 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 09:49:30.864  1022  1022 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 09:49:30.864  1022  1022 I MotionRecognitionService: Plugged
03-17 09:49:30.864  1022  1022 I MotionRecognitionService: mGripSensorEnabled= false
03-17 09:49:30.874  3123  3123 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:30.874  3123  3123 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:30.874  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 09:49:30.874  1175  1175 D PowerUI : Cable  true --> true mBootCompleted : true
03-17 09:49:30.874  1175  1175 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-17 09:49:30.874  1446  1446 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 09:49:30.874  1446  1446 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 09:49:30.874  1790  1790 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 09:49:30.874  1790  1790 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 09:49:30.874  1790  1790 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 09:49:30.884  2653  2653 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 09:49:30.884  2653  2770 D HeadsetStateMachine: Disconnected process message: 10
03-17 09:49:30.884  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 09:49:30.884  1790  1790 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 09:49:30.884  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 09:49:30.884  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 09:49:30.884  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 09:49:30.884  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 09:49:30.884  1175  1175 D SViewCoverView: level :100 plugged : 2
03-17 09:49:30.884  1022  1504 I ActivityManager: Killing 1528:com.android.printspooler/u0a132 (adj 15): empty #31
03-17 09:49:30.884  1790  1790 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-17 09:49:30.894  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.894  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.894  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.894  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:30.894  1347  1347 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
03-17 09:49:30.894  2633  2633 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
03-17 09:49:30.904  1790  1790 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
03-17 09:49:30.904  1790  1790 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 09:49:30.904  1790  1790 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 09:49:30.904  1790  1790 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 09:49:30.904  1790  1790 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 09:49:30.904  1790  1790 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 09:49:30.904  1790  1790 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
03-17 09:49:30.914  3139  3139 E Zygote  : MountEmulatedStorage()
03-17 09:49:30.914  3139  3139 E Zygote  : v2
03-17 09:49:30.914  3139  3139 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:30.914  3139  3139 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:30.914  3139  3139 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:30.914  3139  3139 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:30.914  3139  3139 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:30.914  1022  2835 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3139 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:30.914  1022  2835 I ActivityManager: Killing 2335:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
03-17 09:49:30.924  3123  3123 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 09:49:30.924  1022  1504 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:30.924  1022  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:30.924  1022  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-17 09:49:30.934  1022  1569 D SettingsProvider: name = aw_daemon_service_key_version_check
03-17 09:49:30.934  1022  1569 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:30.934  1022  1569 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:30.934  1022  1569 D SettingsProvider: selectionArgs: false
03-17 09:49:30.934  1022  1569 D SettingsProvider: selectionArgs: 10157
03-17 09:49:30.934  1022  1569 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:30.934  1022  1569 D SettingsProvider: ret = -1
03-17 09:49:30.944  3139  3139 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:30.944  3139  3139 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:30.944  1347  1347 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-17 09:49:30.944  1347  1347 I SettingSearch/SearchIntentReceiver: search setting db init!!
03-17 09:49:30.944  1022  1569 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10157
03-17 09:49:30.954  1790  1790 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-17 09:49:30.954  2980  2980 E AffinityControl: AffinityControl: registerfunction enter
03-17 09:49:30.954  1347  1347 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-17 09:49:30.954  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 09:49:30.964  1347  3154 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
03-17 09:49:30.964  3139  3139 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 09:49:30.964  1790  1790 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
03-17 09:49:30.964  2633  2633 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2633) connected done
03-17 09:49:30.964  2633  2633 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2633) Send Response Message to SecPhone
03-17 09:49:30.964  2633  2633 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2633) Response ��
03-17 09:49:30.974  1790  1790 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 09:49:30.974  1790  1790 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 09:49:30.974  1790  1790 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
03-17 09:49:30.974  1790  1790 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-17 09:49:30.984  1790  1790 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
03-17 09:49:30.984  1790  1790 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 09:49:30.984   314  1079 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 09:49:30.984  1790  1790 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458204570992
03-17 09:49:30.984  1790  1790 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458226140000
03-17 09:49:30.984  1790  1790 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-17 09:49:30.984  1790  1790 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
03-17 09:49:30.994  1790  1790 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458226140000
03-17 09:49:30.994  2633  2633 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2633) Send BOOTING COMPLETED done
03-17 09:49:31.004  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.004  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.004  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.004  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.024  1022  1047 W libprocessgroup: failed to open /acct/uid_10045/pid_2275/cgroup.procs: No such file or directory
03-17 09:49:31.024  1022  1047 W libprocessgroup: failed to open /acct/uid_10132/pid_1528/cgroup.procs: No such file or directory
03-17 09:49:31.024  1022  1047 W libprocessgroup: failed to open /acct/uid_10110/pid_2335/cgroup.procs: No such file or directory
03-17 09:49:31.034  3160  3160 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.034  3160  3160 E Zygote  : v2
03-17 09:49:31.034  3160  3160 I libpersona: KNOX_SDCARD checking this for 10146
03-17 09:49:31.034  3160  3160 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:31.034  3160  3160 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:31.034  3123  3123 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 09:49:31.034  3160  3160 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:31.034  3160  3160 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 09:49:31.034  1022  1569 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3160 uid=10146 gids={50146, 9997} abi=armeabi-v7a
03-17 09:49:31.044  2980  2980 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 09:49:31.044  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.044  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.044  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.044  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.054  1790  1790 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 59
03-17 09:49:31.054  1790  1790 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458226140000
03-17 09:49:31.054   306   306 I art     : Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 857us total 22.479ms
03-17 09:49:31.054  1022  1271 E PersonaManagerService: inState():  stateMachine is null !!
03-17 09:49:31.054  1022  1271 I PersonaManagerService: PersonaId don't exist
03-17 09:49:31.054  1022  1271 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 09:49:31.064  3160  3160 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:31.064  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
03-17 09:49:31.064  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
03-17 09:49:31.064  3160  3160 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:31.064  3123  3123 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
03-17 09:49:31.074   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.929ms
03-17 09:49:31.084  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-17 09:49:31.084   314  1079 D AT_Distributor: SetAtdStatus(), 1_1_0
03-17 09:49:31.084   314  1079 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 09:49:31.094   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 17.555ms
03-17 09:49:31.114  3178  3178 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.114  3178  3178 E Zygote  : v2
03-17 09:49:31.114  3178  3178 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:31.114  3178  3178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:31.114  3178  3178 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:31.114  1022  1504 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3178 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:31.114  3178  3178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:31.114  3178  3178 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 09:49:31.114  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 09:49:31.124  1022  1271 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-17 09:49:31.124  3123  3123 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-17 09:49:31.134  1022  1271 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 09:49:31.134  3123  3123 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-17 09:49:31.134  1022  1271 W ActivityManager: mDVFSHelper.acquire()
03-17 09:49:31.144  1022  1271 D FocusedStackFrame: Set to : 0
03-17 09:49:31.144  1022  1271 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 09:49:31.144  1022  1271 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 09:49:31.144  1022  1271 D InputDispatcher: Focused application set to: xxxx
03-17 09:49:31.144  1022  1271 D InputDispatcher: Focus left window: 1511
03-17 09:49:31.144  2980  2980 D AndroidRuntime: Shutting down VM
03-17 09:49:31.144  1022  1053 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 09:49:31.144  1022  1053 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 09:49:31.154  3178  3178 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:31.154  3178  3178 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:31.154  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.154  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.154  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.154  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.154  1022  1053 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 09:49:31.154  1022  1053 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 09:49:31.154  1022  1053 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 09:49:31.154  1022  1053 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 09:49:31.164   259   259 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 09:49:31.164  1511  1511 D Launcher.HomeView: onPause
03-17 09:49:31.164  1511  1511 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 09:49:31.174  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 09:49:31.174  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 09:49:31.174  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:31.174  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:31.174  3195  3195 I libpersona: KNOX_SDCARD checking this for 10082
03-17 09:49:31.174  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:31.174  3195  3195 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:31.174  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:31.174  3195  3195 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.174  3195  3195 E Zygote  : v2
03-17 09:49:31.174  3195  3195 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:31.174  3195  3195 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:31.174  1022  1504 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3195 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
03-17 09:49:31.174  3195  3195 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 09:49:31.184  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.184  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.184  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.184  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.184  1790  1790 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-17 09:49:31.184  1790  1790 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
03-17 09:49:31.194  3205  3205 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.194  3205  3205 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:31.194  3205  3205 E Zygote  : v2
03-17 09:49:31.194  3205  3205 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:31.194  1022  1504 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3205 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:31.204  2653  2773 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-17 09:49:31.194  1022  1504 I ActivityManager: Killing 1635:com.google.android.partnersetup/u0a14 (adj 15): empty #31
03-17 09:49:31.204  3205  3205 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:31.204  3205  3205 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:31.204  3205  3205 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:31.204  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.204  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.204  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.204  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.214  3195  3195 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:31.214  3195  3195 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:31.224  3221  3221 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.224  3221  3221 I libpersona: KNOX_SDCARD checking this for 10161
03-17 09:49:31.224  3221  3221 E Zygote  : v2
03-17 09:49:31.224  3221  3221 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:31.224  3221  3221 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:31.224  3221  3221 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:31.224  1022  1504 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3221 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 09:49:31.224  3221  3221 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 09:49:31.234  3205  3205 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:31.234  3205  3205 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:31.244  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.244  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.244  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.244  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.254  3178  3178 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 09:49:31.254  3237  3237 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.254  3237  3237 E Zygote  : v2
03-17 09:49:31.254  3237  3237 I libpersona: KNOX_SDCARD checking this for 10167
03-17 09:49:31.254  3237  3237 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:31.254  3237  3237 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:31.264  1022  1569 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3237 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 09:49:31.264  3237  3237 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:31.264  3237  3237 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 09:49:31.274  3221  3221 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:31.274  3221  3221 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:31.274   299   299 E USB_UICC: Timeout! No signal received. Retry num = 30
03-17 09:49:31.284  2653  2773 D BluetoothMediaBrowser: no now playing list
03-17 09:49:31.284  2653  2773 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
03-17 09:49:31.304  3237  3237 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:31.304  3237  3237 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:31.304  1022  1509 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 09:49:31.304  1022  1509 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 09:49:31.304  1022  1509 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 09:49:31.314  1022  1051 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 09:49:31.314  1022  1047 W libprocessgroup: failed to open /acct/uid_10014/pid_1635/cgroup.procs: No such file or directory
03-17 09:49:31.324  1022  1509 D PersonaManager: isKioskContainerExistOnDevice
03-17 09:49:31.324   318   318 I ServiceManager: Waiting for service AtCmdFwd...
03-17 09:49:31.334  1022  1022 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 09:49:31.334  1022  1022 D SensorService: [SO] activate (ident=0xb7f32b90, enabled=0)
03-17 09:49:31.334  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-17 09:49:31.344  1022  1022 D SensorManager: unregisterListener ::   
03-17 09:49:31.344  1022  1022 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-17 09:49:31.344  1022  1022 D SensorService: [SO] changed settle time [1]
03-17 09:49:31.344  1022  1022 D SensorService: [SO] setDelay [66000000]
03-17 09:49:31.344  1022  1022 D SensorService: [SO] activate (ident=0xb7f32b90, enabled=1)
03-17 09:49:31.344  1022  1022 D SensorService: [SO] AR_init
03-17 09:49:31.344  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-17 09:49:31.354  1022  1022 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-17 09:49:31.354  2980  2980 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 09:49:31.404   299   299 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 09:49:31.404   299   299 E USB_UICC: usb_uicc_init_qmi failed ! 
03-17 09:49:31.404   299   299 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 09:49:31.404   299   299 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-17 09:49:31.424  1022  1045 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 09:49:31.444  1511  1511 V ActivityThread: updateVisibility : ActivityRecord{3179cc20 token=android.os.BinderProxy@13f9efc9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,03-17 09:49:31.444  1511  1511 D Launcher.HomeView: onStop
,03-17 09:49:31.454  1511  1511 V ActivityThread: updateVisibility : ActivityRecord{3179cc20 token=android.os.BinderProxy@13f9efc9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,03-17 09:49:31.454  1511  1511 D Launcher: onTrimMemory. Level: 20
,03-17 09:49:31.474  3205  3205 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 09:49:31.484  1022  1048 I ActivityManager: Waited long enough for: ServiceRecord{180f6e8 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-17 09:49:31.494  1022  1045 D SensorService: [SO] -0.460 0.211 9.883
03-17 09:49:31.494  1022  1045 D SensorService: [SO] [100 -> 255]
,03-17 09:49:31.534  3195  3195 E UpdateRequestReceiver: ignoring update request
,03-17 09:49:31.544  3195  3195 E UpdateRequestReceiver: ignoring update request
,03-17 09:49:31.594  3237  3237 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-17 09:49:31.604  3195  3195 E UpdateRequestReceiver: ignoring update request
,03-17 09:49:31.604  3237  3237 I LibraryLoader: Loading: webviewchromium
,03-17 09:49:31.614  3237  3237 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6524-6529)
03-17 09:49:31.614  3237  3237 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 09:49:31.634  3221  3266 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 09:49:31.634  3221  3266 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 09:49:31.654  3178  3178 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 09:49:31.664  3195  3195 E UpdateRequestReceiver: ignoring update request
,03-17 09:49:31.664  3195  3195 E UpdateRequestReceiver: ignoring update request
,03-17 09:49:31.684  3221  3266 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 09:49:31.694  3195  3195 E UpdateRequestReceiver: ignoring update request
,03-17 09:49:31.694  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.694  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.694  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:31.694  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:31.694  3237  3237 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {25280778}
,03-17 09:49:31.704  3237  3237 I LibraryLoader: Expected native library version number "",actual native library version number "",
03-17 09:49:31.704  3237  3237 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 09:49:31.714  3278  3278 E Zygote  : MountEmulatedStorage()
03-17 09:49:31.714  3278  3278 E Zygote  : v2
03-17 09:49:31.714  3278  3278 I libpersona: KNOX_SDCARD checking this for 10088
03-17 09:49:31.714  3278  3278 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:31.714  3278  3278 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:31.724  1022  1035 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3278 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 09:49:31.724  3278  3278 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:31.724  3278  3278 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 09:49:31.734  3237  3237 I BrowserStartupController: Initializing chromium process, renderers=0
,03-17 09:49:31.734  3237  3237 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:49:31.744  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 09:49:31.744  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
03-17 09:49:31.744  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-17 09:49:31.754  3237  3237 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-17 09:49:31.754  3237  3237 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,03-17 09:49:31.754  3237  3237 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,03-17 09:49:31.774   259   441 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-17 09:49:31.774   259  1044 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-17 09:49:31.784  3278  3278 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:31.784  3278  3278 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:31.804  3237  3237 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 09:49:31.804  3237  3237 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 09:49:31.804  3237  3237 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 09:49:31.804  3237  3237 I Adreno-EGL: Local Branch: 
03-17 09:49:31.804  3237  3237 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 09:49:31.804  3237  3237 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 09:49:31.804  3237  3237 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 09:49:31.834  3205  3205 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 09:49:31.844  3205  3205 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 09:49:31.854  3221  3266 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 09:49:31.854  3221  3266 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29660a50: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 09:49:31.854  3221  3266 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 09:49:31.954   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 09:49:31.954   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 09:49:31.964  3221  3221 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 09:49:32.024  3205  3205 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-17 09:49:32.024  3205  3205 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 09:49:32.024  3205  3205 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,03-17 09:49:32.024  3205  3205 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 09:49:32.024  3178  3178 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-17 09:49:32.024  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
03-17 09:49:32.024  3178  3178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
03-17 09:49:32.034  1022  1600 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:32.034  1022  1600 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-17 09:49:32.034  1022  1600 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
03-17 09:49:32.034  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.034  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.034  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.034  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.044  3319  3319 E Zygote  : MountEmulatedStorage()
03-17 09:49:32.044  3319  3319 E Zygote  : v2
03-17 09:49:32.044  3319  3319 I libpersona: KNOX_SDCARD checking this for 10088
03-17 09:49:32.044  3319  3319 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:32.054  3237  3305 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
03-17 09:49:32.054  1022  1600 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3319 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 09:49:32.054  1022  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:32.054  1022  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:32.054  1022  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 09:49:32.054  3319  3319 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:32.054  3319  3319 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:32.064  3319  3319 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 09:49:32.064  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
03-17 09:49:32.064  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
03-17 09:49:32.064  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-17 09:49:32.064  3237  3237 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-17 09:49:32.074  1175  1175 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-17 09:49:32.074  1022  1504 I ActivityManager: Killing 2406:com.sec.modem.settings/1000 (adj 15): empty #31
,03-17 09:49:32.084  3319  3319 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:32.084  3319  3319 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:32.084  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 09:49:32.084  3178  3178 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-17 09:49:32.084  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-17 09:49:32.094  3178  3178 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-17 09:49:32.094  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-17 09:49:32.094  3178  3178 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
03-17 09:49:32.094  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-17 09:49:32.104  3178  3178 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
03-17 09:49:32.104  1175  1175 D OverheatReceiver: into the SAFE_MODE_ACTION
03-17 09:49:32.104  1175  1175 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-17 09:49:32.104  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-17 09:49:32.104  1175  1175 D OverheatReceiver: isSafeMode = false
03-17 09:49:32.104  3178  3291 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-17 09:49:32.114  1483  1483 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-17 09:49:32.114  1022  1035 D SettingsProvider: name = internet_call_settings_visibility
03-17 09:49:32.114  1022  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.114  1022  1035 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:32.114  1022  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.114  1022  1035 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:32.114  1022  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.114  1022  1035 D SettingsProvider: selectionArgs: false
03-17 09:49:32.114  1022  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.114  1022  1035 D SettingsProvider: selectionArgs: 1001
03-17 09:49:32.114  1022  1035 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:32.114  1022  1035 D SettingsProvider: ret = -1
03-17 09:49:32.114  1483  1483 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 09:49:32.124  3341  3341 E Zygote  : MountEmulatedStorage(),
03-17 09:49:32.124  3341  3341 E Zygote  : v2
03-17 09:49:32.124  3341  3341 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:32.124  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
03-17 09:49:32.124  3341  3341 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:32.124  3341  3341 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:32.134  1022  1382 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3341 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 09:49:32.134  3237  3237 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:49:32.134  3341  3341 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 09:49:32.134  3178  3291 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 09:49:32.134  3341  3341 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:32.134  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
03-17 09:49:32.134  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
03-17 09:49:32.134  3237  3237 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 09:49:32.154  3237  3237 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 09:49:32.154  3237  3237 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 09:49:32.154  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-17 09:49:32.154  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-17 09:49:32.164  3237  3237 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 09:49:32.164  3178  3291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
03-17 09:49:32.164  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-17 09:49:32.174  1022  1142 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:32.174  1022  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:32.174  1022  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 09:49:32.174  3237  3237 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 09:49:32.174  3237  3237 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:49:32.174  1459  1459 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-17 09:49:32.184  3341  3341 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:32.184  3341  3341 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:32.184  1022  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:32.184  1022  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:32.184  1022  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 09:49:32.194  3178  3178 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 09:49:32.194  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-17 09:49:32.194  1022  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:32.194  1022  1510 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:32.194  1022  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 09:49:32.204  1022  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_2406/cgroup.procs: No such file or directory
,03-17 09:49:32.214  1022  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.214  1022  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.214  1022  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.214  1022  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.214  1022  1509 E Tethering: No numeric data
,03-17 09:49:32.214  1022  1510 E Tethering: No numeric data
,03-17 09:49:32.214  1022  1569 E Tethering: No numeric data
,03-17 09:49:32.214  1022  1509 E Tethering: No numeric data
,03-17 09:49:32.224  1022  1034 E Tethering: No numeric data
,03-17 09:49:32.224  1022  1510 E Tethering: No numeric data
,03-17 09:49:32.224  3361  3361 E Zygote  : MountEmulatedStorage()
03-17 09:49:32.224  3361  3361 E Zygote  : v2
03-17 09:49:32.224  3361  3361 I libpersona: KNOX_SDCARD checking this for 10052
03-17 09:49:32.224  3361  3361 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:32.224  3361  3361 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 09:49:32.224  1022  1142 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3361 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-17 09:49:32.234  3361  3361 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:32.234  3361  3361 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 09:49:32.234  1022  1142 I ActivityManager: Killing 2438:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,03-17 09:49:32.244  3237  3370 D OpenGLRenderer: Render dirty regions requested: true
,03-17 09:49:32.244  1022  1142 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 09:49:32.244  1022  1142 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 09:49:32.244  1022  1022 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 09:49:32.244  1022  1142 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 09:49:32.244  1022  1022 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 09:49:32.254  3237  3237 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 09:49:32.254  3237  3237 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 09:49:32.264  3361  3361 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:32.264  3361  3361 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:32.264   291   291 E SMD     : DCD OFF
,03-17 09:49:32.274  3178  3291 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-17 09:49:32.324   318   318 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 09:49:32.354  1022  1047 W libprocessgroup: failed to open /acct/uid_10127/pid_2438/cgroup.procs: No such file or directory
,03-17 09:49:32.364  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.364  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.364  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.364  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.374  3380  3380 E Zygote  : MountEmulatedStorage(),
03-17 09:49:32.374  3380  3380 E Zygote  : v2
03-17 09:49:32.374  3380  3380 I libpersona: KNOX_SDCARD checking this for 10008
03-17 09:49:32.374  3380  3380 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:32.374  3380  3380 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:32.384  1022  1510 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3380 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 09:49:32.384  3380  3380 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:32.384  3380  3380 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 09:49:32.394  3278  3278 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 09:49:32.404  3380  3380 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:32.404  3380  3380 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:32.414  1347  3154 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 09:49:32.414  1347  3154 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 09:49:32.424  3341  3341 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-17 09:49:32.424  3278  3278 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
03-17 09:49:32.424  3341  3341 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 09:49:32.424  1022  1500 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:32.424  1022  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:32.424  1022  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 09:49:32.444  3341  3341 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-17 09:49:32.444  3341  3401 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 09:49:32.444  3341  3341 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 09:49:32.444   259   259 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 09:49:32.444  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.444  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.444  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.444  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.454  3341  3341 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-17 09:49:32.454  3341  3341 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-17 09:49:32.454  3341  3341 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-17 09:49:32.454  3341  3341 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,03-17 09:49:32.454  3341  3341 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 09:49:32.454  3341  3341 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 09:49:32.464  3341  3341 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-17 09:49:32.464  3341  3341 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!,
,03-17 09:49:32.464  3341  3341 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-17 09:49:32.474  3408  3408 E Zygote  : MountEmulatedStorage()
03-17 09:49:32.474  1022  1600 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3408 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
03-17 09:49:32.474  3408  3408 E Zygote  : v2
03-17 09:49:32.474  3408  3408 I libpersona: KNOX_SDCARD checking this for 10014
03-17 09:49:32.474  1022  1504 D InputDispatcher: Focus entered window: 3237
03-17 09:49:32.474  3408  3408 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:32.474  3408  3408 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:32.484  3408  3408 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:32.484  3408  3408 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 09:49:32.484  1022  1053 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 09:49:32.484  1022  1053 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 09:49:32.484  3237  3237 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 09:49:32.484  3237  3370 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 09:49:32.494  3278  3278 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-17 09:49:32.494  3237  3370 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 09:49:32.494  3237  3370 D OpenGLRenderer: Enabling debug mode 0
,03-17 09:49:32.494  1459  1459 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-17 09:49:32.504   306   306 I art     : Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 666us total 30.562ms
,03-17 09:49:32.514  1022  1500 D LocationManagerService: getProviders()=[passive]
03-17 09:49:32.514  3408  3408 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:32.514  3408  3408 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:32.524   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 963us total 18.677ms
,03-17 09:49:32.534  1022  1569 E Tethering: No numeric data
,03-17 09:49:32.534  1022  2835 E Tethering: No numeric data
,03-17 09:49:32.534  1022  1271 E Tethering: No numeric data
,03-17 09:49:32.544   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 810us total 19.073ms
,03-17 09:49:32.544  3341  3401 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-17 09:49:32.564  3178  3291 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-17 09:49:32.564  3341  3401 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-17 09:49:32.634  3278  3278 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-17 09:49:32.644  1022  1504 E Tethering: No numeric data
,03-17 09:49:32.654  1022  1034 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 09:49:32.654  1022  3433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 09:49:32.654  1175  1175 I StatusBar: Icon Only
,03-17 09:49:32.654  1175  1175 D PanelView: There is/are notification(s) 
,03-17 09:49:32.664  1022  3436 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 09:49:32.664  3237  3237 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@10c3d4a7 time:37589
,03-17 09:49:32.684  1022  1053 I ActivityManager: Displayed Component not be shown by security: +1s441ms
,03-17 09:49:32.684  1022  1053 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@7,
,03-17 09:49:32.684  1022  1053 W ActivityManager: mDVFSHelper.release()
,03-17 09:49:32.684  1022  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1303e42f u0 com.test.thalitest/.MainActivity t11} time:37605
03-17 09:49:32.684  1022  1048 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 09:49:32.714  3278  3278 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-17 09:49:32.714  3341  3350 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 09:49:32.714  3341  3350 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 09:49:32.724  3341  3350 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 09:49:32.734  3341  3349 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 09:49:32.734  3341  3349 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 09:49:32.734  3341  3349 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 09:49:32.764  3341  3401 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 09:49:32.774  3341  3401 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 09:49:32.774  1022  2835 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:32.774  1022  2835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:32.774  1022  2835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 09:49:32.804  3178  3291 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 09:49:32.804  3178  3291 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-17 09:49:32.804  3178  3291 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 09:49:32.804  1022  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:32.804  1022  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:32.814  1022  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 09:49:32.824  1022  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.824  1022  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.824  1022  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:32.824  1022  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:32.834  1022  1510 V VibratorService: hasVibrator - useVibetonz: true
,03-17 09:49:32.834  3278  3278 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-17 09:49:32.844  3450  3450 E Zygote  : MountEmulatedStorage()
03-17 09:49:32.844  3450  3450 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:32.844  3450  3450 E Zygote  : v2
03-17 09:49:32.844  3450  3450 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:32.844  3450  3450 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:32.844  1022  1382 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3450 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 09:49:32.844  3450  3450 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:32.844  3450  3450 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:32.854  1022  1382 I ActivityManager: Killing 2470:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 09:49:32.854  1022  1382 I ActivityManager: Killing 2453:com.sec.tcpdumpservice/1000 (adj 15): empty #32
,03-17 09:49:32.864  3341  3401 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 09:49:32.874  3278  3278 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 09:49:32.874  3341  3401 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-17 09:49:32.874  3361  3443 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 09:49:32.874  1832  1832 I SamsungIME: getCurrentCandidateView
03-17 09:49:32.874  1022  1504 I ActivityManager: Killing 2513:com.wsomacp/u0a23 (adj 15): empty #31
,03-17 09:49:32.884  1022  1600 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:32.884  1022  1600 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:32.884  1022  1600 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 09:49:32.884  3341  3401 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-17 09:49:32.904   285   697 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
,03-17 09:49:32.904   285   697 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 09:49:32.904   285   697 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 09:49:32.904   285   697 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 09:49:32.904   285   697 I str_params: key: 'call_forwarding' value: ''
,03-17 09:49:32.904  1993  1993 V InCall  : ProximitySensor -  - screenonImmediately: false
,03-17 09:49:32.904  1993  1993 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-17 09:49:32.904  1347  3154 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 09:49:32.914  1993  1993 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-17 09:49:32.914  3450  3450 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:32.914  3450  3450 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:32.914  1022  1510 V VibratorService: hasVibrator - useVibetonz: true
,03-17 09:49:32.924  1993  1993 D ScoverManager: serviceVersion : 16908288
,03-17 09:49:32.924  1022  1142 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 09:49:32.924  1993  1993 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-17 09:49:32.924  1459  1459 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-17 09:49:32.924  1022  1569 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 09:49:32.924  1993  1993 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-17 09:49:32.924  1993  1993 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-17 09:49:32.934  1993  1993 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
03-17 09:49:32.934  1022  1509 V VibratorService: hasVibrator - useVibetonz: true
03-17 09:49:32.934  1993  1993 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-17 09:49:32.934  1993  1993 I InCall  : CallSContextMotion - stopPutDownListening
,03-17 09:49:32.934  1993  1993 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 09:49:32.944  1022  2835 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 09:49:32.944  1993  1993 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-17 09:49:32.964  1347  3154 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 09:49:32.964  3341  3401 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 09:49:32.984  3341  3401 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 09:49:32.984  1022  1022 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 09:49:32.994  3341  3401 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 09:49:32.994  3341  3401 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-17 09:49:32.994  3341  3401 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 09:49:32.994  3341  3402 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-17 09:49:32.994   259  1044 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-17 09:49:32.994   259   447 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-17 09:49:32.994  3341  3402 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 09:49:33.004  3450  3450 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-17 09:49:33.004  3341  3402 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0],
03-17 09:49:33.004  1175  1175 D PhoneStatusBarView: setCallBackground:0
03-17 09:49:33.004  3341  3402 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 09:49:33.004  3341  3402 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 09:49:33.004  3341  3402 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 09:49:33.014  3341  3401 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
03-17 09:49:33.014  3278  3278 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
03-17 09:49:33.014  1022  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_2453/cgroup.procs: No such file or directory
03-17 09:49:33.014  1022  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_2470/cgroup.procs: No such file or directory
03-17 09:49:33.014  1022  1047 W libprocessgroup: failed to open /acct/uid_10023/pid_2513/cgroup.procs: No such file or directory
,03-17 09:49:33.014  3341  3401 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/09:49:33
,03-17 09:49:33.014  3341  3401 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-17 09:49:33.014  3341  3401 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-17 09:49:33.014  3341  3402 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 09:49:33.024  3341  3402 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-17 09:49:33.024  3341  3402 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 09:49:33.024  3341  3402 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 09:49:33.034  3450  3450 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 09:49:33.034  3450  3450 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 09:49:33.034  3450  3450 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 09:49:33.034  3237  3237 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 09:49:33.044  1022  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.044  1022  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.044  1022  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.044  1022  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.054  1022  1382 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 09:49:33.054  3473  3473 E Zygote  : MountEmulatedStorage()
03-17 09:49:33.054  3473  3473 E Zygote  : v2
,03-17 09:49:33.054  3473  3473 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:33.054  3473  3473 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:33.054  3473  3473 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:33.054  3473  3473 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 09:49:33.054  1022  1509 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3473 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:33.064  3473  3473 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:33.064  1993  1993 D VideoCallManager: Instantiating VideoCallManager
03-17 09:49:33.074  3341  3402 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 09:49:33.074  3221  3221 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 09:49:33.084  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 09:49:33.084  1022  1569 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 09:49:33.094  1993  1993 I GFX construct_block_size_descriptor_2d second part: took 2.573907ms for 0*0 texture 0
,03-17 09:49:33.094  3473  3473 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:33.094  3473  3473 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:33.104  1993  1993 I GFX generate_partition_tables: took 5.171875ms for 0*0 texture 0
,03-17 09:49:33.104  1993  1993 I GFX raster: took 11.642449ms for 176*144 texture 0
03-17 09:49:33.104  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb79cdf40 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb79cd7e8 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 09:49:33.114  1832  1832 D SamsungIME: Dismiss ExpandCandiate
,03-17 09:49:33.114  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-17 09:49:33.114  1993  1993 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 09:49:33.114  1993  1993 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 09:49:33.114  1993  1993 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 09:49:33.114  1993  1993 I Adreno-EGL: Local Branch: 
03-17 09:49:33.114  1993  1993 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 09:49:33.114  1993  1993 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 09:49:33.114  1993  1993 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 09:49:33.144  1993  1993 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 09:49:33.154  1993  1993 I glCompressedTexImage2D: took 0.441407ms for 320*61440 texture 37809,
,03-17 09:49:33.164  1022  1600 I AudioService: getStreamVolume 3 index 0
,03-17 09:49:33.164  1993  1993 I draw setup: took 11.743074ms for 320*240 texture 37809
,03-17 09:49:33.164  1993  1993 E GFX GPU raster: drawn
,03-17 09:49:33.164  1993  1993 I GFX GPU raster ASTC: took 43.513023ms for 320*240 texture 12
,03-17 09:49:33.164  1993  1993 I GFX raster: took 43.598127ms for 320*240 texture 0
03-17 09:49:33.164  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb79c9ef8 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb79cde70 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 09:49:33.164  3361  3361 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-17 09:49:33.174  3341  3402 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-17 09:49:33.184  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 09:49:33.184  1993  1993 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 09:49:33.184  1993  1993 I glCompressedTexImage2D: took 0.377344ms for 480*122880 texture 37813,
03-17 09:49:33.184  1993  1993 I draw setup: took 0.917396ms for 480*640 texture 37813
03-17 09:49:33.184  1993  1993 E GFX GPU raster: drawn,
03-17 09:49:33.184  1022  1500 I art     : Explicit concurrent mark sweep GC freed 25811(1365KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 22MB/33MB, paused 2.880ms total 168.364ms
,03-17 09:49:33.194  1993  1993 I GFX GPU raster ASTC: took 8.997188ms for 480*640 texture 12
,03-17 09:49:33.194  1993  1993 I GFX raster: took 9.113386ms for 480*640 texture 0
03-17 09:49:33.194  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb79cde70 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7bff6e0 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 09:49:33.214  3237  3489 D jxcore_app_log: JniHelper::setJavaVM(0xb7622448), pthread_self() = -1211176768,
,03-17 09:49:33.224  3237  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 09:49:33.224  3237  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 09:49:33.224  3237  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 09:49:33.224  3237  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 09:49:33.224  3237  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 09:49:33.224  3237  3489 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f8efa2 added. We now have 1 listener(s)
,03-17 09:49:33.224  3341  3401 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 09:49:33.224  3237  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,03-17 09:49:33.224  3237  3489 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,03-17 09:49:33.234  3237  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-17 09:49:33.234  3237  3489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-17 09:49:33.234  3237  3489 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 09:49:33.234  1832  1832 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 09:49:33.234  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: MANUFACTURER_DATA
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 09:49:33.234  3237  3489 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@111a8d69 added. We now have 1 listener(s)
03-17 09:49:33.234  3237  3489 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 09:49:33.234  1993  1993 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 09:49:33.234  3361  3361 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
03-17 09:49:33.234  3361  3361 I ContactLabelSupplier: get() : Execute runnable (UI thread)
,03-17 09:49:33.234  1993  1993 I glCompressedTexImage2D: took 0.355520ms for 440*116864 texture 37809
,03-17 09:49:33.234  1993  1993 I draw setup: took 0.897760ms for 440*330 texture 37809
03-17 09:49:33.234  1993  1993 E GFX GPU raster: drawn
,03-17 09:49:33.244  3361  3443 I ContactLabelSupplier: get() : OptedIn = false
,03-17 09:49:33.244  1993  1993 I GFX GPU raster ASTC: took 5.107343ms for 440*330 texture 12
03-17 09:49:33.244  1993  1993 I GFX raster: took 5.196407ms for 440*330 texture 0
03-17 09:49:33.244  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c0fa08 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb7bfafa8 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 09:49:33.264  3237  3489 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 09:49:33.274  3237  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 09:49:33.274  3237  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 09:49:33.274  3237  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 09:49:33.274  3237  3489 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 09:49:33.274  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 09:49:33.274  1993  1993 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 09:49:33.274  1993  1993 I glCompressedTexImage2D: took 0.460782ms for 480*163840 texture 37811
03-17 09:49:33.274  1993  1993 I draw setup: took 0.803333ms for 480*640 texture 37811
03-17 09:49:33.274  1993  1993 E GFX GPU raster: drawn
,03-17 09:49:33.274  3237  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 09:49:33.284  1993  1993 I GFX GPU raster ASTC: took 6.134219ms for 480*640 texture 12
03-17 09:49:33.284  1993  1993 I GFX raster: took 6.211459ms for 480*640 texture 0
03-17 09:49:33.284  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7bf7e98 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7bf8028 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 09:49:33.284  1347  3154 D ScoverManager: serviceVersion : 16908288
03-17 09:49:33.284  3237  3489 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
03-17 09:49:33.284  3473  3473 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 09:49:33.284  3473  3473 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 09:49:33.294  3473  3473 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 09:49:33.294  1022  2835 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 09:49:33.294  3237  3489 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 09:49:33.294  3237  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 09:49:33.294  3237  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 09:49:33.294  3237  3489 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 09:49:33.294  3237  3489 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 09:49:33.294  3237  3489 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 09:49:33.294  3237  3489 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 09:49:33.294  3237  3489 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 09:49:33.294  3237  3489 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 09:49:33.294  3237  3489 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 09:49:33.304  3237  3237 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 09:49:33.304  3237  3237 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 09:49:33.324  3473  3483 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 09:49:33.324  1022  1569 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 09:49:33.324   318   318 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 09:49:33.324  3341  3401 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-17 09:49:33.334  1022  1271 I AudioService: getStreamVolume 3 index 0
03-17 09:49:33.334  1022  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:33.334  1022  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:33.334  1022  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 09:49:33.334  1022  1271 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 09:49:33.344  3450  3450 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 09:49:33.344  3450  3450 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 09:49:33.344  3450  3450 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 09:49:33.344  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 09:49:33.354  2739  2808 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 09:49:33.354  1993  1993 I GFX construct_block_size_descriptor_2d second part: took 2.481197ms for 0*0 texture 0
,03-17 09:49:33.354  1022  1382 I ActivityManager: Killing 2555:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,03-17 09:49:33.364  1993  1993 I GFX generate_partition_tables: took 7.528178ms for 0*0 texture 0
03-17 09:49:33.364  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.364  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.364  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.364  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.364  1993  1993 I GFX raster: took 11.954428ms for 176*144 texture 0
,03-17 09:49:33.364  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb79cd848 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7bfafa8 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 09:49:33.374  3506  3506 E Zygote  : MountEmulatedStorage()
03-17 09:49:33.374  3506  3506 E Zygote  : v2
03-17 09:49:33.374  3506  3506 I libpersona: KNOX_SDCARD checking this for 10055
03-17 09:49:33.374  3506  3506 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:33.374  3506  3506 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:33.374  3506  3506 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:33.374  3506  3506 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:33.384  1832  1832 I SamsungIME: getDebugLevel  : 0x4f4c
03-17 09:49:33.384  1022  1600 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3506 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,03-17 09:49:33.384  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 09:49:33.384  3278  3278 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,03-17 09:49:33.384  1993  1993 I GFX construct_block_size_descriptor_2d second part: took 2.384844ms for 0*0 texture 0
,03-17 09:49:33.394  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.394  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.394  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.394  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.394  1993  1993 I GFX generate_partition_tables: took 6.197811ms for 0*0 texture 0
,03-17 09:49:33.404  1993  1993 I GFX raster: took 10.867812ms for 176*144 texture 0
03-17 09:49:33.404  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c23f80 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7bfe4a0 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 09:49:33.404  1993  1993 D ScoverManager: registerListener
,03-17 09:49:33.404  1022  1569 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 09:49:33.404  3523  3523 E Zygote  : MountEmulatedStorage()
03-17 09:49:33.404  3523  3523 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:33.404  3523  3523 E Zygote  : v2
03-17 09:49:33.404  3523  3523 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:33.404  3523  3523 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:33.414  1022  1600 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3523 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 09:49:33.414  1022  1600 I ActivityManager: Killing 2578:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,03-17 09:49:33.414  1022  1271 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 09:49:33.414  1022  1271 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@16c8be9f, pid : 1993, uid : 1001, type : 1
,03-17 09:49:33.414  1832  1832 I SamsungIME: KeybaordView init() : load resources
,03-17 09:49:33.414  3523  3523 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:33.414  3523  3523 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:33.424  3341  3401 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 09:49:33.434  1993  1993 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 09:49:33.444  3506  3506 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:33.444  3506  3506 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:33.444  3523  3523 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:33.444  3523  3523 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:33.454  1022  2775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 09:49:33.474  3361  3444 I Velvet.VelvetFactory: refreshing search history.
,03-17 09:49:33.474  1022  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.474  1022  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.474  1022  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.474  1022  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.484  3237  3253 W art     : Suspending all threads took: 12.243ms
,03-17 09:49:33.494  3237  3253 I art     : Background sticky concurrent mark sweep GC freed 24180(1614KB) AllocSpace objects, 6(96KB) LOS objects, 8% free, 7MB/7MB, paused 13.800ms total 82.727ms
,03-17 09:49:33.494  1022  1142 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3544 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-17 09:49:33.494  1022  1142 I ActivityManager: Killing 2391:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 09:49:33.494  3544  3544 E Zygote  : MountEmulatedStorage()
03-17 09:49:33.494  3544  3544 I libpersona: KNOX_SDCARD checking this for 10090
03-17 09:49:33.494  3544  3544 E Zygote  : v2
03-17 09:49:33.494  3544  3544 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:33.504  3544  3544 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 09:49:33.504  3544  3544 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:33.504  3544  3544 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:33.524   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 09:49:33.524   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 09:49:33.524  3221  3221 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 09:49:33.534   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 09:49:33.534   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 09:49:33.534  3544  3544 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:33.534  3544  3544 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:33.544  3221  3221 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 09:49:33.554  3523  3523 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 09:49:33.554   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 09:49:33.554   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 09:49:33.554  3221  3221 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
03-17 09:49:33.554  3523  3523 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 09:49:33.554  1022  1504 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:33.554  1022  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:33.554  1022  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 09:49:33.584  1022  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:33.584  1022  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 09:49:33.584  1022  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 09:49:33.604  1022  1047 W libprocessgroup: failed to open /acct/uid_10135/pid_2578/cgroup.procs: No such file or directory
03-17 09:49:33.604  1022  1047 W libprocessgroup: failed to open /acct/uid_10139/pid_2555/cgroup.procs: No such file or directory
03-17 09:49:33.604  3506  3506 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
03-17 09:49:33.604  1022  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_2391/cgroup.procs: No such file or directory
,03-17 09:49:33.644  3544  3544 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 09:49:33.644  3544  3544 D elm:15121: ELMEngine.ELMEngine( context ).
,03-17 09:49:33.644  3544  3544 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-17 09:49:33.644  1022  1504 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:33.644  1022  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:33.644  1022  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 09:49:33.654  3544  3544 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 09:49:33.654  1832  1832 I SamsungIME: getCurrentKeyboard
03-17 09:49:33.654  1832  1832 I SamsungIME: getTextKeyboard
,03-17 09:49:33.654  1022  1569 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:33.654  1022  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:33.654  1022  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 09:49:33.664  3544  3544 D elm:15121: ElmAgentService : onCreate()
,03-17 09:49:33.664  3341  3402 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
03-17 09:49:33.664  3544  3575 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 09:49:33.664  1446  1446 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 09:49:33.664  3544  3544 D elm:15121: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-17 09:49:33.664  3544  3544 D elm:15121: BootCompletedState : startBootCompleted() call
,03-17 09:49:33.674  1022  1500 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 09:49:33.684  3544  3544 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 09:49:33.694  3473  3483 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 09:49:33.694  3544  3544 I elm:15121: Get License : 0
,03-17 09:49:33.694  3544  3544 D elm:15121: ElmAgentService : onDestroy().
,03-17 09:49:33.694  3523  3523 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 09:49:33.704  3523  3523 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 09:49:33.714  3341  3402 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 09:49:33.714  1347  3154 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 09:49:33.724  1022  1600 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:33.724  1022  1600 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:33.724  1022  1600 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 09:49:33.734  3237  3441 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-17 09:49:33.734  3237  3441 I chromium: 
,03-17 09:49:33.734  3506  3506 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 09:49:33.734  3506  3506 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 09:49:33.734  3506  3506 D UserAnalysis: Create SecureDbHelper
,03-17 09:49:33.744  1832  1832 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 09:49:33.744  1022  1142 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:33.744  1022  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:33.744  1022  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 09:49:33.744  1347  3154 D Settings_Utils: isSupportVNFestival SM-A300FU XEO
,03-17 09:49:33.754  3341  3402 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 09:49:33.754  1022  1510 I ActivityManager: Killing 1812:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-17 09:49:33.764  3278  3538 I System.out: Thread-429(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 09:49:33.764  3278  3538 I System.out: Thread-429(ApacheHTTPLog):isSBSettingEnabled false
,03-17 09:49:33.774  3278  3538 I System.out: Thread-429(ApacheHTTPLog):isShipBuild true
03-17 09:49:33.774  3278  3538 I System.out: Thread-429(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 09:49:33.774  3278  3538 I System.out: Thread-429(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 09:49:33.774  1446  1446 V EmergencyMode: [EmergencyBase] setBootTime
03-17 09:49:33.774  1446  1446 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 09:49:33.774   278   981 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 09:49:33.774   278   981 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-17 09:49:33.784  3237  3237 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 09:49:33.784  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.784  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.784  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.784  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.804  3590  3590 E Zygote  : MountEmulatedStorage()
03-17 09:49:33.804  3590  3590 E Zygote  : v2
03-17 09:49:33.804  3590  3590 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:33.804  3590  3590 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:33.804  3590  3590 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:33.804  3590  3590 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 09:49:33.804  1022  2835 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3590 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 09:49:33.804  1347  3154 W ResourceType: Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,03-17 09:49:33.814  3590  3590 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:33.814  1347  3154 W ResourceType: Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,03-17 09:49:33.824  3506  3506 D IntelligenceServiceApplication: onCreate()
,03-17 09:49:33.824  3506  3506 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 09:49:33.834  3590  3590 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:33.834  3590  3590 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:33.844  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.844  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.844  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:33.844  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:33.854  3221  3245 W art     : Suspending all threads took: 5.479ms
,03-17 09:49:33.864  1022  1504 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3607 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 09:49:33.864  1022  1504 I ActivityManager: Killing 2610:com.android.calendar/u0a131 (adj 15): empty #31
,03-17 09:49:33.864  3607  3607 E Zygote  : MountEmulatedStorage()
03-17 09:49:33.864  3607  3607 I libpersona: KNOX_SDCARD checking this for 10056
03-17 09:49:33.864  3607  3607 E Zygote  : v2
03-17 09:49:33.864  3607  3607 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:33.874  3607  3607 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 09:49:33.874  3607  3607 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:33.884  3607  3607 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:33.894  3506  3506 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 09:49:33.914  1022  1142 W ActivityManager: userId = 0, bbcId = -10000,
,03-17 09:49:33.914  1022  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:33.914  1022  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 09:49:33.914  3506  3506 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 09:49:33.934  3607  3607 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:33.934  3607  3607 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:33.944  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:33.944  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:33.944  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 09:49:33.944  3506  3506 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 09:49:33.944  3506  3506 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 09:49:33.954  3178  3291 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 09:49:33.964  3221  3583 W MessageQueue: Handler (android.os.Handler) {30556d47} sending message to a Handler on a dead thread
03-17 09:49:33.964  3221  3583 W MessageQueue: java.lang.IllegalStateException: Handler (android.os.Handler) {30556d47} sending message to a Handler on a dead thread
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at ffw.a(SourceFile:327)
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at guw.a(SourceFile:120)
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at guf.c(SourceFile:26)
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at gui.run(SourceFile:297)
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:33.964  3221  3583 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 09:49:33.974  2633  3157 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3157)  
,03-17 09:49:33.974  1022  1035 I ActivityManager: Killing 2668:com.android.keychain/1000 (adj 15): empty #31
,03-17 09:49:33.994  1022  1271 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:33.994  1022  1271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:33.994  1022  1271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-17 09:49:34.004  3590  3590 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-17 09:49:34.014  3590  3590 I testFeature: Feature.Feature(context)
,03-17 09:49:34.014  3590  3590 I testFeature: Feature.readInternalDefaultXml()
03-17 09:49:34.014  3590  3590 I testFeature: ResetFeatureValue
,03-17 09:49:34.014  3523  3523 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 09:49:34.024  1022  1034 I ActivityManager: Killing 2532:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
03-17 09:49:34.024  1022  1034 I ActivityManager: Killing 2708:com.android.chrome/u0a77 (adj 15): empty #32
,03-17 09:49:34.024  3590  3590 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 09:49:34.024  3590  3590 I CameraApp: CameraApp.getAppFeature()...
,03-17 09:49:34.024  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.024  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.024  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.024  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.044  3626  3626 E Zygote  : MountEmulatedStorage()
03-17 09:49:34.044  3626  3626 E Zygote  : v2
,03-17 09:49:34.044  3626  3626 I libpersona: KNOX_SDCARD checking this for 10095
03-17 09:49:34.044  3626  3626 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:34.044  3626  3626 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 09:49:34.044  3523  3523 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W,
03-17 09:49:34.044  1974  1974 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
03-17 09:49:34.044  3523  3523 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
03-17 09:49:34.044  3626  3626 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:34.044  3626  3626 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:34.054  1022  2835 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3626 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
03-17 09:49:34.054  3523  3523 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-17 09:49:34.054  1022  2835 I ActivityManager: Killing 2788:com.android.email/u0a141 (adj 15): empty #31
03-17 09:49:34.054  3523  3523 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
03-17 09:49:34.054  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:34.054  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:34.054  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
03-17 09:49:34.054  3523  3523 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
03-17 09:49:34.054  1974  3635 D SecUISvc: Thread created.
,03-17 09:49:34.054  1974  1974 D SecUISvc: Service started flags 0 startId 1
,03-17 09:49:34.064  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 09:49:34.064  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 09:49:34.064  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.064  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.064  3523  3523 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 09:49:34.074  3361  3443 W GAV2    : Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 09:49:34.084  3647  3647 E Zygote  : MountEmulatedStorage()
03-17 09:49:34.084  3647  3647 E Zygote  : v2
03-17 09:49:34.084  3647  3647 I libpersona: KNOX_SDCARD checking this for 10026
03-17 09:49:34.084  3647  3647 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:34.084  1022  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_1812/cgroup.procs: No such file or directory
,03-17 09:49:34.084  1022  1047 W libprocessgroup: failed to open /acct/uid_10131/pid_2610/cgroup.procs: No such file or directory
03-17 09:49:34.084  1022  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_2668/cgroup.procs: No such file or directory
,03-17 09:49:34.084  3647  3647 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:34.094  3647  3647 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:34.094  3626  3626 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:34.094  1022  1510 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3647 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 09:49:34.094  3626  3626 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:34.094  3647  3647 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 09:49:34.104  1022  1047 W libprocessgroup: failed to kill pid 2708: No such process
,03-17 09:49:34.104  3361  3443 W GAV2    : Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,03-17 09:49:34.124  3221  3587 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
03-17 09:49:34.124  3221  3587 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 09:49:34.124  1022  1510 I ActivityManager: Killing 1283:com.android.defcontainer/u0a3 (adj 15): empty #31
,03-17 09:49:34.124  3221  3587 I System.out: Thread-465(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
03-17 09:49:34.124  3647  3647 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:34.124  3221  3587 I System.out: Thread-465(ApacheHTTPLog):isSBSettingEnabled false
03-17 09:49:34.124  3221  3587 I System.out: Thread-465(ApacheHTTPLog):isShipBuild true
03-17 09:49:34.124  3221  3587 I System.out: Thread-465(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 09:49:34.124  3221  3587 I System.out: Thread-465(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 09:49:34.124  3647  3647 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:34.124  3361  3504 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 09:49:34.134   278   981 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 09:49:34.134   278   981 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,03-17 09:49:34.144  3380  3380 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 09:49:34.164  3380  3380 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 09:49:34.164  3380  3380 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 09:49:34.174  1022  2861 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 09:49:34.174  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 09:49:34.174  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 09:49:34.174  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:34.184  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
03-17 09:49:34.184  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:34.184  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:34.184  3380  3380 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 09:49:34.194  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.194  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.194  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.194  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.204  3626  3626 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,03-17 09:49:34.214  3667  3667 E Zygote  : MountEmulatedStorage()
03-17 09:49:34.214  3667  3667 E Zygote  : v2
03-17 09:49:34.214  3667  3667 I libpersona: KNOX_SDCARD checking this for 10013
03-17 09:49:34.214  3667  3667 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:34.214  3667  3667 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:34.214  3667  3667 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 09:49:34.214  3667  3667 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 09:49:34.214  1022  1569 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3667 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,03-17 09:49:34.224  1022  1569 I ActivityManager: Killing 2889:com.mobeam.barcodeService/1000 (adj 15): empty #31
,03-17 09:49:34.244  3667  3667 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:34.244  3667  3667 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:34.274  3626  3626 E SQLiteLog: (284) automatic index on titles(filter_id)
,03-17 09:49:34.284  3607  3607 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.7.KK_APP
,03-17 09:49:34.304  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.304  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.304  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.304  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.314  3626  3626 I FilterProviderReceiver: onReceive in FilterProviderReceiver
03-17 09:49:34.314  3626  3626 I FilterProviderReceiver: onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,03-17 09:49:34.314  1022  1047 W libprocessgroup: failed to open /acct/uid_10039/pid_2532/cgroup.procs: No such file or directory
03-17 09:49:34.314  1022  1047 W libprocessgroup: failed to open /acct/uid_10077/pid_2708/cgroup.procs: No such file or directory
,03-17 09:49:34.314  1022  1271 V VibratorService: hasVibrator - useVibetonz: true
,03-17 09:49:34.314  3667  3667 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive,
,03-17 09:49:34.324  1022  1047 W libprocessgroup: failed to open /acct/uid_10003/pid_1283/cgroup.procs: No such file or directory
03-17 09:49:34.324  1022  1047 W libprocessgroup: failed to open /acct/uid_10141/pid_2788/cgroup.procs: No such file or directory
,03-17 09:49:34.334  3683  3683 E Zygote  : MountEmulatedStorage()
03-17 09:49:34.334  3683  3683 E Zygote  : v2
,03-17 09:49:34.334  3683  3683 I libpersona: KNOX_SDCARD checking this for 10058
03-17 09:49:34.334  3683  3683 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:34.334  3683  3683 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:34.344  1022  1510 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3683 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 09:49:34.344  3683  3683 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:34.344  3683  3683 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:34.344  1022  1600 I ActivityManager: Killing 2911:flipboard.boxer.app/u0a97 (adj 15): empty #31
,03-17 09:49:34.354  1022  1382 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:34.354  1022  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 09:49:34.354  1022  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 09:49:34.364   306   306 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 23.375ms
,03-17 09:49:34.364  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.364  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.364  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.364  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.384   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.837ms
,03-17 09:49:34.384  3683  3683 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:34.384  3683  3683 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:34.404   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 16.738ms
,03-17 09:49:34.414  3699  3699 E Zygote  : MountEmulatedStorage()
03-17 09:49:34.414  3699  3699 I libpersona: KNOX_SDCARD checking this for 10098
03-17 09:49:34.414  3667  3698 V OneTimeService: OneTimeService.onHandleIntent
03-17 09:49:34.414  3699  3699 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:34.414  3699  3699 E Zygote  : v2
,03-17 09:49:34.424  3699  3699 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 09:49:34.424  1022  1510 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3699 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,03-17 09:49:34.424  3699  3699 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:34.424  3699  3699 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:34.434  3361  3444 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-17 09:49:34.454  3237  3253 I art     : Background sticky concurrent mark sweep GC freed 34537(2MB) AllocSpace objects, 5(1054KB) LOS objects, 21% free, 9MB/11MB, paused 5.346ms total 48.255ms
,03-17 09:49:34.464  1022  2835 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:34.474  1022  2835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:34.474  1022  2835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 09:49:34.484  1022  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_2889/cgroup.procs: No such file or directory
,03-17 09:49:34.484  1022  1047 W libprocessgroup: failed to open /acct/uid_10097/pid_2911/cgroup.procs: No such file or directory
,03-17 09:49:34.484  1022  2835 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:34.484  1022  2835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:34.484  1022  2835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 09:49:34.484  3699  3699 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:34.484  3699  3699 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:34.494  1022  2835 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:34.494  1022  2835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:34.494  1022  2835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 09:49:34.494  3361  3444 I LibraryLoader: Loading: webviewchromium
,03-17 09:49:34.494  1022  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:34.494  1022  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 09:49:34.494  1022  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 09:49:34.494  3361  3444 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9415-9419)
03-17 09:49:34.494  3361  3444 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 09:49:34.524  3699  3699 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 09:49:34.554  3699  3699 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-17 09:49:34.564  3361  3444 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:49:34.574  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.574  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.574  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.574  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.584  3727  3727 E Zygote  : MountEmulatedStorage()
03-17 09:49:34.584  3727  3727 E Zygote  : v2
03-17 09:49:34.584  3727  3727 I libpersona: KNOX_SDCARD checking this for 10099
03-17 09:49:34.584  3727  3727 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:34.584  3727  3727 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:34.594  3727  3727 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:34.594  3727  3727 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 09:49:34.594  1022  1500 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3727 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 09:49:34.594  1022  1500 I ActivityManager: Killing 2946:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 09:49:34.604  1022  1509 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:34.604  1022  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:34.604  1022  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 09:49:34.604  3683  3683 I ExternalOEMControlProvider: onCreate
,03-17 09:49:34.614  1022  1509 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:34.614  1022  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:34.614  1022  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 09:49:34.614  1761  1761 I Hs20UtilService: Starting #4
,03-17 09:49:34.624  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.624  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.624  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.624  1022  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.624  1761  1811 I Hs20UtilService: Message received 5003
,03-17 09:49:34.634  3727  3727 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:34.634  3727  3727 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:34.634  3746  3746 E Zygote  : MountEmulatedStorage()
03-17 09:49:34.634  3746  3746 E Zygote  : v2
03-17 09:49:34.634  3746  3746 I libpersona: KNOX_SDCARD checking this for 10018
03-17 09:49:34.634  3746  3746 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:34.634  3746  3746 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:34.644  1022  1504 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3746 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
03-17 09:49:34.644  3746  3746 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:34.644  3746  3746 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:34.664  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.664  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.664  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.664  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.684  3746  3746 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 09:49:34.684  3746  3746 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:34.684  3764  3764 E Zygote  : MountEmulatedStorage(),
03-17 09:49:34.684  3764  3764 E Zygote  : v2
03-17 09:49:34.684  3764  3764 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:34.684  3764  3764 I libpersona: KNOX_SDCARD not a persona,
03-17 09:49:34.684  3764  3764 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:34.694  1022  1500 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3764 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-17 09:49:34.694  3764  3764 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:34.694  1022  1500 I ActivityManager: Killing 2291:flipboard.app/u0a96 (adj 15): empty #31
,03-17 09:49:34.694  3764  3764 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:34.704  3237  3502 W jxcore-log: Initializing JXcore engine
03-17 09:49:34.704  3237  3502 W jxcore-log: JXcore engine is ready
,03-17 09:49:34.744  1022  1500 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-17 09:49:34.744  1022  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:34.744  1022  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:34.744  1022  1500 D SettingsProvider: selectionArgs: false
03-17 09:49:34.744  1022  1500 D SettingsProvider: selectionArgs: 10058
03-17 09:49:34.744  1022  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:34.744  1022  1500 D SettingsProvider: ret = -1
,03-17 09:49:34.744  3764  3764 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:34.754  3764  3764 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:34.764  1022  1500 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-17 09:49:34.764  1895  1895 E audit   : type=1400 msg=audit(1458204574.764:205): avc:  denied  { ioctl } for  pid=3502 comm="Thread-437" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-17 09:49:34.764  1895  1895 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:34.764  1895  1895 E audit   : type=1300 msg=audit(1458204574.764:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9e87b8f8 items=0 ppid=306 ppcomm=main pid=3502 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-437" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,03-17 09:49:34.764  1895  1895 E audit   : type=1320 msg=audit(1458204574.764:205): 
,03-17 09:49:34.774  3647  3647 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 09:49:34.784  3237  3502 W jxcore-log: Starting JXcore engine
,03-17 09:49:34.784  1022  1509 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-17 09:49:34.784  1022  1509 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:34.784  1022  1509 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:34.784  1022  1509 D SettingsProvider: selectionArgs: false
03-17 09:49:34.784  1022  1509 D SettingsProvider: selectionArgs: 10058
03-17 09:49:34.784  1022  1509 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:34.784  1022  1509 D SettingsProvider: ret = -1
,03-17 09:49:34.794  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 09:49:34.794  1022  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:34.794  1022  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:34.794  1022  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 09:49:34.804  3764  3764 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 09:49:34.824  1022  1047 W libprocessgroup: failed to open /acct/uid_1101/pid_2946/cgroup.procs: No such file or directory
,03-17 09:49:34.834  3408  3408 I RlzPingService: Setting next ping for 1458809374838
,03-17 09:49:34.834  1022  1047 W libprocessgroup: failed to open /acct/uid_10096/pid_2291/cgroup.procs: No such file or directory
,03-17 09:49:34.854  1347  3154 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 09:49:34.884  3746  3746 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 09:49:34 GMT+01:00 2016
,03-17 09:49:34.884  3221  3587 I System.out: Thread-465 calls detatch()
,03-17 09:49:34.884  1022  2835 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:34.884  1022  2835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 09:49:34.884  1022  2835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 09:49:34.904  3746  3746 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-17 09:49:34.904  1022  1509 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
03-17 09:49:34.904  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.904  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.904  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.904  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.904  3237  3502 W jxcore-log: Platform android
03-17 09:49:34.904  3237  3502 W jxcore-log: 
,03-17 09:49:34.904  3237  3502 W jxcore-log: Process ARCH arm
03-17 09:49:34.904  3237  3502 W jxcore-log: 
,03-17 09:49:34.914  3764  3764 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-17 09:49:34.914  3764  3764 I ServiceMode: setReferenceIsDumpState : 0
,03-17 09:49:34.924  3785  3785 E Zygote  : MountEmulatedStorage(),
03-17 09:49:34.924  3785  3785 E Zygote  : v2
03-17 09:49:34.924  3785  3785 I libpersona: KNOX_SDCARD checking this for 10020
03-17 09:49:34.924  3785  3785 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:34.924  3785  3785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 09:49:34.924  1022  1035 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3785 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,03-17 09:49:34.924  3785  3785 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:34.924  3785  3785 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 09:49:34.934  3746  3746 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-17 09:49:34.934  3746  3746 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 09:49:34.934  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 09:49:34.944  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.944  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.944  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:34.944  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:34.954  3746  3746 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 09:49:34.954  3800  3800 E Zygote  : MountEmulatedStorage()
03-17 09:49:34.954  3800  3800 E Zygote  : v2
03-17 09:49:34.954  3800  3800 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:34.954  3800  3800 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:34.954  3800  3800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:34.964  3785  3785 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 09:49:34.964  3800  3800 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 09:49:34.964  3785  3785 D ActivityThread: Added TimaKeyStore provider,
03-17 09:49:34.964  3178  3291 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
03-17 09:49:34.964  1022  2835 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3800 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:34.964  3800  3800 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:34.964  1022  2835 I ActivityManager: Killing 2994:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,03-17 09:49:34.974  3746  3784 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 09:49:34.984  3746  3784 I KLMS-2.5.123: : KLMSIntentService(): BOOT_COMPLETED
,03-17 09:49:34.994  3800  3800 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:34.994  3800  3800 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:35.044  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.044  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.044  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.044  1022  1034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:35.054  3800  3800 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-17 09:49:35.064  3818  3818 E Zygote  : MountEmulatedStorage()
,03-17 09:49:35.064  3818  3818 E Zygote  : v2
03-17 09:49:35.064  3818  3818 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:35.064  3818  3818 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:35.064  3818  3818 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:35.064  1022  1034 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3818 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 09:49:35.074  3818  3818 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:35.074  1022  1034 I ActivityManager: Killing 3016:com.sec.usbsettings/1000 (adj 15): empty #31
,03-17 09:49:35.074  3818  3818 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:35.074  3800  3800 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 09:49:35.084  1022  1509 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:35.084  1022  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:35.084  1022  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 09:49:35.084  1022  1271 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.084  1022  1271 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.084  1022  1271 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.084  1022  1271 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:35.094  3800  3800 D NPS_WSSNPS: [] Service onCreate!!
,03-17 09:49:35.104  3833  3833 E Zygote  : MountEmulatedStorage()
,03-17 09:49:35.104  3833  3833 E Zygote  : v2
03-17 09:49:35.104  3833  3833 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:35.104  3833  3833 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:35.104  3833  3833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:35.104  3833  3833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:35.104  3833  3833 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:35.104  1022  1271 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3833 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:35.114  3818  3818 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:35.114  3818  3818 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:35.124  3278  3538 I System.out: pool-10-thread-1 calls detatch()
,03-17 09:49:35.124  3800  3842 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-17 09:49:35.144  3800  3800 D NPS_WSSNPS: [50.150321] smlDBHelper
,03-17 09:49:35.154  3746  3746 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-17 09:49:35.174  3833  3833 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:35.174  3833  3833 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:35.174  3800  3800 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-17 09:49:35.184  3237  3502 I jxcore-log: JXcore Cordova bridge is ready!
03-17 09:49:35.184  3237  3502 I jxcore-log: 
,03-17 09:49:35.184  3237  3502 W jxcore-log: JXcore engine is started
,03-17 09:49:35.194  3800  3853 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-17 09:49:35.194  3237  3489 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 09:49:35.194  1022  1047 W libprocessgroup: failed to open /acct/uid_10153/pid_2994/cgroup.procs: No such file or directory
,03-17 09:49:35.194  3800  3853 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
,03-17 09:49:35.194  3800  3853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-17 09:49:35.204  3237  3237 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 09:49:35.204  1022  2835 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:35.204  1022  2835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:35.204  1022  2835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 09:49:35.204  3800  3800 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-17 09:49:35.204  3800  3800 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-17 09:49:35.204  3800  3800 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-17 09:49:35.204  3800  3800 I NPS_WSSNPS: [50.150321] smlBREmailDelete
,03-17 09:49:35.214  3800  3800 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
03-17 09:49:35.214  3800  3800 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
,03-17 09:49:35.214  3800  3800 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
03-17 09:49:35.214  3800  3800 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
,03-17 09:49:35.214  3800  3800 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
03-17 09:49:35.214  3800  3800 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-17 09:49:35.214  1022  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_3016/cgroup.procs: No such file or directory
,03-17 09:49:35.224  3237  3502 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 09:49:35.224  3237  3502 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 09:49:35.234   278   981 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 09:49:35.234   278   981 D Netd    : getNetworkForDns: using netid 502 for uid 10052
,03-17 09:49:35.234  3800  3800 D NPS_WSSNPS: [50.150321] dsServerSocket close
,03-17 09:49:35.244  3818  3818 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-17 09:49:35.244  1022  1569 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 09:49:35.244  1022  1569 D SecContentProvider2: mCursor = null
,03-17 09:49:35.244  1022  1034 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-17 09:49:35.244  1022  1034 D SecContentProvider2: mCursor = null
,03-17 09:49:35.244  3818  3818 V MTPRx   : sealedState: false
03-17 09:49:35.244  3818  3818 V MTPRx   : sealedUsbMassStorageState: false
,03-17 09:49:35.264  3237  3237 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
03-17 09:49:35.264  3237  3237 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 09:49:35.264  1022  1142 D FocusedStackFrame: Set to : 0
03-17 09:49:35.264  1022  1142 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 09:49:35.264  1022  1142 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 09:49:35.264  1022  1142 D InputDispatcher: Focused application set to: xxxx
03-17 09:49:35.264  1022  1142 D InputDispatcher: Focus left window: 3237
03-17 09:49:35.274   291   291 E SMD     : DCD OFF
03-17 09:49:35.274  1022  1053 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 09:49:35.274  1022  1053 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 09:49:35.274  1022  1035 D SettingsProvider: name = access_control_enabled
03-17 09:49:35.274   259  1044 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (280 us)
03-17 09:49:35.284  1022  1600 D SettingsProvider: name = mtp_usb_connection_status
,03-17 09:49:35.294  3647  3647 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-17 09:49:35.294  1022  1035 D SettingsProvider: name = media_player_mode
,03-17 09:49:35.304  1022  1510 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 09:49:35.314  3237  3489 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 47ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 09:49:35.314  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 09:49:35.334  1022  1504 D SettingsProvider: name = mtp_running_status
,03-17 09:49:35.334  3647  3647 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 09:49:35.334  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 09:49:35.334  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:35.334  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.334  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.334  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.344  3361  3444 I qtaguid : Tagging socket 39 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052
,03-17 09:49:35.344  3647  3647 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 09:49:35.354  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 09:49:35.354  1022  1035 D SettingsProvider: name = media_mount_count
,03-17 09:49:35.354  3872  3872 E Zygote  : MountEmulatedStorage()
03-17 09:49:35.354  3872  3872 E Zygote  : v2
03-17 09:49:35.354  3872  3872 I libpersona: KNOX_SDCARD checking this for 10065
03-17 09:49:35.354  3872  3872 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:35.354  3872  3872 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:35.364  3872  3872 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:35.364  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 09:49:35.364  1022  1034 D SettingsProvider: name = mtp_sync_alive
,03-17 09:49:35.364  3872  3872 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:35.364  1022  1500 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3872 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 09:49:35.374  1022  1500 I ActivityManager: Killing 2420:com.android.mms/u0a41 (adj 15): empty #31
,03-17 09:49:35.374  1022  1509 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found,
,03-17 09:49:35.374  1022  1271 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 09:49:35.374  1022  1271 W ActivityManager: mDVFSHelper.acquire()
,03-17 09:49:35.384  1022  1271 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 09:49:35.384  1022  1271 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 09:49:35.384  1022  1271 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-17 09:49:35.394  1347  3154 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 09:49:35.394  1022  1035 D SettingsProvider: name = sdcard_launch
,03-17 09:49:35.414  3872  3872 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:35.414  3872  3872 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:35.414  1022  1569 D SettingsProvider: name = boot_time_connected
,03-17 09:49:35.414  1022  1022 D SensorService: [SO] activate (ident=0xb7f32b90, enabled=0)
03-17 09:49:35.414  1022  1022 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-17 09:49:35.414  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 09:49:35.414  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 09:49:35.414  1347  3154 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 09:49:35.424  3727  3888 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,03-17 09:49:35.424  1022  1271 D SettingsProvider: name = mtp_open_session
,03-17 09:49:35.434  1022  1022 D SensorManager: unregisterListener ::   
03-17 09:49:35.434  1022  1022 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-17 09:49:35.434  1022  1022 D SensorService: [SO] changed settle time [0]
03-17 09:49:35.434  1022  1022 D SensorService: [SO] setDelay [200000000]
03-17 09:49:35.434  1022  1022 D SensorService: [SO] activate (ident=0xb7f32b90, enabled=1)
03-17 09:49:35.434  1022  1022 D SensorService: [SO] AR_init
03-17 09:49:35.434  1022  1022 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-17 09:49:35.434  1022  1034 I ActivityManager: Killing 3065:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,03-17 09:49:35.434  1022  1509 I ActivityManager: Killing 2924:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,03-17 09:49:35.444  1022  1022 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
03-17 09:49:35.444  1511  1511 D Launcher: onRestart, Launcher: 647111460
,03-17 09:49:35.444  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 09:49:35.444  1511  1511 D Launcher: onStart, Launcher: 647111460
03-17 09:49:35.444  1511  1511 D Launcher.HomeView: onStart
03-17 09:49:35.444  1511  1511 D Launcher: onResume, Launcher: 647111460
03-17 09:49:35.454  1022  1142 D SettingsProvider: name = kids_home_mode
03-17 09:49:35.454  1022  1142 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 09:49:35.454  1022  1142 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 09:49:35.454  1022  1142 D SettingsProvider: selectionArgs: false
03-17 09:49:35.454  1022  1142 D SettingsProvider: selectionArgs: 10006
03-17 09:49:35.454  1022  1142 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 09:49:35.454  1022  1142 D SettingsProvider: ret = -1
,03-17 09:49:35.454  1511  1511 D Launcher.HomeView: onResume
,03-17 09:49:35.454  1347  3154 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 09:49:35.454  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 09:49:35.464  1511  1511 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 09:49:35.464  1175  1175 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 09:49:35.464  1511  1511 D MenuAppsGridFragment: onResume
,03-17 09:49:35.464  1022  1569 D ActivityManager: handle home activity for 0
03-17 09:49:35.464  1022  1022 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 09:49:35.464  1022  1569 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 09:49:35.464  1022  1569 D KnoxTimeoutHandler: post home show event for user 0
03-17 09:49:35.464  1022  1569 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 09:49:35.464  1022  1569 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 09:49:35.464  1022  1569 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 09:49:35.464  1022  1022 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 09:49:35.464  1022  1022 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 09:49:35.464  1022  1022 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 09:49:35.474   259   259 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=4, Mauncher
,03-17 09:49:35.474  1022  1051 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 09:49:35.474  1022  1051 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 09:49:35.484  1022  1142 D InputDispatcher: Focus entered window: 1511
,03-17 09:49:35.484  1022  1053 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 09:49:35.484  1511  1511 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 09:49:35.484  1022  1053 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 09:49:35.484  1022  1504 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 09:49:35.494  1511  1511 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
03-17 09:49:35.494  3473  3473 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 09:49:35.494  3473  3473 I PCWCLIENTTRACE_PushUtil: sales region : global
,03-17 09:49:35.494  3473  3473 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 09:49:35.494  3473  3473 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-17 09:49:35.494  3473  3473 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 09:49:35.494  3473  3473 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 09:49:35.494  1022  1382 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 09:49:35.504  1022  3896 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 09:49:35.504  1175  1175 I StatusBar: Icon Only
,03-17 09:49:35.504  1175  1175 D PanelView: There is/are notification(s) 
,03-17 09:49:35.514  3237  3237 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 09:49:35.514  1832  1832 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 09:49:35.514  1022  1382 D CountryDetector: No listener is left
,03-17 09:49:35.524  3473  3473 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account,
,03-17 09:49:35.544  1511  1511 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@13f9efc9 time:40465
,03-17 09:49:35.544  1022  1053 D PersonaManager: isKioskContainerExistOnDevice
,03-17 09:49:35.564  1022  1053 I ActivityManager: Displayed Component not be shown by security: +183ms
,03-17 09:49:35.564  3872  3872 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 09:49:35.574  3473  3473 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 09:49:35.584  3473  3473 I ReactiveServiceManager: Supported : 1
,03-17 09:49:35.584  1022  1047 W libprocessgroup: failed to open /acct/uid_10081/pid_2924/cgroup.procs: No such file or directory
,03-17 09:49:35.584  3870  3870 D AndroidRuntime: 
03-17 09:49:35.584  3870  3870 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 09:49:35.584  1022  1047 W libprocessgroup: failed to open /acct/uid_10041/pid_2420/cgroup.procs: No such file or directory
03-17 09:49:35.584  1022  1047 W libprocessgroup: failed to open /acct/uid_10043/pid_3065/cgroup.procs: No such file or directory
,03-17 09:49:35.594  3870  3870 D AndroidRuntime: CheckJNI is OFF
03-17 09:49:35.594  3870  3870 D AndroidRuntime: readGMSProperty: start
03-17 09:49:35.594  3870  3870 D AndroidRuntime: readGMSProperty: already setted!!
03-17 09:49:35.594  3870  3870 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 09:49:35.594  3870  3870 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 09:49:35.594  3870  3870 D AndroidRuntime: readGMSProperty: end
03-17 09:49:35.594  3870  3870 D AndroidRuntime: addProductProperty: start
,03-17 09:49:35.614  1022  1569 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:35.614  1022  1569 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:35.614  1022  1569 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 09:49:35.614  1916  1916 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 09:49:35.614  1916  1916 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 09:49:35.624  1022  1504 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-17 09:49:35.624  1022  1504 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 09:49:35.644  1022  1045 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 09:49:35.654  3727  3903 I Gmail   : getAccountsCursor
,03-17 09:49:35.654  1022  1600 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 09:49:35.654  1022  1504 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 09:49:35.654  1022  1382 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 09:49:35.664  1022  1034 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 09:49:35.674  1022  1504 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 09:49:35.674  1022  1504 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
03-17 09:49:35.674  1022  1504 E terrier : handleString: Failed to handle string(-4)
03-17 09:49:35.674  1022  1504 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-17 09:49:35.674  3473  3473 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 09:49:35.674  3473  3473 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-17 09:49:35.674  3473  3473 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 09:49:35.674  3473  3473 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 09:49:35.674  3473  3473 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 09:49:35.674  3473  3473 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 09:49:35.674  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.674  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.674  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:35.674  1022  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:35.684  1916  1916 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 09:49:35.684  3647  3859 D Volley  : [501] g.b: Cache cleared.
03-17 09:49:35.694  3647  3780 D Volley  : [495] g.b: Cache cleared.
,03-17 09:49:35.704  3915  3915 E Zygote  : MountEmulatedStorage()
03-17 09:49:35.704  3915  3915 E Zygote  : v2
03-17 09:49:35.704  3915  3915 I libpersona: KNOX_SDCARD checking this for 10028
03-17 09:49:35.704  3915  3915 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:35.704  3915  3915 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:35.704  3915  3915 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:35.704  1022  1510 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3915 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-17 09:49:35.704  1022  1510 I ActivityManager: Killing 2739:com.google.android.apps.plus/u0a117 (adj 15): empty #31
03-17 09:49:35.714  3915  3915 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 09:49:35.714  1022  1510 I ActivityManager: Killing 1608:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,03-17 09:49:35.744  2653  2763 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
03-17 09:49:35.744  1022  1500 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:35.744  1022  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:35.744  1022  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 09:49:35.744  3870  3870 E AffinityControl: AffinityControl: registerfunction enter
,03-17 09:49:35.754  3727  3727 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,03-17 09:49:35.754  3647  3647 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-17 09:49:35.754  3647  3647 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-17 09:49:35.764  3647  3914 D Ads     : Skipping gmscore version check
,03-17 09:49:35.764  3915  3915 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:35.764  3915  3915 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:35.774  3870  3870 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,03-17 09:49:35.784  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052,
03-17 09:49:35.784  3647  3647 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
,03-17 09:49:35.784  3361  3444 I qtaguid : Untagging socket 43
,03-17 09:49:35.784  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052,
03-17 09:49:35.784  3361  3444 I qtaguid : Untagging socket 43
03-17 09:49:35.784  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052
,03-17 09:49:35.784  3361  3444 I qtaguid : Untagging socket 43
,03-17 09:49:35.784  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052
03-17 09:49:35.784  3361  3444 I qtaguid : Untagging socket 43
,03-17 09:49:35.794  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052
,03-17 09:49:35.794  3727  3912 I Gmail   : Observing account changes for notifications
,03-17 09:49:35.794  3361  3444 I qtaguid : Untagging socket 43
,03-17 09:49:35.794  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052
03-17 09:49:35.794  3361  3444 I qtaguid : Untagging socket 43
,03-17 09:49:35.794  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052
03-17 09:49:35.794  3361  3444 I qtaguid : Untagging socket 43
,03-17 09:49:35.814  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052
,03-17 09:49:35.814  3361  3444 I qtaguid : Untagging socket 43
,03-17 09:49:35.814  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052
03-17 09:49:35.814  3361  3444 I qtaguid : Untagging socket 43
03-17 09:49:35.814  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052
03-17 09:49:35.814  3361  3444 I qtaguid : Untagging socket 43
03-17 09:49:35.814  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052
,03-17 09:49:35.814  3361  3444 I qtaguid : Untagging socket 43
03-17 09:49:35.814  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052
03-17 09:49:35.814  3361  3444 I qtaguid : Untagging socket 43
03-17 09:49:35.814  1022  1504 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:35.814  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052
03-17 09:49:35.814  1022  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:35.814  1022  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 09:49:35.814  3361  3444 I qtaguid : Untagging socket 43
,03-17 09:49:35.824  1022  1509 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-17 09:49:35.824  1022  1509 D PackageManager: START PACKAGE DELETE: observer{328544476}
03-17 09:49:35.824  1022  1509 D PackageManager: pkg{<packageName>}
03-17 09:49:35.824  1022  1509 D PackageManager: user{0}
03-17 09:49:35.824  1022  1509 D PackageManager: caller{2000}
03-17 09:49:35.824  1022  1509 D PackageManager: flags{2}
03-17 09:49:35.824  1022  1509 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-17 09:49:35.824  1022  1509 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-17 09:49:35.824  1022  1509 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 09:49:35.824  1022  1509 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-17 09:49:35.824  1022  1063 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-17 09:49:35.824  1022  1063 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-17 09:49:35.824  1022  1063 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,03-17 09:49:35.834  1022  1142 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:35.834  1022  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:35.834  1022  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
03-17 09:49:35.834  1022  1504 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 09:49:35.844  1022  1063 D ApplicationPolicy: getApplicationUninstallationEnabled
,03-17 09:49:35.844  1022  1045 D SensorService: [SO] currT = 40761045000, prevT = 40331033000, diff = 430012000, [-0.479 0.211 9.883]
03-17 09:49:35.844  1022  1045 D SensorService: [SO] -0.479 0.211 9.883
03-17 09:49:35.844  1022  1045 D SensorService: [SO] [100 -> 255]
,03-17 09:49:35.844  1022  1063 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-17 09:49:35.874  1022  1048 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 09:49:35.874  1022  1048 W ActivityManager: mDVFSHelper.release()
03-17 09:49:35.874  1022  1048 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 09:49:35.884  1022  1063 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
,03-17 09:49:35.884  1022  1600 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:35.884  1022  1600 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:35.884  1022  1600 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 09:49:35.894  3647  3647 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
,03-17 09:49:35.894  1022  1504 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 09:49:35.894  2162  3936 D FileApkUtils: Optimizing (staging complete)
03-17 09:49:35.894  2162  3936 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
,03-17 09:49:35.894  2162  3936 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-17 09:49:35.894  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:35.894  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 09:49:35.894  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 09:49:35.904  1022  1509 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:35.904  1022  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:35.904  1022  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 09:49:35.924  1022  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:35.924  1022  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:35.924  1022  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:35.924  2162  3936 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
,03-17 09:49:35.934  1022  1048 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,03-17 09:49:35.934  1022  1048 I ActivityManager: Killing 3237:com.test.thalitest/u0a167 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-17 09:49:35.944  1022  1047 W libprocessgroup: failed to open /acct/uid_10068/pid_1608/cgroup.procs: No such file or directory
03-17 09:49:35.944  1022  1047 W libprocessgroup: failed to open /acct/uid_10117/pid_2739/cgroup.procs: No such file or directory
,03-17 09:49:35.964  3178  3291 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 09:49:35.974   259  1044 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-17 09:49:35.974   259   441 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 09:49:35.984  3647  3647 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-17 09:49:36.064  1022  1063 W PackageSettings: Skipping PackageSetting{20c34b1e com.example.hello/10168} due to missing metadata
,03-17 09:49:36.114  3361  3444 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3361, getuid(): 10052,
,03-17 09:49:36.114  3915  3915 I System.out: Inside onCreate() of WakeupTriggerProvide
,03-17 09:49:36.124  3915  3915 I System.out: Inside WakeupProvider
,03-17 09:49:36.124  3361  3504 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 09:49:36.134  1022  1271 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1175 (0x0)
,03-17 09:49:36.134  1022  1382 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:36.144  1022  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:36.144  1022  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:36.144  2633  2633 D FactoryTestApp: [DummyFtClient$onDestroy](2633) Destroy DummyFtClient service
,03-17 09:49:36.154  3727  3943 E Gmail   : Error finding the version of the Email provider.....
03-17 09:49:36.154  3727  3943 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 09:49:36.154  3727  3943 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 09:49:36.154  3727  3943 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
03-17 09:49:36.154  3727  3943 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-17 09:49:36.154  3727  3943 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 09:49:36.154  3727  3943 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:36.154  3727  3943 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:36.154  3727  3943 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 09:49:36.154  3727  3943 W EmailMigration: We do not support migrating this version of the Email provider.
,03-17 09:49:36.154  1022  1063 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-17 09:49:36.174  1022  1022 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 09:49:36.184  1022  1063 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-17 09:49:36.184  1022  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12025117 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:41107
,03-17 09:49:36.194  1022  1504 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:36.194  1022  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:36.194  1022  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 09:49:36.194  3727  3889 I Gmail   : getAccountsCursor
,03-17 09:49:36.234  1832  1832 E SamsungIME: mOCRHelper is null
,03-17 09:49:36.234  3915  3915 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,03-17 09:49:36.244  1483  1483 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 09:49:36.254  1022  1022 D RCPManagerService: PackageReceiver onReceive()
,03-17 09:49:36.254  1022  1022 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-17 09:49:36.264  1022  1022 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-17 09:49:36.304  1022  1131 V NetworkStats: removeUidsLocked() for UIDs [10167]
03-17 09:49:36.304  1022  1131 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 09:49:36.304  1022  1131 V NetworkStats: performPollLocked(flags=0x3)
,03-17 09:49:36.304  1022  1131 D NetworkStatsFactory: UpdateStatsForKnox updated
,03-17 09:49:36.304  1022  1131 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 09:49:36.314  1022  1131 V NetworkStats: performPollLocked() took 17ms
,03-17 09:49:36.324  1022  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 09:49:36.334  1022  1271 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:36.334  1022  1271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 09:49:36.334  1022  1271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:36.354  2633  2633 D FactoryTestApp: [Support$Values.getString](2633) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 09:49:36.354  2633  2633 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2633) mConnectionMode = gsm
03-17 09:49:36.354  2633  2633 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2633) RUNNING_FTCLIENT : false
03-17 09:49:36.354  2633  2633 D FactoryTestApp: [DummyFtClient$onDestroy](2633) kill process
03-17 09:49:36.354  2633  2633 I Process : Sending signal. PID: 2633 SIG: 9
,03-17 09:49:36.364  1022  3950 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:36.364  1022  3950 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:36.364  1022  3950 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 09:49:36.404  1022  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 09:49:36.404  1022  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 09:49:36.414  3915  3915 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,03-17 09:49:36.414  1022  1103 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 09:49:36.424  1022  2835 I art     : Explicit concurrent mark sweep GC freed 46527(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 24MB/36MB, paused 4.982ms total 263.768ms
,03-17 09:49:36.424  1022  1063 I art     : WaitForGcToComplete blocked for 237.301ms for cause Explicit
,03-17 09:49:36.464  1022  1271 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:36.474  1022  1271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 09:49:36.474  1022  1271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-17 09:49:36.474  1022  3952 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:36.474  1022  3952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:36.474  1022  3952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:36.484  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:36.494  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.494  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.494  1022  1600 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:36.494  3341  3401 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 09:49:36.504  1022  2835 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin,
03-17 09:49:36.504  1022  2835 D SecContentProvider2: mCursor = null
,03-17 09:49:36.514  3956  3956 E Zygote  : MountEmulatedStorage(),
03-17 09:49:36.514  3956  3956 E Zygote  : v2
,03-17 09:49:36.514  3956  3956 I libpersona: KNOX_SDCARD checking this for 10102
03-17 09:49:36.514  1022  1600 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3956 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-17 09:49:36.514  3956  3956 I libpersona: KNOX_SDCARD not a persona,
03-17 09:49:36.514  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-17 09:49:36.514  1022  1022 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-17 09:49:36.514  1022  1022 V EnterpriseBillingPolicy: uID is 10167
03-17 09:49:36.514  1022  1022 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
03-17 09:49:36.514  1022  1022 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 09:49:36.514  1022  1022 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-17 09:49:36.514  1022  1022 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 09:49:36.514  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 09:49:36.514  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package ,
03-17 09:49:36.514  1022  1022 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 09:49:36.514  1022  1022 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 09:49:36.524  1022  1509 I ActivityManager: Process com.sec.factory (pid 2633)(adj 0) has died(73,648),
,03-17 09:49:36.524  3956  3956 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 09:49:36.534  3956  3956 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 09:49:36.534  3956  3956 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 09:49:36.534  1022  2835 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 09:49:36.544   306   306 I art     : Explicit concurrent mark sweep GC freed 8707(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 35.186ms,
,03-17 09:49:36.554  1645  3955 I GoogleHttpClient: GMS http client unavailable, use old client
,03-17 09:49:36.554  1022  1022 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 09:49:36.554  1472  1472 D RegisteredServicesCache: empty dynamic service
,03-17 09:49:36.554  3341  3401 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 09:49:36.564  3341  3401 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 09:49:36.574  3341  3401 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 09:49:36.574  1022  1600 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 09:49:36.574  3341  3401 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 09:49:36.584   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 21.685ms
,03-17 09:49:36.594  3956  3956 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:36.594  3956  3956 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:36.594   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 17.871ms
,03-17 09:49:36.614  1916  2195 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 09:49:36.624  1916  1916 D ChimeraCfgMgr: Reading stored module config
,03-17 09:49:36.634  3956  3956 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 09:49:36.654  3727  3727 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@13c59725 that was originally bound here
03-17 09:49:36.654  3727  3727 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@13c59725 that was originally bound here
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at com.android.emailcommon.service.H.a(SourceFile:181)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at com.android.emailcommon.service.H.mb(SourceFile:224)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at com.android.email.service.n.j(SourceFile:160)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:171)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at com.android.email.provider.b.F(SourceFile:115)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 09:49:36.654  3727  3727 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 09:49:36.654  1022  1509 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@358d41ad
,03-17 09:49:36.694  2162  2162 W InstanceID/Rpc: Found 10011
,03-17 09:49:36.694  3341  3401 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 09:49:36.704  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:36.704  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 09:49:36.704  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 09:49:36.704  3341  3401 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 09:49:36.704  3341  3401 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 09:49:36.724  1022  1165 D TaskPersister: removeObsoleteFile: deleting file=11_task.xml
,03-17 09:49:36.724  1022  1165 D TaskPersister: removeObsoleteFile: deleting file=11_task_thumbnail.png
,03-17 09:49:36.734  1022  1047 D EnterpriseDeviceManagerService: Package has changed for user 0
03-17 09:49:36.734  1022  1047 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-17 09:49:36.734  1022  1047 W TextServicesManagerService: no available spell checker services found
,03-17 09:49:36.744  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:36.744  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:36.754  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:36.754  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:36.784  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-17 09:49:36.784  1022  1022 V EnterpriseBillingPolicy: uID is 10167
03-17 09:49:36.784  1022  1022 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 09:49:36.784  1022  1022 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 09:49:36.784  1022  1022 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,03-17 09:49:36.784  1022  2775 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-17 09:49:36.784  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 09:49:36.784  1022  1022 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 09:49:36.784  1022  1022 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 09:49:36.784  1916  1916 D WearableService: callingUid 10011, callindPid: 1916
,03-17 09:49:36.784  1022  1022 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 09:49:36.854  1916  1916 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
03-17 09:49:36.854  1022  1047 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 09:49:36.864  1022  1022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 09:49:36.874  1022  1022 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-17 09:49:36.874  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:36.874  1022  1063 I art     : Explicit concurrent mark sweep GC freed 17486(948KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 24MB/36MB, paused 55.165ms total 453.598ms
,03-17 09:49:36.884  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:36.884  1022  1034 I ActivityManager: Killing 3087:com.sec.dsm.system/1000 (adj 15): empty #31
,03-17 09:49:36.904  1022  1382 I ActivityManager: Killing 3123:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-17 09:49:36.904  1022  1063 D PackageManager: delete codoeFile: 
,03-17 09:49:36.904  1916  1916 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 09:49:36.904  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.904  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.904  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:36.904  1022  1022 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:36.914  1022  1063 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-17 09:49:36.914  1022  1063 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-17 09:49:36.914  1916  1916 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 09:49:36.924  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:36.924  3981  3981 E Zygote  : MountEmulatedStorage()
03-17 09:49:36.924  3981  3981 E Zygote  : v2
03-17 09:49:36.924  3981  3981 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:36.924  3981  3981 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:36.924  1022  1063 D PackageManager: result of delete: 1{328544476}
03-17 09:49:36.924  3981  3981 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:36.924  3981  3981 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:36.924  3981  3981 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:36.924  1022  1022 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3981 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 09:49:36.934  1022  1047 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 09:49:36.934  1022  1047 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 09:49:36.934  1022  1047 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 09:49:36.934  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:36.934  3870  3870 D AndroidRuntime: Shutting down VM
,03-17 09:49:36.944  1022  1063 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 09:49:36.944  1022  1063 D PackageManager: userId{-1}
03-17 09:49:36.944  1022  1063 D PackageManager: andCode{true}
,03-17 09:49:36.964  3981  3981 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:36.964  3981  3981 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:36.964  1022  1504 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:36.964  1022  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:36.964  1022  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:36.964  3178  3291 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 09:49:36.974  1916  1916 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 09:49:36.994  1511  1511 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 09:49:36.994  1511  1511 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 09:49:37.014  1022  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.014  1022  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.014  1022  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.014  1022  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.034  4000  4000 E Zygote  : MountEmulatedStorage()
,03-17 09:49:37.034  4000  4000 E Zygote  : v2
03-17 09:49:37.034  4000  4000 I libpersona: KNOX_SDCARD checking this for 10003
03-17 09:49:37.034  4000  4000 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:37.034  4000  4000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:37.034  4000  4000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 09:49:37.034  1022  1063 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4000 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-17 09:49:37.034  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 09:49:37.034  3915  3915 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 09:49:37.044  4000  4000 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 09:49:37.044  3915  3915 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
03-17 09:49:37.044  1022  3949 W ActivityManager: userId = 0, bbcId = -10000,
03-17 09:49:37.044  1022  3949 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.044  1022  3949 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 09:49:37.044  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 09:49:37.044  1022  1600 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:37.044  1022  1600 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.044  1022  1600 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.044  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:37.054  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 09:49:37.054  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:37.054  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 09:49:37.054  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 09:49:37.064  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 09:49:37.064  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 09:49:37.064  1022  1047 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 09:49:37.064  1022  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:37.064  1022  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.064  1022  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.064  4000  4000 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 09:49:37.064  1022  1047 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-17 09:49:37.064  1022  1047 I CrashAnrDetector: onPackageRemoved : com.test.thalitest,
03-17 09:49:37.074  4000  4000 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:37.094  1022  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_3123/cgroup.procs: No such file or directory
03-17 09:49:37.094  1022  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_3087/cgroup.procs: No such file or directory
,03-17 09:49:37.104  3981  3981 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 09:49:37.114  1022  2835 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:37.114  1022  2835 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:37.114  1022  2835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 09:49:37.114  1022  1271 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.114  1022  1271 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.114  1022  1271 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.114  1022  1271 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.134  4020  4020 E Zygote  : MountEmulatedStorage()
03-17 09:49:37.134  4020  4020 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:37.134  4020  4020 E Zygote  : v2
03-17 09:49:37.134  4020  4020 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:37.134  4020  4020 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:37.134  1022  1271 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4020 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:37.134  4020  4020 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:37.134  4020  4020 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:37.144  3870  3870 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,03-17 09:49:37.164  4020  4020 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:37.164  4020  4020 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:37.184  3727  3948 E SQLiteLog: (283) recovered 85 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 09:49:37.184  4020  4020 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 09:49:37.184  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 09:49:37.184  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 09:49:37.184  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:37.194  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:37.194  3915  3915 D DialogFlow: initQueue()
,03-17 09:49:37.194  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:37.194  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:37.224  3956  4042 I Babel   : MmsConfig: mnc/mcc: 0/0
03-17 09:49:37.224  3956  4042 I Babel   : MmsConfig.loadMmsSettings
03-17 09:49:37.224  3956  4042 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-17 09:49:37.224  3956  4042 I Babel   : MmsConfig.loadFromDatabase
,03-17 09:49:37.244  4020  4020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-17 09:49:37.244  1022  3951 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.244  1022  3951 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.244  1022  3951 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.244  1022  3951 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.264  4044  4044 E Zygote  : MountEmulatedStorage(),
03-17 09:49:37.264  4044  4044 E Zygote  : v2
03-17 09:49:37.264  4044  4044 I libpersona: KNOX_SDCARD checking this for 10029
03-17 09:49:37.264  4044  4044 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:37.264  4044  4044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:37.264  1022  3951 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4044 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
,03-17 09:49:37.264  4044  4044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:37.274  4044  4044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:37.274  1022  1382 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:37.274  1022  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:37.274  1022  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-17 09:49:37.274  1022  1600 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:37.274  1022  1600 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.274  1022  1600 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.284  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.284  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.284  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.284  1022  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.284  4020  4020 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-17 09:49:37.284  4020  4020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-17 09:49:37.284  3956  4042 E Babel   : canonicalizeMccMnc: invalid mccmnc 
03-17 09:49:37.284  3956  4042 I Babel   : MmsConfig.loadFromResources
,03-17 09:49:37.294  3956  4042 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
03-17 09:49:37.294  3956  4042 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-17 09:49:37.294  4057  4057 E Zygote  : MountEmulatedStorage()
03-17 09:49:37.294  4057  4057 E Zygote  : v2
03-17 09:49:37.294  4057  4057 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:37.294  4057  4057 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:37.304  4057  4057 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:37.304  4057  4057 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:37.304  4057  4057 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:37.314  3956  4039 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 09:49:37.314  4044  4044 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:37.314  4044  4044 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:37.324  1022  1500 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4057 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 09:49:37.324  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:37.324  1022  1035 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:37.324  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-17 09:49:37.334  4057  4057 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:37.344  4057  4057 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:37.354  3956  3956 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 09:49:37.364  4020  4020 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-17 09:49:37.364  4020  4020 I F_PHONE : default registerAction()
03-17 09:49:37.364  4020  4020 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 09:49:37.364  4057  4057 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 09:49:37.364  3956  4039 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 09:49:37.374  3956  4039 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 09:49:37.394  3956  4039 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 09:49:37.394  3956  4039 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 09:49:37.404  3956  4039 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-17 09:49:37.404  3956  4039 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 09:49:37.404  3956  4039 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 09:49:37.404  3956  4039 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 09:49:37.414  4057  4057 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-17 09:49:37.414  4057  4057 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-17 09:49:37.414  1022  3951 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:37.414  1022  3951 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 09:49:37.414  1022  3951 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-17 09:49:37.424  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.424  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.424  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.424  1483  1483 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 09:49:37.424  1022  1035 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.424  1483  1483 D BluetoothBDTestService: onCreate()
,03-17 09:49:37.424  1483  1483 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-17 09:49:37.424  1483  1483 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-17 09:49:37.424  1483  1483 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
,03-17 09:49:37.434  3956  4039 W VideoCapabilities: Unsupported mime video/wvc1,
,03-17 09:49:37.434  3956  4039 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 09:49:37.444  4080  4080 E Zygote  : MountEmulatedStorage()
03-17 09:49:37.444  4080  4080 E Zygote  : v2
03-17 09:49:37.444  4080  4080 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:37.444  4080  4080 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:37.444  4080  4080 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 09:49:37.444  1022  1035 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4080 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:37.454  1022  3949 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:37.454  4080  4080 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:37.454  1022  3949 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.454  1022  3949 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.454  4080  4080 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:37.454  1022  1600 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:37.454  1022  1600 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.454  1022  1600 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.464  3956  4039 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-17 09:49:37.464  3956  4039 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 09:49:37.464  3956  4039 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 09:49:37.474  3956  4039 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-17 09:49:37.474  4080  4080 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:37.474  4080  4080 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:37.484  3956  4039 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-17 09:49:37.494  4080  4080 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 09:49:37.494  3956  4039 W VideoCapabilities: Unsupported mime video/mp43
,03-17 09:49:37.504  3956  4039 W VideoCapabilities: Unsupported mime video/sorenson
,03-17 09:49:37.514  3956  3956 V Babel   : babel boot account: SMS
,03-17 09:49:37.514  3956  3956 V Babel   : babel boot account: thalitester@gmail.com
,03-17 09:49:37.514  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.514  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.514  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.514  1022  2835 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.524  3956  4039 W VideoCapabilities: Unsupported mime video/mp4v-esdp,
03-17 09:49:37.534  4098  4098 E Zygote  : MountEmulatedStorage(),
03-17 09:49:37.534  4098  4098 E Zygote  : v2
03-17 09:49:37.534  4098  4098 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:37.534  4098  4098 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:37.534  4098  4098 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:37.534  4098  4098 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-17 09:49:37.534  4098  4098 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:37.534  1022  2835 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4098 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 09:49:37.534  1022  2835 I ActivityManager: Killing 3139:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-17 09:49:37.564  4098  4098 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 09:49:37.564  4098  4098 D ActivityThread: Added TimaKeyStore provider
03-17 09:49:37.564  1022  1569 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 09:49:37.564  3956  4039 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 09:49:37.564  1022  3949 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.564  1022  3949 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.564  1022  3949 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.564  1022  3949 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.574  4115  4115 E Zygote  : MountEmulatedStorage(),
03-17 09:49:37.574  4115  4115 E Zygote  : v2,
03-17 09:49:37.574  4115  4115 I libpersona: KNOX_SDCARD checking this for 10030
03-17 09:49:37.574  4115  4115 I libpersona: KNOX_SDCARD not a persona
,03-17 09:49:37.574  4115  4115 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:37.584  4115  4115 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:37.584  1022  3949 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4115 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 09:49:37.584  4115  4115 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-17 09:49:37.584  1022  3949 I ActivityManager: Killing 3160:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
03-17 09:49:37.594  4080  4080 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-17 09:49:37.594  1022  1101 V AlarmManager: waitForAlarm result :4
03-17 09:49:37.594  4080  4080 I KnoxUsageLogPro: premStatus:2
,03-17 09:49:37.604  4080  4122 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458204577614
,03-17 09:49:37.604  4080  4080 I KnoxUsageLogPro: isEulaShown : false
03-17 09:49:37.604  4080  4080 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-17 09:49:37.614  4115  4115 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:37.614  4115  4115 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:37.624  1022  1035 I ActivityManager: Killing 3205:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-17 09:49:37.624  1022  1101 V AlarmManager: waitForAlarm result :4
,03-17 09:49:37.634  2162  3997 D GCM     : COMPAT: Multi user not supported
,03-17 09:49:37.644  1022  3949 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:37.644  1022  3949 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 09:49:37.644  1022  3949 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.644  1916  1916 D GCM     : COMPAT: Multi user not supported
,03-17 09:49:37.654  1022  1510 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:37.654  1022  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.654  1022  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.654  1022  1142 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:37.654  1022  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.654  1022  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.654  1022  1035 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:37.664  1022  1035 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 09:49:37.664  1022  1035 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.664  1022  1271 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:37.664  1022  1271 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 09:49:37.664  1022  1271 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.674  1022  3949 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:37.674  1022  3949 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.674  1022  3949 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.684  1022  1510 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:37.684  1022  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 09:49:37.684  1022  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.694  1022  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_3139/cgroup.procs: No such file or directory
,03-17 09:49:37.694  1022  1047 W libprocessgroup: failed to open /acct/uid_1000/pid_3205/cgroup.procs: No such file or directory
03-17 09:49:37.694  1022  1047 W libprocessgroup: failed to open /acct/uid_10146/pid_3160/cgroup.procs: No such file or directory
,03-17 09:49:37.694  1022  2835 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:37.694  1022  2835 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.694  1022  2835 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.714  2162  3997 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 09:49:37.714  1022  3950 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:37.714  1022  3950 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.714  1022  3950 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.734  1022  1600 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:37.734  1022  1600 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.734  1022  1600 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:37.784  1022  3952 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:37.784  1022  3952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:37.784  1022  3952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 09:49:37.814  1022  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.814  1022  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.814  1022  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:37.814  1022  3950 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:37.824  2162  4087 I Icing   : Storage manager: low false usage 2.11MB avail 9.97GB capacity 11.63GB
,03-17 09:49:37.834  4139  4139 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:37.834  4139  4139 E Zygote  : MountEmulatedStorage()
03-17 09:49:37.834  4139  4139 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:37.834  4139  4139 E Zygote  : v2
03-17 09:49:37.834  4139  4139 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 09:49:37.834  4139  4139 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 09:49:37.834  4139  4139 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:37.844  1022  3950 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4139 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 09:49:37.844  1022  3950 I ActivityManager: Killing 3195:com.google.android.configupdater/u0a82 (adj 15): empty #31
,03-17 09:49:37.864  4139  4139 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:37.864  4139  4139 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:37.884  2162  2162 D SystemUpdateService: onCreate
,03-17 09:49:37.904  2162  4155 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 09:49:37.914  4139  4139 E KnoxSetupWizardClient: isShipMode : 1
,03-17 09:49:37.914  4139  4139 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 09:49:37.954  2162  2162 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 09:49:37.954  2162  4164 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 09:49:37.964  1022  1047 W libprocessgroup: failed to open /acct/uid_10082/pid_3195/cgroup.procs: No such file or directory
,03-17 09:49:37.964  2162  2162 D ChimeraCfgMgr: Reading stored module config
,03-17 09:49:37.974  3178  3291 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 09:49:37.984  2162  4164 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-17 09:49:38.044  4080  4122 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 42525
,03-17 09:49:38.054  3727  3948 E File    : fail readDirectory() errno=2
,03-17 09:49:38.054  3727  3999 I Gmail   : notifyAccountChanged
,03-17 09:49:38.064  3727  3903 I Gmail   : getAccountsCursor
,03-17 09:49:38.074  3727  3999 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 09:49:38.094  1022  1500 W ActivityManager: userId = 0, bbcId = -10000
03-17 09:49:38.094  1022  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:38.094  1022  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:38.104  3727  3999 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 09:49:38.104  2162  2162 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-17 09:49:38.114  2162  2162 D BootCompletedReceiver: Got an BootCompleted event.
,03-17 09:49:38.114  4139  4160 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
03-17 09:49:38.114  1022  3952 I ActivityManager: Killing 3278:com.dropbox.android/u0a88 (adj 15): empty #31
,03-17 09:49:38.124  4139  4160 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-17 09:49:38.124  4139  4160 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-17 09:49:38.124  4139  4160 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-17 09:49:38.124  4139  4160 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-17 09:49:38.124  4139  4160 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-17 09:49:38.124  4139  4160 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-17 09:49:38.124  4115  4115 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 09:49:38.124  4115  4115 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 09:49:38.124  4115  4115 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 09:49:38.124  4139  4139 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-17 09:49:38.134  3727  3999 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 09:49:38.134  3727  3999 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 09:49:38.134  2162  4156 I CheckinService: Checking schedule, now: 1458204578144 next: 1458299986961
,03-17 09:49:38.134  2162  4156 I CheckinService: active receiver: disabled
,03-17 09:49:38.144  2162  2162 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-17 09:49:38.144  3915  3980 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-17 09:49:38.164  4139  4139 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-17 09:49:38.164  4139  4139 D ShortcutReceiver:  KnoxContainerVersion 2.3.0
,03-17 09:49:38.164  4139  4139 D ShortcutReceiver:  shortcut migration not required 
,03-17 09:49:38.164  2162  4163 I SystemUpdateService: cancelUpdate (empty URL)
,03-17 09:49:38.164  2162  4163 I SystemUpdateService: active receiver: disabled
,03-17 09:49:38.164  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:38.164  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 09:49:38.164  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:38.164  1022  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 09:49:38.174  4115  4115 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 09:49:38.174  4115  4115 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 09:49:38.174  4115  4115 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 09:49:38.194  1645  1727 I art     : Explicit concurrent mark sweep GC freed 4225(179KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 894us total 61.998ms
,03-17 09:49:38.204  4173  4173 E Zygote  : MountEmulatedStorage()
03-17 09:49:38.204  4173  4173 I libpersona: KNOX_SDCARD checking this for 1000
03-17 09:49:38.204  4173  4173 E Zygote  : v2
03-17 09:49:38.204  4173  4173 I libpersona: KNOX_SDCARD not a persona
03-17 09:49:38.204  1645  1668 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-17 09:49:38.204  4173  4173 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 09:49:38.204  4173  4173 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 09:49:38.204  4173  4173 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 09:49:38.204  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 09:49:38.204  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 09:49:38.204  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:38.204  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 09:49:38.204  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:38.214  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 09:49:38.214  1022  1569 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4173 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 09:49:38.214  1022  1569 I ActivityManager: Killing 3319:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,03-17 09:49:38.214  4115  4115 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-17 09:49:38.214  4115  4115 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 09:49:38.224  2162  4087 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring for write failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs for write failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Could not open file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs
03-17 09:49:38.224  2162  4087 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.tags.h for write failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Trie initialize fail
03-17 09:49:38.224  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h for write failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage for write failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage for write failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
03-17 09:49:38.224  2162  4087 E Icing   : Init docstore failed
,03-17 09:49:38.224  2162  4087 E Icing   : Index init failed, resetting corpora
,03-17 09:49:38.254  2162  4164 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 09:49:38.264  4173  4173 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 09:49:38.264  4173  4173 D ActivityThread: Added TimaKeyStore provider
,03-17 09:49:38.274   291   291 E SMD     : DCD OFF
,03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.index failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Clearing index failed
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docids failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.perdocdata failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.cscoring failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.docs failed: Read-only file system
,03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-21 failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-3 failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user.__unseen__iim.a4a57c962707b0e8 failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user.__unseen__sq_ig.252f29a15a98237b failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tagacct.counts failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.h failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.n failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.x failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.s failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.urifps.deleted failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : D,eleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.usage failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.delusage failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Clearing docstore failed
03-17 09:49:38.274  2162  4087 E Icing   : Deleting file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/compact_status failed: Read-only file system
03-17 09:49:38.274  2162  4087 E Icing   : Deleting compact status failed
03-17 09:49:38.274  2162  4135 E Icing   : Not initialized
,03-17 09:49:38.294  3727  3897 E Gmail   : Search registration failed: 16
,03-17 09:49:38.294  1022  3949 W ActivityManager: userId = 0, bbcId = -10000
,03-17 09:49:38.294  1022  3949 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 09:49:38.294  1022  3949 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 09:49:38.314  1022  1047 W libprocessgroup: failed to open /acct/uid_10088/pid_3278/cgroup.procs: No such file or directory
03-17 09:49:38.314  1022  1047 W libprocessgroup: failed to open /acct/uid_10088/pid_3319/cgroup.procs: No such file or directory

```
