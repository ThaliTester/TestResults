#### Test 63036995fb62ea7_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
03-17 07:10:31.669  2883  2883 E Zygote  : MountEmulatedStorage()
03-17 07:10:31.669  2883  2883 E Zygote  : v2
03-17 07:10:31.669  2883  2883 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:31.669  2882  2882 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:51:18:22 
--------- beginning of system
03-17 07:10:31.669  2883  2883 I libpersona: KNOX_SDCARD checking this for 10099
03-17 07:10:31.669  2883  2883 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:31.679  1019  1570 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
03-17 07:10:31.679  2883  2883 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:31.679  2883  2883 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 07:10:31.679  2887  2887 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
03-17 07:10:31.679  1019  1031 I ActivityManager: Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=2883 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:31.699  2737  2898 I BooksConfig: GmsCore Version = 7.8.99 (2134222-436)
03-17 07:10:31.699  2883  2883 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:31.709  2883  2883 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:31.739  2682  2760 I bt_vendor: bluetooth satus is on
03-17 07:10:31.739  2682  2839 D bt_userial_mct: userial_open(port:0)
03-17 07:10:31.739  2682  2839 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
03-17 07:10:31.739  1970  2777 I Icing   : Internal init done: storage state 0
03-17 07:10:31.739  2682  2839 I bt_vendor: Done intiailizing UART
03-17 07:10:31.749  2682  2839 I bt_vendor: Done intiailizing UART
03-17 07:10:31.749  2682  2839 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
03-17 07:10:31.749  2682  2839 I bt_vendor: Bluetooth Firmware and transport layer are initialized
03-17 07:10:31.749  2682  2906 D bt_userial_mct: Entering userial_read_thread()
03-17 07:10:31.749  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:31.749  1019  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:31.749  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
03-17 07:10:31.749  1019  1715 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
03-17 07:10:31.759  1019  1528 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:31.759  1019  2775 D SSRM:a  : DeviceInfo:: 000000000000
03-17 07:10:31.759  1019  1528 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:31.759  1019  1528 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:31.759  1019  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 07:10:31.759  1019  2775 D SSRM:a  : SettingsAirViewInfo:: 000000000
,03-17 07:10:31.789  1695  1712 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-17 07:10:31.789  1695  1712 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 07:10:31.789  1695  1712 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 07:10:31.799  1695  1712 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-17 07:10:31.799  1695  1712 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 07:10:31.809  1019  1570 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
03-17 07:10:31.809  1019  1230 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
03-17 07:10:31.809  1019  1230 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:31.809  1019  1230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:31.809  1019  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 07:10:31.809  1019  1241 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:31.809  1019  1591 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 07:10:31.809  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:31.809  1019  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:31.819  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:31.819  1019  1591 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
03-17 07:10:31.819  2682  2836 I         : BTE_InitTraceLevels -- TRC_HCI
03-17 07:10:31.819  2682  2836 I         : BTE_InitTraceLevels -- TRC_L2CAP
03-17 07:10:31.819  2682  2836 I         : BTE_InitTraceLevels -- TRC_RFCOMM
03-17 07:10:31.819  2682  2836 I         : BTE_InitTraceLevels -- TRC_AVDT
03-17 07:10:31.819  2682  2836 I         : BTE_InitTraceLevels -- TRC_AVRC
03-17 07:10:31.819  2682  2836 I         : BTE_InitTraceLevels -- TRC_A2D
03-17 07:10:31.819  2682  2836 I         : BTE_InitTraceLevels -- TRC_BNEP
03-17 07:10:31.819  1019  1591 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
03-17 07:10:31.819  1019  1570 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
03-17 07:10:31.819  2682  2836 I         : BTE_InitTraceLevels -- TRC_BTM
03-17 07:10:31.829  2682  2836 I         : BTE_InitTraceLevels -- TRC_GAP
03-17 07:10:31.829  1019  1570 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 07:10:31.829  2682  2836 I         : BTE_InitTraceLevels -- TRC_PAN
03-17 07:10:31.829  2682  2836 I         : BTE_InitTraceLevels -- TRC_SAP
03-17 07:10:31.829  2682  2836 I         : BTE_InitTraceLevels -- TRC_SDP
03-17 07:10:31.829  2682  2836 I         : BTE_InitTraceLevels -- TRC_GATT
03-17 07:10:31.829  2682  2836 I         : BTE_InitTraceLevels -- TRC_SMP
03-17 07:10:31.829  2682  2836 I         : BTE_InitTraceLevels -- TRC_BTAPP
03-17 07:10:31.829  2682  2836 I         : BTE_InitTraceLevels -- TRC_BTIF
03-17 07:10:31.829  2682  2836 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
03-17 07:10:31.829  1019  1591 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 07:10:31.829  1019  1570 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
03-17 07:10:31.839  1019  1591 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 07:10:31.839  1019  1570 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
03-17 07:10:31.849  1019  1241 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:31.849  1019  1591 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 07:10:31.849  1019  1570 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
03-17 07:10:31.849  1970  2777 I Icing   : Post-init done
03-17 07:10:31.849  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:31.849  1019  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:31.849  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 07:10:31.849  1019  1570 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 07:10:31.849  1019  1570 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-17 07:10:31.859  1019  1570 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 07:10:31.859  1019  1570 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
03-17 07:10:31.859  1019  1570 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-17 07:10:31.859  1019  1570 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
03-17 07:10:31.859   302   302 E USB_UICC: Timeout! No signal received. Retry num = 29
03-17 07:10:31.869   330   330 I ServiceManager: Waiting for service AtCmdFwd...
03-17 07:10:31.879  1019  1367 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:31.889  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:31.889  1019  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:31.889  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:31.889  1695  1712 I NotificationStore: System rebooted after Notification storage file was last written
03-17 07:10:31.889  1695  1712 I NotificationStore: Deleting the file
03-17 07:10:31.909  1019  1591 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-17 07:10:31.909  1019  1570 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
03-17 07:10:31.919  1019  1591 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
03-17 07:10:31.919  1019  1591 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
03-17 07:10:31.919  1019  1570 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
03-17 07:10:31.929  2682  2836 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
03-17 07:10:31.939  2682  2836 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa44ad6e9 
03-17 07:10:31.939  2682  2836 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa44ad6e9 
03-17 07:10:31.949  2682  2767 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
03-17 07:10:31.949  2682  2767 E bt-btif : Calling BTA_HhEnable
03-17 07:10:31.959  2682  2767 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
03-17 07:10:31.959  2682  2767 D BluetoothAdapterProperties: Address is:7C:F9:0E:51:18:22
03-17 07:10:31.959  2682  2767 E BluetoothServiceJni: populateRssiValuesNative
03-17 07:10:31.959  2682  2767 I bluedroid: getModelRssiValues
03-17 07:10:31.959  2682  2767 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-17 07:10:31.959  2682  2767 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
03-17 07:10:31.959  2682  2767 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A5)
03-17 07:10:31.959  1019  1019 D SettingsProvider: name = bluetooth_name
03-17 07:10:31.959  1019  1715 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
03-17 07:10:31.969  1019  1715 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
03-17 07:10:31.969  2682  2767 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-17 07:10:31.969  2682  2767 D BluetoothAdapterProperties: Scan Mode:20
03-17 07:10:31.969  2682  2767 D BluetoothAdapterProperties: Discoverable Timeout:120
03-17 07:10:31.969  2682  2767 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:A2:30:44
03-17 07:10:31.969  2682  2767 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
03-17 07:10:31.969  2682  2767 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
03-17 07:10:31.969  2682  2767 E bt-btif : btif_sock_init: !radio_req && !rfc_init
03-17 07:10:31.969  1019  1019 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
03-17 07:10:31.969  1019  1019 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
03-17 07:10:31.969  2682  2906 E bt_mct  : hci lib postload completed
03-17 07:10:31.969  2682  2767 E bt-btif : btif_sock_init: !vhci_init
03-17 07:10:31.969  2682  2767 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
03-17 07:10:31.979  2682  2767 D IOP_DB_BT: db_open: db_open : handle 3026534416l, read 13894 bytes onto local cache
03-17 07:10:31.979  2682  2767 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
03-17 07:10:31.979  2682  2767 D IOP_DB_BT: db_query: result 1
03-17 07:10:31.979  2682  2767 I         : iop_db_open: iop_db_open status 0
03-17 07:10:31.979  2682  2767 D bte_conf: Device ID record 1 : primary
03-17 07:10:31.979  2682  2767 D bte_conf:   vendorId            = 0075
03-17 07:10:31.979  2682  2767 D bte_conf:   vendorIdSource      = 0001
03-17 07:10:31.979  2682  2767 D bte_conf:   product             = 0100
03-17 07:10:31.979  2682  2767 D bte_conf:   version             = 0200
03-17 07:10:31.979  2682  2767 D bte_conf:   clientExecutableURL = 
03-17 07:10:31.979  2682  2767 D bte_conf:   serviceDescription  = 
03-17 07:10:31.979  2682  2767 D bte_conf:   documentationURL    = 
03-17 07:10:31.979  2682  2767 D bte_conf: bte_load_did_conf no section named DID2.
03-17 07:10:31.979  2682  2767 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
03-17 07:10:31.979  2682  2760 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-17 07:10:31.979  2682  2760 D BluetoothAdapterProperties: ScanMode =  20
03-17 07:10:31.979  2682  2760 D BluetoothAdapterProperties: State =  11
03-17 07:10:31.979  1019  1241 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
03-17 07:10:31.979  2682  2760 D BluetoothAdapterProperties: Setting state to 12
03-17 07:10:31.979  2682  2760 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
03-17 07:10:31.989  1019  1713 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
03-17 07:10:31.989  1191  1832 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 07:10:31.989  1191  1832 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-17 07:10:31.989  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:31.989  1019  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:31.989  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
03-17 07:10:31.989  2682  2767 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-17 07:10:31.999  2682  2767 D BluetoothAdapterProperties: Scan Mode:21
03-17 07:10:31.999  1019  1031 D SettingsProvider: name = bluetooth_a2dp_sink_mode
03-17 07:10:31.999  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:31.999  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:31.999  1019  1031 D SettingsProvider: selectionArgs: false
03-17 07:10:31.999  1019  1031 D SettingsProvider: selectionArgs: 1002
03-17 07:10:31.999  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:31.999  1019  1031 D SettingsProvider: ret = -1
03-17 07:10:31.999  2682  2767 D BluetoothAdapterProperties: Discoverable Timeout:120
03-17 07:10:31.999  1019  1713 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:32.009  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.009  1019  1031 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
03-17 07:10:32.009  1019  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:32.009  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 07:10:32.009  2682  2760 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-17 07:10:32.009  2682  2760 D BluetoothAdapterService: updateAdapterState state is 12
03-17 07:10:32.009  1019  1241 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
03-17 07:10:32.009  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.009  1019  1241 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:32.009  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 07:10:32.029  1811  2022 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:32.029  2682  2760 D BluetoothAdapterService: Autoconnection is available 
03-17 07:10:32.029  2682  2760 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
03-17 07:10:32.029  2682  2760 D BluetoothAdapterService: starting service from this receiver
03-17 07:10:32.029  1811  2022 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:32.029  1191  1191 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
03-17 07:10:32.039  1019  1048 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:32.039  1019  1048 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:32.039  1019  1241 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
03-17 07:10:32.039  1479  1517 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:32.039  1479  1517 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:32.039  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.039  1019  1241 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:32.039  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
03-17 07:10:32.059  2682  2760 I BluetoothAdapterState: Entering On State from state = 11
03-17 07:10:32.059  1191  1191 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
03-17 07:10:32.059  1501  1515 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:32.059  1501  1515 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:32.059  2682  2682 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
03-17 07:10:32.059  2682  2694 D BluetoothA2dp: onBluetoothStateChange: up=true
03-17 07:10:32.069  2682  2769 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:32.069  2682  2769 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:32.069  1019  1048 D BluetoothA2dp: onBluetoothStateChange: up=true
03-17 07:10:32.069  1191  2754 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:32.069  1191  2754 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:32.069  1191  1191 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
03-17 07:10:32.069  2150  2163 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:32.069  2150  2163 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:32.069  2682  2682 I BluetoothPbapService: Handler(): got msg=1
03-17 07:10:32.079  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
03-17 07:10:32.079  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
03-17 07:10:32.079  1019  1528 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
03-17 07:10:32.079  1485  1513 D BluetoothAdapter: onBluetoothStateChange: up=true
03-17 07:10:32.079  1485  1513 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-17 07:10:32.079  2883  2883 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
03-17 07:10:32.079  1191  1191 I PhoneStatusBar: Icon Only
03-17 07:10:32.079  1019  1048 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
03-17 07:10:32.079  1191  1191 I StatusBar: Icon Only
03-17 07:10:32.079  1191  1191 D PanelView: There is/are notification(s) 
03-17 07:10:32.079  1191  1191 D PanelView: kidsfalse mQsExpansionEnabled:true
03-17 07:10:32.079  2907  2907 D AndroidRuntime: 
03-17 07:10:32.079  2907  2907 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 07:10:32.079  1019  1019 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-17 07:10:32.079  1019  1019 I InputMethodManagerService: [BT Setting State] State =12
03-17 07:10:32.079  1019  1019 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
03-17 07:10:32.089  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
03-17 07:10:32.089  1191  1191 I PhoneStatusBar: Icon Only
03-17 07:10:32.089  1191  1191 I StatusBar: Icon Only
03-17 07:10:32.089  1191  1191 D PanelView: There is/are notification(s) 
03-17 07:10:32.089  1191  1191 D PanelView: kidsfalse mQsExpansionEnabled:true
03-17 07:10:32.089  2907  2907 D AndroidRuntime: CheckJNI is OFF
03-17 07:10:32.089  2907  2907 D AndroidRuntime: readGMSProperty: start
03-17 07:10:32.089  2907  2907 D AndroidRuntime: readGMSProperty: already setted!!
03-17 07:10:32.089  2907  2907 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 07:10:32.089  2907  2907 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 07:10:32.089  2907  2907 D AndroidRuntime: readGMSProperty: end
03-17 07:10:32.089  2907  2907 D AndroidRuntime: addProductProperty: start
03-17 07:10:32.089  2682  2915 V BluetoothPbapService: PBAP Service initSocket try: 0
03-17 07:10:32.089  1479  1479 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@c5b080, true
03-17 07:10:32.089  1479  1479 D BluetoothHeadset: registerMessageListener
03-17 07:10:32.099  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 07:10:32.099  2682  2769 D HeadsetService: registerMessageListener
03-17 07:10:32.099  2682  2769 D HeadsetService: registerMessageListener
03-17 07:10:32.099  2682  2776 D HeadsetStateMachine: Disconnected process message: 70
03-17 07:10:32.099  2682  2776 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@392bef62
03-17 07:10:32.099  1479  1479 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
03-17 07:10:32.099  1479  1479 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
03-17 07:10:32.099  1695  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-17 07:10:32.109  2682  2915 D BluetoothSocket: bindListen(): myUserId = 0
03-17 07:10:32.109  2682  2915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-17 07:10:32.109  1695  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 07:10:32.109  1695  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 07:10:32.109  1695  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-17 07:10:32.109  1771  1771 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
03-17 07:10:32.109  1479  1479 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-17 07:10:32.109  1479  1479 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
03-17 07:10:32.109  1479  1479 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
03-17 07:10:32.109  2682  2776 D HeadsetStateMachine: Disconnected process message: 9
03-17 07:10:32.109  2682  2776 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
03-17 07:10:32.109  2682  2915 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
03-17 07:10:32.109  2682  2915 D BluetoothSocket: bindListen(), new LocalSocket 
03-17 07:10:32.109  2682  2915 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-17 07:10:32.109  2682  2915 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@270f8f3
03-17 07:10:32.109  2682  2915 D BluetoothSocket: channel: 19
03-17 07:10:32.109  2682  2915 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
03-17 07:10:32.109  1695  2089 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 07:10:32.109  2883  2883 E ActivityThread: Failed to find provider info for flipboard.auth.internal
03-17 07:10:32.119  1191  1191 D BluetoothTile:  onBluetoothStateChange:
03-17 07:10:32.119  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
03-17 07:10:32.119  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.119  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:32.119  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 07:10:32.129   286   710 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
03-17 07:10:32.129   286   710 V voice   : voice_set_parameters: enter: A2dpSuspended=false
03-17 07:10:32.129   286   710 V voice   : voice_set_parameters: exit with code(-2)
03-17 07:10:32.129   286   710 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
03-17 07:10:32.129   286   710 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-17 07:10:32.129   286   710 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-17 07:10:32.129   286   710 V audio_hw_primary: adev_set_parameters: exit
03-17 07:10:32.129  1695  1704 I art     : Explicit concurrent mark sweep GC freed 27802(1655KB) AllocSpace objects, 6(156KB) LOS objects, 39% free, 10MB/17MB, paused 1.185ms total 69.677ms
03-17 07:10:32.129  2682  2776 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
03-17 07:10:32.129  2682  2916 D BluetoothMapMasInstance: set MAP SDP message type : 1
03-17 07:10:32.139  1191  1727 D BluetoothTile:  handleUpdatestate:false name:null
03-17 07:10:32.139  1695  1706 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-17 07:10:32.139  1191  1191 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-17 07:10:32.149  1191  1191 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-17 07:10:32.149  1191  1191 D BluetoothTile:  getBluetoothState : 12
03-17 07:10:32.149  2737  2898 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 07:10:32.149  2682  2916 D BluetoothSocket: bindListen(): myUserId = 0
03-17 07:10:32.149  2682  2916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
03-17 07:10:32.149  1019  1032 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=88, mSplitNum[1]=125, mSplitNum[2]=162, mBgSplitQueueNum=3 divideNum= 36 r.nextReceiver= 51 receivers.size=198
03-17 07:10:32.149  1019  1032 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
03-17 07:10:32.159  1019  1032 I ActivityManager: Killing 1207:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
03-17 07:10:32.159  1191  1727 D BluetoothTile:  handleUpdatestate:false name:null
03-17 07:10:32.159  1019  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-17 07:10:32.169  1019  1241 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
03-17 07:10:32.169  1019  1019 I DrmEventReceiver: DrmEventReceiver : onReceive
03-17 07:10:32.169  1019  1019 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
03-17 07:10:32.169  1191  1727 D BluetoothTile:  handleUpdatestate:false name:null
03-17 07:10:32.169  1191  1191 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
03-17 07:10:32.169  1191  1191 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
03-17 07:10:32.169  1019  1019 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-17 07:10:32.169  1019  1019 I System.out: start Service
03-17 07:10:32.169  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-17 07:10:32.169  1019  1230 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:32.169  2737  2852 E BooksSync: Soft error
03-17 07:10:32.169  2737  2852 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 07:10:32.169  2737  2852 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 07:10:32.169  2682  2916 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
03-17 07:10:32.169  2682  2916 D BluetoothSocket: bindListen(), new LocalSocket 
03-17 07:10:32.169  2682  2916 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-17 07:10:32.169  2682  2916 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34e639b0
03-17 07:10:32.169  1019  1230 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.169  1019  1230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:32.169  1019  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 07:10:32.179  2737  2852 E BooksSync: Sync error
03-17 07:10:32.179  2737  2852 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 07:10:32.179  2737  2852 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 07:10:32.179  2737  2852 I BooksSync: Finished books sync
03-17 07:10:32.179  1019  1019 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
03-17 07:10:32.189  2682  2916 D BluetoothSocket: channel: 5
03-17 07:10:32.189  1261  1261 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
03-17 07:10:32.199  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.199  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.199  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.199  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.209   285   515 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 935
03-17 07:10:32.209   285   515 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 935
03-17 07:10:32.209  2930  2930 E Zygote  : MountEmulatedStorage()
03-17 07:10:32.209  2930  2930 E Zygote  : v2
03-17 07:10:32.209  2930  2930 I libpersona: KNOX_SDCARD checking this for 10085
03-17 07:10:32.209  2930  2930 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:32.209  2930  2930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:32.219  2930  2930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:32.219  2930  2930 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:32.219  1019  1044 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=2930 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:32.219  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.219  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.219  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.219  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.239  2907  2907 E AffinityControl: AffinityControl: registerfunction enter
03-17 07:10:32.259  2944  2944 E Zygote  : MountEmulatedStorage()
03-17 07:10:32.259  2944  2944 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:32.259  2944  2944 E Zygote  : v2
03-17 07:10:32.259  2944  2944 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:32.259  2944  2944 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:32.259  2944  2944 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:32.259  2944  2944 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:32.259  1019  1044 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2944 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:32.259  1019  1713 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
03-17 07:10:32.259  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.259  1019  1713 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:32.259  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 07:10:32.269  2907  2907 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 07:10:32.269  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 07:10:32.279  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.279  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:32.279  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:32.279  1019  2932 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
03-17 07:10:32.289  2930  2930 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:32.289  2930  2930 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:32.289  1019  1751 E PersonaManagerService: inState():  stateMachine is null !!
03-17 07:10:32.289  1019  1751 I PersonaManagerService: PersonaId don't exist
03-17 07:10:32.289  1019  1751 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 07:10:32.299  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 07:10:32.299  1019  1019 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
03-17 07:10:32.299  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.299  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:32.299  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:32.309  1019  1751 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 07:10:32.319  2930  2930 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:32.319  2930  2930 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:32.319  2930  2930 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:32.319  2930  2930 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:32.319  2930  2930 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:32.319  2930  2930 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-17 07:10:32.319  2944  2944 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:32.319  2944  2944 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:32.329  1019  1528 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 07:10:32.329  1019  1528 D SecContentProvider2: mCursor = null
03-17 07:10:32.329  1261  1261 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 07:10:32.329  1019  1751 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 07:10:32.329  1019  1751 W ActivityManager: mDVFSHelper.acquire()
03-17 07:10:32.329  1019  1751 D FocusedStackFrame: Set to : 0
03-17 07:10:32.339  1531  1531 D Launcher.HomeView: onPause
03-17 07:10:32.339  1531  1531 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 07:10:32.339  1019  1751 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 07:10:32.339  1019  1751 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 07:10:32.339  1019  1751 D InputDispatcher: Focused application set to: xxxx
03-17 07:10:32.339  1019  1751 D InputDispatcher: Focus left window: 1531
03-17 07:10:32.349  2907  2907 D AndroidRuntime: Shutting down VM
03-17 07:10:32.349  1019  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 07:10:32.349  1019  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 07:10:32.359  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
03-17 07:10:32.359  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.359  1019  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:32.359  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 07:10:32.359   285   285 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-17 07:10:32.359  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:32.359  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:32.359  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:32.359  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:32.359  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:32.359  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:32.369  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 07:10:32.369  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 07:10:32.369  1019  1751 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 07:10:32.379  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 07:10:32.379  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 07:10:32.379  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.379  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:32.379  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:32.379   257   257 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 07:10:32.389  1019  1528 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 07:10:32.389  1019  1528 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-17 07:10:32.389  1019  1528 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
03-17 07:10:32.389  1019  1230 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
03-17 07:10:32.389  1019  1230 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.389  1019  1230 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:32.389  1019  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 07:10:32.399  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 07:10:32.399  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 07:10:32.399  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.399  1019  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:32.399  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:32.409  1019  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.409  1019  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.409  1019  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.409  1019  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.419  2967  2967 E Zygote  : MountEmulatedStorage()
03-17 07:10:32.419  2967  2967 E Zygote  : v2
03-17 07:10:32.419  2967  2967 I libpersona: KNOX_SDCARD checking this for 10174
03-17 07:10:32.419  2967  2967 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:32.429  2967  2967 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:32.429  2967  2967 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:32.429  2967  2967 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 07:10:32.429  1019  1554 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2967 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 07:10:32.449  1019  1043 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 25446, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-17 07:10:32.459  1019  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 07:10:32.459  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.459  1019  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:32.459  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:32.459  1531  1531 V ActivityThread: updateVisibility : ActivityRecord{4a8d7f3 token=android.os.BinderProxy@3124fa51 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 07:10:32.469  1464  1464 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 07:10:32.469  1464  1464 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 07:10:32.479  2967  2967 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:32.479  2967  2967 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:32.479  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 07:10:32.479  1191  1191 D PowerUI : Cable  true --> true mBootCompleted : true
03-17 07:10:32.479  1191  1191 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-17 07:10:32.489  2682  2682 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 07:10:32.489  2682  2776 D HeadsetStateMachine: Disconnected process message: 10
03-17 07:10:32.489  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.489  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.489  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.489  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.499  2982  2982 E Zygote  : MountEmulatedStorage()
03-17 07:10:32.499  2982  2982 E Zygote  : v2
03-17 07:10:32.499  2982  2982 I libpersona: KNOX_SDCARD checking this for 10160
03-17 07:10:32.499  2982  2982 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:32.509  1019  1713 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=2982 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-17 07:10:32.509  2982  2982 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:32.509  1261  2965 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-17 07:10:32.509  1019  1713 I ActivityManager: Killing 1447:com.samsung.android.app.mirrorlink/1000 (adj 15): empty #31
03-17 07:10:32.509  1019  1230 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 07:10:32.509  1019  1230 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 07:10:32.509  1019  1230 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 07:10:32.509  2982  2982 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:32.519  2982  2982 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:32.519  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 07:10:32.519  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 07:10:32.519  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 07:10:32.519  1531  1531 D Launcher.HomeView: onStop
03-17 07:10:32.519  1531  1531 V ActivityThread: updateVisibility : ActivityRecord{4a8d7f3 token=android.os.BinderProxy@3124fa51 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 07:10:32.519  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 07:10:32.529  1019  1389 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 07:10:32.529  1019  1389 D SecContentProvider2: mCursor = null
03-17 07:10:32.529   318   318 I art     : Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 710us total 25.461ms
03-17 07:10:32.529  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 07:10:32.539  1019  1230 D PersonaManager: isKioskContainerExistOnDevice
03-17 07:10:32.549   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 661us total 17.700ms
03-17 07:10:32.559  1501  1501 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-17 07:10:32.559  1019  1019 I MotionRecognitionService: Plugged
03-17 07:10:32.559  2907  2907 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 07:10:32.559  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
03-17 07:10:32.569  2982  2982 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:32.569  2982  2982 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:32.569   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.174ms total 22.017ms
,03-17 07:10:32.579  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_1207/cgroup.procs: No such file or directory
,03-17 07:10:32.589  1019  1713 I ActivityManager: Killing 1431:com.sec.android.provider.emergencymode/u0a96 (adj 15): empty #31,
,03-17 07:10:32.589  1019  1019 D SensorService: [SO] activate (ident=0xb77edf60, enabled=0)
03-17 07:10:32.589  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 07:10:32.589  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 07:10:32.599  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,03-17 07:10:32.599  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:32.599  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:32.599  1019  1019 D SensorManager: unregisterListener ::   
03-17 07:10:32.599  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-17 07:10:32.599  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-17 07:10:32.609  1019  1019 D SensorService: [SO] changed settle time [1]
03-17 07:10:32.609  1019  1019 D SensorService: [SO] setDelay [66000000]
03-17 07:10:32.609  1019  1019 D SensorService: [SO] activate (ident=0xb7880c78, enabled=1)
03-17 07:10:32.609  1019  1019 D SensorService: [SO] AR_init
03-17 07:10:32.609  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 07:10:32.609  1019  1528 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-17 07:10:32.609  2982  2982 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:32.609  1019  1528 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:32.619  1019  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:32.619  1019  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 07:10:32.619  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:32.619  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.619  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.619  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:32.619  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 07:10:32.629  1531  1531 D Launcher: onTrimMemory. Level: 20
,03-17 07:10:32.639  1501  1501 D CscUpdateService: onStart
,03-17 07:10:32.639  1501  1501 E CscUpdateService: costomer file is exists : it has been preconfiged.
,03-17 07:10:32.649  1501  1501 I CscUpdateService: set_CSC_version
,03-17 07:10:32.649  1501  1501 E CscParser: update(): xml file exist
,03-17 07:10:32.649  2998  2998 E Zygote  : MountEmulatedStorage()
03-17 07:10:32.649  2998  2998 E Zygote  : v2
03-17 07:10:32.649  2998  2998 I libpersona: KNOX_SDCARD checking this for 10003
03-17 07:10:32.649  2998  2998 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:32.649  1261  2965 E SQLiteLog: (283) recovered 60 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
03-17 07:10:32.649  2998  2998 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:32.649  2998  2998 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:32.659  2998  2998 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:32.659  1019  1384 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=2998 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-17 07:10:32.659  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_1447/cgroup.procs: No such file or directory
,03-17 07:10:32.659  1019  1043 W libprocessgroup: failed to open /acct/uid_10096/pid_1431/cgroup.procs: No such file or directory
,03-17 07:10:32.669  1261  1261 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-17 07:10:32.669  1501  1501 I CscUtil : isWifiOnly = false
,03-17 07:10:32.679  1501  1501 I System.out: HandDataNode = null
03-17 07:10:32.679  1501  1501 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
,03-17 07:10:32.689  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 07:10:32.689  1501  1501 I CscUpdateService: This is normal boot : CSC not updated
,03-17 07:10:32.699  2998  2998 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:32.699  2998  2998 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:32.709  1501  3014 E CscParser: update(): xml file exist
,03-17 07:10:32.709  1501  3014 D CscGPS  : CSCGPS.updateParameters
03-17 07:10:32.709  1501  3014 D CscGPS  : supl host : null
03-17 07:10:32.709  1501  3014 D CscGPS  : SUPL Host is null or invalid
03-17 07:10:32.709  1501  3014 D CscGPS  : supl_ver : null
03-17 07:10:32.709  1501  3014 D CscGPS  : SUPL Ver is null or invalid
03-17 07:10:32.709  1501  3014 D CscGPS  : supl port : null
03-17 07:10:32.709  1501  3014 D CscGPS  : SUPL PORT is null or invalid
03-17 07:10:32.709  1501  3014 D CscGPS  : LPP : null
03-17 07:10:32.709  1501  3014 D CscGPS  : LPP is null or invalid
03-17 07:10:32.709  1501  3014 D CscGPS  : CSC don't have any AGPS value.
,03-17 07:10:32.729  1019  1031 D SettingsProvider: name = next_alarm_formatted
,03-17 07:10:32.729  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:32.729  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 07:10:32.729  1019  1031 D SettingsProvider: selectionArgs: false
03-17 07:10:32.729  1019  1031 D SettingsProvider: selectionArgs: 10085
03-17 07:10:32.729  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:32.729  1019  1031 D SettingsProvider: ret = -1
,03-17 07:10:32.729  1501  1521 D TP/MmsProvider: Update uri=content://mms, match=0
,03-17 07:10:32.729  1501  1521 D TP/MmsProvider: update , handleReadChangedBroadcast
03-17 07:10:32.729  1501  1521 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 07:10:32.739  1501  1501 I CscUpdateService: same CSC Version
,03-17 07:10:32.739  1501  1501 D CscUtil : Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOE6:user/release-keys
03-17 07:10:32.739  2432  2432 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-17 07:10:32.739  2432  2432 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 3691.818072
03-17 07:10:32.739  2432  2432 I Mms/ReservationManager: resetAfterConnected()
,03-17 07:10:32.739  2967  2967 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-17 07:10:32.739  1501  1748 D TP/MmsSmsProvider: query,matched:7, calling pid = 2432
,03-17 07:10:32.739  1501  1748 D TP/MmsSmsProvider: match 7:Elapsed time : 1.513 ms
,03-17 07:10:32.739  2432  3017 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 07:10:32.739  2432  3017 D Mms/TelephonyPermission: isDefault true
,03-17 07:10:32.749  1501  1515 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2432
,03-17 07:10:32.749  2432  2432 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 07:10:32.749  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,03-17 07:10:32.759  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:32.759  1019  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:32.759  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-17 07:10:32.759  1019  1041 D SensorService: [SO] currT = 36131076000, prevT = 35821172000, diff = 309904000, [0.172 0.402 10.228]
,03-17 07:10:32.759  1019  1041 D SensorService: [SO] 0.172 0.402 10.228
03-17 07:10:32.759  1019  1041 D SensorService: [SO] [100 -> 255]
03-17 07:10:32.759  2967  2967 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 6131-6132)
03-17 07:10:32.759  2967  2967 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 07:10:32.769  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.769  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.769  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:32.769  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:32.779  3023  3023 E Zygote  : MountEmulatedStorage()
03-17 07:10:32.779  3023  3023 E Zygote  : v2
03-17 07:10:32.779  3023  3023 I libpersona: KNOX_SDCARD checking this for 10048
03-17 07:10:32.779  3023  3023 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:32.779  3023  3023 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:32.779  3023  3023 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:32.779  1019  1032 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3023 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 07:10:32.789  3023  3023 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:32.789  2432  2432 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-17 07:10:32.789  2432  3021 D Mms/TelephonyPermission: isDefault true
03-17 07:10:32.789  2432  3021 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-17 07:10:32.789  2432  3021 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 52.513177
03-17 07:10:32.789  2967  2967 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {272c13c6}
03-17 07:10:32.789  1501  1521 D TP/MmsSmsProvider: query,matched:200, calling pid = 2432
,03-17 07:10:32.799  2967  2967 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 07:10:32.799  2967  2967 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 07:10:32.819  2982  2982 D [0]UMC:UMCContentProvider: @onCreate
,03-17 07:10:32.829  2967  2967 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 07:10:32.829  2967  2967 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:32.829  2967  2967 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 07:10:32.849  1019  1031 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,03-17 07:10:32.859  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:32.859   302   302 E USB_UICC: Timeout! No signal received. Retry num = 30
,03-17 07:10:32.859  3023  3023 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:32.859  3023  3023 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:32.869  2967  2967 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 07:10:32.869   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 07:10:32.879  2967  2967 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 07:10:32.879  2967  2967 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 07:10:32.879  2967  2967 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 07:10:32.879  2967  2967 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 07:10:32.879  2967  2967 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 07:10:32.879  2967  2967 I Adreno-EGL: Local Branch: 
03-17 07:10:32.879  2967  2967 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 07:10:32.879  2967  2967 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 07:10:32.879  2967  2967 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 07:10:32.979  2930  2930 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 121.001ms
,03-17 07:10:32.979   302   302 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 07:10:32.979   302   302 E USB_UICC: usb_uicc_init_qmi failed ! 
,03-17 07:10:32.979   302   302 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 07:10:32.979   302   302 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-17 07:10:33.009  1019  1389 I art     : Explicit concurrent mark sweep GC freed 58301(3MB) AllocSpace objects, 29(1346KB) LOS objects, 33% free, 26MB/40MB, paused 2.798ms total 219.304ms
,03-17 07:10:33.009  1501  1521 D TP/MmsSmsProvider: match 200:Elapsed time : 219.065 ms
,03-17 07:10:33.029   257   451 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,03-17 07:10:33.029  2982  2982 D [0]UMC:Core: onCreate(): 
,03-17 07:10:33.029  2982  2982 D [0]UMC:Core: @isManagedProfileUser
03-17 07:10:33.029  2982  2982 D [0]UMC:Core: userId: 0
,03-17 07:10:33.049  2982  2982 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
03-17 07:10:33.049  2982  2982 D [0]UMC:Core: userInfo.isManagedProfile() : false
,03-17 07:10:33.049  1019  1751 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,03-17 07:10:33.049  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:33.049  1019  1751 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:33.049  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-17 07:10:33.059  1261  2965 D MediaScanner: Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-17 07:10:33.059  1501  1521 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-17 07:10:33.059  1501  1521 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
,03-17 07:10:33.059  1019  1384 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,03-17 07:10:33.059  1501  1515 D TP/SmsProvider: query,matched:0, calling pid = 2432
,03-17 07:10:33.059  2998  3059 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,03-17 07:10:33.059  1501  1521 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 07:10:33.059  1501  1521 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
03-17 07:10:33.069  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:33.069  1019  1384 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:33.069  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-17 07:10:33.069  1501  1515 D TP/SmsProvider: match 0:Elapsed time : 3.455 ms
,03-17 07:10:33.069  1501  1521 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-17 07:10:33.069  1501  1521 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:33.069  1501  1521 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:33.069  1501  1521 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:33.069  1501  1521 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:33.069  1501  1521 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:33.069  1501  1521 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 07:10:33.069  3023  3023 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 07:10:33.069  3023  3023 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:33.069  3023  3023 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-17 07:10:33.079  1501  1521 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-17 07:10:33.079  1501  1521 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 07:10:33.079  1019  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:33.079  1019  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.079  1019  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.079  1019  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:33.089  2998  3059 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,03-17 07:10:33.089   382   382 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2998
03-17 07:10:33.089   382   382 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,03-17 07:10:33.089  2998  3059 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,03-17 07:10:33.089  2998  3059 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,03-17 07:10:33.089  3061  3061 E Zygote  : MountEmulatedStorage()
,03-17 07:10:33.089  3061  3061 E Zygote  : v2
03-17 07:10:33.089  3061  3061 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:33.089  3061  3061 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:33.099  3061  3061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:33.099  1019  1528 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3061 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:33.099  3061  3061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:33.099  3061  3061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:33.099   382   382 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2998
03-17 07:10:33.099   382   382 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,03-17 07:10:33.109  2432  3021 D Mms/Conversation: deleteTempConversation(),deleted=0
,03-17 07:10:33.109  1501  1515 D TP/SmsProvider: query,matched:51, calling pid = 2432
,03-17 07:10:33.109  1501  1515 D TP/SmsProvider: match 51:Elapsed time : 1.082 ms
,03-17 07:10:33.119  1501  1521 D SmsProvider: Update uri=content://sms/outbox, match=8
,03-17 07:10:33.119  2982  2982 D [0]UMC:DeviceInfo: USA==US==
,03-17 07:10:33.119  1501  1521 D TP/MmsSmsProvider: need read changed broadcast:false,
,03-17 07:10:33.119  2432  3021 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-17 07:10:33.119  2432  3021 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-17 07:10:33.119  2432  3021 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
,03-17 07:10:33.129  3061  3061 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:33.129  3061  3061 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:33.129  1501  1748 D TP/SmsProvider: query,matched:26, calling pid = 2432
,03-17 07:10:33.129  1501  1748 D TP/SmsProvider: match 26:Elapsed time : 2.523 ms
,03-17 07:10:33.139  2432  3021 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 07:10:33.139  2432  3021 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 07:10:33.139  2432  3021 D Mms/TelephonyPermission: isDefault true
,03-17 07:10:33.149  1501  1521 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2432
,03-17 07:10:33.169  1019  1389 D SettingsProvider: name = block_emergency_message
,03-17 07:10:33.169  1019  1389 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:33.169  1019  1389 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:33.169  1019  1389 D SettingsProvider: selectionArgs: false
03-17 07:10:33.169  1019  1389 D SettingsProvider: selectionArgs: 10048
03-17 07:10:33.169  1019  1389 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:33.169  1019  1389 D SettingsProvider: ret = -1
03-17 07:10:33.169  1019  1528 W ActivityManager: getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,03-17 07:10:33.179  1501  3074 D TP/MmsSmsProvider: query,matched:200, calling pid = 2432
03-17 07:10:33.179  1501  3074 D TP/MmsSmsProvider: match 200:Elapsed time : 1.005 ms
,03-17 07:10:33.189  1501  1515 I art     : Explicit concurrent mark sweep GC freed 40542(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 7MB/12MB, paused 1.112ms total 75.123ms
,03-17 07:10:33.189  1019  1384 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,03-17 07:10:33.189  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:33.189  1019  1384 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:33.189  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,03-17 07:10:33.199  1353  1353 I WifiCredService: onCreate
,03-17 07:10:33.199  1501  1748 D TP/SmsProvider: query,matched:0, calling pid = 2432
,03-17 07:10:33.199  2432  3017 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 07:10:33.209  1501  1748 D TP/SmsProvider: match 0:Elapsed time : 1.828 ms
,03-17 07:10:33.209  1608  1616 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 07:10:33.219  1353  1353 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 07:10:33.219  1353  1353 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 07:10:33.219  1353  1353 D MY_TAG  : Action boot completed received
,03-17 07:10:33.219  1353  1353 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,03-17 07:10:33.219  1019  1133 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 07:10:33.219  1019  1133 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 07:10:33.229  1019  1133 E WifiNative-wlan0: invaild command id : 215
,03-17 07:10:33.229  1501  1521 D TP/SmsProvider: query,matched:51, calling pid = 2432
,03-17 07:10:33.239  1501  1521 D TP/SmsProvider: match 51:Elapsed time : 1.859 ms
,03-17 07:10:33.239  1531  1531 D Launcher.Model: reloadBadges entered.
,03-17 07:10:33.239  3061  3061 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-17 07:10:33.239  1608  1623 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 07:10:33.239  1608  1623 D BadgeProvider: sendNotify, [notify] : null
03-17 07:10:33.239  1608  1623 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 07:10:33.239  1608  1623 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 07:10:33.239  1608  1623 D BadgeProvider: update, [UpdateCount] : 1
,03-17 07:10:33.249  2432  3017 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 07:10:33.249  2432  3017 D Mms/MessagingNotification: remove alarm
,03-17 07:10:33.259  1501  1515 D TP/SmsProvider: query,matched:0, calling pid = 2432
,03-17 07:10:33.259  2432  3021 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 07:10:33.259  1501  1515 D TP/SmsProvider: match 0:Elapsed time : 1.215 ms
,03-17 07:10:33.259  3061  3061 D DSM     : [Lines:107] Normal booted
,03-17 07:10:33.259  3061  3061 D DSM     : [Lines:114] Boot completed
,03-17 07:10:33.269  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.269  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.269  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.269  2432  3017 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 481.963073
03-17 07:10:33.269  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:33.269  1608  1623 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 07:10:33.279  3087  3087 E Zygote  : MountEmulatedStorage()
03-17 07:10:33.279  3087  3087 E Zygote  : v2
03-17 07:10:33.279  3087  3087 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:33.279  3087  3087 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:33.279  3087  3087 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:33.289  3087  3087 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:33.289  1019  1715 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3087 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:33.289  3087  3087 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:33.289  2432  3086 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 07:10:33.309  1353  1353 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
,03-17 07:10:33.309  3087  3087 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:33.309  1353  1353 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
,03-17 07:10:33.309  3087  3087 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:33.309  1353  1353 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
,03-17 07:10:33.319  1353  1353 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,03-17 07:10:33.319  1019  1751 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,03-17 07:10:33.319  1353  3102 V NearbySettings: MountReceiver.mPrefHandler - 7002
,03-17 07:10:33.319  2982  2982 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,03-17 07:10:33.329  3087  3087 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 07:10:33.349  1531  1531 D Launcher.Model: reloadBadges entered.
,03-17 07:10:33.349  1608  1616 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
,03-17 07:10:33.349  1608  1616 D BadgeProvider: sendNotify, [notify] : null
,03-17 07:10:33.349  1608  1616 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 07:10:33.349  1608  1616 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 07:10:33.349  1608  1616 D BadgeProvider: update, [UpdateCount] : 1
,03-17 07:10:33.349  2982  2982 D [0]UMC:AdminManager: init - start
,03-17 07:10:33.359  2432  3021 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 07:10:33.359  2432  3021 D Mms/MessagingNotification: remove alarm
,03-17 07:10:33.359  2982  2982 D [0]UMC:AdminManager: loadAdmins
,03-17 07:10:33.359  1019  1230 I ActivityManager: Killing 1761:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
,03-17 07:10:33.369  1501  1515 D TP/SmsProvider: query,matched:0, calling pid = 2432
,03-17 07:10:33.369  1501  1515 D TP/SmsProvider: match 0:Elapsed time : 1.264 ms
,03-17 07:10:33.369  2432  3106 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 07:10:33.369  2967  2967 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:33.379  2432  3021 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 106.621875
,03-17 07:10:33.379  2982  2982 D [0]UMC:AdminManager: init - end
,03-17 07:10:33.379  2982  2982 D GSLBManager: migrateStoredUrlFromOldPref
,03-17 07:10:33.389  1019  1384 I ActivityManager: Killing 1582:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,03-17 07:10:33.399  1261  2965 V MediaScanner: processDirectory :  /system/media
,03-17 07:10:33.399  1353  1353 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
,03-17 07:10:33.409  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 07:10:33.409  1353  1353 I NearbySettings: MountReceiver.onReceive - Internal Path
,03-17 07:10:33.409  1019  1367 D SettingsProvider: name = personal_mode_enabled
,03-17 07:10:33.429  2967  2967 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 07:10:33.429  1261  2965 V MediaScanner:  prescan time: 676ms (DB items: 141)
03-17 07:10:33.429  1261  2965 V MediaScanner:     scan time: 153ms (Caching mode: true), (makeEntry time: 22ms ~14%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 07:10:33.429  1261  2965 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 07:10:33.429  1261  2965 V MediaScanner:    total time: 829ms
03-17 07:10:33.429  1261  2965 V MediaScanner: checked files: 133  directories : 6  (I: 0, U: 0)
,03-17 07:10:33.429  1261  2965 D MediaScanner: checkDefaultSounds
03-17 07:10:33.429  1261  2965 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
03-17 07:10:33.429  3087  3087 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 07:10:33.439  1261  2965 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-17 07:10:33.439  2967  2967 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 07:10:33.439  2967  2967 D PhoneWindow: *FMB* installDecor flags : -2139027200
03-17 07:10:33.439  1261  2965 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
03-17 07:10:33.439  1261  2965 D MediaScanner: OK. notification_sound is already exist in setting DB.
03-17 07:10:33.439  1261  2965 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
03-17 07:10:33.439  1261  2965 D MediaScanner: OK. ringtone is already exist in setting DB.
,03-17 07:10:33.439  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-17 07:10:33.439  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
03-17 07:10:33.449  1261  2965 D MediaScannerService: !@done scanning volume internal
03-17 07:10:33.449  2655  2655 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2655) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 07:10:33.449  2655  2655 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2655) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-17 07:10:33.449  2655  2655 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2655) ACTION_MEDIA_SCANNER_FINISHED = Ignored
03-17 07:10:33.449  3087  3087 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,03-17 07:10:33.449  2967  2967 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 07:10:33.449  1261  2965 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,03-17 07:10:33.449  1501  1501 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 07:10:33.449  1501  1501 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-17 07:10:33.449  1501  1501 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:33.459  1501  1501 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:33.459  1501  1501 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:33.459  1501  1501 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:33.459  2967  2967 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 07:10:33.459  2967  2967 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:33.459  1261  2965 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-17 07:10:33.459  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:33.459  1261  2965 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-17 07:10:33.469  2982  2982 D GSLBManager:  key : segd-api
03-17 07:10:33.469  2982  2982 D GSLBManager:  value : https://eu-segd-api.secb2b.com:443/v2
,03-17 07:10:33.469  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:33.469  1261  2965 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,03-17 07:10:33.469  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:33.469  1261  2965 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 07:10:33.469  1261  2965 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-17 07:10:33.469  1261  2965 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-17 07:10:33.469  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:33.469  1261  2965 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,03-17 07:10:33.479  1019  1043 W libprocessgroup: failed to open /acct/uid_10138/pid_1761/cgroup.procs: No such file or directory
,03-17 07:10:33.479  1261  2965 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-17 07:10:33.479  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,03-17 07:10:33.489  1019  1043 W libprocessgroup: failed to open /acct/uid_10057/pid_1582/cgroup.procs: No such file or directory
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 07:10:33.499  1353  1353 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 07:10:33.499  1353  1353 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-17 07:10:33.499  1261  2965 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,03-17 07:10:33.499  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,03-17 07:10:33.509  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3,
03-17 07:10:33.509  2982  2982 D GSLBManager:  key : umc-cdn
03-17 07:10:33.509  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 07:10:33.509  2982  2982 D GSLBManager:  value : 
,03-17 07:10:33.509  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-17 07:10:33.509  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,03-17 07:10:33.509  3087  3087 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,03-17 07:10:33.519  3087  3087 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,03-17 07:10:33.519  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.519  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.519  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.519  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:33.519  1261  2965 V MediaScanner: processDirectory :  /storage/emulated/0
,03-17 07:10:33.529  1353  1353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:33.529  1261  2965 D MediaScanner: Skipping:
03-17 07:10:33.529  1261  2965 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
,03-17 07:10:33.529  1261  2965 D MediaScanner: Skipping:,
03-17 07:10:33.529  1261  2965 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,03-17 07:10:33.529  3114  3114 E Zygote  : MountEmulatedStorage()
,03-17 07:10:33.529  3114  3114 E Zygote  : v2
03-17 07:10:33.529  3114  3114 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:33.529  3114  3114 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:33.539  3114  3114 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:33.539  1261  2965 V MediaScanner: processDirectory :  /storage/extSdCard
03-17 07:10:33.539  1261  2965 W MediaScanner: Error opening directory, reason : Permission denied.
03-17 07:10:33.539  1261  2965 W MediaScanner: 7klwibgf7fxlKdCbid7
,03-17 07:10:33.539  1019  1367 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3114 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 07:10:33.549  1019  1367 I ActivityManager: Killing 2150:com.vlingo.midas/u0a31 (adj 15): empty #31
03-17 07:10:33.549  1261  2965 V MediaScanner:  prescan time: 37ms (DB items: 27)
03-17 07:10:33.549  1261  2965 V MediaScanner:     scan time: 21ms (Caching mode: true), (makeEntry time: 15ms ~71%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 07:10:33.549  1261  2965 V MediaScanner: postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 07:10:33.549  1261  2965 V MediaScanner:    total time: 61ms
03-17 07:10:33.549  1261  2965 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
,03-17 07:10:33.549  3114  3114 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 07:10:33.549  1353  1353 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-17 07:10:33.549  3114  3114 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:33.559  1261  2965 D MediaScannerService: !@done scanning volume external
,03-17 07:10:33.569  2982  2982 D GSLBManager:  key : segp-api
03-17 07:10:33.569  2982  2982 D GSLBManager:  value : 
,03-17 07:10:33.569  2655  2655 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2655) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 07:10:33.569  2655  2655 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2655) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-17 07:10:33.569  2655  2655 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2655) ...
03-17 07:10:33.569  2655  2655 D FactoryTestApp: [Support$Values.getString](2655) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 07:10:33.569  2655  2655 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2655) mConnectionMode = gsm
03-17 07:10:33.569  2655  2655 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2655) Create IPCWriterToSecPhoneService
03-17 07:10:33.569  2655  2655 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2655)  
,03-17 07:10:33.579  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.579  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.579  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.579  2655  2655 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
03-17 07:10:33.579  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:33.589  3114  3114 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:33.589  3114  3114 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:33.589  3131  3131 E Zygote  : MountEmulatedStorage()
,03-17 07:10:33.589  3131  3131 E Zygote  : v2
03-17 07:10:33.589  3131  3131 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:33.589  3131  3131 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:33.589  3131  3131 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:33.589  1019  1230 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3131 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:33.599  1019  1230 I ActivityManager: Killing 2178:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
,03-17 07:10:33.599  3131  3131 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:33.599  1019  1715 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-17 07:10:33.599  3131  3131 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:33.599  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:33.599  1019  1715 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:33.599  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,03-17 07:10:33.619  2967  3140 D OpenGLRenderer: Render dirty regions requested: true
,03-17 07:10:33.619  1019  1384 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 07:10:33.619  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 07:10:33.619  1019  1384 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 07:10:33.619  1019  1384 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 07:10:33.619  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 07:10:33.619  2967  3047 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 07:10:33.629  2967  2967 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 07:10:33.629  2967  2967 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 07:10:33.639  3131  3131 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:33.639  3131  3131 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:33.649   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 07:10:33.649  2655  2655 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2655) connected done
03-17 07:10:33.649  2655  2655 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2655) Send Response Message to SecPhone
03-17 07:10:33.649  2655  2655 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2655) Response ��
,03-17 07:10:33.659   324  1075 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 07:10:33.659  1019  1713 D InputDispatcher: Focus entered window: 2967
,03-17 07:10:33.669  2655  2655 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2655) Send BOOTING COMPLETED done
03-17 07:10:33.669  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 07:10:33.669  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 07:10:33.669  2967  2967 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 07:10:33.669  2967  3140 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 07:10:33.679  2967  3140 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 07:10:33.679  1019  1043 W libprocessgroup: failed to open /acct/uid_10031/pid_2150/cgroup.procs: No such file or directory
03-17 07:10:33.679  2967  3140 D OpenGLRenderer: Enabling debug mode 0
03-17 07:10:33.679  1019  1043 W libprocessgroup: failed to open /acct/uid_10050/pid_2178/cgroup.procs: No such file or directory
,03-17 07:10:33.679  3131  3131 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
,03-17 07:10:33.699  1353  1353 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-17 07:10:33.699  1353  1353 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
,03-17 07:10:33.699  1353  1353 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-17 07:10:33.719  3114  3114 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 07:10:33.749  1353  1353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,03-17 07:10:33.749  1353  3152 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-17 07:10:33.759  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.759  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.759  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.759  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:33.759   324  1075 D AT_Distributor: SetAtdStatus(), 1_1_0,
03-17 07:10:33.759   324  1075 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 07:10:33.769  3153  3153 E Zygote  : MountEmulatedStorage()
,03-17 07:10:33.769  3153  3153 E Zygote  : v2
03-17 07:10:33.769  3153  3153 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:33.769  3153  3153 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:33.769  3153  3153 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 07:10:33.769  1019  1384 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3153 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:33.779  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 07:10:33.779  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.779  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.779  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:33.779  3153  3153 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 07:10:33.779  3153  3153 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:33.789  3163  3163 E Zygote  : MountEmulatedStorage()
03-17 07:10:33.789  3163  3163 E Zygote  : v2
03-17 07:10:33.789  3163  3163 I libpersona: KNOX_SDCARD checking this for 10150
03-17 07:10:33.789  3163  3163 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:33.799  1019  1713 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3163 uid=10150 gids={50150, 9997} abi=armeabi-v7a,
,03-17 07:10:33.799  3153  3153 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:33.799  3153  3153 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:33.819  3153  3153 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:33.829  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.829  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.829  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:33.829  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:33.839  3174  3174 E Zygote  : MountEmulatedStorage(),
03-17 07:10:33.849  3174  3174 E Zygote  : v2
,03-17 07:10:33.849  1019  1715 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3174 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,03-17 07:10:33.849  3174  3174 I libpersona: KNOX_SDCARD checking this for 10086
,03-17 07:10:33.849  3174  3174 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:33.859   291   291 E SMD     : DCD OFF,
,03-17 07:10:33.869  3163  3163 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 07:10:33.869  3163  3163 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:33.869  3163  3163 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:33.869  3174  3174 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:33.869   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 07:10:33.879  3174  3174 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:33.879  3174  3174 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:33.889  3163  3163 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:33.889  3163  3163 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:33.899  3174  3174 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:33.899  3174  3174 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:33.899  3153  3153 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 07:10:33.909  1970  3109 I iu.UploadsManager: #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
03-17 07:10:33.909  2982  2982 D GSLBManager:  key : myknoxapi
03-17 07:10:33.909  2982  2982 D GSLBManager:  value : 
,03-17 07:10:33.919  2982  2982 D GSLBManager: migrateStoredUrlFromOldPref : Finished Migrating
,03-17 07:10:33.919  2982  2982 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 07:10:33.919  2982  2982 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 07:10:33.929  2982  2982 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 07:10:33.929  2982  2982 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 07:10:33.929  2982  2982 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 07:10:33.939  1019  1751 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 07:10:33.939  2982  2982 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-17 07:10:33.939  2982  2982 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 07:10:33.949  2982  2982 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 07:10:33.959  2682  2781 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-17 07:10:33.959  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 07:10:33.959  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:33.959  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:33.959  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
03-17 07:10:33.969  2982  2982 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
03-17 07:10:33.969  2982  2982 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-17 07:10:33.969  2982  2982 D [0]UMC:CoreReceiver:  check PreETag 
,03-17 07:10:33.979  1970  3109 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 70 ms
,03-17 07:10:33.979  2682  2781 D BluetoothMediaBrowser: no now playing list
03-17 07:10:33.979  2682  2781 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-17 07:10:34.009   382   382 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,03-17 07:10:34.019  1019  1528 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 07:10:34.029  1191  1191 I StatusBar: Icon Only
03-17 07:10:34.029  1191  1191 D PanelView: There is/are notification(s) 
,03-17 07:10:34.029  1019  1050 I ActivityManager: Displayed Component not be shown by security: +1s623ms
,03-17 07:10:34.039  1019  3202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 07:10:34.039  2982  2982 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-17 07:10:34.039  1019  1050 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 07:10:34.039  2982  2982 V [0]UMC:ProfileStorage: Enter loadList
03-17 07:10:34.039  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3a3d9471 u0 com.test.thalitest/.MainActivity t236} time:37413
03-17 07:10:34.039  1019  1050 W ActivityManager: mDVFSHelper.release()
03-17 07:10:34.039  1019  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 07:10:34.039  2982  2982 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
,03-17 07:10:34.039  2982  2982 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 07:10:34.039  2967  2967 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@86ed350 time:37416
,03-17 07:10:34.039  2982  2982 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 07:10:34.049  2982  2982 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 07:10:34.049  2982  2982 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 07:10:34.049  2982  2982 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 07:10:34.049  1771  1771 I SamsungIME: getCurrentCandidateView
,03-17 07:10:34.049  1019  1230 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 07:10:34.049  2982  2982 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
,03-17 07:10:34.049  2982  2982 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 07:10:34.059  2982  2982 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 07:10:34.059  2998  3059 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,03-17 07:10:34.059  2998  3059 I SecureStorage: [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,03-17 07:10:34.069  3153  3153 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 07:10:34.079  2982  2982 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-17 07:10:34.079  2982  2982 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
03-17 07:10:34.079  2982  2982 I [0]UMC:Core: shutdown
,03-17 07:10:34.079  1019  1751 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 07:10:34.079  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.079  1019  1751 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.079  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 07:10:34.079  2982  2982 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-17 07:10:34.089  2982  2982 I art     : System.exit called, status: 0
03-17 07:10:34.089  2982  2982 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-17 07:10:34.109  3114  3114 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 07:10:34.119  3114  3114 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 07:10:34.119  3174  3174 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:34.129  3114  3114 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-17 07:10:34.129  3114  3114 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,03-17 07:10:34.129  3114  3114 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,03-17 07:10:34.129  3114  3114 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 07:10:34.129  3153  3153 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-17 07:10:34.139  3153  3153 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-17 07:10:34.139  1771  1771 D SamsungIME: Dismiss ExpandCandiate
,03-17 07:10:34.149  3174  3174 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:34.159  1019  1528 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2982)(adj 0) has died(74,1099)
,03-17 07:10:34.169  1771  1771 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 07:10:34.189  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 07:10:34.189  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 07:10:34.189  1332  1332 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:34.189  1332  1332 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:34.199  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.199  1332  1332 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 07:10:34.199  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.199  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.199  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.209  1332  1332 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
03-17 07:10:34.209  1332  1332 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 07:10:34.209  1332  1332 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 07:10:34.209  1332  1332 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 07:10:34.209  1332  1332 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 07:10:34.209  1332  1332 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 07:10:34.209  1332  1332 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-17 07:10:34.219  3174  3174 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:34.219  3217  3217 E Zygote  : MountEmulatedStorage()
03-17 07:10:34.219  3217  3217 E Zygote  : v2
03-17 07:10:34.219  3217  3217 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:34.219  3217  3217 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:34.219  3217  3217 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:34.219  1019  1367 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3217 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 07:10:34.219  1019  1751 D SettingsProvider: name = aw_daemon_service_key_version_check
03-17 07:10:34.219  1019  1751 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.219  1019  1751 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.219  1019  1751 D SettingsProvider: selectionArgs: false
03-17 07:10:34.219  1019  1751 D SettingsProvider: selectionArgs: 10162
03-17 07:10:34.219  1019  1751 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.219  1019  1751 D SettingsProvider: ret = -1
03-17 07:10:34.219  3217  3217 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:34.229  3217  3217 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:34.229  3174  3174 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:34.229   257   451 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-17 07:10:34.239   257  1103 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-17 07:10:34.249  1019  1751 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-17 07:10:34.249  1332  1332 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 07:10:34.259  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 07:10:34.259  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:34.279  3174  3174 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:34.279  2967  2967 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2967
,03-17 07:10:34.279  3217  3217 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:34.289  3217  3217 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:34.289  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 07:10:34.289  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 07:10:34.289  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
03-17 07:10:34.289  3153  3153 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
03-17 07:10:34.289  3153  3153 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
03-17 07:10:34.299  3174  3174 E UpdateRequestReceiver: ignoring update request
03-17 07:10:34.299  1332  1332 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-17 07:10:34.299  3153  3153 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
03-17 07:10:34.299  1019  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.299  1019  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.299  1019  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.299  1019  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.319  1332  1332 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
03-17 07:10:34.319  1332  1332 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 07:10:34.319  3240  3240 E Zygote  : MountEmulatedStorage()
03-17 07:10:34.319  3240  3240 E Zygote  : v2
03-17 07:10:34.319  3240  3240 I libpersona: KNOX_SDCARD checking this for 10094
03-17 07:10:34.319  3240  3240 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:34.319  1019  1528 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3240 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
03-17 07:10:34.319  3240  3240 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:34.319  1019  1528 I ActivityManager: Killing 2217:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,03-17 07:10:34.329  3240  3240 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:34.329  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 07:10:34.339  3240  3240 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:34.339  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 07:10:34.339   318   318 I art     : Explicit concurrent mark sweep GC freed 8759(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 22.517ms
,03-17 07:10:34.359  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.359  1019  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.359  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 07:10:34.359  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:34.359  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:34.359  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:34.359  3153  3153 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 07:10:34.359   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 19.225ms
,03-17 07:10:34.369  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:34.369  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:34.369  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:34.369  3153  3153 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
03-17 07:10:34.369  3153  3153 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-17 07:10:34.379  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458195034327
,03-17 07:10:34.389  3240  3240 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:34.389  3240  3240 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:34.389   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 23.553ms
,03-17 07:10:34.389  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458216600000
03-17 07:10:34.389  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-17 07:10:34.389  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-17 07:10:34.399  1332  1332 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458216600000
,03-17 07:10:34.399  1019  1528 I ActivityManager: Killing 1546:com.android.printspooler/u0a136 (adj 15): empty #31,
,03-17 07:10:34.419  3153  3153 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 07:10:34.419  1191  1191 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-17 07:10:34.419  1191  1191 D OverheatReceiver: into the SAFE_MODE_ACTION
03-17 07:10:34.419  1191  1191 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-17 07:10:34.419  3153  3153 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
03-17 07:10:34.419  1191  1191 D OverheatReceiver: isSafeMode = false
03-17 07:10:34.419  3153  3153 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
03-17 07:10:34.419  3153  3153 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
03-17 07:10:34.419  3153  3153 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-17 07:10:34.419  3153  3153 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
03-17 07:10:34.419  3153  3153 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-17 07:10:34.429  1501  1501 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
03-17 07:10:34.429  1019  1032 D SettingsProvider: name = internet_call_settings_visibility
03-17 07:10:34.429  1019  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:34.429  1019  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:34.429  1019  1032 D SettingsProvider: selectionArgs: false
03-17 07:10:34.429  1019  1032 D SettingsProvider: selectionArgs: 1001
03-17 07:10:34.429  3153  3153 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
03-17 07:10:34.429  1019  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:34.429  1019  1032 D SettingsProvider: ret = -1
,03-17 07:10:34.429  1501  1501 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 07:10:34.429  3153  3153 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,03-17 07:10:34.429  3153  3207 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-17 07:10:34.429  1332  1332 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 34
03-17 07:10:34.429  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458216600000
,03-17 07:10:34.439  1771  1771 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 07:10:34.439  1479  1479 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-17 07:10:34.439  1019  1528 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-17 07:10:34.449  1019  1528 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.449  1019  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.449  1019  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 07:10:34.449  1479  1479 I Telecom : InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
,03-17 07:10:34.449  1019  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-17 07:10:34.449  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.449  1019  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 07:10:34.449  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
,03-17 07:10:34.459  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.459  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.459  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.459  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.469  3257  3257 E Zygote  : MountEmulatedStorage()
03-17 07:10:34.469  3257  3257 I libpersona: KNOX_SDCARD checking this for 10012
03-17 07:10:34.469  3257  3257 E Zygote  : v2
03-17 07:10:34.469  3257  3257 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:34.469  3257  3257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 07:10:34.469  3153  3207 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
03-17 07:10:34.469  1019  1384 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=3257 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
03-17 07:10:34.469  3257  3257 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:34.469  3153  3207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
03-17 07:10:34.469  3257  3257 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:34.479  3153  3153 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-17 07:10:34.489  3153  3153 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-17 07:10:34.489  3240  3240 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
03-17 07:10:34.489  3153  3153 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
03-17 07:10:34.489  3240  3240 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 07:10:34.489  3240  3240 D elm:15183: MDMBridge.setEnterpriseBridge()
03-17 07:10:34.489  3153  3153 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
03-17 07:10:34.499  3153  3153 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-17 07:10:34.499  1771  1771 I SamsungIME: KeybaordView init() : load resources
,03-17 07:10:34.499  3257  3257 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:34.499  3257  3257 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:34.509  1332  1332 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,03-17 07:10:34.509  1332  1332 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 07:10:34.529  1771  1771 I SamsungIME: getCurrentKeyboard
03-17 07:10:34.529  1771  1771 I SamsungIME: getTextKeyboard
,03-17 07:10:34.539  1771  1771 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 07:10:34.559  2967  2967 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 07:10:34.589  1019  1043 W libprocessgroup: failed to open /acct/uid_10113/pid_2217/cgroup.procs: No such file or directory
,03-17 07:10:34.589  1019  1043 W libprocessgroup: failed to open /acct/uid_10136/pid_1546/cgroup.procs: No such file or directory
,03-17 07:10:34.619  1019  1554 I art     : Explicit concurrent mark sweep GC freed 17496(886KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/40MB, paused 3.143ms total 162.807ms
,03-17 07:10:34.619  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
03-17 07:10:34.619  1019  1554 E Tethering: No numeric data
,03-17 07:10:34.619  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.619  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.619  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 07:10:34.629  1019  3272 E Tethering: No numeric data
03-17 07:10:34.629  1019  1715 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 07:10:34.629  3153  3153 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
03-17 07:10:34.629  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.629  1019  1715 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.629  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 07:10:34.629  1019  1713 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-17 07:10:34.629  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:34.629  1019  1713 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.629  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 07:10:34.629  3240  3240 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 07:10:34.639  1019  1031 E Tethering: No numeric data
,03-17 07:10:34.639  1019  3272 E Tethering: No numeric data
03-17 07:10:34.639  1479  1479 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-17 07:10:34.639  1479  1479 I Telecom : InCallController: Unbinding from InCallService unbind
,03-17 07:10:34.649  1019  1230 E Tethering: No numeric data
,03-17 07:10:34.659  1901  1901 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:34.669  1019  1241 E Tethering: No numeric data
,03-17 07:10:34.669  3240  3240 D elm:15183: ElmAgentService : onCreate()
,03-17 07:10:34.669  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,03-17 07:10:34.669  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.669  3240  3274 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 07:10:34.669  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.669  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-17 07:10:34.669  3240  3240 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-17 07:10:34.669  3240  3240 D elm:15183: BootCompletedState : startBootCompleted() call
,03-17 07:10:34.679  1901  1901 D SecUISvc: Service started flags 0 startId 1
,03-17 07:10:34.679  1901  3277 D SecUISvc: Thread created.
,03-17 07:10:34.679  3257  3257 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 07:10:34.679  3257  3257 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 07:10:34.689  3240  3240 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 07:10:34.719  1464  1464 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 07:10:34.729  3240  3240 I elm:15183: Get License : 0
,03-17 07:10:34.739  3240  3240 D elm:15183: ElmAgentService : onDestroy().
,03-17 07:10:34.739  3257  3257 I MultiDex: VM with version 2.1.0 has multidex support
03-17 07:10:34.739  3257  3257 I MultiDex: install
03-17 07:10:34.739  3257  3257 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 07:10:34.739  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.739  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.739  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.739  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.759  3283  3283 E Zygote  : MountEmulatedStorage()
03-17 07:10:34.759  3283  3283 E Zygote  : v2
03-17 07:10:34.759  3283  3283 I libpersona: KNOX_SDCARD checking this for 10003
03-17 07:10:34.759  3283  3283 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:34.759  3217  3217 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-17 07:10:34.759  1019  1019 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3283 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-17 07:10:34.769  3283  3283 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:34.769  3217  3217 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 07:10:34.769  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.769  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.769  3283  3283 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:34.769  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.769  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.769  3283  3283 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:34.789  3153  3207 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init,
03-17 07:10:34.789  3217  3217 I DBG_POLICYDM: [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
03-17 07:10:34.789   286   710 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
,03-17 07:10:34.789   286   710 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 07:10:34.789   286   710 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 07:10:34.789   286   710 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 07:10:34.789   286   710 I str_params: key: 'call_forwarding' value: ''
03-17 07:10:34.789  1910  1910 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 07:10:34.789  1910  1910 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-17 07:10:34.789  1910  1910 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-17 07:10:34.799  2168  2168 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,03-17 07:10:34.799  2168  2168 I dhcpcd  : wlan0: no IPv6 Routers available
,03-17 07:10:34.799  3294  3294 E Zygote  : MountEmulatedStorage(),
03-17 07:10:34.799  3294  3294 E Zygote  : v2
03-17 07:10:34.799  3294  3294 I libpersona: KNOX_SDCARD checking this for 10009
03-17 07:10:34.799  3294  3294 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:34.799  3294  3294 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 07:10:34.799  1910  1910 D ScoverManager: serviceVersion : 16908288
,03-17 07:10:34.799  1019  1367 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3294 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:34.799  1019  1384 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 07:10:34.799  3294  3294 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:34.799  1910  1910 D InCall  : InCallUtils - isCoverClosed false
,03-17 07:10:34.799  3294  3294 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:34.809  1479  1479 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-17 07:10:34.809  1019  1528 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 07:10:34.809  1464  1464 V EmergencyMode: [EmergencyBase] setBootTime
,03-17 07:10:34.809  1464  1464 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 07:10:34.809  1910  1910 D InCall  : InCallUtils - isCoverClosed false
,03-17 07:10:34.809  1910  1910 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-17 07:10:34.809  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.809  1910  1910 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
03-17 07:10:34.809  1910  1910 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-17 07:10:34.809  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.819  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.819  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.819  1910  1910 I InCall  : CallSContextMotion - stopPutDownListening
03-17 07:10:34.819  1910  1910 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 07:10:34.829  1191  1191 D PhoneStatusBarView: setCallBackground:0
,03-17 07:10:34.829  1019  1230 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 07:10:34.829  1910  1910 D InCall  : InCallUtils - isCoverClosed false
,03-17 07:10:34.829  1019  1032 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3305 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:34.839  3305  3305 E Zygote  : MountEmulatedStorage()
03-17 07:10:34.839  3305  3305 I libpersona: KNOX_SDCARD checking this for 10028
03-17 07:10:34.839  3305  3305 E Zygote  : v2
03-17 07:10:34.839  3305  3305 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:34.839  3305  3305 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:34.839  1019  1032 I ActivityManager: Killing 2394:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,03-17 07:10:34.839  3305  3305 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:34.849  3305  3305 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:34.849  3283  3283 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:34.869  3283  3283 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:34.869  2967  3203 D jxcore_app_log: JniHelper::setJavaVM(0xb70e2450), pthread_self() = -1218100168
03-17 07:10:34.869   330   330 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 07:10:34.879  1910  1910 D VideoCallManager: Instantiating VideoCallManager
,03-17 07:10:34.889  1910  1910 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 07:10:34.889  2967  3203 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 07:10:34.889  2967  3203 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 07:10:34.889  2967  3203 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 07:10:34.889  2967  3203 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 07:10:34.889  2967  3203 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 07:10:34.889  1910  1910 I GFX construct_block_size_descriptor_2d second part: took 2.561875ms for 0*0 texture 0
03-17 07:10:34.889  2967  3203 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee7f25f added. We now have 1 listener(s)
,03-17 07:10:34.899  2967  3203 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:51:18:22
,03-17 07:10:34.899  1910  1910 I GFX generate_partition_tables: took 5.229427ms for 0*0 texture 0
,03-17 07:10:34.899  2967  3203 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
,03-17 07:10:34.899  2967  3203 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"},
03-17 07:10:34.899  2967  3203 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 07:10:34.899  2967  3203 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
03-17 07:10:34.899  1910  1910 I GFX raster: took 11.535416ms for 176*144 texture 0
03-17 07:10:34.899  1910  1910 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7496ec8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7496798 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 07:10:34.909  2967  3203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
03-17 07:10:34.909  2967  3203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 07:10:34.909  2967  3203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 07:10:34.909  2967  3203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:51:18:22
03-17 07:10:34.909  2967  3203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 07:10:34.909  2967  3203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 07:10:34.909  2967  3203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 07:10:34.909  2967  3203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 07:10:34.909  2967  3203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 07:10:34.909  2967  3203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 07:10:34.909  2967  3203 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f63490a added. We now have 1 listener(s),
03-17 07:10:34.909  2967  3203 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 07:10:34.919  3257  3257 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 07:10:34.919  3294  3294 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:34.919  3294  3294 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:34.929  1910  1910 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-17 07:10:34.929  1910  1910 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 07:10:34.929  1910  1910 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 07:10:34.929  1910  1910 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 07:10:34.929  1910  1910 I Adreno-EGL: Local Branch: 
03-17 07:10:34.929  1910  1910 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 07:10:34.929  1910  1910 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 07:10:34.929  1910  1910 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 07:10:34.939  2967  3203 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 07:10:34.949  2998  2998 E BluetoothHeadset: BTStateChangeCB is registed
,03-17 07:10:34.949  2998  2998 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-17 07:10:34.949  1019  1713 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-17 07:10:34.959  1910  1910 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 07:10:34.969  1910  1910 I glCompressedTexImage2D: took 0.353542ms for 320*61440 texture 37809
,03-17 07:10:34.979  1910  1910 I draw setup: took 11.095938ms for 320*240 texture 37809
03-17 07:10:34.979  1910  1910 E GFX GPU raster: drawn
,03-17 07:10:34.979  3305  3305 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:34.979  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.979  1019  1713 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.979  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
03-17 07:10:34.979  2967  3203 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 07:10:34.979  2967  3203 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-17 07:10:34.979  2967  3203 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 07:10:34.979  2967  3203 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 07:10:34.989  3305  3305 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:34.989  1910  1910 I GFX GPU raster ASTC: took 40.875942ms for 320*240 texture 12
03-17 07:10:34.989  1910  1910 I GFX raster: took 40.957504ms for 320*240 texture 0
03-17 07:10:34.989  1910  1910 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7496e48 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb74969b0 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 07:10:34.989  2967  3203 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 07:10:34.989  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:34.989  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.989  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.989  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.009  1910  1910 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 07:10:35.009  1910  1910 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 07:10:35.009  1910  1910 I glCompressedTexImage2D: took 0.435625ms for 480*122880 texture 37813,
03-17 07:10:35.009  1910  1910 I draw setup: took 0.967917ms for 480*640 texture 37813
03-17 07:10:35.009  3257  3257 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 07:10:35.009  1910  1910 E GFX GPU raster: drawn
,03-17 07:10:35.009  3257  3257 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16e808ba: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 07:10:35.009  3257  3257 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL,
,03-17 07:10:35.019  3153  3153 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 07:10:35.019  1019  1031 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3335 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:35.019  3153  3153 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] ,
03-17 07:10:35.019  2998  2998 E BluetoothHeadset: BluetoothHeadset service is binded
,03-17 07:10:35.029  3335  3335 E Zygote  : MountEmulatedStorage()
03-17 07:10:35.029  3335  3335 E Zygote  : v2
03-17 07:10:35.029  3335  3335 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:35.029  3335  3335 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:35.029  3335  3335 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 07:10:35.029  2967  3203 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:51:18:22
03-17 07:10:35.029  3335  3335 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:35.029  3335  3335 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:35.039  2998  2998 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-17 07:10:35.049  1910  1910 I GFX GPU raster ASTC: took 8.763282ms for 480*640 texture 12
03-17 07:10:35.049  1910  1910 I GFX raster: took 8.856667ms for 480*640 texture 0
03-17 07:10:35.049  1910  1910 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74969b0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb76c4060 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 07:10:35.049  2967  3203 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 07:10:35.049  2967  3203 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 07:10:35.049  2967  3203 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 07:10:35.049  2967  3203 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 07:10:35.049  2967  3203 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 07:10:35.049  2967  3203 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 07:10:35.049  2967  3203 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 07:10:35.049  2967  3203 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 07:10:35.049  2967  3203 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 07:10:35.049  2967  3203 D io.jxcore.node.ConnectivityMonitor: start: OK
03-17 07:10:35.049  1353  3152 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 07:10:35.069  1019  3272 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,03-17 07:10:35.069  1353  3152 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 07:10:35.069  1019  3272 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.069  1019  3272 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.069  1019  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-17 07:10:35.069  1019  1043 W libprocessgroup: failed to open /acct/uid_10142/pid_2394/cgroup.procs: No such file or directory
,03-17 07:10:35.089  2967  2967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 07:10:35.099  2967  2967 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 07:10:35.119  3335  3335 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:35.119  3335  3335 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:35.119  1019  1230 I ActivityManager: Killing 2413:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-17 07:10:35.129  2967  2967 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 07:10:35.149  1910  1910 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-17 07:10:35.149  1910  1910 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 07:10:35.149  1910  1910 I glCompressedTexImage2D: took 0.436458ms for 440*116864 texture 37809
03-17 07:10:35.149  1910  1910 I draw setup: took 0.876041ms for 440*330 texture 37809
03-17 07:10:35.149  1910  1910 E GFX GPU raster: drawn,
,03-17 07:10:35.159  1910  1910 I GFX GPU raster ASTC: took 5.090313ms for 440*330 texture 12
03-17 07:10:35.159  1910  1910 I GFX raster: took 5.177448ms for 440*330 texture 0
03-17 07:10:35.159  1910  1910 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76c82b8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb76c8678 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 07:10:35.159  3153  3207 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-17 07:10:35.189  1910  1910 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 07:10:35.189  1910  1910 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS,
,03-17 07:10:35.189  1910  1910 I glCompressedTexImage2D: took 0.473750ms for 480*163840 texture 37811
03-17 07:10:35.189  1910  1910 I draw setup: took 0.909218ms for 480*640 texture 37811,
03-17 07:10:35.189  1910  1910 E GFX GPU raster: drawn
,03-17 07:10:35.209  1910  1910 I GFX GPU raster ASTC: took 6.378385ms for 480*640 texture 12
03-17 07:10:35.209  1910  1910 I GFX raster: took 6.462135ms for 480*640 texture 0
03-17 07:10:35.209  1910  1910 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7707c88 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb76c3e18 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 07:10:35.259  1910  1910 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 07:10:35.259  1910  1910 I GFX construct_block_size_descriptor_2d second part: took 2.467761ms for 0*0 texture 0
,03-17 07:10:35.269  1910  1910 I GFX generate_partition_tables: took 7.777344ms for 0*0 texture 0
,03-17 07:10:35.269  1910  1910 I GFX raster: took 12.520834ms for 176*144 texture 0
03-17 07:10:35.269  1910  1910 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76c8238 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb76c1878 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 07:10:35.279  1910  1910 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 07:10:35.289  1910  1910 I GFX construct_block_size_descriptor_2d second part: took 3.343021ms for 0*0 texture 0
,03-17 07:10:35.299  3217  3217 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-17 07:10:35.309  1910  1910 I GFX generate_partition_tables: took 6.176719ms for 0*0 texture 0
,03-17 07:10:35.309  1910  1910 I GFX raster: took 11.930053ms for 176*144 texture 0
03-17 07:10:35.309  1910  1910 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb76c18e0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb76c1a68 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 07:10:35.319  3217  3217 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 07:10:35.319  1910  1910 D ScoverManager: registerListener
03-17 07:10:35.319  3217  3285 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 07:10:35.319  1019  1031 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 07:10:35.319  3217  3217 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-17 07:10:35.329  1019  1715 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 07:10:35.329  1019  1715 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@1e86f944, pid : 1910, uid : 1001, type : 1
,03-17 07:10:35.329  3217  3217 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-17 07:10:35.329  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-17 07:10:35.339  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.339  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:35.339  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 07:10:35.339  3217  3285 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-17 07:10:35.339  1910  1910 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 07:10:35.349  3217  3217 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-17 07:10:35.359  3217  3217 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,03-17 07:10:35.359  3217  3217 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 07:10:35.359  3217  3217 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 07:10:35.359  3217  3217 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-17 07:10:35.369  3217  3217 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
03-17 07:10:35.369  1019  1043 E libprocessgroup: failed to kill 1 processes for processgroup 2413
,03-17 07:10:35.379  3217  3217 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-17 07:10:35.379  1019  1230 E Tethering: No numeric data
,03-17 07:10:35.379  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:35.379  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:35.379  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:35.389  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:35.389  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:35.389  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:35.389  1019  1528 E Tethering: No numeric data
,03-17 07:10:35.389  1019  1713 E Tethering: No numeric data
,03-17 07:10:35.389  1970  1970 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
,03-17 07:10:35.409  3217  3285 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-17 07:10:35.409  2737  2774 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 07:10:35.409  2998  2998 D BluetoothA2dp: Proxy object connected
,03-17 07:10:35.419  3283  3283 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 07:10:35.459  3335  3335 I CameraApp: CameraApp.onCreate()... mFeature : null
03-17 07:10:35.459  3335  3335 I testFeature: Feature.Feature(context)
03-17 07:10:35.459  3335  3335 I testFeature: Feature.readInternalDefaultXml()
03-17 07:10:35.459  3335  3335 I testFeature: ResetFeatureValue
,03-17 07:10:35.459  3335  3335 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 07:10:35.459  3335  3335 I CameraApp: CameraApp.getAppFeature()...
,03-17 07:10:35.459  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.459  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.459  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.459  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.469  3356  3356 E Zygote  : MountEmulatedStorage(),
03-17 07:10:35.469  3356  3356 I libpersona: KNOX_SDCARD checking this for 10100,
03-17 07:10:35.469  3356  3356 E Zygote  : v2
03-17 07:10:35.469  3356  3356 I libpersona: KNOX_SDCARD not a persona,
03-17 07:10:35.479  3356  3356 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:35.479  3356  3356 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 07:10:35.479  3356  3356 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:35.489  1019  1713 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3356 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 07:10:35.489  1019  1713 I ActivityManager: Killing 1719:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-17 07:10:35.509  3356  3356 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:35.509  3356  3356 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:35.539  3153  3207 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 07:10:35.549  1019  1032 E Tethering: No numeric data
,03-17 07:10:35.549  3283  3283 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 07:10:35.549  3283  3283 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 07:10:35.549  3283  3283 D UserAnalysis: Create SecureDbHelper
,03-17 07:10:35.559  3153  3207 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-17 07:10:35.559  3153  3207 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 07:10:35.579  3356  3356 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 07:10:35.579  1019  1043 W libprocessgroup: failed to open /acct/uid_10015/pid_1719/cgroup.procs: No such file or directory
,03-17 07:10:35.589  3283  3283 D IntelligenceServiceApplication: onCreate()
,03-17 07:10:35.589  3283  3283 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 07:10:35.599  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.599  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.599  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.599  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.609  3356  3356 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-17 07:10:35.619  3378  3378 E Zygote  : MountEmulatedStorage()
,03-17 07:10:35.619  3378  3378 E Zygote  : v2
03-17 07:10:35.619  3378  3378 I libpersona: KNOX_SDCARD checking this for 10060
03-17 07:10:35.619  3378  3378 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:35.619  3378  3378 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:35.619  3378  3378 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 07:10:35.619  1019  1713 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3378 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 07:10:35.619  3378  3378 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:35.619  1019  1713 I ActivityManager: Killing 2473:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 07:10:35.629  1019  1713 I ActivityManager: Killing 2494:com.sec.android.omc/1000 (adj 15): empty #31
,03-17 07:10:35.629  1019  1715 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:35.629  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.629  1019  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:35.629  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-17 07:10:35.649  1695  3387 I GoogleHttpClient: GMS http client unavailable, use old client
,03-17 07:10:35.649  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.649  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.649  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.649  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.649  3378  3378 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-17 07:10:35.659  3378  3378 D ActivityThread: Added TimaKeyStore provider,
,03-17 07:10:35.669  3396  3396 E Zygote  : MountEmulatedStorage()
03-17 07:10:35.679  3396  3396 E Zygote  : v2
03-17 07:10:35.679  3396  3396 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:35.679  3396  3396 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:35.679  3396  3396 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:35.679  3396  3396 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 07:10:35.679  3396  3396 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:35.679  1019  1751 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3396 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:35.699  3396  3396 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:35.699  3396  3396 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:35.729  3283  3283 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 07:10:35.739  1019  1528 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-17 07:10:35.739  3283  3283 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 07:10:35.739  1019  1384 V VibratorService: hasVibrator - useVibetonz: true
,03-17 07:10:35.749  1353  3152 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 07:10:35.749  1019  1528 V VibratorService: hasVibrator - useVibetonz: true
,03-17 07:10:35.759  1019  1384 V VibratorService: hasVibrator - useVibetonz: true
,03-17 07:10:35.779  3217  3231 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:35.779  1353  3152 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:35.779  3217  3231 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:35.789  3217  3231 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 07:10:35.789  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2473/cgroup.procs: No such file or directory
,03-17 07:10:35.789  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2494/cgroup.procs: No such file or directory
,03-17 07:10:35.789  3217  3227 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:35.789  3217  3227 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:35.789  3217  3227 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 07:10:35.839  1353  3152 D ScoverManager: serviceVersion : 16908288
,03-17 07:10:35.849  3283  3283 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 07:10:35.849  3283  3283 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 07:10:35.879  3217  3285 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 07:10:35.879  3217  3285 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 07:10:35.889  3217  3285 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 07:10:35.889  3217  3285 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-17 07:10:35.889  3217  3285 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-17 07:10:35.909  1019  2775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 07:10:35.919  3217  3285 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 07:10:35.929  3217  3285 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 07:10:35.939  3217  3285 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 07:10:35.939  3217  3285 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-17 07:10:35.939  3217  3285 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 07:10:35.949  3217  3286 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 07:10:35.949  2967  3344 W jxcore-log: Initializing JXcore engine
03-17 07:10:35.949  2967  3344 W jxcore-log: JXcore engine is ready
,03-17 07:10:35.949  3217  3285 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/18/13:15:33
,03-17 07:10:35.949  3217  3286 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 07:10:35.959  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.959  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.959  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.959  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.959  3217  3285 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/07:10:35
,03-17 07:10:35.959  3217  3285 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-17 07:10:35.959  3217  3285 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0,
,03-17 07:10:35.969  3419  3419 E Zygote  : MountEmulatedStorage(),
03-17 07:10:35.969  3419  3419 E Zygote  : v2
03-17 07:10:35.969  3419  3419 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 07:10:35.969  3419  3419 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:35.979  3419  3419 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 07:10:35.979  3217  3286 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
03-17 07:10:35.979  3217  3286 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
03-17 07:10:35.979  3217  3286 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
03-17 07:10:35.979  3419  3419 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:35.979  3217  3286 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
03-17 07:10:35.979  3419  3419 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:35.979  3217  3286 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
03-17 07:10:35.979  1019  1713 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3419 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:35.979  3217  3286 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-17 07:10:35.989  3217  3286 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0,
,03-17 07:10:35.989  3217  3286 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 07:10:35.989  1019  1713 I ActivityManager: Killing 2539:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-17 07:10:35.989  1019  1713 I ActivityManager: Killing 2522:com.sec.modem.settings/1000 (adj 15): empty #32
,03-17 07:10:35.989  1019  1713 I ActivityManager: Killing 2509:com.wsomacp/u0a25 (adj 15): empty #33
,03-17 07:10:35.999  3378  3378 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-17 07:10:36.009  3217  3286 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 07:10:36.009  3419  3419 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.009  3419  3419 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.009  1895  1895 E audit   : type=1400 msg=audit(1458195036.009:205): avc:  denied  { ioctl } for  pid=3344 comm="Thread-354" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3088 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 07:10:36.019  1895  1895 E audit   :  SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:36.019  1895  1895 E audit   : type=1300 msg=audit(1458195036.009:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9b3788f8 items=0 ppid=318 ppcomm=main pid=3344 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-354" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 07:10:36.019  1895  1895 E audit   : type=1320 msg=audit(1458195036.009:205): 
,03-17 07:10:36.019  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.019  3217  3286 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-17 07:10:36.029  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.029  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.029  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.039  2967  3344 W jxcore-log: Starting JXcore engine
,03-17 07:10:36.049  3435  3435 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.049  3435  3435 E Zygote  : v2
03-17 07:10:36.049  3435  3435 I libpersona: KNOX_SDCARD checking this for 10062
03-17 07:10:36.049  3435  3435 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.049  3435  3435 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:36.069  3435  3435 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:36.069  1019  1384 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3435 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:36.069  3435  3435 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.069  1019  1384 I ActivityManager: Killing 2550:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-17 07:10:36.099  3435  3435 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.099  3435  3435 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.139  3419  3419 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-17 07:10:36.149  3419  3419 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 07:10:36.149  3419  3419 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 07:10:36.149  3419  3419 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 07:10:36.159  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.159  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.159  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.159  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.179  1019  1367 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3450 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-17 07:10:36.179  1019  1367 I ActivityManager: Killing 2458:com.sec.android.app.mt/1000 (adj 15): empty #31
03-17 07:10:36.179  3450  3450 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.179  3450  3450 E Zygote  : v2
03-17 07:10:36.179  3450  3450 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:36.179  3450  3450 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:36.179  3450  3450 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:36.179  3450  3450 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:36.179  3450  3450 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.199   318   318 I art     : Explicit concurrent mark sweep GC freed 8765(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 652us total 28.584ms
,03-17 07:10:36.209  3450  3450 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.209  3450  3450 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.209  2967  3344 W jxcore-log: Platform android
03-17 07:10:36.209  2967  3344 W jxcore-log: 
,03-17 07:10:36.209  2967  3344 W jxcore-log: Process ARCH arm
03-17 07:10:36.209  2967  3344 W jxcore-log: 
,03-17 07:10:36.219  1019  1043 W libprocessgroup: failed to open /acct/uid_10131/pid_2550/cgroup.procs: No such file or directory
,03-17 07:10:36.219   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 19.184ms
,03-17 07:10:36.239  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.239   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 666us total 17.980ms
03-17 07:10:36.239  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.239  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.239  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.259  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2539/cgroup.procs: No such file or directory
03-17 07:10:36.259  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2522/cgroup.procs: No such file or directory
03-17 07:10:36.259  1019  1043 W libprocessgroup: failed to open /acct/uid_10025/pid_2509/cgroup.procs: No such file or directory
,03-17 07:10:36.259  3467  3467 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.259  3467  3467 E Zygote  : v2
03-17 07:10:36.259  3467  3467 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:36.259  3467  3467 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.259  3467  3467 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:36.269  3467  3467 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 07:10:36.269  3467  3467 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:36.269  1019  1367 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3467 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:36.269  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2458/cgroup.procs: No such file or directory
,03-17 07:10:36.289  3217  3285 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 07:10:36.289  3467  3467 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.289  3467  3467 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.289  3435  3435 I ExternalOEMControlProvider: onCreate
,03-17 07:10:36.309  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.309  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.309  3450  3450 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
,03-17 07:10:36.309  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.309  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.319  3484  3484 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.319  3484  3484 E Zygote  : v2
03-17 07:10:36.319  3484  3484 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:36.319  3484  3484 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:36.319  3484  3484 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:36.329  3484  3484 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:36.329  1019  1751 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3484 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:36.329  3484  3484 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.329  1019  1751 I ActivityManager: Killing 2623:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-17 07:10:36.329  1019  1713 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-17 07:10:36.329  1019  1713 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:36.329  1019  1713 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:36.329  1019  1713 D SettingsProvider: selectionArgs: false
03-17 07:10:36.329  1019  1713 D SettingsProvider: selectionArgs: 10062
03-17 07:10:36.329  1019  1713 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:36.329  1019  1713 D SettingsProvider: ret = -1
,03-17 07:10:36.339  1019  1713 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 07:10:36.349  3450  3450 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.349  1019  1715 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-17 07:10:36.349  1019  1715 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:36.349  1019  1715 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:36.349  1019  1715 D SettingsProvider: selectionArgs: false
03-17 07:10:36.349  1019  1715 D SettingsProvider: selectionArgs: 10062
03-17 07:10:36.349  1019  1715 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:36.349  1019  1715 D SettingsProvider: ret = -1
,03-17 07:10:36.359  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:36.369  3484  3484 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.369  3484  3484 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.369  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:36.369  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:36.369  1019  1715 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
03-17 07:10:36.369  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:36.369  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:36.369  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:36.369  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:36.369  3450  3450 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-17 07:10:36.369  3217  3286 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-17 07:10:36.379  3450  3450 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
03-17 07:10:36.379  3450  3450 D ShortcutReceiver:  shortcut migration not required 
,03-17 07:10:36.389  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.389  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.389  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.389  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.389  3484  3484 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 07:10:36.399  3502  3502 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.399  3502  3502 E Zygote  : v2
03-17 07:10:36.399  3502  3502 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:36.399  3502  3502 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.399  3502  3502 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:36.399  1019  3272 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3502 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 07:10:36.399  1019  3272 I ActivityManager: Killing 2638:com.android.calendar/u0a135 (adj 15): empty #31
,03-17 07:10:36.409  3502  3502 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:36.409  3502  3502 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.409  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:36.419  1019  1241 I ActivityManager: Killing 2700:com.android.keychain/1000 (adj 15): empty #31
,03-17 07:10:36.419  3217  3286 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 07:10:36.429  3502  3502 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.429  3502  3502 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.439  3217  3286 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 07:10:36.459  3484  3484 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-17 07:10:36.459  3484  3484 I ServiceMode: setReferenceIsDumpState : 0
,03-17 07:10:36.459  3467  3467 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 07:10:36.459  3467  3467 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 07:10:36.459  3467  3467 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 07:10:36.469  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.469  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.469  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.469  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.479  2967  3344 I jxcore-log: JXcore Cordova bridge is ready!
03-17 07:10:36.479  2967  3344 I jxcore-log: 
,03-17 07:10:36.479  2967  3344 W jxcore-log: JXcore engine is started
,03-17 07:10:36.489  3517  3517 E Zygote  : MountEmulatedStorage()
,03-17 07:10:36.489  3517  3517 E Zygote  : v2
03-17 07:10:36.489  3517  3517 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:36.489  3517  3517 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.489  3517  3517 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:36.489  1019  3272 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3517 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:36.489  1353  3152 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 07:10:36.489  3517  3517 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:36.489  1019  3272 I ActivityManager: Killing 2807:com.android.email/u0a145 (adj 15): empty #31
03-17 07:10:36.489  3517  3517 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.489  3502  3502 E KnoxSetupWizardClient: isShipMode : 1
03-17 07:10:36.489  3502  3502 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.499  3467  3478 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 07:10:36.499  3217  3285 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
03-17 07:10:36.499  2967  3203 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 07:10:36.499  3419  3419 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 07:10:36.509  3217  3285 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 07:10:36.509  1353  3152 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-17 07:10:36.509  2967  3344 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 07:10:36.509  2967  3344 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 07:10:36.519  3517  3517 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.519  3517  3517 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.519  3419  3419 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.519  3419  3419 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.529  3305  3305 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 07:10:36.529  2967  2967 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-17 07:10:36.529  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.529  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.529  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.529  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.549  1019  2871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 07:10:36.549  3536  3536 E Zygote  : MountEmulatedStorage()
,03-17 07:10:36.549  3536  3536 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:36.549  3536  3536 E Zygote  : v2
03-17 07:10:36.549  3536  3536 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:36.549  3536  3536 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:36.549  3536  3536 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:36.549  1019  1032 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3536 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:36.549  3536  3536 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:36.549  1019  1032 I ActivityManager: Killing 1608:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
03-17 07:10:36.549  1019  1032 I ActivityManager: Killing 1231:com.android.defcontainer/u0a4 (adj 15): empty #32
,03-17 07:10:36.559  1019  1241 D FocusedStackFrame: Set to : 0
03-17 07:10:36.559  1019  1241 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 07:10:36.559  1019  1241 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,03-17 07:10:36.559  1019  1241 D InputDispatcher: Focused application set to: xxxx
03-17 07:10:36.559  1019  1241 D InputDispatcher: Focus left window: 2967
,03-17 07:10:36.559  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 07:10:36.559  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 07:10:36.569   257   451 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (304 us)
,03-17 07:10:36.569  3536  3536 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.569  3536  3536 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.599  2967  3203 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 66ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 07:10:36.599  1019  1230 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-17 07:10:36.599  1019  1230 W ActivityManager: mDVFSHelper.acquire()
,03-17 07:10:36.609  3502  3524 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
03-17 07:10:36.609  3502  3524 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-17 07:10:36.609  3502  3524 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-17 07:10:36.609  3502  3524 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-17 07:10:36.609  3502  3524 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-17 07:10:36.609  3502  3524 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-17 07:10:36.609  3502  3524 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-17 07:10:36.609  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
03-17 07:10:36.609  1019  1230 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 07:10:36.609  1019  1230 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 07:10:36.609  1019  1230 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 07:10:36.619  1531  1531 D Launcher: onRestart, Launcher: 526486237
,03-17 07:10:36.619  3517  3517 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.619  3517  3517 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:36.649  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 07:10:36.649  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.649  1019  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.649  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 07:10:36.649  1531  1531 D Launcher: onStart, Launcher: 526486237
,03-17 07:10:36.649  1531  1531 D Launcher.HomeView: onStart
03-17 07:10:36.649  1531  1531 D Launcher: onResume, Launcher: 526486237
,03-17 07:10:36.649  1019  1389 D SettingsProvider: name = kids_home_mode
03-17 07:10:36.649  1019  1389 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:36.649  1019  1389 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:36.649  1019  1389 D SettingsProvider: selectionArgs: false
03-17 07:10:36.649  1019  1389 D SettingsProvider: selectionArgs: 10007
03-17 07:10:36.649  1019  1389 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:36.649  1019  1389 D SettingsProvider: ret = -1
03-17 07:10:36.649  1531  1531 D Launcher.HomeView: onResume
03-17 07:10:36.649  1019  1367 I ActivityManager: Killing 2367:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,03-17 07:10:36.649  2655  3149 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3149)  
,03-17 07:10:36.659  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.659  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.659  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.659  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.659  1531  1531 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
,03-17 07:10:36.669  3517  3517 D NPS_WSSNPS: [] Service onCreate!!,
,03-17 07:10:36.669  3556  3556 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.669  3556  3556 E Zygote  : v2
03-17 07:10:36.669  3556  3556 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:36.669  3556  3556 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.669  3556  3556 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:36.679  3556  3556 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:36.679  3556  3556 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:36.679  1019  1032 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3556 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:36.679  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.679  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.679  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.679  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.689  3536  3536 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 07:10:36.689  3536  3536 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 07:10:36.699  3566  3566 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.699  3566  3566 E Zygote  : v2
,03-17 07:10:36.699  3566  3566 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:36.699  3566  3566 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:36.699  3566  3566 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:36.699  3566  3566 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 07:10:36.699  3566  3566 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.709  3556  3556 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:36.709  3556  3556 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.709  1019  1032 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3566 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:36.719  3517  3578 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-17 07:10:36.729  3566  3566 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.729  3566  3566 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.739  1531  1531 D MenuAppsGridFragment: onResume
,03-17 07:10:36.739  3467  3478 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 07:10:36.739  3517  3517 D NPS_WSSNPS: [50.150321] smlDBHelper
,03-17 07:10:36.749  1019  1554 D ActivityManager: handle home activity for 0
,03-17 07:10:36.749  1019  1554 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,03-17 07:10:36.749  1019  1554 D KnoxTimeoutHandler: post home show event for user 0
03-17 07:10:36.749  1019  1554 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 07:10:36.749  1019  1554 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 07:10:36.749  1019  1554 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 07:10:36.759  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,03-17 07:10:36.759  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,03-17 07:10:36.759  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 07:10:36.759   257   257 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-17 07:10:36.759  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 07:10:36.769  3517  3517 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-17 07:10:36.769  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 07:10:36.769  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 07:10:36.779  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2623/cgroup.procs: No such file or directory
03-17 07:10:36.779  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2700/cgroup.procs: No such file or directory
,03-17 07:10:36.779  1019  1043 W libprocessgroup: failed to open /acct/uid_10135/pid_2638/cgroup.procs: No such file or directory
03-17 07:10:36.779  1019  1043 W libprocessgroup: failed to open /acct/uid_10145/pid_2807/cgroup.procs: No such file or directory
03-17 07:10:36.779  1019  1043 W libprocessgroup: failed to open /acct/uid_10072/pid_1608/cgroup.procs: No such file or directory
03-17 07:10:36.779  1019  1043 W libprocessgroup: failed to open /acct/uid_10004/pid_1231/cgroup.procs: No such file or directory
,03-17 07:10:36.779  1019  1043 W libprocessgroup: failed to open /acct/uid_10044/pid_2367/cgroup.procs: No such file or directory
,03-17 07:10:36.779  3517  3590 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-17 07:10:36.779  3517  3590 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
,03-17 07:10:36.779  3517  3590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-17 07:10:36.779  1019  1019 D SensorService: [SO] activate (ident=0xb7880c78, enabled=0)
03-17 07:10:36.779  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-17 07:10:36.779  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 07:10:36.779  1019  1715 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 07:10:36.779  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.779  1019  1715 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:36.779  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
03-17 07:10:36.789  3536  3536 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 07:10:36.789  3556  3556 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.789  1019  1528 D InputDispatcher: Focus entered window: 1531
,03-17 07:10:36.789  1019  1019 D SensorManager: unregisterListener ::   
,03-17 07:10:36.789  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-17 07:10:36.789  1019  1019 D SensorService: [SO] changed settle time [0]
03-17 07:10:36.789  1019  1019 D SensorService: [SO] setDelay [200000000]
03-17 07:10:36.789  1019  1019 D SensorService: [SO] activate (ident=0xb7880c78, enabled=1)
03-17 07:10:36.789  1019  1019 D SensorService: [SO] AR_init
03-17 07:10:36.789  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 07:10:36.799  3556  3556 I StatusChecker: onReceive : net.mt.init : DONE
,03-17 07:10:36.799  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 07:10:36.799  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 07:10:36.799  1531  1531 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 07:10:36.809  3517  3517 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-17 07:10:36.809  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-17 07:10:36.819  1531  1531 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 07:10:36.819  1019  1230 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 07:10:36.819  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.819  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.819  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.819  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.829  2967  2967 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 07:10:36.829  3536  3536 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
03-17 07:10:36.829  1019  3603 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-17 07:10:36.829  3517  3517 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
03-17 07:10:36.829  3517  3517 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
03-17 07:10:36.829  3517  3517 I NPS_WSSNPS: [50.150321] smlBREmailDelete
03-17 07:10:36.829  3605  3605 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.829  3605  3605 E Zygote  : v2
03-17 07:10:36.829  3605  3605 I libpersona: KNOX_SDCARD checking this for 10116
03-17 07:10:36.829  3605  3605 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:36.829  1191  1191 I StatusBar: Icon Only
03-17 07:10:36.829  1191  1191 D PanelView: There is/are notification(s) 
,03-17 07:10:36.829  3605  3605 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:36.839  3605  3605 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:36.839  1771  1771 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
03-17 07:10:36.839  3605  3605 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:36.839  1019  1751 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3605 uid=10116 gids={50116, 9997} abi=armeabi-v7a
03-17 07:10:36.839  1019  1751 I ActivityManager: Killing 2883:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-17 07:10:36.839  3517  3517 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
03-17 07:10:36.839  1019  1241 V VibratorService: hasVibrator - useVibetonz: true
03-17 07:10:36.839  3517  3517 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
03-17 07:10:36.839  3517  3517 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
03-17 07:10:36.839  3517  3517 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
03-17 07:10:36.839  3517  3517 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
03-17 07:10:36.839  3517  3517 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-17 07:10:36.849  3517  3517 D NPS_WSSNPS: [50.150321] dsServerSocket close
,03-17 07:10:36.849  1019  1528 I ActivityManager: Killing 2280:flipboard.app/u0a98 (adj 15): empty #31
,03-17 07:10:36.849  3305  3305 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-17 07:10:36.859  1019  1241 D SettingsProvider: name = access_control_enabled
,03-17 07:10:36.859  1019  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.859  1019  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.859  1019  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.859  1019  1554 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.859   291   291 E SMD     : DCD OFF
,03-17 07:10:36.869  1531  1531 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3124fa51 time:40244
,03-17 07:10:36.869  1019  1050 D PersonaManager: isKioskContainerExistOnDevice
,03-17 07:10:36.879  3622  3622 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.879  3622  3622 E Zygote  : v2
03-17 07:10:36.879  3622  3622 I libpersona: KNOX_SDCARD checking this for 10069
03-17 07:10:36.879  3622  3622 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.879  3622  3622 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:36.889  3622  3622 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:36.889  1019  1554 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3622 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:36.889  3622  3622 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:36.889  1019  1554 I ActivityManager: Killing 2944:com.sec.usbsettings/1000 (adj 15): empty #31
03-17 07:10:36.889  3605  3605 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.889  3605  3605 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.909  1019  1050 I ActivityManager: Displayed Component not be shown by security: +299ms
,03-17 07:10:36.919  3622  3622 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.919  3622  3622 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.959  3605  3605 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.969  3536  3536 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 07:10:36.969  1019  3272 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:36.969  1019  3272 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:36.969  1019  3272 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:36.969  1019  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 07:10:36.979  3605  3605 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-17 07:10:36.979  1019  1389 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:36.979  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:36.979  1019  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.979  3536  3536 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 07:10:36.979  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
03-17 07:10:36.979  3536  3536 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 07:10:36.979  3536  3536 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 07:10:36.979  3536  3536 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 07:10:36.979  3536  3536 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.979  3536  3536 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 07:10:36.989  3622  3622 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 07:10:36.999  1019  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.999  1019  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.999  1019  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.999  1019  1528 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.009  3605  3605 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-17 07:10:37.009  3644  3644 E Zygote  : MountEmulatedStorage()
03-17 07:10:37.009  3644  3644 E Zygote  : v2
03-17 07:10:37.009  3644  3644 I libpersona: KNOX_SDCARD checking this for 10125
03-17 07:10:37.009  3644  3644 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:37.009  1019  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 07:10:37.019  1019  1528 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3644 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,03-17 07:10:37.019  3305  3305 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 07:10:37.029  3644  3644 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:37.029  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2944/cgroup.procs: No such file or directory
03-17 07:10:37.029  1019  1043 W libprocessgroup: failed to open /acct/uid_10099/pid_2883/cgroup.procs: No such file or directory
03-17 07:10:37.029  1019  1043 W libprocessgroup: failed to open /acct/uid_10098/pid_2280/cgroup.procs: No such file or directory
,03-17 07:10:37.029  3305  3305 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 07:10:37.029  3644  3644 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:37.029  1019  1044 W ProcessCpuTracker: Skipping unknown process pid 2944
,03-17 07:10:37.029  3644  3644 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.039  3294  3294 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 07:10:37.059  3294  3294 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 07:10:37.059  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.059  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.059  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.059  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.069  3644  3644 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.069  3644  3644 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.069  3661  3661 E Zygote  : MountEmulatedStorage()
03-17 07:10:37.069  3661  3661 E Zygote  : v2
03-17 07:10:37.069  3661  3661 I libpersona: KNOX_SDCARD checking this for 10014
03-17 07:10:37.069  3661  3661 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:37.079  3661  3661 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 07:10:37.079  3661  3661 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:37.079  3661  3661 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.079  1019  1031 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3661 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,03-17 07:10:37.079  1019  1031 I ActivityManager: Killing 2737:com.google.android.apps.books/u0a75 (adj 15): empty #31
,03-17 07:10:37.099   318   318 I art     : Explicit concurrent mark sweep GC freed 8793(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 668us total 22.006ms
03-17 07:10:37.099  1019  1044 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 07:10:37.109  1019  1044 W ActivityManager: mDVFSHelper.release()
03-17 07:10:37.109  1019  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 07:10:37.109  3644  3644 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:37.109  3644  3644 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 07:10:37.109  3644  3644 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:37.119  3661  3661 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.119  3661  3661 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.129   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 848us total 21.037ms
,03-17 07:10:37.149   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.223ms total 21.182ms
,03-17 07:10:37.159  1019  1043 W libprocessgroup: failed to open /acct/uid_10075/pid_2737/cgroup.procs: No such file or directory
,03-17 07:10:37.179  3305  3545 D Volley  : [416] DiskBasedCache.clear: Cache cleared.
,03-17 07:10:37.179  3305  3593 D Volley  : [423] DiskBasedCache.clear: Cache cleared.
,03-17 07:10:37.189  1019  1384 I ActivityManager: Killing 2432:com.android.mms/u0a46 (adj 15): empty #31
,03-17 07:10:37.189  1019  1751 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.199  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.199  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:37.199  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:37.199  3661  3661 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 07:10:37.199  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.209  1019  1041 D SensorService: [SO] currT = 40581135000, prevT = 40131081000, diff = 450054000, [0.192 0.421 10.247]
,03-17 07:10:37.209  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.209  1019  1041 D SensorService: [SO] 0.192 0.421 10.247
03-17 07:10:37.209  1019  1041 D SensorService: [SO] [100 -> 255]
03-17 07:10:37.209  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.209  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 07:10:37.209  1353  3152 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 07:10:37.209  1695  1695 V GLSUser : [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,03-17 07:10:37.209  1019  1230 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.209  1019  1230 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.209  1019  1230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.209  1019  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:37.219  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.219  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.219  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.219  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.229  3680  3680 E Zygote  : MountEmulatedStorage(),
03-17 07:10:37.229  3680  3680 I libpersona: KNOX_SDCARD checking this for 10015
03-17 07:10:37.229  3680  3680 E Zygote  : v2
03-17 07:10:37.229  3680  3680 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:37.229  3680  3680 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 07:10:37.229  3661  3678 V OneTimeService: OneTimeService.onHandleIntent
,03-17 07:10:37.239  3680  3680 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:37.239  1019  1751 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3680 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
03-17 07:10:37.239  3680  3680 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 07:10:37.239  3644  3644 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-17 07:10:37.239  3644  3644 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-17 07:10:37.249  1019  1713 D SettingsProvider: name = scon_is_running
03-17 07:10:37.249  1019  1713 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:37.249  1019  1713 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:37.249  1019  1713 D SettingsProvider: selectionArgs: false
03-17 07:10:37.249  1019  1713 D SettingsProvider: selectionArgs: 10125
03-17 07:10:37.249  1019  1713 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:37.249  1019  1713 D SettingsProvider: ret = -1
,03-17 07:10:37.259  1019  1715 D CountryDetector: No listener is left
,03-17 07:10:37.259  1019  1713 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,03-17 07:10:37.269  3680  3680 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.269  3680  3680 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.269  1970  1970 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
03-17 07:10:37.269  1019  3273 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.269  1019  3273 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.269  1019  3273 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.269  1019  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 07:10:37.279  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:37.279  3644  3644 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-17 07:10:37.289  1019  1713 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.289  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.289  1019  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.289  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:37.289  3644  3644 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 07:10:37.299  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.299  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.299  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.299  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.299  3305  3305 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-17 07:10:37.299  3305  3305 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-17 07:10:37.309  3698  3698 E Zygote  : MountEmulatedStorage()
03-17 07:10:37.309  3698  3698 E Zygote  : v2
03-17 07:10:37.309  3698  3698 I libpersona: KNOX_SDCARD checking this for 10131
03-17 07:10:37.309  3698  3698 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:37.309  3698  3698 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:37.319  3698  3698 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:37.319  3698  3698 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.319  1019  1230 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3698 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-17 07:10:37.319  1019  1043 W libprocessgroup: failed to open /acct/uid_10046/pid_2432/cgroup.procs: No such file or directory
,03-17 07:10:37.329  1019  1715 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:37.329  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.329  1019  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.329  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:37.339  3698  3698 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.339  1019  1230 I ActivityManager: Killing 3023:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
03-17 07:10:37.339  3698  3698 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.339  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2194f85 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t235} time:40718
,03-17 07:10:37.349   257   453 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-17 07:10:37.349   257   451 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 07:10:37.349  1019  1044 I ActivityManager: Killing 2095:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,03-17 07:10:37.359  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 07:10:37.359  1019  1019 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-17 07:10:37.359  1019  1019 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:37.369  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.369  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.369  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.369  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.389  3716  3716 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:37.389  3716  3716 E Zygote  : v2
03-17 07:10:37.389  3716  3716 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:37.389  3716  3716 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:37.389  3716  3716 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:37.389  3698  3698 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 07:10:37.389  3698  3698 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:37.389  3698  3698 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:37.389  3698  3698 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:37.389  1019  1019 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3716 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:37.389  3716  3716 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:37.389  3716  3716 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.389  1019  1715 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:37.389  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.389  1019  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.389  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:37.409  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.409  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.409  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.409  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:37.419  3716  3716 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.419  3716  3716 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.419  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 07:10:37.419  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:37.419  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:37.419  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:37.429  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:37.429  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:37.429  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:37.429  3305  3305 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-17 07:10:37.439  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.439  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.439  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.439  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:37.449  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.449  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.449  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:37.449  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 07:10:37.459  1019  1043 W libprocessgroup: failed to open /acct/uid_10012/pid_2095/cgroup.procs: No such file or directory
03-17 07:10:37.459  1019  1043 W libprocessgroup: failed to open /acct/uid_10048/pid_3023/cgroup.procs: No such file or directory
,03-17 07:10:37.459  1019  1713 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.459  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.459  1019  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:37.459  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:37.469  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.469  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.469  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.469  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:37.479  3698  3698 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-17 07:10:37.489  1695  1695 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-17 07:10:37.499  1019  3273 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:37.499  3698  3698 D ManifestProvider: onCreate()
,03-17 07:10:37.499  1019  3273 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.499  1019  3273 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:37.499  1019  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 07:10:37.509  3305  3305 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-17 07:10:37.509  1019  1554 I ActivityManager: Killing 2930:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,03-17 07:10:37.549  3698  3698 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-17 07:10:37.559  1019  1241 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.559  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.559  1019  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.559  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:37.569  1019  1031 I art     : Explicit concurrent mark sweep GC freed 28065(1493KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 30MB/45MB, paused 3.511ms total 172.049ms
,03-17 07:10:37.579  2967  2967 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2967
,03-17 07:10:37.579  3716  3716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:37.589  2967  2967 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2543557b that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 07:10:37.589  2967  2967 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@2543557b that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:37.589  2967  2967 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 07:10:37.599  1019  1384 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.599  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.599  1019  1384 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:37.599  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 07:10:37.609  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 07:10:37.609  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.609  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:37.609  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 07:10:37.609  2604  2604 I Hs20UtilService: Starting #2
,03-17 07:10:37.609  2604  2619 I Hs20UtilService: Message received 5003
03-17 07:10:37.609  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:37.609  2967  2967 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@39d90f98 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 07:10:37.609  2967  2967 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@39d90f98 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:37.609  2967  2967 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 07:10:37.609  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.609  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.609  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:37.609  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 07:10:37.619  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.619  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.619  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.619  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.629  3748  3748 E Zygote  : MountEmulatedStorage()
,03-17 07:10:37.629  3748  3748 E Zygote  : v2,
03-17 07:10:37.629  3748  3748 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:37.629  3748  3748 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:37.629  3748  3748 I libpersona: KNOX_SDCARD not a persona,
,03-17 07:10:37.629  3748  3748 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:37.639  1019  3273 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3748 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 07:10:37.639  3748  3748 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.649  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.649  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.649  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.649  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.659  3748  3748 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.659  3748  3748 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.659  1019  3273 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3759 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 07:10:37.669  3759  3759 E Zygote  : MountEmulatedStorage(),
03-17 07:10:37.669  3759  3759 E Zygote  : v2,
03-17 07:10:37.669  3759  3759 I libpersona: KNOX_SDCARD checking this for 10019
03-17 07:10:37.669  3759  3759 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:37.669  3759  3759 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:37.679  3759  3759 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:37.679  3759  3759 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.699  3759  3759 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.699  3759  3759 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.709  3748  3748 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-17 07:10:37.719  1019  1751 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.719  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.719  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.719  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:37.739  1019  1043 W libprocessgroup: failed to open /acct/uid_10085/pid_2930/cgroup.procs: No such file or directory
,03-17 07:10:37.769  3680  3680 I RlzPingService: Setting next ping for 1458799837777
,03-17 07:10:37.819  3759  3759 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 07:10:37 GMT+01:00 2016
,03-17 07:10:37.819  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:37.819  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.819  1019  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:37.819  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 07:10:37.829  3759  3759 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 07:10:37.829  3698  3698 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@1f618add
,03-17 07:10:37.829  3698  3698 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
03-17 07:10:37.829  3698  3698 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-17 07:10:37.829  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.829  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.829  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.829  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.839  3759  3759 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 07:10:37.839  3759  3759 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 07:10:37.849  3305  3305 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-17 07:10:37.849  3785  3785 E Zygote  : MountEmulatedStorage()
03-17 07:10:37.849  3785  3785 E Zygote  : v2
03-17 07:10:37.849  3785  3785 I libpersona: KNOX_SDCARD checking this for 10022
03-17 07:10:37.849  3785  3785 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:37.849  3759  3759 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 07:10:37.849  1019  1367 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3785 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,03-17 07:10:37.859  3759  3783 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 07:10:37.859  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.859  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.859  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.859  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.859  3759  3783 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED
,03-17 07:10:37.879  3791  3791 E Zygote  : MountEmulatedStorage()
03-17 07:10:37.879  3791  3791 I libpersona: KNOX_SDCARD checking this for 10135
03-17 07:10:37.879  3791  3791 E Zygote  : v2
03-17 07:10:37.879  3791  3791 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:37.879  1019  1367 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3791 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-17 07:10:37.879  1019  1367 I ActivityManager: Killing 3061:com.sec.dsm.system/1000 (adj 15): empty #31
,03-17 07:10:37.939  3785  3785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:37.939  3791  3791 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:37.939  3785  3785 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:37.939  3791  3791 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:37.939  3791  3791 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:37.939  3785  3785 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.949  1019  1384 I ActivityManager: Killing 3087:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-17 07:10:37.959  3759  3759 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 07:10:37.969  3785  3785 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.969  3785  3785 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.979  3791  3791 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 07:10:37.979  3791  3791 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.989  2682  2761 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 07:10:37.999  1019  1528 D TimaService: TIMA: in getTimaVersion
,03-17 07:10:38.009  1019  1715 D TimaService: TIMA3: KeyStore3_init
,03-17 07:10:38.009  1019  1715 D TimaService: TIMA: in getTimaVersion
03-17 07:10:38.009  1019  1715 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize()
,03-17 07:10:38.009  1019  1715 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-17 07:10:38.009  1019  1715 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-17 07:10:38.009  1019  1715 I TLC_TZ_KEYSTORE: : root = /firmware/image, root_strlen = 15
,03-17 07:10:38.009  1019  1715 I TLC_TZ_KEYSTORE: : process = tima_key, process_strlen = 8
03-17 07:10:38.009  1019  1715 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-17 07:10:38.009  3791  3791 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:38.009  1019  1715 I TZ: qc_tlc_communication: process = tima_key, process_strlen = 8
,03-17 07:10:38.009  3791  3791 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:38.009  1019  1715 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 1088 = 0x440
03-17 07:10:38.009  1019  1715 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 1088 = 0x440
03-17 07:10:38.009  1019  1715 I TZ: qc_tlc_communication: max_message_size = 2176 = 0x880
03-17 07:10:38.009  3791  3791 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:38.009  1019  1715 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x880
03-17 07:10:38.009  1019  1715 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 07:10:38.019  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.019  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.019  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.019  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.039  3819  3819 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.039  3819  3819 E Zygote  : v2
03-17 07:10:38.039  3819  3819 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:38.039  3819  3819 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:38.039  3819  3819 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:38.039  3819  3819 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:38.039  1019  1367 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3819 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:38.039  3819  3819 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:38.039  1019  1367 I ActivityManager: Killing 3114:com.sec.android.diagmonagent/1000 (adj 15): empty #31
03-17 07:10:38.039  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3061/cgroup.procs: No such file or directory
,03-17 07:10:38.049  1353  3152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 07:10:38.059  1353  3152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 07:10:38.059  1019  1241 I ActivityManager: Killing 3131:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-17 07:10:38.069  3819  3819 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.069  3819  3819 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.079  1019  1715 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 07:10:38.079  1019  1715 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
03-17 07:10:38.079  1019  1715 I TLC_TZ_KEYSTORE: : ctx = 0xb7a55ab0, comm = 0xb7908c88, sendmsg = 0xa0f75000, recvmsg = 0xa0f75440
03-17 07:10:38.079  1019  1715 I TZ_init: : TZ_init: sending initialization request...
,03-17 07:10:38.079  1019  1715 E TZ_init: : TZ_init Process: Secure memory is not initialized!
03-17 07:10:38.079  1019  1715 E TZ_init: : trustlet initialization failed
03-17 07:10:38.079  1019  1715 I TZ_init: : TZ_init_START...
,03-17 07:10:38.079  1332  1364 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:38.089  1353  3152 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 07:10:38.089  1019  1715 I TZ_init: : TZ_init_with_data: sending initialization request...
,03-17 07:10:38.089  1019  1230 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.089  1019  1715 I TZ_init: : TZ_init: successful initialization
03-17 07:10:38.089  1019  1715 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 07:10:38.089  1019  1715 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-17 07:10:38.089  1019  1715 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,03-17 07:10:38.089  1970  3747 D FileApkUtils: Spent 87ms computing apk sha1.
,03-17 07:10:38.089  1970  3747 D FileApkUtils: Module already staged or being staged:chimera-modules/MapsModule.apk
,03-17 07:10:38.089  1970  3747 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,03-17 07:10:38.089  1019  1230 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:38.089  1019  1230 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:38.089  1019  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 07:10:38.119  1970  3747 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
03-17 07:10:38.119  1970  3747 D DexOptUtils: Lollipop platform, using <isa> directory.
,03-17 07:10:38.119  1970  3747 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
03-17 07:10:38.119  1970  3747 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,03-17 07:10:38.119  3819  3819 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-17 07:10:38.119  1019  3273 D SecContentProvider2: uri = 14 selection = getSealedState
,03-17 07:10:38.119  1019  3273 D SecContentProvider2: mCursor = null
,03-17 07:10:38.129  1019  1230 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 07:10:38.129  1019  1230 D SecContentProvider2: mCursor = null
,03-17 07:10:38.129  3819  3819 V MTPRx   : sealedState: false
03-17 07:10:38.129  3819  3819 V MTPRx   : sealedUsbMassStorageState: false
,03-17 07:10:38.129  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.129  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.129  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.129  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.139  3840  3840 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.139  3840  3840 E Zygote  : v2
03-17 07:10:38.139  3840  3840 I libpersona: KNOX_SDCARD checking this for 10042
03-17 07:10:38.139  3840  3840 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:38.149  3840  3840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:38.149  3840  3840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:38.149  1970  1970 W InstanceID/Rpc: Found 10012
,03-17 07:10:38.149  3840  3840 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 07:10:38.149  1019  1751 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3840 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:38.159  1019  1528 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.159  1019  1528 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.159  1019  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:38.159  1019  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
03-17 07:10:38.159  1019  1715 D SettingsProvider: name = mtp_usb_connection_status
,03-17 07:10:38.169  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3087/cgroup.procs: No such file or directory
03-17 07:10:38.169  1019  1230 D SettingsProvider: name = media_player_mode
,03-17 07:10:38.179  1019  1715 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 07:10:38.189  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
03-17 07:10:38.189  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.189  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.189  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.189  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.189  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3131/cgroup.procs: No such file or directory,
03-17 07:10:38.189  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3114/cgroup.procs: No such file or directory
,03-17 07:10:38.199  1019  3272 D SettingsProvider: name = mtp_running_status
,03-17 07:10:38.209  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:38.209  3840  3840 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.209  3858  3858 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.209  3858  3858 E Zygote  : v2
03-17 07:10:38.209  3858  3858 I libpersona: KNOX_SDCARD checking this for 10139
03-17 07:10:38.209  3858  3858 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:38.209  3840  3840 D ActivityThread: Added TimaKeyStore provider,
03-17 07:10:38.209  1019  1032 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3858 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-17 07:10:38.219  3858  3858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:38.219  3858  3858 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:38.219  3858  3858 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.219  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:38.229  3839  3839 I dex2oat : ----------------------------------------------------
03-17 07:10:38.229  3839  3839 I dex2oat : <SS>: S T A R T I N G . . .
03-17 07:10:38.229  3839  3839 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 07:10:38.229  3839  3839 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=94 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 07:10:38.239  1019  1384 D SettingsProvider: name = media_mount_count
,03-17 07:10:38.239  3858  3858 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.239  3858  3858 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.249  3840  3840 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 07:10:38.249  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:38.249  1019  1389 D SettingsProvider: name = mtp_sync_alive
,03-17 07:10:38.259  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:38.269  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.269  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.269  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.269  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.269  3858  3858 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,03-17 07:10:38.269  3858  3858 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:38.279  3858  3858 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 07:10:38.279  3858  3858 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 07:10:38.279  3858  3858 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:38.289  1019  3272 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.299  1019  3272 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.299  1019  3272 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.299  1019  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.309  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.309  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:38.309  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.309  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.319  1019  1384 I ActivityManager: Killing 3163:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,03-17 07:10:38.329  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-17 07:10:38.329  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:38.329  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:38.329  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-17 07:10:38.329  3716  3746 I AMMetaDataParserService: Resource data:2131165186
03-17 07:10:38.329  3840  3840 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-17 07:10:38.329  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.329  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.329  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.329  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.329  3716  3746 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 07:10:38.329  3716  3746 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:38.329  3716  3746 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:38.329  3716  3746 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:38.329  3716  3746 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-17 07:10:38.329  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:38.339  3879  3879 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.339  3879  3879 I libpersona: KNOX_SDCARD checking this for 10145
,03-17 07:10:38.339  3879  3879 E Zygote  : v2
03-17 07:10:38.339  3879  3879 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:38.339  3879  3879 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:38.349  1019  1241 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3879 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-17 07:10:38.349  3879  3879 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:38.349  3879  3879 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.359  3716  3746 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,03-17 07:10:38.369   318   318 I art     : Explicit concurrent mark sweep GC freed 8757(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 25.391ms
,03-17 07:10:38.369  1019  3273 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.369  1019  3273 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.369  1019  3273 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.369  1019  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.379  1019  1713 D SettingsProvider: name = sdcard_launch
,03-17 07:10:38.379  1019  3272 D SettingsProvider: name = boot_time_connected
,03-17 07:10:38.389  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:38.389  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:38.389   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 17.581ms
,03-17 07:10:38.399  1019  1043 W libprocessgroup: failed to open /acct/uid_10150/pid_3163/cgroup.procs: No such file or directory
,03-17 07:10:38.399  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.399  3879  3879 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.399  3879  3879 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.399  3716  3746 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
03-17 07:10:38.399  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.399  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.399  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.409   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 16.883ms
,03-17 07:10:38.409  1019  1715 D SettingsProvider: name = mtp_open_session
,03-17 07:10:38.429  3716  3746 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510
,03-17 07:10:38.429  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:38.439  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.439  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.439  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.439  1019  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.439  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.439  3748  3748 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,03-17 07:10:38.439  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:38.439  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:38.439  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:38.439  1019  1241 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:38.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:38.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:38.449  3879  3879 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:38.449  3879  3879 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:38.449  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.449  1019  1241 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:38.449  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,03-17 07:10:38.449  3879  3879 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 07:10:38.449  3879  3879 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:38.449  3879  3879 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:38.449  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.449  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:38.449  3467  3467 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 07:10:38.449  3467  3467 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 07:10:38.449  3467  3467 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 07:10:38.449  3467  3467 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-17 07:10:38.449  3467  3467 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 07:10:38.449  3467  3467 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 07:10:38.449  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.449  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-17 07:10:38.459  3716  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.,SelectBookmarkFolderActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-17 07:10:38.459  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
03-17 07:10:38.469  1970  3875 D GCM     : COMPAT: Multi user not supported
03-17 07:10:38.469  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.469  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.469  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.469  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
03-17 07:10:38.489  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:38.489  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:38.489  3716  3746 I AMMetaDataParserService: Resource data:2131034113
,03-17 07:10:38.499  3902  3902 E Zygote  : MountEmulatedStorage(),
03-17 07:10:38.499  3902  3902 E Zygote  : v2
03-17 07:10:38.499  3902  3902 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 07:10:38.499  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.499  1019  1031 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3902 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:38.499  1019  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.499  1019  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
03-17 07:10:38.499  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:38.499  3902  3902 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:38.499  1019  1715 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.499  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.499  1019  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.499  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:38.499  3902  3902 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:38.509  3902  3902 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:38.509  3467  3467 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
03-17 07:10:38.509  3902  3902 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.519  1695  3908 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
03-17 07:10:38.519  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
03-17 07:10:38.519  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.519  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.519  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.519  3716  3746 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 07:10:38.519  3716  3746 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:38.519  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
03-17 07:10:38.519  3716  3746 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:38.519  3716  3746 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:38.529  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:38.529  3716  3746 I GFX construct_block_size_descriptor_2d second part: took 2.292761ms for 0*0 texture 0
,03-17 07:10:38.529  1019  1031 W SEAMService:  hashset_to_int_array returning null
,03-17 07:10:38.539  3902  3902 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.539  3902  3902 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.539  1019  1230 W SEAMService:  hashset_to_int_array returning null
,03-17 07:10:38.549  3748  3748 E SQLiteLog: (284) automatic index on seams_container_info(seams_container_id)
,03-17 07:10:38.549  3748  3748 E SQLiteLog: (284) automatic index on seams_container_info(sp_id)
,03-17 07:10:38.549  3716  3746 I GFX generate_partition_tables: took 6.172292ms for 0*0 texture 0
03-17 07:10:38.549  3716  3746 I GFX raster: took 9.880782ms for 96*96 texture 0
03-17 07:10:38.549  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ab4c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74ab4f8 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:38.549  1019  1031 W SEAMService:  hashset_to_int_array returning null
,03-17 07:10:38.559  1019  1230 D RCPManagerService: exchangeData() failure , invalid userId
03-17 07:10:38.559  3902  3902 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 07:10:38.569  1019  1389 I ActivityManager: Killing 3174:com.google.android.configupdater/u0a86 (adj 15): empty #31,
,03-17 07:10:38.569  3716  3746 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 07:10:38.569  3467  3467 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 07:10:38.579  3467  3467 I ReactiveServiceManager: Supported : 1
,03-17 07:10:38.579  1019  1554 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-17 07:10:38.579  1019  1554 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 07:10:38.589  3902  3902 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
03-17 07:10:38.589  1970  3921 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 07:10:38.589  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.589  1019  1230 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:38.589  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.589  1019  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:38.589  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-17 07:10:38.599  1019  1554 D QSEECOMAPI: : Loaded image: APP id = 10
,03-17 07:10:38.609  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.609  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.609  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.609  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.609  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:38.609  3716  3746 I GFX raster: took 0.815208ms for 96*96 texture 0
03-17 07:10:38.609  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ab4c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74ab4f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:38.609  1019  1554 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 07:10:38.609  1019  1554 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-17 07:10:38.609  1019  1554 E terrier : handleString: Failed to handle string(-4)
03-17 07:10:38.609  1019  1554 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-17 07:10:38.619  3928  3928 E Zygote  : MountEmulatedStorage(),
03-17 07:10:38.619  3928  3928 E Zygote  : v2
03-17 07:10:38.619  3928  3928 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 07:10:38.619  3467  3467 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 07:10:38.619  1019  1715 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3928 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:38.619  3467  3467 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-17 07:10:38.629  3928  3928 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:38.619  3467  3467 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 07:10:38.619  3467  3467 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 07:10:38.619  3467  3467 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 07:10:38.619  3467  3467 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
03-17 07:10:38.629  3928  3928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:38.629  3716  3746 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
03-17 07:10:38.629  3928  3928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:38.629  3928  3928 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:38.629  3902  3902 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
03-17 07:10:38.639  2655  2655 D FactoryTestApp: [DummyFtClient$onDestroy](2655) Destroy DummyFtClient service
03-17 07:10:38.639  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 07:10:38.639  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.639  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.639  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.639  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.649  3902  3902 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
03-17 07:10:38.649  1019  1043 W libprocessgroup: failed to open /acct/uid_10086/pid_3174/cgroup.procs: No such file or directory
,03-17 07:10:38.659  1019  1241 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:38.669  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:38.669  3946  3946 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.669  3946  3946 I libpersona: KNOX_SDCARD checking this for 10031
03-17 07:10:38.669  3946  3946 E Zygote  : v2
03-17 07:10:38.669  3946  3946 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:38.669  3716  3746 I GFX construct_block_size_descriptor_2d second part: took 2.520521ms for 0*0 texture 0
03-17 07:10:38.669  1019  1715 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3946 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-17 07:10:38.669  3946  3946 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:38.679  1970  1970 D SystemUpdateService: onCreate
03-17 07:10:38.679  1019  1715 I ActivityManager: Killing 3217:com.policydm/1000 (adj 15): empty #31
,03-17 07:10:38.679  3946  3946 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:38.679  3946  3946 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.689  3716  3746 I GFX generate_partition_tables: took 7.671771ms for 0*0 texture 0
03-17 07:10:38.689  3716  3746 I GFX raster: took 11.125521ms for 96*96 texture 0
03-17 07:10:38.689  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ab4f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c4ce8 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:38.699  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
03-17 07:10:38.699  3928  3928 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:38.699  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.699  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:38.699  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
03-17 07:10:38.699  3928  3928 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.699  3716  3746 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 07:10:38.709  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 07:10:38.709  1019  1554 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:38.709  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.709  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.709  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:38.709  2655  2655 D FactoryTestApp: [Support$Values.getString](2655) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 07:10:38.709  2655  2655 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2655) mConnectionMode = gsm
03-17 07:10:38.709  2655  2655 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2655) RUNNING_FTCLIENT : false
03-17 07:10:38.709  2655  2655 D FactoryTestApp: [DummyFtClient$onDestroy](2655) kill process
03-17 07:10:38.709  2655  2655 I Process : Sending signal. PID: 2655 SIG: 9
,03-17 07:10:38.729  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:38.739  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:38.739  3716  3746 I GFX raster: took 0.720208ms for 96*96 texture 0
03-17 07:10:38.739  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cc7a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74cc870 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:38.739  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.739  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.739  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.739  1019  1713 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.739  3946  3946 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.749  3946  3946 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.749  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:38.749  1019  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.749  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.749  3902  3902 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
,03-17 07:10:38.749  3902  3902 I F_PHONE : default registerAction()
03-17 07:10:38.749  3902  3902 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 07:10:38.759  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
03-17 07:10:38.759  1019  1241 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
03-17 07:10:38.759  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.759  1019  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.759  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.759  1019  1389 I ActivityManager: Process com.sec.factory (pid 2655)(adj 0) has died(48,1108)
,03-17 07:10:38.769  1019  1389 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:38.769  3716  3746 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 07:10:38.779  1019  3273 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.779  1019  3273 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:38.779  1019  3273 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:38.779  1019  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-17 07:10:38.779  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3217/cgroup.procs: No such file or directory
,03-17 07:10:38.779  1970  1970 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 07:10:38.789  1970  3875 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 07:10:38.789  3928  3928 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:38.789  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.789  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.789  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.789  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.809  3973  3973 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.809  3973  3973 E Zygote  : v2
,03-17 07:10:38.809  3973  3973 I libpersona: KNOX_SDCARD checking this for 10072
03-17 07:10:38.809  3973  3973 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:38.809  3973  3973 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:38.809  3973  3973 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 07:10:38.809  3973  3973 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.809  1019  3272 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=3973 uid=10072 gids={50072, 9997} abi=armeabi-v7a
03-17 07:10:38.809  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.819  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:38.819  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.819  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.819  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.819  3716  3746 I GFX raster: took 1.008125ms for 96*96 texture 0
03-17 07:10:38.819  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74caa08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74caa40 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:38.829  1019  3273 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:38.829  3946  3946 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 07:10:38.829  3928  3928 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
03-17 07:10:38.829  3928  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:38.839  3716  3746 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
03-17 07:10:38.839  1019  3273 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.839  1019  3273 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:38.839  1019  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:38.849  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.849  1695  1695 I ConfigService: onCreate
,03-17 07:10:38.869  3973  3973 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.869  3973  3973 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.869  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:38.869  1019  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:38.869  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-17 07:10:38.869  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:38.869  3716  3746 I GFX raster: took 0.621562ms for 96*96 texture 0
03-17 07:10:38.869  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74caa40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74cba18 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:38.869  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.869  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.869  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.869  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.879  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 07:10:38.879  1501  1501 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:38.879  1501  1501 D BluetoothBDTestService: onCreate()
,03-17 07:10:38.889  1501  1501 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
,03-17 07:10:38.889  1501  1501 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-17 07:10:38.889  1501  1501 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17,
03-17 07:10:38.889  3996  3996 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.889  3996  3996 I libpersona: KNOX_SDCARD checking this for 10146
,03-17 07:10:38.889  3996  3996 E Zygote  : v2
03-17 07:10:38.889  3996  3996 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:38.889  3996  3996 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:38.889  1970  1970 I ConfigFetchService: onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
,03-17 07:10:38.889  3996  3996 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:38.899  3996  3996 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:38.899  1019  1384 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=3996 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 07:10:38.909  1970  3923 I CheckinService: Checking schedule, now: 1458195038917 next: 1458225725438
,03-17 07:10:38.909  1970  3923 I CheckinService: active receiver: disabled
03-17 07:10:38.909  1019  1384 I ActivityManager: Killing 3240:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,03-17 07:10:38.909  1019  1554 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:38.909  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:38.909  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:38.909  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:38.909  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:38.909  3716  3746 I GFX raster: took 0.697239ms for 96*96 texture 0
03-17 07:10:38.909  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74c93b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c9478 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:38.919  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.919  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.919  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.919  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.919  3716  3746 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 07:10:38.919  3996  3996 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.919  3996  3996 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.939  4012  4012 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.939  4012  4012 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:38.939  4012  4012 E Zygote  : v2
03-17 07:10:38.939  4012  4012 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:38.939  4012  4012 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:38.949  1019  1384 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4012 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:38.949  1019  1384 I ActivityManager: Killing 3283:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,03-17 07:10:38.949  4012  4012 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:38.959  4012  4012 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.979  1811  1811 I GCoreUlr: DispatchingService.onCreate()
,03-17 07:10:38.989  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:38.989  3716  3746 I GFX raster: took 0.527969ms for 96*96 texture 0
03-17 07:10:38.989  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cbc30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74cbcf8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:38.999  1019  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:38.999  3973  3973 D BadgeProvider: onCreate
,03-17 07:10:38.999  3973  3973 D BadgeProvider: DatabaseHelper
,03-17 07:10:39.009  3996  3996 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:39.019  3716  3746 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527,
,03-17 07:10:39.019  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.019  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.019  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:39.029  4012  4012 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.029  4012  4012 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.049  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-17 07:10:39.049  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:39.049  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:39.049  3716  3746 I AMMetaDataParserService: Resource data:2131034113
,03-17 07:10:39.069  3716  3746 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 07:10:39.069  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:39.069  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.069  3716  3746 I GFX raster: took 0.841510ms for 96*96 texture 0
03-17 07:10:39.069  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ab4c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74c5998 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.079  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.079  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.079  1019  1554 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:39.079  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 07:10:39.089  3716  3746 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 07:10:39.099  1019  3272 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.109  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.109  3716  3746 I GFX raster: took 0.820156ms for 96*96 texture 0
03-17 07:10:39.109  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ab4c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74cdd00 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.119  3716  3746 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 07:10:39.139  1019  3272 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.139  1019  3272 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.139  1019  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:39.139  3946  3946 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
03-17 07:10:39.139  4012  4012 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:39.159  1970  4035 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 07:10:39.169  1970  4035 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-17 07:10:39.189  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.189  1019  3272 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:39.189  3716  3746 I GFX raster: took 0.678437ms for 96*96 texture 0
03-17 07:10:39.189  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ab4f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74cc5f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.199  3716  3746 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 07:10:39.219  1970  4035 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 07:10:39.229  1970  3972 I SystemUpdateService: cancelUpdate (empty URL)
,03-17 07:10:39.229  1970  3972 I SystemUpdateService: active receiver: disabled
,03-17 07:10:39.259  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.259  1019  4038 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 07:10:39.269  3716  3746 I GFX raster: took 0.652345ms for 96*96 texture 0
03-17 07:10:39.269  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cc7a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c8d60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.269  3716  3746 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 07:10:39.279  1970  4035 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,03-17 07:10:39.289  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.289  3716  3746 I GFX raster: took 0.813854ms for 96*96 texture 0
03-17 07:10:39.289  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74caa08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c8d60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.289  3716  3746 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 07:10:39.309  1019  1043 W libprocessgroup: failed to open /acct/uid_10003/pid_3283/cgroup.procs: No such file or directory
03-17 07:10:39.309  1019  1043 W libprocessgroup: failed to open /acct/uid_10094/pid_3240/cgroup.procs: No such file or directory
,03-17 07:10:39.329  1970  4035 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,03-17 07:10:39.329  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.329  3716  3746 I GFX raster: took 0.632552ms for 96*96 texture 0
03-17 07:10:39.329  1019  1230 I art     : Explicit concurrent mark sweep GC freed 24921(1482KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 30MB/45MB, paused 2.864ms total 171.720ms
,03-17 07:10:39.329  3973  3985 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 07:10:39.339  1019  1045 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
03-17 07:10:39.339  1019  1715 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.339  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74caa40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c8d60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.349  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 07:10:39.349  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.349  1019  1045 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
03-17 07:10:39.349  1019  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:39.349  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:39.349  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 07:10:39.349  1019  1367 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 07:10:39.359  1019  1528 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.369  1019  1528 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.369  1019  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:39.369  1019  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-17 07:10:39.369  1019  1715 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.369  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.369  3716  3746 I GFX raster: took 0.687968ms for 96*96 texture 0
03-17 07:10:39.369  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74c93b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c8d60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.379  4012  4012 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-17 07:10:39.379  1019  3272 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.379  4012  4012 I KnoxUsageLogPro: premStatus:2
,03-17 07:10:39.379  3716  3746 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 07:10:39.389  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.389  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.389  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.389  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.389  4012  4051 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458195039399
,03-17 07:10:39.389  4012  4012 I KnoxUsageLogPro: isEulaShown : false
03-17 07:10:39.389  4012  4012 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-17 07:10:39.399  4053  4053 E Zygote  : MountEmulatedStorage()
03-17 07:10:39.399  4053  4053 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:39.399  4053  4053 E Zygote  : v2
03-17 07:10:39.399  4053  4053 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:39.399  4053  4053 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:39.409  4053  4053 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:39.409  1019  1384 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4053 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:39.409  4053  4053 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:39.409  1019  1384 I ActivityManager: Killing 3335:com.sec.factory.camera/1000 (adj 15): empty #31
03-17 07:10:39.409  1811  4034 I art     : Explicit concurrent mark sweep GC freed 12920(801KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 10MB/17MB, paused 1.091ms total 202.531ms
,03-17 07:10:39.429  4012  4051 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 42763
,03-17 07:10:39.429  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:39.429  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:39.429  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:39.429  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:39.439  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:39.439  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:39.439  3946  3946 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,03-17 07:10:39.439  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:39.439  3716  3746 I GFX raster: took 0.549688ms for 96*96 texture 0
03-17 07:10:39.439  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cbc30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c8d60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.449  3716  3746 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 07:10:39.459  4053  4053 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:39.459  4053  4053 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.459  1531  1531 D Launcher.Model: reloadBadges entered.
03-17 07:10:39.459  3973  3994 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 07:10:39.459  3973  3994 D BadgeProvider: sendNotify, [notify] : null
03-17 07:10:39.459  3973  3994 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 07:10:39.459  3973  3994 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 07:10:39.459  3973  3994 D BadgeProvider: update, [UpdateCount] : 1
,03-17 07:10:39.469  1019  4037 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1191 (0x0)
,03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
,03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
,03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
,03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
,03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
,03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:39.489  3716  3746 I AMMetaDataParserService: Resource data:2131034112
,03-17 07:10:39.489  1019  1230 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
,03-17 07:10:39.499  3716  3746 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-17 07:10:39.499  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:39.499  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.499  3716  3746 I GFX raster: took 0.605781ms for 96*96 texture 0
03-17 07:10:39.499  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cc7a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c8d60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.499  1019  1554 I ActivityManager: Killing 3356:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,03-17 07:10:39.519  1970  2148 I art     : Explicit concurrent mark sweep GC freed 33912(2MB) AllocSpace objects, 41(656KB) LOS objects, 40% free, 11MB/19MB, paused 1.680ms total 144.107ms
,03-17 07:10:39.529  3716  3746 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-17 07:10:39.529  3879  3980 I Process : Sending signal. PID: 3879 SIG: 9
,03-17 07:10:39.549  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.549  3716  3746 I GFX raster: took 1.335156ms for 96*96 texture 0
,03-17 07:10:39.549  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cc7a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c8d60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.559  1019  4038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.559  1019  4038 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.559  1019  4038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.559  1019  4038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:39.579  3716  3746 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-17 07:10:39.579  1970  4035 I AuthZen : Fetching signing key...
,03-17 07:10:39.589  1019  1043 W libprocessgroup: failed to open /acct/uid_10100/pid_3356/cgroup.procs: No such file or directory
,03-17 07:10:39.589  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3335/cgroup.procs: No such file or directory
,03-17 07:10:39.599  1970  1970 I ConfigFetchService: service connected
,03-17 07:10:39.619  1970  4035 I AuthZen : Signing key fetched successfully!
,03-17 07:10:39.629  1970  4035 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 07:10:39.629  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.629  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.629  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.629  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.639  1970  4035 I AuthZen : Starting Enrollment...
,03-17 07:10:39.649  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec,
03-17 07:10:39.649  4078  4078 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:39.649  4078  4078 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:39.649  4078  4078 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:39.649  4078  4078 E Zygote  : v2
03-17 07:10:39.649  4078  4078 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:39.649  4078  4078 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:39.649  4078  4078 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:39.659  1019  1367 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4078 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:39.659   254   254 E lowmemorykiller: Error writing /proc/3879/oom_score_adj; errno=22
03-17 07:10:39.659  1019  1367 I ActivityManager: Killing 3378:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,03-17 07:10:39.679  1019  4037 I ActivityManager: Killing 3396:com.samsung.helphub/1000 (adj 15): empty #31
,03-17 07:10:39.679  4078  4078 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.689  4078  4078 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.709  3946  3946 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 07:10:39.709  3946  3946 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 07:10:39.719  3946  3946 D DialogFlow: initQueue()
,03-17 07:10:39.729  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.729  3716  3746 I GFX raster: took 0.762969ms for 96*96 texture 0
03-17 07:10:39.729  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74c8d60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7488d40 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.739  3716  3746 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-17 07:10:39.739  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.739  3716  3746 I GFX raster: took 0.705521ms for 96*96 texture 0
,03-17 07:10:39.739  4078  4078 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 07:10:39.739  4078  4078 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,03-17 07:10:39.749  4078  4078 D SecurityLogAgent: StateMachine : Current State = 1
03-17 07:10:39.749  4078  4078 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-17 07:10:39.749  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.749  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.749  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.749  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.749  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ac718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7471bc0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.759  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528,
03-17 07:10:39.759  1019  3273 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4095 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,03-17 07:10:39.769  1019  3273 I ActivityManager: Killing 3419:com.fmm.dm/1000 (adj 15): empty #31,
,03-17 07:10:39.769  4095  4095 E Zygote  : MountEmulatedStorage()
03-17 07:10:39.769  4095  4095 E Zygote  : v2,
03-17 07:10:39.769  4095  4095 I libpersona: KNOX_SDCARD checking this for 10152
03-17 07:10:39.769  4095  4095 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:39.769  4095  4095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 07:10:39.779  4095  4095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 07:10:39.789  4095  4095 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:39.809  1019  1751 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:39.809  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.809  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.809  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:39.819  4095  4095 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.819  4095  4095 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.em,ergency.InteractionEmergencyMessageActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: Resource data:2131034113
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 07:10:39.829  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
03-17 07:10:39.829  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:39.829  3716  3746 I GFX raster: took 0.813489ms for 96*96 texture 0
03-17 07:10:39.829  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb713f5c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb748a198 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:39.839  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.839  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.839  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.839  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.859  1019  3273 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4111 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
03-17 07:10:39.859   254   254 E lowmemorykiller: Error writing /proc/3879/oom_score_adj; errno=22
03-17 07:10:39.859  1019  3273 I ActivityManager: Killing 3435:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
03-17 07:10:39.859  4111  4111 E Zygote  : MountEmulatedStorage()
03-17 07:10:39.859  4111  4111 I libpersona: KNOX_SDCARD checking this for 10032
03-17 07:10:39.859  4111  4111 E Zygote  : v2
03-17 07:10:39.859  4111  4111 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:39.859   291   291 E SMD     : DCD OFF,
03-17 07:10:39.859  4111  4111 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:39.869  4111  4111 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:39.869  4111  4111 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:39.879  3716  3746 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
03-17 07:10:39.889  4111  4111 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:39.889  4111  4111 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:39.899  1019  4037 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:39.899  1019  4037 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.899  1019  4037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.899  1019  4037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:39.909  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.909  3716  3746 I GFX raster: took 0.813073ms for 96*96 texture 0
03-17 07:10:39.909  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb713f5c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb71fd3b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.909  3716  3746 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 07:10:39.919  4095  4095 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-17 07:10:39.959  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3396/cgroup.procs: No such file or directory
03-17 07:10:39.959  1019  1043 W libprocessgroup: failed to open /acct/uid_10060/pid_3378/cgroup.procs: No such file or directory
,03-17 07:10:39.959  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3419/cgroup.procs: No such file or directory
03-17 07:10:39.959  1019  1043 W libprocessgroup: failed to open /acct/uid_10062/pid_3435/cgroup.procs: No such file or directory
,03-17 07:10:39.959  1019  4037 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.959  1019  4037 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.959  1019  4037 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:39.959  1019  4037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,03-17 07:10:39.969  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.969  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.969  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.969  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.969  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:39.969  3716  3746 I GFX raster: took 0.648542ms for 96*96 texture 0
,03-17 07:10:39.979  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb70dd888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7488d40 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:39.979  1695  1712 I art     : Explicit concurrent mark sweep GC freed 8161(457KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 10MB/17MB, paused 1.013ms total 459.768ms
,03-17 07:10:39.979  4131  4131 E Zygote  : MountEmulatedStorage()
03-17 07:10:39.979  4131  4131 E Zygote  : v2
03-17 07:10:39.979  4131  4131 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:39.979  4131  4131 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:39.979  4131  4131 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:39.989  1019  1032 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4131 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:39.989  4131  4131 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:39.989  1970  4035 D AuthZen : getting auth token. Attempt 0
,03-17 07:10:39.999  1019  3272 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 07:10:39.999  4131  4131 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.009  3716  3746 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 07:10:40.009  1970  1970 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-17 07:10:40.019  4131  4131 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.019  4131  4131 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:40.019   318   318 I art     : Explicit concurrent mark sweep GC freed 8773(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 656us total 37.127ms
03-17 07:10:40.019  1019  3272 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:40.019  1019  3272 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:40.019  1019  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:40.019  1019  1715 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:40.029  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:40.029  1019  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:40.029  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:40.039   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 673us total 19.924ms
,03-17 07:10:40.049  1970  1970 I Kids    : [GCoreUtils] Current gmscore version, 7899436 is smaller than the required version 8400000
,03-17 07:10:40.049  1019  1032 I ActivityManager: Process com.android.email (pid 3879)(adj 13) has died(52,1108)
03-17 07:10:40.059  3996  3996 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@30d9c3ab
03-17 07:10:40.059  3996  3996 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@30d9c3ab
,03-17 07:10:40.059   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.767ms
,03-17 07:10:40.079  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.079  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.079  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.079  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.089  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:40.099  3716  3746 I GFX raster: took 0.666457ms for 96*96 texture 0
03-17 07:10:40.099  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cc7a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7471bc0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:40.099  3840  3840 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-17 07:10:40.109  4151  4151 E Zygote  : MountEmulatedStorage()
,03-17 07:10:40.109  4151  4151 E Zygote  : v2
03-17 07:10:40.109  4151  4151 I libpersona: KNOX_SDCARD checking this for 10145
03-17 07:10:40.109  4151  4151 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.109  4151  4151 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 07:10:40.109  1019  1031 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4151 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
03-17 07:10:40.109  4151  4151 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:40.109  1019  4037 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.109  4151  4151 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.109  1019  4037 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:40.109  1019  4037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:40.119  1019  4037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:40.119  3716  3746 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 07:10:40.119  1970  1970 D SystemUpdateService: onDestroy
03-17 07:10:40.119  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.119  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.119  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.119  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.139  4165  4165 E Zygote  : MountEmulatedStorage()
03-17 07:10:40.139  4165  4165 E Zygote  : v2
03-17 07:10:40.139  4165  4165 I libpersona: KNOX_SDCARD checking this for 10033
03-17 07:10:40.139  4165  4165 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.139  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:40.139  4165  4165 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:40.139  3716  3746 I GFX raster: took 0.868542ms for 96*96 texture 0
03-17 07:10:40.139  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb748a198 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb71fd3b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:40.139  4165  4165 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 07:10:40.139  4165  4165 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-17 07:10:40.139  1019  1751 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4165 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 07:10:40.149  4151  4151 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.149  4151  4151 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:40.149  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.149  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.149  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.149  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.159  3716  3746 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 07:10:40.169  4180  4180 E Zygote  : MountEmulatedStorage()
03-17 07:10:40.169  4180  4180 E Zygote  : v2
03-17 07:10:40.169  4180  4180 I libpersona: KNOX_SDCARD checking this for 1101
03-17 07:10:40.169  4180  4180 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.169  4180  4180 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:40.179  4180  4180 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:40.179  4180  4180 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.179  1019  1751 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4180 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,03-17 07:10:40.179  1019  1751 I ActivityManager: Killing 3450:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,03-17 07:10:40.179  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:40.179  3716  3746 I GFX raster: took 0.673490ms for 96*96 texture 0
03-17 07:10:40.179  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ac718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7488d40 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:40.179  4165  4165 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.189  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.189  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.189  4165  4165 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:40.189  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.189  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
03-17 07:10:40.189  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.199  4192  4192 E Zygote  : MountEmulatedStorage()
03-17 07:10:40.199  4192  4192 E Zygote  : v2
03-17 07:10:40.199  4192  4192 I libpersona: KNOX_SDCARD checking this for 10104
03-17 07:10:40.199  4192  4192 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.209  4192  4192 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 07:10:40.209  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:40.209  3716  3746 I GFX raster: took 0.679219ms for 96*96 texture 0
,03-17 07:10:40.209  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7471bc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb71fd3b0 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:40.209  4192  4192 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:40.209  4192  4192 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 07:10:40.209  1019  1751 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4192 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-17 07:10:40.209  1019  3273 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:40.219  1019  3273 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:40.219  1019  3273 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:40.219  1019  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:40.229  1970  1970 D ConfigFetchService: ConfigApi connection successful.
,03-17 07:10:40.229  3716  3746 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 07:10:40.249  4180  4180 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.249  4180  4180 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:40.249  1019  1554 I ActivityManager: Killing 3484:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-17 07:10:40.249  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.249  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:40.249  3716  3746 I GFX raster: took 0.526094ms for 96*96 texture 0
03-17 07:10:40.249  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7488d40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb71fd3b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:40.249  4192  4192 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.259  4192  4192 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.259  1695  4101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
,03-17 07:10:40.259  1695  4101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-17 07:10:40.259  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.269  1019  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:40.269  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 07:10:40.269  1695  4101 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-17 07:10:40.269  1695  4101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 07:10:40.279  3716  3746 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 07:10:40.279  4151  4151 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:40.279  4151  4151 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:40.279  4151  4151 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:40.279  4151  4151 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:40.279  4151  4151 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-17 07:10:40.309  3716  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 07:10:40.309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-17 07:10:40.,309  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-17 07:10:40.319  1695  4101 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:40.319  4180  4180 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,03-17 07:10:40.329  1019  1230 I ActivityManager: Killing 3502:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-17 07:10:40.329  1019  1230 I ActivityManager: Killing 3536:com.fmm.ds/1000 (adj 15): empty #31
,03-17 07:10:40.329  1019  1715 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.339  4192  4192 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:40.339  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.339  1019  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:40.339  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:40.349  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,03-17 07:10:40.349  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-17 07:10:40.359  4180  4180 V SmartcardService: main Received broadcast
03-17 07:10:40.359  4180  4180 V SmartcardService: Starting smartcard service after boot completed
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:40.359  3716  3746 I AMMetaDataParserService: Resource data:2131165203
,03-17 07:10:40.369  1019  1528 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.369  1019  1528 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.369  1019  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:40.369  1019  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,03-17 07:10:40.379  3716  3746 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 07:10:40.379  3716  3746 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:40.379  3716  3746 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:40.379  3716  3746 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:40.379  3716  3746 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:40.389  1019  4038 I ActivityManager: Killing 3517:com.wssnps/1000 (adj 15): empty #31
,03-17 07:10:40.399  1970  3952 I EventLogService: Aggregate from 1458192985994 (log), 1458192985994 (data)
,03-17 07:10:40.399  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.409  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.409  1019  1367 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:40.409  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 07:10:40.429  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.429  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.429  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.429  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.439  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:40.439  4212  4212 E Zygote  : MountEmulatedStorage()
03-17 07:10:40.439  4212  4212 E Zygote  : v2
03-17 07:10:40.439  4212  4212 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:40.439  4212  4212 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:40.439  4212  4212 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:40.449  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700",
03-17 07:10:40.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:40.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:40.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
03-17 07:10:40.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:40.449  1019  1713 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=4212 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:40.449  4212  4212 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 07:10:40.449  4212  4212 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.459  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3450/cgroup.procs: No such file or directory
03-17 07:10:40.459  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3484/cgroup.procs: No such file or directory
,03-17 07:10:40.459  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3502/cgroup.procs: No such file or directory
03-17 07:10:40.459  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3536/cgroup.procs: No such file or directory
,03-17 07:10:40.459  1019  1367 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:40.469  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3517/cgroup.procs: No such file or directory
,03-17 07:10:40.479  3716  3746 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-17 07:10:40.479  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:40.489  1019  1713 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:40.489  1811  4034 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-17 07:10:40.499  4212  4212 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.499  4212  4212 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.549  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:40.549  3716  3746 I GFX construct_block_size_descriptor_2d second part: took 2.489636ms for 0*0 texture 0
,03-17 07:10:40.549  1970  4035 E AuthZen : Error getting auth token
03-17 07:10:40.549  1970  4035 E AuthZen : com.google.android.gms.auth.ad: BadAuthentication
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:318)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 07:10:40.549  1970  4035 E AuthZen : Failed to do enrollment for account: thalitester@gmail.com
03-17 07:10:40.549  1970  4035 E AuthZen : com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:40.549  1970  4035 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 07:10:40.559  1019  4037 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:40.559  1019  4038 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:40.579  4212  4212 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:40.579  1019  4038 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.579  1019  4038 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:40.579  1019  4038 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:40.579  1019  4038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,03-17 07:10:40.589  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.589  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.589  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.589  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.599  4165  4165 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:40.599  4165  4165 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:40.599  4165  4165 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:40.599  3716  3746 I GFX generate_partition_tables: took 10.034531ms for 0*0 texture 0
,03-17 07:10:40.599  3716  3746 I GFX raster: took 13.348855ms for 96*96 texture 0
03-17 07:10:40.599  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb767cc30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb767ccd8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:40.609  4234  4234 E Zygote  : MountEmulatedStorage()
03-17 07:10:40.609  4234  4234 I libpersona: KNOX_SDCARD checking this for 10157
03-17 07:10:40.609  4234  4234 E Zygote  : v2
03-17 07:10:40.609  4234  4234 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:40.609  4234  4234 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:40.609  4234  4234 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:40.609  4234  4234 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.619  1019  1241 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4234 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,03-17 07:10:40.619  3716  3746 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-17 07:10:40.619  4165  4165 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:40.629  1970  4035 D a       : Opening database auth.proximity.permit_store...
,03-17 07:10:40.629  1019  1043 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
03-17 07:10:40.629  4165  4165 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:40.629  4165  4165 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:40.639  4234  4234 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.639  4234  4234 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.649  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:40.649  3716  3746 I GFX raster: took 0.773802ms for 96*96 texture 0
03-17 07:10:40.649  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7498018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74980c0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:40.649  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 07:10:40.659  4165  4165 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:40.659  4165  4165 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-17 07:10:40.659  4165  4165 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:40.669  3716  3746 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 07:10:40.669  1970  4035 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
,03-17 07:10:40.669  1970  4035 D AuthZenTransactionCache: Clearing transaction cache
,03-17 07:10:40.669  4234  4234 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:40.689  1695  1695 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,03-17 07:10:40.699  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.699  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.699  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.699  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.719  4250  4250 E Zygote  : MountEmulatedStorage(),
03-17 07:10:40.719  4250  4250 E Zygote  : v2
03-17 07:10:40.719  4250  4250 I libpersona: KNOX_SDCARD checking this for 10159,
03-17 07:10:40.719  4250  4250 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.719  4250  4250 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 07:10:40.719  4250  4250 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:40.729  4250  4250 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.729  1019  1031 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4250 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:40.729  1019  1031 I ActivityManager: Killing 3556:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 07:10:40.739  1019  1554 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:40.739  1019  1389 W ActivityManager: getTasks: caller 10146 does not hold GET_TASKS; limiting output
,03-17 07:10:40.749  1019  1031 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:40.749  3996  4069 I Process : Sending signal. PID: 3996 SIG: 9
,03-17 07:10:40.759  3839  3839 I dex2oat : dex2oat took 2.529s (threads: 4)
,03-17 07:10:40.759  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:40.769  3716  3746 I GFX raster: took 0.838177ms for 96*96 texture 0
03-17 07:10:40.769  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7498018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7499538 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:40.769  4151  4232 W art     : Verification of boolean com.android.email.activity.MessageListItemOuterContainer.onTouchEvent(android.view.MotionEvent) took 110.448ms
,03-17 07:10:40.769  3716  3746 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 07:10:40.779  3973  3994 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 07:10:40.779  4250  4250 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:40.779  4250  4250 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.789  1970  3747 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
03-17 07:10:40.789  1970  3747 D DexOptUtils: Set odex to world readable.
,03-17 07:10:40.789  1970  3747 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
,03-17 07:10:40.789  1970  3747 D FileApkUtils: Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
,03-17 07:10:40.809  1019  1528 I ActivityManager: Process com.android.exchange (pid 3996)(adj 15) has died(41,1112)
,03-17 07:10:40.819  1531  1531 D Launcher.Model: reloadBadges entered.
,03-17 07:10:40.819  3973  3992 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 07:10:40.819  3973  3992 D BadgeProvider: sendNotify, [notify] : null
03-17 07:10:40.819  3973  3992 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 07:10:40.819  3973  3992 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 07:10:40.819  3973  3992 D BadgeProvider: update, [UpdateCount] : 1
,03-17 07:10:40.829  1970  3747 D GmsModuleFndr: Beginning GMS chimera module scan
,03-17 07:10:40.839  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3556/cgroup.procs: No such file or directory
,03-17 07:10:40.839  1970  3747 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
03-17 07:10:40.839  1970  3747 D ChimeraCfgMgr: Beginning module configuration check
,03-17 07:10:40.839  1970  3747 D ChimeraCfgMgr: Module APKs unchanged, check complete
,03-17 07:10:40.869  4250  4250 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
,03-17 07:10:40.879  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:40.879  3716  3746 I GFX raster: took 0.778854ms for 96*96 texture 0
03-17 07:10:40.879  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7498018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb749b990 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:40.879  3716  3746 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 07:10:40.899  1019  2775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-17 07:10:40.959  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:40.959  3716  3746 I GFX raster: took 0.618074ms for 96*96 texture 0
03-17 07:10:40.959  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb749bab8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb749bbf0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:40.969  3716  3746 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 07:10:41.029  1019  2775 D SSRM:n  : SIOP:: AP = 400
,03-17 07:10:41.039  1019  1528 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,03-17 07:10:41.039  1019  1528 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 07:10:41.039  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 07:10:41.039  1019  3273 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 07:10:41.059  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.059  3716  3746 I GFX raster: took 0.622241ms for 96*96 texture 0
,03-17 07:10:41.059  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb749bab8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb749bbf0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.069  3716  3746 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 07:10:41.079  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,03-17 07:10:41.079  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-17 07:10:41.079  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-17 07:10:41.079  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
,03-17 07:10:41.079  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-17 07:10:41.079  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-17 07:10:41.079  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:41.079  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
,03-17 07:10:41.079  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
,03-17 07:10:41.089  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
,03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR,
03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-17 07:10:41.099  3716  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
,03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity,
03-17 07:10:41.099  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-17 07:10:41.109  4111  4128 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:41.109  4111  4128 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:41.109  4111  4128 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:41.119  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-17 07:10:41.119  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-17 07:10:41.119  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-17 07:10:41.119  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-17 07:10:41.119  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-17 07:10:41.119  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:41.119  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 07:10:41.119  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 07:10:41.119  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:41.119  3716  3746 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:41.129  3716  3746 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-17 07:10:41.129  3716  3746 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:41.129  3716  3746 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:41.129  3716  3746 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:41.129  3716  3746 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 07:10:41.129  3716  3746 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:41.129  3716  3746 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:41.129  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:41.129  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.129  3716  3746 I GFX raster: took 0.935312ms for 96*96 texture 0
03-17 07:10:41.129  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb79d31f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb79d32a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.159  1811  4034 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-17 07:10:41.159  3716  3746 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:41.169  1811  4034 I GCoreUlr: Unbound from all location providers
,03-17 07:10:41.169  4165  4165 I Process : Sending signal. PID: 4165 SIG: 9
,03-17 07:10:41.209  4111  4128 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 07:10:41.209  4192  4284 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-17 07:10:41.209  4192  4284 I Babel_SMS: MmsConfig.loadMmsSettings
03-17 07:10:41.209  4192  4284 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
03-17 07:10:41.209  4192  4284 I Babel_SMS: MmsConfig.loadFromDatabase
,03-17 07:10:41.209  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.209  3716  3746 I GFX construct_block_size_descriptor_2d second part: took 2.650209ms for 0*0 texture 0
,03-17 07:10:41.219  1019  3273 I ActivityManager: Process com.sec.android.app.sns3 (pid 4165)(adj 0) has died(39,1110)
,03-17 07:10:41.219  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.219  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.219  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.219  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.219  3716  3746 I GFX generate_partition_tables: took 8.799322ms for 0*0 texture 0
,03-17 07:10:41.219  3716  3746 I GFX raster: took 12.395312ms for 96*96 texture 0
03-17 07:10:41.219  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ac098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb767c628 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.229  3716  3746 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519,
,03-17 07:10:41.239  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:41.239  4287  4287 I libpersona: KNOX_SDCARD checking this for 10034
03-17 07:10:41.239  3716  3746 I GFX raster: took 0.659011ms for 96*96 texture 0
03-17 07:10:41.239  4287  4287 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:41.239  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb70dd888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb74c5220 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:41.239  4287  4287 E Zygote  : MountEmulatedStorage()
03-17 07:10:41.239  4287  4287 E Zygote  : v2
,03-17 07:10:41.249  4287  4287 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:41.249  4287  4287 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 07:10:41.249  3716  3746 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-17 07:10:41.249  1019  1044 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4287 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,03-17 07:10:41.249  4287  4287 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:41.259  1811  1811 I GCoreUlr: DispatchingService.onDestroy()
,03-17 07:10:41.269  1811  1811 I GCoreUlr: Unbound from all location providers
,03-17 07:10:41.279  4287  4287 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:41.279  4287  4287 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:41.279  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.279  3716  3746 I GFX raster: took 0.660729ms for 96*96 texture 0
,03-17 07:10:41.279  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ab1c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74acbb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.289  4192  4284 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-17 07:10:41.289  4192  4284 I Babel_SMS: MmsConfig.loadFromResources
,03-17 07:10:41.289  4192  4284 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,03-17 07:10:41.289  4192  4284 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,03-17 07:10:41.299  3716  3746 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:41.309  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.309  3716  3746 I GFX raster: took 0.701875ms for 96*96 texture 0
,03-17 07:10:41.309  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cd478 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb767c628 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.319   286   286 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,03-17 07:10:41.319   286   286 W QCamera2Factory: getCameraInfo: X
,03-17 07:10:41.319  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:41.319   286   711 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,03-17 07:10:41.319   286   711 W QCamera2Factory: getCameraInfo: X
,03-17 07:10:41.329  1019  1230 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
03-17 07:10:41.329  1019  1230 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.329  1019  1230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:41.329  1019  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 07:10:41.359  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.359  3716  3746 I GFX raster: took 0.714063ms for 96*96 texture 0
03-17 07:10:41.359  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74c9430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb748a198 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.359  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.359  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.369  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.369  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.369  3716  3746 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
,03-17 07:10:41.379  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen,
03-17 07:10:41.379  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-17 07:10:41.379  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:41.379  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:41.379  3716  3746 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:41.379  3716  3746 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:41.379  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
03-17 07:10:41.379  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.379  3716  3746 I GFX raster: took 0.681562ms for 96*96 texture 0
03-17 07:10:41.379  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb79d31f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74cd6a0 counterpartCT=4 counterpartW=96 counterparth=96,
,03-17 07:10:41.379  4303  4303 E Zygote  : MountEmulatedStorage(),
03-17 07:10:41.379  4303  4303 E Zygote  : v2
,03-17 07:10:41.389  4303  4303 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:41.389  3716  3746 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
03-17 07:10:41.389  1019  1384 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4303 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:41.389  1019  1384 I ActivityManager: Killing 3566:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31,
03-17 07:10:41.389  4303  4303 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:41.389  4303  4303 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 07:10:41.389  4303  4303 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 07:10:41.399  4303  4303 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:41.419  4303  4303 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:41.419  4303  4303 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:41.429  4192  4192 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 07:10:41.429  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:41.429  3716  3746 I GFX raster: took 0.629062ms for 96*96 texture 0
03-17 07:10:41.439  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ac098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb74c5220 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:41.439  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:41.439  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:41.439  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:41.439  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:41.439  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:41.439  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:41.449  3716  3746 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:41.459  4192  4192 I Babel_Crash: startup - clean
,03-17 07:10:41.459  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.459  3716  3746 I GFX raster: took 0.635104ms for 96*96 texture 0
03-17 07:10:41.459  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb70dd888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb74c8d60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.469  3716  3746 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:41.479  4192  4318 I Babel   : deleted: false for 0
,03-17 07:10:41.479  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.479  3716  3746 I GFX raster: took 0.763334ms for 96*96 texture 0
03-17 07:10:41.479  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ab1c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7471bc0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.489  3716  3746 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:41.499  3946  4077 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-17 07:10:41.499  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.499  3716  3746 I GFX raster: took 0.739323ms for 96*96 texture 0
03-17 07:10:41.499  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cd478 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c8d60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.509  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:41.509  1019  1751 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:41.519  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.519  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:41.519  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,03-17 07:10:41.519  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.519  3716  3746 I GFX raster: took 0.725105ms for 96*96 texture 0
03-17 07:10:41.519  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74c9430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb71fd3b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.529  4303  4303 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-17 07:10:41.529  4303  4303 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-17 07:10:41.529  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3566/cgroup.procs: No such file or directory
,03-17 07:10:41.529  4303  4321 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-17 07:10:41.529  3716  3746 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
03-17 07:10:41.529  4303  4321 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-17 07:10:41.539  4303  4303 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-17 07:10:41.539  4303  4303 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 07:10:41.539  4303  4303 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-17 07:10:41.549  4303  4321 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
03-17 07:10:41.549  4303  4303 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-17 07:10:41.549  4303  4303 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-17 07:10:41.549  4303  4303 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,03-17 07:10:41.549  4303  4303 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 07:10:41.549  4303  4303 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 07:10:41.559  4303  4303 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-17 07:10:41.559  4303  4303 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 07:10:41.559  4303  4303 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-17 07:10:41.559  4303  4303 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 07:10:41.569  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-17 07:10:41.569  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-17 07:10:41.569  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-17 07:10:41.569  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-17 07:10:41.569  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:41.569  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:41.569  3716  3746 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:41.569  3716  3746 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:41.569  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:41.569  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.569  3716  3746 I GFX raster: took 0.703334ms for 96*96 texture 0
03-17 07:10:41.569  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb79d31f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c8d60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.589  3716  3746 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:41.589  4303  4303 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-17 07:10:41.589  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.589  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.589  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.589  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.599  1019  2871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-17 07:10:41.609  4325  4325 E Zygote  : MountEmulatedStorage(),
03-17 07:10:41.609  4325  4325 E Zygote  : v2
03-17 07:10:41.609  4325  4325 I libpersona: KNOX_SDCARD checking this for 10041
03-17 07:10:41.609  4325  4325 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:41.609  4325  4325 I libpersona: KNOX_SDCARD not a persona,
03-17 07:10:41.609  4325  4325 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 07:10:41.619  4325  4325 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 07:10:41.619  1019  4038 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4325 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:41.619  1019  4038 I ActivityManager: Killing 3622:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,03-17 07:10:41.629  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-17 07:10:41.629  3716  3746 I GFX raster: took 0.647292ms for 96*96 texture 0
03-17 07:10:41.629  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ac098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb767cca0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.639  4325  4325 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:41.639  4325  4325 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:41.639  4303  4321 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 07:10:41.639  4303  4321 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 07:10:41.649  3716  3746 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:41.649  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-17 07:10:41.669  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.669  3716  3746 I GFX raster: took 0.634948ms for 96*96 texture 0
03-17 07:10:41.669  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb70dd888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7471bc0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.669  3716  3746 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:41.679  4303  4321 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 07:10:41.679  4303  4321 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-17 07:10:41.689  4303  4321 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-17 07:10:41.699  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.699  4192  4192 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
03-17 07:10:41.699  3716  3746 I GFX raster: took 0.628594ms for 96*96 texture 0
03-17 07:10:41.699  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ab1c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb71fd3b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.709  4192  4192 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 07:10:41.709  4192  4192 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 07:10:41.709  4303  4321 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 07:10:41.709  3716  3746 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:41.709  4192  4192 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 07:10:41.709  4192  4192 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 07:10:41.719  4192  4192 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-17 07:10:41.719  4192  4192 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 07:10:41.719  4192  4192 W AudioCapabilities: Unsupported mime audio/qcelp
03-17 07:10:41.719  1019  1043 W libprocessgroup: failed to open /acct/uid_10069/pid_3622/cgroup.procs: No such file or directory
,03-17 07:10:41.719  4303  4321 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 07:10:41.719  4192  4192 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 07:10:41.729  4303  4321 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 07:10:41.729  4303  4321 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-17 07:10:41.729  4303  4322 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 07:10:41.739  4303  4321 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 07:10:41.739  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.739  3716  3746 I GFX raster: took 0.661459ms for 96*96 texture 0
03-17 07:10:41.739  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cd478 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c8d60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.739  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:41.749  4303  4321 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/18/13:15:33
,03-17 07:10:41.749  4303  4321 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/07:10:41
,03-17 07:10:41.749  4192  4192 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 07:10:41.749  4303  4321 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-17 07:10:41.749  4303  4322 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 07:10:41.749  4303  4321 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-17 07:10:41.749  4192  4192 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 07:10:41.759  4303  4322 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 07:10:41.759  4303  4322 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 07:10:41.759  4303  4322 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 07:10:41.759  4325  4325 I SA      : [SSP] onCreated
,03-17 07:10:41.769  4303  4322 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 07:10:41.769  4303  4322 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 07:10:41.769  4303  4322 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-17 07:10:41.769  4303  4322 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 07:10:41.769  4303  4322 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 07:10:41.769  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.769  3716  3746 I GFX raster: took 0.887812ms for 96*96 texture 0
03-17 07:10:41.769  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74c9430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c8d60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.779  3716  3746 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:41.779  4192  4192 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-17 07:10:41.789  4192  4192 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 07:10:41.789  4192  4192 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 07:10:41.789  4303  4322 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 07:10:41.789  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-17 07:10:41.789  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:41.789  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:41.789  3716  3746 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:41.799  3716  3746 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:41.799  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:41.799  4192  4192 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-17 07:10:41.799  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.799  3716  3746 I GFX raster: took 0.851406ms for 96*96 texture 0
03-17 07:10:41.799  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb79d31f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb767cca0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.799  4192  4192 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-17 07:10:41.799  4192  4192 W VideoCapabilities: Unsupported mime video/mp43
,03-17 07:10:41.809  4192  4192 W VideoCapabilities: Unsupported mime video/sorenson
,03-17 07:10:41.809  4325  4325 I SA      : [TPM] There is no property file
,03-17 07:10:41.809  4325  4325 I SA      : [SCU] isHaveSA() - false
,03-17 07:10:41.809  4325  4325 I SA      : [TPM] getModelProperty : null
03-17 07:10:41.809  3716  3746 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
03-17 07:10:41.809  4325  4325 I SA      : [TPM] getCSCProperty : null
,03-17 07:10:41.809  4325  4325 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-17 07:10:41.809  4325  4325 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-17 07:10:41.809  4325  4325 I SA      : [DM] TFT FEATURE: false
,03-17 07:10:41.819  4192  4192 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-17 07:10:41.819  4303  4322 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-17 07:10:41.819  4325  4325 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
03-17 07:10:41.819  4325  4325 I SA      : [DM] init START
,03-17 07:10:41.819  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.819  3716  3746 I GFX raster: took 0.642814ms for 96*96 texture 0
,03-17 07:10:41.819  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ac098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb71fd3b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.829  3716  3746 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:41.839  4325  4325 I SA      : [DM] This device is not a Vodafone
,03-17 07:10:41.839  4325  4325 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,03-17 07:10:41.839  4325  4325 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,03-17 07:10:41.839  4325  4325 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,03-17 07:10:41.849  4325  4325 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
03-17 07:10:41.849  4325  4325 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,03-17 07:10:41.849  4325  4325 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
03-17 07:10:41.849  4325  4325 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
03-17 07:10:41.849  4325  4325 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-17 07:10:41.849  4325  4325 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,03-17 07:10:41.849  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:41.849  4325  4325 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,03-17 07:10:41.849  4325  4325 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,03-17 07:10:41.849  3716  3746 I GFX raster: took 0.679740ms for 96*96 texture 0
03-17 07:10:41.849  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb70dd888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb74c5010 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:41.849  4325  4325 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
03-17 07:10:41.849  4325  4325 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,03-17 07:10:41.849  4325  4325 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,03-17 07:10:41.849  4325  4325 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,03-17 07:10:41.849  4325  4325 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,03-17 07:10:41.859  3716  3746 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:41.869  4325  4325 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75),
03-17 07:10:41.869  4325  4325 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-17 07:10:41.869  4325  4325 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-17 07:10:41.869  4325  4325 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,03-17 07:10:41.869  4325  4325 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
03-17 07:10:41.869  4325  4325 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,03-17 07:10:41.869  4325  4325 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,03-17 07:10:41.869  4325  4325 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,03-17 07:10:41.869  4325  4325 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,03-17 07:10:41.879  4192  4192 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 07:10:41.879  4325  4325 I SA      : [SCU] isHaveSA() - false
03-17 07:10:41.879  4325  4325 I SA      : support phone number id : false
03-17 07:10:41.879  4325  4325 I SA      : [DM] Supports Ref Jpn : true
,03-17 07:10:41.879  4325  4325 I SA      : [DM] init END
,03-17 07:10:41.889  4325  4325 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
03-17 07:10:41.889  4325  4325 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-17 07:10:41.889  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.889  3716  3746 I GFX raster: took 0.640208ms for 96*96 texture 0
03-17 07:10:41.889  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ab1c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb767c628 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.889  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,03-17 07:10:41.889  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.889  1019  1031 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 07:10:41.889  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-17 07:10:41.899  4325  4325 I SA      : [OR] onReceive END
,03-17 07:10:41.909  3716  3746 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:41.919  4325  4325 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 07:10:41.919  4325  4325 I SA      : [ODM] queryOpenData(key= GEO_IP )
03-17 07:10:41.919  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.929  4325  4325 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-17 07:10:41.929  1019  1751 I art     : Explicit concurrent mark sweep GC freed 32431(2009KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 30MB/45MB, paused 2.796ms total 175.131ms
03-17 07:10:41.929  4325  4325 I SA      : [LBE] REF_JPN : true
03-17 07:10:41.929  4325  4325 I SA      : [BDC] create
,03-17 07:10:41.939  3716  3746 I GFX raster: took 0.700625ms for 96*96 texture 0
03-17 07:10:41.939  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cd478 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7498088 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.939  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:41.959  4303  4321 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 07:10:41.959  4192  4192 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 07:10:41.959  4192  4192 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 07:10:41.969  4192  4192 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 07:10:41.969  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.969  3716  3746 I GFX raster: took 0.908437ms for 96*96 texture 0
,03-17 07:10:41.969  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74c9430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c5220 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:41.969  4325  4325 I SA      : [DBMV2] getEmailID
,03-17 07:10:41.969  4192  4192 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 07:10:41.969  4325  4325 I SA      : [DBMV2] getDataV02ForItems
03-17 07:10:41.969  4325  4325 I SA      : [SSP] query invoked
,03-17 07:10:41.979  4325  4325 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-17 07:10:41.979  4303  4322 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-17 07:10:41.979  4325  4325 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-17 07:10:41.979  4325  4325 I SA      : [BDC] destroy
,03-17 07:10:41.989  1019  1389 I ActivityManager: Killing 3294:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,03-17 07:10:41.989  3716  3746 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:41.999  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
,03-17 07:10:41.999  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:41.999  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:41.999  3716  3746 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:41.999  3716  3746 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-17 07:10:41.999  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:41.999  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:41.999  3716  3746 I GFX raster: took 0.713489ms for 96*96 texture 0
,03-17 07:10:41.999  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb79d31f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74cd6a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.009  3716  3746 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:42.019  4303  4321 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-17 07:10:42.019  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.019  3716  3746 I GFX raster: took 0.788959ms for 96*96 texture 0
03-17 07:10:42.019  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ac098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7471bc0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.019  4192  4192 I vclib   : onServiceConnected
,03-17 07:10:42.029  4192  4192 W Babel   : Attempted to change video mute state without an active call.
03-17 07:10:42.029  4303  4321 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 07:10:42.029  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.029  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.029  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.029  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.029  3716  3746 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:42.049  4303  4322 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 07:10:42.049  4348  4348 E Zygote  : MountEmulatedStorage(),
03-17 07:10:42.049  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.049  3716  3746 I GFX raster: took 0.627760ms for 96*96 texture 0
03-17 07:10:42.049  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb70dd888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb74c5220 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.049  4348  4348 E Zygote  : v2,
,03-17 07:10:42.049  4348  4348 I libpersona: KNOX_SDCARD checking this for 10035,
,03-17 07:10:42.059  4348  4348 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:42.059  4348  4348 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:42.059  3716  3746 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-17 07:10:42.059  4348  4348 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:42.059  4348  4348 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 07:10:42.059  4303  4322 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 07:10:42.069  1019  1384 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4348 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 07:10:42.069  1019  1384 I ActivityManager: Killing 3644:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,03-17 07:10:42.069  1019  1713 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:42.079  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.079  1019  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:42.079  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.089  4348  4348 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:42.089   318   318 I art     : Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 25.854ms
,03-17 07:10:42.089  4348  4348 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:42.099  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.109  3716  3746 I GFX raster: took 0.656823ms for 96*96 texture 0
03-17 07:10:42.109  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ab1c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74cd6a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.109   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 17.357ms
,03-17 07:10:42.109  3716  3746 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:42.129  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:42.129  3716  3746 I GFX raster: took 0.641927ms for 96*96 texture 0
03-17 07:10:42.129  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cd478 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7471bc0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.129   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 17.110ms
,03-17 07:10:42.129  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:42.179  4348  4364 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-17 07:10:42.179  4348  4364 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-17 07:10:42.179  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.179  3716  3746 I GFX raster: took 0.814635ms for 96*96 texture 0
,03-17 07:10:42.179  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74c9430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74c5220 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.189  4348  4348 E SPPClientService: [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
03-17 07:10:42.189  4348  4348 E SPPClientService: [SystemStateMoniter] Current Time : 45563
,03-17 07:10:42.189  3716  3746 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:42.199  4348  4364 D SPPClientService: PushLog.txt file is not deleted.
,03-17 07:10:42.199  4348  4364 D SPPClientService: PushLog.txt file is not deleted.
03-17 07:10:42.199  4348  4364 D SPPClientService: ============PushLog. stop!
,03-17 07:10:42.209  1019  1043 W libprocessgroup: failed to open /acct/uid_10009/pid_3294/cgroup.procs: No such file or directory
,03-17 07:10:42.209  1019  1043 W libprocessgroup: failed to open /acct/uid_10125/pid_3644/cgroup.procs: No such file or directory
,03-17 07:10:42.219  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
03-17 07:10:42.219  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.219  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:42.219  3716  3746 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:42.229  3716  3746 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-17 07:10:42.229  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
03-17 07:10:42.229  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.229  3716  3746 I GFX raster: took 0.755990ms for 96*96 texture 0
03-17 07:10:42.229  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb79d31f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74cd5f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.229  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.229  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.229  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.229  1019  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.239  3716  3746 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:42.249  4366  4366 E Zygote  : MountEmulatedStorage(),
03-17 07:10:42.249  4366  4366 I libpersona: KNOX_SDCARD checking this for 10166
03-17 07:10:42.249  4366  4366 E Zygote  : v2
03-17 07:10:42.249  4366  4366 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:42.249  4366  4366 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:42.249  4366  4366 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:42.249  1019  1715 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4366 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:42.249  1019  1715 I ActivityManager: Killing 3661:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,03-17 07:10:42.249  4366  4366 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:42.259  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.259  3716  3746 I GFX raster: took 0.651771ms for 96*96 texture 0
03-17 07:10:42.259  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ac098 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb74cd6a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.259  3716  3746 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:42.269  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.269  3716  3746 I GFX raster: took 0.623698ms for 96*96 texture 0
03-17 07:10:42.269  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb70dd888 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb74ccfe0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.269  4366  4366 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:42.269  4366  4366 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:42.279  3716  3746 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:42.299  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.299  3716  3746 I GFX raster: took 0.682552ms for 96*96 texture 0
03-17 07:10:42.299  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74ab1c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb74c5220 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.309  3716  3746 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:42.359  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.359  1019  1043 W libprocessgroup: failed to open /acct/uid_10014/pid_3661/cgroup.procs: No such file or directory
,03-17 07:10:42.359  3716  3746 I GFX raster: took 0.828907ms for 96*96 texture 0
,03-17 07:10:42.359  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74cd478 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74cd6a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.369  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:42.389  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.389  3716  3746 I GFX raster: took 0.862240ms for 96*96 texture 0
03-17 07:10:42.389  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb74c9430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb74ccfe0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.399  3716  3746 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
,03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-17 07:10:42.439  3716  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNum,berEditActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
,03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
,03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
,03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource dat,a:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
,03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
,03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
,03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
,03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-17 07:10:42.439  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,03-17 07:10:42.449  1019  3273 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 07:10:42.449  1019  3273 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4301, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,03-17 07:10:42.449  1019  3273 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
03-17 07:10:42.449  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 07:10:42.459  1019  1059 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-17 07:10:42.459  1019  1019 I MotionRecognitionService: Plugged
,03-17 07:10:42.459  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 07:10:42.459  1464  1464 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 07:10:42.459  1464  1464 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 07:10:42.469  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 07:10:42.469  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 07:10:42.479  2682  2682 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 07:10:42.479  2682  2776 D HeadsetStateMachine: Disconnected process message: 10,
,03-17 07:10:42.479  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 07:10:42.479  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 07:10:42.479  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 07:10:42.499  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
,03-17 07:10:42.499  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.499  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:42.499  3716  3746 I AMMetaDataParserService: Resource data:2131165197
,03-17 07:10:42.499  3716  3746 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:42.499  3716  3746 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 07:10:42.499  3716  3746 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:42.499  3716  3746 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:42.499  3716  3746 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,03-17 07:10:42.499  3716  3746 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 07:10:42.499  3716  3746 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:42.499  3716  3746 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:42.509  4366  4381 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 07:10:42.509  3716  3746 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
,03-17 07:10:42.509  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
03-17 07:10:42.509  4366  4381 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 07:10:42.519  3716  3746 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 07:10:42.529  3716  3746 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 07:10:42.549  4366  4381 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 07:10:42.599  4366  4381 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 07:10:42.599  4366  4381 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@329ecf74: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 07:10:42.599  4366  4381 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 07:10:42.609  1695  1695 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,03-17 07:10:42.679  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-17 07:10:42.679  3716  3746 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 07:10:42.709  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 07:10:42.769  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-17 07:10:42.769  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.769  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:42.769  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:42.769  3716  3746 I AMMetaDataParserService: Resource data:2131165197
,03-17 07:10:42.769  3716  3746 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 07:10:42.769  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:42.779  3716  3746 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 07:10:42.789  3716  3746 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 07:10:42.819  3716  3746 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 07:10:42.849  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 07:10:42.859   291   291 E SMD     : DCD OFF
,03-17 07:10:42.889  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
,03-17 07:10:42.889  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-17 07:10:42.889  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:42.889  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
,03-17 07:10:42.889  3716  3746 I AMMetaDataParserService: Resource data:2131165197
,03-17 07:10:42.889  3716  3746 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 07:10:42.889  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:42.899  3716  3746 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 07:10:42.909  3716  3746 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 07:10:42.949  3716  3746 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 07:10:42.949  4391  4391 I dex2oat : ----------------------------------------------------
,03-17 07:10:42.959  4391  4391 I dex2oat : <SS>: S T A R T I N G . . .
,03-17 07:10:42.959  4391  4391 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 07:10:42.959  4391  4391 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads377952521.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads377952521.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 07:10:42.969  1019  1241 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:42.969  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.969  3716  3746 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 07:10:42.969  1019  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
,03-17 07:10:42.969  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-17 07:10:42.979  3716  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-17 07:10:42.979  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-17 07:10:42.989  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-17 07:10:42.989  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.989  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-17 07:10:42.989  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 07:10:42.989  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-17 07:10:42.989  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:42.989  3716  3746 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:42.999  3716  3746 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 07:10:42.999  3716  3746 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:42.999  3716  3746 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 07:10:42.999  3716  3746 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 07:10:42.999  3716  3746 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:42.999  3716  3746 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-17 07:10:42.999  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:42.999  4366  4366 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 07:10:43.009  3716  3746 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-17 07:10:43.019  3716  3746 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-17 07:10:43.029  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,03-17 07:10:43.039  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
,03-17 07:10:43.039  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-17 07:10:43.039  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,03-17 07:10:43.039  3716  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 07:10:43.049  4391  4391 I dex2oat : dex2oat took 97.426ms (threads: 4)
,03-17 07:10:43.069   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 07:10:43.069   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:43.069  4366  4366 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 07:10:43.119  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-17 07:10:43.119  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.119  3716  3746 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:43.119  3716  3746 I AMMetaDataParserService: Resource data:2131165220
,03-17 07:10:43.129  3716  3746 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 07:10:43.129  3716  3746 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:43.129  3716  3746 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:43.129  3716  3746 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:43.129  3716  3746 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:43.129  3716  3746 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:43.129  3716  3746 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-17 07:10:43.129  3716  3746 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:43.129  1019  1751 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:43.129  1019  1751 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:43.129  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-17 07:10:43.129  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.139  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:43.139  3716  3746 I GFX raster: took 0.772968ms for 96*96 texture 0
03-17 07:10:43.139  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7bc7a70 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7bc77a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.149  3716  3746 I AMMetaDataParserService: Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,03-17 07:10:43.159  3716  3746 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:43.169  3716  3746 I GFX raster: took 0.611771ms for 96*96 texture 0
,03-17 07:10:43.169  3716  3746 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7bc78c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7bdab98 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.169  1019  1230 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.169  1019  1230 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.169  1019  1230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.169  1019  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:43.179  3716  3746 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password,
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop fo,r running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.androi,d.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity,
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE,
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED,
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED,
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity,
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.229  1019  1715 I ActivityManager: Killing 3698:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-17 07:10:43.189  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
,03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  371,6  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
,03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
,03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
,03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
,03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  37,46 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.set,tings.bluetooth.BluetoothPermissionActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.199  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.279  1019  1043 W libprocessgroup: failed to open /acct/uid_10131/pid_3698/cgroup.procs: No such file or directory
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: g,etResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716,  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-17 07:10:43.209  3716  3746 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
,03-17 07:10:43.359   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 07:10:43.359   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:43.359  4366  4366 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 07:10:43.359   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 07:10:43.359   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:43.359  4366  4366 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 07:10:43.369   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 07:10:43.369   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:43.369  4366  4366 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 07:10:43.369  1019  1230 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:43.379  1019  1230 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.379  1019  1230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.379  1019  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.379  4366  4366 W InstanceID/Rpc: Found 10012
,03-17 07:10:43.429   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 07:10:43.429   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:43.429  4366  4366 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 07:10:43.449  1019  3273 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.449  1019  3273 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:43.449  1019  3273 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.449  1019  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:43.459  1019  1100 V AlarmManager: waitForAlarm result :4
,03-17 07:10:43.459  1019  1100 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.499  1970  4431 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 28 ms
,03-17 07:10:43.519  1019  4038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.519  1019  4038 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.519  1019  4038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.519  1019  4038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:43.559  1019  3272 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.559  1019  3272 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.559  1019  3272 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.559  1019  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:43.559  1019  3273 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.559  1019  3273 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
03-17 07:10:43.559  1019  3273 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.559  1019  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:43.569  4366  4445 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
,03-17 07:10:43.569  4366  4445 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 07:10:43.569  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.579  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.579  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.579  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:43.579  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.579  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.579  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.579  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.579  4366  4445 I System.out: Thread-728(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 07:10:43.589  4366  4445 I System.out: Thread-728(ApacheHTTPLog):isSBSettingEnabled false
,03-17 07:10:43.589  4366  4445 I System.out: Thread-728(ApacheHTTPLog):isShipBuild true
,03-17 07:10:43.589  4366  4445 I System.out: Thread-728(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 07:10:43.589  4366  4445 I System.out: Thread-728(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 07:10:43.599  1019  1031 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4451 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:43.599  4451  4451 E Zygote  : MountEmulatedStorage()
03-17 07:10:43.599  4451  4451 I libpersona: KNOX_SDCARD checking this for 10101
03-17 07:10:43.599  4451  4451 E Zygote  : v2
03-17 07:10:43.599  4451  4451 I libpersona: KNOX_SDCARD not a persona,
03-17 07:10:43.599   281   998 D EnterpriseController: uids 10166
03-17 07:10:43.599   281   998 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 07:10:43.599   281   998 D Netd    : getNetworkForDns: using netid 502 for uid 10166
03-17 07:10:43.599  4451  4451 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:43.599  4451  4451 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:43.599  4451  4451 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 07:10:43.609  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.609  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.609  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.609  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:43.619  4451  4451 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:43.619  4451  4451 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.639  1019  1032 I ActivityManager: Killing 2967:com.test.thalitest/u0a174 (adj 15): empty #31
,03-17 07:10:43.679  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-17 07:10:43.689  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{17c5f8dd u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-17 07:10:43.759  1019  1043 W libprocessgroup: failed to open /acct/uid_10174/pid_2967/cgroup.procs: No such file or directory
,03-17 07:10:43.879  1019  1751 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:43.879  1019  1751 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:43.969  4451  4471 I Gmail   : getAccountsCursor
,03-17 07:10:43.969  1019  1751 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.979  4451  4451 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 07:10:43.979  1695  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:43.999  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.999  1019  1032 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 07:10:44.009  1019  1751 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:44.019  1019  1751 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:44.019  4366  4445 I System.out: Thread-728 calls detatch()
,03-17 07:10:44.019  4451  4477 I Gmail   : Observing account changes for notifications
,03-17 07:10:44.019  1019  4038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.019  1019  4038 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:44.019  1019  4038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:44.019  1019  4038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 07:10:44.029  1019  1713 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.029  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:44.029  1019  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:44.029  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 07:10:44.039  1019  1389 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:44.039  1019  1389 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:44.059  4451  4481 E Gmail   : Error finding the version of the Email provider.....
03-17 07:10:44.059  4451  4481 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 07:10:44.059  4451  4481 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 07:10:44.059  4451  4481 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
03-17 07:10:44.059  4451  4481 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
03-17 07:10:44.059  4451  4481 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 07:10:44.059  4451  4481 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:44.059  4451  4481 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:44.059  4451  4481 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 07:10:44.059  1019  4038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.059  4451  4481 W EmailMigration: We do not support migrating this version of the Email provider.
03-17 07:10:44.059  1019  4038 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:44.059  1019  4038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:44.059  1019  4038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 07:10:44.059  4451  4483 I Gmail   : getAccountsCursor
,03-17 07:10:44.059  1019  1713 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.069  1019  1528 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.069  1019  1528 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:44.069  1019  1528 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:44.069  1019  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 07:10:44.069  1695  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:44.069  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.069  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.069  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.069  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:44.089  4486  4486 E Zygote  : MountEmulatedStorage()
,03-17 07:10:44.089  4486  4486 E Zygote  : v2
03-17 07:10:44.089  4486  4486 I libpersona: KNOX_SDCARD checking this for 10092
,03-17 07:10:44.089  4486  4486 I libpersona: KNOX_SDCARD not a persona,
,03-17 07:10:44.089  4486  4486 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:44.089  1019  1367 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=4486 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:44.089  4486  4486 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:44.099  1019  1751 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
03-17 07:10:44.099  4486  4486 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 07:10:44.099  1019  4037 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:44.099  1019  4037 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:44.109  1019  1554 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:44.109  1019  1554 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:44.109  1019  3273 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.119  1695  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:44.119  4451  4451 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@397eb5b2 that was originally bound here
03-17 07:10:44.119  4451  4451 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@397eb5b2 that was originally bound here
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at com.android.emailcommon.service.ak.a(SourceFile:181)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at com.android.emailcommon.service.ak.e(SourceFile:224)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:177)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:198)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:142)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:44.119  4451  4451 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 07:10:44.119  1019  1715 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@38e45358
,03-17 07:10:44.119  4486  4486 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:44.119  4486  4486 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:44.169  4451  4484 E SQLiteLog: (283) recovered 62 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 07:10:44.309  4451  4484 E File    : fail readDirectory() errno=2
,03-17 07:10:44.319  4451  4499 I Gmail   : notifyAccountChanged
,03-17 07:10:44.329  4451  4506 I Gmail   : getAccountsCursor
,03-17 07:10:44.329  1019  1241 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.339  4451  4499 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 07:10:44.339  1695  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:44.359  4451  4499 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 07:10:44.359  1019  3272 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 07:10:44.359  1019  3272 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:44.359  1019  3272 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:44.359  1019  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 07:10:44.369  1019  1384 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.369  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:44.369  1019  1384 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-17 07:10:44.379  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 07:10:44.379  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:44.379  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:44.379  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.379  1019  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:44.389  4451  4499 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 07:10:44.389  4451  4499 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 07:10:44.389  4507  4507 E Zygote  : MountEmulatedStorage()
,03-17 07:10:44.389  4507  4507 E Zygote  : v2
03-17 07:10:44.389  4507  4507 I libpersona: KNOX_SDCARD checking this for 10092
03-17 07:10:44.399  4507  4507 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:44.399  4507  4507 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:44.399  1019  1384 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=4507 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 07:10:44.399  1019  1554 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:44.399  4507  4507 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:44.399  4451  4484 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
03-17 07:10:44.399  4507  4507 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
03-17 07:10:44.399  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:44.399  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:44.399  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,03-17 07:10:44.419  4451  4484 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,03-17 07:10:44.429  4507  4507 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:44.429  4507  4507 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:44.439  4451  4484 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
,03-17 07:10:44.439  1019  1052 D PowerManagerService: [s] UserActivityState : 1 -> 2
03-17 07:10:44.439  1019  1052 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-17 07:10:44.439  1019  1052 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 07:10:44.439  1019  1052 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 07:10:44.439  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:44.439  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:44.439  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:44.439  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:44.439  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:44.439  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:44.449  1019  1163 D lights  : lcd : 22 +
,03-17 07:10:44.449  1019  1713 I ActivityManager: Killing 3257:com.google.android.gms:car/u0a12 (adj 15): empty #31
,03-17 07:10:44.459  1019  1052 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-17 07:10:44.459  1019  1052 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 07:10:44.459  1019  1163 D lights  : lcd : 22 -
,03-17 07:10:44.459  1019  1163 D lights  : lcd : 19 +
,03-17 07:10:44.459  1019  1241 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:44.469  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:44.469  1019  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:44.469  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:44.479  1019  1163 D lights  : lcd : 19 -
,03-17 07:10:44.479  1019  1052 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-17 07:10:44.479  1019  1052 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 07:10:44.499  4486  4486 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 07:10:44.509  4486  4486 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-17 07:10:44.509  1019  1043 W libprocessgroup: failed to open /acct/uid_10012/pid_3257/cgroup.procs: No such file or directory
,03-17 07:10:44.529  4451  4471 I Gmail   : getAccountsCursor
,03-17 07:10:44.529  1019  4037 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.529  1695  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:44.549  1019  1751 I ActivityManager: Killing 3305:com.android.vending/u0a28 (adj 15): empty #31
,03-17 07:10:44.569  4486  4486 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_9807ade0d39f04306c7e28de04204d1f53ae2228_armv7a
,03-17 07:10:44.579  4486  4486 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 07:10:44.579  4486  4486 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_b492ffd532b8b6365d97439f842c164c3c90fd4e_armv7a
,03-17 07:10:44.579  4486  4486 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_e16babc055b114839529ea959e1ce06f2a593b63_armv7a
,03-17 07:10:44.659  1019  1043 W libprocessgroup: failed to open /acct/uid_10028/pid_3305/cgroup.procs: No such file or directory
,03-17 07:10:44.679  4486  4486 I libDropboxSync.so: Setting global terminate handler.
,03-17 07:10:44.679  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,03-17 07:10:44.709  4486  4486 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_aa417f8c60b792b71fc3cef90fc4bb8ddba4ea56_armv7a
,03-17 07:10:44.749  4486  4486 I com.dropbox.sync.android.L: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 07:10:44.769  4486  4486 I com.dropbox.sync.android.L: Removing unclaimed file/directory in cache: "local-dbapp_noauth"
,03-17 07:10:44.779  4486  4486 I com.dropbox.sync.android.bf: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/3.0.2 DropboxSync/3.1+dev (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-17 07:10:44.789  4486  4486 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:44.789  4486  4486 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:44.809  4486  4486 I com.dropbox.sync.android.aS: Created NativeDbappNoAuthClientProvider
,03-17 07:10:44.819  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.sync.android.DbxSyncService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.819  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:44.819  1019  1367 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 07:10:44.819  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 07:10:44.849  4486  4529 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
03-17 07:10:44.849  4486  4529 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 07:10:44.849  4486  4529 I System.out: (HTTPLog)-Static: isShipBuild true
03-17 07:10:44.849  4486  4529 I System.out: (HTTPLog)-Thread-687-411819165: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 07:10:44.849  4486  4529 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 07:10:44.849   281   998 D EnterpriseController: uids 10092
03-17 07:10:44.849   281   998 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 07:10:44.849   281   998 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-17 07:10:44.919  4486  4529 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 07:10:44.949  4486  4486 I com.dropbox.sync.android.DbxSyncService: DbxSyncService starting.
,03-17 07:10:44.959  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:44.959  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.959  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:44.959  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:44.969  4541  4541 E Zygote  : MountEmulatedStorage()
,03-17 07:10:44.969  1019  1230 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4541 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-17 07:10:44.969  4541  4541 E Zygote  : v2
03-17 07:10:44.969  4541  4541 I libpersona: KNOX_SDCARD checking this for 10057,
,03-17 07:10:44.969  4541  4541 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:44.969  4541  4541 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:44.979  1019  3272 I ActivityManager: Killing 3716:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-17 07:10:44.979  4541  4541 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:44.979  4541  4541 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:45.009  4541  4541 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:45.009  4541  4541 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:45.049  4303  4321 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:45.069  4303  4321 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 07:10:45.079  4303  4321 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 07:10:45.079  4303  4321 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 07:10:45.089  4303  4321 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 07:10:45.089  4303  4321 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 07:10:45.089  4303  4321 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 07:10:45.089  4303  4321 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 07:10:45.129  4486  4529 I com.dropbox.sync.android.aF: Created new socket: SSL socket over Socket[address=api.dropbox.com/108.160.172.205,port=443,localPort=46954]
,03-17 07:10:45.189  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3716/cgroup.procs: No such file or directory
,03-17 07:10:45.239  1019  1554 D LocationManagerService: getProviders()=[passive]
,03-17 07:10:45.309  1019  4038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-17 07:10:45.309  1019  4038 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.309  1019  4038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.309  1019  4038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 07:10:45.419  1019  3272 I splitIntent: Queue : backgroundsplit_2 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 07:10:45.429  1019  3272 I ActivityManager: Killing 3785:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,03-17 07:10:45.439  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.439  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:45.439  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:45.439  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.439  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.439  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:45.439  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.449  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.449  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:45.449  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.449  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.449  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:45.599  1019  1389 I art     : Explicit concurrent mark sweep GC freed 28354(1732KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 30MB/45MB, paused 2.403ms total 151.259ms
,03-17 07:10:45.599  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 07:10:45.599  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.599  1019  1554 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:45.599  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 07:10:45.609  2604  2604 I Hs20UtilService: Starting #3
,03-17 07:10:45.609  2604  2619 I Hs20UtilService: Message received 5011
,03-17 07:10:45.609  4078  4078 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 07:10:45.609  4078  4078 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 07:10:45.609  4078  4078 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 07:10:45.609  4078  4078 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-17 07:10:45.619  1019  1133 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 07:10:45.619  1019  1133 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 07:10:45.619  1019  1133 E WifiNative-wlan0: invaild command id : 215
,03-17 07:10:45.619  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.619  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.619  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 07:10:45.629  1501  4577 D SIP     : [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,03-17 07:10:45.639  1353  1353 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,03-17 07:10:45.639  1353  1353 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 07:10:45.639  1501  4577 E File    : fail readDirectory() errno=2
,03-17 07:10:45.639  1353  1353 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 07:10:45.639  1353  1353 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-17 07:10:45.639  1353  1353 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 07:10:45.639  1353  1353 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 07:10:45.639  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.639  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.639  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.639  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.659  4579  4579 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:45.659  4579  4579 E Zygote  : v2,
03-17 07:10:45.659  4579  4579 I libpersona: KNOX_SDCARD checking this for 10068
03-17 07:10:45.659  4579  4579 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:45.659  1019  1367 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4579 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 07:10:45.659  4579  4579 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:45.659  1019  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:45.659  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.659  4579  4579 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:45.659  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.669  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.669  4579  4579 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:45.679  1019  1043 W libprocessgroup: failed to open /acct/uid_10022/pid_3785/cgroup.procs: No such file or directory
,03-17 07:10:45.679  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-17 07:10:45.689  4579  4579 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:45.689  4579  4579 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:45.709  4579  4579 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 07:10:45.719  4579  4579 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-17 07:10:45.729  4579  4579 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,03-17 07:10:45.769  4579  4579 D FileShare-Client: Outbound.stopDelayTimer - 
,03-17 07:10:45.769  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.769  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.769  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.769  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.779  4597  4597 E Zygote  : MountEmulatedStorage(),
03-17 07:10:45.779  4597  4597 I libpersona: KNOX_SDCARD checking this for 10069
03-17 07:10:45.779  4597  4597 E Zygote  : v2
,03-17 07:10:45.779  4597  4597 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:45.779  4597  4597 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:45.779  1019  1241 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4597 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:45.789  4597  4597 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:45.789  1019  1241 I ActivityManager: Killing 3819:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-17 07:10:45.789  4597  4597 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:45.789  1019  4038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 07:10:45.789  1019  4038 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:45.789  1019  4038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.789  1019  4038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms,
,03-17 07:10:45.799  4597  4597 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:45.799  4597  4597 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:45.799  1019  3272 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:45.809  1019  3272 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.809  1019  3272 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:45.809  1019  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.829  1695  4126 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,03-17 07:10:45.829  1695  4126 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-17 07:10:45.829  1695  4126 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 07:10:45.829  1695  4126 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-17 07:10:45.829  4597  4597 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-17 07:10:45.839  1019  1528 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.839  1019  1528 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:45.839  1019  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-17 07:10:45.839  1019  1528 I ActivityManager: Killing 3791:com.android.calendar/u0a135 (adj 15): empty #31
,03-17 07:10:45.839  1695  4126 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:45.839  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.839  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.839  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:45.849  1019  1751 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-17 07:10:45.849  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.849  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.849  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.859  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.859  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.859  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:45.859  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.859  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.859  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:45.869  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.869  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:45.869  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-17 07:10:45.869   291   291 E SMD     : DCD OFF
,03-17 07:10:45.869  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.869  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.869  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:45.879  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.879  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.879  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:45.879  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.879  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:45.879  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:45.889  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.889  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:45.889  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:45.889  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.889  1019  1019 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.889  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.889  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 07:10:45.889  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.889  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.889  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.899  1019  1554 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 07:10:45.899  1019  1554 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-17 07:10:45.899  1019  1554 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
,03-17 07:10:45.899  1019  1554 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!,
,03-17 07:10:45.899  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.899  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.899  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.899  1695  4612 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 07:10:45.909  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.909  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.909  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.909  1695  1695 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 07:10:45.909  1019  1032 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,03-17 07:10:45.909  1019  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-17 07:10:45.909  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.909  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.919  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.919  1019  1019 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 07:10:45.919  4541  4570 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at com.google.android.gms.auth.b.c(Unknown Source)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
03-17 07:10:45.919  4541  4570 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,03-17 07:10:45.919  4541  4565 E VelvetNetworkClient: Failed to get auth token
,03-17 07:10:45.929  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.929  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.929  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.929  1191  1191 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-17 07:10:45.929  1970  1970 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 07:10:45.929  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 07:10:45.929  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
03-17 07:10:45.929  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
03-17 07:10:45.929  1191  1191 I PhoneStatusBar: Icon Only
03-17 07:10:45.929  1191  1191 I StatusBar: Icon Only
,03-17 07:10:45.929  1191  1191 D PanelView: There is/are notification(s) 
03-17 07:10:45.929  1191  1191 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 07:10:45.929  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.929  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.929  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.929  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
03-17 07:10:45.929  1191  1191 I PhoneStatusBar: Icon Only
03-17 07:10:45.929  1191  1191 I StatusBar: Icon Only
,03-17 07:10:45.929  1191  1191 D PanelView: There is/are notification(s) 
03-17 07:10:45.929  1191  1191 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 07:10:45.939  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.939  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.939  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,03-17 07:10:45.939  1019  3273 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.939  1019  3273 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:45.939  1019  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.949  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.949  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.949  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.949  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.949  1019  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:45.949  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.949  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.959  1019  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:45.959  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.959  1019  4038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
03-17 07:10:45.959  1019  4038 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.959  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3819/cgroup.procs: No such file or directory
03-17 07:10:45.959  1019  4038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.959  1019  1043 W libprocessgroup: failed to open /acct/uid_10135/pid_3791/cgroup.procs: No such file or directory
,03-17 07:10:45.959  1019  4038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.969  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.969  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:45.969  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.969  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:45.979  1019  4038 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4614 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-17 07:10:45.979  4614  4614 E Zygote  : MountEmulatedStorage()
03-17 07:10:45.979  4614  4614 I libpersona: KNOX_SDCARD checking this for 10012
03-17 07:10:45.979  4614  4614 E Zygote  : v2
03-17 07:10:45.979  4614  4614 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:45.979  4614  4614 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:45.979  1019  4037 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.979  1019  4037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:45.979  1019  4037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.989  4614  4614 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:45.989  4614  4614 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:45.989  1019  1528 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:45.989  1019  1528 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.989  1019  1528 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.989  1019  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.999  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.999  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.999  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.999  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:45.999  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.999  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.999  1191  1191 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-17 07:10:45.999  1019  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 07:10:46.009  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.009  1019  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:46.009  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.009  1970  4623 D LocationInitializer: Restart initialization of location
,03-17 07:10:46.009  4614  4614 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:46.009  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.009  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.009  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-17 07:10:46.009  4614  4614 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:46.019  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.019  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.019  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.019  1019  1751 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 07:10:46.019  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.019  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:46.019  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.029  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.029  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.029  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.029  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.029  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.029  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.029  4614  4614 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 07:10:46.029  4614  4614 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 07:10:46.039  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.039  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.039  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.039  1019  4037 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:46.039  1019  4037 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.039  1019  4037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:46.039  1019  4037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.049  1019  1019 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.049  1019  1019 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.049  1019  1019 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-17 07:10:46.049  1019  1230 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 07:10:46.049  1019  1230 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.049  1019  1230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:46.049  1019  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.059  1019  1715 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 07:10:46.059  1019  1715 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-17 07:10:46.059  1019  1715 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
03-17 07:10:46.059  1019  1715 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 07:10:46.059  1695  4631 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 07:10:46.059  4614  4614 I MultiDex: VM with version 2.1.0 has multidex support
03-17 07:10:46.059  4614  4614 I MultiDex: install
03-17 07:10:46.059  4614  4614 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 07:10:46.079  4614  4614 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 07:10:46.129  4614  4614 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 07:10:46.139  4614  4614 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16e808ba: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 07:10:46.139  4614  4614 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 07:10:46.159  1695  1695 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 07:10:46.169  1970  1970 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 07:10:46.169  1019  4037 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 07:10:46.169  4614  4614 D WearableService: callingUid 10012, callindPid: 4614
,03-17 07:10:46.169  1019  4037 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.169  1019  4037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:46.169  1019  4037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.199  1019  1528 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:46.209  1019  1528 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.209  1019  1528 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:46.209  1019  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.219  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 07:10:46.229  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.229  1019  1554 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:46.229  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.229  1970  4634 D LocationInitializer: Restart initialization of location
,03-17 07:10:46.229  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 07:10:46.229  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.239  1019  1389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:46.239  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 07:10:46.239  1019  4038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 07:10:46.239  1353  1353 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 07:10:46.239  1353  1353 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 07:10:46.239  1353  1353 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 07:10:46.239  1353  1353 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-17 07:10:46.239  1353  1353 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 07:10:46.239  1353  1353 I NearbySettings: MountReceiver.onReceive - Keep current state
03-17 07:10:46.249  2604  2604 I Hs20UtilService: Starting #4
,03-17 07:10:46.249  1019  4038 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.249  1019  4038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:46.249  1019  4038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:46.249  2604  2619 I Hs20UtilService: Message received 5007
,03-17 07:10:46.259  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 07:10:46.259  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.259  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:46.259  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 07:10:46.269  2604  2604 I Hs20UtilService: Starting #5
,03-17 07:10:46.269  2604  2619 I Hs20UtilService: Message received 5007
,03-17 07:10:46.269  1353  1353 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 07:10:46.269  1695  1704 I art     : Explicit concurrent mark sweep GC freed 11482(631KB) AllocSpace objects, 3(108KB) LOS objects, 40% free, 10MB/17MB, paused 1.089ms total 44.325ms
,03-17 07:10:46.279  1353  1353 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 07:10:46.279  1811  4613 E MDM     : [208] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 07:10:46.279  1811  4638 E MDM     : [209] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 07:10:46.289  1019  1751 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 07:10:46.289  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.289  1019  1751 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.289  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 07:10:46.289  2604  2604 I Hs20UtilService: Starting #6
,03-17 07:10:46.289  2604  2619 I Hs20UtilService: Message received 5007
03-17 07:10:46.289  1019  1343 E Watchdog: !@Sync 1
,03-17 07:10:46.299  1353  1353 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 07:10:46.299  1353  1353 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 07:10:46.299  1353  1353 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 07:10:46.299  1353  1353 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-17 07:10:46.299  1353  1353 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,03-17 07:10:46.309  1353  1353 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 07:10:46.309  1019  1554 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 07:10:46.319  1019  1554 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:46.319  1019  1554 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.319  1019  1554 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 07:10:46.319  2604  2604 I Hs20UtilService: Starting #7
03-17 07:10:46.319  1353  1353 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 07:10:46.319  1353  1353 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 07:10:46.319  2604  2619 I Hs20UtilService: Message received 5007
,03-17 07:10:46.329  1019  1715 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,03-17 07:10:46.329  1019  4038 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-17 07:10:46.329  1019  4038 D SecContentProvider2: mCursor = null
,03-17 07:10:46.329  1019  1230 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-17 07:10:46.329  1019  1230 D SecContentProvider2: mCursor = null
,03-17 07:10:46.329  1019  3273 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
03-17 07:10:46.329  1019  3273 D SecContentProvider2: mCursor = null
,03-17 07:10:46.339  1019  1141 D SettingsProvider: name = audio_safe_volume_state
,03-17 07:10:46.339  1019  1031 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
03-17 07:10:46.339  1019  1031 D SecContentProvider2: mCursor = null
,03-17 07:10:46.339  1019  1389 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-17 07:10:46.339  1019  1389 D SecContentProvider2: mCursor = null
,03-17 07:10:46.339  1019  1384 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,03-17 07:10:46.339  1019  1384 D SecContentProvider2: mCursor = null
,03-17 07:10:46.349  3467  3467 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 07:10:46.349  3467  3467 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 07:10:46.349  3467  3467 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 07:10:46.349  3467  3467 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:46.349  1019  4037 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
,03-17 07:10:46.349  1019  4037 I splitIntent: base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
03-17 07:10:46.349  1019  4037 I splitIntent: other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
,03-17 07:10:46.349  1019  4037 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,03-17 07:10:46.359  1019  4037 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.359  1019  4037 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.359  1019  4037 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.359  1019  4037 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.369   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,03-17 07:10:46.369  4640  4640 E Zygote  : MountEmulatedStorage(),
03-17 07:10:46.369  4640  4640 E Zygote  : v2
03-17 07:10:46.369  4640  4640 I libpersona: KNOX_SDCARD checking this for 10111,
03-17 07:10:46.369  4640  4640 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:46.369  1019  4037 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4640 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:46.369  4640  4640 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:46.379  4640  4640 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 07:10:46.379  4640  4640 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:46.379  1019  1715 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
03-17 07:10:46.379  1019  1052 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
03-17 07:10:46.379  1019  1052 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255))),
03-17 07:10:46.379  1019  1052 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 07:10:46.379  1191  1191 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 07:10:46.399  1019  1052 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
,03-17 07:10:46.399  1019  1163 D lights  : lcd : 32 +
,03-17 07:10:46.399  1019  1052 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 07:10:46.399  4640  4640 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:46.409  4640  4640 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:46.409  1019  1163 D lights  : lcd : 32 -
,03-17 07:10:46.409  1019  1052 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
,03-17 07:10:46.409  1019  1052 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 07:10:46.609  4640  4640 I MusicStore: Database version: 120
,03-17 07:10:46.619  1019  2871 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 07:10:46.689  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,03-17 07:10:46.699  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 07:10:46.699  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.699  1019  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:46.699  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:46.739   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 07:10:46.739   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:46.739  4640  4640 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 07:10:46.759  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,03-17 07:10:46.759  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.759  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:46.759  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:46.789   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 07:10:46.789   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:46.789  4640  4640 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 07:10:46.799   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 07:10:46.799   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:46.799  4640  4640 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 07:10:46.829  4640  4640 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 07:10:46.829  4640  4640 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 07:10:46.849  4640  4640 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 07:10:46.909  4640  4640 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 07:10:46.909  4640  4640 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@bae479: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-17 07:10:46.909  4640  4640 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 07:10:46.909  4640  4640 D AndroidMusic: GMSCore installation verified
,03-17 07:10:46.919  1019  1100 V AlarmManager: waitForAlarm result :4
,03-17 07:10:46.929  4640  4640 I ConfigStore: Config Database version: 1
,03-17 07:10:47.009  1019  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,03-17 07:10:47.009  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.009  1019  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:47.009  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:47.029  1019  1528 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,03-17 07:10:47.029  1019  1528 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.029  1019  1528 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:47.029  1019  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:47.049  1019  1389 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:47.059  1019  3272 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:47.069  1019  4038 I AudioService: getStreamVolume 3 index 0
,03-17 07:10:47.069  4640  4640 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-17 07:10:47.079  4640  4640 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-17 07:10:47.089  4640  4640 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 07:10:47.129  1019  1751 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 07:10:47.129  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.129  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:47.129  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:47.139  1019  4037 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,03-17 07:10:47.139  1019  4037 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.139  1019  4037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:47.139  1019  4037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:47.139  1019  1715 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,03-17 07:10:47.139  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.149  1019  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:47.149  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:47.149  1019  3273 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:47.159  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.159  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.159  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.159  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.169  4640  4640 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 07:10:47.179  4668  4668 E Zygote  : MountEmulatedStorage(),
03-17 07:10:47.179  4668  4668 E Zygote  : v2
03-17 07:10:47.179  4668  4668 I libpersona: KNOX_SDCARD checking this for 10002
03-17 07:10:47.179  4668  4668 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:47.179  4668  4668 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:47.179  4668  4668 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:47.179  1019  1019 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4668 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:47.179  4668  4668 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:47.199  4668  4668 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:47.199  4668  4668 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.209  1019  4037 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:47.209  1019  4037 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.209  1019  4037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:47.209  1019  4037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.209  4640  4640 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,03-17 07:10:47.219  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-17 07:10:47.219  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.219  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:47.219  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.219  4640  4640 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-17 07:10:47.229  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 07:10:47.229  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.229  1019  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:47.229  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:47.249  1019  1032 I ActivityManager: Killing 3858:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-17 07:10:47.269  1019  3273 I ActivityManager: Killing 3748:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,03-17 07:10:47.279  1019  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.279  1019  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.279  1019  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.279  1019  1389 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.289  4687  4687 E Zygote  : MountEmulatedStorage(),
03-17 07:10:47.289  4687  4687 E Zygote  : v2
03-17 07:10:47.289  4687  4687 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:47.289  4687  4687 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:47.289  4687  4687 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 07:10:47.289  4687  4687 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:47.299  1019  1389 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4687 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:47.299  4687  4687 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:47.309   318   318 I art     : Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 21.241ms
,03-17 07:10:47.319  4687  4687 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:47.319  4687  4687 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.329   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 18.416ms
,03-17 07:10:47.349   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 598us total 18.540ms
,03-17 07:10:47.369  1019  1043 W libprocessgroup: failed to open /acct/uid_10139/pid_3858/cgroup.procs: No such file or directory
,03-17 07:10:47.369  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3748/cgroup.procs: No such file or directory
,03-17 07:10:47.369  4687  4687 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 07:10:47.449  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 07:10:47.449  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:47.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:47.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:47.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:47.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:47.469  4687  4687 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 07:10:47.479  4687  4687 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 07:10:47.479  4687  4687 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:47.479  4687  4687 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 07:10:47.479  4687  4687 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-17 07:10:47.479  4687  4687 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 07:10:47.559  4303  4312 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:47.559  4303  4312 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:47.559  4303  4312 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 07:10:47.559  4303  4311 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:47.569  4303  4311 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:47.569  4303  4311 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 07:10:47.569  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.569  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.569  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.569  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.579  4704  4704 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:47.589  4704  4704 E Zygote  : v2
03-17 07:10:47.589  4704  4704 I libpersona: KNOX_SDCARD checking this for 10009
03-17 07:10:47.589  4704  4704 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:47.589  4704  4704 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:47.589  1019  4038 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4704 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 07:10:47.589  4704  4704 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:47.589  4704  4704 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,03-17 07:10:47.609  4704  4704 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:47.609  4704  4704 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.659  1019  1713 I ActivityManager: Killing 3928:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-17 07:10:47.669  4704  4704 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 07:10:47.679  4704  4704 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 07:10:47.679  1019  4038 I ActivityManager: Killing 4012:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-17 07:10:47.679  3759  3759 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 07:10:47 GMT+01:00 2016
,03-17 07:10:47.679  1019  3272 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:47.679  1019  3272 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:47.679  1019  3272 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:47.679  1019  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 07:10:47.689  3759  3759 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 07:10:47.689  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,03-17 07:10:47.689  3759  3759 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 07:10:47.699  3759  3759 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 07:10:47.699  3759  3759 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 07:10:47.699  3759  4721 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 07:10:47.709  4303  4303 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:47.709  3759  4721 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-17 07:10:47.719  4325  4325 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,03-17 07:10:47.719  4303  4722 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 07:10:47.719  4325  4325 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-17 07:10:47.719  4325  4325 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
03-17 07:10:47.719  4303  4722 I DBG_POLICYDM: [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
03-17 07:10:47.719  4303  4722 E DBG_POLICYDM: [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,03-17 07:10:47.719  3759  4721 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-17 07:10:47.729  3759  4721 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,03-17 07:10:47.729  4325  4325 I SA      : [SLFUCHKMGR] constructor called
,03-17 07:10:47.729  3759  4721 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,03-17 07:10:47.729  4303  4722 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 07:10:47.729  4325  4325 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-17 07:10:47.729  4325  4325 I SA      : [OR] == isSIMCardReady false ==
,03-17 07:10:47.739  3759  4721 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,03-17 07:10:47.739  3759  4721 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,03-17 07:10:47.739  4325  4325 I SA      : [SCU] == networkStateCheck == true
03-17 07:10:47.739  4325  4325 I SA      : [DM] getCountryCodeFromCSC : PL
03-17 07:10:47.739  4325  4325 I SA      : isChinaCountryCode : false
03-17 07:10:47.739  4325  4325 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-17 07:10:47.739  4325  4325 I SA      : [OR] == networkStateCheck true ==
,03-17 07:10:47.739  4325  4325 I SA      : [OR] GetMyCountryZoneTask
,03-17 07:10:47.739  4325  4325 I SA      : [OR] onReceive END
,03-17 07:10:47.739  3759  3759 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 07:10:47.749  1261  1261 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
03-17 07:10:47.749  4303  4722 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 07:10:47.749  4303  4722 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 07:10:47.749  4325  4724 I SA      : [SRS] prepareGetMyCountryZone
,03-17 07:10:47.749  4303  4722 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 07:10:47.749  4303  4722 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 07:10:47.749  4303  4722 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 07:10:47.749  1019  4038 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
03-17 07:10:47.749  4303  4722 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 07:10:47.759  1019  4038 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:47.759  4303  4722 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 07:10:47.759  1019  4038 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:47.759  1019  4038 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 07:10:47.759  4303  4722 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-17 07:10:47.759  4303  4722 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-17 07:10:47.759  1649  1649 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 07:10:47.759  4325  4724 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-17 07:10:47.759  4303  4722 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,03-17 07:10:47.769  4325  4724 I SA      : [SSP] query invoked
,03-17 07:10:47.769  4325  4724 I SA      : [TPMU] GetMccFromDB : null
,03-17 07:10:47.769  4325  4724 I SA      : [SCU] getMccFromPreferece mcc = 260
03-17 07:10:47.769  4325  4724 I SA      : [TPM] isNoProxy(default) : true
,03-17 07:10:47.769  1332  1349 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,03-17 07:10:47.779  1019  1389 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 07:10:47.779  1019  1389 D SecContentProvider2: mCursor = null
,03-17 07:10:47.779  4303  4722 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 07:10:47.779  1649  1649 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-17 07:10:47.779  4303  4722 I DBG_POLICYDM: [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
03-17 07:10:47.779  1649  1649 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,03-17 07:10:47.779  1649  1649 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,03-17 07:10:47.779  1649  1649 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-17 07:10:47.779  4325  4724 E File    : fail readDirectory() errno=2
,03-17 07:10:47.789  1649  1649 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 07:10:47.789  1649  1649 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 07:10:47.789  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.789  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.789  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.789  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.799  4727  4727 E Zygote  : MountEmulatedStorage()
03-17 07:10:47.799  1019  1241 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4727 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-17 07:10:47.799  4727  4727 E Zygote  : v2
03-17 07:10:47.799  4727  4727 I libpersona: KNOX_SDCARD checking this for 10125
03-17 07:10:47.799  4727  4727 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:47.809  4727  4727 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:47.809  4727  4727 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:47.809  4727  4727 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:47.829  4727  4727 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:47.829  4727  4727 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.829  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3928/cgroup.procs: No such file or directory
03-17 07:10:47.829  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4012/cgroup.procs: No such file or directory
,03-17 07:10:47.839  4727  4727 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:47.839  4727  4727 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:47.839  4727  4727 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:47.869  4727  4727 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:47.869  4727  4727 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,03-17 07:10:47.869  4727  4727 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 07:10:47.879  1019  1384 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:47.879  1019  3273 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:47.889  4078  4078 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 07:10:47.889  4078  4078 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 07:10:47.889  4078  4078 D SecurityLogAgent: StateMachine : Current State = 1
03-17 07:10:47.889  4078  4078 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-17 07:10:47.899  1019  1713 I ActivityManager: Killing 4053:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 07:10:47.919  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 07:10:47.919  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.919  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:47.919  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.959  1970  4745 I iu.SyncManager: SYNC; picasa accounts
,03-17 07:10:47.969  1970  1970 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-17 07:10:47.969  1970  1970 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-17 07:10:47.989  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,03-17 07:10:47.989  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.989  1019  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:47.989  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.999  1970  4745 I iu.UploadsManager: num queued entries: 0
,03-17 07:10:47.999  1970  1970 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-17 07:10:47.999  1970  4745 I iu.UploadsManager: num updated entries: 0
,03-17 07:10:47.999  1970  4745 I iu.SyncManager: NEXT; no task
,03-17 07:10:48.009  1970  1970 I Kids    : [GCoreUtils] Current gmscore version, 7899436 is smaller than the required version 8400000
,03-17 07:10:48.009  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4053/cgroup.procs: No such file or directory
03-17 07:10:48.009  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,03-17 07:10:48.009  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.009  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.009  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 07:10:48.019  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,03-17 07:10:48.019  4348  4348 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:48.019  4348  4348 E SPPClientService: [SystemStateMoniter] Current Time : 51397
03-17 07:10:48.019  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.019  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:48.019  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 07:10:48.029  4348  4348 E SPPClientService: [SystemStateMoniter] No Connect : false
,03-17 07:10:48.029  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.029  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.029  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.029  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.039  4748  4748 E Zygote  : MountEmulatedStorage()
03-17 07:10:48.039  4748  4748 E Zygote  : v2
03-17 07:10:48.039  4748  4748 I libpersona: KNOX_SDCARD checking this for 10113
03-17 07:10:48.039  4748  4748 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:48.039  4748  4748 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:48.049  4748  4748 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:48.049  4192  4747 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager,
03-17 07:10:48.049  4748  4748 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
03-17 07:10:48.049  4192  4747 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 07:10:48.049  4192  4747 I System.out: (HTTPLog)-Static: isShipBuild true
03-17 07:10:48.049  4192  4747 I System.out: (HTTPLog)-Thread-641-169577796: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 07:10:48.049  4192  4747 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 07:10:48.049   281   998 D EnterpriseController: uids 10104
03-17 07:10:48.049  1019  4038 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4748 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:48.049   281   998 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 07:10:48.049   281   998 D Netd    : getNetworkForDns: using netid 502 for uid 10104
,03-17 07:10:48.059  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{2db06789 u0 com.samsung.android.providers.context/.ContextService}
,03-17 07:10:48.069  4748  4748 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:48.069  4748  4748 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:48.139  4192  4747 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,03-17 07:10:48.189  1019  1044 I ActivityManager: Waited long enough for: ServiceRecord{109e038e u0 com.android.settings/.wifi.WifiCredService}
,03-17 07:10:48.209   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 07:10:48.209   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:48.209  4748  4769 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 07:10:48.209   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 07:10:48.209   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:48.209  4748  4769 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 07:10:48.219  4748  4748 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-17 07:10:48.219  4748  4748 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-17 07:10:48.219  4748  4748 I GAv4    :   adb logcat -s GAv4
,03-17 07:10:48.219   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 07:10:48.219   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:48.229  4748  4770 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 07:10:48.229   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 07:10:48.229   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:48.229  4748  4770 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 07:10:48.229  4748  4748 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-17 07:10:48.239  4192  4747 I Babel   : connection state changed from UNKNOWN to CONNECTED
,03-17 07:10:48.249  4748  4748 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-17 07:10:48.259  4748  4772 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-17 07:10:48.399  4325  4724 I SA      : [RC New] Execute method=[GET] start
,03-17 07:10:48.409  1019  1384 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:48.409  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.409  1019  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:48.409  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.429  4748  4748 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700),
,03-17 07:10:48.439  4325  4724 I SA      : [RC New] Security=[true]
,03-17 07:10:48.439  4325  4724 I System.out: Thread-665(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 07:10:48.439  4325  4724 I System.out: Thread-665(ApacheHTTPLog):isSBSettingEnabled false
03-17 07:10:48.439  4325  4724 I System.out: Thread-665(ApacheHTTPLog):isShipBuild true
03-17 07:10:48.439  4325  4724 I System.out: Thread-665(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 07:10:48.439  4325  4724 I System.out: Thread-665(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 07:10:48.439   281   998 D EnterpriseController: uids 10041
03-17 07:10:48.439   281   998 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 07:10:48.439   281   998 D Netd    : getNetworkForDns: using netid 502 for uid 10041
,03-17 07:10:48.439  4748  4748 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 1812-1818)
03-17 07:10:48.439  4748  4748 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 07:10:48.449  4748  4748 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {62fb47}
,03-17 07:10:48.449  4748  4748 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 07:10:48.449  4748  4748 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 07:10:48.449  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:48.449  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:48.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:48.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:48.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:48.449  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:48.459  4748  4748 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 07:10:48.459  4748  4748 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:48.459  4748  4748 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 07:10:48.489  4748  4748 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 07:10:48.489  4748  4748 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 07:10:48.489  4748  4748 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 07:10:48.489  4748  4748 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 07:10:48.489  4748  4748 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 07:10:48.489  4748  4748 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 07:10:48.489  4748  4748 I Adreno-EGL: Local Branch: 
03-17 07:10:48.489  4748  4748 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 07:10:48.489  4748  4748 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 07:10:48.489  4748  4748 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 07:10:48.559  4748  4801 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-17 07:10:48.569  4748  4748 I NSApplication: Starting up...
,03-17 07:10:48.579  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.579  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.579  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.579  1019  3272 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.589  1019  3272 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4806 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 07:10:48.589  4806  4806 E Zygote  : MountEmulatedStorage()
03-17 07:10:48.589  4806  4806 I libpersona: KNOX_SDCARD checking this for 10081
03-17 07:10:48.589  4806  4806 E Zygote  : v2,
03-17 07:10:48.589  4806  4806 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:48.589  4806  4806 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 07:10:48.599  1019  3272 I ActivityManager: Killing 3946:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-17 07:10:48.599  4806  4806 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:48.599  4806  4806 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-17 07:10:48.619  4806  4806 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:48.619  4806  4806 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:48.689  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,03-17 07:10:48.699  1019  1043 W libprocessgroup: failed to open /acct/uid_10031/pid_3946/cgroup.procs: No such file or directory
,03-17 07:10:48.819  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.819  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.819  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.819  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.829  4823  4823 E Zygote  : MountEmulatedStorage()
,03-17 07:10:48.829  4823  4823 E Zygote  : v2
,03-17 07:10:48.839  4823  4823 I libpersona: KNOX_SDCARD checking this for 10120
03-17 07:10:48.839  4823  4823 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:48.839  4823  4823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:48.839  1019  4038 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4823 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:48.839  1019  4038 I ActivityManager: Killing 4095:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,03-17 07:10:48.839  4823  4823 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:48.839  4823  4823 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:48.859  4823  4823 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:48.859  4823  4823 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:48.869   291   291 E SMD     : DCD OFF
,03-17 07:10:48.879  4823  4823 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 07:10:49.049  1019  1043 W libprocessgroup: failed to open /acct/uid_10152/pid_4095/cgroup.procs: No such file or directory
,03-17 07:10:49.119  1019  1230 I art     : Explicit concurrent mark sweep GC freed 25248(1480KB) AllocSpace objects, 3(68KB) LOS objects, 33% free, 30MB/45MB, paused 2.314ms total 152.839ms
,03-17 07:10:49.119  1019  1230 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-17 07:10:49.129  1019  1230 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.129  1019  1230 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:49.129  1019  1230 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.139  4325  4724 I SA      : [RC New] [v2liruge] api execute + 707,
03-17 07:10:49.149  4325  4724 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,03-17 07:10:49.149  4451  4475 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 07:10:49.149  4325  4724 I System.out: AsyncTask #1 calls detatch()
,03-17 07:10:49.169  4325  4724 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,03-17 07:10:49.179  4325  4724 I SA      : [OCP] update openData : PL
,03-17 07:10:49.179  4325  4724 I SA      : [TPMU] getNetworkMcc : 
,03-17 07:10:49.179  4325  4724 I SA      : [SCU] saveMccToPreferece Start
,03-17 07:10:49.189  4325  4724 I SA      : [SCU] RegionMCC : 260
03-17 07:10:49.189  4325  4724 I SA      : [SSP] query invoked
,03-17 07:10:49.189  4325  4724 I SA      : [TPMU] GetMccFromDB : null
,03-17 07:10:49.189  4325  4724 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-17 07:10:49.189  4325  4724 I SA      : [SCU] saveMccToPreferece End
,03-17 07:10:49.189  4325  4724 I SA      : [RC New] executeRequest [v2liruge] end. 787
03-17 07:10:49.189  4325  4724 I SA      : [RC New] Execute end
,03-17 07:10:49.189  4325  4325 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-17 07:10:49.189  4325  4325 I SA      : [OR] GetMyCountryZoneTask Success
,03-17 07:10:49.289  1019  1059 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,03-17 07:10:49.329  3605  3605 I PageBuddyNotiSvc: mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,03-17 07:10:49.329  1019  1105 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 07:10:49.339  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.349  1485  1485 D RegisteredComponentCache: Collect Tech packages for Knox
,03-17 07:10:49.349  1485  1485 D PersonaManager: isKioskContainerExistOnDevice,
,03-17 07:10:49.349  1501  1501 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:49.359  1485  1485 D PersonaManager: isKioskContainerExistOnDevice
,03-17 07:10:49.359  1485  1485 D RegisteredServicesCache: empty dynamic service
,03-17 07:10:49.359  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.359  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.399  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.419  1019  1389 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 07:10:49.419  1019  1389 D SecContentProvider2: mCursor = null
,03-17 07:10:49.459  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.459  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.459  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.459  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.469  4846  4846 E Zygote  : MountEmulatedStorage()
,03-17 07:10:49.469  1019  3273 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4846 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 07:10:49.469  4846  4846 E Zygote  : v2
03-17 07:10:49.469  4846  4846 I libpersona: KNOX_SDCARD checking this for 10010
03-17 07:10:49.469  4846  4846 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:49.479  4846  4846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:49.479  1019  3273 I ActivityManager: Killing 4131:com.sec.modem.settings/1000 (adj 15): empty #31
03-17 07:10:49.479  4846  4846 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:49.479  4846  4846 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 07:10:49.489  1531  1531 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 07:10:49.489  1531  1531 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 07:10:49.509  4846  4846 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:49.509  4846  4846 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:49.549  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 07:10:49.549  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.549  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.559  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.559  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:49.559  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:49.559  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:49.559  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.579  1019  1019 W IntentResolver: resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,03-17 07:10:49.579  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-17 07:10:49.579  1019  1019 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 07:10:49.579  1019  1019 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 07:10:49.579  1019  1019 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,03-17 07:10:49.589  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.589  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.589  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.589  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 07:10:49.589  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.599  1019  1019 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-17 07:10:49.599  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 07:10:49.599  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 07:10:49.599  1019  1019 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3d561022
,03-17 07:10:49.599  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 07:10:49.599  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 07:10:49.599  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 07:10:49.609  1019  1043 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-17 07:10:49.609  1019  1043 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-17 07:10:49.619  1019  1043 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-17 07:10:49.639  1019  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4131/cgroup.procs: No such file or directory
,03-17 07:10:49.659  4846  4846 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-17 07:10:49.669  1019  1043 D LocationProviderProxy: applying state to connected service
,03-17 07:10:49.699  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 13 sec
,03-17 07:10:49.729  4846  4846 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-17 07:10:49.729  1019  4038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:49.729  1019  4038 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-17 07:10:49.859  1019  1715 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1019) eventTime = 53232,
,03-17 07:10:49.859  1019  1715 D PowerManagerService: [s] UserActivityState : 2 -> 1,
03-17 07:10:49.859  1019  1715 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019 (0x0)
03-17 07:10:49.859  1019  1715 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1019, ws=WorkSource{10054}) (elapsedTime=3482)
,03-17 07:10:49.869  1019  1528 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,03-17 07:10:49.869  1019  1528 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.869  1019  1528 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 07:10:49.869  1019  1528 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-17 07:10:49.879  4846  4846 D hcjo    : AutoUpdateManager:IDLE:execute
03-17 07:10:49.879  1019  1019 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
03-17 07:10:49.879  1019  1019 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-17 07:10:49.879   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 07:10:49.879  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.879  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.879  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.879  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.879  4846  4846 D InitializeManagerStateMachine: execute::IDLE:EXECUTE,
03-17 07:10:49.879  4846  4846 D InitializeManagerStateMachine: exit::IDLE
03-17 07:10:49.879  4846  4846 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-17 07:10:49.889  4846  4846 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
03-17 07:10:49.889  4846  4846 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-17 07:10:49.889  4846  4846 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-17 07:10:49.889  4846  4846 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-17 07:10:49.889  4846  4846 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-17 07:10:49.889  4846  4846 D InitializeManagerStateMachine: entry::SUCCESS
03-17 07:10:49.889  4846  4846 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-17 07:10:49.899  4866  4866 E Zygote  : MountEmulatedStorage()
,03-17 07:10:49.899  1019  1044 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4866 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:49.899  4866  4866 E Zygote  : v2
03-17 07:10:49.899  4866  4866 I libpersona: KNOX_SDCARD checking this for 10062
03-17 07:10:49.899  4866  4866 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:49.899  4866  4866 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:49.899  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.899  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.899  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.899  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.899  4866  4866 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:49.909  4866  4866 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:49.919  4874  4874 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:49.919  4874  4874 E Zygote  : v2
03-17 07:10:49.919  4874  4874 I libpersona: KNOX_SDCARD checking this for 10135,
03-17 07:10:49.919  4874  4874 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:49.919  4874  4874 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 07:10:49.919  4874  4874 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:49.919  4874  4874 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 07:10:49.919  1019  1044 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4874 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-17 07:10:49.939  4704  4704 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 07:10:49.939  4846  4846 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,03-17 07:10:49.939  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 07:10:49.939  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 07:10:49.939  1332  1332 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:49.949  4874  4874 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:49.949  4874  4874 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:49.949  4866  4866 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:49.959  4866  4866 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:49.959  1332  1332 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 07:10:49.959  4704  4704 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-17 07:10:49.959  1332  1332 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 07:10:49.969  1332  1332 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,03-17 07:10:49.979  4846  4846 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
03-17 07:10:49.979  4846  4846 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,03-17 07:10:49.979  1332  1332 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 07:10:49.979  1332  1332 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-17 07:10:49.979  1332  1332 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 07:10:49.979  1332  1332 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 07:10:49.979  1332  1332 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 07:10:49.979  1332  1332 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 07:10:49.989  4874  4874 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:49.989  4874  4874 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:49.989  4874  4874 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:49.989  3759  3759 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Mar 17 07:10:49 GMT+01:00 2016
,03-17 07:10:49.989  4846  4846 D InitializeManagerStateMachine: exit::SUCCESS
,03-17 07:10:49.989  4846  4846 D InitializeManagerStateMachine: entry::IDLE
,03-17 07:10:49.989  1019  1384 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:49.989  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.989  1019  1384 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:49.989  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 07:10:49.999  1019  3273 I ActivityManager: Killing 4180:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
03-17 07:10:49.999  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 07:10:49.999  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 07:10:49.999  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 07:10:49.999  1332  1332 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 07:10:50.009  3759  3759 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 07:10:50.009  1332  1332 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 07:10:50.009  4325  4325 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,03-17 07:10:50.019  3759  3759 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 07:10:50.019  3759  3759 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 07:10:50.019  1332  1332 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 07:10:50.029  3759  3759 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 07:10:50.029  3759  4899 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-17 07:10:50.029  1332  1332 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,03-17 07:10:50.029  1332  1332 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 07:10:50.039  3759  4899 I KLMS-2.5.183: : KLMSIntentService(): TIME_CHANGED
,03-17 07:10:50.039  3759  4899 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().START : Thu Mar 17 07:10:50 GMT+01:00 2016
,03-17 07:10:50.039  1019  1715 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.049  1019  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.049  1019  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.049  1019  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.059  3759  4899 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().END
,03-17 07:10:50.059  4486  4538 I System.out: Thread-695(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 07:10:50.059  4486  4538 I System.out: Thread-695(ApacheHTTPLog):isSBSettingEnabled false
03-17 07:10:50.059  4486  4538 I System.out: Thread-695(ApacheHTTPLog):isShipBuild true
03-17 07:10:50.059  4486  4538 I System.out: Thread-695(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 07:10:50.059  4486  4538 I System.out: Thread-695(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 07:10:50.069  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.069  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.069  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.069  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.069  3759  3759 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 07:10:50.069   281   998 D EnterpriseController: uids 10092
03-17 07:10:50.069   281   998 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 07:10:50.069   281   998 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-17 07:10:50.089  4902  4902 E Zygote  : MountEmulatedStorage(),
03-17 07:10:50.089  4902  4902 E Zygote  : v2
03-17 07:10:50.089  4902  4902 I libpersona: KNOX_SDCARD checking this for 10046
03-17 07:10:50.089  4902  4902 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:50.089  4902  4902 I libpersona: KNOX_SDCARD not a persona,
,03-17 07:10:50.089  4866  4866 I ExternalOEMControlProvider: onCreate
,03-17 07:10:50.089  4902  4902 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:50.089  4902  4902 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:50.089  1019  1713 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4902 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,03-17 07:10:50.109  1019  1241 I ActivityManager: Killing 4234:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,03-17 07:10:50.109  1649  1649 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-17 07:10:50.119  1649  1649 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 07:10:50.119  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.119  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.119  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.119  1019  1241 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.119  4902  4902 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:50.129  4902  4902 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.129  1019  1043 W libprocessgroup: failed to open /acct/uid_1101/pid_4180/cgroup.procs: No such file or directory
03-17 07:10:50.129  4866  4911 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-17 07:10:50.139  4918  4918 E Zygote  : MountEmulatedStorage(),
03-17 07:10:50.139  4918  4918 E Zygote  : v2
,03-17 07:10:50.139  4918  4918 I libpersona: KNOX_SDCARD checking this for 10085
03-17 07:10:50.139  4918  4918 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:50.139  4918  4918 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:50.139  1019  1241 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4918 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:50.139  4918  4918 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 07:10:50.139  4918  4918 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:50.159  1332  1349 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:50.159  1019  1043 W libprocessgroup: failed to open /acct/uid_10157/pid_4234/cgroup.procs: No such file or directory
,03-17 07:10:50.159  4902  4902 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-17 07:10:50.159  4902  4902 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:50.159  4902  4902 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:50.159  4902  4902 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:50.159  4902  4902 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 07:10:50.159  4902  4902 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:50.169  4918  4918 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:50.169  4918  4918 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.179  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.179  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.179  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:50.179  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 07:10:50.189  4918  4918 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:50.189  4918  4918 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:50.189  4918  4918 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:50.189  4918  4918 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:50.189  4918  4918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:50.189  4918  4918 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-17 07:10:50.189  1019  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.199  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.199  1019  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.199  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.209  1019  1041 D SensorService: [SO] 0.192 0.383 10.190
,03-17 07:10:50.219  1019  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.219  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.219  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:50.219  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 07:10:50.219  4902  4902 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,03-17 07:10:50.229  4078  4078 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 07:10:50.229  4078  4078 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,03-17 07:10:50.229  4078  4078 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 07:10:50.229  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.229  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.239  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.239  1019  4038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.249  4940  4940 E Zygote  : MountEmulatedStorage(),
03-17 07:10:50.249  4940  4940 E Zygote  : v2
03-17 07:10:50.249  4940  4940 I libpersona: KNOX_SDCARD checking this for 10157
,03-17 07:10:50.249  4940  4940 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:50.249  4940  4940 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:50.249  4940  4940 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 07:10:50.259  1019  4038 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4940 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,03-17 07:10:50.259  4940  4940 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:50.279   318   318 I art     : Explicit concurrent mark sweep GC freed 8697(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 23.953ms
,03-17 07:10:50.279  4940  4940 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:50.279  4940  4940 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.289   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 17.859ms
,03-17 07:10:50.299  4940  4940 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:50.309   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 17.192ms
,03-17 07:10:50.319  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.319  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.319  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.319  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.339  4956  4956 E Zygote  : MountEmulatedStorage(),
03-17 07:10:50.339  4956  4956 E Zygote  : v2
,03-17 07:10:50.339  4956  4956 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:50.339  4956  4956 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:50.339  1019  3273 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4956 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:50.339  4956  4956 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:50.339  4956  4956 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 07:10:50.339  1019  4038 I ActivityManager: Killing 3973:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-17 07:10:50.339  4956  4956 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:50.359  1019  4038 I ActivityManager: Killing 4366:com.google.android.youtube/u0a166 (adj 15): empty #31
,03-17 07:10:50.359  1019  1031 D SettingsProvider: name = next_alarm_formatted
03-17 07:10:50.359  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:50.359  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:50.359  1019  1031 D SettingsProvider: selectionArgs: false
03-17 07:10:50.359  1019  1031 D SettingsProvider: selectionArgs: 10085
03-17 07:10:50.359  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-17 07:10:50.359  1019  1031 D SettingsProvider: ret = -1
,03-17 07:10:50.369  4956  4956 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:50.369  4956  4956 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.379  4902  4902 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 145.867ms
,03-17 07:10:50.399   257  1172 I SurfaceFlinger: id=13 Removed Uoast (8/8)
,03-17 07:10:50.399   257   451 I SurfaceFlinger: id=13 Removed Uoast (-2/8)
,03-17 07:10:50.399  4956  4956 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458195050412
03-17 07:10:50.399  4956  4956 D         : TimeServiceNative: User Time to be set is 1458195050412
03-17 07:10:50.399  4956  4956 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-17 07:10:50.399  4956  4956 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-17 07:10:50.399  4956  4956 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458195050412
,03-17 07:10:50.399   335   431 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-17 07:10:50.399  4956  4956 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-17 07:10:50.399   335  4971 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458195050412
03-17 07:10:50.399   335  4971 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458195050412, operation = 0
03-17 07:10:50.399   335  4971 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/7/70 21:24:26
03-17 07:10:50.409   335  4971 D QC-time-services: Daemon:Value read from RTC seconds = 21590666000
03-17 07:10:50.409   335  4971 D QC-time-services: Daemon:new time 1458195050412 
03-17 07:10:50.409   335  4971 D QC-time-services: Daemon: delta 1436604384412 genoff 1436604384412 
03-17 07:10:50.409   335  4971 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436604384412 to memory
03-17 07:10:50.409   335  4971 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-17 07:10:50.409   335  4971 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 07:10:50.429   335  4971 D QC-time-services: Updating the TOD offset,
03-17 07:10:50.429   335  4971 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436604384412 to memory
03-17 07:10:50.429   335  4971 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-17 07:10:50.429   335  4971 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 07:10:50.429   335  4971 E QC-time-services: Daemon:Update to modem bit set
,03-17 07:10:50.429   335  4971 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-17 07:10:50.429  4956  4956 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-17 07:10:50.429   335  4971 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120639584412
,03-17 07:10:50.429   335   427 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-17 07:10:50.429   335   431 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-17 07:10:50.439  1019  4037 I ActivityManager: Killing 4451:com.google.android.gm/u0a101 (adj 15): empty #31
,03-17 07:10:50.449  4902  4972 D Mms/ArtClassLoader: init before art
,03-17 07:10:50.459  4902  4902 D Mms/TelephonyPermission: start operation mode monitor
,03-17 07:10:50.459  1019  1043 W libprocessgroup: failed to open /acct/uid_10072/pid_3973/cgroup.procs: No such file or directory
,03-17 07:10:50.459  4902  4902 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:50.469  4918  4918 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 100.519ms
,03-17 07:10:50.469  4902  4902 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-17 07:10:50.469  4902  4902 D Mms/TelephonyPermission: isDefault true
,03-17 07:10:50.469  4902  4902 D Mms/MmsApp: onCreate() com.android.mms
,03-17 07:10:50.489  4902  4902 D Mms/MmsApp: [start]    initCountryIso consume time = 264.285313
,03-17 07:10:50.489  1019  1043 W libprocessgroup: failed to open /acct/uid_10166/pid_4366/cgroup.procs: No such file or directory
,03-17 07:10:50.489  1019  1043 W libprocessgroup: failed to open /acct/uid_10101/pid_4451/cgroup.procs: No such file or directory
,03-17 07:10:50.489  1019  1715 D CountryDetector: The first listener is added
,03-17 07:10:50.499  4902  4902 D Mms/MmsApp: [end]    initCountryIso consume time = 10.509895
,03-17 07:10:50.499  4902  4902 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.526146
,03-17 07:10:50.499  4902  4902 D Mms/MmsConfig: before partial update
,03-17 07:10:50.509  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.509  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.509  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.509  1019  1230 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.519  4975  4975 E Zygote  : MountEmulatedStorage()
03-17 07:10:50.519  4975  4975 E Zygote  : v2
,03-17 07:10:50.519  4975  4975 I libpersona: KNOX_SDCARD checking this for 10094
03-17 07:10:50.519  4975  4975 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:50.519  4975  4975 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:50.519  4975  4975 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 07:10:50.519  4975  4975 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:50.519  1019  1230 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4975 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
03-17 07:10:50.519  1019  1230 I ActivityManager: Killing 4507:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,03-17 07:10:50.529  4902  4902 D Mms/MmsConfig: Load Resize quality : 80
,03-17 07:10:50.529  4902  4902 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-17 07:10:50.539  4902  4902 D EasySignUpManager_1.0.1: isAuth is false
,03-17 07:10:50.539  4902  4902 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-17 07:10:50.539  4975  4975 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:50.539  1501  1521 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4902
,03-17 07:10:50.539  4975  4975 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.539  1501  1521 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.807 ms
,03-17 07:10:50.549  4902  4902 D EasySignUpManager_1.0.1: isAuth is false
03-17 07:10:50.549  4902  4902 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-17 07:10:50.559  4902  4902 E CscParser: mps_code.dat does not exist
03-17 07:10:50.559  4902  4902 E CscParser: customer_path =/system/csc/customer.xml
03-17 07:10:50.559  4902  4902 E CscParser: fileName + /system/csc/customer.xml
,03-17 07:10:50.569  4902  4902 E CscParser: mps_code.dat does not exist
,03-17 07:10:50.569  4902  4902 E CscParser: customer_path =/system/csc/customer.xml
,03-17 07:10:50.569  4902  4902 E CscParser: fileName + /system/csc/customer.xml
,03-17 07:10:50.569  4975  4975 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,03-17 07:10:50.569  4975  4975 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 07:10:50.579  4975  4975 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-17 07:10:50.579  1019  3272 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.579  1019  3272 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.579  1019  3272 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:50.579  1019  3272 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 07:10:50.579  4975  4975 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-17 07:10:50.579  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.579  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.579  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.579  1019  1751 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.589  4902  4902 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-17 07:10:50.589  4902  4902 D Mms/MmsConfig:  enable multiwindow = true
,03-17 07:10:50.599  4991  4991 E Zygote  : MountEmulatedStorage()
,03-17 07:10:50.599  4991  4991 E Zygote  : v2
,03-17 07:10:50.599  4991  4991 I libpersona: KNOX_SDCARD checking this for 10134
03-17 07:10:50.599  4991  4991 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:50.599  4991  4991 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:50.599  4902  4902 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-17 07:10:50.599  4902  4902 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-17 07:10:50.599  4991  4991 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:50.599  4991  4991 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,03-17 07:10:50.599  1019  1751 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4991 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,03-17 07:10:50.609  4975  4975 D elm:15183: ElmAgentService : onCreate()
,03-17 07:10:50.609  4975  4994 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
03-17 07:10:50.609  4975  4994 D elm:15183: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,03-17 07:10:50.609  4975  4975 D elm:15183: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
03-17 07:10:50.609  4975  4975 D elm:15183: ModuleBase.ModifySetAlarm()
03-17 07:10:50.609  4975  4975 D elm:15183: MDMBridge.getInstance()
03-17 07:10:50.609  4975  4975 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 07:10:50.609  1019  1100 V AlarmManager: waitForAlarm result :8
03-17 07:10:50.609  4902  4902 D Mms/MmsConfig: [end]    init() consume time = 116.769531
,03-17 07:10:50.609  4902  4902 D Mms/Contact: [start]    init() consume time = 0.644167
,03-17 07:10:50.609  1019  1100 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:50.619  4975  4975 D elm:15183: ElmAgentService : onDestroy().
,03-17 07:10:50.619  1019  1241 I ActivityManager: Killing 4486:com.dropbox.android/u0a92 (adj 15): empty #31
,03-17 07:10:50.629  1501  3074 D TP/MmsSmsProvider: query,matched:13, calling pid = 4902
,03-17 07:10:50.629  1501  3074 D TP/MmsSmsProvider: match 13:Elapsed time : 2.567 ms,
,03-17 07:10:50.639  4991  4991 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:50.639  4991  4991 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.639  4902  4902 D Mms/Contact: [end]    init consume time = 29.916146
,03-17 07:10:50.649  4991  4991 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:50.649  4991  4991 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-17 07:10:50.649  1019  1043 W libprocessgroup: failed to open /acct/uid_10092/pid_4507/cgroup.procs: No such file or directory
,03-17 07:10:50.659  4902  5011 D Mms/DraftCache: [start]    rebuildCache consume time = 13.71026
,03-17 07:10:50.659  1501  1521 D TP/MmsSmsProvider: query,matched:12, calling pid = 4902
,03-17 07:10:50.669  4902  4902 D Mms/MethodReflector: getSubId is called
03-17 07:10:50.669  4902  4902 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 07:10:50.669  1501  1521 D TP/MmsSmsProvider: match 12:Elapsed time : 2.046 ms
,03-17 07:10:50.669  4902  4902 D Mms/MethodReflector: getTelephonyProperty is called
03-17 07:10:50.669  4902  4902 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 07:10:50.669  4902  4902 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 07:10:50.669  4902  4902 D Mms/DownloadManager: auto download without roaming -> true
03-17 07:10:50.669  4902  4902 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-17 07:10:50.669  4902  4902 D Mms/MethodReflector: getSubId is called
,03-17 07:10:50.669  4902  4902 D Mms/MethodReflector: getDefaultSmsSubId is called
03-17 07:10:50.669  4902  4902 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-17 07:10:50.669  4902  4902 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
03-17 07:10:50.669  4902  4902 D Mms/MethodReflector: getTelephonyProperty is called
03-17 07:10:50.669  4902  4902 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-17 07:10:50.669  4902  4902 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-17 07:10:50.669  4902  4902 D Mms/DownloadManager: auto download without roaming -> true
03-17 07:10:50.669  4902  4902 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-17 07:10:50.669  4902  4902 D Mms/DownloadManager: auto download during roaming secondary -> false
03-17 07:10:50.669  4902  4902 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 07:10:50.669  4902  5011 D Mms/DraftCache: [end]    rebuildCache consume time = 15.863646
,03-17 07:10:50.679  4902  4902 D ComposerPerformance: 1458195050688 ms / [DONE] Composer constructor
,03-17 07:10:50.679  1019  1367 I ActivityManager: Killing 3680:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-17 07:10:50.679  4902  5012 D Mms/Conversation: [start]    init() consume time = 10.974115
,03-17 07:10:50.689  1501  1515 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-17 07:10:50.689  1501  1515 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,03-17 07:10:50.689  1501  1515 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-17 07:10:50.689  4902  4902 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
03-17 07:10:50.689  4902  4902 I Mms/ReservationManager: ReservationManager()
,03-17 07:10:50.689  4902  4902 I Mms/ReservationManager: resetAfterConnected()
,03-17 07:10:50.699  1501  1515 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-17 07:10:50.699  1501  1748 D TP/MmsSmsProvider: query,matched:7, calling pid = 4902
,03-17 07:10:50.699  1501  1515 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 07:10:50.699  1501  1515 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:50.699  1501  1515 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 07:10:50.699  1501  1515 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:50.699  1501  1515 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 07:10:50.699  4902  4972 D Mms/ArtClassLoader: init [DONE] art
03-17 07:10:50.699  1501  1515 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 07:10:50.699  3153  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 14 sec
,03-17 07:10:50.699  1501  1748 D TP/MmsSmsProvider: match 7:Elapsed time : 5.876 ms
,03-17 07:10:50.709  4902  4902 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 07:10:50.709  1501  1515 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-17 07:10:50.709  1501  1515 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 07:10:50.709  4902  5012 D Mms/Conversation: [end]    init consume time = 28.855833,
03-17 07:10:50.709  4902  5012 D Mms/MessagingNotification: [start]    init() consume time = 1.199011
,03-17 07:10:50.719  4902  4902 D Mms/MmsApp: [end]    onCreate() consume time = 1.701718
,03-17 07:10:50.719  1019  3273 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,03-17 07:10:50.719  4902  4902 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,03-17 07:10:50.719  4902  4902 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
03-17 07:10:50.719  4902  5012 D Mms/MessagingNotification: [end]    init consume time = 0.778854
,03-17 07:10:50.719  1019  3273 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.719  1019  3273 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:50.719  4902  4902 D Mms/MethodReflector: getSubId is called
03-17 07:10:50.719  4902  4902 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 07:10:50.719  1019  3273 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
03-17 07:10:50.719  4902  4902 D Mms/MethodReflector: getTelephonyProperty is called
03-17 07:10:50.719  4902  4902 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 07:10:50.719  4902  4902 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 07:10:50.719  4902  4902 D Mms/DownloadManager: auto download without roaming -> true
03-17 07:10:50.719  4902  4902 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-17 07:10:50.719  4902  4902 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 07:10:50.719  4902  5013 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 5.208542
,03-17 07:10:50.719  1019  3273 I ActivityManager: Killing 4541:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,03-17 07:10:50.729  4902  5014 D Mms/Synchronizer: [start]    doSync consume time = 3.320521
,03-17 07:10:50.729  1501  1521 D TP/MmsSmsProvider: update, matched:300, calling pid = 4902
03-17 07:10:50.729  1501  1521 V TP/MmsSmsProvider: syncDBData start
,03-17 07:10:50.729  1501  1521 V TP/MmsSmsProvider: syncDBData sms end
03-17 07:10:50.729  1501  1515 D TP/MmsSmsProvider: query,matched:0, calling pid = 4902
03-17 07:10:50.729  1501  1515 V TP/MmsSmsProvider: getSimpleConversations entered.
,03-17 07:10:50.729  1501  1521 V TP/MmsSmsProvider: syncDBData mms end
,03-17 07:10:50.729  1501  1515 D TP/MmsSmsProvider: match 0:Elapsed time : 1.353 ms
,03-17 07:10:50.729  1501  1521 V TP/MmsSmsProvider: syncDBData end
,03-17 07:10:50.729  1501  1521 D TP/MmsSmsProvider: query,matched:400, calling pid = 4902
,03-17 07:10:50.729  4902  5014 D Mms/Synchronizer: [end]    doSync consume time = 8.482448
,03-17 07:10:50.739  4902  5013 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 3.382396
,03-17 07:10:50.739  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.739  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.739  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.739  1019  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.749  5015  5015 E Zygote  : MountEmulatedStorage(),
03-17 07:10:50.749  5015  5015 E Zygote  : v2
03-17 07:10:50.749  5015  5015 I libpersona: KNOX_SDCARD checking this for 10072
03-17 07:10:50.749  5015  5015 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:50.749  1019  1713 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5015 uid=10072 gids={50072, 9997} abi=armeabi-v7a,
,03-17 07:10:50.779  1019  1043 W libprocessgroup: failed to open /acct/uid_10092/pid_4486/cgroup.procs: No such file or directory
,03-17 07:10:50.809  5015  5015 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 07:10:50.809  5015  5015 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:50.809  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
03-17 07:10:50.809  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.809  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:50.809  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts,
03-17 07:10:50.809  1019  4037 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.809  1019  4037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:50.809  1019  4037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 07:10:50.819  5015  5015 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:50.819  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.819  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.829  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.829  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.829  1019  1241 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-17 07:10:50.829  1019  1241 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-17 07:10:50.829  1019  1241 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
03-17 07:10:50.829  1019  1241 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
03-17 07:10:50.829  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.829  1019  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.829  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.839  1695  5025 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-17 07:10:50.849  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.849  1019  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.849  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.849  1695  1695 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 07:10:50.859  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.859  1019  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.859  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.859  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.869  1019  1241 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:50.869  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.869  1970  1970 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-17 07:10:50.869  5015  5015 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:50.869  1019  1389 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.869  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.869  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.869  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.869  5015  5015 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.879   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 07:10:50.879  1019  1389 I ActivityManager: Killing 4579:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,03-17 07:10:50.879  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.879  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.879  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.889  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.889  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.889  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.899  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.899  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.899  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.899  1019  1043 W libprocessgroup: failed to open /acct/uid_10015/pid_3680/cgroup.procs: No such file or directory
03-17 07:10:50.899  1019  1043 W libprocessgroup: failed to open /acct/uid_10057/pid_4541/cgroup.procs: No such file or directory
,03-17 07:10:50.899  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.899  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.899  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.899  5015  5015 D BadgeProvider: onCreate
,03-17 07:10:50.899  5015  5015 D BadgeProvider: DatabaseHelper
,03-17 07:10:50.909  1019  1389 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.909  1019  1389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.909  1019  1389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.909  1811  5034 E MDM     : [210] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-17 07:10:50.909  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.909  1019  1367 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.909  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.919  1019  4037 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:50.919  1019  4037 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.919  1019  4037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.919  1019  4037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.919  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.919  1019  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.919  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.929  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.929  1019  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.929  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.929  1019  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 07:10:50.929  1019  1384 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.929  1019  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.929  1019  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.929  1970  5035 D LocationInitializer: Restart initialization of location
,03-17 07:10:50.929  1019  1751 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.929  1019  1751 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.929  1019  1751 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.929  1019  1751 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.939  1019  1713 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.939  1019  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.939  1019  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.949  4902  5012 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-17 07:10:50.949  1501  1515 D TP/SmsProvider: query,matched:26, calling pid = 4902
,03-17 07:10:50.949  1501  1515 D TP/SmsProvider: match 26:Elapsed time : 2.593 ms
,03-17 07:10:50.979  1019  1019 I ValidateNoPeople: mEvictionCount: 0
,03-17 07:10:50.979  4902  4902 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-17 07:10:50.979  4902  4902 D Mms/Contact: performUpdate:widgetCount=0
,03-17 07:10:50.989  4902  5037 D Mms/ContactsCache: [start]    invalidate() consume time = 249.872447
,03-17 07:10:50.989  4902  5037 D Mms/ContactsCache: [end]    invalidate() consume time = 0.855261
,03-17 07:10:51.009  1019  1043 W libprocessgroup: failed to open /acct/uid_10068/pid_4579/cgroup.procs: No such file or directory
,03-17 07:10:51.029  1019  1367 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,03-17 07:10:51.029  1019  1367 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:51.029  1019  1367 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 07:10:51.029  1019  1367 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-17 07:10:51.039  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:51.039  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:51.039  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,03-17 07:10:51.069  1019  2775 D SSRM:n  : SIOP:: AP = 400
,03-17 07:10:51.099  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.099  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.099  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.099  1019  1367 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.109  1019  1751 I art     : Explicit concurrent mark sweep GC freed 28828(1623KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 30MB/45MB, paused 2.598ms total 155.869ms
,03-17 07:10:51.119  5040  5040 E Zygote  : MountEmulatedStorage()
,03-17 07:10:51.119  5040  5040 E Zygote  : v2
,03-17 07:10:51.119  5040  5040 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:51.119  5040  5040 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:51.119  1501  3074 D TP/MmsSmsProvider: query,matched:6, calling pid = 4902
03-17 07:10:51.119  5040  5040 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:51.119  1501  3074 D TP/MmsSmsProvider: match 6:Elapsed time : 2.315 ms
,03-17 07:10:51.119  1019  1367 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5040 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:51.119  5040  5040 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:51.119  5040  5040 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:51.149  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.149  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.149  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.149  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.159  5057  5057 E Zygote  : MountEmulatedStorage(),
03-17 07:10:51.159  5057  5057 E Zygote  : v2
03-17 07:10:51.159  5057  5057 I libpersona: KNOX_SDCARD checking this for 10025
,03-17 07:10:51.159  5057  5057 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 07:10:51.159  5057  5057 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:51.159  5057  5057 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:51.159  5057  5057 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:51.169  5040  5040 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:51.169  5040  5040 D ActivityThread: Added TimaKeyStore provider,
03-17 07:10:51.169  1019  3273 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5057 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,03-17 07:10:51.189  5057  5057 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:51.189  5057  5057 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:51.189  5040  5040 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-17 07:10:51.199  1019  1751 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 07:10:51.199  1019  1751 D SecContentProvider2: mCursor = null
,03-17 07:10:51.199  1019  1230 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 07:10:51.199  1019  1230 D SecContentProvider2: mCursor = null
,03-17 07:10:51.199  5040  5040 V MTPRx   : sealedState: false
03-17 07:10:51.199  5040  5040 V MTPRx   : sealedUsbMassStorageState: false
03-17 07:10:51.199  5040  5040 E MTPRx   : check value of boot_completed is1
03-17 07:10:51.199  5040  5040 E MTPRx   : check booting is completed_sys.boot_completed
,03-17 07:10:51.199  5040  5040 E MTPRx   : Sd-Card path/storage/extSdCard
,03-17 07:10:51.199  5040  5040 E MTPRx   : Status for mount/Unmount :removed
03-17 07:10:51.199  5040  5040 E MTPRx   : SDcard is not available
,03-17 07:10:51.199  1019  1032 I ActivityManager: Killing 4597:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,03-17 07:10:51.209  5040  5040 W MTPRx   : value of connected istrue
03-17 07:10:51.209  5040  5040 W MTPRx   : value of configured istrue
03-17 07:10:51.209  5040  5040 W MTPRx   : value of mtpEnabled istrue
03-17 07:10:51.209  5040  5040 W MTPRx   : value of ptpEnabled isfalse
,03-17 07:10:51.209  5040  5040 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-17 07:10:51.219  5040  5040 E MTPRx   : mFirstTime: false
,03-17 07:10:51.219  5057  5057 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 07:10:51.229  5040  5040 D         : MTP: reading debug level property
,03-17 07:10:51.229  5040  5040 E MTPJNIInterface: Getting CryptionKey from JAVA
,03-17 07:10:51.229  5040  5040 E MTPRx   : currentUserId is 0
,03-17 07:10:51.229  5040  5040 E MTPRx   : Start observing USB_STATE_MATCH 
,03-17 07:10:51.229  5040  5040 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
,03-17 07:10:51.229  5040  5040 E MTPRx   : is_Privatemode is NOT 1
,03-17 07:10:51.239  1019  1230 D SettingsProvider: name = boot_time_connected
,03-17 07:10:51.239  5040  5040 E MTPRx   : Sending NORMAL_BOOT to stack
03-17 07:10:51.239  5040  5040 E MTPJNIInterface: noti = 17
,03-17 07:10:51.239  1019  4037 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 07:10:51.249  1019  1389 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-17 07:10:51.249  5040  5040 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-17 07:10:51.249  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-17 07:10:51.249  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:51.249  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:51.249  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 07:10:51.249  5057  5057 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-17 07:10:51.249  1019  1713 D SettingsProvider: name = mtp_running_status
,03-17 07:10:51.259  1019  1751 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 07:10:51.259  5040  5040 E MTPRx   : else part ... so first time!!!
,03-17 07:10:51.259  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:51.259  5040  5040 E MTPPlaObsrvr: inside setContext()
03-17 07:10:51.259  5040  5040 E MTPPlaObsrvr:  inside createplafiles
,03-17 07:10:51.279  1019  1043 W libprocessgroup: failed to open /acct/uid_10069/pid_4597/cgroup.procs: No such file or directory
,03-17 07:10:51.279  5040  5040 E MTPPlaObsrvr: playlist count is0
03-17 07:10:51.279  5040  5040 E MTPPlaObsrvr:  inside try branch createplafiles
,03-17 07:10:51.279  5040  5040 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-17 07:10:51.279  4902  5012 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-17 07:10:51.279  5040  5040 E MTPPlaObsrvr: Inside registerContentObserver
,03-17 07:10:51.279  5040  5040 E MtpAdbObserver: inside setContext()
,03-17 07:10:51.279  5040  5040 E MtpAdbObserver: Inside registerContentObserver
03-17 07:10:51.279  5040  5040 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-17 07:10:51.289  1019  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-17 07:10:51.289  1019  1032 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:51.289  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:51.289  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 07:10:51.289  1019  1554 D SettingsProvider: name = mtp_running_status
,03-17 07:10:51.289  5040  5075 V MtpMediaDBManager: inside deleteAllDB
03-17 07:10:51.289  1019  3272 D SettingsProvider: name = mtp_usb_conditions_met
03-17 07:10:51.289  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-17 07:10:51.289  5040  5040 E MtpService: onCreate.
,03-17 07:10:51.289  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,03-17 07:10:51.289  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-17 07:10:51.289  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-17 07:10:51.289  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-17 07:10:51.299  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-17 07:10:51.299  1019  1241 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
03-17 07:10:51.299  5040  5040 E MtpService: < MTP > Registering BroadCast receiver :::::
03-17 07:10:51.299  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,03-17 07:10:51.299  1019  1241 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:51.299  1019  1241 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:51.299  1019  1241 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 07:10:51.299  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,03-17 07:10:51.299  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-17 07:10:51.299  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-17 07:10:51.299  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-17 07:10:51.299  5040  5040 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
03-17 07:10:51.299  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-17 07:10:51.309  5057  5057 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-17 07:10:51.309  5040  5040 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-17 07:10:51.309  5040  5040 E MtpService: onStartCommand.
03-17 07:10:51.309  5040  5075 V MtpMediaDBManager: inside Thread updateDB
,03-17 07:10:51.309  1261  1261 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-17 07:10:51.319  5040  5040 W MTPRx   : calling native method
03-17 07:10:51.319  5040  5040 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-17 07:10:51.319  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.319  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.319  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.319  1019  3273 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.319  5040  5076 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-17 07:10:51.329  5077  5077 E Zygote  : MountEmulatedStorage()
03-17 07:10:51.329  5077  5077 E Zygote  : v2
03-17 07:10:51.329  5077  5077 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:51.329  5077  5077 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:51.329  5077  5077 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 07:10:51.339  5077  5077 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 07:10:51.339  5077  5077 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:51.349  1019  3273 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=5077 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:51.349  5040  5075 E MtpMediaDBManager: count : 27
03-17 07:10:51.349  5040  5040 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-17 07:10:51.349  5040  5040 E MTPJNIInterface: noti = 10
,03-17 07:10:51.349  5040  5040 E MtpService: onStartCommand.
,03-17 07:10:51.349  5040  5040 W MTPRx   : calling native method
03-17 07:10:51.349  5040  5040 E MTPRx   : Checking the driver time out
03-17 07:10:51.349  5040  5040 E MTPJNIInterface: noti = 2
,03-17 07:10:51.349  5040  5040 D         : deleting sockets before message queue initialization
03-17 07:10:51.349  5040  5040 D         : event handler thread is created, so set the flag
03-17 07:10:51.349  5040  5040 E MTPRx   : called native method
03-17 07:10:51.349  5040  5040 E MTPJNIInterface: setting Media scanner status0
03-17 07:10:51.349  5040  5040 E MTPJNIInterface: After setting Media scanner status0
,03-17 07:10:51.359  5040  5076 E MtpService: handleMessage. msg= { when=-4ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-17 07:10:51.359  3467  3467 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,03-17 07:10:51.359  5040  5040 W MTPRx   : notification from stack 1
,03-17 07:10:51.359  5040  5088 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-17 07:10:51.359  5040  5088 E MTPJNIInterface: Getting media scanner status0
,03-17 07:10:51.359  5040  5088 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A5)
,03-17 07:10:51.369  5077  5077 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:51.369  5077  5077 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:51.379  3467  5090 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 07:10:51.379  5040  5075 W MtpMediaDBManager: sending db update complete noti to stack
03-17 07:10:51.379  5040  5075 E MTPJNIInterface: noti = 29
,03-17 07:10:51.389  3467  5090 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 07:10:51.389  3467  5090 I ReactiveServiceManager: Supported : 1
,03-17 07:10:51.389  1019  1389 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-17 07:10:51.389  5040  5088 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 07:10:51.389  5040  5088 E MTPJNIInterface: SDcard is not available
03-17 07:10:51.389  1019  1389 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 07:10:51.409  1019  1389 D QSEECOMAPI: : Loaded image: APP id = 11
,03-17 07:10:51.409  5040  5088 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-17 07:10:51.409  5040  5088 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 07:10:51.419  5040  5088 E MTPJNIInterface: SDcard is not available
03-17 07:10:51.419  5040  5088 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 07:10:51.419  5040  5088 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-17 07:10:51.419  5040  5088 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 07:10:51.419  5040  5088 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 07:10:51.419  5040  5088 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 07:10:51.419  5040  5088 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 07:10:51.419  5040  5088 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 07:10:51.419  5040  5088 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-17 07:10:51.419  5040  5040 W MTPRx   : notification from stack 2
,03-17 07:10:51.419  1019  1389 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 07:10:51.419  1019  1389 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,03-17 07:10:51.419  1019  1389 E terrier : handleString: Failed to handle string(-4)
03-17 07:10:51.419  1019  1389 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-17 07:10:51.419  3467  5090 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 07:10:51.419  3467  5090 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 07:10:51.419  5040  5094 D         : [mtp_init_device] Library open with 32 bits.
03-17 07:10:51.419  5040  5094 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,03-17 07:10:51.419  5040  5094 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-17 07:10:51.419  5040  5094 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-17 07:10:51.419  5040  5094 E         :  [sua_support_present:1287] returning false 
03-17 07:10:51.419  5040  5094 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,03-17 07:10:51.419  3467  5090 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 07:10:51.419  3467  5090 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 07:10:51.419  3467  5090 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 07:10:51.419  3467  5090 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account

```
