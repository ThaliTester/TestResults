#### Test 62509094588eeb1_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
I/qcom-bluetooth( 3113): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
--------- beginning of system
D/UsbHostRestrictor( 1022): SIM was never inserted
D/UsbHostRestrictor( 1022): writableHostSysNode[false]
D/UsbHostRestrictor( 1022): Can NOT Write Disable Sys Node to [ON]
I/qcom-bluetooth( 3124): /system/etc/init.qcom.bt.sh: Transport : smd 
D/PersonaManagerService( 1022): ACTION_BOOT_COMPLETED
E/PersonaManagerServiceHandler( 1022):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
D/UsbStorageNotification( 1022): boot completed
I/qcom-bluetooth( 3127): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
D/StorageNotification( 1177): boot completed
D/GpsLocationProvider( 1022): receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
D/GpsLocationProvider_ex( 1022): BOOT_COMPLETED native_init 
D/KnoxKeyguardUpdateMonitor( 1022): onBootComplete
I/KnoxKeyguardUpdateMonitor( 1022): onTrustManagedChanged user 0, managed:false
I/KnoxKeyguardUpdateMonitor( 1022): onTrustChanged user:0, enable:false
D/KeyguardViewMediator( 1177): onTrustChanged( Showing = false , userId = 0 )
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
I/qcom-bluetooth( 3132): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,D/SensorService( 1022): [SO] currT = 38811044000, prevT = 38371103000, diff = 439941000, [-0.421 0.172 9.883]
D/SensorService( 1022): [SO] -0.421 0.172 9.883
D/SensorService( 1022): [SO] [100 -> 255]
I/qcom-bluetooth( 3133): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
I/qcom-bluetooth( 3134): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
D/GpsLocationProvider( 1022): set_capabilities_callback: 55u
I/qcom-bluetooth( 3135): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
E/LocSvc_api_v02( 1022): I/locClientOpen:2279]: Service instance id is -1
E/Geofence_Adapter( 1022): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
W/DriveInitializer( 2108): Background init thread ended
E/Geofence_Adapter( 1022): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
D/GpsLocationProvider_ex( 1022): BOOT_COMPLETED native_cleanup 
D/StatusBarManagerService( 1022): setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
D/PhoneStatusBar( 1177): updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3145): MountEmulatedStorage()
I/libpersona( 3145): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3145): v2
I/libpersona( 3145): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=3145 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3145): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3145): TimaSignature is unavailable
D/ActivityThread( 3145): Added TimaKeyStore provider
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ContextImpl( 3145): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.mobeam.barcodeService, destAppInfo.processName = com.mobeam.barcodeService
I/splitIntent( 1022): Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=87, mSplitNum[1]=126, mSplitNum[2]=164, mBgSplitQueueNum=3 divideNum= 37 r.nextReceiver= 50 receivers.size=201
I/splitIntent( 1022): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3165): MountEmulatedStorage()
E/Zygote  ( 3165): v2
I/libpersona( 3165): KNOX_SDCARD checking this for 10097
I/libpersona( 3165): KNOX_SDCARD not a persona
I/SELinux ( 3165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3165): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=3165 uid=10097 gids={50097, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/LocSvc_ApiV02( 1022): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/art     (  309): Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 20.876ms
E/LocSvc_ApiV02( 1022): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PREMIUM_SERVICES_CONFIG_REQ_V02
D/qmi_secgps_clnt( 1022): qmi_secgps_client_init()
D/TimaKeyStoreProvider( 3165): TimaSignature is unavailable
D/ActivityThread( 3165): Added TimaKeyStore provider
D/qmi_secgps_clnt( 1022): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
D/qmi_secgps_clnt( 1022): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
D/qmi_secgps_clnt( 1022): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.656ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.251ms
E/Zygote  ( 3186): MountEmulatedStorage()
E/Zygote  ( 3186): v2
I/libpersona( 3186): KNOX_SDCARD checking this for 10081
I/libpersona( 3186): KNOX_SDCARD not a persona
I/SELinux ( 3186): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=3186 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 3186): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3186): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/qcom-bluetooth( 3185): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/qcom-bluetooth( 3195): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3186): TimaSignature is unavailable
D/ActivityThread( 3186): Added TimaKeyStore provider
E/LocSvc_utils_cfg( 1022): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
E/Zygote  ( 3204): MountEmulatedStorage()
E/Zygote  ( 3204): v2
I/libpersona( 3204): KNOX_SDCARD checking this for 1101
I/libpersona( 3204): KNOX_SDCARD not a persona
E/LocSvc_ApiV02( 1022): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
I/ActivityManager( 1022): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3204 uid=1101 gids={41101, 9997} abi=armeabi-v7a
I/bt_vendor( 2994): bluetooth satus is on
D/bt_userial_mct( 2994): userial_open(port:0)
I/bt_vendor( 2994): bt-vendor : BT_VND_OP_USERIAL_OPEN
E/LocSvc_ApiV02( 1022): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
I/ActivityManager( 1022): Killing 2416:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
I/bt_vendor( 2994): Done intiailizing UART
I/bt_vendor( 2994): Done intiailizing UART
I/bt_userial_mct( 2994): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 2994): Bluetooth Firmware and transport layer are initialized
D/bt_userial_mct( 2994): Entering userial_read_thread()
E/LocSvc_ApiV02( 1022): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
I/qmi_secgps_clnt( 1022): SECGPS: Set AGPS Mode : 7
D/qmi_secgps_clnt( 1022): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1022): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/ActivityManager( 1022): Killing 2438:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
E/LocSvc_ApiV02( 1022): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
E/LocSvc_ApiV02( 1022): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1022): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 3204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/        ( 2994): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2994): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2994): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2994): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2994): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2994): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2994): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2994): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2994): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2994): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2994): BTE_InitTraceLevels -- TRC_SAP
I/        ( 2994): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2994): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2994): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2994): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2994): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 2994): BTE_InitTraceLevels -- TRC_PROTOCOL
I/SELinux ( 3204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3204): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/LocSvc_ApiV02( 1022): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
I/qmi_secgps_clnt( 1022): SECGPS: Set XTRA enable : 1
D/qmi_secgps_clnt( 1022): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1022): SECGPS: Set GNSS RF CONFIG : 1
W/ResourcesManager( 3186): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3186): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3186): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3186): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3186): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
D/qmi_secgps_clnt( 1022): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt( 1022): SECGPS: Set CERT TYPE : 15
D/qmi_secgps_clnt( 1022): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02( 1022): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
D/TimaKeyStoreProvider( 3204): TimaSignature is unavailable
D/ActivityThread( 3204): Added TimaKeyStore provider
W/ResourcesManager( 3204): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
V/DownloadManager( 1225): onReceive intent + android.intent.action.BOOT_COMPLETED
V/SmartcardService( 3204): main Received broadcast
V/SmartcardService( 3204): Starting smartcard service after boot completed
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
E/LocSvc_ApiV02( 1022): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02( 1022): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
E/LocSvc_ApiV02( 1022): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
D/SecContentProvider2( 1022): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1022): mCursor = null
E/LocSvc_ApiV02( 1022): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
E/LocSvc_ApiV02( 1022): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
I/ActivityManager( 1022): Killing 2359:com.sec.android.app.mt/1000 (adj 15): empty #31
W/bt-l2cap( 2994): l2c_link_processs_ble_num_bufs 16
E/bt-btm  ( 2994): BTM_SecRegister:p_cb_info->p_le_callback == 0xa4496ead 
E/bt-btm  ( 2994): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4496ead 
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_2438/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10127/pid_2416/cgroup.procs: No such file or directory
D/BluetoothAdapterProperties( 2994): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
E/Zygote  ( 3223): MountEmulatedStorage()
E/Zygote  ( 3223): v2
I/libpersona( 3223): KNOX_SDCARD checking this for 1000
I/libpersona( 3223): KNOX_SDCARD not a persona
I/SELinux ( 3223): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3223): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/bt-btif ( 2994): Calling BTA_HhEnable
I/ActivityManager( 1022): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=3223 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3223): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/bt-btif ( 2994): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties( 2994): Address is:08:EC:A9:50:76:27
E/BluetoothServiceJni( 2994): populateRssiValuesNative
I/bluedroid( 2994): getModelRssiValues
E/BluetoothServiceJni( 2994): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 2994): modelRssiValuesCallback, low, mid, high = -70,-60,127
D/BluetoothAdapterProperties( 2994): Name is: Thali Test (Galaxy A3)
D/SettingsProvider( 1022): name = bluetooth_name
D/BluetoothAdapterProperties( 2994): Scan Mode:20
D/BluetoothAdapterProperties( 2994): Discoverable Timeout:120
D/BluetoothAdapterProperties( 2994): LE Address is:C8:D9:53:A0:EC:4E
E/bt-btif ( 2994): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2994): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 2994): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 2994): btif_sock_init: !vhci_init
D/IOP_DB_BT( 2994): db_open: file /etc/bluetooth/iop_bt.db
E/bt_mct  ( 2994): hci lib postload completed
D/IOP_DB_BT( 2994): db_open: db_open : handle 3028647952l, read 13894 bytes onto local cache
D/TimaKeyStoreProvider( 3223): TimaSignature is unavailable
D/IOP_DB_BT( 2994): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 2994): db_query: result 1
D/ActivityThread( 3223): Added TimaKeyStore provider
I/        ( 2994): iop_db_open: iop_db_open status 0
D/bte_conf( 2994): Device ID record 1 : primary
D/bte_conf( 2994):   vendorId            = 0075
D/bte_conf( 2994):   vendorIdSource      = 0001
D/bte_conf( 2994):   product             = 0100
D/bte_conf( 2994):   version             = 0200
D/bte_conf( 2994):   clientExecutableURL = 
D/bte_conf( 2994):   serviceDescription  = 
D/bte_conf( 2994):   documentationURL    = 
D/bte_conf( 2994): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 2994): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 2994): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2994): ScanMode =  20
D/BluetoothAdapterProperties( 2994): State =  11
D/SecContentProvider( 1022): uri = 3 selection = isDiscoverableEnabled
D/BluetoothAdapterProperties( 2994): Setting state to 12
I/BluetoothAdapterState( 2994): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties( 2994): Scan Mode:21
D/BluetoothAdapterProperties( 2994): Discoverable Timeout:120
D/SettingsProvider( 1022): name = bluetooth_a2dp_sink_mode
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 1002
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1022): ret = -1
W/ContextImpl( 3223): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
W/BackupManagerService( 1022): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/BluetoothAdapterService( 2994): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2994): updateAdapterState state is 12
D/SSRM:a  ( 1022): DeviceInfo:: 000000000000
D/SSRM:a  ( 1022): SettingsAirViewInfo:: 000000000
W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_2359/cgroup.procs: No such file or directory
E/Zygote  ( 3245): MountEmulatedStorage()
I/libpersona( 3245): KNOX_SDCARD checking this for 10153
E/Zygote  ( 3245): v2
I/libpersona( 3245): KNOX_SDCARD not a persona
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
I/SELinux ( 3245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3245 uid=10153 gids={50153, 9997} abi=armeabi-v7a
I/SELinux ( 3245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3245): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapterService( 2994): Autoconnection is available 
D/MediaScannerReceiver( 1225): action: android.intent.action.BOOT_COMPLETED
D/BluetoothAdapterService( 2994): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 2994): starting service from this receiver
D/SettingsProvider( 1022): name = next_alarm_formatted
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 10081
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1022): ret = -1
I/BluetoothAdapterState( 2994): Entering On State from state = 11
D/BluetoothAdapter( 1177): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1177): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1839): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1839): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1456): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1456): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 2994): onBluetoothStateChange: up=true
D/BluetoothAdapter( 2994): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 1463): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1463): onBluetoothStateChange: Bluetooth is on
I/BluetoothPbapService( 2994): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
I/BluetoothPbapService( 2994): Handler(): got msg=1
D/BluetoothAdapter( 1446): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1446): onBluetoothStateChange: Bluetooth is on
D/BluetoothA2dp( 1022): onBluetoothStateChange: up=true
D/SecContentProvider( 1022): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/BluetoothA2dp( 2994): onBluetoothStateChange: up=true
E/ActivityThread( 3165): Failed to find provider info for flipboard.auth.internal.debug
E/ActivityThread( 3165): Failed to find provider info for flipboard.auth.internal
D/BluetoothAdapter( 1022): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1022): onBluetoothStateChange: Bluetooth is on
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3245): TimaSignature is unavailable
D/ActivityThread( 3245): Added TimaKeyStore provider
E/Zygote  ( 3260): MountEmulatedStorage()
E/Zygote  ( 3260): v2
I/libpersona( 3260): KNOX_SDCARD checking this for 10096
I/SELinux ( 3260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3260): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Start proc flipboard.app for content provider flipboard.app/flipboard.remoteservice.UserContentProvider: pid=3260 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/BackupManagerService( 1022): dataChanged but no participant pkg='com.android.providers.settings' uid=10081
W/InputMethodManagerService( 1022): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1022): [BT Setting State] State =12
I/InputMethodManagerService( 1022): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/SELinux ( 3260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
V/BluetoothPbapService( 2994): PBAP Service initSocket try: 0
E/SELinux ( 3260): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
I/SamsungIME( 1895): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothTile( 1177):  onBluetoothStateChange:
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/BluetoothMapMasInstance( 2994): set MAP SDP message type : 1
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 12
D/BluetoothHeadset( 1446): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@355650c5, true
D/BluetoothHeadset( 1446): registerMessageListener
D/HeadsetService( 2994): registerMessageListener
D/HeadsetService( 2994): registerMessageListener
D/HeadsetStateMachine( 2994): Disconnected process message: 70
D/HeadsetStateMachine( 2994): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@e924c1f
W/BluetoothAdapter( 2994): getBluetoothService() called with no BluetoothManagerCallback
I/Telecom ( 1446): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1446): BluetoothPhoneService: updateHeadsetWithCallState
W/BluetoothAdapter( 2994): getBluetoothService() called with no BluetoothManagerCallback
D/StatusBarManagerService( 1022): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
D/BluetoothSocket( 2994): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 2994): bindListen(), new LocalSocket 
D/BluetoothSocket( 2994): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2994): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6760b6c
D/BluetoothSocket( 2994): channel: 5
D/BluetoothSocket( 2994): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
D/BluetoothSocket( 2994): bindListen(), new LocalSocket 
D/BluetoothSocket( 2994): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 2994): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3945f535
D/BluetoothSocket( 2994): channel: 19
D/BluetoothPbapService( 2994): PBAP Socket is BluetoothServerSocket
D/StatusBarManagerService( 1022): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
I/Telecom ( 1446): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
I/Telecom ( 1446): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
I/Telecom ( 1446): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/HeadsetStateMachine( 2994): Disconnected process message: 9
D/HeadsetStateMachine( 2994): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/TimaKeyStoreProvider( 3260): TimaSignature is unavailable
D/ActivityThread( 3260): Added TimaKeyStore provider
W/ResourcesManager( 3245): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/audio_hw_primary(  286): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  286): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  286): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  286): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  286): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  286): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  286): adev_set_parameters: exit
E/HeadsetStateMachine( 2994): terminateScoUsingVirtualVoiceCall:No present call to terminate
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
D/AndroidRuntime( 3146): 
D/AndroidRuntime( 3146): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 3146): CheckJNI is OFF
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 3146): readGMSProperty: start
D/AndroidRuntime( 3146): readGMSProperty: already setted!!
D/AndroidRuntime( 3146): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3146): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3146): readGMSProperty: end
D/AndroidRuntime( 3146): addProductProperty: start
E/Zygote  ( 3279): MountEmulatedStorage()
E/Zygote  ( 3279): v2
I/libpersona( 3279): KNOX_SDCARD checking this for 1000
I/libpersona( 3279): KNOX_SDCARD not a persona
I/SELinux ( 3279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3279 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1022): Killing 2484:com.wsomacp/u0a23 (adj 15): empty #31
I/SELinux ( 3279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3279): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3279): TimaSignature is unavailable
D/ActivityThread( 3279): Added TimaKeyStore provider
I/MultiDex( 3260): VM with version 2.1.0 has multidex support
I/MultiDex( 3260): install
I/MultiDex( 3260): VM has multidex support, MultiDex support library is disabled.
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/MediaScannerService( 1225): !@start scanning volume internal: [/system/media, /oem/media]
E/Zygote  ( 3295): MountEmulatedStorage()
E/Zygote  ( 3295): v2
I/libpersona( 3295): KNOX_SDCARD checking this for 10155
I/libpersona( 3295): KNOX_SDCARD not a persona
I/SELinux ( 3295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3295): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3295 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
W/art     ( 3186): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 196.884ms
I/ActivityManager( 1022): Killing 2527:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/ActivityManager( 1022): Killing 2549:com.sec.android.app.camera/u0a135 (adj 15): empty #31
D/MtpService( 1225): updating state; isCurrentUser=true, mMtpLocked=false
I/DrmEventReceiver( 1022): DrmEventReceiver : onReceive
I/DrmEventReceiver( 1022): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
I/DrmEventReceiver( 1022): DrmEventReceiver : beginStartingService
I/System.out( 1022): start Service
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
D/TP/MmsProvider( 1463): Update uri=content://mms, match=0
D/TP/MmsProvider( 1463): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1463): need read changed broadcast:false
I/Mms:transaction( 2389): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
D/Mms/MessagingNotification( 2389): [start]    nonBlockingUpdateMessageIndicator() consume time = 8353.570778
I/Mms/ReservationManager( 2389): resetAfterConnected()
D/TimaKeyStoreProvider( 3295): TimaSignature is unavailable
D/ActivityThread( 3295): Added TimaKeyStore provider
D/Mms/MessagingNotification( 2389): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2389): isDefault true
D/TP/MmsProvider( 1463): Query uri=content://mms, match=0, calling pid = 2389
D/TP/MmsSmsProvider( 1463): query,matched:7, calling pid = 2389
D/TP/MmsSmsProvider( 1463): match 7:Elapsed time : 3.946 ms
I/Mms/ReservationManager( 2389): getReservedSendMessageCount(): retMessageCount=0
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
W/ResourcesManager( 3295): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/TP/MmsSmsProvider( 1463): query,matched:200, calling pid = 2389
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 1463): match 200:Elapsed time : 0.970 ms
E/Zygote  ( 3322): MountEmulatedStorage()
E/Zygote  ( 3322): v2
I/libpersona( 3322): KNOX_SDCARD checking this for 10043
I/libpersona( 3322): KNOX_SDCARD not a persona
I/SELinux ( 3322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3322 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 3322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3322): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/Mms/SmsReceiverService( 2389): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
D/Mms/TelephonyPermission( 2389): isDefault true
D/Mms/SmsReceiverService( 2389): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2389): [start]    handleBootCompleted() consume time = 61.239844
D/TimaKeyStoreProvider( 3322): TimaSignature is unavailable
D/ActivityThread( 3322): Added TimaKeyStore provider
D/WVMDrmPlugIn(  285): WVMDrmPlugin::onInitialize : 1719
W/ResourcesManager( 3322): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3322): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3322): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
D/WVMDrmPlugIn(  285): WVMDrmPlugin::onSetOnInfoListener : add 1719
E/SQLiteLog( 1225): (283) recovered 298 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
W/libprocessgroup( 1022): failed to open /acct/uid_10023/pid_2484/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10135/pid_2549/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10139/pid_2527/cgroup.procs: No such file or directory
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3260): Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3260): Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
D/[0]UMC:Core( 3295): onCreate(): 
D/TP/MmsSmsProvider( 1463): getThreadUnReadCount unreadCount=0 imUnreadCount=0
D/TP/MmsSmsProvider( 1463): deleteConversation threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1463): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1463): updateThread(), thread_id = 9223372036854775806
D/[0]UMC:DeviceInfo( 3295): USA==US==
V/TP/MmsSmsDatabaseHelper( 1463): sUpgradeVersion = 0, db.getVersion() = 81
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
I/TimaServiceEventReceiver( 1022): TimaServiceEventReceiver : onReceive
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
I/DrmEventService( 1022): action event :android.intent.action.BOOT_COMPLETED
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1463): (284) automatic index on im_threads(normal_thread_id)
I/ANDROID_DRM_FRWORKS_DrmManager(  285): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
E/CscReceiver( 1463): onReceive android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1022): name = block_emergency_message
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 10043
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1022): ret = -1
W/ActivityManager( 1022): getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
I/System.out( 3260): Reading bundled version for config.json
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
I/art     ( 1463): Explicit concurrent mark sweep GC freed 35076(2MB) AllocSpace objects, 5(80KB) LOS objects, 45% free, 4MB/8MB, paused 4.803ms total 186.098ms
D/TP/SmsProvider( 1463): query,matched:0, calling pid = 2389
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/CscUpdateService( 1463): onStart
D/USER_AGENT( 3295): UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
E/CscUpdateService( 1463): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1463): set_CSC_version
E/CscParser( 1463): update(): xml file exist
D/[0]UMC:AdminManager( 3295): init - start
D/[0]UMC:AdminManager( 3295): loadAdmins
I/ActivityManager( 1022): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3362 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
D/TP/SmsProvider( 1463): match 0:Elapsed time : 31.954 ms
E/Zygote  ( 3362): MountEmulatedStorage()
I/libpersona( 3362): KNOX_SDCARD checking this for 10002
E/Zygote  ( 3362): v2
I/libpersona( 3362): KNOX_SDCARD not a persona
I/SELinux ( 3362): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/[0]UMC:AdminManager( 3295): init - end
D/GSLBManager( 3295): migrateStoredUrlFromOldPref
I/SELinux ( 3362): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3362): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/CscUtil ( 1463): isWifiOnly = false
I/System.out( 1463): HandDataNode = null
I/CscUpdateService( 1463): PATH_CSCNAME =CustomerDataSet.CSCName
I/WifiCredService( 1313): onCreate
I/CscUpdateService( 1463): This is normal boot : CSC not updated
D/TP/SmsProvider( 1463): query,matched:51, calling pid = 2389
D/TP/SmsProvider( 1463): match 51:Elapsed time : 4.647 ms
D/GSLBManager( 3295): migrateStoredUrlFromOldPref : Migration Not Needed
D/TimaKeyStoreProvider( 3362): TimaSignature is unavailable
D/ActivityThread( 3362): Added TimaKeyStore provider
D/WifiTimerReceiver( 1313): action: android.intent.action.BOOT_COMPLETED
D/WifiTimerReceiver( 1313): extra: Bundle[mParcelledData.dataSize=84]
D/MY_TAG  ( 1313): Action boot completed received
D/[0]UMC:UMCAdmin( 3295): deactivateUMCAdminIfNotRequired : -1
E/CscParser( 1463): update(): xml file exist
D/WifiCredService( 1313): Action received :android.net.wifi.WIFI_STATE_CHANGED
E/WifiStateMachine( 1022): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1022): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1022): invaild command id : 215
E/[0]UMC:Utils( 3295): Admin not found in package com.samsung.knoxpb.mdm
D/TP/MmsSmsProvider( 1463): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1463): need read changed broadcast:false
D/CscGPS  ( 1463): CSCGPS.updateParameters
D/CscGPS  ( 1463): supl host : null
D/CscGPS  ( 1463): SUPL Host is null or invalid
D/CscGPS  ( 1463): supl_ver : null
D/CscGPS  ( 1463): SUPL Ver is null or invalid
D/CscGPS  ( 1463): supl port : null
D/CscGPS  ( 1463): SUPL PORT is null or invalid
D/CscGPS  ( 1463): LPP : null
D/CscGPS  ( 1463): LPP is null or invalid
D/CscGPS  ( 1463): CSC don't have any AGPS value.
E/[0]UMC:Utils( 3295): Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
D/[0]UMC:UMCAdmin( 3295): deactivateUMCAdmin : -1
D/[0]UMC:UMCAdmin( 3295): isContainer : 0
D/Mms/Conversation( 2389): deleteTempConversation(),deleted=0
D/SmsProvider( 1463): Update uri=content://sms/outbox, match=8
D/Mms/MessagingNotification( 2389): isBlockingModeEnabled() = false, Zen mode = 0
D/TP/MmsSmsProvider( 1463): need read changed broadcast:false
D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
I/CscUpdateService( 1463): same CSC Version
D/CscUtil ( 1463): Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
D/EnterpriseDeviceManagerService( 1022): isManagedProfileUser(): userId = 0
D/SettingsProvider( 1022): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
D/Mms/SmsReceiverService( 2389): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2389): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2389): [SIM-1]sendFirstQueuedMessage()
E/[0]UMC:UMCAdmin( 3295): No active admin owned by uid 10155
D/[0]UMC:UMCAdmin( 3295): isContainer : 0
D/[0]UMC:UMCAdmin( 3295): deactivateUMCAdmin - UMC App Admin deactivated
D/TP/SmsProvider( 1463): query,matched:26, calling pid = 2389
E/AffinityControl( 3146): AffinityControl: registerfunction enter
W/ActivityManager( 1022): userId = 0, bbcId = -10000
I/System.out( 3260): Reading bundled version for services.json
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
D/[0]UMC:CoreReceiver( 3295): Intent : android.intent.action.BOOT_COMPLETED
D/[0]UMC:CoreReceiver( 3295):  check PreETag 
D/TP/SmsProvider( 1463): match 26:Elapsed time : 4.119 ms
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
I/System.out( 3260): Reading bundled version for dynamicStrings.json
D/MediaScanner( 1225): Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
D/AndroidRuntime( 3146): Calling main entry com.android.commands.am.Am
E/Zygote  ( 3389): MountEmulatedStorage()
I/libpersona( 3389): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3389): v2
I/libpersona( 3389): KNOX_SDCARD not a persona
I/SELinux ( 3389): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
E/flip    ( 3260): [ERROR:4] Removing local copy of remote dynamicStrings.json: exception=java.io.IOException: invalid JSON, unexpected EOF in string
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
I/SELinux ( 3389): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/SELinux ( 3389): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/ActivityManager( 1022): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3389 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/System.out( 3260): Parsed section Cover Stories, private: false
E/PersonaManagerService( 1022): inState():  stateMachine is null !!
I/PersonaManagerService( 1022): PersonaId don't exist
I/ActivityManager( 1022): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/TimaKeyStoreProvider( 3389): TimaSignature is unavailable
D/ActivityThread( 3389): Added TimaKeyStore provider
E/SMD     (  291): DCD OFF
D/CustomFrequencyManagerService( 1022): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1022): mDVFSHelper.acquire()
D/FocusedStackFrame( 1022): Set to : 0
D/Launcher.HomeView( 1499): onPause
D/Launcher( 1499): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1022): Focused application set to: xxxx
D/InputDispatcher( 1022): Focus left window: 1499
D/PhoneWindow( 1022): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1022): *FMB* installDecor flags : -2122120936
D/Mms/SmsReceiver( 2389): unregisterForServiceStateChanges, already unregistered
D/AndroidRuntime( 3146): Shutting down VM
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
D/Mms/MessagingNotification( 2389): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2389): isDefault true
I/NearbySettings( 1313): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1313): MountReceiver.onReceive - Internal Path
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, uhalitest
V/MediaScanner( 1225): processDirectory :  /system/media
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3411): MountEmulatedStorage()
I/libpersona( 3411): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3411): v2
I/libpersona( 3411): KNOX_SDCARD not a persona
I/SELinux ( 3411): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3411): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1022): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3411 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3411): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
I/art     (  309): Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 648us total 20.885ms
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
I/art     ( 1022): Explicit concurrent mark sweep GC freed 57977(3MB) AllocSpace objects, 26(881KB) LOS objects, 33% free, 22MB/33MB, paused 10.845ms total 240.475ms
D/TimaKeyStoreProvider( 3411): TimaSignature is unavailable
D/ActivityThread( 3411): Added TimaKeyStore provider
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 19.735ms
D/BadgeProvider( 1591): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
I/GAV2    ( 2797): Thread[GAThread,5,main]: No campaign data found.
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 18.463ms
D/[0]UMC:ByodSetupStarter( 3295): Container ID : 0
V/MediaScanner( 1225):  prescan time: 522ms (DB items: 138)
V/MediaScanner( 1225):     scan time: 96ms (Caching mode: true), (makeEntry time: 24ms ~25%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1225): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1225):    total time: 618ms
V/MediaScanner( 1225): checked files: 130  directories : 6  (I: 0, U: 0)
D/MediaScanner( 1225): checkDefaultSounds
D/MediaScanner( 1225): system alarm_alert  : Vwiurug_etwofi5wgg
E/Zygote  ( 3428): MountEmulatedStorage()
E/Zygote  ( 3428): v2
I/libpersona( 3428): KNOX_SDCARD checking this for 10167
I/libpersona( 3428): KNOX_SDCARD not a persona
I/SELinux ( 3428): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3428 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3428): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3428): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
V/[0]UMC:Utils( 3295): checkAppScreen() : com.test.thalitest
I/[0]UMC:Core( 3295): shutdown
D/MediaScanner( 1225): OK. alarm_alert is already exist in setting DB.
I/art     ( 3295): System.exit called, status: 0
I/AndroidRuntime( 3295): VM exiting with result code 0, cleanup skipped.
D/MediaScanner( 1225): system notification_sound  : K_Oprkltf5wgg
D/SettingsProvider( 1022): name = personal_mode_enabled
D/MediaScanner( 1225): OK. notification_sound is already exist in setting DB.
D/TP/MmsProvider( 1463): Query uri=content://mms, match=0, calling pid = 2389
D/MediaScanner( 1225): system ringtone  : Wmfi_lpf_pwirywu5wgg
W/ResourcesManager( 3411): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 3428): TimaSignature is unavailable
D/ActivityThread( 3428): Added TimaKeyStore provider
I/ActivityManager( 1022): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3295)(adj 0) has died(38,633)
V/WindowOrientationListener( 1022): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1022): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/BadgeProvider( 1591): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1591): sendNotify, [notify] : null
D/BadgeProvider( 1591): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1591): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1591): update, [UpdateCount] : 1
V/WindowOrientationListener( 1022): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/daemonapp( 1816): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1816): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
V/ActivityThread( 1499): updateVisibility : ActivityRecord{45058ca token=android.os.BinderProxy@20702cc6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.Model( 1499): reloadBadges entered.
D/Launcher.HomeView( 1499): onStop
D/Launcher( 1499): onTrimMemory. Level: 20
V/ActivityThread( 1499): updateVisibility : ActivityRecord{45058ca token=android.os.BinderProxy@20702cc6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/MediaScanner( 1225): OK. ringtone is already exist in setting DB.
D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1022): isKioskContainerExistOnDevice
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/daemonapp( 1816): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1816): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1816): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/Mms/MessagingNotification( 2389): setBadgeCount(), count=0
W/art     ( 3146): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
D/daemonapp( 1816): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/Mms/MessagingNotification( 2389): remove alarm
D/comsamsunglog( 1816): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1816): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
E/SQLiteLog( 3389): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
D/MediaScannerService( 1225): !@done scanning volume internal
D/comsamsunglog( 1816): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1816): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1816): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1816): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1022): [SO] activate (ident=0xb90859d0, enabled=0)
I/Sensors ( 1022): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/FactoryTestApp( 2962): [DummyFtClient$mBroadcastReceiver](2962) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 2962): [DummyFtClient$mBroadcastReceiver](2962) ACTION_MEDIA_SCANNER_FINISHED = /system/media
D/FactoryTestApp( 2962): [DummyFtClient$mBroadcastReceiver](2962) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,D/SettingsProvider( 1022): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 10157
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1022): ret = -1
,D/SensorManager( 1022): unregisterListener ::   
,I/Sensors ( 1022): AccelerometerSensor(0) setDelay : 66000000(ns)
,W/BackupManagerService( 1022): dataChanged but no participant pkg='com.android.providers.settings' uid=10157
,D/SensorService( 1022): [SO] changed settle time [1]
D/SensorService( 1022): [SO] setDelay [66000000]
D/SensorService( 1022): [SO] activate (ident=0xb90859d0, enabled=1)
D/SensorService( 1022): [SO] AR_init
I/Sensors ( 1022): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/Mms/MessagingNotification( 2389): updateAllHistoryAsRead()
,D/daemonapp( 1816): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/SensorManager( 1022): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,W/ResourcesManager( 1463): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 1463): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1463): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TP/SmsProvider( 1463): query,matched:0, calling pid = 2389
,D/TP/MmsSmsProvider( 1463): query,matched:200, calling pid = 2389
D/daemonapp( 1816): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/TP/SmsProvider( 1463): match 0:Elapsed time : 2.147 ms
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1816): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1816): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1816): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/TP/MmsSmsProvider( 1463): match 200:Elapsed time : 13.407 ms
,D/daemonapp( 1816): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/Zygote  ( 3447): MountEmulatedStorage()
E/Zygote  ( 3447): v2
I/libpersona( 3447): KNOX_SDCARD checking this for 10082
I/libpersona( 3447): KNOX_SDCARD not a persona
,I/SELinux ( 3447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1022): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3447 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3447): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/daemonapp( 1816): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/ActivityManager( 1022): Killing 2609:com.sec.pcw.device/1000 (adj 15): empty #31
,D/DSM     ( 3389): [Lines:107] Normal booted
D/DSM     ( 3389): [Lines:114] Boot completed
,D/daemonapp( 1816): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/MediaScannerService( 1225): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
D/daemonapp( 1816): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1457959154327
,D/daemonapp( 1816): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1457980740000
D/daemonapp( 1816): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1816): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,I/SmartcardBootCompleteReceiver( 1313): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1313): Received intent with action - android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3447): TimaSignature is unavailable
,D/ActivityThread( 3447): Added TimaKeyStore provider
,E/Zygote  ( 3462): MountEmulatedStorage()
E/Zygote  ( 3462): v2
I/libpersona( 3462): KNOX_SDCARD checking this for 1000
I/libpersona( 3462): KNOX_SDCARD not a persona
D/SensorService( 1022): [SO] Reset Rotation Old [100], Init [1]
,I/SELinux ( 3462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3462): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3462 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1022): Killing 2732:com.sec.android.soagent/u0a31 (adj 15): empty #31
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started
,D/daemonapp( 1816): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1457980740000
W/ContextImpl( 1313): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
D/TimaKeyStoreProvider( 3462): TimaSignature is unavailable
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityThread( 3462): Added TimaKeyStore provider
,I/SmartcardBootCompleteReceiver( 1313): Broadcast sent with current lockscreen type
,D/daemonapp( 1816): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/daemonapp( 1816): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1457980740000
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1225): savePlaylistTableInBulkDeleter finished
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
D/Mms/MessagingNotification( 2389): [end]    nonBlockingUpdateMessageIndicator() consume time = 863.82927
W/ResourcesManager( 3462): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/SensorService( 1022): [SO] -0.402 0.172 9.883
D/SensorService( 1022): [SO] [100 -> 255]
,D/MediaScanner( 1225): Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/TP/SmsProvider( 1463): query,matched:0, calling pid = 2389
,D/TP/SmsProvider( 1463): match 0:Elapsed time : 3.371 ms
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_2609/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10031/pid_2732/cgroup.procs: No such file or directory
,D/TP/SmsProvider( 1463): query,matched:51, calling pid = 2389
,D/TP/SmsProvider( 1463): match 51:Elapsed time : 3.073 ms
,D/comdaemonstockapp( 1816): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 1816): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,V/MediaScanner( 1225): processDirectory :  /storage/emulated/0
,D/MediaScanner( 1225): Skipping:
D/MediaScanner( 1225): 7klwibgf7fvntblfd7(75ebcf7
,D/[SBeam] ( 1313): SBeamEnabler.initPreferenceForSbeam : 0
,D/Mms/MessagingNotification( 2389): isBlockingModeEnabled() = false, Zen mode = 0
,D/BadgeProvider( 1591): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,I/iu.UploadsManager( 2108): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,W/ActivityThread( 3462): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
,I/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
,I/SettingSearch/SearchIntentReceiver( 1313): action : android.intent.action.BOOT_COMPLETED
,I/SettingSearch/SearchIntentReceiver( 1313): search setting db init!!
,I/WebViewFactory( 3428): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/MediaScanner( 1225): Skipping:
D/MediaScanner( 1225): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,V/MediaScanner( 1225): processDirectory :  /storage/extSdCard
W/MediaScanner( 1225): Error opening directory, reason : Permission denied.
W/MediaScanner( 1225): 7klwibgf7fxlKdCbid7
,D/Launcher.Model( 1499): reloadBadges entered.
D/BadgeProvider( 1591): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1591): sendNotify, [notify] : null
D/BadgeProvider( 1591): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1591): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1591): update, [UpdateCount] : 1
,V/MediaScanner( 1225):  prescan time: 68ms (DB items: 26),
,V/MediaScanner( 1225):     scan time: 106ms (Caching mode: true), (makeEntry time: 23ms ~21%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1225): postscan time: 6ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1225):    total time: 180ms
V/MediaScanner( 1225): checked files: 10  directories : 16  (I: 0, U: 0)
,W/ContextImpl( 1313): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 ,
,E/Zygote  ( 3483): MountEmulatedStorage(),
E/Zygote  ( 3483): v2
I/libpersona( 3483): KNOX_SDCARD checking this for 10161,
I/libpersona( 3483): KNOX_SDCARD not a persona
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER,
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC,
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
I/ActivityManager( 1022): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3483 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,I/SELinux ( 3483): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
I/SELinux ( 3483): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
E/SELinux ( 3483): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
D/Mms/MessagingNotification( 2389): setBadgeCount(), count=0
D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,D/LcdtestApp( 3462): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,D/Mms/MessagingNotification( 2389): remove alarm
,I/LcdtestApp( 3462): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,I/LibraryLoader( 3428): Loading: webviewchromium
D/MediaScannerService( 1225): !@done scanning volume external
,D/FactoryTestApp( 2962): [DummyFtClient$mBroadcastReceiver](2962) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,D/FactoryTestApp( 2962): [DummyFtClient$mBroadcastReceiver](2962) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/TimaKeyStoreProvider( 3483): TimaSignature is unavailable
,D/ActivityThread( 3483): Added TimaKeyStore provider
,D/FactoryTestApp( 2962): [DummyFtClient$sendBootCompletedAndFinish](2962) ...
,I/LibraryLoader( 3428): Time to load native libraries: 8 ms (timestamps 803-811)
I/LibraryLoader( 3428): Expected native library version number "",actual native library version number ""
I/SettingSearch/SearchIntentReceiver( 1313): BOOT_COMPLETED call InitSerachDBThread thread start!
,I/DIAGMON_AGENT( 2893): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
D/FactoryTestApp( 2962): [Support$Values.getString](2962) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 2962): [ModuleCommon$isConnectionModeNone](2962) mConnectionMode = gsm
,D/FactoryTestApp( 2962): [IPCWriterToSecPhoneService$ResponseWriter](2962) Create IPCWriterToSecPhoneService
,I/FactoryTestApp( 2962): [IPCWriterToSecPhoneService$connectToSecPhoneService](2962)  
I/DIAGMON_AGENT( 2893): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 2893): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,I/DIAGMON_AGENT( 2893): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/Mms/MessagingNotification( 2389): updateAllHistoryAsRead()
,I/ActivityManager( 1022): Killing 2303:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
,D/TP/SmsProvider( 1463): query,matched:0, calling pid = 2389
,I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/8)
,E/UpdateRequestReceiver( 3447): ignoring update request
,D/TP/SmsProvider( 1463): match 0:Elapsed time : 8.408 ms
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/8)
,W/ContextImpl( 2962): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
E/UpdateRequestReceiver( 3447): ignoring update request
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3507): MountEmulatedStorage()
E/Zygote  ( 3507): v2
I/libpersona( 3507): KNOX_SDCARD checking this for 1000
I/libpersona( 3507): KNOX_SDCARD not a persona
,I/SELinux ( 3507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3507): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3507 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3507): TimaSignature is unavailable
,D/ActivityThread( 3507): Added TimaKeyStore provider
,E/Zygote  ( 3518): MountEmulatedStorage()
I/libpersona( 3518): KNOX_SDCARD checking this for 10146
E/Zygote  ( 3518): v2
I/libpersona( 3518): KNOX_SDCARD not a persona
,I/SELinux ( 3518): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3518 uid=10146 gids={50146, 9997} abi=armeabi-v7a
,I/SELinux ( 3518): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3518): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/UpdateRequestReceiver( 3447): ignoring update request
,D/Mms/SmsReceiverService( 2389): [end]    handleBootCompleted() consume time = 335.089323
,D/TimaKeyStoreProvider( 3518): TimaSignature is unavailable
,D/ActivityThread( 3518): Added TimaKeyStore provider
,W/libprocessgroup( 1022): failed to open /acct/uid_10110/pid_2303/cgroup.procs: No such file or directory
,I/FactoryTestApp( 2962): [IPCWriterToSecPhoneService$onServiceConnected](2962) connected done
D/FactoryTestApp( 2962): [IPCWriterToSecPhoneService$write](2962) Send Response Message to SecPhone
D/FactoryTestApp( 2962): [IPCWriterToSecPhoneService$write](2962) Response ��
,E/UpdateRequestReceiver( 3447): ignoring update request
,W/ResourcesManager( 3507): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/AT_Distributor(  314): Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,V/WebViewChromiumFactoryProvider( 3428): Binding Chromium to main looper Looper (main, tid 1) {9855d62}
,E/UpdateRequestReceiver( 3447): ignoring update request
,I/LibraryLoader( 3428): Expected native library version number "",actual native library version number ""
,I/chromium( 3428): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/FactoryTestApp( 2962): [IPCWriterToSecPhoneService$handleMessage](2962) Send BOOTING COMPLETED done
,I/iu.UploadsManager( 2108): End new media; added: 0, uploading: 0, time: 271 ms
,E/UpdateRequestReceiver( 3447): ignoring update request
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1022): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3551 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 3551): MountEmulatedStorage()
I/libpersona( 3551): KNOX_SDCARD checking this for 10088
E/Zygote  ( 3551): v2
I/libpersona( 3551): KNOX_SDCARD not a persona
I/SELinux ( 3551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/BrowserStartupController( 3428): Initializing chromium process, renderers=0
W/art     ( 3428): Attempt to remove local handle scope entry from IRT, ignoring
,I/SELinux ( 3551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3551): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 2755): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 2755): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 2755): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/chromium( 3428): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 3428): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/DBG_POLICYDM( 2755): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/BluetoothMediaBrowser( 2994):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
I/DBG_POLICYDM( 2755): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/TimaKeyStoreProvider( 3551): TimaSignature is unavailable
,D/ActivityThread( 3551): Added TimaKeyStore provider
,I/DBG_POLICYDM( 2755): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/chromium( 3428): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothMediaBrowser( 2994): no now playing list
D/BluetoothMediaBrowser( 2994):  getNowPlayingId now playing id : -1
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/AT_Distributor(  314): SetAtdStatus(), 1_1_0
D/AT_Distributor(  314): Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,I/ActivityManager( 1022): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3572 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1022): Killing 2627:com.google.android.music:main/u0a108 (adj 15): empty #31
I/ActivityManager( 1022): Killing 2820:com.osp.app.signin/u0a36 (adj 15): empty #32
,E/Zygote  ( 3572): MountEmulatedStorage(),
I/ActivityManager( 1022): Killing 1791:com.samsung.android.securitylogagent/1000 (adj 15): empty #33
E/Zygote  ( 3572): v2
I/libpersona( 3572): KNOX_SDCARD checking this for 1000
I/SELinux ( 3572): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3572): KNOX_SDCARD not a persona
,I/SELinux ( 3572): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3572): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3572): TimaSignature is unavailable
,D/ActivityThread( 3572): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/FOTA    ( 3507): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,D/PowerManagerService( 1022): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1177 (0x0)
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_1791/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_10108/pid_2627/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_10036/pid_2820/cgroup.procs: No such file or directory
,I/DBG_FMMDM( 3572): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_FMMDM( 3572): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,I/DBG_FMMDM( 3572): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,I/DBG_FMMDM( 3572): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3597): MountEmulatedStorage()
I/ActivityManager( 1022): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3597 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 3597): v2
I/libpersona( 3597): KNOX_SDCARD checking this for 1000
I/libpersona( 3597): KNOX_SDCARD not a persona
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android,
I/SELinux ( 3597): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 3597): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3597): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 3608): MountEmulatedStorage()
,E/Zygote  ( 3608): v2
I/libpersona( 3608): KNOX_SDCARD checking this for 10088
I/libpersona( 3608): KNOX_SDCARD not a persona
,I/Adreno-EGL( 3428): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
,I/Adreno-EGL( 3428): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3428): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3428): Local Branch: 
I/Adreno-EGL( 3428): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3428): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3428):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/SELinux ( 3608): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_DM  ( 3507): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
I/SELinux ( 3608): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1022): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3608 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 3608): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3597): TimaSignature is unavailable
,D/ActivityThread( 3597): Added TimaKeyStore provider
,W/ResourcesManager( 3483): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3483): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 3608): TimaSignature is unavailable
D/ActivityThread( 3608): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 3597): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 3597): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 3597): new DMDBOpenHelper instance
,D/PCWCLIENTTRACE_DMContentProvider( 3597): [URIMatcher] - result : 2
,I/DBG_FMMDM( 3572): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,I/DBG_FMMDM( 3572): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3572): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3507): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,I/DBG_DM  ( 3507): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,E/Zygote  ( 3630): MountEmulatedStorage()
,E/Zygote  ( 3630): v2
I/libpersona( 3630): KNOX_SDCARD checking this for 1000
I/libpersona( 3630): KNOX_SDCARD not a persona
,I/SELinux ( 3630): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3630): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1022): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3630 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 3630): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Killing 2849:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #31
V/JNIHelp ( 3483): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager( 1022): Killing 2869:com.sec.android.cloudagent/u0a1 (adj 15): empty #32
,I/art     (  309): Explicit concurrent mark sweep GC freed 8749(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 638us total 35.613ms
,D/TimaKeyStoreProvider( 3630): TimaSignature is unavailable
,D/ActivityThread( 3630): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 760us total 16.873ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 17.542ms
,I/DBG_FMMDS( 3630): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/DBG_FMMDS( 3630): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,W/System  ( 3483): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@260ba017: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/ActivityThread( 3483): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ProviderInstaller( 3483): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup( 1022): failed to open /acct/uid_10009/pid_2849/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10001/pid_2869/cgroup.procs: No such file or directory
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3551): Setting receiver enabled: false
,I/DBG_DM  ( 3507): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,D/PCWCLIENTTRACE_DMContentProvider( 3597): [URIMatcher] - result : 2
,I/DBG_DM  ( 3507): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 3507): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,E/DBG_FMMDS( 3630): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,I/DBG_DM  ( 3507): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3507): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,I/DBG_FMMDS( 3630): [50.18.150420][Line:43][xdbDBInit] 
,I/DBG_DM  ( 3507): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,W/chromium( 3428): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,I/DBG_DM  ( 3507): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,I/DBG_DM  ( 3507): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 3507): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 3507): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_DM  ( 3507): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/DBG_DM  ( 3507): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,D/OverheatReceiver( 1177): onReceive() getAction : android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 3507): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,I/DBG_DM  ( 3507): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,I/DBG_DM  ( 3507): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
I/DBG_DM  ( 3507): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/DBG_DM  ( 3507): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,I/DBG_DM  ( 3507): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 3507): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,I/DBG_DM  ( 3507): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,W/ContextImpl( 3507): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,I/DBG_DM  ( 3507): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,I/DBG_DM  ( 3507): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,I/DBG_DM  ( 3507): [com.wssyncmldm.XDMService(155/onStartCommand)] 
,D/OverheatReceiver( 1177): into the SAFE_MODE_ACTION
,D/OverheatReceiver( 1177): VZW on -> change to Global UX [safe mode]
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
D/OverheatReceiver( 1177): isSafeMode = false,
,W/chromium( 3428): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,E/ActivityThread( 3551): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,D/BootupListener( 1463): intent.getAction() = android.intent.action.BOOT_COMPLETED
,D/SettingsProvider( 1022): name = internet_call_settings_visibility
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 1001
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1022): ret = -1
I/DBG_DM  ( 3507): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/PhoneUtilsCommon( 1463): isSupportVoLTE is false.
,I/DBG_DM  ( 3507): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,I/dbxyzptlk.db240408.D.h( 3551): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,I/dbxyzptlk.db240408.D.h( 3551): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,I/dbxyzptlk.db240408.D.h( 3551): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,I/Telecom ( 1446): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,W/art     ( 3428): Attempt to remove local handle scope entry from IRT, ignoring
,I/DBG_DM  ( 3507): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
W/AwContents( 3428): onDetachedFromWindow called when already detached. Ignoring
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/PhoneWindow( 3428): *FMB* installDecor mIsFloating : false
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 3428): *FMB* installDecor flags : -2139027200
I/DBG_FMMDS( 3630): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,D/SystemWebViewEngine( 3428): CordovaWebView is running on device made by: samsung
,E/Zygote  ( 3666): MountEmulatedStorage()
,E/Zygote  ( 3666): v2
I/libpersona( 3666): KNOX_SDCARD checking this for 10052
I/libpersona( 3666): KNOX_SDCARD not a persona
,I/SELinux ( 3666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_FMMDS( 3630): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3630): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/SELinux ( 3666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/DBG_FMMDS( 3630): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3630): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
E/SELinux ( 3666): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/DBG_FMMDS( 3630): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
I/DBG_FMMDS( 3630): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,I/ActivityManager( 1022): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3666 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/dbxyzptlk.db240408.D.h( 3551): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,I/Telecom ( 1446): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,W/art     ( 3428): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3428): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider( 3666): TimaSignature is unavailable
D/ActivityThread( 3666): Added TimaKeyStore provider
,I/FOTA_Client( 2940): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 2940): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 2940): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,D/breakpad( 3551): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,W/FOTA_Client( 2940): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3507): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,E/Zygote  ( 3689): MountEmulatedStorage()
E/Zygote  ( 3689): v2
I/libpersona( 3689): KNOX_SDCARD checking this for 10013
I/libpersona( 3689): KNOX_SDCARD not a persona
,I/SELinux ( 3689): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3689): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1022): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3689 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,I/ActivityManager( 1022): Killing 2925:com.samsung.android.sconnect/u0a121 (adj 15): empty #31
,I/DBG_DM  ( 3507): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,E/SELinux ( 3689): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/com.dropbox.sync.android.a( 3551): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,I/DBG_DM  ( 3507): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 3507): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/TimaKeyStoreProvider( 3689): TimaSignature is unavailable
,D/ActivityThread( 3689): Added TimaKeyStore provider
,V/audio_hw_primary(  286): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  286): audio_extn_get_parameters: returns 
V/msm8974_platform(  286): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  286): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  286): key: 'call_forwarding' value: ''
,V/InCall  ( 1948): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1948): ProximitySensor -  - mFromRcsShare: false
,I/InCall  ( 1948): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,D/ScoverManager( 1948): serviceVersion : 16908288
,D/CoverManagerWhiteLists( 1022): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1948): InCallUtils - isCoverClosed : TYPE_FLIP_COVER ,
,D/CoverManagerWhiteLists( 1022): isAllowedToUse : SIGNATURE_MATCH
I/Telecom ( 1446): ProximitySensorManager: Proximity wake lock already released
D/InCall  ( 1948): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,I/InCall  ( 1948): InCallPresenter -  - InCallState = NO_CALLS
,I/InCall  ( 1948): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,D/InCall  ( 1948): InCallPresenter -  - dismissCoverDialog()...
,D/OpenGLRenderer( 3428): Render dirty regions requested: true
,I/InCall  ( 1948): CallSContextMotion - stopPutDownListening
,D/InCall  ( 1948): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,W/libprocessgroup( 1022): failed to kill pid 2925: No such process
,D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
D/CoverManagerWhiteLists( 1022): isAllowedToUse : SIGNATURE_MATCH
,D/InCall  ( 1948): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,D/PhoneStatusBarView( 1177): setCallBackground:0
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PhoneWindow( 3428): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3428): *FMB* isFloatingMenuEnabled return false
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/VideoCallManager( 1948): Instantiating VideoCallManager
,I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, NainActivit
,V/OneTimeInitializerReceiver( 3689): OneTimeInitializerReceiver.onReceive
,D/InputDispatcher( 1022): Focus entered window: 3428
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 3428): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 3428): Initialized EGL, version 1.4
E/        ( 1948): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1948): took 2.322396ms for 0*0 texture 0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/OpenGLRenderer( 3428): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3428): Enabling debug mode 0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,V/OneTimeService( 3689): OneTimeService.onHandleIntent
I/GFX generate_partition_tables( 1948): took 5.267865ms for 0*0 texture 0
,I/GFX raster( 1948): took 11.573126ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1948): Bitmap=0xb8c41ce0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8c45b38 counterpartCT=4 counterpartW=176 counterparth=144
,E/Zygote  ( 3720): MountEmulatedStorage()
,E/Zygote  ( 3720): v2
I/libpersona( 3720): KNOX_SDCARD checking this for 10014
I/libpersona( 3720): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3720 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3720): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/        ( 1948): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
I/SELinux ( 3720): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/Adreno-EGL( 1948): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1948): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1948): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1948): Local Branch: 
I/Adreno-EGL( 1948): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1948): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1948):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/SELinux ( 3720): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1022): failed to open /acct/uid_10121/pid_2925/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3720): TimaSignature is unavailable
,D/ActivityThread( 3720): Added TimaKeyStore provider
,D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,I/ActivityManager( 1022): Displayed Component not be shown by security: +2s85ms
,D/CustomFrequencyManagerService( 1022): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@7
,D/CustomFrequencyManagerService( 1022): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@11
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 1022): mDVFSHelper.release()
I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{337d114e u0 com.test.thalitest/.MainActivity t11} time:42342
,I/GFX GPU raster( 1948): eglCreateImageKHR: EGL_SUCCESS
,I/Timeline( 3428): Timeline: Activity_idle id: android.os.BinderProxy@f0eeb99 time:42349
,I/glCompressedTexImage2D( 1948): took 0.342344ms for 320*61440 texture 37809
I/draw setup( 1948): took 11.784480ms for 320*240 texture 37809
E/GFX GPU raster( 1948): drawn
I/GFX GPU raster ASTC( 1948): took 44.793023ms for 320*240 texture 12
I/GFX raster( 1948): took 44.877814ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1948): Bitmap=0xb8c45f30 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8c45ea0 counterpartCT=4 counterpartW=320 counterparth=240
E/        ( 1948): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1948): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1948): took 0.345157ms for 480*122880 texture 37813
I/draw setup( 1948): took 0.671354ms for 480*640 texture 37813
E/GFX GPU raster( 1948): drawn
,I/GFX GPU raster ASTC( 1948): took 9.331198ms for 480*640 texture 12,
I/GFX raster( 1948): took 9.403228ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1948): Bitmap=0xb8c45ea0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8e87248 counterpartCT=4 counterpartW=480 counterparth=640
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/SamsungIME( 1895): getCurrentCandidateView
E/        ( 1948): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
I/GFX GPU raster( 1948): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1948): took 0.370730ms for 440*116864 texture 37809
I/draw setup( 1948): took 0.700782ms for 440*330 texture 37809
,E/GFX GPU raster( 1948): drawn
,I/GFX GPU raster ASTC( 1948): took 5.741822ms for 440*330 texture 12
I/GFX raster( 1948): took 5.846874ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1948): Bitmap=0xb8e87248 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8e9bd60 counterpartCT=4 counterpartW=440 counterparth=330
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,D/LocationManagerService( 1022): getProviders()=[passive]
,E/YouTube MDX( 3483): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/        ( 1948): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640,
I/GFX GPU raster( 1948): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1948): took 0.528698ms for 480*163840 texture 37811
I/draw setup( 1948): took 0.887864ms for 480*640 texture 37811
E/GFX GPU raster( 1948): drawn
,I/GFX GPU raster ASTC( 1948): took 6.875208ms for 480*640 texture 12
I/GFX raster( 1948): took 6.959947ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1948): Bitmap=0xb8e9bd60 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb8e87050 counterpartCT=4 counterpartW=480 counterparth=640
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1740): Starting #7
,I/Hs20UtilService( 1740): Message received 5003
,I/ActivityManager( 1022): Killing 2672:com.android.calendar/u0a131 (adj 15): empty #31
,I/com.dropbox.sync.android.ad( 3551): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
,I/SurfaceFlinger(  259): id=11 Removed uhalitest (7/8)
,I/SurfaceFlinger(  259): id=11 Removed uhalitest (-2/8)
,D/SamsungIME( 1895): Dismiss ExpandCandiate
,I/KLMS-2.5.123: ( 2641): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 14 13:39:16 GMT+01:00 2016
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 2641): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/ContactAccountLoggerTas( 3666): canRun() : Opted Out
,E/        ( 1948): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1948): took 2.983177ms for 0*0 texture 0,
,E/Zygote  ( 3771): MountEmulatedStorage(),
,E/Zygote  ( 3771): v2
I/libpersona( 3771): KNOX_SDCARD checking this for 10020,
I/libpersona( 3771): KNOX_SDCARD not a persona
,I/SELinux ( 3771): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1022): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3771 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a,
I/SELinux ( 3771): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3771): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/ActivityManager( 1022): userId = 0, bbcId = -10000,
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/GFX generate_partition_tables( 1948): took 8.583958ms for 0*0 texture 0
,I/GFX raster( 1948): took 13.791927ms for 176*144 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1948): Bitmap=0xb8e6f008 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8e6f128 counterpartCT=4 counterpartW=176 counterparth=144
,I/KLMS-2.5.123: ( 2641): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 2641): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/libprocessgroup( 1022): failed to open /acct/uid_10131/pid_2672/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 2641): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/TimaKeyStoreProvider( 3771): TimaSignature is unavailable
,I/KLMS-2.5.123: ( 2641): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ActivityThread( 3771): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 2641): KLMSIntentService(): BOOT_COMPLETED
,D/CustomFrequencyManagerService( 1022): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@11
,E/        ( 1948): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,I/GFX construct_block_size_descriptor_2d second part( 1948): took 2.512760ms for 0*0 texture 0
I/GFX generate_partition_tables( 1948): took 6.056198ms for 0*0 texture 0
,I/GFX raster( 1948): took 10.819429ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1948): Bitmap=0xb8e6f260 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8e6f560 counterpartCT=4 counterpartW=176 counterparth=144
D/ScoverManager( 1948): registerListener
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 21405(1092KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 2.724ms total 156.489ms
,D/CoverManagerWhiteLists( 1022): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManagerWhiteLists( 1022): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1022): registerListenerCallback : binder = android.os.BinderProxy@2671df94, pid : 1948, uid : 1001, type : 1
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/InCall  ( 1948): InCallPresenter -  - Finished InCallPresenter.setUp
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1022): getStreamVolume 3 index 0
,I/Velvet.VelvetFactory( 3666): refreshing search history.
,I/KLMS-2.5.123: ( 2641): KLMSIntentService(): onDestroy()
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,W/GAV2    ( 3666): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 3797): MountEmulatedStorage()
E/Zygote  ( 3797): v2
I/libpersona( 3797): KNOX_SDCARD checking this for 10090
I/libpersona( 3797): KNOX_SDCARD not a persona
,I/SELinux ( 3797): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3797): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1022): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3797 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 3797): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Killing 3017:com.android.keychain/1000 (adj 15): empty #31
,D/JsMessageQueue( 3428): Set native->JS mode to OnlineEventsBridgeMode
,E/Tethering( 1022): No numeric data
,E/Tethering( 1022): No numeric data
,E/Tethering( 1022): No numeric data
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/Tethering( 1022): No numeric data
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Tethering( 1022): No numeric data
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Tethering( 1022): No numeric data
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3483): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/SamsungIME( 1895): getDebugLevel  : 0x4f4c
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3017/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 3797): TimaSignature is unavailable
,D/ActivityThread( 3797): Added TimaKeyStore provider
,W/GAV2    ( 3666): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ContactAccountLoggerTas( 3666): canRun() : Opted Out
,D/[SBeam] ( 1313): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1313): SBeamEnabler.isSBeamSupported : EXIST
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3835): MountEmulatedStorage()
E/Zygote  ( 3835): v2
I/libpersona( 3835): KNOX_SDCARD checking this for 1000
I/libpersona( 3835): KNOX_SDCARD not a persona
,I/SELinux ( 3835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3835): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3835 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1022): Killing 2779:com.sec.spp.push/u0a32 (adj 15): empty #31
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/Tethering( 1022): No numeric data
,E/Tethering( 1022): No numeric data
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/Tethering( 1022): No numeric data
,D/TimaKeyStoreProvider( 3835): TimaSignature is unavailable
,D/ActivityThread( 3835): Added TimaKeyStore provider
,I/DBG_DM  ( 3507): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,I/ActivityManager( 1022): Killing 1616:com.android.defcontainer/u0a3 (adj 15): empty #31
,D/elm:15121( 3797): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 3797): ELMEngine.ELMEngine( context ).
,E/MTPRx   ( 3835): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,D/SecContentProvider2( 1022): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1022): mCursor = null
,V/MTPRx   ( 3835): sealedState: false
V/MTPRx   ( 3835): sealedUsbMassStorageState: false
,D/SettingsProvider( 1022): name = mtp_usb_connection_status
,D/SettingsProvider( 1022): name = media_player_mode
,E/Tethering( 1022): No numeric data
,I/System.out( 3551): Thread-489(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3551): Thread-489(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3551): Thread-489(ApacheHTTPLog):isShipBuild true
I/System.out( 3551): Thread-489(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3551): Thread-489(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1022): name = mtp_usb_conditions_met
,D/elm:15121( 3797): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 3797): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 502 for uid 10088
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SamsungIME( 1895): getDebugLevel  : 0x4f4c
,D/elm:15121( 3797): ElmAgentService : onCreate()
,W/libprocessgroup( 1022): failed to open /acct/uid_10032/pid_2779/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_10003/pid_1616/cgroup.procs: No such file or directory
,I/ActivityManager( 1022): Killing 2685:com.android.chrome/u0a77 (adj 15): empty #31
,D/elm:15121( 3797): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 3797): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:15121( 3797): BootCompletedState : startBootCompleted() call
,V/EmergencyMode( 1436): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,D/elm:15121( 3797): MDMBridge.getAllLicenseInfoFromSDK()
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/elm:15121( 3797): Get License : 0
,D/elm:15121( 3797): ElmAgentService : onDestroy().
,I/SamsungIME( 1895): KeybaordView init() : load resources
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/SettingsProvider( 1022): name = mtp_running_status
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/SettingsProvider( 1022): name = media_mount_count
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/ActivityManager( 1022): Killing 2503:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,D/SettingsProvider( 1022): name = mtp_sync_alive
,E/SMD     (  291): DCD OFF
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,V/VibratorService( 1022): hasVibrator - useVibetonz: true
,W/MessageQueue( 3483): Handler (android.os.Handler) {19222f39} sending message to a Handler on a dead thread
W/MessageQueue( 3483): java.lang.IllegalStateException: Handler (android.os.Handler) {19222f39} sending message to a Handler on a dead thread
W/MessageQueue( 3483): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 3483): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 3483): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 3483): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 3483): 	at android.os.Handler.post(Handler.java:326)
W/MessageQueue( 3483): 	at ffw.a(SourceFile:327)
W/MessageQueue( 3483): 	at guw.a(SourceFile:120)
W/MessageQueue( 3483): 	at guf.c(SourceFile:26)
W/MessageQueue( 3483): 	at gui.run(SourceFile:297)
W/MessageQueue( 3483): 	at android.os.Handler.handleCallback(Handler.java:739)
W/MessageQueue( 3483): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/MessageQueue( 3483): 	at android.os.Looper.loop(Looper.java:145)
W/MessageQueue( 3483): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/SettingsProvider( 1022): name = sdcard_launch
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/NotificationAccessSettings( 1313): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,I/AudioService( 1022): getStreamVolume 3 index 0
,W/libprocessgroup( 1022): failed to open /acct/uid_10077/pid_2685/cgroup.procs: No such file or directory
,D/SettingsProvider( 1022): name = boot_time_connected
,I/MediaRouter( 3666): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/SamsungIME( 1895): getCurrentKeyboard
I/SamsungIME( 1895): getTextKeyboard
,V/VibratorService( 1022): hasVibrator - useVibetonz: true
,W/ContextImpl( 1936): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,V/VibratorService( 1022): hasVibrator - useVibetonz: true
,D/SecUISvc( 1936): Service started flags 0 startId 1
,D/SecUISvc( 1936): Thread created.
,D/SettingsProvider( 1022): name = mtp_open_session
,I/FavoriteContactNamesSup( 3666): get() : Execute runnable (UI thread)
I/ContactLabelSupplier( 3666): get() : Execute runnable (UI thread)
,W/ResourcesManager( 1313): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/ActivityManager( 1022): userId = 0, bbcId = -10000,
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
D/SamsungIME( 1895): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/chromium( 3428): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 3428): 
,W/libprocessgroup( 1022): failed to open /acct/uid_10039/pid_2503/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_PushUtil( 3597): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3597): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3597): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3597): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3597): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3597): ACTION_BOOTUP - Push type: [SPP, GCM]
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/PCWCLIENTTRACE_AccountUtil( 3597): [hasSamungAccount] - No Samsung Account
,V/EmergencyMode( 1436): [EmergencyBase] setBootTime
V/EmergencyMode( 1436): [EmergencyFactory] No Recovery State, kill my self.
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3878): MountEmulatedStorage(),
E/Zygote  ( 3878): v2
I/libpersona( 3878): KNOX_SDCARD checking this for 1000
I/libpersona( 3878): KNOX_SDCARD not a persona
,I/ActivityManager( 1022): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3878 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,I/SELinux ( 3878): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3878): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3878): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3597): [GetString-S]
,D/FileApkUtils( 2108): Optimizing (staging complete)
,D/FileApkUtils( 2108): Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
I/art     ( 2108): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,I/ReactiveServiceManager( 3597): Supported : 1
,D/QSEECOMAPI: ( 1022): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1022): App is not loaded in QSEE
,I/RlzPingService( 3720): Setting next ping for 1458563957174
,D/QSEECOMAPI: ( 1022): Loaded image: APP id = 10
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3878): TimaSignature is unavailable
,D/ActivityThread( 3878): Added TimaKeyStore provider
,D/QSEECOMAPI: ( 1022): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1022): QSEECom_shutdown_app, app_id = 10
,E/terrier ( 1022): handleString: Failed to handle string(-4)
E/terrier ( 1022): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 3597): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3597): [GetString-E]
,E/Zygote  ( 3894): MountEmulatedStorage()
E/Zygote  ( 3894): v2
I/libpersona( 3894): KNOX_SDCARD checking this for 10055
I/libpersona( 3894): KNOX_SDCARD not a persona
,I/SELinux ( 3894): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/DexOptUtils( 2108): Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.,
I/SELinux ( 3894): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3894): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/PCWCLIENTTRACE_PushUtil( 3597): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3597): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3597): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 3597): [ensureRegistration] - No Samsung account
,I/ActivityManager( 1022): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3894 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3894): TimaSignature is unavailable
,D/ActivityThread( 3894): Added TimaKeyStore provider
,E/Zygote  ( 3910): MountEmulatedStorage(),
E/Zygote  ( 3910): v2
I/libpersona( 3910): KNOX_SDCARD checking this for 10028
I/libpersona( 3910): KNOX_SDCARD not a persona
,I/SELinux ( 3910): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 3910): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1022): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3910 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 3910): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/TimaKeyStoreProvider( 3910): TimaSignature is unavailable
,D/ActivityThread( 3910): Added TimaKeyStore provider
,D/ScoverManager( 1313): serviceVersion : 16908288
,D/AndroidHttpClient( 3483): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
D/AndroidHttpClient( 3483): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 3483): Thread-517(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3483): Thread-517(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 3483): Thread-517(ApacheHTTPLog):isShipBuild true
,I/System.out( 3483): Thread-517(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3483): Thread-517(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 502 for uid 10161
,I/ContactLabelSupplier( 3666): get() : OptedIn = false
,I/WebViewFactory( 3666): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/LibraryLoader( 3666): Loading: webviewchromium
,D/jxcore_app_log( 3428): JniHelper::setJavaVM(0xb889a448), pthread_self() = -1192118440
,I/LibraryLoader( 3666): Time to load native libraries: 7 ms (timestamps 3549-3556)
,I/LibraryLoader( 3666): Expected native library version number "",actual native library version number ""
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3428): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3428):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3428):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3428):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3428):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3428): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8075b3c added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428): setBluetoothMacAddress: 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3428): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3428): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3428): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3428): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428):     - Bluetooth MAC address: 08:EC:A9:50:76:27
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@783b94b added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3428): addListener: New listener added - the number of listeners is now 1,
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3428): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,D/UserAnalysis.PlaceProvider( 3894): PlaceProvider onCreate()
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/CameraApp( 3878): CameraApp.onCreate()... mFeature : null
,I/testFeature( 3878): Feature.Feature(context)
,I/testFeature( 3878): Feature.readInternalDefaultXml()
I/testFeature( 3878): ResetFeatureValue
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3428): setScanMode: 1 -> 2
,I/CameraFirmware_broadcast( 3878): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3878): CameraApp.getAppFeature()...
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3931): MountEmulatedStorage()
,E/Zygote  ( 3931): v2
I/libpersona( 3931): KNOX_SDCARD checking this for 10095
I/libpersona( 3931): KNOX_SDCARD not a persona
,I/SELinux ( 3931): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/chromium( 3428): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SELinux ( 3931): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3931): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3931 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 1022): Killing 2655:com.android.email/u0a141 (adj 15): empty #31
,I/ActivityManager( 1022): Killing 3145:com.mobeam.barcodeService/1000 (adj 15): empty #31
,I/ActivityManager( 1022): Killing 3165:flipboard.boxer.app/u0a97 (adj 15): empty #31
,W/art     ( 3666): Attempt to remove local handle scope entry from IRT, ignoring
,D/TimaKeyStoreProvider( 3931): TimaSignature is unavailable
,D/ActivityThread( 3931): Added TimaKeyStore provider
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PreloadFilterInstaller( 3931): uses FILTER_DB_VER_1
,E/SQLiteLog( 3931): (284) automatic index on titles(filter_id)
,I/FilterProviderReceiver( 3931): onReceive in FilterProviderReceiver
I/FilterProviderReceiver( 3931): onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3951): MountEmulatedStorage()
E/Zygote  ( 3951): v2
I/libpersona( 3951): KNOX_SDCARD checking this for 10098
I/libpersona( 3951): KNOX_SDCARD not a persona
,I/SELinux ( 3951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1022): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3951 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,I/SELinux ( 3951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3951): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3951): TimaSignature is unavailable
,D/ActivityThread( 3951): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 8674(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 971us total 44.255ms,
,D/UserAnalysis.SecureDbManager( 3894): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3894): SecurePlaceDbHelper() 
,D/UserAnalysis( 3894): Create SecureDbHelper
,I/System.out( 3483): Thread-517 calls detatch()
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 652us total 20.419ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 860us total 17.890ms
,I/System.out( 3910): Inside onCreate() of WakeupTriggerProvide
I/System.out( 3910): Inside WakeupProvider
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3145/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10097/pid_3165/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10141/pid_2655/cgroup.procs: No such file or directory
,I/FactoryTestApp( 2962): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3544)  
,I/LockPatternUtils( 1313): isSmartCardAuthenticationAvailable: false
,D/IntelligenceServiceApplication( 3894): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3894): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3970): MountEmulatedStorage(),
E/Zygote  ( 3970): v2
I/libpersona( 3970): KNOX_SDCARD checking this for 10056
I/libpersona( 3970): KNOX_SDCARD not a persona
,I/SELinux ( 3970): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 3970): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3970): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3507): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,I/ActivityManager( 1022): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3970 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/PackageIntentReceiver( 3951): ACTION_BOOT_COMPLETED
,I/ActivityManager( 1022): Killing 3204:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,D/PackageIntentReceiver( 3951): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/Settings_Utils( 1313): isSupportVNFestival SM-A300FU XEO
,D/TimaKeyStoreProvider( 3970): TimaSignature is unavailable
,D/ActivityThread( 3970): Added TimaKeyStore provider
,E/Zygote  ( 3984): MountEmulatedStorage()
I/ActivityManager( 1022): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3984 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 3984): v2
I/libpersona( 3984): KNOX_SDCARD checking this for 10099
I/libpersona( 3984): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Killing 3245:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,I/SELinux ( 3984): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3984): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3984): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/VlingoApplication( 3910): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,D/TimaKeyStoreProvider( 3984): TimaSignature is unavailable
D/ActivityThread( 3984): Added TimaKeyStore provider
,D/IntelligenceServiceApplication( 3894): no applications having user consent for prediction
,W/InstanceID/Rpc( 2108): Found 10011
,W/ResourceType( 1313): Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,W/ResourceType( 1313): Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,I/ActivityManager( 1022): Killing 3260:flipboard.app/u0a96 (adj 15): empty #31
,W/libprocessgroup( 1022): failed to open /acct/uid_1101/pid_3204/cgroup.procs: No such file or directory
,V/PlaceDetection v1.0.19 ( 3894): [PlaceDetection::stopService] Service stopped.
,I/ActivityManager( 1022): Killing 3279:com.sec.usbsettings/1000 (adj 15): empty #31
,V/PlaceDetection v1.0.19 ( 3894): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3894): Constructor Preference
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1022): failed to open /acct/uid_10153/pid_3245/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10096/pid_3260/cgroup.procs: No such file or directory
,I/VlingoAndroidCore( 3910): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3279/cgroup.procs: No such file or directory
,D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 502 for uid 10052
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 3666): Tagging socket 39 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/VlingoApplication( 3910): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 3910): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DialogFlow( 3910): initQueue()
,I/System.out( 3551): pool-10-thread-1 calls detatch()
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/VibratorService( 1022): hasVibrator - useVibetonz: true
,W/ActivityManager( 1022): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/GCM     ( 2108): COMPAT: Multi user not supported
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/sCloudBackupApp( 3970): sCloudBackupApp Version Info : 4.04.7.KK_APP
,D/GCM     ( 1839): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4020): MountEmulatedStorage()
E/Zygote  ( 4020): v2
I/libpersona( 4020): KNOX_SDCARD checking this for 10030
I/libpersona( 4020): KNOX_SDCARD not a persona
,I/SELinux ( 4020): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 4020): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1022): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4020 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 4020): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4028): MountEmulatedStorage()
,E/Zygote  ( 4028): v2
I/libpersona( 4028): KNOX_SDCARD checking this for 10058
,I/libpersona( 4028): KNOX_SDCARD not a persona
,I/SELinux ( 4028): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4028): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4028): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4028 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4020): TimaSignature is unavailable
,D/ActivityThread( 4020): Added TimaKeyStore provider
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
,I/qtaguid ( 3666): Untagging socket 43
,I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
I/qtaguid ( 3666): Untagging socket 43
,I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
I/qtaguid ( 3666): Untagging socket 43
,I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
I/qtaguid ( 3666): Untagging socket 43
,I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
I/qtaguid ( 3666): Untagging socket 43
,I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
,I/qtaguid ( 3666): Untagging socket 43
I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
,I/qtaguid ( 3666): Untagging socket 43
I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
,I/qtaguid ( 3666): Untagging socket 43
I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
,I/qtaguid ( 3666): Untagging socket 43
,I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
,I/qtaguid ( 3666): Untagging socket 43
I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
I/qtaguid ( 3666): Untagging socket 43
,I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
I/qtaguid ( 3666): Untagging socket 43
,I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
,I/qtaguid ( 3666): Untagging socket 43
,D/TimaKeyStoreProvider( 4028): TimaSignature is unavailable
D/ActivityThread( 4028): Added TimaKeyStore provider
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1022): [SO] -0.402 0.172 9.883
,I/GCoreUlr( 2108): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/GCoreUlr( 1839): DispatchingService.onCreate()
,W/ActivityManager( 1022): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/BootCompletedReceiver( 2108): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2108): Got an BootCompleted event.
I/qtaguid ( 3666): Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3666, getuid(): 10052
,I/CheckinService( 2108): Disabling old GoogleServicesFramework version
,D/BootCompletedReceiver( 2108): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 2108): onCreate
,D/SystemUpdateService( 2108): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ContactAccountLoggerTas( 3666): canRun() : Opted Out
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 25619(1397KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 22MB/33MB, paused 12.482ms total 194.844ms
,I/Gmail   ( 3984): getAccountsCursor
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AuthZen ( 2108): Handling intent: android.intent.action.BOOT_COMPLETED
,W/GAV2    ( 3984): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/DBG_DM  ( 3507): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,I/Gmail   ( 3984): Observing account changes for notifications
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/ExternalOEMControlProvider( 4028): onCreate,
,D/AuthZenEventHandler( 2108): Handling event: android.intent.action.BOOT_COMPLETED
,I/CheckinService( 2108): Checking schedule, now: 1457959158939 next: 1458299986961
I/CheckinService( 2108): active receiver: disabled
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4020): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 4020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4020): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 4073): MountEmulatedStorage()
E/Zygote  ( 4073): v2
I/libpersona( 4073): KNOX_SDCARD checking this for 1000
,I/libpersona( 4073): KNOX_SDCARD not a persona
,I/SELinux ( 4073): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4073): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4073): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=4073 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/art     ( 3910): Suspending all threads took: 6.327ms
,I/ActivityManager( 1022): Killing 2389:com.android.mms/u0a41 (adj 15): empty #31
,W/jxcore-log( 3428): Initializing JXcore engine
W/jxcore-log( 3428): JXcore engine is ready
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1022): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 10058
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1022): ret = -1
,W/ResourcesManager( 4020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SystemUpdateService( 2108): cancelUpdate (empty URL)
I/SystemUpdateService( 2108): active receiver: disabled
,W/BackupManagerService( 1022): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,D/TimaKeyStoreProvider( 4073): TimaSignature is unavailable
D/ActivityThread( 4073): Added TimaKeyStore provider
,D/CountryDetector( 1022): No listener is left
,D/SettingsProvider( 1022): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 10058
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1022): ret = -1
,W/BackupManagerService( 1022): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GCoreUlr( 1839): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 4073): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/libprocessgroup( 1022): failed to open /acct/uid_10041/pid_2389/cgroup.procs: No such file or directory
,E/audit   ( 1915): type=1400 msg=audit(1457959159.081:205): avc:  denied  { ioctl } for  pid=3930 comm="Thread-472" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1915):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1915): type=1300 msg=audit(1457959159.081:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=936cb8f8 items=0 ppid=309 ppcomm=main pid=3930 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-472" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1915): type=1320 msg=audit(1457959159.081:205): 
W/jxcore-log( 3428): Starting JXcore engine
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/btif_config_util( 2994): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/ResourcesManager( 4020): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4020): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/BaseAppContext( 2108): Using Auth Proxy for data requests.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceMode( 4073): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 4073): setReferenceIsDumpState : 0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4097): MountEmulatedStorage()
E/Zygote  ( 4097): v2
I/libpersona( 4097): KNOX_SDCARD checking this for 1000
I/libpersona( 4097): KNOX_SDCARD not a persona
,I/SELinux ( 4097): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4097): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4097): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/jxcore-log( 3428): Platform android,
W/jxcore-log( 3428): 
W/jxcore-log( 3428): Process ARCH arm
W/jxcore-log( 3428): 
,I/ActivityManager( 1022): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=4097 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
I/ActivityManager( 1022): Killing 3322:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,I/LockPatternUtils( 1313): isSmartCardAuthenticationAvailable: false
,D/TimaKeyStoreProvider( 4097): TimaSignature is unavailable
,D/ActivityThread( 4097): Added TimaKeyStore provider
,E/Gmail   ( 3984): Error finding the version of the Email provider.....
E/Gmail   ( 3984): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3984): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3984): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3984): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3984): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3984): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3984): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3984): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3984): We do not support migrating this version of the Email provider.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/Gmail   ( 3984): getAccountsCursor
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/ActivityManager( 1022): Waited long enough for: ServiceRecord{ffe445 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SystemUpdateService( 2108): onDestroy
,W/ActivityManager( 1022): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/NPS_WSSNPS( 4097): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4097): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,W/libprocessgroup( 1022): failed to open /acct/uid_10043/pid_3322/cgroup.procs: No such file or directory
,E/BaseAppContext( 2108): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,E/SQLiteLog( 3984): (283) recovered 93 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/NPS_WSSNPS( 4097): [] Service onCreate!!,
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4127): MountEmulatedStorage()
,I/libpersona( 4127): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4127): v2
I/libpersona( 4127): KNOX_SDCARD not a persona
I/SELinux ( 4127): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=4127 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4127): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4127): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1022): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4127): TimaSignature is unavailable
D/ActivityThread( 4127): Added TimaKeyStore provider
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4291, temperature: 244, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/art     ( 1664): Explicit concurrent mark sweep GC freed 2733(105KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 13.770ms total 72.877ms
,E/File    ( 3984): fail readDirectory() errno=2
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/NPS_WSSNPS( 4097): [50.150321] NpsServiceTask Start
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,D/PowerUI ( 1177): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1177): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,I/GCoreUlr( 1839): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,V/EmergencyMode( 1436): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1436): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/Auth    ( 1839): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/HeadsetService( 2994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2994): Disconnected process message: 10
,I/Gmail   ( 3984): notifyAccountChanged
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/FactoryTestApp( 2962): [DummyFtClient$onDestroy](2962) Destroy DummyFtClient service
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/FactoryTestApp( 2962): [Support$Values.getString](2962) id=MODEL_COMMUNICATION_MODE, value=gsm
,D/SViewCoverView( 1177): level :100 plugged : 2
I/FactoryTestApp( 2962): [ModuleCommon$isConnectionModeNone](2962) mConnectionMode = gsm
I/FactoryTestApp( 2962): [ModuleCommon$isRunningFtClient](2962) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2962): [DummyFtClient$onDestroy](2962) kill process
I/Process ( 2962): Sending signal. PID: 2962 SIG: 9
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/GoogleHttpClient( 1664): GMS http client unavailable, use old client
,E/ActivityThread( 3984): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@308cef28 that was originally bound here
E/ActivityThread( 3984): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@308cef28 that was originally bound here
E/ActivityThread( 3984): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3984): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3984): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3984): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3984): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3984): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3984): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3984): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3984): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3984): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3984): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3984): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3984): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3984): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3984): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3984): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NPS_WSSNPS( 4097): [50.150321] smlDBHelper
,E/Zygote  ( 4149): MountEmulatedStorage()
I/libpersona( 4149): KNOX_SDCARD checking this for 10102
E/Zygote  ( 4149): v2
I/libpersona( 4149): KNOX_SDCARD not a persona
,I/SELinux ( 4149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4149 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 4149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1022): Unbind failed: could not find connection for android.os.BinderProxy@3da42a5e
,E/SELinux ( 4149): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 3428): JXcore Cordova bridge is ready!
I/jxcore-log( 3428): 
,W/jxcore-log( 3428): JXcore engine is started
,I/Gmail   ( 3984): getAccountsCursor
W/SQLiteConnectionPool( 1664): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/NPS_WSSNPS( 4097): [50.150321] AsyncBulkFlagCheck
,I/org.thaliproject.p2p.ThaliPermissions( 3428): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 3428): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,I/DBG_DM  ( 3507): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,E/jxcore  ( 3428): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3428): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3428): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 3428): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,I/Gmail   ( 3984): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NPS_WSSNPS( 4097): [50.150321] IsRemain_AsyncBulkCheck
I/NPS_WSSNPS( 4097): [50.150321] IsRemain_Asyncing nothing
D/TimaKeyStoreProvider( 4149): TimaSignature is unavailable
W/ContextImpl( 4097): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
D/ActivityThread( 4149): Added TimaKeyStore provider
,I/Gmail   ( 3984): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3984): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3984): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/FocusedStackFrame( 1022): Set to : 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,D/InputDispatcher( 1022): Focused application set to: xxxx
,D/InputDispatcher( 1022): Focus left window: 3428
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (152 us)
,W/PluginManager( 3428): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 91ms. Plugin should use CordovaInterface.getThreadPool().
,D/CustomFrequencyManagerService( 1022): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1022): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1022): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1022): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1022): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 3910): INFO:Resource not found:/Common.properties Using default values
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Launcher( 1499): onRestart, Launcher: 769650094
,I/ActivityManager( 1022): Process com.sec.factory (pid 2962)(adj 0) has died(19,607)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000,
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
D/NPS_WSSNPS( 4097): [50.150321] Service onDestroy
,E/SMD     (  291): DCD OFF
,D/Launcher( 1499): onStart, Launcher: 769650094
D/Launcher.HomeView( 1499): onStart
,D/Launcher( 1499): onResume, Launcher: 769650094
D/SettingsProvider( 1022): name = kids_home_mode
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 10006
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1022): ret = -1
,D/Launcher.HomeView( 1499): onResume
,D/Launcher( 1499): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/GCoreUlr( 1839): Unbound from all location providers
I/GCoreUlr( 1839): Place inference reporting - stopped
,D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SensorService( 1022): [SO] activate (ident=0xb90859d0, enabled=0)
I/Sensors ( 1022): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/NPS_WSSNPS( 4097): [50.150321] smlBRConfigurationDelete
,I/NPS_WSSNPS( 4097): [50.150321] smlBRMessageDelete
D/SensorManager( 1022): unregisterListener ::   
I/NPS_WSSNPS( 4097): [50.150321] smlBREmailDelete
I/Sensors ( 1022): AccelerometerSensor(0) setDelay : 200000000(ns)
I/NPS_WSSNPS( 4097): [50.150321] smlBRNetworkDelete
I/NPS_WSSNPS( 4097): [50.150321] smlBRCallLogDelete
I/NPS_WSSNPS( 4097): [50.150321] smlBRMiniDiaryDelete
D/SensorService( 1022): [SO] changed settle time [0]
D/SensorService( 1022): [SO] setDelay [200000000]
D/SensorService( 1022): [SO] activate (ident=0xb90859d0, enabled=1)
D/SensorService( 1022): [SO] AR_init
I/Sensors ( 1022): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
I/NPS_WSSNPS( 4097): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 4097): [50.150321] smlBRSMemoDelete
I/NPS_WSSNPS( 4097): [50.150321] cpuBooster release : false
,D/MenuAppsGridFragment( 1499): onResume
,D/ActivityManager( 1022): handle home activity for 0
I/WallpaperManagerService( 1022): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1022): post home show event for user 0
D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
,I/SurfaceFlinger(  259): id=13 createSurf (540x960),1 flag=4, Mauncher
,D/SensorManager( 1022): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
D/WallpaperManagerService( 1022):  force update = false; persona id = 0; current user =0; current persona = 0
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1022): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
,D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/NPS_WSSNPS( 4097): [50.150321] dsServerSocket close
,D/SettingsProvider( 1022): name = access_control_enabled
,D/InputDispatcher( 1022): Focus entered window: 1499
,D/SRIB_DCS( 1499): log_dcs ThreadedRenderer::initialize entered! ,
,I/ActivityManager( 1022): Killing 3186:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4149): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1022): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4188 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1022): Killing 3411:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,E/Zygote  ( 4188): MountEmulatedStorage()
E/Zygote  ( 4188): v2
I/libpersona( 4188): KNOX_SDCARD checking this for 10065
I/libpersona( 4188): KNOX_SDCARD not a persona
,I/AuthZen ( 2108): Fetching signing key...
,I/SELinux ( 4188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4188): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AndroidRuntime( 4181): 
D/AndroidRuntime( 4181): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4181): CheckJNI is OFF,
D/AndroidRuntime( 4181): readGMSProperty: start
D/AndroidRuntime( 4181): readGMSProperty: already setted!!
D/AndroidRuntime( 4181): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4181): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4181): readGMSProperty: end
D/AndroidRuntime( 4181): addProductProperty: start
,I/AuthZen ( 2108): Signing key fetched successfully!
,D/Launcher( 1499): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 1313): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,W/BaseAppContext( 2108): Using Auth Proxy for data requests.
,I/ActivityManager( 1022): Killing 1591:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4188): TimaSignature is unavailable
,D/ActivityThread( 4188): Added TimaKeyStore provider
W/ContextImpl( 1313): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
W/IInputConnectionWrapper( 3428): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1895): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/SensorService( 1022): [SO] Reset Rotation Old [100], Init [1]
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3597): unregister AuthInfo UpdateReceiver v2.0
,I/SettingSearch/SearchIntentReceiver( 1313): InitSerachDBThread thread end!
,I/Timeline( 1499): Timeline: Activity_idle id: android.os.BinderProxy@20702cc6 time:46480
,W/GCoreFlp( 1839): No location to return for getLastLocation()
,W/FusedLocationProvider( 1839): location=null
,D/PersonaManager( 1022): isKioskContainerExistOnDevice
,I/GCoreUlr( 1839): DispatchingService.onDestroy()
I/GCoreUlr( 1839): Stopping handler for UlrDispSvcFast
,I/Process ( 4020): Sending signal. PID: 4020 SIG: 9
,I/ActivityManager( 1022): Displayed Component not be shown by security: +385ms
,W/libprocessgroup( 1022): failed to open /acct/uid_10081/pid_3186/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3411/cgroup.procs: No such file or directory
,I/GCoreUlr( 1839): Unbound from all location providers
I/GCoreUlr( 1839): Place inference reporting - stopped
,E/AffinityControl( 4181): AffinityControl: registerfunction enter
I/Icing   ( 2108): Storage manager: low false usage 2.09MB avail 9.95GB capacity 11.63GB
,D/FileShare-Server( 4188): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/ActivityManager( 1022): Killing 3389:com.sec.dsm.system/1000 (adj 15): empty #31
,D/PersistentNotificationBroadcastReceiver( 1839): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/AndroidRuntime( 4181): Calling main entry com.android.commands.pm.Pm
,W/GCoreFlp( 1839): No location to return for getLastLocation()
W/FusedLocationProvider( 1839): location=null
,I/ActivityManager( 1022): Process com.sec.android.app.sns3 (pid 4020)(adj 0) has died(24,600)
,W/art     ( 2108): Suspending all threads took: 9.983ms
,D/a       ( 2108): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 2108): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2108): Clearing transaction cache
,D/SensorService( 1022): [SO] currT = 46631052000, prevT = 46201075000, diff = 429977000, [-0.421 0.172 9.883]
D/SensorService( 1022): [SO] -0.421 0.172 9.883
D/SensorService( 1022): [SO] [100 -> 255]
,D/PackageManager( 1022): START PACKAGE DELETE: observer{917886255}
D/PackageManager( 1022): pkg{<packageName>}
D/PackageManager( 1022): user{0}
D/PackageManager( 1022): caller{2000}
D/PackageManager( 1022): flags{2}
,D/PersonaManagerService( 1022): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1022): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 1022): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,D/PackageManager( 1022): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1022): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1022): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled
,D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled :  enabled true
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4218): MountEmulatedStorage()
,E/Zygote  ( 4218): v2
I/libpersona( 4218): KNOX_SDCARD checking this for 10031
I/libpersona( 4218): KNOX_SDCARD not a persona
,I/SELinux ( 4218): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/PackageManager( 1022): !@killApplicatoin: 10167, uninstall pkg,
,I/SELinux ( 4218): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4218): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4218 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,D/CustomFrequencyManagerService( 1022): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1022): mDVFSHelper.release()
,D/TimaKeyStoreProvider( 4218): TimaSignature is unavailable
E/libEGL  ( 3428): error creating cache file /data/data/com.test.thalitest/cache/com.android.opengl.shaders_cache: No such file or directory (2)
,D/ActivityThread( 4218): Added TimaKeyStore provider
,W/PackageSettings( 1022): Skipping PackageSetting{346815ec com.example.hello/10168} due to missing metadata
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,I/ActivityManager( 1022): Killing 3428:com.test.thalitest/u0a167 (adj 1): stop com.test.thalitest cause uninstall pkg,
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (7/8)
,I/SurfaceFlinger(  259): id=12 Removed NainActivit (-2/8)
,D/CustomFrequencyManagerService( 1022): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{325ec3ea u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:46990
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1022): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,I/DBG_DM  ( 3507): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,W/ActivityManager( 1022): CustomStartingWindow se packge removed so remove capture also
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4239): MountEmulatedStorage(),
,E/Zygote  ( 4239): v2
I/libpersona( 4239): KNOX_SDCARD checking this for 1000
I/libpersona( 4239): KNOX_SDCARD not a persona
,I/SELinux ( 4239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/art     ( 2708): Explicit concurrent mark sweep GC freed 18540(1024KB) AllocSpace objects, 3(48KB) LOS objects, 50% free, 3MB/7MB, paused 753us total 39.465ms
I/ActivityManager( 1022): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=4239 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 4239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4239): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4239): TimaSignature is unavailable
,D/ActivityThread( 4239): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 625us total 25.550ms
,I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 640us total 16.375ms
,E/SamsungIME( 1895): mOCRHelper is null
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 16.647ms
,W/GeofencerStateMachine( 1839): Ignoring removeGeofence because network location is disabled.
,W/ResourcesManager( 1463): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Gmail   ( 3984): getAccountsCursor
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4257): MountEmulatedStorage()
I/libpersona( 4257): KNOX_SDCARD checking this for 10026
E/Zygote  ( 4257): v2
I/libpersona( 4257): KNOX_SDCARD not a persona
,I/SELinux ( 4257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4257): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4257 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1022): failed to open /acct/uid_10068/pid_1591/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3389/cgroup.procs: No such file or directory
,V/GLSActivity( 1839): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 4257): TimaSignature is unavailable
,D/ActivityThread( 4257): Added TimaKeyStore provider
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1022): mCursor = null
,D/RCPManagerService( 1022): PackageReceiver onReceive()
,I/HarmonyEASService( 1022): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1022): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): removeUidsLocked() for UIDs [10167]
D/NetworkStatsFactory( 1022): UpdateStatsForKnox updated
V/NetworkStats( 1022): performPollLocked(flags=0x3)
D/NetworkStatsFactory( 1022): UpdateStatsForKnox main else ---
,V/NetworkStats( 1022): performPollLocked() took 5ms
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/RegisteredServicesCache( 1456): empty dynamic service
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/EnterpriseDeviceManagerService( 1022): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1022): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1022): no available spell checker services found
,I/Babel   ( 4149): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4149): MmsConfig.loadMmsSettings
I/Babel   ( 4149): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 4149): MmsConfig.loadFromDatabase
,W/ContextImpl( 4239): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4283): MountEmulatedStorage(),
,E/Zygote  ( 4283): v2
,I/libpersona( 4283): KNOX_SDCARD checking this for 1000,
,I/libpersona( 4283): KNOX_SDCARD not a persona,
,I/ActivityManager( 1022): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4283 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4283): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 2755): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/DBG_POLICYDM( 2755): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1022): Receieved: android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 4283): TimaSignature is unavailable
,D/ActivityThread( 4283): Added TimaKeyStore provider
,E/Zygote  ( 4298): MountEmulatedStorage(),
E/Zygote  ( 4298): v2
I/libpersona( 4298): KNOX_SDCARD checking this for 10032
I/libpersona( 4298): KNOX_SDCARD not a persona
,I/ActivityManager( 1022): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4298 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1022): Killing 3462:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,E/Babel   ( 4149): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4149): MmsConfig.loadFromResources
,E/Babel   ( 4149): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4149): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 4283): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 4298): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4298): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4298): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1022): uID is 10167,
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null,
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null,
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1022): uID is 10167
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 4298): TimaSignature is unavailable
,D/SSRM:aZ ( 1022): MSG_TYPE_APP_REMOVED::
D/ActivityThread( 4298): Added TimaKeyStore provider
,W/art     ( 1022): Suspending all threads took: 11.857ms
,W/VideoCapabilities( 4149): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 4149): Unsupported mime audio/evrc
,W/AudioCapabilities( 4149): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4149): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 4149): Unsupported mime audio/mpeg-L2
,W/ContextImpl( 4283): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,W/Settings( 4149): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,W/AudioCapabilities( 4149): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4149): Unsupported mime audio/x-ima
,W/AudioCapabilities( 4149): Unsupported mime audio/qcelp,
,W/AudioCapabilities( 4149): Unsupported mime audio/evrc
,E/Zygote  ( 4315): MountEmulatedStorage(),
I/ActivityManager( 1022): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4315 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 4315): v2,
I/libpersona( 4315): KNOX_SDCARD checking this for 1000
,I/libpersona( 4315): KNOX_SDCARD not a persona,
,I/SELinux ( 4315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/F_PHONE ( 4283): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,W/ContextImpl( 4283): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,E/SELinux ( 4315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CustomFrequencyManagerService( 1022): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1022  tag : ACTIVITY_RESUME_BOOSTER@11
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,D/TaskPersister( 1022): removeObsoleteFile: deleting file=11_task.xml
,D/TaskPersister( 1022): removeObsoleteFile: deleting file=11_task_thumbnail.png
,D/TimaKeyStoreProvider( 4315): TimaSignature is unavailable
,D/ActivityThread( 4315): Added TimaKeyStore provider
,W/VideoCapabilities( 4149): Unsupported mime video/wvc1
,W/VideoCapabilities( 4149): Unsupported mime video/x-ms-wmv
,D/F_PHONE ( 4283): [[com.sec.bcservice]] onServiceConnected()
,I/F_PHONE ( 4283): default registerAction()
I/F_PHONE ( 4283): [[com.sec.bcservice]] sendPendingMessage()
,W/VideoCapabilities( 4149): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/ResourcesManager( 4315): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/VideoCapabilities( 4149): Unsupported mime video/wvc1
,W/VideoCapabilities( 4149): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 4149): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 4149): Unsupported mime video/x-ms-wmv8
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 51902(3MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 25MB/37MB, paused 35.913ms total 529.405ms
,I/art     ( 1022): WaitForGcToComplete blocked for 147.978ms for cause Explicit
,W/VideoCapabilities( 4149): Unsupported mime video/mp43
,W/VideoCapabilities( 4149): Unsupported mime video/sorenson
,W/VideoCapabilities( 4149): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4149): Unsupported profile 4 for video/mp4v-es
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,D/GCMRegistrar( 3551): resetting backoff for com.dropbox.android
,V/GCMRegistrar( 3551): Registering app com.dropbox.android of senders 735665981150
,I/GAV2    ( 3666): Thread[GAThread,5,main]: No campaign data found.
,D/BluetoothBDAdrressReceiver( 4315): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
,W/ContextImpl( 4315): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,I/System.out( 3551): Thread-488(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 3551): Thread-488(ApacheHTTPLog):isShipBuild true
I/System.out( 3551): Thread-488(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3551): Thread-488(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 502 for uid 10088
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 1463): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1463): onCreate()
E/BluetoothBDTestService( 1463): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1463): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1463): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,E/Zygote  ( 4342): MountEmulatedStorage(),
E/Zygote  ( 4342): v2
I/libpersona( 4342): KNOX_SDCARD checking this for 1000,
I/libpersona( 4342): KNOX_SDCARD not a persona
,I/SELinux ( 4342): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1022): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4342 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 4342): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4342): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/Babel   ( 4149): babel boot account: SMS
,V/Babel   ( 4149): babel boot account: thalitester@gmail.com
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1022): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4353 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 4353): MountEmulatedStorage()
I/libpersona( 4353): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4353): v2
I/libpersona( 4353): KNOX_SDCARD not a persona
I/ActivityManager( 1022): Killing 2797:com.google.android.apps.plus/u0a117 (adj 15): empty #31
I/SELinux ( 4353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WallpaperManager( 1499): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
D/WallpaperManager( 1499): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/TimaKeyStoreProvider( 4353): TimaSignature is unavailable
,D/ActivityThread( 4353): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4342): TimaSignature is unavailable
,D/ActivityThread( 4342): Added TimaKeyStore provider
,W/ResourceType( 1022): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/AlarmManager( 1022): waitForAlarm result :4
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1839): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,W/ResourcesManager( 4342): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3507): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 11866(797KB) AllocSpace objects, 3(962KB) LOS objects, 33% free, 23MB/35MB, paused 3.234ms total 313.499ms
,I/art     ( 1022): WaitForGcToComplete blocked for 398.819ms for cause HeapTrim
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1022): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/art     ( 4149): Suspending all threads took: 55.016ms
,E/SPPClientService( 4298): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4298): [PushClientApplication] Push log off : This is Ship build version
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,V/AlarmManager( 1022): waitForAlarm result :4
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageManager( 1022): delete codoeFile: 
,E/SPPClientService( 4298): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/AASAuninstall( 1022): userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
,D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
,D/SPPClientService( 4298): PushLog.txt file is not deleted.
,D/SPPClientService( 4298): PushLog.txt file is not deleted.
,D/SPPClientService( 4298): ============PushLog. stop!
,I/KnoxUsageLogPro( 4342): KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,I/KnoxUsageLogPro( 4342): savePreference: key = previous_sys_time value = 1457959161988
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KnoxUsageLogPro( 4342): premStatus:2
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/KnoxUsageLogPro( 4342): isEulaShown : false,
I/KnoxUsageLogPro( 4342): KnoxUsageReceiver onReceive : not Processible, just return
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1022): Killing 2893:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1022): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1022): onPackageRemoved : com.test.thalitest
,I/AASA_removePackage( 1022): UID=10167 Target=com.test.thalitest
,D/PackageManager( 1022): result of delete: 1{917886255}
,D/Finsky  ( 4257): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/AndroidRuntime( 4181): Shutting down VM
,D/PackageManager( 1022): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 1022): userId{-1}
D/PackageManager( 1022): andCode{true}
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4389): MountEmulatedStorage()
I/libpersona( 4389): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4389): v2
I/libpersona( 4389): KNOX_SDCARD not a persona
,I/SELinux ( 4389): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/System.out( 1839): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/ActivityManager( 1022): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4389 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/System.out( 1839): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1839): (HTTPLog)-Static: isShipBuild true
I/System.out( 1839): (HTTPLog)-Thread-242-28965938: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1839): (HTTPLog)-Static: isSBSettingEnabled false
I/SELinux ( 4389): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4389): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/EnterpriseController(  281): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  281): getNetworkForDns: using netid 502 for uid 10011
,I/KnoxUsageLogPro( 4342): savePreference: key = previous_elapsed_time value = 48156
,I/ActivityManager( 1022): Killing 3518:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4389): TimaSignature is unavailable,
D/ActivityThread( 4389): Added TimaKeyStore provider
,E/Zygote  ( 4409): MountEmulatedStorage()
I/libpersona( 4409): KNOX_SDCARD checking this for 10036
E/Zygote  ( 4409): v2
I/libpersona( 4409): KNOX_SDCARD not a persona
,I/SELinux ( 4409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4409): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4409 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1022): Killing 3447:com.google.android.configupdater/u0a82 (adj 15): empty #31
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4424): MountEmulatedStorage()
I/libpersona( 4424): KNOX_SDCARD checking this for 10003
E/Zygote  ( 4424): v2
I/libpersona( 4424): KNOX_SDCARD not a persona
,I/SELinux ( 4424): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 4409): TimaSignature is unavailable
,D/ActivityThread( 4409): Added TimaKeyStore provider
,I/ActivityManager( 1022): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4424 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
I/System.out( 1839): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/SELinux ( 4424): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4424): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4424): TimaSignature is unavailable
,D/ActivityThread( 4424): Added TimaKeyStore provider
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3462/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_10117/pid_2797/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_2893/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10146/pid_3518/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10082/pid_3447/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 4239): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4239): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4239): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 4239): Resource data:2131165186
,E/KnoxSetupWizardClient( 4389): isShipMode : 1
,I/ActivityManager( 1022): Waited long enough for: ServiceRecord{267cd9e3 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
I/KnoxSetupWizardClient( 4389): onReceive : android.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 4239): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4239): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4239): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/ActivityManager( 1022): Killing 3551:com.dropbox.android/u0a88 (adj 15): empty #31
,W/ResourcesManager( 4239): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 4239): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
I/AMMetaDataParserService( 4239): getResourceTypeNamexml
,I/AMMetaDataParserService( 4239): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,W/art     ( 4181): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/ShortcutReceiver( 4389):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 4239): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,W/System.err( 4389): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,D/KnoxShortcutUtil( 4389): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4389):  KnoxContainerVersion 2.3.0
D/ShortcutReceiver( 4389):  shortcut migration not required 
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/SA      ( 4409): [SSP] onCreated
,E/Zygote  ( 4455): MountEmulatedStorage(),
E/Zygote  ( 4455): v2
I/libpersona( 4455): KNOX_SDCARD checking this for 1000
I/libpersona( 4455): KNOX_SDCARD not a persona
,I/SELinux ( 4455): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4455): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 4455): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4455 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1022): Killing 3572:com.fmm.dm/1000 (adj 15): empty #31
,W/libprocessgroup( 1022): failed to open /acct/uid_10088/pid_3551/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4455): TimaSignature is unavailable
,D/ActivityThread( 4455): Added TimaKeyStore provider
,W/System.err( 4389): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4389): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4389): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 4389): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 4389): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4389): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusChecker( 4455): onReceive : android.intent.action.BOOT_COMPLETED
,I/SA      ( 4409): [TPM] There is no property file
,I/SA      ( 4409): [SCU] isHaveSA() - false
,I/SA      ( 4409): [TPM] getModelProperty : null
,I/SA      ( 4409): [TPM] getCSCProperty : null
,I/SA      ( 4409): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4409): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4409): [DM] TFT FEATURE: false
,I/StatusChecker( 4455): onReceive : net.mt.init : DONE
,I/SA      ( 4409): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4409): [DM] init START
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3572/cgroup.procs: No such file or directory
,I/SA      ( 4409): [DM] This device is not a Vodafone
,E/Zygote  ( 4476): MountEmulatedStorage()
,E/Zygote  ( 4476): v2
I/libpersona( 4476): KNOX_SDCARD checking this for 10113
I/libpersona( 4476): KNOX_SDCARD not a persona
,I/SELinux ( 4476): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1022): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4476 uid=10113 gids={50113, 9997} abi=armeabi-v7a
,I/ActivityManager( 1022): Killing 3608:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,I/SELinux ( 4476): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4476): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 4239): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,I/art     (  309): Explicit concurrent mark sweep GC freed 8747(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 2.658ms total 22.191ms,
D/SSRM:n  ( 1022): SIOP:: AP = 410
,I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCr,eateAccountActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
W/ResourceType( 4409): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
D/TimaKeyStoreProvider( 4476): TimaSignature is unavailable
W/ResourceType( 4409): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 4409): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
D/ActivityThread( 4476): Added TimaKeyStore provider
W/ResourceType( 4409): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 17.252ms
W/ResourceType( 4409): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4409): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ResourceType( 4409): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
W/ContextImpl( 4239): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
W/libprocessgroup( 1022): failed to open /acct/uid_10088/pid_3608/cgroup.procs: No such file or directory
I/SA      ( 4409): [SCU] isHaveSA() - false
I/SA      ( 4409): support phone number id : false
I/SA      ( 4409): [DM] Supports Ref Jpn : true
I/SA      ( 4409): [DM] init END
I/SA      ( 4409): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 643us total 16.868ms
I/SA      ( 4409): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
I/SA      ( 4409): [OR] onReceive END
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/PageBuddyNotiSvc( 4476): Intent received : action=android.intent.action.BOOT_COMPLETED
E/Zygote  ( 4493): MountEmulatedStorage()
I/libpersona( 4493): KNOX_SDCARD checking this for 10037
E/Zygote  ( 4493): v2
I/libpersona( 4493): KNOX_SDCARD not a persona
I/SELinux ( 4493): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/AMMetaDataParserService( 4239): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 4239): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4239): getResourcePackageName:assistant
I/AMMetaDataParserService( 4239): Resource data:2131034113
I/SELinux ( 4493): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4493): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4493 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 4476): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
W/ResourcesManager( 4239): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4239): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4239): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
I/AMMetaDataParserService( 4239): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 4239): getResourceTypeNamexml
I/PageBuddyNotiSvc( 4476): onCreate mCpBitFlag=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4493): TimaSignature is unavailable
D/ActivityThread( 4493): Added TimaKeyStore provider
,E/        ( 4239): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SA      ( 4409): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4409): [ODM] queryOpenData(key= GEO_IP )
,D/Finsky  ( 4257): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/GFX construct_block_size_descriptor_2d second part( 4239): took 4.164586ms for 0*0 texture 0
,E/Zygote  ( 4510): MountEmulatedStorage()
,E/Zygote  ( 4510): v2
I/libpersona( 4510): KNOX_SDCARD checking this for 10121
,I/libpersona( 4510): KNOX_SDCARD not a persona
,I/SA      ( 4409): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4409): [LBE] REF_JPN : true
I/SA      ( 4409): [BDC] create
I/GFX generate_partition_tables( 4239): took 6.130938ms for 0*0 texture 0
,I/SELinux ( 4510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1022): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4510 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 4510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/GFX raster( 4239): took 15.438804ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4239): Bitmap=0xb88a1460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88a1058 counterpartCT=4 counterpartW=96 counterparth=96
E/SELinux ( 4510): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SettingsProvider( 1022): name = audio_safe_volume_state
,E/Watchdog( 1022): !@Sync 1
,I/AMMetaDataParserService( 4239): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,E/        ( 4239): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/TimaKeyStoreProvider( 4510): TimaSignature is unavailable
,D/ActivityThread( 4510): Added TimaKeyStore provider
,I/GFX raster( 4239): took 0.862135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4239): Bitmap=0xb88a1460 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8c57c20 counterpartCT=4 counterpartW=96 counterparth=96
I/SA      ( 4409): [DBMV2] getEmailID
,I/SA      ( 4409): [DBMV2] getDataV02ForItems
I/SA      ( 4409): [SSP] query invoked
,W/ResourcesManager( 4510): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4510): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4510): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 4493): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 4239): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/Settings( 4257): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4257): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SA      ( 4409): [SCU] get signed id from samsung account2.0 DB.,
,D/QuickConnect( 4510): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,I/SA      ( 4409): [SCU] get signed id from samsung account1.0 DB.
,D/SettingsProvider( 1022): name = scon_is_running
D/SettingsProvider( 1022): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1022): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1022): selectionArgs: false
D/SettingsProvider( 1022): selectionArgs: 10121
D/SecContentProvider( 1022): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1022): ret = -1
,I/SA      ( 4409): [BDC] destroy
,I/ActivityManager( 1022): Killing 3630:com.fmm.ds/1000 (adj 15): empty #31
,W/BackupManagerService( 1022): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 4510): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 4510): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/QuickConnect( 4510): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/CalendarProvider2( 4493): CalendarProvider2.onCreate() called
,E/Zygote  ( 4527): MountEmulatedStorage()
,E/Zygote  ( 4527): v2
I/libpersona( 4527): KNOX_SDCARD checking this for 10127
I/libpersona( 4527): KNOX_SDCARD not a persona
,I/SELinux ( 4527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1022): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4527 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 4527): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Killing 2940:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4527): TimaSignature is unavailable
,D/ActivityThread( 4527): Added TimaKeyStore provider
,D/Volley  ( 4257): [621] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4257): [628] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 4257): Skipping gmscore version check
,I/ActivityManager( 1022): Killing 3771:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,I/ActivityManager( 1022): Killing 3689:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #32
,W/ResourcesManager( 4527): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4527): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4527): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4527): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3630/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10020/pid_3771/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10013/pid_3689/cgroup.procs: No such file or directory
W/libprocessgroup( 1022): failed to open /acct/uid_10008/pid_2940/cgroup.procs: No such file or directory
,D/Finsky  ( 4257): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4257): [1] Libraries$2.run: Finished loading 1 libraries.
,I/DBG_DM  ( 3507): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,D/Finsky  ( 4257): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/SBrowserFeatureFlag( 4527): initialized in static block : loadCscFeatureValue() succeed! 
,D/ManifestProvider( 4527): onCreate()
,E/NetworkSettingsReceiver( 4527): onReceive: android.intent.action.BOOT_COMPLETED
,E/SMD     (  291): DCD OFF
,W/System.err( 4527): java.lang.NoSuchMethodException: isEnabled []
,W/System.err( 4527): 	at java.lang.Class.getMethod(Class.java:665)
,W/System.err( 4527): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
,W/System.err( 4527): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
,W/System.err( 4527): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
W/System.err( 4527): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4527): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
,W/System.err( 4527): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
,W/System.err( 4527): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
,W/System.err( 4527): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
,W/System.err( 4527): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4527): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4527): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4527): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4527): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4527): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4527): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4527): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 4527): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@2ddfedae
,D/SBrowserFeatureFlag( 4527): initialize : initSupportedPkg() succeed! 
,I/VerificationLog( 4527): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4551): MountEmulatedStorage(),
E/Zygote  ( 4551): v2
,I/libpersona( 4551): KNOX_SDCARD checking this for 10131
I/ActivityManager( 1022): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4551 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/libpersona( 4551): KNOX_SDCARD not a persona
,I/SELinux ( 4551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4551): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4551): TimaSignature is unavailable
,D/ActivityThread( 4551): Added TimaKeyStore provider
,W/ResourcesManager( 4551): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4551): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4551): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/        ( 4239): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,V/AlarmManager( 1022): waitForAlarm result :8
,I/GFX construct_block_size_descriptor_2d second part( 4239): took 3.003855ms for 0*0 texture 0
,I/GFX generate_partition_tables( 4239): took 7.471351ms for 0*0 texture 0
,I/GFX raster( 4239): took 11.496716ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4239): Bitmap=0xb8c57120 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c56680 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 4239): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/daemonapp( 1816): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/Finsky  ( 4257): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager( 1022): Killing 3835:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 4239): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4239): took 0.622083ms for 96*96 texture 0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4239): Bitmap=0xb8c57c20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c3a748 counterpartCT=4 counterpartW=96 counterparth=96
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 2108): updateResources: need to parse f{com.google.android.gms}
,I/AMMetaDataParserService( 4239): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 4239): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 4239): took 0.869584ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4239): Bitmap=0xb8c56680 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c3a748 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4579): MountEmulatedStorage()
I/libpersona( 4579): KNOX_SDCARD checking this for 10135,
E/Zygote  ( 4579): v2
I/libpersona( 4579): KNOX_SDCARD not a persona
I/SELinux ( 4579): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4579 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/AMMetaDataParserService( 4239): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532,
,I/SELinux ( 4579): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4579): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_3835/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 4579): TimaSignature is unavailable
,D/ActivityThread( 4579): Added TimaKeyStore provider
,E/SQLiteLog( 2108): (10) unixWrite() File Descriptor : 101 gets errno : 9
,E/SQLiteLog( 4239): (10) unixWrite() File Descriptor : 37 gets errno : 9
,E/SQLiteDatabase( 4239): Error inserting actname=com.android.contacts.activities.PeopleActivity amicon=[B@b4a170c appname=com.android.contacts id=1457959163354 amtitle=Keypad amstate=1 amintent=android.intent.assistant.main.keypad amlabel=2131690637
E/SQLiteDatabase( 4239): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 4239): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:77)
E/SQLiteDatabase( 4239): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 4239): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 4239): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4239): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4239): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4239): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ResourcesManager( 4579): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4579): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4579): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4579): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4579): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/FileUtils( 2108): Failed to chmod(/data/data/com.google.android.gms/shared_prefs/gms_sync_prefs_sync:CredentialSyncAdapter.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/        ( 4239): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 4239): took 0.675365ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 4239): Bitmap=0xb8c3a748 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88a19d8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/AMMetaDataParserService( 4239): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
E/SQLiteLog( 4239): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 4239): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 4239): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 4239): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 4239): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4239): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
E/SQLiteDatabase( 4239): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
E/SQLiteDatabase( 4239): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
E/SQLiteDatabase( 4239): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4239): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4239): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4239): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 4239): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 4239): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 4239): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 4239): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 4239): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 4239): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 4239): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 4239): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 4239): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 4239): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 4239): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 4239): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
W/System.err( 4239): ,	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
W/System.err( 4239): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
W/System.err( 4239): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 4239): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4239): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4239): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SharedPreferencesImpl( 2108): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,I/GCore-Chimera-Crash( 2108): Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
,I/GCore-Chimera-Crash( 2108): 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM0KRjS36UR
I/GCore-Chimera-Crash( 2108): IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
I/GCore-Chimera-Crash( 2108): ==
I/GCore-Chimera-Crash( 2108): GCore-Chimera-Crash
,I/ActivityManager( 1022): Killing 3797:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,E/SharedPreferencesImpl( 2108): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/SharedPreferencesImpl( 2108): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/AndroidRuntime( 2108): FATAL EXCEPTION: SyncAdapterThread-1
E/AndroidRuntime( 2108): Process: com.google.android.gms, PID: 2108
E/AndroidRuntime( 2108): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 2108): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2108): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 2108): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 2108): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 2108): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
E/AndroidRuntime( 2108): 	at com.google.android.gms.auth.api.credentials.be.persistence.e.a(:com.google.android.gms:73)
E/AndroidRuntime( 2108): 	at com.google.android.gms.auth.api.credentials.be.persistence.af.a(:com.google.android.gms:187)
E/AndroidRuntime( 2108): 	at com.google.android.gms.auth.api.credentials.sync.b.a(:com.google.android.gms:137)
E/AndroidRuntime( 2108): 	at com.google.android.gms.auth.api.credentials.sync.a.a(:com.google.android.gms:137)
E/AndroidRuntime( 2108): 	at com.google.android.gms.common.m.a.onPerformSync(:com.google.android.gms:98)
E/AndroidRuntime( 2108): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,E/SharedPreferencesImpl( 2108): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/DropBoxManagerService( 1022): Can't write: system_app_crash
E/DropBoxManagerService( 1022): java.io.FileNotFoundException: /data/system/dropbox/drop170.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1022): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1022): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1022): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1022): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1022): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1022): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1022): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1022): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1022): 	... 5 more
,E/SharedPreferencesImpl( 2108): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/SharedPreferencesImpl( 2108): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,E/SharedPreferencesImpl( 2108): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,E/SharedPreferencesImpl( 2108): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,E/SharedPreferencesImpl( 2108): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,E/SharedPreferencesImpl( 2108): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,E/SharedPreferencesImpl( 2108): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
,D/PhoneWindow( 1022): *FMB* installDecor mIsFloating : true
,D/PhoneWindow( 1022): *FMB* installDecor flags : 8519682
,D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1022): Focus left window: 1499
D/InputDispatcher( 1022): Focus entered window: 1022
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,W/libprocessgroup( 1022): failed to open /acct/uid_10090/pid_3797/cgroup.procs: No such file or directory
,D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled return false
,I/ActivityManager( 1022): Killing 3597:com.sec.pcw.device/1000 (adj 15): empty #31
,I/ActivityManager( 1022): Killing 3720:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/SurfaceFlinger(  259): id=14 createSurf (73x73),1 flag=4, hms

```
